🛒 nopCommerce Automation Testing Project
This project automates the end-to-end testing of the nopCommerce demo website using Selenium WebDriver with Java, TestNG, and Maven. It follows the Page Object Model (POM) design pattern for maintainability and scalability.

📌 Table of Contents:

🔧 Technologies Used
📁 Project Structure
✅ Test Scenarios



🔧 Technologies Used:

🖥 Language: Java
🧪 Testing Framework: TestNG
🔍 Automation Tool: Selenium WebDriver
📦 Build Tool: Maven
📄 Design Pattern: Page Object Model (POM)
🌐 Test Website: nopCommerce Demo


📁 Project Structure

├── src
│   ├── main
│   │   └── java
│   │       └── pages             # Page classes (HomePage, LoginPage, etc.)
│   └── test
│       └── java
│           └── tests             # Test classes
│           └── utilities         # Reusable methods like wait, screenshots
├── pom.xml                       # Maven dependencies
└── testng.xml                    # Test suite config


✅ Test Scenarios
The following test cases are automated:


🔐 User Account
Register a new user
Login with valid credentials
Logout
Recover password (if applicable)


🛍 Product Actions

Search for products
Add product to cart
Remove product from cart
Add product to wishlist
Compare products
View product details


💳 Checkout & Order

Checkout as guest
Place an order
View order history


🌐 Miscellaneous

Change currency (USD, Euro)
Navigate through main menu categories
Scroll up/down functionality
Verify featured products
Contact us form

