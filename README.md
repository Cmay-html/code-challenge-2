EVENT GUEST LIST MANAGER 

DESCRIPTION 
The Event Guest List Manager is a dynamic web application designed to help users efficiently manage guest lists for events. Built with plain JavaScript, HTML, and CSS, the app offers an intuitive interface that allows users to add, remove, and manage guests in real time — all without page reloads.
This project showcases core JavaScript skills such as DOM manipulation, event handling, and form management, with a focus on creating a smooth user experience.


FEATURES 
	•	Add Guests:Users can enter a guest’s name into the input field and submit it to add the guest to the list instantly.
	•	Guest List Display:The app dynamically updates the guest list on the page, showing all added guests.
	•	Remove Guests:Each guest entry includes a “Remove” button, enabling users to delete guests from the list individually.
	•	Guest Limit Enforcement:The list is capped at 10 guests. Attempting to add more triggers a friendly alert notifying the user of the limit.
	•	Toggle RSVP Status:Guests can be marked as “Attending” or “Not Attending” by toggling their RSVP status directly in the list.


HOW TO USE THE APPLICATION 

Requirements
* A computer, tablet, or phone
* Access to the internet
* A modern web browser

View Live Site
Visit the deployed application at: 
The live site allows you to:
Add Guests:Type the name of a guest into the input field and click the submit button (or press Enter). The guest’s name will appear immediately in the list below.
Remove Guests:Click the “Remove” button next to any guest to delete them from the list.
Manage RSVP:Click the RSVP toggle button beside each guest to mark whether they are attending or not. The status updates visually for easy tracking.
Guest Limit:The app restricts the guest list to a maximum of 10 entries. If you try to add more, an alert will inform you that the limit has been reached.

Local Development
If you want to run the project locally, you'll need:
* Node.js installed on your computer
* Basic understanding of React JS
* Code editor (VS Code recommended)
* Terminal/Command Line
Installation Process
Clone this repository using:git clone git@github.com:Cmay-html/code-challenge-2.git 
or by downloading a ZIP file of the code.

Navigate to the project directory:cd code-challenge-2
Install the required dependencies:npm install
Run the development server:npm run dev
Open your browser and visit http:


User Experience
The application is designed to provide instant feedback and smooth interaction without page refreshes. The form submission is handled using event.preventDefault() to maintain the current view and update the guest list dynamically.

Technologies Used
	•	JavaScript (ES6) for DOM manipulation and event handling
	•	HTML5 for semantic structure
	•	CSS3 for clean and responsive styling


Summary
This guest list manager offers a simple yet effective way to track event attendees, making guest management easy and interactive. Whether you’re organizing a small gathering or a larger event, this app provides essential features to keep your guest list organized and up to date.

Support and Contact Details
If you have any questions, suggestions, or need assistance, please contact:
* Email: cynthialairumbe@gmail.com

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.