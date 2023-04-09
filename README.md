# GShade Installation Data

Version: 4.2.1
Based on ReShade: 5.8.0
Release Date: 04/08/2023

This repository is a fork which directly preserves the GShade installation data and preliminary assets for all major installation modes:

| Mode        | Principal File |
|-------------|----------------|
| Normal      | `dxgi.dll`     |
| Alternative | `d3d11.dll`    |
| DirectInput | `dinput8.dll`  |

The data has been unified into this repository for optimisation and portability. This repository can be used as a functional GShade installation when merged within the XIV game directory. It is recommended to use only one of the aforementioned DLL files to avoid conflicts, e.g. for a Normal installation mode, keep `dxgi.dll` and remove the Alternative `d3d11.dll` and DirectInput `dinput8.dll` files.
