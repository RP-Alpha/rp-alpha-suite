# RP-Alpha Suite

A comprehensive collection of FiveM roleplay server resources designed to provide a complete gameplay experience.

## Overview

The RP-Alpha Suite is a meta-repository that bundles together multiple FiveM resources into a single, cohesive package. This suite provides essential functionality for running a feature-rich roleplay server, including emergency services, jobs, vehicle management, housing, and more.

## What's Included

### Core Resources
- **rpa-lib** - Core library and shared utilities
- **rpa-notify** - Notification system
- **rpa-textui** - Text-based UI components

### Gameplay Resources
- **rpa-police** - Police job and functionality
- **rpa-ambulance** - Medical/EMS services
- **rpa-jobs** - General job system
- **rpa-tuning** - Vehicle customization
- **rpa-vehiclekeys** - Vehicle ownership and key management
- **rpa-garages** - Garage and vehicle storage system
- **rpa-housing** - Housing and property management
- **rpa-fuel** - Fuel system
- **rpa-shops** - Shop and purchasing system
- **rpa-banking** - Banking functionality
- **rpa-appearance** - Character appearance customization
- **rpa-spawn** - Player spawn management
- **rpa-cityhall** - City hall services
- **rpa-mdt** - Mobile Data Terminal for emergency services
- **rpa-dispatch** - Emergency dispatch system
- **rpa-blips** - Map blips and markers
- **rpa-consumables** - Consumable items system

## Installation

### Download

Pre-bundled releases are automatically created when new versions are tagged. To download:

1. Go to the [Releases](https://github.com/RP-Alpha/rp-alpha-suite/releases) page
2. Download the latest `RP-Alpha-Suite-vX.X.X.zip` file
3. Extract the contents to your FiveM server's `resources` folder
4. Add the resources to your `server.cfg` file

### From Source

If you prefer to work with individual repositories, each component can be found in the [RP-Alpha organization](https://github.com/RP-Alpha).

## How It Works

This repository uses GitHub Actions to automatically bundle all component resources whenever a new version tag (e.g., `v1.0.0`) is pushed. The workflow:

1. Checks out this meta-repository
2. Clones each individual resource repository
3. Bundles them into a single archive
4. Creates a GitHub release with the bundled package

## Individual Repositories

Each resource in the suite is maintained in its own repository under the [RP-Alpha organization](https://github.com/RP-Alpha). This allows for:

- Independent development and versioning
- Focused issue tracking and contributions
- Modular updates and maintenance

## Contributing

Contributions should be made to the individual resource repositories rather than this meta-repository. Please check each specific repository for contribution guidelines.

## License

Please refer to the individual resource repositories for their respective license information.

## Links

- Organization: [RP-Alpha](https://github.com/RP-Alpha)
- Issues: [Report an issue](https://github.com/RP-Alpha/rp-alpha-suite/issues)
