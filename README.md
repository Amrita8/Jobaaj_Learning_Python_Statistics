# Recruitment & Salary Statistical Analysis

## Project Overview

This project performs an exploratory and statistical analysis of recruitment data to uncover patterns in hiring decisions, salary distributions, and departmental performance. The analysis aims to provide actionable insights for improving recruitment strategies and compensation structures.

## Dataset Description

The analysis utilizes a recruitment dataset (originally `Statistics.xlsx`) containing **7,168 entries** with the following key features:

* **application_id**: Unique identifier for each applicant.
* **Interview Taken on**: Timestamp of the interview.
* **Status**: Final hiring decision (e.g., Hired, Rejected).
* **event_name**: Gender identification of the applicant.
* **Department**: The department for which the interview was conducted (e.g., Service, Operations, Finance).
* **Post Name**: The specific role or level (e.g., c5, c8, i4).
* **Offered Salary**: The salary amount offered to the candidate.

## Key Analysis Steps

1. **Data Cleaning**:
* Identification and removal of null values in the `Offered Salary` column.
* Filtering out invalid or placeholder data in gender categories.


2. **Hiring Trends**:
* Quantitative analysis of hiring volume segmented by gender.


3. **Salary Distribution**:
* Statistical summary of salary offerings across the organization.
* Comparative analysis of average salaries by department.


4. **Departmental Performance**:
* Evaluation of application volume per department.
* Analysis of Hired vs. Rejected ratios to identify recruitment bottlenecks.



## Key Insights

* **Salary Disparity**: Significant variation in average offered salaries exists across departments, with **General Management, Purchase, and Service Departments** offering higher averages compared to Marketing and Sales.
* **Volume Distribution**: The **Operations and Service Departments** handle the highest volume of applications and have the highest numbers of both hires and rejections.
* **Compensation Skew**: Most salaries are concentrated in the lower to mid-brackets, with a sharp decrease in hiring for high-salary positions.

## Requirements

To run this notebook, you need the following Python libraries installed:

* `pandas`
* `numpy`
* `openpyxl` (for Excel file support)

## Usage

1. Ensure your dataset is named `Statistics.xlsx` and placed in the correct directory (the notebook currently points to a Google Drive path).
2. Open `Statistics.ipynb` in a Jupyter environment or Google Colab.
3. Execute the cells sequentially to reproduce the data cleaning and analysis.

*** ### Suggestions for GitHub:

* **Visualizations**: Since your notebook likely generates charts (histograms/bar plots), consider saving them as `.png` files and embedding them in the README to make it more visually appealing.
* **License**: Add a `LICENSE` file (like MIT) to your repository so others know how they can use your code.
