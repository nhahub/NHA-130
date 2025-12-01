# UK_Train_Rides

Analyze train travel patterns across the UK and visualize insights using Python and Power BI.

## Team Members
- Abdallah Nader Gamal Eldin Etman
- Abdelhamed Abdullah Abdelhamed
- Anas Osama Ali Attya Dorgham
- Hisham Nazieh Abdelsamad Ali
- Mohamed Alaa El-Din ElHabbal


## Project Structure
- `code/` – Python scripts for data cleaning and analysis  
- `dataset/` – Excel files with train ride data  
- `dashboard/` – Power BI dashboard file

## Dataset Information

This project uses a **mock train ticket dataset** for **National Rail (UK)** covering the period:

**🗓 January 2024 → April 2024**

### What the dataset includes
- Type of ticket (Advance, Off-Peak, Anytime, etc.)
- Date of purchase
- Date & time of each journey  
- Departure and arrival stations  
- Delay information (scheduled vs. actual times)  
- Ticket price  
- Railcard usage  
- Additional metadata for analysis

## Features
- Clean and process train ride data  
- Explore peak hours, delayed and cancelled journeys, and station usage.
- Visualize trends with interactive Power BI dashboard

## Requirements
- Python 3.x, to run the iPynb files
- Libraries: pandas, numpy, matplotlib, seaborn  
- Power BI Desktop

## How to run the iPynb Files

1. **Clone the Repository** <br />
   First, clone the repository to your local machine:
   ```bash
   git clone git@github.com:nhahub/NHA-130/.git
   cd NHA-130
   ```
      <br />
2. **<mark>Optional:</mark> Create a Virtual Environment** <br />
   It's recommended to use a virtual environment to avoid conflicts with existing Python libraries or versions you may have installed globally. To create and activate a virtual environment, follow these steps:

   - **<div style="display: flex; align-items: bottom;"><span>Linux/macOS </span></div>** 
   ```
   python3 -m venv venv          # Create virtual environment
   source venv/bin/activate      # Activate virtual environment
   ```

- **<div style="display: flex; align-items: bottom;"><span>Windows </span></div>** 

    - Command Prompt (CMD):
    ```
    python -m venv venv          # Create virtual environment
    venv\Scripts\activate        # Activate virtual environment
    ```
    - PowerShell:
    ```
    python -m venv venv          # Create virtual environment
    .\venv\Scripts\Activate.ps1  # Activate virtual environment
    ```
     <br />
3. **Install Dependencies**<br />
   After activating the virtual environment, install the required libraries using the ```requirements.txt``` file:
   ```
   pip install -r requirements.txt
   ```

   If you encounter the error ```externally managed environment``` while trying to use ```pip install```, this is a common issue on Linux systems. You can resolve it by installing dependencies using your system package manager:
   ```
   sudo apt install -r requirements.txt
   ```

   <br />

## How to Use
1. Check dataset in `dataset/`.
2. Run cleaning.ipynb in `code/`  or open the web page version.
3. Open `dashboard/UK_Train_Rides.pbix` in Power BI.
