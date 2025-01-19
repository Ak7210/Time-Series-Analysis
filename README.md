# Time Series Analysis

---

## Overview of Time Series

### Question: What is Time Series Data?

**Answer:** Sequentially ordered data over time is called **time series data**.

- Observations are typically collected at regular intervals:
  - Every second/minute/hourly
  - Daily
  - Monthly
  - Quarterly/Yearly
- **Examples:**
  - Monthly sales data
  - Quarterly/Annual revenue
  - Hourly weather data (e.g., wind speed)
  - IoT sensor data in industries and smart devices
  - Energy forecasting
  - Etc.

---

### Key Concepts in Time Series Data

- The data may exhibit some **trends**.
- The data may show **seasonality**.
- The data may display **cyclic patterns**:
  - *Note: There is a difference between seasonality and cyclic data.*
- Data can be **non-stationary**, but some modeling techniques require data to be **stationary**.

---

### Key Difference: Seasonality vs. Cyclic Patterns

- **Cyclic patterns:** Cannot predict the nature of the cycles.
- **Seasonality:** Can predict patterns, such as increased sales of sweets during festive seasons.
- Example: The price of gold typically does not follow a seasonal pattern.

---

## Types of Seasonality

- **Additive Seasonality with No Trend**
- **Additive Seasonality with Trend**
- **Multiplicative Seasonality with No Trend**
- **Multiplicative Seasonality with Trend**
