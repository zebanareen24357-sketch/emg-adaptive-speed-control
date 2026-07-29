# EMG-Based Adaptive Speed Control of Electric Drive

An adaptive speed control algorithm for electric drives that uses EMG (electromyography / muscle signal) input, designed as a computationally lightweight, real-time control method. Developed as an M.Tech mini-project, currently being extended toward hardware validation and publication.

## What it does

Uses EMG signals as a control input to adaptively adjust the speed response of an electric drive in real time — instead of relying on a fixed, pre-programmed control profile. The core contribution is a lightweight adaptive control algorithm that can respond to signal variation without heavy computational overhead, making it suitable for embedded/real-time implementation.

## How it works

- **Signal acquisition stage:** EMG signal is captured as the control input
- **Adaptive control stage:** A lightweight algorithm processes the signal and adjusts drive parameters in real time, without relying on a static lookup or fixed-gain controller
- **Drive response stage:** The electric drive's speed is adjusted based on the adaptive controller's output, with performance evaluated against standard control benchmarks

## Tech stack

Tinkercad (circuit simulation) · Arduino

## Demo

Built and simulated in Tinkercad.

<img width="1085" height="842" alt="image" src="https://github.com/user-attachments/assets/755c40d9-163d-4bc9-9800-8e190f43b5c1" /> 
## Results

## Documentation

Full dissertation report and seminar presentation are available in `docs/`.

[Project report.pdf](https://github.com/user-attachments/files/30519588/Project.report.pdf)
## What I'd improve next

- Validate the algorithm on real hardware using an actual EMG sensor (in progress)
- Benchmark against additional standard control methods for a stronger publication case
