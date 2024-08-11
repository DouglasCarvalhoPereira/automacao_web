# 🛒 Web Automation - Price Comparison Script

This repository contains a Python script designed to automate the process of comparing product prices across different websites. The script identifies the lowest price and can trigger an alert if the price difference exceeds a specified threshold, making it a useful tool for monitoring and optimizing product purchases.

## 📂 Project Structure

- **`Pesquisa de preço - Automação Web.ipynb`**: Jupyter Notebook containing the script for price comparison.
- **`Produtos.xlsx`**: Excel file where the product data and price comparisons are stored.
- **`Como agendar uma tarefa no Windows.txt`**: Instructions for scheduling the script as a task on Windows.
- **`.ipynb_checkpoints`**: Directory with checkpoints for the Jupyter Notebook.
- **`LICENSE`**: The project’s license file.

## 🎯 Objective

The primary objective of this project is to automate the process of finding the cheapest price for a product. The script:

- Compares prices from multiple websites.
- Updates the prices automatically.
- Registers the lowest price in an Excel spreadsheet.
- Creates an alert if the price difference between the lowest and other prices exceeds 20%.

This automation can be used for various products simultaneously, making it a powerful tool for saving money and optimizing purchasing decisions.

## 🚀 Getting Started

### Prerequisites

Before running the script, ensure you have the following Python libraries installed:

```bash
pip install pandas selenium openpyxl
```

### Running the Script

1. **Open the Jupyter Notebook**: Load the `Pesquisa de preço - Automação Web.ipynb` file in Jupyter Notebook or JupyterLab.
2. **Execute the Script**: Run the cells in the notebook to start the price comparison process.
3. **View Results**: The results will be stored and updated in the `Produtos.xlsx` file.

### Scheduling the Task on Windows

To automate the script execution, you can schedule it using Windows Task Scheduler. Instructions are provided in the `Como agendar uma tarefa no Windows.txt` file.

## 📊 How It Works

- **Product List**: The script takes a list of products and their respective URLs from the `Produtos.xlsx` file.
- **Price Comparison**: It scrapes prices from the provided URLs using Selenium and compares them.
- **Alert Generation**: If the price difference between the cheapest option and others exceeds 20%, an alert is generated.
- **Automatic Updates**: The `Produtos.xlsx` file is updated automatically with the latest price information.

## 🛠 Technologies Used

- **Python**: Core programming language.
- **Pandas**: For data manipulation and storage.
- **Selenium**: For web scraping and price extraction.
- **Openpyxl**: For reading and writing to Excel files.

## 📧 Contact

For questions, suggestions, or collaboration opportunities, feel free to reach out via email at [carvalhodouglaspereira@gmail.com](mailto:carvalhodouglaspereira@gmail.com).

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
