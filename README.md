**<h1 style="font-size: 24px;">RATE MY RENT</h1>**<hr>

**Overview**

Rate My Rent is a data-driven project designed to help renters assess whether the price they are paying for an apartment is fair based on key factors like neighborhood, size, and amenities. By utilizing machine learning techniques, we aim to provide a reliable rental price prediction tool that is particularly useful for international students and anyone looking to make informed rental decisions in Toronto.

[Check the Medium article here](https://medium.com/@nicolas.domaniczky/rate-my-rent-46cff7c0c2e4)
---

## How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Positiveproton9/CME538projectTeam10.git
   ```
2. Navigate to the `Rent Data` folder
3. Navigate to the `Zillow` folder   

4. Run the notebook:  
   - `Model (with _no_TRREB_data).ipynb`, the best performing model.
   - Optional to run the other model
---

## Features  

- **Data Sources**:  
  Three primary data sources were utilized:  
  - **Zillow**: Provides general rental trends and property-specific details.  
  - **Rentals.ca**: Offers granular data on rental properties in Toronto, including geocoded addresses.  
  - **TRREB (Toronto Regional Real Estate Board)**: Provides insights into market-level rental statistics.

- **Data Cleaning notebooks**:  
  - **`Cleaningdata.ipynb`**: notebook in charge of handling missing values, correcting errors, and standardizing data for consistency, of the Zillow data. It also dropped the files without sqft area and the ones that weren't in Toronto.  
  - **`Rentals_cleaning.ipynb`**: Focuses on cleaning Rentals.ca data, including:  
    - Standardizing columns.  
    - Parsing price and size units.  
    - Adding geocoded addresses.  
    - Introducing neighborhood rankings. 
    - Exporting database   
  - **`TRREB_data_cleaning2.ipynb`**: Notebook that handles data from TRREB, including:  
    - Standardizing columns.  
    - Getting a value for sqft (as they were expressed as range)  
    - Performing Geocode.  
    - Introducing neighborhood rankings
    - Exporting database  

---

**Workflow**

 <img src="https://github.com/Positiveproton9/CME538projectTeam10/blob/main/Rent%20Data/pipeline.jpg" alt="Overview of Rate my rent project's pipeline" width="500">

 ---
 
 **ATTRIBUTION**
 
 |**TASK** | **NAME (CONTRIBUTION)**|
 |----------|-----------------------|
 
 | DATA COLLECTION | JONATHAN (MAJOR), NICOLAS (MAJOR), OMAR (MINOR), VIVIAN (MINOR) |
 |----------|-----------------------|
 
 | DATA WRANGLING | [NICOLAS (MAJOR), OMAR (MAJOR), JONATHAN (MINOR) VIVIAN (MINOR) |
 |-----------------|------------------------|

| DATA PROCESSING | OMAR (MAJOR), VIVIAN (MAJOR), JONATHAN (MAJOR), NICOLAS (MINOR) |
 |-----------------|------------------------|
 
 | MODEL | JONATHAN (MAJOR), OMAR (MAJOR), NICOLAS (MAJOR), VIVIAN (MINOR) |
 |-----------------|------------------------|
 
 | PRESENTATION SLIDE | VIVIAN (MAJOR), OMAR (MINOR), NICOLAS (MINOR), JONATHAN (MINOR) |
 |---------------|------------------|

 | MEDIUM ARTICLE | VIVIAN (MAJOR), JONATHAN (MINOR), NICOLAS (MINOR), OMAR [MINOR] |
 |---------------|------------------|
 
 
 
