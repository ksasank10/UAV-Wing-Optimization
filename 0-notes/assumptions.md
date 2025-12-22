# Project Assumptions

Airfoils:
- NACA 4412 (baseline)
- Eppler E205 (low-Re optimized)
- Selig S5010 (modern UAV airfoil)

Flow Conditions:
- Reynolds number: 200,000
- Mach number: ~0 (incompressible)
- Angle of attack sweep: -2° to 12°
- Purpose: Compare efficiency, stall behavior, and robustness for small UAV wings

Solver Philosophy:
- XFOIL for baseline trends
- CFD for viscous effects and separation
- AVL for induced drag only

## Pre-CFD Predictions

- NACA 4412 is expected to have moderate Cl and gentle stall, but lower Cl/Cd at low Re.
- Eppler E205 should show the best Cl/Cd near cruise conditions due to low-Re optimization.
- Selig S5010 is expected to balance efficiency and robustness better than S1223-style airfoils, with reasonable pitching moment behavior.
