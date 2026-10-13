# Scalien — Guitar Scale & Chord Explorer

An interactive fretboard tool for guitarists, students and teachers. Pick a key and a
scale (or a chord, or a mode), and Scalien draws every note across the neck, plays it
back, and lets you hear and see exactly where each note lives.

**Live:** https://articulate-english.github.io/scalien/

## What it does

- **Scales** — 18 scale types (major, natural / harmonic / melodic minor, the seven
  modes, pentatonic major & minor, blues, whole tone, diminished, chromatic, Hungarian
  minor, Japanese In Sen, Arabic) in all 12 keys, drawn across up to 24 frets.
- **Play back the scale** — plays a proper ascending run in the chosen key and
  highlights each note as it sounds. Choose how far it runs: **1, 2 or 3 octaves**.
  When a run leaves a single hand position, Scalien shifts position up the neck, so
  multi-octave and position-changing shapes play correctly.
- **Start position** — choose which of the five root positions (root on the 6th, 5th,
  4th, 3rd or 2nd string) the run begins from.
- **Repeat Scale** — loop the run for hands-free practice.
- **Octave filter** — show only the octaves you care about.
- **Chords** — 25 chord types with inversions and multiple voicings; play, strum or
  arpeggiate.
- **Modes** — explore all seven modes of any parent scale.
- **Metronome** — built in, with an accent on the downbeat.
- **Theme colours** — cycle the accent colour from the header; your choice is remembered.
- **Theremin** — double-click the Scalien logo to turn it into a theremin (move the
  pointer: left–right for pitch, up–down for volume); single-click to stop.

## For teachers

Point a student at the fretboard and press Play — the note lights up as it sounds, so
you can show exactly where a phrase sits on the neck. Every setting lives in the URL,
so sharing the link shares the exact key, scale and octave range.

## Reporting bugs

Click **Report Bugs** in the app header to open a pre-filled GitHub issue, or open one at
https://github.com/Articulate-English/scalien/issues

## Run locally

It is a single static file with no build step and no dependencies.

- Open `index.html` in a browser, or
- serve it: `python -m http.server --bind 127.0.0.1 8000`

## Tech

Plain HTML / CSS / JavaScript. Sound is generated with the Web Audio API. Notes use
standard tuning (E A D G B E, low to high).
