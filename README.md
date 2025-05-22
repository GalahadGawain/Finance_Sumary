# Simple Finance App

A Streamlit-based application for categorizing and analyzing bank transactions. This tool helps users gain insights into their spending habits by visualizing transaction data and allowing for custom categorization.

## Features

- **Upload Bank Statements:** Easily upload CSV files containing your bank transactions.
- **Transaction Categorization:** Automatically categorizes transactions based on predefined keywords and allows for custom category management.
- **Interactive Data Display:** View your transactions in a clear, sortable, and searchable table.
- **Financial Summaries:** Get an overview of your income and expenses.
- **Payment Status Analysis:** Visualize payment statuses (e.g., credit, debit) with interactive charts.
- **Category-wise Breakdown:** Understand spending patterns across different categories.

## Installation

1.  **Clone the repository (if applicable):**

    ```bash
    git clone [your-repository-url]
    cd [your-repository-name]
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    _(Note: You will need to create a `requirements.txt` file if you haven't already. It should contain `streamlit`, `pandas`, `plotly-express`.)_

## Usage

1.  **Run the Streamlit application:**
    ```bash
    streamlit run main.py
    ```
2.  **Open in Browser:** The application will open in your default web browser. If not, navigate to `http://localhost:8501`.
3.  **Upload your `sample_bank_statement.csv`:** Use the file uploader to load your transaction data.
4.  **Manage Categories:** Add or remove categories and associate keywords for automatic categorization.
5.  **Explore Data:** Interact with the tables and charts to analyze your financial data.

## Project Structure

- `main.py`: The main Streamlit application script.
- `sample_bank_statement.csv`: An example bank statement CSV file.
- `categories.json`: Stores the custom transaction categories and their associated keywords.

## Contributing

Contributions are welcome! Please feel free to submit an issue or a pull request.

## License

MIT
