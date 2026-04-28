# ITPM-Assignment01-IT23634008_SECOND
### Setup Instructions

1. Install Python 3.13
2. Install dependencies:
   pip install playwright openpyxl
3. Install browsers:
   playwright install

### Run the script

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
