# Flipkart Product Web Scraping - Jupyter Notebook

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Collected](#data-collected)
- [Contributing](#contributing)
- [Support](#support)
- [Disclaimer](#disclaimer)

## Introduction

Flipkart is a popular e-commerce platform with a vast catalog of products. Extracting specific product information from Flipkart can be valuable for analysis or other purposes. This Jupyter Notebook addresses the problem of web scraping Flipkart's website to extract essential information about Samsung products.The main objective of this notebook is to demonstrate how to scrape product information from Flipkart for Samsung mobile phones. The notebook provides a step-by-step guide on how to perform web scraping, extract details such as product title, price, product rating, and additional specifications (if available), and analyze the data.

## Requirements

To run this Jupyter Notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- Libraries: `requests`, `BeautifulSoup`, `pandas`,`numpy`

You can install the required libraries using `pip`:

```bash
pip install requests beautifulsoup4 pandas numpy
```

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd flipkart-product-web-scraping
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the `Flipkart_Mobile_Web_Scraping.ipynb` notebook in your Jupyter environment.

## Usage

- Open the Jupyter Notebook, `Flipkart_Mobile_Web_Scraping.ipynb`.
- Follow the step-by-step instructions to perform web scraping of product information from Flipkart for Samsung mobile phones.
- Execute the code cells sequentially to scrape data, extract details, and analyze the collected information.

## Data Collected

The notebook will collect the following product information:

- Product Title
- Product Price
- Product Rating
- Num of Reviews
- Color of Product
- Display Size of Product

You can choose to export this data to a CSV file or use it for further analysis.

## Contributing
If you would like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test them.
- Create a pull request with a clear description of your changes.

## Support

If you have any questions, encounter issues, or need assistance, you can contact at saurav.sabu9@gmail.com. I am here to help you with any inquiries or problems you may have.

## Disclaimer
As I wanted to scrape the data from Flipkart website. I am ensuring that I am not performing any illegal activity using this data. I am going to use this data in my project to build some ML model and perform some data analysis.
