# Urban Sprawl Prediction using Land Cover Data of Canada

## Overview
This project explores **urban sprawl patterns in Canada** using land cover datasets. The study emphasizes the environmental, planning, and policy implications of sprawl while applying predictive modeling techniques in **R**. The analysis combines **exploratory data analysis (EDA)**, spatial data handling, and statistical modeling to understand trends and forecast future sprawl scenarios.  

## Authors
- Gunpreet Singh  
- Gurleen Pelia  
- Mariyam Ahmed  

## Objectives
- Analyze Canada’s **land cover data** to identify sprawl trends.  
- Use **R programming** to process, visualize, and model land cover changes.  
- Predict urban expansion and its potential impacts on ecosystems and sustainable development.  
- Provide insights that support **environmental management, disaster risk reduction, and urban planning**.  

## Dataset
- **Land Cover Data of Canada**: Provides information on forest cover, vegetation, and ecosystem distribution.  
- The dataset helps evaluate:  
  - Climate change impacts  
  - Carbon sequestration  
  - Biodiversity preservation  
  - Urban growth and planning  

## Methodology
1. **Data Preparation**  
   - Import and cleaning of land cover data  
   - Structuring datasets for spatial and temporal analysis  

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Visualization of land cover distributions  
   - Mapping sprawl patterns over time  

3. **Modeling & Prediction**  
   - Applying regression and machine learning techniques in R  
   - Predictive modeling of urban growth scenarios  
   - Evaluating accuracy and performance  

4. **Interpretation**  
   - Identifying factors driving urban sprawl  
   - Policy and planning recommendations  

## Tools & Technologies
- **R** (tidyverse, ggplot2, caret, raster, sf, etc.)  
- R Markdown for documentation and reproducibility  
- Spatial and statistical modeling libraries  

## Key Findings (to be expanded)
- Urban sprawl is significantly correlated with population growth and economic activity.  
- Forested and agricultural areas are under increasing conversion pressure.  
- Predictive modeling shows potential hotspots for future expansion.  

## Project Structure
```
├── DATA6500-Land Use for final.Rmd   # Main R Markdown notebook
├── data/                             # Land cover datasets
├── outputs/                          # Generated plots, maps, and results
├── README.md                         # Project documentation
```

## Usage
To reproduce the analysis:  
```r
# Clone repository and open R project
# Install required packages
install.packages(c("tidyverse", "ggplot2", "sf", "raster", "caret"))

# Run R Markdown notebook
rmarkdown::render("DATA6500-Land Use for final.Rmd")
```

## Future Work
- Incorporate higher-resolution spatial datasets  
- Compare predictive models (e.g., Random Forest, Neural Networks)  
- Explore socio-economic factors more deeply  
- Extend analysis to province-specific case studies  

## License
This project is released for academic and research purposes only.  
