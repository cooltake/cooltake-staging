---
layout: post
title: "定番コード進行8選を聴き比べ — 王道進行・カノン進行・小室進行を無料ツールで試す"
description: "王道進行・カノン進行・小室進行・丸サ進行など、J-POPで多用される定番コード進行8種類をブラウザで再生しながら聴き比べできる無料ツールを公開。キー変更・音色切り替えにも対応。"
date: 2026-07-04
categories: [production]
tags: [コード進行, 作曲, DTM, 音楽理論, 王道進行, カノン進行]
image: /assets/images/thumb-chord-progression-tool.jpg
---

## コード進行は「聴いて覚える」のが一番早い

作曲やアレンジをしていると必ず出会うのが「定番コード進行」です。王道進行・カノン進行・小室進行などは名前を知っていても、実際にどんな響きなのかをすぐに鳴らして確認できる場面は意外と少ないものです。

このツールは、J-POPやボカロ曲で頻出する8種類のコード進行を、キーを変えながらその場で再生して聴き比べられる無料ツールです。メトロノーム機能も内蔵しているので、作曲中のテンポ確認・拍子感の練習にもそのまま使えます。

## 使い方

1. **BPM（テンポ）** をスライダーで設定
2. **拍子**（2/4・3/4・4/4・6/8）を選択
3. **コード進行を鳴らす** にチェックを入れる
4. **進行パターン**・**キー**・**音色**（ピアノ／オルガン／ストリングス）を選んで「開始」

<div id="chordToolMount"></div>

<style>
#chordToolMount { font-family: inherit; }
.ctp-card { background:#12141c; border:1px solid #2a2d3a; border-radius:14px; padding:22px 24px; margin:24px 0; color:#e8e8ef; }
.ctp-row { margin-bottom:14px; }
.ctp-row label { display:block; font-size:.8rem; font-weight:700; margin-bottom:6px; color:#a8acc0; }
.ctp-row select, .ctp-row input[type=range] { width:100%; }
.ctp-pair { display:grid; grid-template-columns:1fr 1fr; gap:12px; }
.ctp-select { width:100%; padding:9px 10px; border-radius:8px; border:1px solid #383c4d; background:#1c1f2b; color:#e8e8ef; font-size:.88rem; }
.ctp-btn { width:100%; padding:12px; border:none; border-radius:10px; background:#5b6ee8; color:#fff; font-weight:700; font-size:.95rem; cursor:pointer; margin-top:6px; }
.ctp-btn:hover { background:#4757d1; }
.ctp-dots { display:flex; gap:6px; justify-content:center; margin-top:12px; }
.ctp-dot { width:14px; height:14px; border-radius:50%; background:#383c4d; transition:background .1s; }
.ctp-chord-display { background:#1c1f2b; border-radius:10px; padding:14px; margin-top:10px; text-align:center; font-size:1.2rem; font-weight:900; color:#8b9bff; min-height:36px; }
.ctp-bpmnum { text-align:right; font-weight:900; font-size:1.15rem; color:#8b9bff; }
</style>

<div class="ctp-card">
  <div class="ctp-row">
    <label>テンポ（BPM）</label>
    <div style="display:flex;align-items:center;gap:10px;">
      <input id="ctpBpm" type="range" min="40" max="240" value="120" oninput="ctpSlide()" style="flex:1;">
      <div class="ctp-bpmnum" style="width:56px;"><span id="ctpBpmNum">120</span></div>
    </div>
  </div>
  <div class="ctp-pair">
    <div class="ctp-row">
      <label>拍子</label>
      <select id="ctpBeats" class="ctp-select" onchange="ctpApplyIfPlaying()">
        <option value="2">2拍子（2/4）</option>
        <option value="3">3拍子（3/4）</option>
        <option value="4" selected>4拍子（4/4）</option>
        <option value="6">6拍子（6/8）</option>
      </select>
    </div>
    <div class="ctp-row">
      <label>音色</label>
      <select id="ctpTimbre" class="ctp-select" onchange="ctpApplyIfPlaying()">
        <option value="piano">ピアノ</option>
        <option value="organ">オルガン</option>
        <option value="strings">ストリングス</option>
      </select>
    </div>
  </div>

  <button class="ctp-btn" id="ctpStartBtn" onclick="ctpToggle()">▶ 再生開始</button>
  <div class="ctp-dots" id="ctpBeatDots"></div>

  <div style="border-top:1px solid #2a2d3a;margin:18px 0 14px;padding-top:14px;">
    <div style="font-size:.85rem;font-weight:900;margin-bottom:10px;color:#e8e8ef;">🎹 コード進行</div>
    <div class="ctp-row">
      <label>進行パターン</label>
      <select id="ctpProgression" class="ctp-select" onchange="ctpApplyIfPlaying()">
        <option value="oudou">王道進行（Ⅳ-Ⅴ-Ⅲm-Ⅵm）</option>
        <option value="canon">カノン進行（I-V-VIm-IIIm-IV-I-IV-V）</option>
        <option value="komuro">小室進行（Ⅵm-Ⅳ-Ⅰ-Ⅴ）</option>
        <option value="marusa">丸サ進行（I-VIm-IIm-V）</option>
        <option value="junkan">循環コード（Ⅰ-Ⅵm-Ⅳ-Ⅴ）</option>
        <option value="blues">ブルース進行（Ⅰ-Ⅳ-Ⅴ）</option>
        <option value="setsunai">切ない系進行（VIm-IV-V-VIm）</option>
        <option value="cliche">クリシェ進行（I-I/VII-I7/♭VII-VIm）</option>
      </select>
    </div>
    <div class="ctp-pair">
      <div class="ctp-row">
        <label>キー</label>
        <div style="display:flex;gap:6px;">
          <select id="ctpKeyRoot" class="ctp-select" onchange="ctpApplyIfPlaying()">
            <option>C</option><option>C#</option><option>D</option><option>D#</option>
            <option>E</option><option>F</option><option>F#</option><option>G</option>
            <option>G#</option><option>A</option><option>A#</option><option>B</option>
          </select>
          <select id="ctpKeyMode" class="ctp-select" onchange="ctpApplyIfPlaying()">
            <option value="major">Major</option>
            <option value="minor">Minor</option>
          </select>
        </div>
      </div>
      <div class="ctp-row">
        <label>拍の長さ（1コードの保持）</label>
        <select id="ctpChordDur" class="ctp-select" onchange="ctpApplyIfPlaying()">
          <option value="whole">全音符（1小節）</option>
          <option value="quarter" selected>4分音符</option>
          <option value="eighth">8分音符</option>
        </select>
      </div>
    </div>
    <div class="ctp-row" style="display:flex;align-items:center;gap:8px;">
      <label style="margin:0;display:flex;align-items:center;gap:6px;font-size:.82rem;color:#e8e8ef;">
        <input type="checkbox" id="ctpChordsOn" onchange="ctpApplyIfPlaying()"> コード進行を再生に含める
      </label>
    </div>
    <div class="ctp-chord-display" id="ctpChordDisplay">—</div>
  </div>
</div>

<script>
(function () {
  'use strict';
  const NOTE_NAMES = ['C','C#','D','D#','E','F','F#','G','G#','A','A#','B'];
  const DEGREE_MAJOR = { I:0, II:2, III:4, IV:5, V:7, VI:9, VII:11 };
  const DEGREE_MINOR = { I:0, II:2, IIIb:3, III:3, IV:5, V:7, VIb:8, VI:8, VIIb:10, VII:10 };

  const PROGRESSIONS = {
    oudou:    { chords:[{deg:'IV',q:''},{deg:'V',q:''},{deg:'III',q:'m'},{deg:'VI',q:'m'}] },
    canon:    { chords:[{deg:'I',q:''},{deg:'V',q:''},{deg:'VI',q:'m'},{deg:'III',q:'m'},{deg:'IV',q:''},{deg:'I',q:''},{deg:'IV',q:''},{deg:'V',q:''}] },
    komuro:   { chords:[{deg:'VI',q:'m'},{deg:'IV',q:''},{deg:'I',q:''},{deg:'V',q:''}] },
    marusa:   { chords:[{deg:'I',q:''},{deg:'VI',q:'m'},{deg:'II',q:'m'},{deg:'V',q:''}] },
    junkan:   { chords:[{deg:'I',q:''},{deg:'VI',q:'m'},{deg:'IV',q:''},{deg:'V',q:''}] },
    blues:    { chords:[{deg:'I',q:'7'},{deg:'IV',q:'7'},{deg:'V',q:'7'}] },
    setsunai: { chords:[{deg:'VI',q:'m'},{deg:'IV',q:''},{deg:'V',q:''},{deg:'VI',q:'m'}] },
    cliche:   { chords:[
                  { deg:'I', q:'' , bassDeg:'I' },
                  { deg:'I', q:'' , bassDeg:'VII', bassLowered:true },
                  { deg:'I', q:'7', bassDeg:'VII', bassLowered:true },
                  { deg:'VI', q:'m', bassDeg:'VI' },
                ] },
  };
  const QUALITY_INTERVALS = { '':[0,4,7], 'm':[0,3,7], '7':[0,4,7,10] };

  function noteNameToMidiBase(name) { return NOTE_NAMES.indexOf(name); }
  function buildChordNotes(chordDef, keyRootSemitone, isMinorKey) {
    const scaleMap = isMinorKey ? DEGREE_MINOR : DEGREE_MAJOR;
    const rootOffset = scaleMap[chordDef.deg];
    const intervals = QUALITY_INTERVALS[chordDef.q] || QUALITY_INTERVALS[''];
    const rootAbs = keyRootSemitone + rootOffset;
    let notes = intervals.map(iv => rootAbs + iv);
    if (chordDef.bassDeg) {
      let bassOffset = scaleMap[chordDef.bassDeg];
      if (chordDef.bassLowered) bassOffset -= 1;
      const bassAbs = keyRootSemitone + bassOffset;
      notes = [bassAbs - 12, ...notes.filter(n => (n % 12 + 12) % 12 !== (bassAbs % 12 + 12) % 12)];
    }
    return notes;
  }
  function semitoneToFreq(semitoneFromC4) {
    const midi = 60 + semitoneFromC4;
    return 440 * Math.pow(2, (midi - 69) / 12);
  }

  function ChordMetronomeEngine() {
    this.ctx = null; this.isPlaying = false; this.timerId = null;
    this.beatCount = 0; this.chordIndex = 0;
    this.onBeat = null; this.onChordChange = null;
  }
  ChordMetronomeEngine.prototype._ensureCtx = function () {
    if (!this.ctx) this.ctx = new (window.AudioContext || window.webkitAudioContext)();
    if (this.ctx.state === 'suspended') this.ctx.resume();
    return this.ctx;
  };
  ChordMetronomeEngine.prototype.playClick = function (accent) {
    const ctx = this._ensureCtx();
    const osc = ctx.createOscillator(); const gain = ctx.createGain();
    osc.type = 'square'; osc.frequency.value = accent ? 1500 : 1000;
    gain.gain.setValueAtTime(accent ? 0.35 : 0.2, ctx.currentTime);
    gain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + 0.05);
    osc.connect(gain).connect(ctx.destination);
    osc.start(); osc.stop(ctx.currentTime + 0.06);
  };
  ChordMetronomeEngine.prototype.playChordNotes = function (semitones, durationSec, timbre) {
    const ctx = this._ensureCtx(); const now = ctx.currentTime;
    semitones.forEach(st => this._playVoice(semitoneToFreq(st), now, durationSec, timbre || 'piano'));
  };
  ChordMetronomeEngine.prototype._playVoice = function (freq, startTime, duration, timbre) {
    const ctx = this.ctx;
    const master = ctx.createGain();
    master.connect(ctx.destination);
    if (timbre === 'organ') {
      const partials = [1,2,3,4]; const gains = [0.5,0.22,0.12,0.08];
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.5, startTime + 0.03);
      master.gain.setValueAtTime(0.5, startTime + Math.max(0.03, duration - 0.08));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration);
      partials.forEach((p, i) => {
        const osc = ctx.createOscillator(); const g = ctx.createGain();
        osc.type = 'sine'; osc.frequency.value = freq * p; g.gain.value = gains[i];
        osc.connect(g).connect(master);
        osc.start(startTime); osc.stop(startTime + duration + 0.05);
      });
    } else if (timbre === 'strings') {
      const osc1 = ctx.createOscillator(); const osc2 = ctx.createOscillator();
      osc1.type = 'sawtooth'; osc2.type = 'sawtooth';
      osc1.frequency.value = freq; osc2.frequency.value = freq * 1.005;
      const filter = ctx.createBiquadFilter();
      filter.type = 'lowpass'; filter.frequency.value = 2200;
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.28, startTime + 0.25);
      master.gain.setValueAtTime(0.28, startTime + Math.max(0.25, duration - 0.3));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration + 0.2);
      osc1.connect(filter); osc2.connect(filter); filter.connect(master);
      osc1.start(startTime); osc2.start(startTime);
      osc1.stop(startTime + duration + 0.3); osc2.stop(startTime + duration + 0.3);
    } else {
      const osc = ctx.createOscillator(); const osc2 = ctx.createOscillator();
      osc.type = 'triangle'; osc2.type = 'sine';
      osc.frequency.value = freq; osc2.frequency.value = freq * 2.001;
      const g2 = ctx.createGain(); g2.gain.value = 0.15;
      master.gain.setValueAtTime(0.45, startTime);
      master.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
      osc.connect(master); osc2.connect(g2).connect(master);
      osc.start(startTime); osc2.start(startTime);
      osc.stop(startTime + duration + 0.05); osc2.stop(startTime + duration + 0.05);
    }
  };
  ChordMetronomeEngine.prototype.stop = function () {
    this.isPlaying = false;
    if (this.timerId) { clearTimeout(this.timerId); this.timerId = null; }
    this.beatCount = 0; this.chordIndex = 0;
  };
  ChordMetronomeEngine.prototype.start = function (options) {
    this.stop(); this._ensureCtx(); this.isPlaying = true;
    const beatsPerBar = options.beatsPerBar || 4;
    const bpm = options.bpm || 120;
    const beatDurSec = 60 / bpm;
    const progression = PROGRESSIONS[options.progressionKey] || PROGRESSIONS.oudou;
    const keyRootSemitone = noteNameToMidiBase(options.keyRoot || 'C');
    const isMinorKey = options.keyMode === 'minor';
    const chordBeatMap = { whole: beatsPerBar, quarter: 1, eighth: 0.5 };
    const chordBeats = chordBeatMap[options.chordDuration] || beatsPerBar;
    this.beatCount = 0; this.chordIndex = 0;
    let beatsIntoChord = 0;
    const self = this;
    function tick() {
      if (!self.isPlaying) return;
      const beatInBar = self.beatCount % beatsPerBar;
      const isAccent = beatInBar === 0;
      if (options.metronomeOn !== false) self.playClick(isAccent);
      if (typeof self.onBeat === 'function') self.onBeat(beatInBar, beatsPerBar);
      if (options.chordsOn && beatsIntoChord === 0) {
        const chordDef = progression.chords[self.chordIndex % progression.chords.length];
        const notes = buildChordNotes(chordDef, keyRootSemitone, isMinorKey);
        const durSec = chordBeats * beatDurSec * 0.92;
        self.playChordNotes(notes, durSec, options.timbre);
        if (typeof self.onChordChange === 'function') self.onChordChange(self.chordIndex % progression.chords.length, chordDef);
      }
      self.beatCount++;
      beatsIntoChord = (beatsIntoChord + 1) % chordBeats;
      if (beatsIntoChord === 0 && options.chordsOn) self.chordIndex++;
      self.timerId = setTimeout(tick, beatDurSec * 1000);
    }
    tick();
  };

  let ctpEngine = null;
  window.ctpSlide = function () {
    document.getElementById('ctpBpmNum').textContent = document.getElementById('ctpBpm').value;
    window.ctpApplyIfPlaying();
  };
  function ctpGetOptions() {
    return {
      bpm: parseInt(document.getElementById('ctpBpm').value, 10),
      beatsPerBar: parseInt(document.getElementById('ctpBeats').value, 10),
      timbre: document.getElementById('ctpTimbre').value,
      progressionKey: document.getElementById('ctpProgression').value,
      keyRoot: document.getElementById('ctpKeyRoot').value,
      keyMode: document.getElementById('ctpKeyMode').value,
      chordDuration: document.getElementById('ctpChordDur').value,
      chordsOn: document.getElementById('ctpChordsOn').checked,
      metronomeOn: true,
    };
  }
  function ctpBuildDots() {
    const beats = parseInt(document.getElementById('ctpBeats').value, 10);
    const wrap = document.getElementById('ctpBeatDots');
    wrap.innerHTML = Array.from({length: beats}, (_, i) => `<div class="ctp-dot" data-i="${i}"></div>`).join('');
  }
  window.ctpToggle = function () {
    const btn = document.getElementById('ctpStartBtn');
    if (!ctpEngine) ctpEngine = new ChordMetronomeEngine();
    if (ctpEngine.isPlaying) {
      ctpEngine.stop();
      btn.textContent = '▶ 再生開始';
      document.querySelectorAll('.ctp-dot').forEach(d => d.style.background = '#383c4d');
    } else {
      ctpBuildDots();
      ctpEngine.onBeat = (beatInBar) => {
        document.querySelectorAll('.ctp-dot').forEach((d, i) => {
          d.style.background = i === beatInBar ? '#8b9bff' : '#383c4d';
        });
      };
      ctpEngine.onChordChange = (idx, chordDef) => {
        const disp = document.getElementById('ctpChordDisplay');
        if (disp) disp.textContent = chordDef.deg + (chordDef.q === 'm' ? 'm' : chordDef.q === '7' ? '7' : '');
      };
      ctpEngine.start(ctpGetOptions());
      btn.textContent = '■ 停止';
    }
  };
  window.ctpApplyIfPlaying = function () {
    if (ctpEngine && ctpEngine.isPlaying) ctpEngine.start(ctpGetOptions());
    ctpBuildDots();
  };
  ctpBuildDots();
})();
</script>

## 8種類のコード進行の特徴

| 進行名 | コード（度数） | 印象 |
|---|---|---|
| 王道進行 | Ⅳ-Ⅴ-Ⅲm-Ⅵm | J-POPで最頻出。切なさと高揚感の両立 |
| カノン進行 | I-V-VIm-IIIm-IV-I-IV-V | パッヘルベルのカノン由来。壮大で安定感がある |
| 小室進行 | Ⅵm-Ⅳ-Ⅰ-Ⅴ | 90年代J-POPの定番。疾走感がある |
| 丸サ進行 | I-VIm-IIm-V | シティポップ・ボカロ曲で人気。おしゃれな響き |
| 循環コード | Ⅰ-Ⅵm-Ⅳ-Ⅴ | 最も基本的な循環。汎用性が高い |
| ブルース進行 | Ⅰ-Ⅳ-Ⅴ（セブンス） | ロック・ブルースの土台 |
| 切ない系進行 | VIm-IV-V-VIm | マイナー始まりでエモーショナルな展開 |
| クリシェ進行 | I-I/VII-I7/♭VII-VIm | ベース音が半音ずつ下がる。ドラマチックな伴奏に最適 |

キーを変えながら聴き比べると、同じ進行でも曲の雰囲気がどう変わるかが体感的につかめます。作曲に行き詰まったときは、まずこのツールで気に入った進行を見つけてから、メロディーを乗せてみるのがおすすめです。
