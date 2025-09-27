# SleepScope Lifestyle and Sleep Analysis

## Overview
SleepInc has shared anonymized lifestyle and sleep data from their SleepScope app. The dataset tracks demographics, physical activity, and health metrics alongside sleep quality indicators. As a data science consultant, the goal is to analyze these factors and identify relationships between **exercise, gender, occupation, and sleep quality**.

This README outlines the dataset, objectives, and how to use the analysis code.

---

## Dataset
**File:** `sleep_health_data.csv`  
**Rows:** 374 individuals  
**Columns:** 13

| Column                           | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| Person ID                        | Unique identifier for each individual                                       |
| Gender                           | Male/Female                                                                 |
| Age                              | Age in years                                                                |
| Occupation                       | Profession of the individual                                                 |
| Sleep Duration (hours)           | Average sleep hours per day                                                  |
| Quality of Sleep (1–10)          | Self-rated sleep quality                                                     |
| Physical Activity Level (min/day)| Average minutes of physical activity                                         |
| Stress Level (1–10)              | Self-rated stress level                                                      |
| BMI Category                     | Underweight, Normal, Overweight                                              |
| Blood Pressure (sys/dia)         | Average systolic/diastolic blood pressure                                    |
| Heart Rate (bpm)                 | Average resting heart rate                                                   |
| Daily Steps                      | Average number of steps per day                                              |
| Sleep Disorder                   | None, Insomnia, or Sleep Apnea                                               |

---

## Objectives
1. Analyze how **exercise levels** relate to sleep quality.
2. Compare **gender-based differences** in sleep patterns and quality.
3. Explore how **occupation** impacts lifestyle and sleep.
4. Identify patterns between lifestyle metrics (stress, BMI, steps) and **sleep quality**.
5. Assess prevalence of **sleep disorders** and related risk factors.

---

## Tools
- Python 3.x  
- Libraries:
  - `pandas` for data wrangling
