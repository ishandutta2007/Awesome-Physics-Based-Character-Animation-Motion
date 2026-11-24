# Awesome-Physics-Based-Character-Animation-Motion

## Top Physics-Based Character Animation & Motion Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Physics-Driven Keyframing, AI Motion Capture, Neural Motion Synthesis, Reinforcement Learning Locomotion & Rigging*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Physics-Based Character Animation & Motion**. These tools enable game animators, VFX artists, and robotics researchers to generate physically plausible character motion, extract 3D skeletal mocap from monocular video, train reinforcement-learning locomotion controllers (DeepMimic / AMP), and retarget animations across rigs.



**Examples** include Cascadeur, Mixamo, Rokoko Studio, DeepMotion, Move.ai, Plask, RADiCAL, Kinetix, Wonder Dynamics, Anyworld, and `NVlabs/motionbricks` (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for physics-based character controllers, neural motion synthesis, markerless video-to-mocap pipelines, and Blender rigging/retargeting tools — ideal for 3D character animators, technical artists, game developers, and embodied AI researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cascadeur](https://cascadeur.com)**  

  Standalone AI-assisted keyframe animation software utilizing rigid-body physics, center-of-mass trajectories, and auto-posing to create realistic character action.



- **[Adobe Mixamo](https://mixamo.com)**  

  Cloud-based automatic 3D humanoid character rigging and curated motion-capture animation library with instant FBX/Collada export.



- **[Rokoko Studio & Vision](https://rokoko.com)**  

  Cloud-connected motion capture platform combining inertial suit streaming with AI-powered single-camera video-to-animation extraction.



- **[DeepMotion (Animate 3D & SayMotion)](https://deepmotion.com)**  

  Cloud AI motion capture and text-to-motion generation platform featuring physics-simulated foot-ground contact and full-body tracking.



- **[Move.ai](https://move.ai)**  

  Markerless cloud motion capture platform extracting high-fidelity multi-person 3D skeletal animations from standard smartphone and multi-camera video.



- **[Plask](https://plask.ai)**  

  Browser-based AI motion capture and 3D animation studio allowing creators to extract, edit, and retarget mocap directly in the cloud.



- **[RADiCAL (RADiCAL Studio)](https://radicalmotion.com)**  

  Cloud-native real-time 3D motion capture and AI character animation platform streaming live skeletal data into Unreal Engine, Unity, and Blender.



- **[Kinetix](https://kinetix.tech)**  

  No-code cloud AI emote and 3D character animation platform enabling user-generated motion assets for games and virtual worlds.



- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  

  Cloud AI VFX platform that automatically animates, lights, and composes CG characters into live-action footage from a single camera feed.



- **[Anyworld](https://anyworld.ai)**  

  Generative AI platform creating interactive, physics-aware 3D characters, behaviors, and animated environments for games and virtual spaces.





## Open-Source GitHub Projects



- **[NVlabs/motionbricks](https://github.com)**  

  Open-source modular motion generation and physics-aware character animation framework from NVIDIA Research for composable 3D human motion synthesis.



- **[ProtoMotions (NVIDIA / Simon Fraser University)](https://github.com)**  

  Open-source GPU-accelerated simulation and reinforcement learning framework for training physically simulated humanoids and animated characters (DeepMimic, AMP, PHC, MaskedMimic).



- **[IsaacGymEnvs / Isaac Lab Character Locomotion](https://github.com)**  

  Open-source GPU-parallelized physics framework powering Adversarial Motion Priors (AMP) and physically simulated character control at thousands of FPS.



- **[DeepMimic](https://github.com)**  

  Foundational open-source physics-based character animation framework using deep reinforcement learning to imitate reference mocap clips with physical balance.



- **[CALM & ASE (Adversarial Skill Embeddings — NVIDIA)](https://github.com)**  

  Open-source frameworks for learning reusable, physically simulated motor skill latent spaces that can be directed interactively for complex character behaviors.



- **[Motion Diffusion Model (MDM)](https://github.com)**  

  Pioneering open-source diffusion model generating diverse, physically coherent 3D human motion sequences from natural language prompts and action labels.



- **[MotionGPT](https://github.com)**  

  Open-source unified motion-language model treating 3D human motion as a discrete token language for text-to-motion, motion-to-text, and motion completion.



- **[SMPL / SMPL-X & HumanML3D Ecosystem](https://github.com)**  

  Standard open-source parametric 3D human body, face, and hand models underlying modern neural motion capture and physics-based character pipelines.



- **[4D-Humans (HMR 2.0)](https://github.com)**  

  Open-source transformer-based 3D human mesh recovery and tracking pipeline reconstructing full-body 3D motion from monocular in-the-wild video.



- **[WHAM (World-grounded Humans with Accurate Motion)](https://github.com)**  

  Open-source video-to-3D-mocap framework recovering accurate global world-space trajectories and foot-ground contacts from moving cameras.



- **[FreeMoCap](https://github.com)**  

  Free, open-source hardware-agnostic multi-camera markerless motion capture system built for animators, biomechanics researchers, and indie studios.



- **[OpenCap (Stanford Neuromuscular Biomechanics Lab)](https://github.com)**  

  Open-source web and mobile multi-camera 3D human movement and musculoskeletal dynamics estimation pipeline using smartphones.



- **[MediaPipe Pose & Holistic (Google)](https://github.com)**  

  Lightweight, real-time open-source pose and hand landmark tracking framework widely used to drive live VTuber and 3D character rigs.



- **[Rigify (Blender Foundation)](https://github.com)**  

  Built-in open-source modular character rigging system in Blender generating full IK/FK animation controls for bipeds, quadrupeds, and custom creatures.



- **[Auto-Rig / Rokoko Studio Live & ExpyKit for Blender](https://github.com)**  

  Open-source Blender add-on suite for retargeting Mixamo, Rokoko, BVH, and mocap animations seamlessly onto Rigify and game-engine armatures.



- **[Ragdoll / Active Ragdoll Physics Controllers (Unity & Godot)](https://github.com)**  

  Open-source spring-damper and PD-controller active ragdoll setups enabling physical balance, hit reactions, and procedural locomotion in real-time engines.



- **[Ozz-animation](https://github.com)**  

  Ultra-fast, cache-friendly open-source C++ runtime skeletal animation library supporting blending, additive layers, two-bone IK, and multithreading.



### Additional Strong Open-Source Options



- **[UniRig (VAST-AI / Tsinghua)](https://github.com)** for open-source AI automatic skeleton prediction and skinning-weight generation for arbitrary 3D meshes.

- **[ActorCore / CMU & AMASS Mocap Datasets](https://mpg.de)** for massive open-access unified 3D human motion capture datasets formatted in SMPL.

- **[MMHuman3D (OpenMMLab)](https://github.com)** for a comprehensive open-source PyTorch codebase covering 3D human pose estimation, parametric body recovery, and visualization.

- **[KalidoKit](https://github.com)** for lightweight browser-based 3D kinematic solver mapping MediaPipe pose/face/hand data onto VRM avatars.

- Many community **Blender physical ragdoll/jiggle-bone add-ons**, **BVH motion-blending utilities**, and **Unreal/Godot motion-matching plugins**.



**Frameworks for building custom systems**: Combine **WHAM / FreeMoCap**, **NVlabs/motionbricks**, **ProtoMotions / DeepMimic**, and **Blender + ExpyKit** with **Ozz-animation** for end-to-end, physics-grounded 3D character animation pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Parametric body models (e.g., SMPL/SMPL-X) and motion capture datasets (e.g., AMASS) are often released under academic or non-commercial research licenses; verify commercial game/film licensing terms before shipping derived assets.

- Markerless video-to-mocap pipelines frequently require foot-skate cleanup and ground-plane contact constraints in Blender or Cascadeur for production-grade animation.



---



**Made for 3D character animators, technical artists, game developers, and embodied AI researchers.**  

Let's make physics-based character animation and motion synthesis faster, lifelike, and open.
