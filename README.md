HTML Structure
Header Section:

Contains the title of the application ("Job Board").
Includes a navigation bar with links for:
Home
Job Listings
Employer Dashboard
Candidate Dashboard
Navigation links switch between the sections dynamically using JavaScript.
Main Sections:

Home Section (#home):
Provides a welcome message and displays a featured job with a button to view details.
Job Listings Section (#job-listings):
Displays available jobs.
Includes a search bar to filter job listings dynamically.
Job Detail Section (#job-detail):
Shows detailed information about a selected job, such as title, location, salary, and description.
Includes a button to apply for the job.
Employer Dashboard Section (#employer-dashboard):
Allows employers to post jobs via a form (e.g., Job Title, Location, Salary).
Candidate Dashboard Section (#candidate-dashboard):
Allows candidates to update their profiles and view job applications.
CSS Styling
Global Styles:

Uses a background image (job.jpg) with a fixed and centered layout.
Text is styled with a white font color for visibility on the dark background.
Section Styling:

Each section has a slightly transparent background (rgba) for readability against the image.
Borders and rounded corners are used for visual appeal.
Navigation and Buttons:

Styled as interactive elements with hover effects to enhance usability.
Buttons and links have consistent colors (rgba(0, 123, 255, 0.8)).
JavaScript Functionality
Navigation between Sections:

The showPage() function hides all sections and displays the selected one based on its id.
Job Search:

Filters job listings based on the text entered in the search bar (input event).
Dynamically displays matching job cards.
Job Application Process:

Mock functionality implemented in the applyForJob() function, showing an alert when a job is applied.
Form Handling:

Both the "Post Job" and "Update Profile" forms prevent the default submission and show a success message.
