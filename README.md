# Cinema-E-Booking-System
The Cinema E-Booking System is a comprehensive web-based application designed to streamline and enhance the movie booking experience for administrators and users. With a focus on usability, security, and real-time updates, the system allows users to browse a vast collection of movies, book tickets online, and manage their profiles seamlessly.

This project is developed as part of the Software Engineering course (CSCI 6050) undertaken as a crucial component of my master's program. The course emphasizes the practical application of software engineering principles in designing, developing, and deploying a robust and user-friendly cinema e-booking system. The project integrates aspects of the waterfall and agile methodologies, including iterative development cycles and user feedback, to ensure a high-quality and industry-relevant solution.

# Key Features:

**Movie Information Management:** 
System administrators can easily add, update, or delete movie details, including title, category, cast, director, producer, synopsis, reviews, trailer (picture and video), MPAA-US film rating code, and show dates/times.

**Ticket and Promotion Management:** 
Administrators have control over ticket prices, online booking fees, and promotions. The system enables the addition of promotions with automatic email notifications to subscribed users.

**User Registration and Profile Management:**
Users can register securely, providing personal information and optional payment details. Registration includes a verification process via email, after which users receive a unique account ID. Registered users can manage their profiles, change passwords, and subscribe/unsubscribe to promotions.

**Booking Facility:** 
The system offers a user-friendly booking interface for selecting movies, show dates/times, ticket quantities, and age categories. Users can also choose seats through a graphical hall view. Only registered and signed-in users can book tickets.

**Secure Checkout:** 
A secure payment facility allows users to pay for tickets online, utilizing promotion codes for discounts. Upon successful payment, users receive a booking confirmation page and email.

**Order History and Ticket Refund:** 
Users can view their order history. The system supports ticket returns with refunds if canceled up to 60 minutes before the show time (low priority).

**Administrative Tools:** 
Administrators can pull predefined reports and manage system parameters. Multi-user access is supported with appropriate authentication and authorization mechanisms.

**Development Process:**
The system uses an incremental hybrid model, combining waterfall and agile methodologies. Prototypes are utilized for UI design, and development is carried out in sprints with continuous testing to ensure a high-quality product.

# Architecture Style:
Multi-Layered Architecture


# Technology Stack: 
Front-End: Angular
Back-end: Java SpringBoot
Database: MySQL

### Setting up and Running the Cinema E-Booking System Project

1. **Install Java JDK:**
   - Download and install the latest version of Java JDK from the official Oracle website: [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)

2. **Set up Spring Boot IDE:**
   - Choose a Spring Boot compatible IDE such as Spring Tool Suite (STS) or Eclipse.
   - Download and install the chosen IDE from their official websites.
   - For Spring Tool Suite, download it from [Spring Tools](https://spring.io/tools).

3. **Download Visual Studio Code:**
   - Download and install Visual Studio Code from the official website: [Visual Studio Code](https://code.visualstudio.com/)

4. **Install Angular CLI and Node.js:**
   - Open a terminal or command prompt.
   - Run the following commands to install Node.js and Angular CLI:
     ```bash
     npm install -g @angular/cli
     ```
     This installs the Angular CLI globally on your system.

5. **Install MySQL:**
   - Download and install MySQL from the official website: [MySQL](https://dev.mysql.com/downloads/)
   - Follow the installation instructions provided during the installation process.

6. **Clone the Repository:**
   - Clone the Cinema E-Booking System project repository from your GitHub account or the provided repository link.

7. **Set up Backend (Spring Boot):**
   - Open the backend project in your chosen IDE.
   - Configure the database connection in the application properties file.
   - Run the Spring Boot application.

8. **Set up Frontend (Angular):**
   - Open the frontend project in Visual Studio Code or your preferred code editor.
   - Install the required dependencies by running:
     ```bash
     npm install
     ```
   - Update the API base URL in the Angular environment file.
   - Run the Angular application using:
     ```bash
     ng serve
     ```

9. **Access the Application:**
   - Open a web browser and navigate to `http://localhost:4200` to access the Cinema E-Booking System. (Port Number can be changed).

