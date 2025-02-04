# Minverva Helper: Automated Course Scheduling System

This repository contains the python code, row data and report for the project-Minverva Helper.It is the Final project for the McGill course: Decision Analytics.

## Overview
The Minverva Helper leverages machine learning and optimization techniques to streamline the course selection process. The goal is to recommend an optimal set of courses based on user-defined preferences, constraints, and historical data.

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
