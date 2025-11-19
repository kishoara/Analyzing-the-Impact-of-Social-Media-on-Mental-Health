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

<img width="1341" height="664" alt="stat" src="https://github.com/user-attachments/assets/f297c369-9f2d-4b81-86bf-726d8bda01ed" />


#### Variable Details

<img width="1023" height="629" alt="Variable Details" src="https://github.com/user-attachments/assets/b5df5139-d674-4234-9221-89106cfdf9dd" />


#### Histogram Plot

<img width="1384" height="884" alt="hist" src="https://github.com/user-attachments/assets/0630d489-7ed1-4b6b-9590-31a60372354f" />


#### KDE Plot

<img width="1386" height="884" alt="kde" src="https://github.com/user-attachments/assets/1833d7f6-009d-4edb-b4c4-fac10a4bd2b3" />


#### Exploring Numeric and Categorical Data

<img width="1428" height="1388" alt="numbericandcat" src="https://github.com/user-attachments/assets/24c607a1-82c4-4030-816b-0f6f5805e787" />


#### Continuous Features vs Happiness Rate

<img width="1280" height="2094" alt="catvstar" src="https://github.com/user-attachments/assets/b10a2715-a4f9-4323-b28b-1592228c96ca" />


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

    ## 🎥 Live View


https://github.com/user-attachments/assets/cb6d9435-bf86-434a-8eaa-0e18f10db946





    
