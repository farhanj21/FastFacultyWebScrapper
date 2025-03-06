# FastFacultyWebScrapper
FastFacultyWebScrapper is a web scraping project designed to extract faculty data from various campuses of FAST-NUCES and save it in CSV format for further analysis.

## Project Structure
The project contains CSV and Jupyter Notebook files for faculty data for the following campuses:
- Chiniot-Faisalabad Campus
- Lahore Campus
- Islamabad Campus
- Karachi Campus
- Peshawar Campus

## Installation
1. Clone the repository
   ```bash
   git clone https://github.com/farhanj21/FastFacultyWebScrapper.git
   ```
2. Install the required dependencies for all files
    ```bash
   pip install beautifulsoup4 pandas requests selenium fake-useragent
   ```
3. Open the relevant Jupyter Notebook and run the cells to scrape and save faculty data.
4. For "fast_faculty.ipynb" change the following frac value to the last digit of your roll number.
    ```bash
    sample_ = faculty.sample(frac=0.4)
    ```
    
