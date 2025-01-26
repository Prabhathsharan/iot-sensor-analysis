# IoT Sensor Data Analysis

This repository contains Python code for analyzing IoT sensor data, visualizing trends, and identifying patterns. The project provides insights into power consumption trends and anomaly detection.

## Features

- **Total power consumption analysis** – Calculates power usage for each site.
- **Hourly trends visualization** – Analyzes power consumption patterns over time.
- **Sensor correlation analysis** – Identifies relationships between different sensor readings.
- **Anomaly detection using machine learning** – Detects unusual patterns using Isolation Forest.
- **Trend and seasonality decomposition** – Understands power consumption trends over time.
- **Interactive visualization** – Dynamic dashboards using Plotly.
- **Forecasting future consumption** – Predicts future trends with ARIMA modeling.
- **Clustering analysis** – Groups similar sensor patterns for better insights.

## How to Run

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the analysis script:**
   ```bash
   python iot_data_analysis.py
   ```

3. **Visualize results:**  
   Check generated plots and CSV files in the output folder.

## Deployment Readiness

This project is fully Dockerized and ready for deployment across multiple environments.

### Steps to Deploy via Docker:

1. **Build the Docker image:**
   ```bash
   docker build -t iot-sensor-analysis .
   ```

2. **Run the Docker container:**
   ```bash
   docker run -d -p 5000:5000 iot-sensor-analysis
   ```

3. **Access the application:**  
   Navigate to `http://localhost:5000` in your web browser.

## Challenges Faced

- Handling missing timestamps and ensuring data continuity.
- Managing large datasets efficiently for time series analysis.
- Choosing appropriate machine learning models for anomaly detection and forecasting.

## Outcomes and Insights

- Identification of peak consumption periods across different sites.
- Detection of irregular sensor behavior for maintenance and optimization.
- Improved understanding of power usage trends for better energy planning.

## Future Improvements

- Implementing real-time streaming analytics for continuous monitoring.
- Integration with cloud platforms for scalable data storage and processing.
- Applying deep learning techniques for enhanced forecasting accuracy.

## License

This project is licensed under the MIT License.

## Contributors

Feel free to contribute by opening an issue or submitting a pull request.

