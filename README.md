<p align="center">
  <img src="jiafei.png" width="220">
</p>

<h1 align="center">SillySeams</h1>

<p align="center">
  <b>A high-precision wavtool for UTAU / OpenUtau</b>
</p>

<p align="center">
  WSOLA-based waveform alignment | S-curve morphing | Dynamic crossfade compensation
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-🦀-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square">
</p>

---

## ✨ What It Does

SillySeams is a wavtool designed for UTAU and OpenUtau that performs precise waveform alignment using WSOLA.

Instead of traditional linear crossfading, it applies:

- S-curve interpolation for smoother period morphing  
- Period-aware stitching (WSOLA phase-matching) 
- Dynamic compensation between crossfade points  

This results in more natural waveform continuity and reduced artifacts during note transitions.

> 🥀 Built-in search window is 15ms  
> Minor timing shifts may occur, though typically not noticeable...
