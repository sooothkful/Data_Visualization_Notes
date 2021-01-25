

# All data visualizations map data values into quantifiable features of the resulting graphic.

## Aesthetics 

   - Quantifiable features of a graphic
   
   - They describe every aspect of a given graphical element
   
### Commonly used aesthetics:

 - Position
  
 - Shape
  
 - Size
 
 - Color
  
 - Line Width
  
 - Line Type
 
   
### An aesthetic can represent:

 1. Continuous data
  
 2. Discrete data
  
 3. Both
 
 **Factors** - variables that hold qualitative data
 
 **Levels** - different categories of qualitative data

## Scales 
   - Map data values onto aesthetics
   
   - For each data value there must only be one aesthetic value
  
# Coordinate Systems & Axes
   
 ## Cartesian Coordinates 
 
 - 2D Visualization - 2D Cartesian coordinate system is most widely used:
 
   - Two position scales - one for x-axis and one for y-axis
   
   - Must specify geometric arrangement for axes - don't have to be orthogonal
   
   - When axes are measured by different units - can compress or squeeze either of them and maintain a valid visualization
   
   - Must choose an aspect ratio that ensures that important differences in position are noticeable
   
   - If axes are measured by the same units - then spacing should be the same on both axes
   
   - Changing units can be done, however, because it is a linear transformation and the Cartesian coordinate systems are invariant under linear transformations
 
 
      
## Nonlinear Axes
     
   - In some instances a nonlinear scale is preferred
   
   - For **logarithmic scales** - always label ticks and be sure to include what base is used
   
   - **Ratios should not be displayed on a linear scale**
   
   - If larger values need to be compressed into a smaller range on scale and lower values do not - one can use a **square-root transformation**
   
   - **Square-root scales** can be a little tricky to label - you don't want to label with squares (unintuitive) - may label with linear labels - but this probably won't 
      provide great coverage over the entirety of the scale - may need to use arbitrary values to provide reasonable coverage for the data range.
      
 
## Curved Axes

   - Polar coordinate system - specifies positions via an angle and a radial distance from the origin, and so the angle axis is circular
   
   - Polar coordinates are useful for data of periodic nature - data values at one end of the scale can be logically joined to data values at the other end (ex: last day of the       year sits right next to the first day of the next year)

   - Geospatial data - drawing maps on Cartesian axes is misleading because the earth is a sphere - causes surface area of continents on map to be distorted
   
   - Interupted Goode homolosine projection- represents true surface areas - but splits some land masses in two
   
   - Robinson projection and Winkel tripel projections are commonly used  
   
      
# Color Scales
     
## Color as a Tool

## Color to Represent Data Values
  
## Color as a Tool to Highlight

# Directory of Visualizations
  
## Amounts
### Bar Plots
### Grouped and Stacked Bars
### Dot Plots and Heatmaps

## Distributions
### Histograms

  **Single distributions**
  
  
  **Multiple distributions**
  
  
### Density Plots

 **Single distributions**
 
  
 **Multiple distributions**


### Emperical Cumulative Distributions

 **Highly Skewed Distributions**
  
  
 **Q-Q Plots**


### Visualizing many distributions at once

 **Boxplots**
  
  
  **Violins**
  
  
 **Strip Charts**
  
  
 **Sina Plots**
  
  
 **Stacked Histograms**
  
  
 **Overlapping Densities**
  
  
 **Ridgeline Plots**
  
  
## Proportions
### Pie Charts
### Side-by-Side Bars
### Stacked Bars & Stacked Densities
### Proportions as part of a whole
### Nested Proportions


 **Mosiac Plots**
  
  
 **Treemaps**
  
  
 **Nested Pies**
  
  
 **Parallel Sets**


## Multiple Quantitative Variables
### Scatter plots
### Correlograms
### Dimension Reduction
### Paired Data

## Visualizations of Independent Variables
### Time Series

 **Individual Time Series**
  
  
 **Multiple Time Series**
  
  
 **Dose-response Curves**
  
  
 **Two or more response variables**
  
  
## Trends
### Smoothing
### Defined functional form
### Detrending
### Time-series decomposition

## Geospatial Data
### Projections
### Layers
### Choropleth Mapping
### Cartograms
 
## Uncertainty
### Probabilities as Frequencies
### Point Estimates
### Curve Fits
### Hypothetical Outcome Plots

# Proportional Ink

# Handling Overlapping Points

# Mistakes to Avoid
## Color
## Redundant Coding
## Multi-panel Figures
## Titles, Captions, Tables
## Context
## Axis Labels
## Line Drawings
## 3D

# File Formats
## Bitmap & Vector
## Compression
## Converting image formats

# Software
## Reproducibility & Repeatability
## Exploration vs Presentation
## Content & Design

# Storytelling
## Figures
## Consistency vs Repetitiveness



      


