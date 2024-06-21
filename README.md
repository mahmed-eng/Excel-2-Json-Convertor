# Excel to JSON Converter

This project provides a simple web application to convert Excel files (.xlsx, .xls) to JSON format. The application also allows users to view the Excel data in a tabular format and download the converted JSON file.
### URL: https://excel2jsonconvertor.web.app/

## Features

- Convert Excel files to JSON format.
- Display Excel data in a tabular format.
- Download the converted JSON file.
- User-friendly interface with responsive design.

## Technologies Used

- HTML
- CSS
- JavaScript
- [SheetJS (xlsx)](https://cdnjs.com/libraries/xlsx)

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mahmed-eng/Excel-2-Json-Convertor.git
   cd excel-to-json-converter

2. Open the index.html file in your preferred web browser.

3. Follow the on-screen instructions to select an Excel file and convert it to JSON.

# File Structure
.
├── index.html
├── README.md
└── assets
    └── xlsx.full.min.js

### Code Explanation
### HTML
The main structure of the application is defined in the index.html file. The file includes the necessary elements for user interaction, such as file input, buttons for converting and displaying data, and containers for displaying the JSON output and table.

### CSS
The styling is embedded within the index.html file, providing a clean and responsive design. Key styles include:
Flexbox layout for centering the content.
Styling for buttons and containers.
Responsive design elements to ensure usability on different screen sizes.

### JavaScript
The functionality is powered by JavaScript, using the SheetJS (xlsx) library to handle Excel file reading and conversion.

## File Reading:
The file input element triggers the reading of the selected Excel file.

## Conversion to JSON: 
The XLSX.read and XLSX.utils.sheet_to_json methods are used to read and convert the Excel file to JSON format.

## Displaying Data:
The converted JSON data is displayed in a preformatted text block and optionally as an HTML table.

## Downloading JSON:
A download button allows users to save the JSON data as a file.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
SheetJS (xlsx) for providing the excellent library to handle Excel file operations.

## Contributing
Contributions are welcome! Please create an issue first to discuss what you would like to change.

## Contact
For any inquiries, please contact 
### LinkedIn: https://www.linkedin.com/in/m-ahmed-hashmi-a119a021b/

### Github: https://github.com/mahmed-eng
