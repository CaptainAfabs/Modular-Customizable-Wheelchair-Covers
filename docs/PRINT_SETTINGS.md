# Print settings

These are the settings I use on my own printer for my aunt's chair. They are tuned for **strength against impact and finger force**, not for speed. If you want to deviate, the only setting I'd strongly warn against changing is the wall count.

## Filament

| Use case | Recommended | Notes |
|---|---|---|
| Indoor / cool-weather outdoor (< ~60 °C) | **PETG** | First choice. Tough, UV-stable enough for daily outdoor use, doesn't shatter. |
| Hot weather, in-car storage, hot climates (< ~95 °C) | **ABS** or **ASA** | Higher heat tolerance. ASA is more UV-stable than ABS. |
| Maximum toughness (rough usage) | **PA (nylon)** or **PC** | Overkill for most users; expensive; harder to print. |
| Budget / first prototype only | PLA | **Not recommended for long-term use.** It will creep in heat and can shatter on hand impact. Use only to verify fit. |

A spool of 1 kg PETG (~$20 USD in mid-2026) is enough for **two full wheels plus spares**.

## Slicer settings

Best results in Bambu Studio, OrcaSlicer, PrusaSlicer, or Cura with the following:

| Setting | Value | Why |
|---|---|---|
| Nozzle | **0.4 mm** (hardened steel preferred) | Standard; hardened resists abrasion if you ever print with glass-filled filament. |
| Layer height | **0.20 mm** | Speed/strength sweet spot. 0.16 mm is fine if you have time. |
| Walls / perimeters | **6** | **Do not reduce this.** Walls do almost all the impact resistance for this part. |
| Top / bottom layers | 4 / 4 | Smooth surface, good visual finish for paint. |
| Infill | **5 % gyroid** | The walls are doing the structural work; infill is just there to prevent the top from sagging. |
| Wall line width | 0.4 mm (default) per loop | Matches nozzle exactly so loops bond cleanly. |
| Z seam | Random or Aligned-back | Random hides better on coloured prints. |
| Ironing | On (top layer only) | Optional, but gives a smoother finish for paint or decals. |
| Supports | Tree, ~30° overhang threshold | Only required around the zip-tie apertures on some slicers. |
| Build plate | PEI or textured powder-coated | No brim, no raft. |
| Brim / raft | None | Part has plenty of bed contact. |
| Nozzle / bed temp | Per filament spec | PETG: ~240 °C / 80 °C. ABS: ~250 °C / 100 °C, enclosure recommended. |

## Print orientation

Print the segment **flat on the bed** (top face up, large face down). This gives:
- Strongest layer adhesion in the direction the cover takes finger impact.
- Cleanest aesthetic top surface for paint or vinyl wrap.
- No supports needed for the seam features.

## How many to print

| You need | Segments to print |
|---|---|
| One wheel covered | 8 |
| Both wheels covered (typical) | 16 |
| A full set with one spare | 17 |
| A full set with one spare per wheel | 18 |

## Print time

On a Bambu P1S / X1C at default PETG profile with these settings, one segment is **about 1 hour 20 minutes**. A full 8-segment wheel set is **roughly 10–11 hours** — comfortably an overnight print.

You can fit **2 segments per build plate** on a 256 mm × 256 mm bed, 3 on some larger printers. Don't try to nest more than that; the segments don't pack efficiently because of the radial geometry.

## Print quality check

Before assembly, look at each segment for:

1. **Clean tongue and groove edges.** No stringing, no elephant-foot blob on the bottom. The tongue should slide into the groove on an adjacent segment with light pressure; if it doesn't fit, sand it lightly along the layer lines.
2. **No clogged apertures.** Every zip-tie hole should be open all the way through. Punch out any film with a 4 mm drill bit or the tip of a flush cutter.
3. **No delamination.** Flex the segment with both hands. If layers separate, your bed temperature was too low or the filament is wet — dry it and reprint.

## Wheel diameter compatibility

The provided STL is sized for the most common manual wheelchair drive wheel (**24 inch / 610 mm**). If your aunt/parent/friend uses a different wheel size:

- **22" or 25"** — use the F3D source file and scale the assembly uniformly. The aperture pattern will still line up with most spoke configurations.
- **20" sport / kids' chair** — scale to 0.85×; check the central aperture clears the hub.
- **26"** — scale to 1.08×; verify your printer can still fit the larger segment.

If you don't have Fusion 360, **the free [Fusion 360 Personal Use license](https://www.autodesk.com/products/fusion-360/personal)** is sufficient to open and modify the source file.
