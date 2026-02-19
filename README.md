
# Boston Red Sox 2026 Pitching Staff Projection (R)

## Overview

This project builds a data-driven projection of the **Boston Red Sox 2026 Opening Day pitching staff** using R. The model selects:

* 5 Starting Pitchers
* 8 Relievers
* Remaining depth options

The goal is to simulate a front-office roster construction process using objective performance metrics.

---

## Model Approach

Two scoring systems were created:

**Starter Score**
0.45(IP) + 0.35(WAR) − 0.20(FIP)

* IP = durability
* WAR = total value
* FIP = run prevention

**Reliever Score**
0.45(Dominance) + 0.30(WAR) − 0.25(FIP)

* Dominance = K/9 − BB/9
* Emphasizes swing-and-miss ability

Pitchers are ranked by role and the top 13 are selected.

---

## Tools Used

* tidyverse
* gt
* R Markdown

---

## Outcome

A clean, front-office style pitching staff chart showing:

* Rotation
* Bullpen roles
* Non-roster pitchers

This project demonstrates how analytics can support roster construction and pitching role optimization.

---

**Adam Holtsmaster**
Baseball Analytics | R | Sports Data Science
