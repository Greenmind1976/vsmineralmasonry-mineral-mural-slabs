# VSMineralMasonry - Mineral Mural Slabs

Standalone Vintage Story mod for mineral mural slabs, slurry crafting, and related burnished stone content from VSMineralMasonry.

## Included Content

- Mineral mural slabs
- Slab placement and cycling helpers
- Stone slurry and granule crafting flow
- Burnished stone variants tied to the mural slab pipeline

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
