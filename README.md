# Pyourly

## Efficient Air-Quality Index Monitoring System

### Abstract

The Pyourly project aims to revolutionize the way individuals monitor and protect themselves from exposure to harmful air pollutants by developing a portable, high-quality Air Quality Index (AQI) sensor and monitoring system that provides _real-time feedback_. Pyourly sets itself apart from existing solutions by offering _offline_ capabilities and addressing the limitations of current techniques, while highlighting the _critical health risks_ associated with prolonged exposure to poor air quality.

### Shortcomings of Current Techniques

Current techniques for monitoring air quality often fall short in several ways. Traditional stationary AQI monitoring stations are expensive, limited in scope, and cannot offer personalized information to individuals. Portable monitors are often inaccurate or unreliable, while mobile apps may rely on a constant internet connection, limiting their utility in areas with poor connectivity. These limitations hinder individuals' ability to make informed decisions about their exposure to harmful air pollutants.

### Health Risks Associated with Air Pollution

Exposure to poor air quality poses both short-term and long-term health risks. Short-term effects include aggravated respiratory conditions, allergic reactions, headaches, and fatigue. Prolonged exposure increases the risk of developing chronic health issues such as asthma, cardiovascular diseases, and even certain types of cancer. Therefore, the importance of monitoring and avoiding overexposure to bad air quality cannot be overstated.

### Features

1. Highly sensitive and **portable** sensing system with continuous readings of Air Quality Index (AQI) throughout the day, to monitor the user's risk fo over-exposure to air pollution.
2. Detects over-exposure and sends a warning notification to the user.
3. Display a history of the user's surrounding AQI and analysis of the same.
4. While the integrated sensor reads the AQI inside the room, AQI of the surroundings is fetched from [OpenWeatherMap API](https://openweathermap.org/api/air-pollution) and the comparison is displayed to the user.
5. The integrated sensor data is synced on [Microsoft Azure Cloud](https://azure.microsoft.com/) for storage and analysis, securely, protecting the user's privacy.
6. With the hardware, based on a **Raspberry Pi**, the UI is available as a beautiful, interactive, easy-to-use and mobile-friendly web-app, which is light to download.

### Technologies Used

1. Raspberry Pi Microprocessor
2. An Air Quality Sensor
3. ThingSpeak API to post and fetch the air quality data.
4. ReactJS, Progressive Web App (PWA), HTML, CSS
5. Python, used for coding Raspberry Pi

### What sets us apart?

Here's how Pyourly is a cut above similar apps in the segment:

1. **Low Latency**: The Air Monitoring App stands out for its low latency, which is facilitated by an express server running on a Raspberry Pi. This setup enables direct access to real-time data without relying on intermediary platforms such as ThingSpeak API. By cutting out the need for third-party middleware, the app significantly reduces data retrieval time, ensuring that users receive immediate updates on air quality metrics.
2. **Better UI/UX**: Apart from the other apps, Pyourly stands out with its interactive user interface which keeps users engaged and also informs them about the indoor and outdoor air quality.
3. **Friendly Notification Feature**: The notification feature in **Pyourly** serves as a crucial tool to keep users informed about the current air quality. With the aim of promoting proactive health measures, the app generates timely alerts tailored to pollution levels. For instance, when detecting mild pollution, the app sends a friendly reminder such as, "Mild pollution alert: Time to open the windows, maybe?" This encourages users to take simple precautions. In more critical situations, like extreme pollution, the app issues a poignant warning. By leveraging these personalized notifications, the Air Monitoring App empowers users to safeguard their well-being amidst fluctuating air quality conditions.
4. **Low Cost**: Because of the selection of the most suitable hardware i.e., Raspberry Pi and an Air Quality Sensor, we reduce the price of the product.
5. **Accurate Measurements**: The use of quality sensors and data validation techniques to identify and eliminate erroneous or inconsistent data points, ensuring that only accurate measurements are considered.

### Offline Features of the App:

Storing data locally when there is no internet connectivity, providing historical data and trends, allowing users to set up alerts for certain air quality thresholds, and offering educational content on air quality and its impact on health.
