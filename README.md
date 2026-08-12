# Game Design for Myanmar

A 2D Unity game raising awareness of the humanitarian crisis following Myanmar's
2021 military coup, developed through Bridgewater State University's Adrian Tinsley
Program (ATP) summer research program under the mentorship of Dr. Paul Kim.

## Overview

The project explores how serious games can communicate complex sociopolitical
issues that traditional media struggles to convey. Players take on the role of a
peaceful protester navigating day and night phases modeled on real civil
disobedience practices in Myanmar, including evading patrolling soldiers,
managing limited health, and rescuing detained political prisoners.

## Key Features

- Day/night gameplay cycle referencing the real-world practice of nightly pot-banging
  protests during curfew hours
- Patrolling soldier AI conveying the risk faced by real protesters
- A prison-key rescue mechanic for freeing detained non-player characters
- Dialogue system letting players hear detained characters' stories
- Health/lives system balancing challenge with player empowerment

## Technical Implementation

- **Engine:** Unity, C#
- **Sprites:** created in Krita, animated using Unity's animation recording feature
- **Player movement:** custom Player Script (MonoBehaviour, Rigidbody2D, Animator)
  handling arrow-key input, animation state, and physics-based movement
- **Day/night lighting:** Universal Render Pipeline (URP), simulating a 24-hour
  lighting cycle
- **Scene boundaries:** tilemap colliders
- **Dialogue:** custom Dialogue Manager script controlling NPC conversation timing

## About This Repository

The original source code from the 2023 build was not preserved. This repository
documents the project through the accompanying research paper and presentation
poster, which cover the full methodology, technical approach, related work, and
reflections.

## Files

- `Kyi_ATP_2023_Paper.pdf` — full research paper: abstract, methodology, related
  work, technical implementation, and reflections
- `Kyi_ATP_2023_Poster.pdf` — presentation poster

## Author

May Zar Kyi — Bridgewater State University, Adrian Tinsley Program, 2023
