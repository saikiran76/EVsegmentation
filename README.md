# Electric Vehicle segmentation
## Electric Vehicle Segmentation Analysis

Welcome to the Electric Vehicle Segmentation Analysis repository! This project aims to provide insights into the segmentation of electric vehicles (EVs) based on various attributes and properties. We have conducted an in-depth analysis using data collected from different electric vehicle models. The repository contains a comprehensive breakdown of our approach and findings.

### Objective
The main objective of this project is to segment electric vehicles into meaningful clusters based on their properties, including boot space, range per full charge, transmission type, and more. By analyzing these attributes, we aim to identify distinct segments of EVs that cater to different consumer preferences and needs.

### Data Collection and Preprocessing
We collected data on electric vehicles from various sources, capturing essential attributes such as boot space, range, and transmission type. Before analysis, we conducted preprocessing steps including:
- Handling null values through mean imputation.
- Encoding categorical attributes using appropriate techniques (Label/Ordinal Encoding).
- Scaling attribute values to ensure fair representation in clustering algorithms.

### Exploratory Data Analysis (EDA)
Our analysis begins with exploratory data analysis, where we delve into statistical summaries and visualizations to gain insights into the distribution and relationships among different attributes. Descriptive analysis and bivariate analysis techniques are employed to uncover patterns and potential correlations.

### Segmentation Extraction
Using a combination of EDA insights and domain knowledge, we extracted potential segments that go beyond traditional demographic categories. We explored various attributes, particularly focusing on:
- Range (km/full charge) - Unearthing segments such as "long-range electric cars" and "short-range electric cars" to cater to different driving needs.
- Boot Space - Defining segments based on storage capacity, e.g., "high boot space, high range vehicles" ideal for long-distance travel and cargo.

### Clustering Techniques
To achieve segmentation, we employed clustering algorithms including K-Nearest Neighbors (KNN) and hierarchical clustering. These algorithms group similar EVs together, allowing us to define distinct segments based on shared characteristics.

### Results and Potential Segments
Our analysis yielded several potential segments that could guide marketing strategies and product offerings. These segments transcend geographic, demographic, psychographic, and behavioral categories. Examples include:
- "Low-cost sedans with automatic transmissions"
- "High-end SUVs with manual transmissions"
- "Long-range electric cars for commuting and travel"
- "Short-range electric cars for urban driving"

### Libraries and Tools
This analysis was conducted using a variety of tools and libraries, including:
- Pandas and NumPy for data manipulation.
- Scikit-Learn for clustering algorithms.
- Matplotlib, Seaborn, and Plotly Express for data visualization.

### Usage
Feel free to explore our analysis and findings in the repository. The provided Jupyter notebooks detail the step-by-step process of data preprocessing, EDA, segmentation extraction, and clustering. We hope this analysis contributes to a better understanding of the electric vehicle market and its diverse segments.

For any inquiries or feedback, please don't hesitate to reach out. Happy exploring!

