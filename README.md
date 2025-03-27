STEP 1: Install Required Libraries

This line ensures that all the necessary Python libraries are available. If any are missing, it installs them:
- pandas, numpy, matplotlib/seaborn, scikit-learn

![Screen Shot 2025-03-27 at 4 31 47 AM](https://github.com/user-attachments/assets/ddd11828-a43b-479e-b0a2-55503b76b992)

STEP 2: Import the Libraries

This tells Python you want to use the tools from the libraries you just installed. It’s like turning them on.

You're also importing tools for:
- Cleaning and scaling data (like LabelEncoder, StandardScaler)
- Machine learning models (KMeans for clustering, Decision Trees, etc.)
- Splitting your data for training/testing
- Measuring accuracy and performance

![Screen Shot 2025-03-27 at 4 32 15 AM](https://github.com/user-attachments/assets/d6add8ca-f47e-4047-b322-49338db6b5fd)

Step 3a: Upload Your Dataset
- Uploads a CSV file 
- Reads it into a DataFrame with pd.read_csv()
- Strips extra spaces from column names
- Shows the first 5 rows 

![Screen Shot 2025-03-27 at 4 36 26 AM](https://github.com/user-attachments/assets/c97e52b4-822a-49ec-86ff-163b85a3cb2b)

Step 3b: Exploring Data with Smart Tools
- Used the "Generate code with df" tool to auto-generate Python code from a natural language question.
- It filtered the dataset based on year, rating, and genre.
- You can also click "View recommended plots" to get instant charts based on the filtered data.
- The "New interactive sheet" lets you explore multiple data visually in a spreadsheet like view , perfect for quick analysis without writing extra code.
![Screen Shot 2025-03-27 at 4 47 56 AM](https://github.com/user-attachments/assets/de46d72e-612d-4e90-ab10-24cc721fdaf6)

Step 3c: Explore & Filter Your Results (Far Right Button)
- Interactive Filters: Use the filter boxes above each column to narrow down data by year, genre, rating, director, and more no coding required.
- Smart Search Bar: The search field lets you look across all columns at once, making it easy to locate specific results fast.

![Screen Shot 2025-03-27 at 4 49 51 AM](https://github.com/user-attachments/assets/c4744680-2f88-491f-ba77-efd67d4b00f0)

Step 3d: Export Filtered Data (Far Right Button)
- Download Options: Easily export your filtered dataset.
- Format Choices: Choose between CSV, JSON, or Markdown for flexibility.
- One-Click Copy: Use the built-in copy tool to quickly grab and save your data for use in reports or other tools.
  
![Screen Shot 2025-03-27 at 4 50 12 AM](https://github.com/user-attachments/assets/a42ded8d-e8ca-4b4a-b3cf-3da8719d9af4)

Step 4: Basic Summary Report

This step gives you a quick overview of your dataset:
- Rows & Columns: Shows how many rows and columns your file has.
- Data Types: Tells you what kind of data is in each column (like numbers or text).
- Missing Values: Shows if any data is missing in each column.
- Basic Stats: Gives simple stats (like average, min, and max) for number columns.
  
![Screen Shot 2025-03-27 at 4 58 39 AM](https://github.com/user-attachments/assets/60519b68-f207-434e-abd7-05aa8a967bf2)
