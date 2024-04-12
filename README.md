# web-archive-project-using-spring-boot
This is a future project, user can archive a webpage by requesting the domain name.

# Project Details
Project Name: Web Archive <br> <br> 
Project Brief: This is a tool to take web page archive by requesting the domain name. <br>
Project Similartiy: This will be a similar project like Google Web Cache or Archive.org. <br> <br/>
Project Features: 
- User can create web page archive of a domain by inputting the domain name.
- User can schdule the process for a webpage.
- User can list multiple web page for taking the archive on a schedule basis.
- User can manage the list and stop the schdule process for particular web page.
- User can see the web archive on a calendar selection view to see the last updated page on a particular date.
- User can differ 02 web archives on side by side. <br>
- More features comming or create a issue to add a feature request

# Project's System Design
- User will input the webpage link.
- Request the webpage using Rest-Template of Spring boot and store the HTML in database.
- Spring boot has a support for Scheduling Jobs. We will run a scheduler after 05 minutes and check the Schduler table of Database and run the specific jobs.

# Technogloy 
Backend: Spring Boot (Java) <br>
Frontend: Thymeleaf <br>
Database: H2 <br>
