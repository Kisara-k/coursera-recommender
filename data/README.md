# Coursera Courses Dataset

## Introduction

This dataset contains metadata for courses available on Coursera, the popular online learning platform. The data provides comprehensive information about course offerings, including course details, learning outcomes, skills covered, and instructor information.

**Source**: [Coursera Courses Metadata for Analytics 2025](https://www.kaggle.com/datasets/longnguyen3774/coursera-courses-metadata-for-analytics-2025)

## Dataset Structure

| Field            | Description                                                                   |
| ---------------- | ----------------------------------------------------------------------------- |
| `url`            | Official Coursera course URL                                                  |
| `name`           | Course title                                                                  |
| `category`       | Primary category (e.g., "Information Technology", "Business", "Data Science") |
| `what_you_learn` | Key learning outcomes (if available)                                          |
| `skills`         | Comma-separated list of associated skills                                     |
| `language`       | Course language                                                               |
| `instructors`    | Instructor names or identifiers                                               |
| `content`        | Course overview and structure summary                                         |

## Data Quality

- **Complete Columns**: All columns except `what_you_learn` have no missing values
- **Data Cleaning**: All columns have been cleaned and standardized
