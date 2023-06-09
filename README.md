MPCC-Project

Welcome to the MPCC-Project repository! This project aims to showcase the installation and setup of a LAMP stack (Linux, Apache, MySQL, PHP) for hosting the MPCC-Project web application.

Installation Instructions
-------------------------

To get started with the MPCC-Project, follow these steps:

1. Clone the repository:
   git clone https://github.com/ravib7/MPCC-Project.git

2. Navigate to the project directory:
   cd MPCC-Project

3. Run the setup script:
   ./mpcc.sh

   The setup script will install Apache, MySQL, PHP, and other required dependencies. It will also configure the necessary files and settings.

4. Access the MPCC-Project web application:
   - Open a web browser and enter "http://localhost" or "http://<server-ip>" in the address bar.

   - You should see the MPCC-Project homepage indicating a successful installation.

5. Explore the MPCC-Project:
   - The MPCC-Project source code is located in the "var/www/MPCC-Project" directory.

   - Customize and modify the application according to your needs.

Configuration
-------------

- Apache Virtual Host Configuration: The Apache Virtual Host is configured in the file "MPCC-Project.conf" located in the "/etc/apache2/sites-available" directory.

- MySQL Configuration: MySQL database configuration can be found in the "setup.sh" script. It sets up a database named "mpcc" and a user named "mpccuser" with the necessary privileges.

- PHP Configuration: PHP settings can be adjusted in the "/etc/php/8.1/apache2/php.ini" file.

Troubleshooting
---------------

- If you encounter any issues during the installation or setup process, please refer to the error messages or consult the Apache and MySQL logs for more information. The log files are typically located in the "/var/log/apache2" and "/var/log/mysql" directories, respectively.

- For additional support or assistance, feel free to create an issue on the GitHub repository or reach out to miranahmed5882@gmail.com
