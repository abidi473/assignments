# ChatGPT's code

import pandas as pd

# 1. Read the original CSV file
df = pd.read_csv(r"C:\Users\Abid\Downloads\Assignment 12 draft\teaching_prices_messy.csv")

# 2. Remove duplicate rows
df = df.drop_duplicates()

# 3. Save the cleaned data as a new CSV file
df.to_csv("teaching_prices_clean.csv", index=False)

print("Data cleaning completed!")
print("Original file remains unchanged.")
print("Cleaned file saved as teaching_prices_clean.csv")

# 8. Display the cleaned dataset information
print(df.info())
print(df.head())
