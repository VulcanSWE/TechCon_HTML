Practical HTML
 Novice
 Weight: 1
 Project over - took place from Jul 14, 2025 12:00 AM to Jul 21, 2025 12:00 AM
 An auto review will be launched at the deadline
In a nutshell…
Auto QA review: 0.0/46 mandatory
Altogether:  0.0%
Mandatory: 0.0%
Optional: no optional tasks


This project challenges you to build a comprehensive website for the TechCon 2024 conference using HTML. You’ll create various webpages, each focusing on a specific aspect of the conference, while incorporating essential HTML elements and best practices.

Project Scope:
The website will consist of five core webpages:

Homepage (index.html): This is the landing page that introduces TechCon 2024 and provides navigation to other sections of the website.
About Page (about.html): This page delves into the history, mission, and notable speakers of the TechCon conference.
Schedule Page (schedule.html): This webpage presents a detailed schedule of conference events, sessions, and speakers in an accessible table format.
Register Page (register.html): This page offers a user-friendly registration form for attendees to sign up for the TechCon conference.
Contact Page (contact.html): This webpage provides comprehensive contact information for TechCon, including email address, social media links, an embedded map, and a “Contact Us” form.
Concepts Covered:
Throughout this project, you’ll gain practical experience with the following HTML concepts:

HTML Structure: You’ll solidify your understanding of fundamental HTML tags like <header>, <nav>, <main>, <section>, <article>, <footer>, and their proper usage for website structure and organization.
Headings and Text: You’ll learn to structure headings (h1-h6) for emphasis and utilize paragraph tags (<p>) and other text formatting elements effectively.
Links and Navigation: You’ll implement hyperlinks (<a> tags) to create navigation menus and link between different webpages within the TechCon website.
Tables: You’ll create a well-formatted table on the Schedule page to present conference schedules in an organized and easy-to-read manner.
Forms: You’ll design user-friendly registration and contact forms using the <form> tag and various input types (text, email, password, checkbox) to collect attendee information.
Images and Multimedia: You’ll incorporate images (using <img> tags with appropriate alt attributes) to enhance the visual appeal of the website. You’ll also explore embedding a promotional video (using the <video> tag) and an interactive Google Map (using <iframe>) on the Contact page.
By successfully completing this project, you’ll gain valuable hands-on experience building a real-world website with HTML. This will serve as a solid foundation for you to explore more advanced web development concepts like CSS and JavaScript in the future.

Quiz questions
Great! You've completed the quiz successfully! Keep going! (Show quiz)
Tasks
0. Building the Homepage for TechCon 2024 Conference Website
mandatory
Score: 0.0% (Checks completed: 0.0%)
Objective:
Create the homepage (index.html) for the TechCon 2024 conference website, demonstrating effective use of HTML structure, embedding media, and designing with accessibility standards.

Requirements:
Header:

Use a <header> tag to contain the top part of the page.
Include the conference name within an <h1> tag to emphasize its importance.
Implement a navigation menu using a <nav> tag with links (<a> tags) to other pages: About, Schedule, Register, and Contact. Ensure that each link is properly named and points to the respective HTML files (about.html, schedule.html, register.html, contact.html).
Main Section:

Utilize a <main> tag to define the dominant content of the webpage.
Within the main section, use a <section> tag to introduce the conference. This section should include:
A brief paragraph (<p>) describing the event.
An embedded promotional video using the <video> tag with controls enabled. Make sure the video is accessible and includes subtitles or a description if available.
Footer:

Use a <footer> tag for the bottom part of the webpage.
Include copyright information relevant to the event and the current year. Ensure this information is simple and clear. Make sure to explicitly add the text copyright.
Repo:

GitHub repository: TechCon_HTML
Directory: techcon_website
File: index.html
   
1. Creating the About Page for TechCon 2024 Conference Website
mandatory
Score: 0.0% (Checks completed: 0.0%)
Objective:
Develop the About page (about.html) for the TechCon 2024 conference, highlighting the history, mission, and notable past speakers of the conference through well-structured HTML content and embedded media.

Requirements:
Header:

Utilize a <header> tag to contain the top section of the page.
Place the page title “About TechCon 2024” within an <h1> tag for prominence.
Include the same navigation menu as the homepage using a <nav> tag, with links to Home, Schedule, Register, and Contact. Each link should be properly directed to the respective HTML files.
Main Content:

Use a <main> tag to define the core content of the webpage.
Divide the content into multiple <article> sections, each dedicated to a different aspect of the conference:
History: An article detailing the origins and evolution of TechCon, enhanced with historical images (<img> tags with appropriate alt attributes).
Mission: A section that explains the goals and driving principles of the conference. Include any relevant motivational images or icons.
Past Speakers: Showcase notable speakers from previous years with short biographies and their contributions to the tech industry. Use <img> tags for speaker photos, ensuring each has an alt attribute describing the person.
Footer:

The footer should be consistent across all pages, using a <footer> tag.
Include copyright information, mirroring the layout and content from the homepage.
Repo:

GitHub repository: TechCon_HTML
Directory: techcon_website
File: about.html
   
2. Designing the Schedule Page for TechCon 2024 Conference Website
mandatory
Score: 0.0% (Checks completed: 0.0%)
Objective:
Create the Schedule page (schedule.html) for TechCon 2024, providing a detailed and accessible timetable of events, sessions, and speakers, using a structured HTML table format.

Requirements:
Header:

Include a <header> tag containing the page title “Schedule for TechCon 2024” displayed within an <h1> tag.
Implement a consistent navigation menu as in previous pages using a <nav> tag, linking to Home, About, Register, and Contact.
Main Content:

Utilize a <main> tag to centralize the primary content of the schedule.
Construct a detailed schedule using a <table>:
Headers: Use <th> tags for columns such as “Time”, “Session”, and “Speaker”, applying scope attributes to clarify their relevance.
Data Rows: Populate with <td> tags containing the specifics of each session.
Caption: Include a <caption> that succinctly describes the table (e.g., “Detailed Schedule of Events for TechCon 2024”). This should be one line of code for checker purposes.
Footer:

Use a <footer> tag consistent with the rest of the website.
Include copyright information similar to other pages.
Repo:

GitHub repository: TechCon_HTML
Directory: techcon_website
File: schedule.html
  
3. Building the Register Page for TechCon 2024 Conference Website
mandatory
Score: 0.0% (Checks completed: 0.0%)
Objective:
Create the Register page (register.html) for TechCon 2024, designing a user-friendly and accessible registration form that collects essential attendee information.

Requirements:
Header:

Include a <header> tag with the page title “Register for TechCon 2024” encapsulated in an <h1> tag.
Implement the standard navigation menu using a <nav> tag, linking to Home, About, Schedule, and Contact.
Main Content:

Use a <main> tag for the central content.
Design a registration form using a <form> tag:
Field for Name: Include an <input> type=“text” for the attendee’s full name with a corresponding <label>.
Field for Email: Incorporate an <input> type=“email” for email addresses to ensure proper formatting, paired with a <label>.
Password Fields: Add fields for password and password confirmation using <input> type=“password”, each with labels explaining their purpose.
Checkbox for Terms and Conditions: Provide a checkbox <input> type=“checkbox” for users to agree to the terms and conditions, clearly described alongside.
Submit Button: Place a <button> type=“submit” to finalize registration, labeled appropriately (e.g., “Register Now”).
Footer:

Consistently use a <footer> tag across all pages.
Repeat the copyright information found on other pages.
Repo:

GitHub repository: TechCon_HTML
Directory: techcon_website
File: register.html
   
4. Constructing the Contact Page for TechCon 2024 Conference Website
mandatory
Score: 0.0% (Checks completed: 0.0%)
Objective:
Develop the Contact page (contact.html) for TechCon 2024, featuring comprehensive contact details, interactive elements like an embedded map, and a “Contact Us” form, ensuring ease of communication for attendees.

Updated Requirements:
Header:

Incorporate a <header> tag that includes the page title “Contact Us” within an <h1> tag.
Feature the consistent navigation menu using a <nav> tag with links to Home, About, Schedule, and Register.
Main Content:

Use a <main> tag to house the primary content of the page.
Detail contact information, including:
Email Address: Display an official conference email using <a> tags configured with href="mailto:email@example.com" to facilitate direct emailing. (Use the example email given as is - don’t modify it)
Social Media Links: List clickable icons or text linked to the conference’s social media profiles using <a> tags with href attributes pointing to the respective URLs and target="_blank" to open in new tabs.
Embedded Google Maps: Location of the conference venue using an <iframe>. This map should be responsive and provide a clear view of the venue’s location.
Contact Us Form:
Include a form <form> that asks for the user’s name, email, and a message.
Fields to include:
Name: <input type="text"> with a corresponding <label>.
Email: <input type="email"> with a corresponding <label>.
Message: <textarea> with a corresponding <label>.
Submit Button: <button type="submit"> labeled “Send Message”.
Footer:

Employ a <footer> tag that is consistent across all pages.
Include copyright information, echoing the setup found on other pages.
Repo:

GitHub repository: TechCon_HTML
Directory: techcon_website
File: contact.html