# windows.cobaltstrike

## Overview

This repository contains a forked and updated version of the Volatility 3 plugin [windows.cobaltstrike](https://github.com/Immersive-Labs-Sec/volatility_plugins/tree/main/cobaltstrike) from Immersive Labs. This plugin scans all processes in active memory for signs of a Cobalt Strike configuration block. If one is found, it will attempt to parse it and extract the relevant information.

## Installation

To install, place `cobaltstrike.py` in your Volatility 3 installation under `volatility3/plugins/windows/`.
