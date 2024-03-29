# Project Structure

This document outlines the structure of the project and provides an overview of the different tools that make up this Python application for monitoring e-commerce prices, as well as how the work will be separated.

## General idea

The application is meant to track the prices of products on e-commerce websites like Amazon, eBay, or Walmart.  It will use web scraping techniques to extract product information, including prices, and availability.  
The application will periodically scrape product data and compare prices over time, alerting users trough email when there are price drops or promotions, and providing links to the product pages for quick purchase.  
Users will be able to track multiple products, set price thresholds, and customize certain aspects of the application such as how frequently should the product be checked.  
The application , ATM, is not meant to have any GUI and will be run from the command line.
### Additional features:
- Be able to shut down the program and re-run it without losing the data.

## Structure / user experience:
- Main menu:
  - Add product
    - TODO whether to add product by name or by URL
    - Set settings and information
  - List products
    - Show all products (then you can select one to see more details)
      - Show product details
  - Remove product (confirm with user)
  - Modify product settings / thresholds
  - Exit

## Tools & Libraries:
These are the current candidates for the tools and libraries that will be used in the project:

- **Scrapy**: An open-source and collaborative web crawling framework for Python. It provides a high-level API for extracting structured data from websites.
- **Notification**: TODO: look for a good candidate
- **TinyDB**: A lightweight, document-oriented database for Python that allows you to store and query data in JSON format.

## Separation of work:
TODO