# MLB Live Odds Scraper

## Overview

This Excel-based scraper automates the daily gathering and aggregation of Major League Baseball (MLB) betting odds from multiple major sportsbooks. It pulls moneyline, runline, and total (over/under) lines, showing both opening and current values to help bettors, analysts, and data enthusiasts monitor line movements, spot value bets, and track market trends. The output is organized into clean tables that update via Power Query, enabling fast refreshes and seamless data integration.

## Features

*Scrapes and consolidates moneyline, runline, and total lines from 10 major sportsbooks.
*Tracks opening and current betting odds for comprehensive line movement analysis.
*Outputs aggregated tables by game and bet type (Moneyline, Runline, Over/Under).
*Refresh log sheet for monitoring successful updates and error diagnostics.
*Designed for easy manual or scheduled refresh in Excel, with transparent Power Query automation steps.
*Compatible with Power BI import for added data visualization and reporting.
*Fully documented with sample datasets and operational instructions.

## Usage

1. Open the Excel file and navigate to the Refresh_Log sheet to check the status of previous refreshes.
2. To update odds, refresh all data queries (Data > Refresh All).
3. Review aggregated betting odds in the main output sheets (e.g., Sportscapping_ML_RL_OU).
4. Optional: Import the Excel file into Power BI Desktop to create dynamic visual reports (see Power BI documentation for import steps).

## License

This project is licensed under the MIT License. See the LICENSE file for details.
