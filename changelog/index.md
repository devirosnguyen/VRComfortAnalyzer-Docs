---
title: Changelog
---

# Changelog

[Home](../) · [Manual](../manual/)

## 0.9.0 (pre-release)
First version for testing. Requires Playtest Replay & Heatmaps 1.1.
- VR Comfort Probe: per-frame artificial vs physical motion, 100 ms windows stored in the session file, snap turns,
  teleports, scene loads and exclusions as events, frame drops against the display refresh rate; rig detection for
  XR Origin, OVRCameraRig and custom rigs; no allocations per frame.
- Analysis: threshold presets with sources, exposure bands, low-frequency (0.1–0.5 Hz) reference indicator, Comfort Risk
  Index, suggested rating with reasons; several sessions combined.
- Editor: "Comfort risk" heatmap kind, comfort row under the Replay timeline, VR Comfort window, HTML/CSV report with
  moments to review.
- Optional in-game Fast Motion Sickness (FMS) prompt.
- Sample: comfort sample scene with an autopilot (teleport / gentle / fast profiles), lift, bobbing deck, ramp, and three
  recorded sessions.
- Not yet validated on a Meta Quest device.
