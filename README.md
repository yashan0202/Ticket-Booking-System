<h1>Automated Ticket Booking System - BookMyTrip</h1>
<br>
<h2>Project Overview</h2>
<br>
<p>This project is an automated ticket booking system built for the BookMyTrip website, aimed at simplifying the process of booking train tickets. Leveraging Selenium WebDriver, this automation script navigates through the booking process, allowing users to book train tickets seamlessly from a specified origin to destination on a selected date. Users can choose their preferred berth type (3AC, 2AC, 1AC, Sleeper), view train availability, and check the probability of ticket confirmation.</p>
<br>
<h2>Features</h2>
<br>
<h3>1. Automated Booking:</h3> Automates the train ticket booking process from start to finish on the BookMyTrip website.

<h3>2. Customizable Travel Details:</h3>
<ul>Origin and Destination Selection: Allows users to specify the start and end points for their journey.</ul>
<ul>Date Selection: Users can input a specific travel date for booking.</ul>
<ul>Preferred Berth Selection: Options include Sleeper, 3AC, 2AC, and 1AC, providing flexibility based on user preference.</ul>

<h3>3. Train Availability Check:</h3> Displays available trains for the selected route and date.

<h3>4. Ticket Confirmation Probability:</h3> Shows the likelihood of ticket confirmation based on seat availability.
<br>
<h2>Technologies Used</h2>
<br>
<ul>Programming Language: Java</ul>
<ul>Automation Framework: Selenium WebDriver</ul>
<ul>Integrated Development Environment (IDE): Eclipse</ul>
<br>
<h2>Project Structure</h2>
<br>
<ul>Config Files: Contains setup configurations for Selenium and the browser driver.</ul>
<ul>Page Objects: Organized by key pages of the booking process on BookMyTrip, simplifying code structure and maintenance.</ul>
<ul>Test Cases: Covers the full range of automated booking functionalities and ensures all scenarios (valid bookings, out-of-stock, etc.) are managed appropriately.</ul>
<br>
<h2>How It Works</h2>
<br>
<h3>1. Setup and Initialization:</h3> The script initiates by loading the BookMyTrip website and applying the required configurations.

<h3>2. Booking Workflow:</h3>
<ul>User inputs origin and destination cities.</ul>
<ul>Selects a travel date.</ul>
<ul>Chooses a preferred berth type.</ul>

<h3>3. Checking Availability:</h3> Once the details are selected, the script verifies the availability of trains on the chosen date.

<h3>Confirmation Probability:</h3> Based on real-time data, the script calculates and displays the probability of ticket confirmation.

<h3>Booking Confirmation:</h3> Completes the booking if seats are available, and displays a booking confirmation message.
<br>
<h2>Error Handling</h2>
<br>
<ul>Timeouts and Page Load Delays: Implemented to handle scenarios where the website takes longer to load.</ul>

<ul>Invalid Inputs and Availability Checks: Ensures proper error messages are displayed if tickets are unavailable or if an invalid route is selected.</ul>
<br>
<h2>Future Enhancements</h2>
<br>
<ul>Adding more detailed logging for user actions and any exceptions encountered.</ul>

<ul>Integrating with a payment gateway simulation for a more comprehensive booking experience.</ul>

<ul>Extending the automation to include other transportation modes (e.g., buses, flights).</ul>
<br>
<h2>Getting Started</h2>
<br>
To try out this project locally:

<ol>Clone the repository.</ol>
<ol>Set up Selenium WebDriver for the browser of choice (Chrome, Firefox, etc.).</ol>
<ol>Open the project in Eclipse IDE.</ol>
<ol>Configure the origin, destination, date, and berth in the test script.</ol>
<ol>Run the automation script.</ol>

<br>
<br>

<h2><i>Developed by: </i>Yash Anand</h2>
