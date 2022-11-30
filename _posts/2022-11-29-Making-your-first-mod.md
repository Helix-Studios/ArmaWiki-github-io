---
title: Making your first Arma 3 Mod
date: 2022-11-29 12:00:00 -500
categories: [Informational, Tutorial]
tags: [informational, texturing]     # TAG names should always be lowercase
---

## Getting Started

## Required Tools

In order to start your modding journey, you will need a few things. Listed below are the very basic tools required for starting your journey.

> - [Arma 3 Tools](https://store.steampowered.com/app/233800/Arma_3_Tools/)
> - [Arma 3 Tools](https://store.steampowered.com/app/233800/Arma_3_Tools/)
> - [Arma 3 Tools](https://store.steampowered.com/app/233800/Arma_3_Tools/)
> - [Arma 3 Tools](https://store.steampowered.com/app/233800/Arma_3_Tools/)
> - [Arma 3 Tools](https://store.steampowered.com/app/233800/Arma_3_Tools/)

## File structure

## Config

---

```C++
class CfgPatches
{
    class PATCH_TEMPLATE
    {
        units[] = {};
        weapons[] = {};
        requiredAddons[] = {};
        version = "1.0.0"; // Version of mod.
        author[]= {"Name"}; // Author name.
        authorUrl = ""; // Link to website/discord etc.
    };
};

class CfgUnitInsignia
{
    class PATCH_1 // Class name of patch.
    {
        displayName = "Patch 1";// Name of patch in game.
        author = "Schlopp";// Author name.
        texture = "\HS_Patches\icon\alpha1.paa";// File path to texture.
        textureVehicle = "";
    };
};
```

> File containing config must be named `config.cpp`

> This wiki page is still under development.
{: .prompt-info }

---