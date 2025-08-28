🧠 Script Summary: CAR Map Automation
This script automates the process of accessing and interacting with the CAR map portal using Selenium and Chrome. It’s designed to locate and activate a specific map layer related to rural properties.

🔧 Key Functionalities
User Input Handling:

Accepts a CAR code via command-line argument or a pop-up input box (using tkinter).

Validates the code to ensure it's not empty and has at least 10 characters.

Browser Automation:

Launches Chrome with anti-detection settings using webdriver_manager and selenium.

Navigates to the CAR map portal.

Waits for the page to load and interacts with UI elements:

Opens the layer selection dropdown.

Expands the “Imóveis Rurais” group.

Selects the layer named car_area_imovel.

🧱 Technologies Used
Library	Purpose
selenium	Web automation
tkinter	GUI input for CAR code
webdriver_manager	Auto-install ChromeDriver
ctypes	(Unused in snippet, possibly for alerts)
sys	Command-line argument handling
time	Delays for page loading
📌 Notes
The script is part of your Mapa-Onr_API_CAR project.

It’s packaged with PyInstaller (script.spec) for easy distribution.

The GUI input makes it user-friendly for non-technical users.
