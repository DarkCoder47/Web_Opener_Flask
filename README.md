### Web Opener Flask
Web Opener is a simple web application built with Flask that allows users to choose a website (such as Google, YouTube, Wikipedia, Gmail, Facebook, or Instagram) from a dropdown menu and open it in their browser using Selenium WebDriver.

### Features
- **Website Selection**: Choose from a list of predefined websites.
- **Selenium Integration**: Opens the selected website directly in the browser via Selenium WebDriver.
- **Backend**: Flask is used for the backend.
- **Frontend**: Basic HTML, CSS, and JavaScript for a clean, responsive interface.

### Prerequisites
Before running the application, make sure you have the following installed:

- Python 3.x
- Flask
- Selenium
- WebDriver Manager (for browser WebDriver management)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DarkCoder47/web-opener.git
   cd web-opener
   ```

2. Set up a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Windows: use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```bash
   python app.py
   ```

   The app will be available at [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

### Usage
1. Open the web application in your browser at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).
2. Select a website from the dropdown menu (Google, YouTube, Wikipedia, Gmail, Facebook, Instagram).
3. Click the "Open Site" button.
4. The selected website will open in your browser.

### Project Structure
```
/your_project_directory
    /app.py            # Main Flask app
    /templates
        /index.html    # HTML form for selecting the website
    /static
        /style.css     # Custom styles
        /script.js     # Optional JavaScript for interactivity
    /requirements.txt  # List of dependencies
    /README.md         # Project documentation
```
