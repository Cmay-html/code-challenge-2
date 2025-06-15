Event Guest List Manager
Overview
The Event Guest List Manager is a dynamic web application designed to help users efficiently manage guest lists for events. Built with plain JavaScript, HTML, and CSS, the app offers an intuitive interface that allows users to add, remove, and manage guests in real time — all without page reloads.
This project showcases core JavaScript skills such as DOM manipulation, event handling, and form management, with a focus on creating a smooth user experience.
Features
	•	Add Guests: Users can enter a guest’s name into the input field and submit it to add the guest to the list instantly.
	•	Guest List Display: The app dynamically updates the guest list on the page, showing all added guests.
	•	Remove Guests: Each guest entry includes a “Remove” button, enabling users to delete guests from the list individually.
	•	Guest Limit Enforcement: The list is capped at 10 guests. Attempting to add more triggers a friendly alert notifying the user of the limit.
	•	Toggle RSVP Status: Guests can be marked as “Attending” or “Not Attending” by toggling their RSVP status directly in the list.
How to Use the Application
	1.	Adding Guests: Type the name of a guest into the input field and click the submit button (or press Enter). The guest’s name will appear immediately in the list below.
	2.	Removing Guests: Click the “Remove” button next to any guest to delete them from the list.
	3.	Managing RSVP: Click the RSVP toggle button beside each guest to mark whether they are attending or not. The status updates visually for easy tracking.
	4.	Guest Limit: The app restricts the guest list to a maximum of 10 entries. If you try to add more, an alert will inform you that the limit has been reached.
User Experience
The application is designed to provide instant feedback and smooth interaction without page refreshes. The form submission is handled using event.preventDefault() to maintain the current view and update the guest list dynamically.
Technologies Used
	•	JavaScript (ES6) for DOM manipulation and event handling
	•	HTML5 for semantic structure
	•	CSS3 for clean and responsive styling
Summary
This guest list manager offers a simple yet effective way to track event attendees, making guest management easy and interactive. Whether you’re organizing a small gathering or a larger event, this app provides essential features to keep your guest list organized and up to date.