# INFERNO

**A fire drill you can fail.**

A real fire drill is theatre. Everyone ambles out, nobody fails, nothing is measured, and the muscle memory it builds is a slow walk toward the nearest door, which is sometimes the wrong one. INFERNO puts the drill in VR, on a real building model, and grades the run against the building's actual evacuation protocol. You do not pass by reaching the exit. You pass by getting there the right way.

Built at Yantra Central Hack 2025 at VIT. **Won Best UI/UX.**

## What it does

- **Scored against the real protocol.** Route, timing and efficiency, not a completion tick. Two people can both survive and score worlds apart.
- **Haptics only where they teach.** A door handle that is hot before you open it, rising heat that tells you to stay low. Feeling the wrong choice is what makes the right one automatic under stress.
- **A working fire extinguisher,** so the correct response to a small fire is something you do rather than something you are told.
- **Hand tracking and room-scale locomotion,** so moving through a burning building uses your hands and your feet rather than a menu.

## My part

This was a team build. I worked on the **XR interaction layer**: the XR Origin, locomotion, hand tracking and the hand animations, the fire extinguisher mechanic, and the scene setup those run in. The commit history is intact if you want to see exactly what landed where.

Built with **[Ashwani Kumar Moudgil](https://github.com/Ashwani1330)**, **Raghav Sharma** and **Rajan Hasija** under [ISTE-VIT](https://github.com/ISTE-VIT). This repository is my fork of the team's.

## Stack

Unity · C# · XR Interaction Toolkit · XR Hands · Blender for the models.

## Running it

Open in Unity with the XR Interaction Toolkit and XR Hands packages installed, then build to a standalone headset. Developed against Meta Quest.

---

Part of a run of immersive work: [VRChemLab](https://github.com/Bhargs24/VRChemLab) (Best AR/VR Project, VIT 2025) and [Xposure](https://github.com/Bhargs24/Xposure).
