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
      <label>音色</label>
      <select id="ctp5Timbre" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
        <option value="piano">ピアノ</option>
        <option value="organ">オルガン</option>
        <option value="strings">ストリングス</option>
      </select>
    </div>
  </div>
  <div class="ctp-row">
    <label>拍の長さ（1コードの保持）</label>
    <select id="ctp5ChordDur" class="ctp-select" onchange="ctp5ApplyIfPlaying()">
      <option value="whole">全音符（1小節）</option>
      <option value="quarter" selected>4分音符</option>
      <option value="eighth">8分音符</option>
    </select>
  </div>
  <button class="ctp-btn" id="ctp5StartBtn" onclick="ctp5Toggle()">▶ 再生開始</button>
  <div class="ctp-dots" id="ctp5BeatDots"></div>
  <div class="ctp-chord-display" id="ctp5ChordDisplay">—</div>
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
.ctp-chord-display { background:#1c1f2b; border-radius:10px; padding:14px; margin-top:10px; text-align:center; font-size:1.2rem; font-weight:900; color:#8b9bff; min-height:36px; }
.ctp-bpmnum { text-align:right; font-weight:900; font-size:1.15rem; color:#8b9bff; }
</style>

<script>
(function () {
  'use strict';
  'use strict';

  const NOTE_NAMES = ['C','C#','D','D#','E','F','F#','G','G#','A','A#','B'];

  // Roman numeral -> semitone offset from tonic (major scale degrees), quality
  // Supports the extra symbols needed by クリシェ進行: I/VII, I7/♭VII
  const DEGREE_MAJOR = { I:0, II:2, III:4, IV:5, V:7, VI:9, VII:11 };
  const DEGREE_MINOR = { I:0, II:2, IIIb:3, III:3, IV:5, V:7, VIb:8, VI:8, VIIb:10, VII:10 };

  // Chord progression definitions — matched to Cooltake Studio コード進行シリーズ #01〜#08 (Cキー基準)
  // 'm' = minor triad, '' = major triad, '7' = dominant7, 'maj7' = major7th, 'm7' = minor7th, 'm7b5' = half-diminished7th
  const PROGRESSIONS = {
    oudou: {
      name: '王道進行（Ⅳ-Ⅴ-Ⅲm-Ⅵm）',
      chords: [
        { deg:'IV', q:'' }, { deg:'V', q:'' }, { deg:'III', q:'m' }, { deg:'VI', q:'m' },
      ],
    },
    canon: {
      name: 'カノン進行（I-V-VIm-IIIm-IV-I-IV-V）',
      chords: [
        { deg:'I', q:'' }, { deg:'V', q:'' }, { deg:'VI', q:'m' }, { deg:'III', q:'m' },
        { deg:'IV', q:'' }, { deg:'I', q:'' }, { deg:'IV', q:'' }, { deg:'V', q:'' },
      ],
    },
    komuro: {
      name: '小室進行（Ⅵm-Ⅳ-Ⅰ-Ⅴ）',
      chords: [
        { deg:'VI', q:'m' }, { deg:'IV', q:'' }, { deg:'I', q:'' }, { deg:'V', q:'' },
      ],
    },
    marusa: {
      name: '丸サ進行（IIm7-V7-Imaj7-VIIm7♭5-III7）',
      chords: [
        { deg:'II', q:'m7' }, { deg:'V', q:'7' }, { deg:'I', q:'maj7' },
        { deg:'VII', q:'m7b5' }, { deg:'III', q:'7' },
      ],
    },
    junkan: {
      name: '循環コード（Ⅰ-Ⅵm-Ⅳ-Ⅴ）',
      chords: [
        { deg:'I', q:'' }, { deg:'VI', q:'m' }, { deg:'IV', q:'' }, { deg:'V', q:'' },
      ],
    },
    blues: {
      name: 'ブルース進行（Ⅰ-Ⅳ-Ⅴ）',
      chords: [
        { deg:'I', q:'7' }, { deg:'IV', q:'7' }, { deg:'V', q:'7' },
      ],
    },
    setsunai: {
      name: '切ない系進行（I-V-VIm-IIIm-IV-I-IV-V）',
      chords: [
        { deg:'I', q:'' }, { deg:'V', q:'' }, { deg:'VI', q:'m' }, { deg:'III', q:'m' },
        { deg:'IV', q:'' }, { deg:'I', q:'' }, { deg:'IV', q:'' }, { deg:'V', q:'' },
      ],
    },
    cliche: {
      name: 'クリシェ進行（I-I/VII-I/♭VII-I/VI）',
      // Slash chords: I major triad held, bass descends chromatically I→VII→♭VII→VI
      chords: [
        { deg:'I', q:'' , bassDeg:'I' },
        { deg:'I', q:'' , bassDeg:'VII' },
        { deg:'I', q:'' , bassDeg:'VII', bassLowered:true },
        { deg:'I', q:'' , bassDeg:'VI' },
      ],
    },
  };

  // Interval structures (semitones from chord root)
  const QUALITY_INTERVALS = {
    '':     [0,4,7],
    'm':    [0,3,7],
    '7':    [0,4,7,10],
    'maj7': [0,4,7,11],
    'm7':   [0,3,7,10],
    'm7b5': [0,3,6,10],
  };

  function noteNameToMidiBase(name) {
    // returns semitone index 0-11 for note letter (ignores octave), Major/Minor handled elsewhere
    const idx = NOTE_NAMES.indexOf(name);
    return idx;
  }

  function degreeSemitone(deg, scaleMap) {
    return scaleMap[deg];
  }

  // Build a chord's absolute note list (as semitone-from-C values, will be offset by key root)
  function buildChordNotes(chordDef, keyRootSemitone, isMinorKey) {
    const scaleMap = isMinorKey ? DEGREE_MINOR : DEGREE_MAJOR;
    const rootOffset = degreeSemitone(chordDef.deg, scaleMap);
    const intervals = QUALITY_INTERVALS[chordDef.q] || QUALITY_INTERVALS[''];
    const rootAbs = keyRootSemitone + rootOffset;
    let notes = intervals.map(iv => rootAbs + iv);

    if (chordDef.bassDeg) {
      let bassOffset = degreeSemitone(chordDef.bassDeg, scaleMap);
      if (chordDef.bassLowered) bassOffset -= 1; // ♭VII etc.
      const bassAbs = keyRootSemitone + bassOffset;
      // Put bass note an octave below the rest, replace/prepend
      notes = [bassAbs - 12, ...notes.filter(n => (n % 12 + 12) % 12 !== (bassAbs % 12 + 12) % 12)];
    }
    return notes;
  }

  function semitoneToFreq(semitoneFromC4) {
    // C4 = MIDI 60, A4 = 440Hz = MIDI 69
    const midi = 60 + semitoneFromC4;
    return 440 * Math.pow(2, (midi - 69) / 12);
  }

  /* ---------------- Audio Engine ---------------- */
  function ChordMetronomeEngine() {
    this.ctx = null;
    this.isPlaying = false;
    this.timerId = null;
    this.beatCount = 0;
    this.chordIndex = 0;
    this.onBeat = null;      // callback(beatInBar, totalBeatsInBar)
    this.onChordChange = null; // callback(chordIndex, chordLabel)
  }

  ChordMetronomeEngine.prototype._ensureCtx = function () {
    if (!this.ctx) {
      this.ctx = new (window.AudioContext || window.webkitAudioContext)();
    }
    if (this.ctx.state === 'suspended') this.ctx.resume();
    return this.ctx;
  };

  ChordMetronomeEngine.prototype.playClick = function (accent) {
    const ctx = this._ensureCtx();
    const osc = ctx.createOscillator();
    const gain = ctx.createGain();
    osc.type = 'square';
    osc.frequency.value = accent ? 1500 : 1000;
    gain.gain.setValueAtTime(accent ? 0.35 : 0.2, ctx.currentTime);
    gain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + 0.05);
    osc.connect(gain).connect(ctx.destination);
    osc.start();
    osc.stop(ctx.currentTime + 0.06);
  };

  // timbre: 'piano' | 'organ' | 'strings'
  ChordMetronomeEngine.prototype.playChordNotes = function (semitones, durationSec, timbre) {
    const ctx = this._ensureCtx();
    const now = ctx.currentTime;
    semitones.forEach(st => {
      const freq = semitoneToFreq(st);
      this._playVoice(freq, now, durationSec, timbre || 'piano');
    });
  };

  ChordMetronomeEngine.prototype._playVoice = function (freq, startTime, duration, timbre) {
    const ctx = this.ctx;
    const master = ctx.createGain();
    master.connect(ctx.destination);

    if (timbre === 'organ') {
      const partials = [1, 2, 3, 4];
      const gains = [0.5, 0.22, 0.12, 0.08];
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.5, startTime + 0.03);
      master.gain.setValueAtTime(0.5, startTime + Math.max(0.03, duration - 0.08));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration);
      partials.forEach((p, i) => {
        const osc = ctx.createOscillator();
        const g = ctx.createGain();
        osc.type = 'sine';
        osc.frequency.value = freq * p;
        g.gain.value = gains[i];
        osc.connect(g).connect(master);
        osc.start(startTime);
        osc.stop(startTime + duration + 0.05);
      });
    } else if (timbre === 'strings') {
      const osc1 = ctx.createOscillator();
      const osc2 = ctx.createOscillator();
      osc1.type = 'sawtooth';
      osc2.type = 'sawtooth';
      osc1.frequency.value = freq;
      osc2.frequency.value = freq * 1.005; // slight detune for ensemble effect
      const filter = ctx.createBiquadFilter();
      filter.type = 'lowpass';
      filter.frequency.value = 2200;
      master.gain.setValueAtTime(0.0001, startTime);
      master.gain.linearRampToValueAtTime(0.28, startTime + 0.25); // slow swell = strings
      master.gain.setValueAtTime(0.28, startTime + Math.max(0.25, duration - 0.3));
      master.gain.linearRampToValueAtTime(0.0001, startTime + duration + 0.2);
      osc1.connect(filter);
      osc2.connect(filter);
      filter.connect(master);
      osc1.start(startTime); osc2.start(startTime);
      osc1.stop(startTime + duration + 0.3);
      osc2.stop(startTime + duration + 0.3);
    } else {
      // piano: quick attack, exponential decay, slight inharmonicity via 2 partials
      const osc = ctx.createOscillator();
      const osc2 = ctx.createOscillator();
      osc.type = 'triangle';
      osc2.type = 'sine';
      osc.frequency.value = freq;
      osc2.frequency.value = freq * 2.001;
      const g2 = ctx.createGain();
      g2.gain.value = 0.15;
      master.gain.setValueAtTime(0.45, startTime);
      master.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
      osc.connect(master);
      osc2.connect(g2).connect(master);
      osc.start(startTime); osc2.start(startTime);
      osc.stop(startTime + duration + 0.05);
      osc2.stop(startTime + duration + 0.05);
    }
  };

  ChordMetronomeEngine.prototype.stop = function () {
    this.isPlaying = false;
    if (this.timerId) { clearTimeout(this.timerId); this.timerId = null; }
    this.beatCount = 0;
    this.chordIndex = 0;
  };

  /**
   * options:
   *  bpm, beatsPerBar (m), noteValue (n, e.g. 4 = quarter note gets the beat),
   *  progressionKey, keyRoot ('C'..'B'), keyMode ('major'|'minor'),
   *  chordDuration ('whole'|'quarter'|'eighth') -> how long each chord in the progression is held,
   *    expressed as a MULTIPLE of the bar's beat unit is handled by caller via chordBeats
   *  timbre, metronomeOn (bool), chordsOn (bool)
   */
  ChordMetronomeEngine.prototype.start = function (options) {
    this.stop();
    this._ensureCtx();
    this.isPlaying = true;
    const beatsPerBar = options.beatsPerBar || 4;
    const bpm = options.bpm || 120;
    const beatDurSec = 60 / bpm; // duration of one "beat" (the denominator note value gets the beat, standard metronome behavior)
    const progression = PROGRESSIONS[options.progressionKey] || PROGRESSIONS.oudou;
    const keyRootSemitone = noteNameToMidiBase(options.keyRoot || 'C');
    const isMinorKey = options.keyMode === 'minor';

    // How many beats each chord is held for
    const chordBeatMap = { whole: beatsPerBar, quarter: 1, eighth: 0.5 };
    const chordBeats = chordBeatMap[options.chordDuration] || beatsPerBar;

    this.beatCount = 0;
    this.chordIndex = 0;
    let beatsIntoChord = 0;

    const self = this;
    function tick() {
      if (!self.isPlaying) return;
      const beatInBar = self.beatCount % beatsPerBar;
      const isAccent = beatInBar === 0;

      if (options.metronomeOn !== false) {
        self.playClick(isAccent);
      }
      if (typeof self.onBeat === 'function') self.onBeat(beatInBar, beatsPerBar);

      if (options.chordsOn && beatsIntoChord === 0) {
        const chordDef = progression.chords[self.chordIndex % progression.chords.length];
        const notes = buildChordNotes(chordDef, keyRootSemitone, isMinorKey);
        const durSec = chordBeats * beatDurSec * 0.92; // slight gap before next
        self.playChordNotes(notes, durSec, options.timbre);
        if (typeof self.onChordChange === 'function') {
          self.onChordChange(self.chordIndex % progression.chords.length, chordDef);
        }
      }

      self.beatCount++;
      beatsIntoChord = (beatsIntoChord + 1) % chordBeats;
      if (beatsIntoChord === 0 && options.chordsOn) {
        self.chordIndex++;
      }

      self.timerId = setTimeout(tick, beatDurSec * 1000);
    }
    tick();
  };

  global.ChordMetronomeEngine = ChordMetronomeEngine;
  global.CHORD_PROGRESSIONS = PROGRESSIONS;
  global.NOTE_NAMES = NOTE_NAMES;

  let ctp5Engine = null;
  window.ctp5Slide = function () {
    document.getElementById('ctp5BpmNum').textContent = document.getElementById('ctp5Bpm').value;
    window.ctp5ApplyIfPlaying();
  };
  function ctp5GetOptions() {
    return {
      bpm: parseInt(document.getElementById('ctp5Bpm').value, 10),
      beatsPerBar: 4,
      timbre: document.getElementById('ctp5Timbre').value,
      progressionKey: 'junkan',
      keyRoot: document.getElementById('ctp5KeyRoot').value,
      keyMode: document.getElementById('ctp5KeyMode').value,
      chordDuration: document.getElementById('ctp5ChordDur').value,
      chordsOn: true,
      metronomeOn: true,
    };
  }
  function ctp5BuildDots() {
    const wrap = document.getElementById('ctp5BeatDots');
    wrap.innerHTML = Array.from({length: 4}, (_, i) => `<div class="ctp-dot" data-i="${i}"></div>`).join('');
  }
  window.ctp5Toggle = function () {
    const btn = document.getElementById('ctp5StartBtn');
    if (!ctp5Engine) ctp5Engine = new ChordMetronomeEngine();
    if (ctp5Engine.isPlaying) {
      ctp5Engine.stop();
      btn.textContent = '▶ 再生開始';
      document.querySelectorAll('#ctp5BeatDots .ctp-dot').forEach(d => d.style.background = '#383c4d');
    } else {
      ctp5BuildDots();
      ctp5Engine.onBeat = (beatInBar) => {
        document.querySelectorAll('#ctp5BeatDots .ctp-dot').forEach((d, i) => {
          d.style.background = i === beatInBar ? '#8b9bff' : '#383c4d';
        });
      };
      ctp5Engine.onChordChange = (idx, chordDef) => {
        const disp = document.getElementById('ctp5ChordDisplay');
        const qLabel = {'':'', m:'m', '7':'7', maj7:'maj7', m7:'m7', m7b5:'m7♭5'}[chordDef.q] || '';
        if (disp) disp.textContent = chordDef.deg + qLabel + (chordDef.bassDeg && chordDef.bassDeg !== chordDef.deg ? ' / ' + (chordDef.bassLowered ? '♭' : '') + chordDef.bassDeg : '');
      };
      ctp5Engine.start(ctp5GetOptions());
      btn.textContent = '■ 停止';
    }
  };
  window.ctp5ApplyIfPlaying = function () {
    if (ctp5Engine && ctp5Engine.isPlaying) ctp5Engine.start(ctp5GetOptions());
    ctp5BuildDots();
  };
  ctp5BuildDots();
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
