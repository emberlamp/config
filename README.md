# gh-config

GitHub CLI extension to get configuration values from emberlamp/config repository.

## Purpose

Centralized configuration management for all emberlamp CLI extensions.

## Installation

```bash
gh extension install emberlamp/config
```

## Usage

### Get a config value
```bash
gh config warningsEnabled
```

### List all config keys
```bash
gh config --list
```

## Configuration

The config is stored in [emberlamp/config](https://github.com/emberlamp/config) repository.

```json
{
  "warningsEnabled": true,
  "pinRepoEnabled": false,
  "defaultOrg": "emberlamp",
  "features": {
    "autoPin": false,
    "autoLicense": true,
    "autoReadme": true
  }
}
```