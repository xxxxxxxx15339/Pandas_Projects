# 🟢 Project 2. Weather Data Cleaner

## 📁 Dataset

Create a CSV file named **`weather_data.csv`** with the following sample data:

| Date       | Temperature | Humidity |
|------------|-------------|----------|
| 2023-06-01 | 27.5        | 60       |
| 2023-06-02 | 28.1        |          |
| 2023-06-03 |             | 55       |
| 2023-06-04 | 29.0        | 58       |
| 2023-06-05 | 30.2        |          |
| 2023-07-01 | 35.0        | 40       |
| 2023-07-02 | 36.2        | 38       |
| 2023-07-03 |             | 35       |
| 2023-07-04 | 37.1        | 37       |
| 2023-07-05 | 36.8        | 39       |

---

## 📄 Your Tasks

1. **Load** the CSV into a pandas DataFrame.
2. **Convert** the `Date` column to datetime format.
3. **Clean** missing temperature values by replacing them with the mean temperature.
4. **Filter** data for **July only**.
5. **Calculate** the average temperature in July.
6. **Plot** daily temperatures for July.

---

## 💡 Hints

- Load data:
  ```python
  df = pd.read_csv('weather_data.csv')
