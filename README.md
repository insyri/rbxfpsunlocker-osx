# rbxfpsunlocker-osx [![License](https://img.shields.io/badge/License-GPL3.0-green.svg)](https://github.com/lanylow/rbxfpsunlocker-osx/blob/main/LICENSE) ![OS](https://img.shields.io/badge/OS-macOS-green.svg)

The first Roblox FPS unlocker for macOS. This is a very simple and unpolished FPS unlocker with more updates to come.

## Machine Support

This has ONLY been tested on Intel-based machines, you can try run under Rosetta 2 but expect issues. There are no plans to make this work for Apple Silicon machines natively due to lack of hardware, this is subject to change.

## Usage

1. Download the latest release from https://github.com/lanylow/rbxfpsunlocker-osx/releases.
2. Extract `rbxfpsunlocker.zip` by double clicking on it, if it wasn't extracted automatically.
3. Locate `rbxfpsunlocker` in Finder in your Downloads and right click and press `Get Info`.
4. Copy all text after where it says `Where:`.
5. Open Terminal and write the following command. Replace the `<path>` with the copied path from Finder.

```
cd <path>
```

Exclude angled brackets. (`<>`)

6. Using the `cd` command, you should now be in your Downloads folder or wherever else your FPS unlocker file may be.
7. In the same Terminal window, run the following command. `<cap>` may be replaced with whatever framerate is desired, e.g. 90, 120, 144, etc. If no framerate is supplied it will automatically be set to 120.

```
sudo ./rbxfpsunlocker <cap>
```

8. Enjoy those smooth frames but on macOS now.

A more user friendly setup will soon be released with a video tutorial.

## Compiling (advanced)

1. [Install Git](https://git-scm.com/downloads).

2. Open Terminal, clone and change directory into the repository:

```
git clone https://github.com/lanylow/rbxfpsunlocker-osx/ && cd rbxfpsunlocker-osx
```

3. Compile. This will fail if you don't have [Xcode Developer tools](https://mac.install.guide/commandlinetools/index.html) installed.

```
make
```

4. Launch the unlocker:

```
sudo ./rbxfpsunlocker <cap>
```

## Disclaimer

**Use at your own risk**, this is new and still in-development. However, this uses the same computational/theoretical method as [axstin](https://github.com/axstin/)'s [rbxfpsunlocker](https://github.com/axstin/rbxfpsunlocker), which Roblox approved as legal.

## Credits

@fjij - For bringing the idea to our attention

@lanylow - For reverse engineering and coding the unlocker

@SeizureSaladd - For testing the code and coding the front-end
