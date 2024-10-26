<a id="readme-top"></a>

[![Contributors][https://img.shields.io/badge/contributors-3-blue]](https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/graphs/contributors)
[![Forks][https://img.shields.io/badge/forks-5-brightgreen]](https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/network/members)
[![Stargazers][https://img.shields.io/badge/stars-10-yellow]](https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/stargazers)
[![Issues][https://img.shields.io/badge/issues-3-orange]](https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/issues)
[![MIT License][https://img.shields.io/badge/license-MIT-lightgrey]](https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/blob/main/LICENSE.txt)
[![LinkedIn][https://img.shields.io/badge/LinkedIn-Profile-blue]](https://www.linkedin.com/in/amoghasbhardwaj/)


<br />
<div align="center">
  <h3 align="center">COVID Bed Slot Booking System</h3>
  <p align="center">
    A web-based application for managing COVID bed bookings efficiently.
    <br />
    <a href="https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System">View Demo</a>
    ·
    <a href="https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

The COVID Bed Slot Booking System is an innovative web application designed to streamline the bed booking process for hospitals during the COVID-19 pandemic. By automating the booking process, this system reduces the manual workload and enhances efficiency.

### Key Features
- **Admin Dashboard**: Login with admin credentials to manage hospitals and users.
- **Hospital Management**: Add hospitals and their credentials, including bed counts and locations.
- **User Registration**: Create user login credentials using SRFID for secure access.
- **Bed Selection**: Users can select available beds from a list of hospitals.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

<div align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
  </a>
  <a href="https://getbootstrap.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="40" height="40"/>
  </a>
  <a href="https://www.python.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  </a>
  <a href="https://flask.palletsprojects.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="Flask" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
  </a>
  <a href="https://httpd.apache.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apache/apache-original.svg" alt="Apache" width="40" height="40"/>
  </a>
</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### ER Diagram
<img width="532" alt="Screenshot 2024-10-26 at 1 28 51 PM" src="https://github.com/user-attachments/assets/ad10802f-3e67-4d4e-81a7-d07ccb4768c9">


### Schema Diagram
<img width="478" alt="Screenshot 2024-10-26 at 1 28 35 PM" src="https://github.com/user-attachments/assets/e3133415-4fe7-4598-b2c7-28432249cd74">

### Work flow chart

<img width="175" alt="Screenshot 2024-10-26 at 1 29 18 PM" src="https://github.com/user-attachments/assets/6a7118b7-10b3-4c2b-b2f4-a4c143b0a524">


## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

- Python 3.9
- MySQL
- Apache Web Server

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/amoghasbhardwaj/Covid-Bed-Slot-Booking-System.git
2. Navigate to the project directory
	```sh
	cd Covid-Bed-Slot-Booking-System

3. Set up a virtual environment (optional)
	```sh
	python -m venv env
	source env/bin/activate  # For macOS/Linux
	env\Scripts\activate     # For Windows
4. Install required Python packages
	```sh
	pip install -r requirements.txt
5. Set up your MySQL database and configure the connection settings in your application.
6. Run the application
	```sh
	python app.py


### Usage

After setting up the application, you can access it via your web browser. Use the following credentials to test the application:

1.	Admin Login: Use admin credentials to manage hospitals and bookings.
2.	Hospital Login: Use hospital credentials to add data and manage beds.
3.	User Login: Use user credentials to book beds.

<br/>

### Roadmap

- Admin login and management
- Hospital registration
- User registration and login
- Bed selection feature
- Implement hospital suggestions based on user location
- Add severity-based bed allocation
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- LICENSE -->
### License
Distributed under the MIT License. See LICENSE.txt for more information.

### Contributors
<a href="https://github.com/vishwjit22154">
  <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="Vishwajit" width="40" height="40" style="border-radius: 50%;" />
</a>
<span>Vishwajit</span>

<!-- CONTACT -->
<p align="right">(<a href="#readme-top">back to top</a>)</p>
