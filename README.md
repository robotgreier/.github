# SPIKE

**R-STDP-Based Biomimetic Robot Navigation: A System-Level Energy and Latency Analysis**

SPIKE is an autonomous taskbot that locates, picks up, and delivers objects using a spiking neural network (SNN) with reward-modulated spike-timing-dependent plasticity (R-STDP). The same network runs either as Python software on a Raspberry Pi 4 or as SystemVerilog hardware on an Arty A7-100T FPGA, so that latency and energy can be compared at both inference and system level.

## Repositories

| Repository | Content |
|---|---|
| [ros2](https://github.com/robotgreier/ros2) | ROS 2 Jazzy workspace for the taskbot: sensing, spike encoding, reward, motor control, power logging |
| [python_neural_network](https://github.com/robotgreier/python_neural_network) | Python SNN software emulation and hyperparameter tuning |
| [fpga_project](https://github.com/robotgreier/fpga_project) | SystemVerilog SNN implementation for the Arty A7-100T (Vivado) |

## Publications

- E. Holm, H. Torkildsen, G. J. Arason, J. K. Dall, B. Nossum, and A. Muhtaroglu, "R-STDP-Based Biomimetic Robot Navigation: A System-Level Energy and Latency Analysis," submitted to *Biomimetics* (MDPI), 2026.
- E. Holm, H. Torkildsen, G. J. Arason, J. K. Dall, B. Nossum, and A. Muhtaroglu, "SPIKE: An Energy-Aware Autonomous Taskbot with Real-Time Navigation Control using a Low-Cost FPGA-Based Spiking Neural Network," accepted for the International Conference on Control, Robotics Engineering and Technology (CRET 2026).

Developed as a bachelor project at Oslo Metropolitan University (OsloMet) in collaboration with SINTEF Digital.
