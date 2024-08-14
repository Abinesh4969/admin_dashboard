#Sales Performance Dashboard
Overview
The Sales Performance Dashboard is a web application designed to manage and analyze sales data. Built using Laravel 11 and PHP 8.2, this application allows users to input sales data, perform calculations, view data in both list and detailed formats, visualize data with charts, and generate reports in PDF format.

Features
Sales Data Management: CRUD operations for sales entries including product name, sales amount, sales date, and salesperson.
Calculations: Compute total sales, average sales per product, and total sales per salesperson.
Views: List view for all sales entries and detailed view for individual entries.
Visual Graphics: Interactive charts using Chart.js to visualize sales data.
Reporting: PDF download functionality for sales reports and charts.

#Requirements
PHP 8.2
Laravel 11
Composer
MySQL 

Clone the Project
cd sales_admin_dashboard
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve

#Usage
#Sales Data Management
Create: Add new sales entries via the "Add Sale" form.
Read: View sales entries in the list view.
Update: Edit existing sales entries from the list or detailed view.
Delete: Remove sales entries as needed.

#Calculations

1-Total Sales
2-Average Sales Per Product
3-Total Sales Per Salesperson

#Views:
List View: Displays a table of all sales entries with pagination.
Detailed View: Shows detailed information and calculated statistics for each sales entry.
Visual Graphics
Charts: View visualizations for total sales per month, average sales per product, and top-performing salespersons using Chart.js.
Reporting
PDF Reports: Generate and download sales reports in PDF format through the reporting section.
Technologies Used
Laravel 11: PHP web application framework.
PHP 8.2: Server-side scripting language.
Chart.js: JavaScript library for creating charts.
MySQL: Database management system.
dompdf : PDF generation.
