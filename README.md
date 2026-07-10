# Dolibarr Inventory and POS Evaluation

This repository contains documentation, sample data, and setup notes for an ITEC 4366 final project evaluating Dolibarr ERP/CRM as a locally hosted open-source business solution.

The reference business for this project is Barbour Farms Country Store in Byron, Georgia. The business problem being evaluated is manual inventory management between in-store sales and online product availability. Dolibarr was selected because it can manage products, stock, warehouses, barcodes, sales records, and point-of-sale activity from a locally installable web application.

## Application

* Application: Dolibarr ERP/CRM
* Project type: Open-source business solution evaluation
* Local environment: XAMPP, Apache, PHP, MySQL
* Local demo URL: `http://localhost/dolibarr/htdocs`
* Main modules used: Products, Stocks/Warehouses, Barcode, TakePOS

## Features Demonstrated

1. Product records with SKU and barcode values
2. Warehouse-based stock tracking
3. TakePOS sale process
4. Automatic stock decrease after a sale
5. MGA-inspired branding/customization
6. Discussion of future website/e-commerce synchronization

## Repository Contents

* `documentation/` — final write-up and presentation outline
* `sample-data/` — sample products and demo test steps
* `notes/` — installation and troubleshooting notes

## Important Note

This repository does not include a full XAMPP installation, database files, real passwords, or sensitive configuration files. The official Dolibarr package should be downloaded from the official Dolibarr website or repository. This repo is intended to document the local evaluation and demonstration completed for the class project.

