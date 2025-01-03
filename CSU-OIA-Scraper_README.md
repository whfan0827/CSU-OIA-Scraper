# CSU-OIA-Scraper

A private repository for scraping and structuring data from the CSU OIA website.

## Features
This project:
- Automatically scrapes text, PDF, and Word documents from [CSU OIA](https://oia.csu.edu.tw/).
- Saves structured data in JSON format for easy processing.
- Organizes downloaded files into separate directories (`json`, `pdfs`, `docs`).

## Project Structure
The project structure is as follows:
```
CSU-OIA-Scraper/
├── data/
│   ├── json/       # Contains structured JSON files
│   ├── pdfs/       # Contains downloaded PDF files
│   ├── docs/       # Contains downloaded Word files
├── src/
│   ├── scraper.py  # Main scraper script
├── tests/
│   ├── test_scraper.py  # Unit tests for scraper
├── README.md       # Project documentation
├── requirements.txt  # Python dependencies
├── .gitignore      # Files and directories to ignore
```

## Requirements
- Python 3.x
- Required libraries (listed in `requirements.txt`):
  - `requests`
  - `beautifulsoup4`

## Installation
To set up the project locally, follow these steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/whfan0827/CSU-OIA-Scraper.git
   cd CSU-OIA-Scraper
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the scraper:
```bash
python src/scraper.py
```

## Testing
Run unit tests using the following command:
```bash
python -m unittest discover tests
```

## Contributing
Feel free to fork this repository, create feature branches, and submit pull requests.

## License
This project is private and proprietary.
