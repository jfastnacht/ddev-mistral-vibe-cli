[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/jfastnacht/ddev-mistral-vibe-cli/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/jfastnacht/ddev-mistral-vibe-cli)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/commits)
[![release](https://img.shields.io/github/v/release/jfastnacht/ddev-mistral-vibe-cli)](https://github.com/jfastnacht/ddev-mistral-vibe-cli/releases/latest)

# DDEV Mistral Vibe Cli

## Overview

This add-on integrates Mistral Vibe Cli into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get jfastnacht/ddev-mistral-vibe-cli
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev describe` | View service status and used ports for Mistral Vibe Cli |
| `ddev logs -s mistral-vibe-cli` | Check Mistral Vibe Cli logs |

## Advanced Customization

To change the Docker image:

```bash
ddev dotenv set .ddev/.env.mistral-vibe-cli --mistral-vibe-cli-docker-image="ddev/ddev-utilities:latest"
ddev add-on get jfastnacht/ddev-mistral-vibe-cli
ddev restart
```

Make sure to commit the `.ddev/.env.mistral-vibe-cli` file to version control.

All customization options (use with caution):

| Variable | Flag | Default |
| -------- | ---- | ------- |
| `MISTRAL_VIBE_CLI_DOCKER_IMAGE` | `--mistral-vibe-cli-docker-image` | `ddev/ddev-utilities:latest` |

## Credits

**Contributed and maintained by [@jfastnacht](https://github.com/jfastnacht)**
