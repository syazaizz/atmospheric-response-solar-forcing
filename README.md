# atmospheric-response-solar-forcing

# Atmospheric Sensitivity to Solar Forcing

Climate Modelling Project using SpeedyWeather.jl - To study atmospheric sensitivity to solar forcing

# Project Overview

This project investigates how small variations in solar radiation influence Earth’s atmospheric temperature and climate response. Using a global circulation model, controlled numerical experiments were performed to quantify the relationship between solar forcing and atmospheric temperature change, and to estimate climate sensitivity.

# Motivation

Understanding the connection between solar variability and Earth’s climate requires tracing a full physical chain from space to atmosphere:

**1. Solar Activity**
Variations in solar output and magnetic activity (e.g., solar cycles)

**2. Solar Wind & Heliosphere**
Solar wind shapes the heliosphere and modulates the interplanetary magnetic field

**3. Galactic Cosmic Rays**
The heliosphere controls the flux of cosmic rays entering Earth’s atmosphere

**4. Atmospheric Ionisation & Cloud Processes**
Cosmic rays may influence ionisation and cloud formation mechanisms

**5. Climate Response (Focus of this project)**
Changes in radiative forcing affect atmospheric temperature and circulation

-- This project focuses on the final stage of this chain:
how changes in solar radiation translate into atmospheric temperature response

# Scientific Objective
- Simulate Earth’s atmosphere under baseline solar conditions
- Introduce a controlled perturbation in solar forcing
- Quantify the resulting temperature response (ΔT)
- Compute climate sensitivity:
  $$𝜆 = {Δ𝑇\over Δ𝑆}$$

# Tools & Model
Climate model: SpeedyWeather.jl

- Documentation:
https://speedyweather.github.io/SpeedyWeatherDocumentation/dev/

# Future Work
- Incorporate time-dependent solar forcing
- Couple with cosmic ray modulation models
- Extend toward full Sun–Earth system modelling
- Improve radiative transfer and feedback representation​

