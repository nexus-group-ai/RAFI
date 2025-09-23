# RAFI - Randomised Automated Fairness Initiative

A web-based tool for conducting fair and transparent raffles or winner selections from uploaded participant data.

## 🎉 Live Demo

Visit the live application: [https://nexus-group-ai.github.io/rafi/](https://nexus-group-ai.github.io/rafi/)

## Features

- **File Upload**: Support for CSV and Excel (.xlsx, .xls) files
- **Drag & Drop**: Easy file upload with drag and drop functionality
- **Attendance Filtering**: Automatically filters participants based on attendance status
- **Animated Selection**: Exciting winner selection animation
- **Responsive Design**: Works on desktop and mobile devices
- **Sound Effects**: Celebration sound when picking a winner
- **Visual Effects**: Balloon animation for winner announcement

## How to Use

1. **Upload Your File**: Choose a CSV or Excel file containing participant data
2. **Required Columns**: Ensure your file has these columns:
   - `First Name` (or variations like `first name`, `firstname`)
   - `Last Name` (or variations like `last name`, `lastname`) 
   - `Attendance` (with values: 1 = Present, 0 = Absent)
3. **Review Participants**: Check the list of eligible participants
4. **Pick Winner**: Click "Pick a Winner!" to start the animated selection
5. **Celebrate**: Watch the animation and see the winner announcement!

## File Format Requirements

### Required Columns
- **First Name**: First name of participant
- **Last Name**: Last name of participant  
- **Attendance**: Numeric value (1 = eligible, 0 = not eligible)

### Supported File Types
- CSV files (.csv)
- Excel files (.xlsx, .xls)

### Example Data Structure
```csv
First Name,Last Name,Attendance
John,Doe,1
Jane,Smith,1
Bob,Johnson,0
Alice,Williams,1
```

## GitHub Pages Setup

This project is configured for GitHub Pages deployment:

1. The main application files are in the `/docs` folder
2. GitHub Pages serves from the `/docs` folder on the main branch
3. The site is automatically deployed when changes are pushed to main

## Development

### Streamlit Version
The original Streamlit version is available in `app.py` for local development:

```bash
pip install streamlit pandas openpyxl
streamlit run app.py
```

### Web Version
The GitHub Pages compatible version is in `/docs/index.html` and uses:
- Pure HTML/CSS/JavaScript
- Bootstrap 5 for styling
- SheetJS for Excel file parsing
- Font Awesome for icons

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5, Custom CSS with CSS Variables
- **File Processing**: SheetJS (xlsx library)
- **Icons**: Font Awesome
- **Deployment**: GitHub Pages

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

© 2025 Nexus Group AI. All rights reserved.

## About Nexus Group AI

Developed by Nexus Group AI to ensure fairness and transparency in winner selection processes.

- **GitHub**: [https://github.com/nexus-group-ai](https://github.com/nexus-group-ai)
- **LinkedIn**: [https://www.linkedin.com/company/101388118/](https://www.linkedin.com/company/101388118/)