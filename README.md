# Special Regimen Sheet EIM-UC

> Automated Google Apps Script solution for processing academic records (RAP) for the Special Regimen at the Escuela de Ingeniería Mecánica, Universidad de Camagüey (EIM-UC).

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📋 Overview

This repository contains Google Apps Script (GAS) code that automates the processing and management of academic records (Registro de Actividades del Profesor - RAP) for the Special Regimen program at EIM-UC. The system streamlines the workflow for managing student records, grades, and administrative tasks through Google Sheets integration.

## ✨ Features

- **Automated Data Processing**: Processes academic records (RAP) with validation and error handling
- **Sheet Operations**: Manages Google Sheets data manipulation and formatting
- **DAE Automation**: Automates Departamento de Asuntos Estudiantiles (DAE) related tasks
- **Interactive Dialogs**: User-friendly HTML-based dialogs for data input and parsing
- **Modular Architecture**: Well-organized code structure for maintainability and scalability

## 📁 Project Structure

```
Special-Regimen-Sheet-EIM-UC/
├── Code.gs                 # Main entry point and core functionality
├── DataProcessing.gs       # Data validation and processing logic
├── SheetOperations.gs      # Google Sheets API operations
├── DAE_Automation.gs       # DAE-specific automation tasks
├── Modal.html              # Modal dialog interface
├── Parser.html             # Data parsing interface
├── package.json            # Project metadata and dependencies
├── LICENSE                 # MIT License
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- A Google account with access to Google Apps Script
- Access to the Special Regimen Google Sheet at EIM-UC
- Basic understanding of Google Apps Script and JavaScript

### Installation

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/profrabs/Special-Regimen-Sheet-EIM-UC.git
   ```

2. **Open Google Apps Script Editor**
   - Navigate to your Google Sheet
   - Click on `Extensions` > `Apps Script`

3. **Copy the code files**
   - Create new script files in the Apps Script editor matching the structure above
   - Copy the contents of each `.gs` file to the corresponding script file
   - Copy the HTML files for dialogs

4. **Configure permissions**
   - Run the main function to authorize the script
   - Grant necessary permissions for Google Sheets access

## 📖 Usage

### Basic Workflow

1. **Open the Google Sheet** with the Special Regimen data
2. **Access the custom menu** that appears after the script is loaded
3. **Select the desired operation**:
   - Process new RAP records
   - Update student information
   - Generate reports
   - Run DAE automation tasks

### Code Modules

#### Code.gs
Main entry point containing:
- Menu creation and UI initialization
- Global configurations
- Main workflow orchestration

#### DataProcessing.gs
Handles:
- Data validation and sanitization
- Record processing algorithms
- Format transformations
- Error handling and logging

#### SheetOperations.gs
Manages:
- Reading and writing to Google Sheets
- Cell formatting and styling
- Range operations
- Sheet structure management

#### DAE_Automation.gs
Automates:
- Student record updates
- Administrative report generation
- Integration with DAE systems
- Batch processing operations

### HTML Dialogs

#### Modal.html
Provides interactive modal dialogs for:
- User input collection
- Confirmation prompts
- Progress indicators

#### Parser.html
Specialized interface for:
- Data parsing and import
- Format conversion
- Bulk data processing

## 🛠️ Development

### Code Style

- Follow Google Apps Script best practices
- Use meaningful variable and function names
- Add JSDoc comments for functions
- Keep functions focused and modular

### Testing

Test your changes by:
1. Creating a copy of the production sheet
2. Running operations on test data
3. Verifying results manually
4. Checking logs for errors

### Debugging

- Use `Logger.log()` for debugging information
- Check `View` > `Logs` in the Apps Script editor
- Use `console.log()` for client-side HTML debugging
- Monitor the execution transcript for performance issues

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Rafael Alberto Benítez Sánchez**

## 🙏 Acknowledgments

- Escuela de Ingeniería Mecánica (EIM)
- Universidad de Camagüey (UC)
- All contributors and users of this system

## 📞 Support

For questions, issues, or suggestions:
- Open an issue on GitHub
- Contact the development team at EIM-UC

## 📚 Additional Resources

- [Google Apps Script Documentation](https://developers.google.com/apps-script)
- [Google Sheets API Reference](https://developers.google.com/sheets/api)
- [JavaScript Best Practices](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

---

**Note**: This system is specifically designed for internal use at EIM-UC. Ensure proper authorization before accessing or modifying academic records.
