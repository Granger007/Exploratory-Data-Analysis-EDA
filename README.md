To perform Exploratory Data Analysis (EDA) on a housing dataset in order to understand the structure, distributions, correlations, and patterns in the data using summary statistics and visualizations.

💠 Tools & Libraries Used

Pandas – data manipulation

Matplotlib – static visualizations

Seaborn – advanced statistical plots

Plotly Express – interactive visualizations

📁 Dataset

The dataset contains housing sales information, including:

Property features (e.g., bedrooms, bathrooms, sqft_living, etc.)

Sale price (price)

Categorical attributes (e.g., waterfront, view, condition, grade, zipcode)

Location and time data (lat, long, date, etc.)

📌 EDA Tasks Performed

1. Summary Statistics

Used df.describe() and df.info() to get the mean, median, standard deviation, and data types.

Checked for missing values.

2. Distribution Analysis

Plotted histograms for numerical features to visualize distributions and skewness.

Created boxplots to identify outliers.

3. Relationship Analysis

Built a correlation heatmap using Seaborn to understand relationships between features.

Used scatter plots to visualize key feature interactions (e.g., sqft_living vs price).

4. Categorical Group Analysis

Grouped data by waterfront, grade, etc., and plotted bar charts of mean values.

5. Interactive Visualizations

Used Plotly to create:

Interactive histograms for key numeric columns (e.g., sqft_living)

Scatter plots showing relationships between variables (e.g., sqft_living vs price, colored by grade)

VISUALS

<img width="831" height="636" alt="image" src="https://github.com/user-attachments/assets/bde8aa57-336e-4251-bcb2-1360ad3385f1" />
<img width="1238" height="638" alt="image" src="https://github.com/user-attachments/assets/31e70288-7111-4480-af76-eb9fb115efb9" />
<img width="1653" height="620" alt="image" src="https://github.com/user-attachments/assets/ac7ee9c3-8965-4acf-ae7f-dfe851aed467" />




📌 Conclusion

The EDA provided useful insights into the housing data, revealing:

Strong correlation between sqft_living and price

Skewed distributions in price-related features

Outliers in features like sqft_lot

Clear value differences based on features like grade 
