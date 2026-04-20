# VSMineralMasonry - Mineral Mural Slabs

`VSMineralMasonry - Mineral Mural Slabs` is the decorative showcase branch of Mineral Masonry.

It centers on mural slab surfaces and the polish workflow used to turn mineral-themed stone into display pieces, feature walls, and high-detail focal points.

## What It Adds

- Mineral mural slabs
- Slab placement and cycling helpers
- Burnished stone variants tied to the mural slab pipeline

## Best Use Cases

- Building feature walls, floors, and display panels
- Highlighting ore and mineral themes in workshops, vaults, or galleries
- Producing polished decorative stone from a dedicated crafting chain
- Adding premium visual focal points to otherwise plain masonry builds

## Build

Set `VINTAGE_STORY` to your Vintage Story app folder, then build the project:

```bash
dotnet build VSMineralMasonry.MineralMuralSlabs.csproj -c Release -p:NuGetAudit=false
```

## Release Package

Create a distributable zip with:

```bash
./release.sh
```

## Local Install

Install the built mod into your local Vintage Story app with:

```bash
./build-install.sh
```
