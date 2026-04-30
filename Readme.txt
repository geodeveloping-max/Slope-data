# Slope Displacement Data

This repository contains slope monitoring data from 6 different locations of Mississippi.

## Data Structure

The data is organized in `Slope displacement data/slope data/` with the following files:

| File | Location |
|------|----------|
| slope1_I-220N Ramp.csv | I-220N Ramp |
| slope2_Metro Center.csv | Metro Center |
| slope3_Terry Road.csv | Terry Road |
| slope4_I20W.csv | I20W |
| slope5_Sowell Road.csv | Sowell Road |
| slope6_McRaven Road.csv | McRaven Road |

## Data Columns

Each CSV file contains the following columns:

### Measurement Data
- **Measurement Time**: Timestamp of the measurement (daily intervals)
- **Slope Movement**: Cumulative slope displacement value

### Soil Monitoring (at 5ft, 10ft, 15ft depths)
- **Moisture-[depth]**: Volumetric water content at specified depth
- **Suction-[depth]**: Matric suction at specified depth (kPa)
- **Temp-[depth]**: Temperature at specified depth (°F)

### Precipitation Data
- **Precipitation**: Daily precipitation amount
- **Pre1_Precip, Pre2_Precip, Pre3_Precip**: Precipitation from 1-3 days prior
- **sum_2days_Precip through sum_21days_Precip**: Cumulative precipitation over various periods
- **cum_Precip**: Cumulative precipitation

## Data Format

- CSV format with comma-separated values
- Date format: YYYY-MM-DD HH:MM:SS
- All measurements recorded at midnight (00:00:00)

## Usage

This data can be used for:
- Slope stability analysis
- Correlation between precipitation and slope movement
- Soil moisture and suction relationship studies
- Temperature effects on slope behavior