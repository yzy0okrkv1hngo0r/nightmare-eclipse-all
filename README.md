# nightmare-eclipse-all

This repository is an umbrella project that aggregates multiple standalone C/C++ components and submodules into a single codebase. It combines a number of named modules and Windows-oriented project folders under one root repository.

## Overview

The repository is primarily a collection of native code projects rather than a single app. Based on the repository metadata, the language composition is:

- C++: 50.2%
- C: 49.7%
- C#: 0.1%

## Included components

The repo includes the following modules and project folders:

- BlueHammer
- MiniPlasma
- RedSun
- YellowKey
- green-plasma
- un-defend
- BigDiskBuster
- BrokenArrow
- FalconFlank
- GreatXML
- GreenSection
- HardBreacher
- LegacyHive
- PrettyPrague
- RoguePlanet
- ShieldCrash
- ShieldBreak
- MSNightmare (contains several submodule-backed components)

## Repository layout

A representative structure is:

```text
nightmare-eclipse-all/
├── BlueHammer/
├── MiniPlasma/
├── RedSun/
├── YellowKey/
├── green-plasma/
├── un-defend/
├── MSNightmare/
│   ├── BigDiskBuster/
│   ├── BrokenArrow/
│   ├── FalconFlank/
│   ├── GreatXML/
│   ├── GreenSection/
│   ├── HardBreacher/
│   ├── LegacyHive/
│   ├── PrettyPrague/
│   ├── RoguePlanet/
│   ├── ShieldBreak/
│   └── ShieldCrash/
├── .gitmodules
├── .gitattributes
└── README.md
```

## Getting started

Clone the repository with submodules enabled:

```bash
git clone --recurse-submodules https://github.com/yzy0okrkv1hngo0r/nightmare-eclipse-all.git
cd nightmare-eclipse-all
```

If you already cloned it without the submodules, initialize them afterwards:

```bash
git submodule update --init --recursive
```

## Notes

- This is a multi-project repository rather than a single standalone program.
- Individual folders and submodules may have their own build requirements, dependencies, and licensing.
- Some components appear to be Windows-focused and may require Visual Studio or related tooling.

## License and usage

Because this repository is a collection of multiple projects, each component should be reviewed independently for its own license and build instructions before use, modification, or distribution.

This root README serves as a high-level overview of the combined repo structure.
