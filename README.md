[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/jfastnacht/ddev-mistral-vibe-cli/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/jfastnacht/ddev-mistral-vibe-cli)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/commits)
[![release](https://img.shields.io/github/v/release/jfastnacht/ddev-mistral-vibe-cli)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/releases/latest)

# DDEV Mistral Vibe CLI

## Overview

This add-on integrates Mistral Vibe CLI into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get jfastnacht/ddev-mistral-vibe-cli
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Configuration

You can find the configuration files within `.ddev/mistral-vibe-cli`. Add your AI service and model configuration
to the `.ddev/mistral-vibe-cli/config.toml` and set your API key in `.ddev/mistral-vibe-cli/.env`.

For more information on configuring Mistral Vibe CLI consult the documentation at
https://docs.mistral.ai/mistral-vibe/introduction/configuration

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev vibe` | Run Mistral Vibe CLI in web container |

## Credits

**Contributed and maintained by [@jfastnacht](https://github.com/jfastnacht)**
