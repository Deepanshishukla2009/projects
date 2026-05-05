📊 Capstone Python Project

🧹 Stage 1: Data Preprocessing (Google Colab)
The raw dataset is cleaned and processed using the preprocessing script DataPreprocessing.py.

🔧 Steps Performed:
🗑️ Removed duplicate records
🧼 Cleaned column names
🔢 Converted data types (Year, Month, numeric fields)
⚠️ Handled missing values
⚙️ Created new features:
📊 Gender Ratio
📈 Efficiency
📉 Gap Analysis
📅 Created Date column
🔃 Sorted data chronologically

📁 Output:
A cleaned dataset is generated:
➡️ You can save it with any name
Example: clean_death_data.csv

🖥️ Stage 2: GUI Application (Tkinter)
The GUI is implemented using the GUI code file.

✨ Features:
📊 Dashboard (Total, Male, Female deaths)
📋 Data viewing with filters (Year, Zone)
📈 Graph analysis:
Year-wise gender comparison
Registration vs certification
Zone-wise heatmap
📂 Load dataset dynamically
🧾 Help & Terms section

▶️ How to Run the Project

🔹 Step 1: Run Data Preprocessing (Colab)
Open the preprocessing file in Google Colab
Upload dataset or connect Google Drive
Run all cells
✅ This will generate:
clean_death_data.csv

🔹 Step 2: Run GUI Application

📦 Install required libraries: pip install pandas matplotlib pillow

▶️ Run the GUI file: python GUI code.py

🔹 Step 3: Load Dataset in GUI
Click "Load Data" button
Select clean_death_data.csv

⚙️ How the System Works

🔹 Raw dataset is preprocessed in Google Colab
🔹 Cleaned dataset is saved as CSV
🔹 GUI loads the cleaned dataset
🔹 User interacts with:
Dashboard
Filters
Graphs
📁 Project Structure
project/
│
├── DataPreprocessing.py
├── GUI code.py
├── clean_death_data.csv
├── screenshots/
└── README.md

⚠️ Important Notes
❗ Preprocessing must be run before using GUI
❗ GUI depends on cleaned dataset
❗ Dataset must be loaded manually in GUI
❗ Paths may need adjustment for local system
💡 Key Features
✅ End-to-end data pipeline
✅ Feature engineering for insights
✅ Interactive GUI dashboard
✅ Zone-based heatmap visualization
✅ Real-world dataset handling

👩‍💻 Author

Deepanshi Shukla

Harshita Mathur

🚀 Future Improvements
🔮 Add ML prediction model

⚡ Automate dataset loading

🌐 Deploy as web application
