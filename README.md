<div align="center">

# Yiwen Shi

**Embodied AI · Robot Learning · Robotics Software**

*XR Teleoperation · Humanoid Manipulation · Embodied Navigation*

I build robot systems and reproducible experiments at the intersection of **perception, control, and learning**.

[Explore my projects](https://github.com/415Aurora?tab=repositories) · [GitHub profile](https://github.com/415Aurora)

</div>

---

## About

I have an academic background in **Intelligent Construction** and focus on **embodied intelligence and robotics**. My work spans humanoid robot teleoperation, robot control and simulation, and the evaluation of multimodal decision-making systems.

I am particularly interested in **robot learning / VLA**, **learning from demonstrations**, **embodied navigation**, and building reliable robotics research infrastructure.

## Featured Projects

### 01 · [Grasp-XR-Teleop](https://github.com/415Aurora/Grasp-XR-Teleop)
**Humanoid teleoperation · Manipulation demonstrations · Simulation**

An experimental tool-manipulation workflow based on Unitree's XR teleoperation ecosystem, combining humanoid teleoperation with structured trial execution and data recording.

- Standardized task definitions, episode/trial organization and experiment-summary tooling.
- Wrench grasp-and-transfer task in the Isaac-based simulation setup, with a specified target zone and success criterion.
- Explicit separation of project-specific extensions from [Unitree's upstream `xr_teleoperate`](https://github.com/unitreerobotics/xr_teleoperate).

**Explore:** [Project overview](https://github.com/415Aurora/Grasp-XR-Teleop#readme) · [Experiment workflow](https://github.com/415Aurora/Grasp-XR-Teleop/tree/main/docs/graduation_design)

### 02 · [RoboNeck-AVP](https://github.com/415Aurora/RoboNeck-AVP)
**XR pose retargeting · Real-time control design · Hardware integration**

A Python application that maps Apple Vision Pro head orientation to a dual-axis Dynamixel robotic neck.

- Yaw/pitch retargeting, calibration, deadzones, soft limits, and constrained commands.
- Input freshness, readiness and safe HOLD/FAULT behavior.
- PyQt6 operator console, diagnostics and a mock-hardware testing path.

**Explore:** [Control architecture and setup](https://github.com/415Aurora/RoboNeck-AVP#readme) · [Regression tests](https://github.com/415Aurora/RoboNeck-AVP/tree/main/tests)

### 03 · [jev-navi](https://github.com/415Aurora/jev-navi)
**Embodied navigation · Multimodal decision models · Evaluation**

A research testbed for investigating frozen multimodal decision models in closed-loop, language-conditioned local navigation using Habitat.

- Model action-proposal adapters, short RGB/action histories and a metric-depth safety layer.
- Reproducible task manifests, episode logging, offline replay and failure analysis.
- Preliminary real-model pilots and diagnostics, **not** a validated full VLN-CE benchmark or a claimed successful navigation policy.

**Explore:** [Research summary](https://github.com/415Aurora/jev-navi#readme) · [Research protocol](https://github.com/415Aurora/jev-navi/blob/main/docs/research_protocol.md) · [Pilot diagnostics](https://github.com/415Aurora/jev-navi/blob/main/docs/startlux_pilot_2026-10-27.md)

### 04 · [ur5-control-lab](https://github.com/415Aurora/ur5-control-lab)
**ROS · MoveIt · Gazebo · Robot motion planning**

A UR5 simulation and control lab with a graphical operator interface, planning execution and structured experiment exports.

- ROS Noetic / Gazebo and MoveIt integration, including Cartesian pose targets.
- Runtime and trajectory metrics exported as CSV/JSON.
- Docker/local launch scripts and software regression tests.

**Explore:** [Setup and architecture](https://github.com/415Aurora/ur5-control-lab#readme)

## Technical Toolkit

| Area | Tools and topics |
| --- | --- |
| **Robotics** | ROS / ROS 2, MoveIt, Gazebo, robot kinematics and control |
| **Simulation & evaluation** | Isaac Sim / Isaac Lab, Habitat, scenario configuration, trajectory analysis |
| **Embodied AI** | Imitation learning, VLA research, multimodal decision models, evaluation protocols |
| **Hardware & sensing** | Unitree G1, Apple Vision Pro, Dynamixel, depth and stereo perception |
| **Development** | Python, Docker, Git, pytest, experiment automation |

## How I Approach Research Engineering

1. **Make the system run:** establish clear interfaces between sensors, control services, robot execution and simulators.
2. **Make experiments comparable:** freeze configs, define success criteria, log trajectories and failure modes.
3. **Make claims verifiable:** distinguish software smoke tests from real-model results, simulation from hardware, and upstream capabilities from new contributions.
4. **Make work reproducible:** document dependencies, test paths, evaluation scripts and known limitations.

## Other Projects

- [OpenGlasses](https://github.com/415Aurora/OpenGlasses) — smart-glasses prototyping, camera transport and multimodal interaction.
- [SteelMind](https://github.com/415Aurora/SteelMind) — tool-driven engineering workflows with deterministic analysis and document generation.

---

<div align="center">

**Interested in robotics research, embodied AI, and research engineering collaborations.**

[GitHub](https://github.com/415Aurora) · [Repositories](https://github.com/415Aurora?tab=repositories)

</div>
