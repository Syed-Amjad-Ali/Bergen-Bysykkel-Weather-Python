# Bergen Bysykkel 2024: Python Edition - Cleaning, Predicting, and Mapping (Part 1)

This is Part 1 of a two-part analysis exploring Bergen's bicycle rental trends, now implemented in Python! In this installment, we perform **data cleaning**, build **basic predictive models**, and end with an **interactive map** showcasing bike traffic across stations. Part 2 will delve deeper into advanced methods, integrating weather data for precision modeling and actionable insights.

## Data Sources

- **[Bysykkel Data](https://bergenbysykkel.no/apne-data/historisk)**: Historical bike rental data provided by Bergen Bysykkel.
- **[Weather Data](https://seklima.met.no/observations/?fbclid=IwY2xjawHC3BlleHRuA2FlbQIxMAABHR-1J8AxQO7W68khnBEDM7aVue4GLeWghu0CrBYHs3b1dowE8Wq2u1oBXQ_aem_HFWzKgdTgLH6cHBCCTq4RA)**: Hourly weather observations obtained from SeKlima.

## Highlights of Part 1

1. **Python-Powered Data Cleaning**:
   - Combined hourly bike rental data for 2024 into a clean and structured format.
   - Addressed missing values, ensured consistent timestamps, and added derived features (e.g., weekday, hour).

2. **Foundational Predictive Modeling**:
   - Utilized Python's `scikit-learn` library for linear regression to predict hourly rentals by station, weekday, and time.

3. **Interactive Mapping**:
   - Created an engaging map using Python's `folium` library to visualize station activity, complete with color-coded markers and popups.

## What’s Coming in Part 2?

- Integration of weather data to evaluate its influence on bike rentals.
- Advanced predictive models leveraging machine learning techniques.
- Comparative analysis of model performances.

Stay tuned as we transition from foundational techniques to advanced predictive analytics in Python!

## Getting Started

### Requirements
- Python version >= 3.8
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `folium`, etc.



## Inspiration and Acknowledgments

The initial problem framing and directions for this project are inspired by the **BAN400** course at the [Norwegian School of Economics (NHH)](https://www.nhh.no/en/courses/r-programming-for-data-science/). The earliest solution to this exam available on GitHub is:

- [Hoa Nguyen’s Bergen Bysykkel Analysis](https://github.com/hoanguyen18/Bergen-Bysykkel-), which utilized 2021 data and was implemented in R.

Building on these foundations, this project transitions the analysis to Python, leveraging tools like `pandas`, `scikit-learn`, and `folium` to provide an enhanced and updated perspective using 2024 data.

A notable feature in this implementation is the use of Python's `folium` library for geospatial visualization. This approach mirrors the functionality of the `leaflet` package in R, leveraging free OpenStreetMap data to create an interactive mapping experience, complete with zoom controls, hover effects, and categorical markers.

---

## Legal and Ethical Notes

- This project references the BAN400 preparation material as a learning guide while ensuring originality in its implementation.
- All work is aligned with NHH’s academic integrity guidelines and complies with the Bergen Bysykkel API's open-source licensing.
