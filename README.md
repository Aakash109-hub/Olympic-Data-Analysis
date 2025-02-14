# Olympic Data Analysis Web Application

This web application provides an interactive data analysis experience on historical Olympic data, including insights into medals, country-wise performance, athlete details, and much more. The app is built using **Streamlit** and deployed on Render

### Web Application Link
Access the app here: [Olympic Data Analysis](https://olympic-data-analysis-yxvv.onrender.com/)

![Screenshot 2024-11-04 150940](https://github.com/user-attachments/assets/3d8818d4-ae32-4d44-a8aa-9316e5783f66)


## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Project Overview
This app explores Olympic Games data, allowing users to gain insights on medal tallies, country-wise and athlete-wise performances, and trends over the years. Users can interactively select options and explore visualizations based on historical Olympic data.

## Features
1. **Medal Tally**: View medals by year and country.
2. **Overall Analysis**: Explore top statistics like number of editions, participating cities, sports, events, nations, and athletes. See trends in events, participating nations, and athletes over time.
3. **Country-wise Analysis**: Analyze medals by country, view sports where countries excel, and see top-performing athletes from each country.
4. **Athlete-wise Analysis**: Explore athlete age distributions across medal categories, sports-based distributions for gold medalists, height vs. weight comparisons, and gender participation over time.

## Dataset
This application uses two datasets:
- **Athlete Events Data**: Historical data on athletes and their performance in different Olympic events.
- **NOC Regions Data**: Mapping of National Olympic Committees to their respective regions.

Both datasets are preprocessed using custom functions in the `preprocessor` module to ensure they are ready for analysis.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/olympic-data-analysis.git
   cd olympic-data-analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App Locally**:
   ```bash
   streamlit run app.py
   ```

## Usage
- **Deploy the App**: Visit [https://olympic-data-analysis-yxvv.onrender.com/](https://olympic-data-analysis-yxvv.onrender.com/) to access the web application.
- **Navigation**: Use the sidebar to select between analysis options.
- **Interactive Visuals**: Adjust filters like year, country, or sport to view different analysis results and visualizations.

## Technologies Used
- **Python**: Core programming language.
- **Streamlit**: Web framework for interactive data applications.
- **Pandas**: Data manipulation and analysis.
- **Plotly & Seaborn**: Data visualization libraries.
- **Matplotlib**: Additional plotting for static visualizations.

## Contributing
Feel free to submit issues or pull requests for enhancements, bug fixes, or new features.
