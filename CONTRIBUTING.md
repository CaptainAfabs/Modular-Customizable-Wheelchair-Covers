# Contributing

Thanks for thinking about contributing. This project is open because more eyes and more printers make it better and safer for everyone who needs it. A few notes on how I'd love help.

## The kinds of contribution I most want

- **Fit reports.** "I installed this on a [model of chair] / [wheel diameter], here's what worked and what didn't." File these as an issue with the `fit-report` label. This is the single most useful thing for future users.
- **Pattern packs.** STL files, decals, paint guides for themed sets (sports teams, flags, holidays, school colours). PR these into a `community-patterns/` folder.
- **Translations.** Especially of [`docs/ASSEMBLY.md`](docs/ASSEMBLY.md) and [`docs/INSTALLATION.md`](docs/INSTALLATION.md). PR a `docs/<lang>/ASSEMBLY.md` and link it from the main README.
- **Photos of yours installed.** Open a "Show & Tell" issue. Helps other users see what's possible. **Please don't post identifying photos of someone else without their consent**, especially minors and people with disabilities.
- **Bug reports / hazard reports.** If something breaks, snags, or fails under load, *please* file an issue. Safety beats reputation.

## What needs care

- **Scope changes to the segment geometry.** The current geometry is what's covered by the patent and what I've actually tested on a real chair. Substantial changes to the seam profile or attachment pattern are welcome as a fork; merging them back here means I'll want to know they've been tested on at least one real wheelchair, not just CAD-verified.
- **Adding non-open dependencies.** Source files should open in tools that are free for personal use (Fusion 360 Personal, FreeCAD, OpenSCAD, etc.). Don't introduce a hard dependency on a paid CAD package.
- **License compatibility.** This repo is CERN-OHL-S v2. PRs need to be under a compatible licence (CERN-OHL-S, OHL-W, CC0, public domain, or your own contribution under CERN-OHL-S).

## How to PR

1. Fork.
2. Branch.
3. Make your change.
4. **If you changed CAD or STL: print one and verify it physically.** Photos in the PR.
5. PR with a description of what changed and why.

## Code of conduct

The short version: this project exists to help people with disabilities. Don't be the reason someone is uncomfortable contributing. Don't make it weird. Be kind, give people the benefit of the doubt, and remember that not everyone reading this is an experienced maker.

If something feels off, please open a [Discussion](https://github.com/CaptainAfabs/Modular-Customizable-Wheelchair-Covers/discussions) or a private security advisory through the repo's Security tab — I'd rather hear about it there than not at all.

## Credit

Contributors who add a tested fit report, a translation, or a meaningfully-used pattern get a line in a `CONTRIBUTORS.md` (which I'll create the moment there's a name to put in it). PRs welcome on that file too.

— Adam
