
# Automated Integration of Second-Hand Windows in Revit with Dynamo

## Overview
This repository contains a Dynamo script that automates the integration of second-hand windows into Revit models. By utilizing this tool, architects, designers, and engineers can efficiently incorporate reused windows, helping to reduce material waste and calculate the Global Warming Potential (GWP) savings for sustainable construction practices.

## Features
- **Automated Window Matching:** Matches second-hand windows to existing Revit families based on user-defined dimensional tolerances.
- **Parameter Updates:** Automatically updates necessary window parameters, ensuring proper documentation and usage in BIM workflows.
- **Global Warming Potential Calculation:** Calculates GWP savings when reusing windows compared to new window installations, providing valuable sustainability insights.

## Requirements
- **Revit:** Version 2023 or later
- **Dynamo:** Version 2.x or later
- **Python:** Required for some scripting features
- **Revit Families:** Pre-loaded with window types to be matched with second-hand windows

## Installation
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
2. Open the Dynamo script (`.dyn`) in Revit Dynamo.

3. Adjust the necessary parameters in the Dynamo script:
   - **Tolerance Values:** Modify the tolerance to control how closely the second-hand windows should match the existing window openings.
   - **Window Parameters:** Define which window parameters should be updated (e.g., dimensions, material specifications).

## Usage Instructions
1. Open your Revit model containing window openings.
2. Run the Dynamo script from the Dynamo Player in Revit.
3. Select the second-hand windows dataset to integrate.
4. Adjust tolerance settings to control the match accuracy.
5. Execute the script, which will:
   - Match and place second-hand windows in the corresponding openings.
   - Update parameters and metadata (e.g., size, material).
   - Calculate GWP savings from reusing windows.

6. Review the summary report, which will detail:
   - Successfully matched windows.
   - Adjustments made to parameters.
   - GWP savings analysis.

## Example
An example dataset containing second-hand window data and an example Revit model is included in the `examples/` directory. Use this to familiarize yourself with the workflow before applying it to your projects.

## GWP Calculation
The GWP savings are calculated based on predefined environmental data for reused and new windows. The script provides a comparison between the carbon emissions associated with manufacturing new windows versus using second-hand ones, giving you a clear picture of the environmental impact.

## Contributions
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/repository-name/issues) or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
