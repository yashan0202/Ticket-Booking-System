<h1>Automated Ticket Booking System - BookMyTrip</h1>
<h2>Project Overview</h2>
<p>
        This project is an automated ticket booking system built for the BookMyTrip website, aimed at simplifying the process of booking train tickets. Leveraging <code>Selenium WebDriver</code>, this automation script navigates through the booking process, allowing users to book train tickets seamlessly from a specified origin to destination on a selected date. Users can choose their preferred berth type (3AC, 2AC, 1AC, Sleeper), view train availability, and check the probability of ticket confirmation.
    </p>

  <h2>Features</h2>
    <ul>
        <li><strong>Automated Booking</strong>: Automates the train ticket booking process from start to finish on the BookMyTrip website.</li>
        <li><strong>Customizable Travel Details</strong>:
            <ul>
                <li><strong>Origin and Destination Selection</strong>: Allows users to specify the start and end points for their journey.</li>
                <li><strong>Date Selection</strong>: Users can input a specific travel date for booking.</li>
                <li><strong>Preferred Berth Selection</strong>: Options include Sleeper, 3AC, 2AC, and 1AC, providing flexibility based on user preference.</li>
            </ul>
        </li>
        <li><strong>Train Availability Check</strong>: Displays available trains for the selected route and date.</li>
        <li><strong>Ticket Confirmation Probability</strong>: Shows the likelihood of ticket confirmation based on seat availability.</li>
    </ul>

  <h2>Technologies Used</h2>
    <ul>
        <li><strong>Programming Language</strong>: Java</li>
        <li><strong>Automation Framework</strong>: Selenium WebDriver</li>
        <li><strong>Integrated Development Environment (IDE)</strong>: Eclipse</li>
    </ul>

  <h2>Project Structure</h2>
    <ul>
        <li><strong>Config Files</strong>: Contains setup configurations for Selenium and the browser driver.</li>
        <li><strong>Page Objects</strong>: Organized by key pages of the booking process on BookMyTrip, simplifying code structure and maintenance.</li>
        <li><strong>Test Cases</strong>: Covers the full range of automated booking functionalities and ensures all scenarios (valid bookings, out-of-stock, etc.) are managed appropriately.</li>
    </ul>

  <h2>How It Works</h2>
    <ol>
        <li><strong>Setup and Initialization</strong>: The script initiates by loading the BookMyTrip website and applying the required configurations.</li>
        <li><strong>Booking Workflow</strong>:
            <ul>
                <li>User inputs origin and destination cities.</li>
                <li>Selects a travel date.</li>
                <li>Chooses a preferred berth type.</li>
            </ul>
        </li>
        <li><strong>Checking Availability</strong>: Once the details are selected, the script verifies the availability of trains on the chosen date.</li>
        <li><strong>Confirmation Probability</strong>: Based on real-time data, the script calculates and displays the probability of ticket confirmation.</li>
        <li><strong>Booking Confirmation</strong>: Completes the booking if seats are available, and displays a booking confirmation message.</li>
    </ol>

  <h2>Error Handling</h2>
    <ul>
        <li><strong>Timeouts and Page Load Delays</strong>: Implemented to handle scenarios where the website takes longer to load.</li>
        <li><strong>Invalid Inputs and Availability Checks</strong>: Ensures proper error messages are displayed if tickets are unavailable or if an invalid route is selected.</li>
    </ul>

  <h2>Future Enhancements</h2>
    <ul>
        <li>Adding more detailed logging for user actions and any exceptions encountered.</li>
        <li>Integrating with a payment gateway simulation for a more comprehensive booking experience.</li>
        <li>Extending the automation to include other transportation modes (e.g., buses, flights).</li>
    </ul>

  <h2>Getting Started</h2>
    <p>To try out this project locally:</p>
    <ol>
        <li>Clone the repository.</li>
        <li>Set up Selenium WebDriver for the browser of choice (Chrome, Firefox, etc.).</li>
        <li>Open the project in Eclipse IDE.</li>
        <li>Configure the origin, destination, date, and berth in the test script.</li>
        <li>Run the automation script.</li>
    </ol>

  <h2>Prerequisites</h2>
    <ul>
        <li><strong>Java Development Kit (JDK)</strong>: Ensure Java is installed and configured.</li>
        <li><strong>Selenium WebDriver</strong>: Download and set up the browser driver for Chrome/Firefox.</li>
        <li><strong>Eclipse IDE</strong>: Import the project into Eclipse for seamless execution.</li>
    </ul>

</body>
</html>

<h2><i>Developed by: </i>Yash Anand</h2>
