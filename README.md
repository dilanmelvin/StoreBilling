# StoreBilling - A Simple Billing System for Small Businesses

Welcome to **StoreBilling**, a user-friendly billing system designed specifically for small businesses! This desktop application offers a streamlined experience for managing inventory, employees, and invoices. With an intuitive interface and essential features, StoreBilling ensures efficiency in handling daily business operations.

?? **GitHub Repository:** [github.com/dilanmelvin/Storebilling](https://github.com/dilanmelvin/Storebilling)

## ?? Features
- **Admin and Employee Login:** Secure logins for both administrators and employees.
- **Inventory Management:** Easily add, update, or delete products and generate barcode stickers.
- **Employee Management:** Manage employees by adding or removing their accounts.
- **Invoice Management:** Generate bills and sales reports for easy invoicing.
- **Billing Screen:** Generate and print customer bills directly from the app.

## ?? Screenshots
- ?? **Login Screen**
- ??? **Inventory Management**

## ?? How to Get Started?
To get started with StoreBilling, follow the installation steps below to set up the environment.

### Prerequisites
Ensure you have Python 3.x installed on your system. You'll also need to install a few libraries that StoreBilling relies on.

### ?? Required Libraries
To install all the necessary libraries, just run:

```bash
pip install -r requirements.txt

# StoreBilling ????

## Key Libraries:
- **Tkinter**: For creating a simple and intuitive GUI.
- **SQLite3**: Used for local database management.
- **Pillow**: For handling images in the app.
- **Barcode**: To generate product barcodes.
- **ReportLab**: For generating PDF reports of invoices.
- **PyWin32**: Provides access to Windows-specific APIs.
- **SvgWrite**: A Python library for creating SVG (Scalable Vector Graphics) files.
- **Keyboard**: Detects and simulates keypress events in Python.

You can install these libraries manually too, in case `requirements.txt` doesn't work:

pip install tkinter pillow reportlab python-barcode sqlite3 pywin32 svgwrite keyboard

## ??? Installation
1. Clone the repository to your local machine:

git clone https://github.com/dilanmelvin/Storebilling.git

2. Navigate to the project directory:

cd Storebilling

3. Install the required libraries as mentioned above.

4. Finally, run the application:

python app.py

## ??? User Guide
- **Admin Login**: Log in with the admin credentials to access all functionalities such as employee and inventory management.
- **Employee Login**: Employees can log in using their credentials to access the billing interface.
- **Generate Bills**: Once logged in, employees can generate bills for customers, which can be printed directly from the billing screen.
- **Barcode Generation**: Admins can generate barcode stickers for all products with a single click.
- **Sales Reports**: Track daily, weekly, or monthly sales with the reporting feature.

## ?? Tech Stack
- **Python 3.x**
- **Tkinter (GUI)**
- **SQLite3 (Database)**
- **Barcode & ReportLab (Barcode generation and report creation)**
- **PyWin32 (Windows API support)**
- **SvgWrite (SVG graphics generation)**
- **Keyboard (For keyboard event handling)**

## ?? Contributing
Feel free to fork this repository and make your own changes! If you find bugs or have feature requests, feel free to open an issue. Contributions are always welcome.

- Fork it!
- Create your feature branch:

git checkout -b my-new-feature

- Commit your changes:

git commit -am 'Add some feature'

- Push to the branch:

git push origin my-new-feature

- Submit a pull request.

## ?? Connect
- **GitHub**: Dilan Melvin
- **Email**: dilanmelvin@example.com

## ?? License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy billing with StoreBilling! ????
