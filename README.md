# Improvement-of-Autonomous-Drone-Gate-Navigation-2026-2027

# Improvement of Autonomous Drone Gate Navigation (COE/ELE 70A/B, 2026–2027)

Tello drone that detects a 4-marker ArUco gate, aligns with it, and flies through.
Goal: build a baseline, measure it, find weaknesses, improve, and re-test.

## Team
| Role | Name |
|---|---|
| A – Navigation & Control | Aadil Bholat |
| B – Gate Detection & CV | Anas Abdi |
| C – Performance Evaluation | Thomson Chan |
| D – Integration & Documentation | Raymond Cao Jiang |

## Setup
    pip install -r requirements.txt
    python src/tello_aruco_test.py

## Controls
t = takeoff, l = land, a = toggle auto mode, q = quit

## Repo layout
- `src/` – drone code (vision, controller, config)
- `experiments/` – test scripts and test-case definitions
- `docs/` – milestones, reports, diagrams
- `data/` – logs/results (large videos are NOT stored here, see below)
