# Scoop Bucket for svg-to-compose (s2c)

Scoop bucket for installing the [svg-to-compose](https://github.com/rafaeltonholo/svg-to-compose) CLI tool on Windows.

**s2c** converts SVG and Android Vector Drawable files to Jetpack Compose `ImageVector` code.

## Installation

```powershell
scoop bucket add svg-to-compose https://github.com/dev-tonholo/scoop-svg-to-compose
scoop install s2c
```

## Usage

```powershell
# Convert an SVG file to Compose ImageVector
s2c --input icon.svg --output ./icons

# See all available options
s2c --help
```

## Update

```powershell
scoop update s2c
```

## Uninstall

```powershell
scoop uninstall s2c
```

## License

MIT
