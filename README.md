### ⛓️ Setting Up a Local Development Environment with Apache Web Server

This guide outlines the steps to fork a repository, clone it into the root directory of an Apache web server, start the web server, and navigate to `localhost` to run the `index.html` file. The links across all web pages are already in place.

#### Prerequisites:
- Git installed on your system
- Apache web server installed and configured

#### Steps:

1. **Fork the Repository:**
   - Fork the repository on GitHub to your own account.

2. **Clone the Repository:**
   - Open a terminal window.
   - Navigate to the root directory of your Apache web server.
   - Clone the forked repository into this directory:
     ```bash
     git clone <forked_repository_URL>
     ```

3. **Start the Apache Web Server:**
   - Start the Apache web server using the appropriate command for your operating system.
     - For macOS:
       ```bash
       sudo apachectl start
       ```
       ```
       brew services start httpd
       ```

     - For Ubuntu:
       ```bash
       sudo service apache2 start
       ```

     - For CentOS:
       ```bash
       sudo systemctl start httpd
       ```

4. **Navigate to `localhost`:**
   - Open a web browser.
   - Enter `localhost` in the address bar and press Enter.
   - This should navigate you to the default index page of the Apache server.

5. **Run the `index.html` File:**
   - Navigate to the repository directory within the Apache web server root directory.
   - Open the `index.html` file in your web browser.

6. **Verify Links:**
   - Test the links across all web pages to ensure they are working correctly.

#### Example Commands:

- Cloning the repository:
  ```bash
  git clone https://github.com/your_username/repository_name.git
  ```

#### Note:
- Ensure that your Apache web server is properly configured to serve files from the directory where the repository is cloned.
- Make sure the permissions are set correctly to allow the Apache web server to access the files.

### Additional Information:
- You can customize the `index.html` file and other web pages as needed.
- Refer to the Apache documentation for more information on configuring and managing the web server.
