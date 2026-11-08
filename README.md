# Dungeon Slime

A C# game project built with MonoGame and .NET 10 using the DesktopVK (Vulkan) backend. The current starter displays a logo in a 1280 × 720 window.

## Getting started

Install the .NET 10 SDK and ensure your graphics drivers support Vulkan. From the repository root:

```sh
dotnet build DungeonSlime.sln
dotnet run --project DungeonSlime/DungeonSlime.csproj
```

Press **Escape** or the gamepad **Back** button to exit.

## Project layout

- `DungeonSlime/` — game entry point, update/draw logic, and content assets.
- `MonoGameLibrary/` — shared `Core` class for window, graphics, content, and sprite rendering setup.
- `DungeonSlime/Content/Content.mgcb` — MonoGame content pipeline configuration.
