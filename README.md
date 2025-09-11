# CargoCalc - TV Fitment Assistant

CargoCalc is a web application designed to help retail employees (e.g., at Best Buy) quickly determine if a customer's television purchase will fit in their vehicle. The app provides three primary tools to address common customer questions, streamlining the sales and loading process.

## Core Features

1.  **Fit Check**: The primary function allows you to select a specific TV and a specific vehicle to see if they are compatible.
2.  **TV Finder**: If a customer wants to know the largest TV they can buy, this tool finds all TV sizes in the database that will fit in their selected vehicle.
3.  **Vehicle Finder**: If a customer has already purchased a TV, this tool provides a list of all vehicles in the database that can accommodate it.
4.  **AI-Powered Suggestions**: If a TV does not fit, the app can generate AI-powered suggestions for alternative transportation methods or recommend smaller TV sizes that are likely to fit.
5.  **Multiple Data Entry Methods**: For both TVs and vehicles, you can use a comprehensive database, enter dimensions manually, or use an experimental AI lookup for vehicle dimensions.
6.  **Feedback System**: An integrated feedback form allows users to report issues or suggest improvements, helping to refine the tool over time.

---

## How to Use the App

The application is organized into three main tabs, each serving a different purpose.

### 1. Fit Check Tab

Use this tab to check if a specific TV fits in a specific vehicle.

1.  **Enter TV Information**:
    *   **Database**: Select the TV's brand and screen size from the dropdown menus. The box dimensions will be filled automatically.
    *   **Manual**: If the TV isn't in the database, switch to the "Manual Entry" tab and input the TV box's width, height, and depth in inches.
2.  **Enter Vehicle Information**:
    *   **Database**: Select the vehicle's make, model, and year from the dropdowns.
    *   **Manual**: If the vehicle isn't listed, switch to the "Manual" tab and enter the cargo area's width, height, and depth.
    *   **AI Lookup**: Use the "AI Lookup" tab as an experimental way to find dimensions by entering the make, model, and year.
3.  **Check Fitment**: Click the "Check Fitment" button.
4.  **View Results**: The app will display a clear result:
    *   **Confirmed Fit**: The TV fits. The result will specify the loading scenario (e.g., Seats Down, Truck Bed).
    *   **Tight Fit**: The TV fits, but with less than 2 inches of clearance. Load with care.
    *   **Will Not Fit**: The TV does not fit in any standard configuration. You can then use the "Get AI Suggestions" button for alternative options.

### 2. TV Finder Tab

Use this tab to find all TV sizes that are compatible with a specific vehicle.

1.  **Select a Vehicle**: Use the vehicle information form to select a vehicle from the database or enter its dimensions manually.
2.  **Find TVs**: Click the "Find TVs That Fit" button.
3.  **View Results**: The app will display a list of all TV screen sizes from the database that are confirmed to fit in that vehicle.

### 3. Vehicle Finder Tab

Use this tab to find all vehicles that are compatible with a specific TV.

1.  **Select a TV**: Use the television information form to select a TV brand and size or enter its box dimensions manually.
2.  **Find Vehicles**: Click the "Find Compatible Vehicles" button.
3.  **View Results**: The app will display a list of all vehicles from the database that can fit the selected TV, along with the required loading scenario for each.

---

### Providing Feedback

After running a "Fit Check," a "Provide Feedback" button will appear. Clicking this opens a dialog where you can rate the app's usefulness and leave comments. This feedback helps improve the accuracy and functionality of the tool.
