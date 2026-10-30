# instamart-customer-intelligence-copilot
Customer Intelligence and Support Copilot Capstone Project using Python, SQL, Machine Learning, NLP and RAG.
Instamart Customer Intelligence & Support Copilot

Project Overview

This project analyzes Instamart customer orders and support tickets. It focuses on data cleaning, customer segmentation, lapse-risk identification, ticket classification, privacy protection, policy-based question answering, and refund eligibility.

Objectives

- Clean and validate raw customer, product, order, and ticket data.
- Store cleaned data in an SQLite database.
- Segment customers and identify customers who may have stopped ordering.
- Classify support tickets and protect sensitive information.
- Evaluate policy question answering and refund-related scenarios.

Technologies Used

- Python 3.11+
- Pandas
- NumPy
- Scikit-learn
- SQLite
- Jupyter Notebook / Google Colab

Project Structure

- "generate_data.py" — Generates the project dataset.
- "mock_llm.py" — Provides the supplied mock language-model interface.
- "Instamart_Customer_Intelligence_Capstone.ipynb" — Main project notebook.
- "data/raw/" — Raw input datasets.
- "data/processed/" — Database and processed datasets.
- "data/policies/" — Policy documents.
- "outputs/" — Generated result files.

How to Run

1. Clone or download this repository.
2. Install the required dependencies.
3. Run the supplied data-generation script.
4. Open and execute the notebook in an environment that supports Python.
5. Check the generated files in the "outputs/" folder.

Outputs

The project generates customer lapse and segmentation results, classified support tickets, privacy-protected tickets, refund eligibility results, and refund-agent scenario results.

Notes

The project uses a supplied mock LLM interface and generated datasets. Results depend on the implemented rules and evaluation scenarios.
