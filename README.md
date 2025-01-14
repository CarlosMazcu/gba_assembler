# GBA Assembly Exercises

This repository contains three directories, each representing a separate exercise. Each exercise is compiled independently.

## Directory Structure

- **`sand`**: Exercise 1
- **`snake`**: Exercise 2
- **`bitfields`**: Exercise 3

Each exercise contains:

- A `main.c` file.
- At least one `.s` file, which implements an algorithm in assembly language.

## Compilation

To compile any exercise, navigate to the respective directory (`./sand`, `./snake`, or `./bitfields`) and run the `make` command:

```bash
make
```

Upon successful compilation, you should see a final message similar to:

```
ROM fixed!
```

## Running the Exercises

Each exercise produces a `.gba` file, which is a Game Boy Advance (GBA) cartridge. You will need a GBA emulator to run these files.

### Installing an Emulator (Linux)

We recommend using **VisualBoyAdvance**. To install it, run the following commands:

```bash
sudo apt update
sudo apt install visualboyadvance
```

### Running the Exercises

If you have VisualBoyAdvance installed, simply execute the following command, replacing the path with the specific `.gba` file:

```bash
vba ./<exercise_name>.gba
```

Example:

```bash
vba ./sand.gba
```

## Notes

- Ensure you have the necessary permissions to execute the `make` command in each directory.
- For the best experience, familiarize yourself with the VisualBoyAdvance emulator options to customize your gameplay.

Enjoy exploring GBA assembly programming!
