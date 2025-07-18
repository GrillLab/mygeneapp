# Project Name (Lab Maintained Fork)

> 🔄 Forked from [@Jamezquita1/mygeneapp][(https://github.com/Jamezquita1/mygeneapp.git)]

This repository is maintained by the Grill Lab. It is based on code originally developed by Jonathan Amezquita, and adapted here for use in our lab workflows.

### Original Version
The original project is maintained independently by the author and can be found here:  
➡️ https://github.com/Jamezquita1/mygeneapp.git


# mygeneapp

A Python tool for querying and organizing gene-related data from WormBase. This app retrieves gene descriptions, protein homology (BLASTp), phenotypes, and strain information, then compiles the results into a structured Excel workbook.

## Features

- Query multiple genes from WormBase
- Retrieve gene descriptions, BLASTp results, phenotypes, and strain data
- Organize all results in a well-formatted Excel file with multiple tabs

## Installation

1. Clone the repository:
git clone https://github.com/Jamezquita1/mygeneapp.git
cd mygeneapp

markdown
Copy
Edit

2. Install dependencies:
pip install -r requirements.txt

shell
Copy
Edit

## Usage

Run the app:
python main.py

markdown
Copy
Edit
(Or use the correct entry point script name.)

## Output

Generates an Excel file with:
- Gene Descriptions
- Protein Homology
- Phenotypes
- Strain Info
- Failed Queries (if any)

## Dependencies

- `requests`
- `openpyxl`
- `beautifulsoup4`
- `pandas`

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Jonathan Amezquita**  
GitHub: [@Jamezquita1](https://github.com/Jamezquita1)

## Acknowledgments

Developed during PhD research at University of Washington/Seattle Children's Research Institute in the Grill Lab.
