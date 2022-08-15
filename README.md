
<br />
<p align="center">
  <a href="https://github.com/Chonky-Seal-OS/installer">
    <img src="https://media.discordapp.net/attachments/827947440945627167/1008536926787207239/chonky-seal-logo.png" alt="Logo" width="250" height="250">
  </a>

  <h3 align="center">GUI Installer for Chonky Seal OS</h3>
</p>

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Here are all dependencies you need to build the project

- Compiler with C++11 support: GCC >= 4.9.0 or Clang >= 3.5.1
- CMake >= 3.2
- Qt >= 5.7
- yaml-cpp >= 0.5.1
- Python >= 3.3 (required for some modules)
- Boost.Python >= 1.55.0 (recommended, or PythonQt; one is required for some modules)
- PythonQt (recommended, or Boost.Python; one is required for some modules)
- extra-cmake-modules >= 5.18 (recommended; required for some modules)

### Installation

1. Clone the installer

```sh
git clone https://github.com/Chonky-Seal-OS/installer
```

2. Create build directory

```sh
mkdir installer/build
cd installer/build
```

3. Compile
```sh
cmake -DCMAKE_BUILD_TYPE=Debug ..
make
```

4. Copy Settings Config File to Build Directory
```sh
cp ../settings.conf .
```

## Usage

Simply run the following command

```bash
./calamares
```

