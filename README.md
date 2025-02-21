# Automated Invoice Generator

This project is an automated invoice generator that reads invoice data from a CSV file and generates PDF invoices using the `fpdf` library.

## Features

- Reads invoice data from a CSV file.
- Generates PDF invoices with a custom header and footer.
- Saves each invoice as a separate PDF file.

## Prerequisites

- Python 3.x
- `fpdf` library

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Automated-Invoice-Generator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Automated-Invoice-Generator
    ```
3. Install the required dependencies:
    ```sh
    pip install fpdf
    ```

## Usage

1. Place your invoice data in a CSV file. The CSV file should have the following columns:
    ```
    Invoice Number, Date, Customer Name, Address, Item, Quantity, Price, Total Amount
    ```
2. Update the `csv_file` variable in `invoice_generator.py` to point to your CSV file:
    ```python
    csv_file = "path/to/your/invoices.csv"
    ```
3. Run the script to generate the invoices:
    ```sh
    python invoice_generator.py
    ```

## Example

Here is an example of how the CSV file should look:
```csv
Invoice Number,Date,Customer Name,Address,Item,Quantity,Price,Total Amount
1,2023-10-01,John Doe,123 Elm St,Widget,2,10.00,20.00
2,2023-10-02,Jane Smith,456 Oak St,Gadget,1,15.00,15.00
```

After running the script, you will find the generated PDF invoices in the project directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [fpdf](http://www.fpdf.org/) - A Python library for PDF generation.

## Contact

For any questions or suggestions, please contact Amy at automate.analyze@gmail.com.
