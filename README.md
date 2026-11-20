# Cluster 10CW Final Project

## Introduction: The Myth of Algorithmic Neutrality

Urban space today is neither neutral nor purely functional; it is a dynamic geography shaped by commercial hotspots, institutional infrastructure, and socio-spatial inequalities (Winner, 2017).

As a vital metric reflecting how efficiently a city is utilized, pedestrian footfall serves as a key indicator for:

- Commercial viability
- Public transit efficacy
- The vibrancy of public spaces (Gehl, 2011)

## The Problem with Traditional Frameworks

Traditional urban transport modeling often treats pedestrian movement purely as a function of independent variables—such as temporal cycles (peak hours) or localized features (proximity to community spaces).

> **The Critical Flaw:** These frameworks systematically fail to account for spatial dependency in natural geography, operating under the incorrect assumption that proximity to commercial services and public transit options are fully independent factors during calculations.

## Research Objective

This project investigates the extent to which spatial infrastructure factors—specifically proximity to public transit services—predict pedestrian footfall volume across urban networks, and evaluates whether accounting for spatial autocorrelation improves our understanding of public space utilization.

## Thesis

**I argue that traditional modeling methods (like Ordinary Least Squares regression) systematically misestimate pedestrian behavior due to ignored spatial dependencies (Sevtsuk, 2021).**

By implementing a Spatial Autoregressive (SAR) model, this study demonstrates that footfall is heavily bound to the conjoined effects of spatial proximity and structural transit infrastructure. Failing to account for this dependency underestimates structural barriers within urban planning, ultimately reinforcing models that favor high-yield commercial centers at the expense of marginalized, transit-dependent neighborhoods.

## Repository Contents

| File | Description |
| --- | --- |
| [`Cluster_10CW_Final_Project_(FINAL).ipynb`](Cluster_10CW_Final_Project_%28FINAL%29.ipynb) | Jupyter notebook containing the data processing, OLS baseline, and SAR model |
| `README.md` | Project overview |
