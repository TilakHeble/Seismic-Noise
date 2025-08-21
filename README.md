# Quantifying Wind-Turbine–Induced Seismic Noise (EKA–WS12)

Generalised Additive Modelling (GAM) of turbine uplift in the 0.5–8 Hz band
Eskdalemuir Seismic Array (EKA), borehole WS12 — Scotland, UK

Overview

This repo contains the analysis, code, and figures for assessing turbine-attributed uplift in seismic energy near EKA. We pre-process vertical velocity to frequency space, apply a Frequency-Domain Weighting Function (FDWF) to emphasise 0.5–8 Hz, integrate to a scalar energy metric, aggregate to 10-min windows, and fit a GAM with:

1. operational status (on/off),

2. smooth wind speed and speed × operational interaction,

3. cyclic wind direction smooth,

4. day-level random effect.

Key result. Turbine operation produces a detectable uplift (~20%) in the weighted energy metric, strongest for south-westerly winds (≈130–150°). RMS displacement during operation peaks at 0.177 nm, well below the 0.336 nm compliance limit → no current compliance risk.
