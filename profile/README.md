# FRCLib Group

An organization dedicated to developing FRCLib and associated projects

## Intro

Yes another one, the 8 gajillionth Rust in FRC project. This project throws no shade at [prior](https://github.com/first-rust-competition) or [current](https://github.com/JaciBrunning/robot.rs) art.
I started this project because I wanted to learn more about Rust. This project stands on the shoulders of giants, those being the WPILib developers, a majority of
they directly inspire the code in this project.

## Getting Some Things Out Of The Way

- This is atrocious PPH (points per hour, a metric for work efficiency [thanks Joey \]).
- I am not pushing for WPILib to support Rust, I am not asking the average high school student to learn Rust.
- This project will not claim to be better than WPILib because it's in Rust, as [we have seen](https://www.phoronix.com/news/Rust-Linux-Maintainer-Step-Down) Rust usage in an established ecosystem can get very emotionally charged.

## Goal
A variant of each part of the robot stack should be implemented in as much pure rust as possible.

## Subproject

### Dashboard Development Kit aka DDK

A set of [Tauri Plugins](https://tauri.app/v1/guides/features/plugin/) that implement things teams may want in their custom dashboards.
Such as:
- NT4 client
- Datalog reader
- Datalog downloader
- WSSim interface
- Driverstation data

This could pair with [FRC Web Components](https://github.com/frc-web-components/frc-web-components) to make custom dashboards on the level of rookie projects
