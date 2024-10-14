# Currency-Converter
We created a Currency Converter Website using HTML, CSS, and JavaScript. We built and used a Currency Conversion API to gather the latest real-time conversion rates.

1. Set Up the Project Structure
Create a project folder and name it "CurrencyConverter" (or a preferred name).
Inside the folder, create three files:
index.html for the webpage structure.
style.css for styling the webpage.
script.js for adding JavaScript functionality.

2. Design the User Interface (UI)
Create the index.html file:
Structure the webpage using HTML. Include elements such as:
A title for the webpage (e.g., "Currency Converter").
An input field for the user to enter the amount to be converted.
A dropdown menu to select the currency type.
A button to trigger the conversion.
A table to display the converted currency values.

3. Style the Webpage
Create the style.css file to style the webpage and make it visually appealing.
Include styling for the heading, input fields, button, and table.

4. Add JavaScript Functionality
Create the script.js file to handle user interactions, fetch data from the API, and perform calculations.
Define a function named populate to fetch currency exchange rates using an external API.
In the populate() function:
Use the Fetch API to request data from the currency conversion API.
Loop through the data to update the table with the latest conversion rates.
Use event listeners to trigger the function when the user clicks the convert button.

5. Obtain the API Key
Sign up for an account on currencyapi.com to get your own API key.
Replace 'YOUR_API_KEY' in the JavaScript code with the actual API key.

6. Testing and Debugging
Test the website by entering different amounts and selecting various currencies.
Check for errors in the console and ensure the currency rates are updating as expected.

7. Deployment
Host the website on a platform like GitHub Pages, Netlify, or Vercel for free.
Share the URL with users for easy access.
