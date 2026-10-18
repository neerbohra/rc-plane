# Foam-board RC plane

A small electric RC plane, sized with hand calculations, with its airfoil checked in CFD, designed in Fusion, and carrying my telemetry logger as a flight recorder.

**Status:** planned for winter break (Dec 2026 - Jan 2027)
**Skills:** aircraft sizing (lift equation, weight budget, centre of gravity), 2D airfoil CFD, Fusion, RC electronics (brushless motor, ESC, servos, radio), build and test

---

## Design targets

| Target | Value |
|---|---|
| All-up weight | under 250 g (no FAA registration or Remote ID needed) |
| Cruise speed | about 8 m/s |
| Wing area | from L = 1/2 rho V^2 S C_L (first estimate about 0.10 m^2) |
| Centre of gravity | about 25-30% of the chord from the leading edge |

## Hand calculations

Show the weight budget table, the wing-area calculation and the Reynolds number here (or link `analysis/`).

## Airfoil CFD

| Angle of attack | C_L (my CFD) | C_L (published) | C_D (my CFD) |
|---|---|---|---|
| 0 deg | | | |
| 2 deg | | | |
| 4 deg | | | |
| 6 deg | | | |
| 8 deg | | | |

Plot: lift curve (C_L vs angle), mine against published data.

## Final specs

| Spec | Value |
|---|---|
| Span | |
| Chord | |
| Wing area | |
| Weight (ready to fly) | |
| CG position | |

## Testing

Glide tests only outside the DC no-fly zone (model aircraft are banned within 15 miles of Reagan National). Powered flights at a club field.

| Date | Test | Result | Change made |
|---|---|---|---|
| | | | |

## Folder layout

```
cad/        Fusion exports: STEP, STL (motor mount, logger bay), 1:1 foam templates (PDF)
cfd/        Airfoil setup notes, SimScale link, results CSV
analysis/   Hand calcs, logger data analysis
images/     Renders, build photos, CFD images
docs/       One-page write-up (PDF)
```

## Milestones

- [ ] FAA TRUST test
- [ ] Hand calcs: weight budget, wing area, CG
- [ ] Airfoil CFD vs published data, lift curve
- [ ] CAD: fuselage, wing, tail, foam templates
- [ ] Build: wing, fuselage, tail, motor, servos, radio
- [ ] Logger mounted and bench tested
- [ ] Weight and CG checked
- [ ] Glide tests
- [ ] Write-up + video
