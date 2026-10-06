# Masterplan

Masterplan is an application that helps you to build D&D 4E campaigns.

You can outline your plot structure, build encounters and maps, detail your campaign world, and create custom creatures and NPCs.

## Screenshots

![Masterplan Main Interface](https://github.com/andyaiken/masterplan/raw/main/screenshots/main-interface.png)

## Installing it

To install Masterplan, get the `Masterplan.zip` file from the latest release, which can be found here:

https://github.com/andyaiken/masterplan/releases/latest

Extract all the files in this zip into their own folder, and run `Masterplan.exe`.

### System Requirements

- Windows 7 or later
- .NET Framework 4.7.2 or later
- Visual Studio 2019 or later (for building from source)

## Building and running it

**Prerequisites** You'll need to have Visual Studio installed (community edition is fine), and the `Microsoft Visual Studio Installer Projects` extension loaded.

To build Masterplan, open `Masterplan.sln` in Visual Studio and build the `Masterplan` project (F6).

Bear in mind that every time you build Masterplan in Visual Studio, the library files are copied from `./Libraries` into the output folder, so any changes you make to these libraries won't be retained.

The other project in the solution is called `Setup`, which creates an installer.

## Using Masterplan

### Getting Started

1. Launch `Masterplan.exe`
2. Create a new campaign or open an existing one
3. Use the tree view on the left to navigate between campaign sections
4. Add encounters, maps, creatures, and NPCs using the toolbar buttons

### Key Features

- **Plot Structure**: Outline your campaign's story arcs and chapters
- **Encounters**: Build tactical encounters with maps and creature placements
- **Maps**: Create grid-based battle maps with terrain and obstacles
- **Creatures & NPCs**: Design custom monsters and non-player characters
- **World Building**: Detail your campaign world with locations, factions, and lore

### Tips

- Use the **Encounter Template Wizard** to quickly build balanced encounters
- The **Map Wizard** helps you create maps with standard sizes and grid types
- Save often — Masterplan stores everything in a single `.mp` file

## Contributing to it

If you find a bug, or you think of a feature that should be in Masterplan, please add something to the GitHub Issues tab (https://github.com/andyaiken/masterplan/issues).

If you're a coder, feel free to submit pull requests to the main repo.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
