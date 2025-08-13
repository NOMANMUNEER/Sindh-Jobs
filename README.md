# JobsPortal Sindh 🇵🇰

A modern, responsive web application built as a learning project to create a centralized portal for government job openings in Sindh, Pakistan. The site features a dynamic, interactive landing page and provides easy filtering of jobs by district and department.



## ✨ Key Features

* **Interactive Landing Page**: An immersive, multi-section landing page that showcases the latest jobs and key features.
* **Comprehensive Job Listings**: A dedicated page to browse all available government jobs.
* **Dynamic Filtering**: Users can easily filter jobs by specific districts or government departments.
* **API-Driven**: The frontend fetches all data from a custom-built API within the Next.js application.
* **Fully Responsive Design**: A consistent and beautiful user experience across desktop and mobile devices.
* **Modern Theming**: A vibrant, dark-themed purple gradient color scheme.

---

## 🛠️ Tech Stack

This project is built with a modern, performant tech stack:

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **Framework**: Next.js (App Router)
* **UI Library**: React
* **Styling**: Tailwind CSS
* **Icons**: Lucide React

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js (version 18.x or later) and npm installed on your machine.

* [Node.js](https://nodejs.org/)

### Installation

1.  **Clone the repository**
    ```sh
    # Replace YOUR_GITHUB_USERNAME with your actual username
    git clone [https://github.com/NOMANMUNEER/Sindh-Jobs.git](https://github.com/NOMANMUNEER/Sindh-Jobs.git)
    ```

2.  **Navigate to the project directory**
    ```sh
    cd jobs-portal-app
    ```

3.  **Install NPM packages**
    ```sh
    npm install
    ```

4.  **Run the development server**
    ```sh
    npm run dev
    ```

Now, open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📡 API Endpoints

The application serves its own data through the following API endpoints:

* `GET /api/jobs`
    * Returns a complete list of all jobs.
* `GET /api/jobs/district/[districtName]`
    * Returns jobs filtered by a specific district.
* `GET /api/jobs/department/[departmentName]`
    * Returns jobs filtered by a specific department.

---

This project was built as part of a learning journey into Next.js and modern web development practices.

