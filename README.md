# Complaint Registration Portal

## Overview
The Complaint Registration Portal is an Angular-based web application that allows users to register complaints and enables an admin to manage and resolve these complaints. The application supports user authentication, complaint registration, and admin management functionalities.

## Features
- **User Authentication**: Users can register, log in, and log out.
- **Complaint Registration**: Users can register complaints, which include a title and description.
- **Admin Dashboard**: Admin can view, update the status of, and delete complaints.
- **Local Storage**: Data persistence using local storage to maintain user sessions and complaint data.

## Technologies Used
- Angular
- TypeScript
- HTML
- CSS
- Local Storage (to store complaints)

### Login User
1. Log in as a normal user (default user credentials: username `user`, password `user`).

### Submitting a Complaint
1. After logging in, navigate to the dashboard.
2. Fill in the complaint title and description.
3. Click on the `Submit Complaint` button.
4. View submitted complaints in the table.

### Admin Management
1. Log in as an admin (default admin credentials: username `admin`, password `admin`).
2. Navigate to the admin dashboard.
3. View all complaints in a table format.
4. Update the status of complaints or delete complaints as needed.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MayurN01/dockerized-complaint-registration-portal.git
    cd dockerized-complaint-registration-portal
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. **Docker Setup**:
    - Build the Docker image:
      ```bash
      sudo docker build -t my-login-app .
      ```
    - Run the Docker container:
      ```bash
      sudo docker run -d -p 8080:80 my-login-app
      ```

4. Open your browser and navigate to `http://localhost:8080`.

## Output

![Image 5](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/admin%20login.png)
![Image 6](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/admin%20portal.png)
![Image 1](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/docker%20bulid.png)
![Image 2](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/docker%20run.png)
![Image 3](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/login%20page.png)
![Image 4](https://github.com/MayurN01/dockerized-complaint-registration-portal/blob/main/images/user%20portal.png)
