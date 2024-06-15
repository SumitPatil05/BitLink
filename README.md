# BitLink - URL Shortener Web App

## Overview
BitLink is a web application designed to shorten long URLs into manageable and user-friendly links. By utilizing a reliable and robust PHP backend with a MySQL database, BitLink ensures efficient URL shortening, tracking, and redirection.

## Features
- **URL Shortening**: Convert long URLs into short, easy-to-share links.
- **Link Management**: Track and manage shortened URLs with ease.
- **Customizable Links**: Option to create custom short links.
- **Analytics**: Monitor the usage of shortened URLs with basic analytics.
- **User-Friendly Interface**: Clean and intuitive interface for seamless interaction.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bitlink.git
   cd bitlink
   ```

2. **Setup MySQL Database**:
   - Create a new MySQL database.
   - Import the provided SQL file to set up the necessary tables:
     ```bash
     mysql -u your_username -p your_database < bitlink.sql
     ```

3. **Configure Database Connection**:
   - Open `config.php` and update the database configuration with your MySQL credentials:
     ```php
     <?php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'your_username');
     define('DB_PASSWORD', 'your_password');
     define('DB_NAME', 'your_database');
     ?>
     ```

4. **Install Dependencies**:
   Ensure you have PHP and a web server like Apache or Nginx installed. If using Apache, place the project files in the `htdocs` directory.

5. **Run the Application**:
   Start your web server and navigate to `http://localhost/bitlink` to access the app.

## Usage
1. **Shorten a URL**: Enter a long URL in the input field on the homepage and click "Shorten".
2. **Manage Links**: View and manage your shortened links in the management section.
3. **Custom Short Links**: If enabled, create custom short URLs.
4. **Analytics**: Check the analytics page to see the usage statistics of your shortened links.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [PHP](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
- [Apache](https://httpd.apache.org/)
- [Nginx](https://www.nginx.com/)

## Contact
For any inquiries or issues, please contact:
* Name: Sumit Patil
* Email: sumitpatilplk920@gmail.com
* GitHub: sumitpatil05


---

Thank you for using BitLink! Simplify your links and enhance your web presence!
