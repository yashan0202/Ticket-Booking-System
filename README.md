<h2>Automated Ticket Booking System - BookMyTrip</h2>

<h3>Project Overview</h3>

<p>This project is an automated ticket booking system built for the BookMyTrip website, aimed at simplifying the process of booking train tickets. Leveraging Selenium WebDriver, this automation script navigates through the booking process, allowing users to book train tickets seamlessly from a specified origin to destination on a selected date. Users can choose their preferred berth type (3AC, 2AC, 1AC, Sleeper), view train availability, and check the probability of ticket confirmation.</p>

<h3>Features</h3>

<h4>Automated Booking:</h4> Automates the train ticket booking process from start to finish on the BookMyTrip website.

<h4>Customizable Travel Details:</h4>
<h4>Origin and Destination Selection:</h4> Allows users to specify the start and end points for their journey.
<h4>Date Selection:</h4> Users can input a specific travel date for booking.
<h4>Preferred Berth Selection:</h4> Options include Sleeper, 3AC, 2AC, and 1AC, providing flexibility based on user preference.
<h4>Train Availability Check:</h4> Displays available trains for the selected route and date.
<h4>Ticket Confirmation Probability:</h4> Shows the likelihood of ticket confirmation based on seat availability.

Technologies Used
Programming Language: Java
Automation Framework: Selenium WebDriver
Integrated Development Environment (IDE): Eclipse
Project Structure
Config Files: Contains setup configurations for Selenium and the browser driver.
Page Objects: Organized by key pages of the booking process on BookMyTrip, simplifying code structure and maintenance.
Test Cases: Covers the full range of automated booking functionalities and ensures all scenarios (valid bookings, out-of-stock, etc.) are managed appropriately.
How It Works
Setup and Initialization: The script initiates by loading the BookMyTrip website and applying the required configurations.
Booking Workflow:
User inputs origin and destination cities.
Selects a travel date.
Chooses a preferred berth type.
Checking Availability: Once the details are selected, the script verifies the availability of trains on the chosen date.
Confirmation Probability: Based on real-time data, the script calculates and displays the probability of ticket confirmation.
Booking Confirmation: Completes the booking if seats are available, and displays a booking confirmation message.
Error Handling
Timeouts and Page Load Delays: Implemented to handle scenarios where the website takes longer to load.
Invalid Inputs and Availability Checks: Ensures proper error messages are displayed if tickets are unavailable or if an invalid route is selected.
Future Enhancements
Adding more detailed logging for user actions and any exceptions encountered.
Integrating with a payment gateway simulation for a more comprehensive booking experience.
Extending the automation to include other transportation modes (e.g., buses, flights).
Getting Started
To try out this project locally:

Clone the repository.
Set up Selenium WebDriver for the browser of choice (Chrome, Firefox, etc.).
Open the project in Eclipse IDE.
Configure the origin, destination, date, and berth in the test script.
Run the automation script.
Prerequisites
Java Development Kit (JDK) - Ensure Java is installed and configured.
Selenium WebDriver - Download and set up the browser driver for Chrome/Firefox.
Eclipse IDE - Import the project into Eclipse for seamless execution.
