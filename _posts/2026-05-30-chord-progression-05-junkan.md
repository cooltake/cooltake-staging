---
layout: post
title: "循環コード（Ⅰ-Ⅵm-Ⅳ-Ⅴ）完全解説【コード進行シリーズ #05】代表曲20選＋50年代から令和まで"
date: 2026-05-30
categories: [chord]
tags: [ギター, キーボード, 作曲, 音楽制作, 初心者]
image: /assets/images/thumb-chord-05.jpg
description: "50年代ロカビリーから現代J-POPまで使われる「循環コード（Ⅰ-Ⅵm-Ⅳ-Ⅴ）」を徹底解説。Stand By Me・亜麻色の髪の乙女・ロビンソンなど代表曲20曲を楽天購入リンク付きで完全網羅。"
---




<div style="background:#eceae7;border-radius:8px;padding:1.4rem 1.6rem;margin:1.5rem 0;border-left:4px solid #1e3a5f;"><h3 style="color:#111827;margin-top:0;font-size:1rem;font-weight:700;">🎵 コード進行図（Cキー）</h3><span style="display:block;color:#374151;font-size:.9rem;margin:.4rem 0 1.2rem;"><strong>C</strong> → <strong>Am</strong> → <strong>F</strong> → <strong>G</strong></span><div style="display:grid;grid-template-columns:repeat(4,1fr);gap:1rem;overflow-x:auto;"><div style="text-align:center;min-width:0;"><span style="display:block;font-size:.85rem;font-weight:700;color:#111827;margin:0 0 6px;">C</span><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ギター</span><img src="/assets/chord-diagrams/guitar-c.svg" alt="C ギター" style="width:100%;max-width:150px;height:auto;display:block;margin:0 auto 10px;"><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ピアノ</span><img src="/assets/chord-diagrams/piano-c.svg" alt="C ピアノ" style="width:100%;max-width:230px;height:auto;display:block;margin:0 auto;"></div><div style="text-align:center;min-width:0;"><span style="display:block;font-size:.85rem;font-weight:700;color:#111827;margin:0 0 6px;">Am</span><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ギター</span><img src="/assets/chord-diagrams/guitar-am.svg" alt="Am ギター" style="width:100%;max-width:150px;height:auto;display:block;margin:0 auto 10px;"><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ピアノ</span><img src="/assets/chord-diagrams/piano-am.svg" alt="Am ピアノ" style="width:100%;max-width:230px;height:auto;display:block;margin:0 auto;"></div><div style="text-align:center;min-width:0;"><span style="display:block;font-size:.85rem;font-weight:700;color:#111827;margin:0 0 6px;">F</span><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ギター</span><img src="/assets/chord-diagrams/guitar-f.svg" alt="F ギター" style="width:100%;max-width:150px;height:auto;display:block;margin:0 auto 10px;"><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ピアノ</span><img src="/assets/chord-diagrams/piano-f.svg" alt="F ピアノ" style="width:100%;max-width:230px;height:auto;display:block;margin:0 auto;"></div><div style="text-align:center;min-width:0;"><span style="display:block;font-size:.85rem;font-weight:700;color:#111827;margin:0 0 6px;">G</span><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ギター</span><img src="/assets/chord-diagrams/guitar-g.svg" alt="G ギター" style="width:100%;max-width:150px;height:auto;display:block;margin:0 auto 10px;"><span style="display:block;font-size:.7rem;color:#6b7280;margin:0 0 4px;">ピアノ</span><img src="/assets/chord-diagrams/piano-g.svg" alt="G ピアノ" style="width:100%;max-width:230px;height:auto;display:block;margin:0 auto;"></div></div><span style="display:block;color:#6b7280;font-size:.75rem;margin:.8rem 0 0;">※ Cキー表示。実際の楽曲は移調される場合があります。</span></div>



<div class="ctp-card">
  <div style="font-size:.85rem;font-weight:900;margin-bottom:12px;color:#e8e8ef;">▶ 循環コードをその場で聴く</div>

  <div class="ctp-row">
    <label>テンポ（BPM）</label>
    <div style="display:flex;align-items:center;gap:10px;">
      <input id="ctp5Bpm" type="range" min="40" max="240" value="90" oninput="ctp5Slide()" style="flex:1;">
      <div class="ctp-bpmnum" style="width:56px;"><span id="ctp5BpmNum">90</span></div>
    </div>
  </div>

  <div class="ctp-pair">
    <div class="ctp-row">
      <label>キー</label>
      <div style="display:flex;gap:6px;">
        <select id="ctp5KeyRoot" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
          <option>C</option><option>C#</option><option>D</option><option>D#</option>
          <option>E</option><option>F</option><option>F#</option><option>G</option>
          <option>G#</option><option>A</option><option>A#</option><option>B</option>
        </select>
        <select id="ctp5KeyMode" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
          <option value="major">Major</option>
          <option value="minor">Minor</option>
        </select>
      </div>
    </div>
    <div class="ctp-row">
      <label>拍の長さ</label>
      <select id="ctp5ChordDur" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="whole" selected>全音符（1小節）</option>
        <option value="half">2分音符</option>
        <option value="quarter">4分音符</option>
        <option value="eighth">8分音符</option>
      </select>
    </div>
  </div>

  <div class="ctp-pair">
    <div class="ctp-row">
      <label>音色</label>
      <select id="ctp5Timbre" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="soft" selected>ソフトパッド</option>
        <option value="piano">ピアノ</option>
        <option value="organ">オルガン</option>
        <option value="strings">ストリングス</option>
      </select>
    </div>
    <div class="ctp-row">
      <label>演奏パターン</label>
      <select id="ctp5Pattern" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="block">ブロック（同時に鳴らす）</option>
        <option value="arpeggio-up">アルペジオ（上行）</option>
        <option value="arpeggio-updown">アルペジオ（上下）</option>
        <option value="rhythm">リズムカッティング</option>
      </select>
    </div>
  </div>

  <div class="ctp-pair">
    <div class="ctp-row">
      <label>メトロノーム音</label>
      <select id="ctp5MetroSound" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="click">電子音（クリック）</option>
        <option value="wood" selected>ウッドブロック</option>
        <option value="beep">ソフトビープ</option>
      </select>
    </div>
    <div class="ctp-row">
      <label>コード変更前のカウント</label>
      <select id="ctp5Countdown" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="0">なし</option>
        <option value="1">1小節</option>
        <option value="2">2小節</option>
      </select>
    </div>
  </div>

  <div class="ctp-pair">
    <div class="ctp-row">
      <label>メトロノーム音量</label>
      <input id="ctp5MetroVol" type="range" min="0" max="100" value="80" oninput="ctp5ApplyIfPlaying()">
    </div>
    <div class="ctp-row">
      <label>コード音量</label>
      <input id="ctp5ChordVol" type="range" min="0" max="100" value="80" oninput="ctp5ApplyIfPlaying()">
    </div>
  </div>

  <button class="ctp-btn" id="ctp5StartBtn" onclick="ctp5Toggle()">▶ 再生開始</button>
  <div class="ctp-dots" id="ctp5BeatDots"></div>
  <div id="ctp5StateLabel" style="font-size:.7rem;color:#a8acc0;text-align:center;margin-top:4px;"></div>

  <div id="ctp5ProgressionSeq" style="display:flex;flex-wrap:wrap;gap:6px;margin:12px 0;"></div>

  <div style="margin-top:8px;">
    <div style="font-size:.75rem;font-weight:700;color:#a8acc0;margin-bottom:6px;">🎼 現在のコードの構成音（オクターブ上下可・次回も記憶）</div>
    <div style="display:flex;align-items:center;gap:10px;margin-bottom:6px;">
      <button class="ctp-btn" onclick="ctp5ShiftOctave(-1)" style="width:auto;padding:6px 14px;">－1oct</button>
      <span id="ctp5OctaveLabel" style="font-size:.78rem;color:#a8acc0;">オクターブ: 0</span>
      <button class="ctp-btn" onclick="ctp5ShiftOctave(1)" style="width:auto;padding:6px 14px;">+1oct</button>
    </div>
    <div id="ctp5Staff" style="background:#0d0f16;border-radius:8px;padding:8px;"></div>
  </div>
</div>

<style>
.ctp-card { background:#12141c; border:1px solid #2a2d3a; border-radius:14px; padding:22px 24px; margin:24px 0; color:#e8e8ef; }
.ctp-row { margin-bottom:14px; }
.ctp-row label { display:block; font-size:.8rem; font-weight:700; margin-bottom:6px; color:#a8acc0; }
.ctp-pair { display:grid; grid-template-columns:1fr 1fr; gap:12px; }
.ctp-select { width:100%; padding:9px 10px; border-radius:8px; border:1px solid #383c4d; background:#1c1f2b; color:#e8e8ef; font-size:.88rem; }
.ctp-btn { width:100%; padding:12px; border:none; border-radius:10px; background:#5b6ee8; color:#fff; font-weight:700; font-size:.95rem; cursor:pointer; margin-top:6px; }
.ctp-btn:hover { background:#4757d1; }
.ctp-dots { display:flex; gap:6px; justify-content:center; margin-top:12px; }
.ctp-dot { width:14px; height:14px; border-radius:50%; background:#383c4d; transition:background .1s; }
.ctp-bpmnum { text-align:right; font-weight:900; font-size:1.15rem; color:#8b9bff; }
</style>

<script>
(function () {
  'use strict';
  'use strict';

  var NOTE_NAMES = ['C','C#','D','D#','E','F','F#','G','G#','A','A#','B'];
  var DEGREE_MAJOR = { I:0, II:2, III:4, IV:5, V:7, VI:9, VII:11 };
  var DEGREE_MINOR = { I:0, II:2, IIIb:3, III:3, IV:5, V:7, VIb:8, VI:8, VIIb:10, VII:10 };

  var QUALITY_INTERVALS = {
    '':     [0,4,7],
    'm':    [0,3,7],
    '7':    [0,4,7,10],
    'maj7': [0,4,7,11],
    'm7':   [0,3,7,10],
    'm7b5': [0,3,6,10],
  };

  function noteNameToMidiBase(name) { return NOTE_NAMES.indexOf(name); }

  // Build a chord's absolute note list (semitones from C4=0), applying a per-chord octave shift.
  function buildChordNotes(chordDef, keyRootSemitone, isMinorKey, octaveShift) {
    var scaleMap = isMinorKey ? DEGREE_MINOR : DEGREE_MAJOR;
    var rootOffset = scaleMap[chordDef.deg];
    var intervals = QUALITY_INTERVALS[chordDef.q] || QUALITY_INTERVALS[''];
    var rootAbs = keyRootSemitone + rootOffset;
    var notes = intervals.map(function (iv) { return rootAbs + iv; });

    if (chordDef.bassDeg) {
      var bassOffset = scaleMap[chordDef.bassDeg];
      if (chordDef.bassLowered) bassOffset -= 1;
      var bassAbs = keyRootSemitone + bassOffset;
      notes = [bassAbs - 12].concat(notes.filter(function (n) {
        return ((n % 12) + 12) % 12 !== ((bassAbs % 12) + 12) % 12;
      }));
    }
    var shift = (octaveShift || 0) * 12;
    return notes.map(function (n) { return n + shift; });
  }

  function semitoneToFreq(semitoneFromC4) {
    var midi = 60 + semitoneFromC4;
    return 440 * Math.pow(2, (midi - 69) / 12);
  }

  // Note name + octave label for staff/reference display, e.g. semitone 0 -> "C4"
  function semitoneToLabel(semitoneFromC4) {
    var midi = 60 + semitoneFromC4;
    var name = NOTE_NAMES[((midi % 12) + 12) % 12];
    var octave = Math.floor(midi / 12) - 1;
    return name + octave;
  }

  /* ---------------- Audio Engine ---------------- */
  function ChordMetronomeEngine() {
    this.ctx = null;
    this.isPlaying = false;
    this.timerId = null;
    this.beatCount = 0;
    this.chordIndex = 0;
    this.state = 'idle'; // 'idle' | 'countdown' | 'playing'
    this.countdownBeatsLeft = 0;
    this.onBeat = null;          // (beatInBar, beatsPerBar, state)
    this.onChordChange = null;   // (chordIndex, chordDef, notes)
    this.metronomeGain = 0.8;    // 0..1
    this.chordGain = 0.8;        // 0..1
  }

  ChordMetronomeEngine.prototype._ensureCtx = function () {
    if (!this.ctx) this.ctx = new (window.AudioContext || window.webkitAudioContext)();
    if (this.ctx.state === 'suspended') this.ctx.resume();
    return this.ctx;
  };

  // sound: 'click' (electronic), 'wood' (woodblock-ish), 'beep'
  ChordMetronomeEngine.prototype.playClick = function (accent, sound) {
    var ctx = this._ensureCtx();
    var vol = this.metronomeGain;
    if (vol <= 0) return;
    var now = ctx.currentTime;

    if (sound === 'wood') {
      // Short noise burst through a bandpass filter -> woodblock-like tick
      var bufferSize = ctx.sampleRate * 0.05;
      var buffer = ctx.createBuffer(1, bufferSize, ctx.sampleRate);
      var data = buffer.getChannelData(0);
      for (var i = 0; i < bufferSize; i++) data[i] = (Math.random() * 2 - 1) * Math.pow(1 - i / bufferSize, 3);
      var noise = ctx.createBufferSource();
      noise.buffer = buffer;
      var filter = ctx.createBiquadFilter();
      filter.type = 'bandpass';
      filter.frequency.value = accent ? 1800 : 1200;
      filter.Q.value = 3;
      var gain = ctx.createGain();
      gain.gain.setValueAtTime((accent ? 0.9 : 0.6) * vol, now);
      gain.gain.exponentialRampToValueAtTime(0.001, now + 0.05);
      noise.connect(filter).connect(gain).connect(ctx.destination);
      noise.start(now);
      noise.stop(now + 0.06);
    } else if (sound === 'beep') {
      var osc = ctx.createOscillator();
      var g = ctx.createGain();
      osc.type = 'sine';
      osc.frequency.value = accent ? 1800 : 1200;
      g.gain.setValueAtTime((accent ? 0.4 : 0.25) * vol, now);
      g.gain.exponentialRampToValueAtTime(0.001, now + 0.08);
      osc.connect(g).connect(ctx.destination);
      osc.start(now);
      osc.stop(now + 0.09);
    } else {
      // 'click' — original electronic square click
      var osc2 = ctx.createOscillator();
      var g2 = ctx.createGain();
      osc2.type = 'square';
      osc2.frequency.value = accent ? 1500 : 1000;
      g2.gain.setValueAtTime((accent ? 0.35 : 0.2) * vol, now);
      g2.gain.exponentialRampToValueAtTime(0.001, now + 0.05);
      osc2.connect(g2).connect(ctx.destination);
      osc2.start(now);
      osc2.stop(now + 0.06);
    }
  };

  // timbre: 'piano' | 'organ' | 'strings' | 'soft'
  // pattern: 'block' (all notes together) | 'arpeggio-up' | 'arpeggio-updown' | 'rhythm' (quarter-note comping)
  ChordMetronomeEngine.prototype.playChordNotes = function (semitones, durationSec, timbre, pattern) {
    var ctx = this._ensureCtx();
    var vol = this.chordGain;
    if (vol <= 0) return;
    var now = ctx.currentTime;
    var self = this;

    if (pattern === 'arpeggio-up' || pattern === 'arpeggio-updown') {
      var seq = semitones.slice();
      if (pattern === 'arpeggio-updown') seq = seq.concat(seq.slice(0, -1).reverse());
      var step = durationSec / seq.length;
      seq.forEach(function (st, i) {
        self._playVoice(semitoneToFreq(st), now + i * step, step * 0.95, timbre, vol);
      });
    } else if (pattern === 'rhythm') {
      // Simple comping: hit on beat 1 and the "and" of beat 2 (durationSec assumed = 1 chord's full hold)
      var hits = [0, durationSec * 0.5];
      hits.forEach(function (t) {
        semitones.forEach(function (st) {
          self._playVoice(semitoneToFreq(st), now + t, durationSec * 0.4, timbre, vol);
        });
      });
    } else {
      // 'block' (default): all notes together, sustained
      semitones.forEach(function (st) {
        self._playVoice(semitoneToFreq(st), now, durationSec, timbre, vol);
      });
    }
  };

  ChordMetronomeEngine.prototype._playVoice = function (freq, startTime, duration, timbre, vol) {
    var ctx = this.ctx;
    var master = ctx.createGain();
    master.connect(ctx.destination);
    vol = vol == null ? 1 : vol;

    if (timbre === 'organ') {
      var partials = [1, 2, 3, 4];
      var gains = [0.5, 0.22, 0.12, 0.08];
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.5 * vol, startTime + 0.03);
      master.gain.setValueAtTime(0.5 * vol, startTime + Math.max(0.03, duration - 0.08));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration);
      partials.forEach(function (p, i) {
        var osc = ctx.createOscillator();
        var g = ctx.createGain();
        osc.type = 'sine';
        osc.frequency.value = freq * p;
        g.gain.value = gains[i];
        osc.connect(g).connect(master);
        osc.start(startTime);
        osc.stop(startTime + duration + 0.05);
      });
    } else if (timbre === 'strings') {
      var osc1 = ctx.createOscillator();
      var osc2 = ctx.createOscillator();
      osc1.type = 'sawtooth'; osc2.type = 'sawtooth';
      osc1.frequency.value = freq; osc2.frequency.value = freq * 1.005;
      var filter = ctx.createBiquadFilter();
      filter.type = 'lowpass'; filter.frequency.value = 1800;
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.26 * vol, startTime + 0.25);
      master.gain.setValueAtTime(0.26 * vol, startTime + Math.max(0.25, duration - 0.3));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration + 0.2);
      osc1.connect(filter); osc2.connect(filter); filter.connect(master);
      osc1.start(startTime); osc2.start(startTime);
      osc1.stop(startTime + duration + 0.3);
      osc2.stop(startTime + duration + 0.3);
    } else if (timbre === 'soft') {
      // Soft pad: sine-based, slow attack, gentle lowpass — non-fatiguing
      var s1 = ctx.createOscillator();
      var s2 = ctx.createOscillator();
      s1.type = 'sine'; s2.type = 'sine';
      s1.frequency.value = freq; s2.frequency.value = freq * 2;
      var g2b = ctx.createGain();
      g2b.gain.value = 0.12;
      var lp = ctx.createBiquadFilter();
      lp.type = 'lowpass'; lp.frequency.value = 1400;
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.22 * vol, startTime + 0.18);
      master.gain.setValueAtTime(0.22 * vol, startTime + Math.max(0.18, duration - 0.25));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration + 0.25);
      s1.connect(lp); s2.connect(g2b); g2b.connect(lp); lp.connect(master);
      s1.start(startTime); s2.start(startTime);
      s1.stop(startTime + duration + 0.3); s2.stop(startTime + duration + 0.3);
    } else {
      // 'piano' (default): triangle + soft 2nd partial, exponential decay, lowpass to remove harshness
      var osc = ctx.createOscillator();
      var osc2b = ctx.createOscillator();
      osc.type = 'triangle'; osc2b.type = 'sine';
      osc.frequency.value = freq; osc2b.frequency.value = freq * 2.001;
      var g2c = ctx.createGain();
      g2c.gain.value = 0.12;
      var lp2 = ctx.createBiquadFilter();
      lp2.type = 'lowpass'; lp2.frequency.value = 3200;
      master.gain.setValueAtTime(0.4 * vol, startTime);
      master.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
      osc.connect(lp2); osc2b.connect(g2c); g2c.connect(lp2); lp2.connect(master);
      osc.start(startTime); osc2b.start(startTime);
      osc.stop(startTime + duration + 0.05);
      osc2b.stop(startTime + duration + 0.05);
    }
  };

  ChordMetronomeEngine.prototype.stop = function () {
    this.isPlaying = false;
    this.state = 'idle';
    if (this.timerId) { clearTimeout(this.timerId); this.timerId = null; }
    this.beatCount = 0;
    this.chordIndex = 0;
  };

  /**
   * options:
   *  bpm, beatsPerBar, progressionKey/progression (custom array), keyRoot, keyMode,
   *  chordDuration ('whole'|'half'|'quarter'|'eighth'),
   *  timbre, pattern, metronomeSound ('click'|'wood'|'beep'),
   *  metronomeOn, chordsOn, octaveShifts (array parallel to chords, semitone-octave shift per chord index),
   *  countdownBars (int, number of metronome-only bars to play before EACH chord change; 0 = off)
   */
  ChordMetronomeEngine.prototype.start = function (options) {
    this.stop();
    this._ensureCtx();
    this.isPlaying = true;
    var beatsPerBar = options.beatsPerBar || 4;
    var bpm = options.bpm || 90;
    var beatDurSec = 60 / bpm;
    var progression = options.progression || { chords: [{ deg: 'I', q: '' }] };
    var keyRootSemitone = noteNameToMidiBase(options.keyRoot || 'C');
    var isMinorKey = options.keyMode === 'minor';
    var chordBeatMap = { whole: beatsPerBar, half: beatsPerBar / 2, quarter: 1, eighth: 0.5 };
    var chordBeats = chordBeatMap[options.chordDuration] || beatsPerBar;
    var octaveShifts = options.octaveShifts || [];
    var countdownBars = options.countdownBars || 0;

    this.beatCount = 0;
    this.chordIndex = 0;
    // beatsIntoChord counts how many "playing" beats have elapsed for the CURRENT chord,
    // BEFORE this tick. When it's 0, this tick must sound a new chord.
    var beatsIntoChord = 0;
    this.state = (countdownBars > 0 && options.chordsOn) ? 'countdown' : 'playing';
    this.countdownBeatsLeft = countdownBars * beatsPerBar;

    var self = this;

    function soundChord() {
      if (!options.chordsOn) return;
      var chordDef = progression.chords[self.chordIndex % progression.chords.length];
      var shift = octaveShifts[self.chordIndex % progression.chords.length] || 0;
      var notes = buildChordNotes(chordDef, keyRootSemitone, isMinorKey, shift);
      var durSec = chordBeats * beatDurSec * 0.95;
      self.playChordNotes(notes, durSec, options.timbre, options.pattern);
      if (typeof self.onChordChange === 'function') {
        self.onChordChange(self.chordIndex % progression.chords.length, chordDef, notes);
      }
    }

    function tick() {
      if (!self.isPlaying) return;
      var beatInBar = self.beatCount % beatsPerBar;
      var isAccent = beatInBar === 0;

      if (options.metronomeOn !== false) {
        self.playClick(isAccent, options.metronomeSound);
      }

      if (self.state === 'countdown') {
        self.countdownBeatsLeft--;
        if (self.countdownBeatsLeft <= 0) {
          self.state = 'playing';
          beatsIntoChord = 0;
        }
      }

      if (typeof self.onBeat === 'function') self.onBeat(beatInBar, beatsPerBar, self.state);

      if (self.state === 'playing') {
        if (beatsIntoChord === 0) soundChord();
        beatsIntoChord++;
        if (beatsIntoChord >= chordBeats) {
          beatsIntoChord = 0;
          self.chordIndex++;
          if (countdownBars > 0 && options.chordsOn) {
            self.state = 'countdown';
            self.countdownBeatsLeft = countdownBars * beatsPerBar;
          }
        }
      }

      self.beatCount++;
      self.timerId = setTimeout(tick, beatDurSec * 1000);
    }
    tick();
  };

/* ============================================================
   UI helper functions shared by ToolsLab + Cooltake embeds (v2)
   Requires: engine-v2.js loaded first (window.ChordMetronomeEngineV2, buildChordNotes, semitoneToLabel)
   ============================================================ */

// Very small staff renderer: draws a 5-line treble staff and note heads for given semitone offsets (relative to C4=0).
// Returns an SVG string. Good enough for "which notes will sound" reference, not full notation engraving.
function ctpRenderStaffSVG(semitones, width) {
  width = width || 260;
  var height = 100;
  var lineGap = 10;
  var top = 20;
  var linesY = [0,1,2,3,4].map(function(i){ return top + i*lineGap; });
  // Staff line pitches (treble clef): E4 F4 G4 A4 B4 C5 D5 E5 F5 (bottom to top: E4,G4,B4,D5,F5)
  // Map semitone-from-C4 to a vertical position using a simple diatonic step approximation.
  var REF = { // semitone-from-C4 -> staff step (0 = bottom line E4), fractional steps for accidentals
    '-8':-3.5,'-7':-3,'-6':-2.5,'-5':-2,'-4':-1.5,'-3':-1,'-2':-0.5,'-1':0,
    '0':0.5,'1':1,'2':1.5,'3':2,'4':2.5,'5':3,'6':3.5,'7':4,'8':4.5,'9':5,'10':5.5,'11':6,
    '12':6.5,'13':7,'14':7.5,'15':8,'16':8.5,'17':9,'18':9.5,'19':10,'20':10.5,'21':11,'22':11.5,'23':12
  };
  function stepFor(s) {
    var v = REF[String(s)];
    if (v == null) v = 6 + (s - 11) * 0.5; // fallback extrapolation for far-out notes
    return v;
  }
  var noteEls = semitones.map(function (s, i) {
    var step = stepFor(s);
    var y = top + 4*lineGap - step*lineGap*0.7; // bottom line (E4)=step0 anchored near line index4
    var x = 60 + i*28;
    var ledger = '';
    if (y < top - 2) ledger = '<line x1="'+(x-10)+'" y1="'+top+'" x2="'+(x+10)+'" y2="'+top+'" stroke="#8b9bff" stroke-width="1"/>';
    if (y > top + 4*lineGap + 2) ledger = '<line x1="'+(x-10)+'" y1="'+(top+4*lineGap)+'" x2="'+(x+10)+'" y2="'+(top+4*lineGap)+'" stroke="#8b9bff" stroke-width="1"/>';
    return ledger + '<ellipse cx="'+x+'" cy="'+y+'" rx="6" ry="4.5" fill="#8b9bff"/>';
  }).join('');
  var lines = linesY.map(function(y){ return '<line x1="20" y1="'+y+'" x2="'+width+'" y2="'+y+'" stroke="#555" stroke-width="1"/>'; }).join('');
  return '<svg viewBox="0 0 '+width+' '+height+'" width="100%" height="'+height+'" xmlns="http://www.w3.org/2000/svg">'+
    '<text x="18" y="'+(top+4*lineGap+4)+'" font-size="30" fill="#8b9bff">𝄞</text>' +
    lines + noteEls + '</svg>';
}

function ctpQualityLabel(q) {
  return { '':'', m:'m', '7':'7', maj7:'maj7', m7:'m7', m7b5:'m7♭5' }[q] || '';
}

function ctpChordLabel(chordDef) {
  var base = chordDef.deg + ctpQualityLabel(chordDef.q);
  if (chordDef.bassDeg && chordDef.bassDeg !== chordDef.deg) {
    base += '/' + (chordDef.bassLowered ? '♭' : '') + chordDef.bassDeg;
  }
  return base;
}


  var ctp5PROGRESSION = { chords: [{deg:'I',q:''},{deg:'VI',q:'m'},{deg:'IV',q:''},{deg:'V',q:''}] };
  var ctp5Engine = null;
  var ctp5OctaveShifts = {};
  var ctp5CurrentChordIdx = 0;

  function ctp5LoadShifts() {
    try {
      var raw = localStorage.getItem('cooltake_ctp5_octave_shifts_junkan');
      ctp5OctaveShifts = raw ? JSON.parse(raw) : {};
    } catch (e) { ctp5OctaveShifts = {}; }
  }
  function ctp5SaveShifts() {
    try { localStorage.setItem('cooltake_ctp5_octave_shifts_junkan', JSON.stringify(ctp5OctaveShifts)); } catch (e) {}
  }
  function ctp5GetShiftsArray() {
    return ctp5PROGRESSION.chords.map(function (_, i) { return ctp5OctaveShifts[i] || 0; });
  }
  window.ctp5Slide = function () {
    document.getElementById('ctp5BpmNum').textContent = document.getElementById('ctp5Bpm').value;
    window.ctp5ApplyIfPlaying();
  };
  function ctp5GetOptions() {
    return {
      bpm: parseInt(document.getElementById('ctp5Bpm').value, 10),
      beatsPerBar: 4,
      timbre: document.getElementById('ctp5Timbre').value,
      pattern: document.getElementById('ctp5Pattern').value,
      metronomeSound: document.getElementById('ctp5MetroSound').value,
      progression: ctp5PROGRESSION,
      keyRoot: document.getElementById('ctp5KeyRoot').value,
      keyMode: document.getElementById('ctp5KeyMode').value,
      chordDuration: document.getElementById('ctp5ChordDur').value,
      chordsOn: true,
      countdownBars: parseInt(document.getElementById('ctp5Countdown').value, 10),
      metronomeOn: true,
      octaveShifts: ctp5GetShiftsArray(),
    };
  }
  function ctp5BuildDots() {
    var wrap = document.getElementById('ctp5BeatDots');
    wrap.innerHTML = Array.from({length: 4}, function (_, i) { return '<div class="ctp-dot" data-i="' + i + '"></div>'; }).join('');
  }
  function ctp5RenderSequence(activeIdx) {
    var wrap = document.getElementById('ctp5ProgressionSeq');
    wrap.innerHTML = ctp5PROGRESSION.chords.map(function (c, i) {
      var label = ctpChordLabel(c);
      var active = i === activeIdx;
      return '<div style="padding:6px 12px;border-radius:8px;font-weight:700;font-size:.85rem;' +
        'border:2px solid ' + (active ? '#8b9bff' : '#383c4d') + ';' +
        'background:' + (active ? 'rgba(139,155,255,.15)' : '#1c1f2b') + ';' +
        'color:' + (active ? '#8b9bff' : '#e8e8ef') + ';">' + label + '</div>';
    }).join('');
  }
  function ctp5UpdateStaff(activeIdx) {
    var chordDef = ctp5PROGRESSION.chords[activeIdx];
    var shift = ctp5OctaveShifts[activeIdx] || 0;
    var keyRoot = document.getElementById('ctp5KeyRoot').value;
    var keyMode = document.getElementById('ctp5KeyMode').value;
    var keyRootSemitone = ['C','C#','D','D#','E','F','F#','G','G#','A','A#','B'].indexOf(keyRoot);
    var notes = buildChordNotes(chordDef, keyRootSemitone, keyMode === 'minor', shift);
    document.getElementById('ctp5Staff').innerHTML = ctpRenderStaffSVG(notes);
    document.getElementById('ctp5OctaveLabel').textContent = 'オクターブ: ' + (shift > 0 ? '+' : '') + shift;
  }
  window.ctp5ShiftOctave = function (delta) {
    var cur = ctp5OctaveShifts[ctp5CurrentChordIdx] || 0;
    var next = Math.max(-2, Math.min(2, cur + delta));
    ctp5OctaveShifts[ctp5CurrentChordIdx] = next;
    ctp5SaveShifts();
    ctp5UpdateStaff(ctp5CurrentChordIdx);
    window.ctp5ApplyIfPlaying();
  };
  window.ctp5Toggle = function () {
    var btn = document.getElementById('ctp5StartBtn');
    if (!ctp5Engine) ctp5Engine = new ChordMetronomeEngine();
    if (ctp5Engine.isPlaying) {
      ctp5Engine.stop();
      btn.textContent = '▶ 再生開始';
      document.getElementById('ctp5StateLabel').textContent = '';
      document.querySelectorAll('#ctp5BeatDots .ctp-dot').forEach(function (d) { d.style.background = '#383c4d'; });
    } else {
      ctp5BuildDots();
      ctp5Engine.onBeat = function (beatInBar, beatsPerBar, state) {
        document.querySelectorAll('#ctp5BeatDots .ctp-dot').forEach(function (d, i) {
          d.style.background = i === beatInBar ? (state === 'countdown' ? '#f59e0b' : '#8b9bff') : '#383c4d';
        });
        document.getElementById('ctp5StateLabel').textContent = state === 'countdown' ? 'カウント中…' : '';
      };
      ctp5Engine.onChordChange = function (idx) {
        ctp5CurrentChordIdx = idx;
        ctp5RenderSequence(idx);
        ctp5UpdateStaff(idx);
      };
      ctp5Engine.metronomeGain = parseInt(document.getElementById('ctp5MetroVol').value, 10) / 100;
      ctp5Engine.chordGain = parseInt(document.getElementById('ctp5ChordVol').value, 10) / 100;
      ctp5Engine.start(ctp5GetOptions());
      btn.textContent = '■ 停止';
    }
  };
  window.ctp5ApplyIfPlaying = function () {
    if (ctp5Engine) {
      ctp5Engine.metronomeGain = parseInt(document.getElementById('ctp5MetroVol').value, 10) / 100;
      ctp5Engine.chordGain = parseInt(document.getElementById('ctp5ChordVol').value, 10) / 100;
    }
    if (ctp5Engine && ctp5Engine.isPlaying) ctp5Engine.start(ctp5GetOptions());
    ctp5BuildDots();
  }

  ctp5LoadShifts();
  ctp5BuildDots();
  ctp5RenderSequence(0);
  ctp5UpdateStaff(0);
})();
</script>


## 循環コードとは？音楽の「永久機関」

Cキーで：**C → Am → F → G（Ⅰ-Ⅵm-Ⅳ-Ⅴ）**

1950年代のロカビリーで確立し、70年以上使われ続ける進行。「50s Progression」とも呼ばれ、安定感・明るさ・推進力のバランスが完璧で初心者でも弾きやすい。

<div style="background:#eceae7;border-radius:8px;padding:1.2rem 1.4rem;margin:1.5rem 0;border-left:4px solid #1e3a5f;"><h3 style="color:#111827;margin-top:0;font-size:1rem;font-weight:700;">🌍 世界での使われ方</h3><ul style="color:#111827;"><li><strong>欧米</strong>：Stand By Me（Ben E. King）、Earth Angel、Blue Moon——50年代から定番の「50s Progression」</li><li><strong>日本</strong>：GSブーム〜現在まで継続使用。亜麻色の髪の乙女・ロビンソン・ダイアモンドなど幅広いジャンルに</li></ul></div>

---

## 循環コードを使った代表曲20選


<div style="display:grid;grid-template-columns:repeat(2,1fr);gap:.6rem;margin:1rem 0;"><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#01</span>  <span style="color:#111827;font-weight:bold;">「亜麻色の髪の乙女」</span>  <span style="color:#4b5563;">— 島谷ひとみ</span>  <span style="color:#64748b;font-size:.85rem;">（2002年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル / ヴィレッジ・シンガーズのカバー</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E4%BA%9C%E9%BA%BB%E8%89%B2%E3%81%AE%E9%AB%AA%E3%81%AE%E4%B9%99%E5%A5%B3%20%E5%B3%B6%E8%B0%B7%E3%81%B2%E3%81%A8%E3%81%BF" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="亜麻色の髪の乙女 YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#02</span>  <span style="color:#111827;font-weight:bold;">「Stand By Me」</span>  <span style="color:#4b5563;">— Ben E. King</span>  <span style="color:#64748b;font-size:.85rem;">（1961年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル / 世界中でカバーされた名曲</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Stand%20By%20Me%20Ben%20E.%20King" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Stand By Me YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#03</span>  <span style="color:#111827;font-weight:bold;">「Blue Moon」</span>  <span style="color:#4b5563;">— Various Artists</span>  <span style="color:#64748b;font-size:.85rem;">（1934年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: ジャズ・ポップスの古典</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Blue%20Moon%20Various%20Artists" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Blue Moon YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#04</span>  <span style="color:#111827;font-weight:bold;">「Earth Angel」</span>  <span style="color:#4b5563;">— The Penguins</span>  <span style="color:#64748b;font-size:.85rem;">（1954年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: ドゥーワップの名曲</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Earth%20Angel%20The%20Penguins" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Earth Angel YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#05</span>  <span style="color:#111827;font-weight:bold;">「夢をあきらめないで」</span>  <span style="color:#4b5563;">— 岡村孝子</span>  <span style="color:#64748b;font-size:.85rem;">（1988年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E5%A4%A2%E3%82%92%E3%81%82%E3%81%8D%E3%82%89%E3%82%81%E3%81%AA%E3%81%84%E3%81%A7%20%E5%B2%A1%E6%9D%91%E5%AD%9D%E5%AD%90" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="夢をあきらめないで YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#06</span>  <span style="color:#111827;font-weight:bold;">「ダイアモンド」</span>  <span style="color:#4b5563;">— プリンセス プリンセス</span>  <span style="color:#64748b;font-size:.85rem;">（1989年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E3%83%80%E3%82%A4%E3%82%A2%E3%83%A2%E3%83%B3%E3%83%89%20%E3%83%97%E3%83%AA%E3%83%B3%E3%82%BB%E3%82%B9%20%E3%83%97%E3%83%AA%E3%83%B3%E3%82%BB%E3%82%B9" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="ダイアモンド YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#07</span>  <span style="color:#111827;font-weight:bold;">「少年時代」</span>  <span style="color:#4b5563;">— 井上陽水</span>  <span style="color:#64748b;font-size:.85rem;">（1990年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル / アルバム「少年時代」</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E5%B0%91%E5%B9%B4%E6%99%82%E4%BB%A3%20%E4%BA%95%E4%B8%8A%E9%99%BD%E6%B0%B4" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="少年時代 YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#08</span>  <span style="color:#111827;font-weight:bold;">「You've Lost That Lovin' Feelin'」</span>  <span style="color:#4b5563;">— Righteous Brothers</span>  <span style="color:#64748b;font-size:.85rem;">（1964年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=You%27ve%20Lost%20That%20Lovin%27%20Feelin%27%20Righteous%20Brothers" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="You've Lost That Lovin' Feelin' YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#09</span>  <span style="color:#111827;font-weight:bold;">「In The Still Of The Night」</span>  <span style="color:#4b5563;">— The Five Satins</span>  <span style="color:#64748b;font-size:.85rem;">（1956年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: ドゥーワップの名作</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=In%20The%20Still%20Of%20The%20Night%20The%20Five%20Satins" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="In The Still Of The Night YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#10</span>  <span style="color:#111827;font-weight:bold;">「愛をとりもどせ!!」</span>  <span style="color:#4b5563;">— クリスタルキング</span>  <span style="color:#64748b;font-size:.85rem;">（1984年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: アニメ「北斗の拳」主題歌</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E6%84%9B%E3%82%92%E3%81%A8%E3%82%8A%E3%82%82%E3%81%A9%E3%81%9B%21%21%20%E3%82%AF%E3%83%AA%E3%82%B9%E3%82%BF%E3%83%AB%E3%82%AD%E3%83%B3%E3%82%B0" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="愛をとりもどせ!! YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#11</span>  <span style="color:#111827;font-weight:bold;">「OH MY LITTLE GIRL」</span>  <span style="color:#4b5563;">— 尾崎豊</span>  <span style="color:#64748b;font-size:.85rem;">（1983年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: アルバム「十七歳の地図」収録</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=OH%20MY%20LITTLE%20GIRL%20%E5%B0%BE%E5%B4%8E%E8%B1%8A" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="OH MY LITTLE GIRL YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#12</span>  <span style="color:#111827;font-weight:bold;">「未来予想図Ⅱ」</span>  <span style="color:#4b5563;">— DREAMS COME TRUE</span>  <span style="color:#64748b;font-size:.85rem;">（1989年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E6%9C%AA%E6%9D%A5%E4%BA%88%E6%83%B3%E5%9B%B3%E2%85%A1%20DREAMS%20COME%20TRUE" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="未来予想図Ⅱ YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#13</span>  <span style="color:#111827;font-weight:bold;">「ロビンソン」</span>  <span style="color:#4b5563;">— スピッツ</span>  <span style="color:#64748b;font-size:.85rem;">（1995年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル / アルバム「ハチミツ」</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E3%83%AD%E3%83%93%E3%83%B3%E3%82%BD%E3%83%B3%20%E3%82%B9%E3%83%94%E3%83%83%E3%83%84" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="ロビンソン YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#14</span>  <span style="color:#111827;font-weight:bold;">「やんちゃ車」</span>  <span style="color:#4b5563;">— 嘉門達夫</span>  <span style="color:#64748b;font-size:.85rem;">（1990年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E3%82%84%E3%82%93%E3%81%A1%E3%82%83%E8%BB%8A%20%E5%98%89%E9%96%80%E9%81%94%E5%A4%AB" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="やんちゃ車 YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#15</span>  <span style="color:#111827;font-weight:bold;">「Will You Love Me Tomorrow」</span>  <span style="color:#4b5563;">— Carole King</span>  <span style="color:#64748b;font-size:.85rem;">（1971年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: アルバム「Tapestry」収録</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Will%20You%20Love%20Me%20Tomorrow%20Carole%20King" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Will You Love Me Tomorrow YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#16</span>  <span style="color:#111827;font-weight:bold;">「ウェディング・ベル」</span>  <span style="color:#4b5563;">— 杏里 / Sugar</span>  <span style="color:#64748b;font-size:.85rem;">（1981年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E3%82%A6%E3%82%A7%E3%83%87%E3%82%A3%E3%83%B3%E3%82%B0%E3%83%BB%E3%83%99%E3%83%AB%20%E6%9D%8F%E9%87%8C%20/%20Sugar" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="ウェディング・ベル YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#17</span>  <span style="color:#111827;font-weight:bold;">「Yesterday Once More」</span>  <span style="color:#4b5563;">— Carpenters</span>  <span style="color:#64748b;font-size:.85rem;">（1973年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: アルバム「Now & Then」</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Yesterday%20Once%20More%20Carpenters" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Yesterday Once More YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#18</span>  <span style="color:#111827;font-weight:bold;">「プレイバックPart2」</span>  <span style="color:#4b5563;">— 山口百恵</span>  <span style="color:#64748b;font-size:.85rem;">（1978年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=%E3%83%97%E3%83%AC%E3%82%A4%E3%83%90%E3%83%83%E3%82%AFPart2%20%E5%B1%B1%E5%8F%A3%E7%99%BE%E6%81%B5" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="プレイバックPart2 YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#19</span>  <span style="color:#111827;font-weight:bold;">「WOMAN"Wの悲劇"より」</span>  <span style="color:#4b5563;">— 薬師丸ひろ子</span>  <span style="color:#64748b;font-size:.85rem;">（1984年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=WOMAN%22W%E3%81%AE%E6%82%B2%E5%8A%87%22%E3%82%88%E3%82%8A%20%E8%96%AC%E5%B8%AB%E4%B8%B8%E3%81%B2%E3%82%8D%E5%AD%90" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="WOMAN&quot;Wの悲劇&quot;より YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div><div style="background:#f0eeeb;border-radius:6px;padding:1rem 1.2rem;margin:0;border-left:3px solid #1e3a5f;"><div style="display:flex;align-items:baseline;gap:.6rem;margin-bottom:.5rem;">  <span style="color:#64748b;font-size:.8rem;min-width:1.8rem;">#20</span>  <span style="color:#111827;font-weight:bold;">「Where Did Our Love Go」</span>  <span style="color:#4b5563;">— The Supremes</span>  <span style="color:#64748b;font-size:.85rem;">（1964年）</span></div><span style="display:block;color:#6b7280;font-size:.82rem;margin:.2rem 0 .7rem 2.4rem;">収録: シングル / モータウン</span><div style="margin-left:2.4rem;"><a href="https://music.youtube.com/search?q=Where%20Did%20Our%20Love%20Go%20The%20Supremes" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;margin:0 auto;"><img src="/assets/images/btn-youtube-music.jpg" alt="Where Did Our Love Go YouTube Music" width="200" style="max-width:100%;height:auto;border-radius:14px;display:block;margin:0 auto;"></a></div></div></div>

---

## ギターでの弾き方

すべてオープンコード。初心者が最初に覚えるべき進行のひとつ：

```
C → Am → F → G
```

<div style="display:flex;flex-wrap:wrap;gap:.6rem;align-items:center;margin-top:.8rem;"><span style="font-size:.78rem;font-weight:700;color:#374151;white-space:nowrap;">🎸 ギターを探す</span><a href="https://h.accesstrade.net/sp/cc?rk=01001xqc00os63&url=https%3A%2F%2Fwww.soundhouse.co.jp%2Fsearch%2Findex%3Fs_cat%3D271%26s_word%3D%25A5%25AE%25A5%25BF%25A1%25BC%26s_ord%3D2" target="_blank" rel="nofollow noopener" title="ギターをサウンドハウスで探す"><img src="/assets/images/btn-soundhouse.jpg" alt="サウンドハウスで探す" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a><a href="https://search.rakuten.co.jp/search/mall/%E3%82%A2%E3%82%B3%E3%83%BC%E3%82%B9%E3%83%86%E3%82%A3%E3%83%83%E3%82%AF%E3%82%AE%E3%82%BF%E3%83%BC+%E5%88%9D%E5%BF%83%E8%80%85+%E3%82%BB%E3%83%83%E3%83%88/" target="_blank" rel="nofollow noopener" title="アコースティックギターを楽天市場で探す"><img src="/assets/images/btn-rakuten.jpg" alt="楽天市場で探す" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a><span style="display:inline-block;width:1px;height:24px;background:#d1d5db;margin:0 .2rem;"></span><span style="font-size:.78rem;font-weight:700;color:#374151;white-space:nowrap;">📖 コード教則本</span><a href="https://books.rakuten.co.jp/search?sitem=%E3%82%AE%E3%82%BF%E3%83%BC+%E3%82%B3%E3%83%BC%E3%83%89+%E6%95%99%E5%89%87%E6%9C%AC&g=212" target="_blank" rel="nofollow noopener" title="ギターコード教則本を楽天ブックスで探す"><img src="/assets/images/btn-rakuten.jpg" alt="ギターコード教則本 楽天ブックス" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a></div>

---

## ピアノ・キーボードでの弾き方

左手ベースラインが5度ずつ下がる動きを意識する：

```
C  : ド・ミ・ソ
Am : ラ・ド・ミ
F  : ファ・ラ・ド
G  : ソ・シ・レ
```

<div style="display:flex;flex-wrap:wrap;gap:.6rem;align-items:center;margin-top:.8rem;"><span style="font-size:.78rem;font-weight:700;color:#374151;white-space:nowrap;">🎹 キーボードを探す</span><a href="https://h.accesstrade.net/sp/cc?rk=01001xqc00os63&url=https%3A%2F%2Fwww.soundhouse.co.jp%2Fsearch%2Findex%3Fs_cat%3D276%26s_word%3D%25A5%25AD%25A1%25BC%25A5%25DC%25A1%25BC%25A5%25C9%26s_ord%3D2" target="_blank" rel="nofollow noopener" title="キーボードをサウンドハウスで探す"><img src="/assets/images/btn-soundhouse.jpg" alt="サウンドハウスで探す" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a><a href="https://search.rakuten.co.jp/search/mall/%E3%83%9D%E3%83%BC%E3%82%BF%E3%83%96%E3%83%AB%E3%82%AD%E3%83%BC%E3%83%9C%E3%83%BC%E3%83%89/" target="_blank" rel="nofollow noopener" title="キーボードを楽天市場で探す"><img src="/assets/images/btn-rakuten.jpg" alt="楽天市場で探す" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a><span style="display:inline-block;width:1px;height:24px;background:#d1d5db;margin:0 .2rem;"></span><span style="font-size:.78rem;font-weight:700;color:#374151;white-space:nowrap;">📖 コード教則本</span><a href="https://books.rakuten.co.jp/search?sitem=%E3%83%94%E3%82%A2%E3%83%8E+%E3%82%B3%E3%83%BC%E3%83%89+%E6%95%99%E5%89%87%E6%9C%AC&g=212" target="_blank" rel="nofollow noopener" title="ピアノコード教則本を楽天ブックスで探す"><img src="/assets/images/btn-rakuten.jpg" alt="ピアノコード教則本 楽天ブックス" height="36" style="height:36px;width:auto;border-radius:6px;display:block;"></a></div>

---

---

## 教則本・コードブック

<div style="background:#fff7ed;border:1px solid #fed7aa;border-radius:10px;padding:1rem 1.2rem;">
<p style="font-size:.8rem;font-weight:700;color:#c2410c;margin:0 0 .6rem;">📖 コード進行の教則本を楽天ブックスで購入</p>
<a href="https://books.rakuten.co.jp/search?sitem=%E3%82%B3%E3%83%BC%E3%83%89%E9%80%B2%E8%A1%8C+%E6%95%99%E5%89%87%E6%9C%AC&g=212" target="_blank" rel="nofollow noopener" style="display:block;text-decoration:none;text-align:center;"><img src="/assets/images/btn-rakuten.jpg" alt="コード進行の教則本を楽天ブックスで購入" width="200" style="max-width:100%;height:auto;border-radius:8px;display:block;margin:0 auto;"></a>
</div>

---

<div style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:.8rem;margin:2rem 0;"><a href="/chord/chord-progression-04-marusa/" style="display:inline-block;padding:.5rem 1rem;background:rgba(30,58,95,.15);border:1px solid rgba(30,58,95,.25);border-radius:8px;color:#1e3a5f;text-decoration:none;font-size:.9rem;">← #04 丸サ進行</a><a href="/chord/chord-progression-06-kanashii/" style="display:inline-block;padding:.5rem 1rem;background:rgba(30,58,95,.15);border:1px solid rgba(30,58,95,.25);border-radius:8px;color:#1e3a5f;text-decoration:none;font-size:.9rem;">#06 切ない系進行 →</a>
