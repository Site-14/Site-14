Space Station: Site 14 is a currently in concept SS:14 server inspired by the fast paced gameplay of SCP: Secret Labs. We are a fork of Einstein Engines.

## Contributing

We are actively looking for a head contributor, contributors in general, and concept artists.

If you wish to help bring Site 14 to life, please join at this link: https://discord.gg/zWmDxaVs8g

All assets related to SCP are licensed under their CC-BY-SA license as required, read more here: https://scp-wiki.wikidot.com/licensing-guide

## Building

Refer to [the Space Wizards' guide](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) on setting up a development environment for general information, but keep in mind that Einstein Engines is not the same and many things may not apply.
We provide some scripts shown below to make the job easier.

### Build dependencies

> - Git
> - .NET SDK 8.0.100


### Windows

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/bat/buildAllDebug.bat` after making any changes to the source
> 4. Run `Scripts/bat/runQuickAll.bat` to launch the client and the server
> 5. Connect to localhost in the client and play

### Linux

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/sh/buildAllDebug.sh` after making any changes to the source
> 4. Run `Scripts/sh/runQuickAll.sh` to launch the client and the server
> 5. Connect to localhost in the client and play

## License

Please read the [LEGAL.md](./LEGAL.md) file for information on the licenses of the code and assets in this repository.
