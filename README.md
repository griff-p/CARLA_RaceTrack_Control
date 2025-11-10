# CARLA_RaceTrack_Control

This repository contains code, configurations, and documentation for running custom racetrack control experiments in the [CARLA simulator](https://carla.org/).  
It is part of the University of Toronto's **Introduction to Self-Driving Cars** course final project on Coursera, designed by **Steven Waslander**. See [course link](https://www.coursera.org/learn/intro-self-driving-cars?specialization=self-driving-cars) for details.

It is designed for reproducing specific environments and behaviors using the same CARLA build across platforms (Windows and Linux).

---

## Repository Contents

- **Link to Simulator Download** (preconfigured CARLA version + racetrack map)
- **Longitudinal Control using PID**
- **Lateral Control using Stanley Controller**

>  Note: The CARLA binaries and map assets are not stored in this repository due to file size limits.

---

## Simulator Setup

Download the preconfigured CARLA setup (matching this repository’s version):

**[CARLA Setup & Racetrack Files (Google Drive)](https://drive.google.com/drive/folders/1zFL3RP6L6ID2Spli8HwYcRu7Z-rKzJhy?usp=sharing)**

> Follow the included guides for both Linux and Windows installation instructions.
> Note: The simplest method is to setup a pyenv and you MUST use Python3.5 or 3.6 (I recommend 3.6, I could not get python3.5 to work)
