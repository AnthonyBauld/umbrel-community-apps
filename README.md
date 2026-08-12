# Umbrel Community Apps

Custom app repository for umbrelOS.

## Included Apps

* **aggr**: Real-time cryptocurrency orderbook and trade aggregator.

## Installation

1. Open the umbrelOS dashboard.
2. Navigate to the App Store.
3. Click the menu icon (three dots) in the top right corner.
4. Select "Community App Stores".
5. Click "Add".
6. Input the repository URL: `https://github.com/AnthonyBauld/umbrel-community-apps`
7. Click "Add".
8. Install applications directly from the newly added store section.

## Repository Structure

Each application requires a dedicated directory containing:
* `docker-compose.yml`: Container orchestration configuration.
* `umbrel-app.yml`: App manifest defining UI parameters, ports, and metadata.
* `exports.sh` (optional): Environment variable definitions.
