# Analyzing the Impact of Social Media on Mental Health

This project is a **Python and React-based interactive dashboard** analyzing the relationship between social media usage and mental health metrics using a sample dataset. The visualizations are created with **Recharts** and styled using **Tailwind CSS**.

--- 

## 🚀 Project Setup

1. **Create React App:**
   
   
   
   ```bash
   npx create-react-app Analyzing-the-Impact-of-Social-Media-on-Mental-Health
   cd Analyzing-the-Impact-of-Social-Media-on-Mental-Health
   ```

2. **Install Dependencies:**

```bash
npm install recharts lucide-react papaparse
npm install -D tailwindcss@3.4.1 postcss autoprefixer
```

3. **Configure Tailwind CSS:**
   
   ```bash
   /** @type {import('tailwindcss').Config} */
   module.exports = {
     content: [
       "./src/**/*.{js,jsx,ts,tsx}",
     ],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

`postcss.config.js`:

```bash
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}
```

`src/index.css`:

```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

4. **Add CSV dataset:** Place your CSV file in the `public/` folder.

5. **Run the Development Server:**
   
   ```bash
   npm start
   ```

## 📊 Dataset Overview

The dataset contains **500 records** and **10 features**. It focuses on daily habits, mental health metrics, and social media usage.

| Attribute                   | Description                                            | Data Type                       | Example |
| --------------------------- | ------------------------------------------------------ | ------------------------------- | ------- |
| `User_ID`                   | Unique identifier for each user                        | String                          | U001    |
| `Age`                       | Age of the user                                        | Number                          | 23      |
| `Gender`                    | Gender of the user                                     | Categorical (Male/Female/Other) | Female  |
| `Daily_Screen_Time(hrs)`    | Average daily screen time on social media in hours     | Number                          | 7.4     |
| `Sleep_Quality(1-10)`       | Self-reported sleep quality (1 = poor, 10 = excellent) | Number                          | 6       |
| `Stress_Level(1-10)`        | Self-reported stress level (1 = low, 10 = high)        | Number                          | 7       |
| `Days_Without_Social_Media` | Number of days without using social media              | Number                          | 1       |
| `Exercise_Frequency(week)`  | Number of exercise sessions per week                   | Number                          | 3       |
| `Social_Media_Platform`     | Primary social media platform used                     | Categorical                     | TikTok  |
| `Happiness_Index(1-10)`     | Self-reported happiness level                          | Number                          | 8       |

## ## 🐍 Python Analysis

All statistical analysis and visualizations were generated using **Pandas + Seaborn + Matplotlib**.

#### Statistical View



#### Variable Details



#### Histogram Plot



#### KDE Plot



#### Exploring Numeric and Categorical Data



#### Continuous Features vs Happiness Rate

#### 

## 📌 Features

- **Descriptive Statistics:** Mean, median, standard deviation, min, and max values for numeric features.

- **Demographic Analysis:** Distribution of users by gender and social media platform.

- **Screen Time Distribution:** Visualization of daily social media usage.

- **Age Group Analysis:** Comparison of screen time, stress, and happiness across age groups.

- **Correlation Analysis:** Explore relationships between screen time, sleep quality, stress, exercise, and happiness.

- **Key Insights:** Highlight important trends and recommendations.
  
  ## 🖥️ Tech Stack
  
  - **Frontend:** React
  
  - **Charts & Visualization:** Recharts
  
  - **Styling:** Tailwind CSS
  
  - **CSV Parsing:** Papaparse (optional)
  
  - **Icons:** Lucide React
  
  - **Python:** Pandas, Numpy, Seaborn, Matplot, Stat
