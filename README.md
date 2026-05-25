# Mental-Health-Care

Descriptive statistical analysis in R exploring how mental health care utilization varies across demographic groups in the United States. Dataset is a long-format U.S. survey file where each row represents one subgroup's reported care rate over the last 4 weeks.
What it does

Cleans and standardizes a long-format survey dataset using tolower(), trimws(), and row-indexed recoding to create six analytical category columns: Age (collapsed to 3 bands), Sex/Gender, Race/Ethnicity, Education (collapsed to 2 levels), Disability Status, and Symptom Presence
Computes overall descriptive statistics using base R summary() and psych::describe() for skewness, kurtosis, and standard error
Generates grouped summary tables (mean, SD, min, max, N) for all six demographic dimensions using dplyr group_by + summarise pipelines
Produces four base R visualizations: scatter plot with regression line (Value vs Lower CI), boxplot by age group, jitter/strip chart by sex, and barplot of mean utilization by education level
