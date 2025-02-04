# Minverva Helper: Automated Course Scheduling System

This repository includes the Python code, raw data, and report for the "Minerva Helper" project, leveraging machine learning and optimization techniques to streamline the course selection process. It is the final project for the McGill University course: Decision Analytics.

## Overview

The "Minerva Helper" project uses machine learning and optimization techniques to simplify the course selection process. It recommends an optimal set of courses based on user preferences, constraints, and historical data. Features include automated course recommendations, schedule optimization, historical analysis, and user-defined constraints like preferred times and instructors.

## Features
- **Automated Course Recommendation**: Uses a weighted scoring model to rank courses based on user preferences.
- **Schedule Optimization**: Ensures course schedules are conflict-free and meet degree requirements.
- **Historical Analysis**: Incorporates past course data to predict availability and difficulty.
- **User Constraints Handling**: Allows users to set constraints like preferred time slots, instructors, and workload limits.

## Technologies Used
- **Programming Languages**: Python
- **Libraries & Tools**: Pandas, NumPy, Scikit-learn, PuLP (for optimization)
- **Data Processing**: Scraping and cleaning course information

## How It Works
1. **Data Collection**: Scrapes course catalog data and past enrollment statistics.
2. **Preprocessing**: Cleans and structures data for analysis.
3. **Scoring Model**: Assigns a weighted score to each course based on relevance, difficulty, and availability.
4. **Optimization Algorithm**: Uses linear programming to generate the best possible schedule.

## Future Enhancements
- Integration with university APIs for real-time course data.
- User interface for interactive course selection.
- More advanced machine learning models for course recommendations.
