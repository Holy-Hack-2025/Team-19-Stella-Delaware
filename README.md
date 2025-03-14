# SwiftLijn

## Table of Contents
- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Data Sources](#data-sources)
- [Acknowledgments](#acknowledgments)
- [Created By](#created-by)

## About
SwiftLijn is an AI-powered bus stop and route optimization solution designed for De Lijn. Our system detects low-density bus stops where demand is minimal and optimizes public transport routes to improve efficiency, reduce costs, and cut traffic congestion in Belgium.

By integrating population density analysis, historical ridership data, and multi-modal transport optimization, SwiftLijn enables De Lijn to operate a cost-effective, passenger-focused transport network.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Holy-Hack-2025/Team-19-Stella-Delaware.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   npm install
   ```

## Usage
To obtain population density data, run the Jupyter density application and execute all cells. Similarly, for the Proof of Concept (POC), open the Jupyter notebook and run all cells to complete the process.

## Configuration
To configure this project, you will need to set up the following environment variables in a .env file:
```
DE_LIJN_API_KEY=your-de-lijn-api-key-here
GEMINI_API_KEY=your-gemini-api-key-here
```
These keys are required for accessing the necessary APIs used in SwiftLijn.

## Data Sources
List and describe any external data files, APIs, or other dependencies.

Example:
- `stadswijen-gent.geojson` - Contains boundary data.
- `PopulationDensity.json` - Stores population density.
- `bus_stops.csv` - Lists all bus stops and line routes.

## Acknowledgments
 All links to data sources used in this project can be found in the Research.md file.

## Created By
Team 19 of the Holy hackathon 2025
   - Dimova Alina  
   - Gerbreders Eriks
   - Mumladze Daniil 
   - Solovyova Aleksia 
   - Tuffin Alec


