# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Tushar Mishra

**INTERN ID**: CT06DF1763

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**DURATION**: 6 WEEKS -- JUNE 5th,2025 to JULY 20th, 2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

# DESCRIPTION OF TASK PERFORMED :
During my internship at CODTECH, I created a Chrome Extension called Website Tracker, designed to monitor user browsing activity and provide detailed insights into how time is spent across various websites. The objective was to build a tool that runs silently in the background, automatically categorizes visited websites, and generates a productivity analysis for the user.

The core functionality of the extension involves tracking the amount of time spent on different websites throughout the day. This was accomplished using Chrome’s extension APIs, particularly the tabs, windows, and idle APIs, which enabled the extension to detect which tab is currently active, when focus is lost, and whether the user is idle. A combination of background and content scripts were used to accurately log start and end times of visits on specific domains.

Each website visited is automatically classified as either productive or unproductive. This classification logic is embedded within the background script and relies on a predefined list of domain categories. Productive sites include platforms like coding websites, documentation, educational platforms, and productivity tools, whereas unproductive ones include social media, video streaming platforms, and other entertainment-based sites. This automated labeling helps in generating focused reports without manual user input.

To handle data persistently and securely, I developed a lightweight backend system using a server-side framework and integrated it with the extension. The backend is responsible for receiving time logs and storing them in a structured format. This allows for centralized data management and easy aggregation of user activity over different time periods. Security protocols were included to protect user data during transmission and storage.

A custom dashboard was also created as part of the extension. This dashboard was designed using HTML, CSS, and JavaScript and is accessible directly through the extension popup or as a separate view. It presents visual insights such as total time spent on productive and unproductive websites, the percentage split between both categories, daily and weekly summaries, bar graphs showing time distribution, and trend lines indicating changes in behavior over time. The data displayed in the dashboard is pulled either from the browser’s local storage for smaller datasets or from the backend for extended history. This separation ensures that the extension performs efficiently while still being capable of handling large volumes of data over time.

In addition to passive tracking, the extension includes features like reminders and alerts when excessive time is spent on unproductive websites. These optional notifications help nudge the user back toward their intended goals by bringing attention to unproductive browsing patterns in real time.

The extension architecture is modular, consisting of a manifest file to define extension metadata and permissions, a background script to manage core logic and event tracking, optional content scripts for site-specific interactions, a popup interface for quick access, an options page for managing user preferences, and a backend API for secure data persistence and processing.

Website Tracker functions as a practical time management assistant. It combines browser-level activity tracking, automated site categorization, backend integration, and visual analytics to give users a clear picture of their online behavior and help them maintain productivity throughout the day.

# OUTPUT OF THE TASK :
<img width="325" height="180" alt="Image" src="https://github.com/user-attachments/assets/caf4e330-2c83-47c9-8df5-2c5e65158270" />

<img width="1366" height="720" alt="Image" src="https://github.com/user-attachments/assets/2aacec06-f519-47d8-9dca-401ef62fe2cf" />

https://github.com/user-attachments/assets/e17cbed6-afe7-41cd-94b7-6d3a31d8adc1
