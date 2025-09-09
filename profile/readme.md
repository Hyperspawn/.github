<img src="https://github.com/Hyperspawn/.github/blob/main/profile/images/Hyperspawn.png" width="192px">

# Hyperspawn

Hyperspawn is an open-source project that aims to develop humanoid robots that mimic human actions accurately and act as proxy avatars for users to control from anywhere in the world. Our solution combines immersive virtual reality (VR) and teleoperation to enable seamless interaction between humans and their robotic avatars.
# Hyperspawn Robotics · Organization Index

**Embodied AI for everyone.** We build open-source humanoid robots and the software to control them — simulation, RL, and teleoperation — so anyone can replicate, study, and push the field forward.

---

## Stack

> These components live in dedicated repos (some private while we stabilize). They’re referenced from **Dropbear** and will be opened as they mature.

- **dropbear_urdf** — URDF/Xacro and meshes for ROS 2 pipelines and downstream simulators.  
- **dropbear_ros** — ROS 2 packages: controllers, joint publishers, teleop nodes, RViz setups.  
- **dropbear_gazebo** — SDF world + plugins + control-bindings for Gazebo.  
- **dropbear_mjcf** — MuJoCo model for MJCF-based stacks and Isaac import.  
- **dropbear_rviz** — RViz presets and visualization tooling.  
- **dropbear_printables** — 3MF plates, STLs, and print guides per subassembly.  
- **dropbear_hardware** — CAD (STEP/FBX/STL/USDC), exploded views, and subassembly trees.  
- **dropbear_electronics** — Schematics, PCBs, harnessing and wiring maps.  
- **dropbear_firmware** — ESP32-based motor control (CAN), sensor I/O, timing.  
- **dropbear_rl** — RL environments + baselines for locomotion & manipulation.  
- **dropbear_sim2real** — Calibration, state estimation alignment, and transfer tooling.  
- **dropbear_isaac** — USD assets + Isaac Sim/Lab workflows, validation scripts.  
- **actuator-testbench / opencycloid-hs / openqdd-hs / myactuator-can** — Open-source actuators and comparative tooling.  
- **hyperspawn_isaacstack** — Adapters/utilities for NVIDIA Isaac frameworks.  
- **llm-control** — Language + vision loop to trigger skills and motion primitives.


---

## Research pillars

### Reinforcement Learning
- Task suites for balance, walking, reaching, grasping.  
- Sim pipelines in MuJoCo and NVIDIA Isaac Lab; policy export hooks to ROS 2.  
- Goal: train in sim, deploy on robot with minimal friction (same joint naming/limits).

### Teleoperation
- **ROS bridge + Python SDK** for “do this” control: keyboard/joystick, or programmatic.  
- Full‑body teleop for debugging and data collection; record/relay trajectories for imitation learning.

### Simulation
- URDF→SDF→MJCF→USD conversion paths; consistent frames and units.  
- Isaac workflows with articulated USD, collision/visual mesh split, and CI validation.

### Hardware
- 3D‑printable frames, modular limbs, and open-source actuators (QDD/planetary/cycloidal).  
- Electronics stack with Jetson Orin + distributed microcontrollers over CAN.

---

## Community & Links

- Website: https://hyperspawn.co  
- Docs: https://www.hyperspawn.co/docs  
- Gallery: https://hyperspawn.co/gallery  
- Web Simulator: https://hyperspawn.co/sim  
- Buy Robot: https://hyperspawn.co/buy  
- Discord: https://discord.com/invite/tFeqrdJzkS  
- Telegram: https://t.me/fractionalrobots  

---

## Note from Maintainers: **[Priyanshu](https://github.com/Priyanshupareek) & [Cole](https://github.com/robit-man)**


You’re at the **assembly stage**, which means you’ve sourced your parts and probably spent a bunch of time and money on this project. To that, I love you for being here. I’ve never met you, but I like the way you think — we might be thinking alike in our tech bubble. Keep going, my guy.

We’re going to have smart robots do everything in the world — from production to abundance of resources for humanity, to a world where people are free from tasks they don’t truly enjoy doing. Even if it’s just sitting and watching, high UBI until the value of money shifts. Okay, I might’ve gone too meta, but peace out ✌️

**Building a humanoid robot is wild.** Only a few years separate us from accessible humanoids. What you’re doing now is pioneering. If you're here, you're part of something bigger.

---

### Contributing

Open an issue or PR on **Dropbear** to propose changes. Be kind, be specific, ship reproducibility.
