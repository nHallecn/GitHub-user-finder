# 🔎 GitHub User Finder 🧑‍💻

A sleek, responsive web application that allows users to search for any GitHub profile and instantly view their key statistics, contact information, and recent public repositories.

This project is built using **vanilla HTML, CSS, and JavaScript**, making direct API calls to the **GitHub REST API**.

---

## ✨ Features

* **Instant Search:** Quickly search for any public GitHub username.
* **Detailed Profile:** Displays the user's avatar, name, bio, location, and GitHub join date.
* **Key Metrics:** Shows Followers, Following, and Public Repositories counts.
* **Latest Repositories:** Fetches and displays the user's 10 most recently updated public repositories, including language, stars, and forks.
* **Contact Info:** Links to the user's company, blog/website, and Twitter profile (if available).
* **Responsive Dark Theme:** Optimized for all screen sizes with a clean, modern dark aesthetic.

---

## 🚀 Getting Started

To run this project locally, follow these simple steps.

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, or Edge).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/github-user-finder.git](https://github.com/YOUR-USERNAME/github-user-finder.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd github-user-finder
    ```
3.  **Open in your browser:**
    Simply open the `index.html` file in your web browser. Since all data fetching uses standard API calls, no local server is required.

    ```bash
    open index.html 
    # Or, double-click the file
    ```

---

## 🔗 Data Source

All profile and repository information is dynamically fetched from:

**[GitHub REST API](https://docs.github.com/en/rest)**

The application adheres to GitHub's rate limits and uses only public data.

