# Read
import pandas as pd
import numpy as np

# Load Excel file
file_path = "Complete CSV file.xlsx"

df = pd.read_excel(file_path)

# Display first 5 rows
df.head()
