# Laptop-Price-Prediction-and-Analysis
Overview
This project provides an end-to-end solution for analyzing and predicting laptop prices using machine learning. It explores the relationship between various laptop features (brand, processor, RAM, GPU, screen size, resolution, etc.) and their impact on price. The project includes interactive data visualizations and a regression model to estimate laptop prices based on user-selected specifications.

Features
Interactive Dashboard: Visualizes relationships between laptop features and price, including:

Price by operating system and brand

Price by screen size and resolution

Price by processor and RAM

Average weight by brand

Data Exploration: Summarizes key statistics and trends from the dataset.

Machine Learning Model: Implements a regression model (Random Forest and Linear Regression) to predict laptop prices.

Custom Filters: Allows users to filter by processor, GPU, and RAM to analyze specific segments.

Dataset
The dataset includes the following columns:

Brand

Processor

RAM (GB)

Storage

GPU

Screen Size (inch)

Resolution

Battery Life (hours)

Weight (kg)

Operating System

Price ($)

Sample entry:

Brand	Processor	RAM (GB)	Storage	GPU	Screen Size	Resolution	Battery Life	Weight	OS	Price ($)
Apple	AMD Ryzen 3	64	512GB SSD	Nvidia GTX 1650	17.3	2560x1440	8.9	1.42	FreeDOS	3997.07
Project Structure
laptop_prices.csv: Dataset file containing laptop specifications and prices.

Linear_Regression_Model.ipynb: Jupyter notebook with data preprocessing, visualization, and model training.

Dashboard (image provided): Visual representation of key analytics and interactive filters.

Installation
Clone the Repository

bash
git clone <your-repo-url>
cd <project-directory>
Install Dependencies

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Launch Jupyter Notebook

bash
jupyter notebook Linear_Regression_Model.ipynb
Usage
Data Exploration

Run the notebook to load and preview the dataset.

Explore summary statistics and visualize distributions.

Visualization

Use the dashboard to analyze price trends by different features.

Compare brands, operating systems, screen sizes, and more.

Model Training & Prediction

The notebook preprocesses data and trains regression models.

Predict laptop prices by providing feature values.

Key Insights
Screen Resolution: Higher resolutions (e.g., 3840x2160) are associated with higher average prices.

RAM & Processor: Laptops with more RAM and higher-end processors (e.g., Intel i9, AMD Ryzen 9) command higher prices.

Brand Impact: Brands like Apple and Razer tend to have higher average prices.

Weight: Average weight varies by brand, with Lenovo and Apple generally being heavier.

Model Details
Regression Algorithms: Linear Regression and Random Forest Regressor.

Feature Importance: Model coefficients indicate the most influential features on price, such as processor type, RAM, screen resolution, and storage.

Performance: The notebook includes model evaluation metrics (e.g., RMSE, R²).

Customization
Modify the dataset (laptop_prices.csv) to add or update laptop entries.

Adjust visualization parameters in the notebook for deeper insights.

Experiment with different machine learning algorithms or hyperparameters.

Contributing
Fork the repository.

Create a new branch: git checkout -b feature-branch

Commit your changes: git commit -m "Description"

Push to the branch: git push origin feature-branch

Open a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Inspired by real-world laptop price datasets and market analysis.

Utilizes open-source Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.
