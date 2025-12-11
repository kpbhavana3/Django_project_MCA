# 🚀 Django Blog Application
https://github.com/user-attachments/assets/9d53d831-1dea-4471-bd69-80e3bfbfa4a1

This is a Django-based blog application that allows users to register, log in, create new posts, view their profile, and browse other users' posts.

## ✨ Features

* **User Registration and Authentication:** Users can sign up and log in securely.
* **Blog Post Management:** Authenticated users can create new blog posts with a title and content.
* **Profile View:** Users can view their profile information.
* **Home/Index Page:** Displays a list of all existing blog posts with author and date information.
* **Post Details:** Clicking on a post title or user name navigates to detailed views:
    * Clicking the post title shows the individual post.
    * Clicking the user name shows all posts by that specific user.
* **Navigation:** Includes links for Home, About, New Post, Profile, and Logout.

## 🛠️ Technologies Used

* **Framework:** Django (Implied by project name and file paths)
* **Database:** Default SQLite (Implied, unless configured otherwise)
* **Frontend:** HTML/CSS (Standard web interface)

## 🏃 Getting Started

### Prerequisites

* Python 3.x
* Git (Recommended for cloning)

### Installation

1.  **Clone the Repository (Replace with actual repository URL):**
    ```bash
    git clone [https://github.com/kpbhavana3/Django_project_MCA.git](https://github.com/kpbhavana3/Django_project_MCA.git)
    cd Django_project_MCA
    ```
    *Note: The GitHub link in the screenshot is `kpbhavana3/Django_project_MCA`.*

2.  **Create a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt # (Assuming you have a requirements file)
    ```

4.  **Database Migration:**
    ```bash
    python manage.py migrate
    ```

5.  **Create a Superuser (Admin Account):**
    ```bash
    python manage.py createsuperuser
    ```

### Running the Application

1.  **Start the Development Server:**
    ```bash
    python manage.py runserver
    ```
2.  **Access the Application:**
    Open your web browser and navigate to `http://127.0.0.1:8000/`.

## 📝 Usage

* **Sign Up:** Click the 'Register' link and fill in the required fields (Username, Email, Password).
* **Login:** Use your newly created credentials on the login page.
* **New Post:** Click **New Post** to create a blog entry by providing a title and content, then click **Post**.
* **View Posts:** The home page shows a feed of posts.
* **View Profile:** Click the **Profile** link to see and potentially update your profile details.
* **Logout:** Click **Logout** to end your session.

 # 🤝 Contribution Guidelines

We welcome contributions from anyone! By contributing to this project, you agree to abide by our Code of Conduct.

## 🐛 Found a Bug or Have a Suggestion?

1.  **Check Existing Issues:** Before submitting a new issue, please check the existing [Issues tab](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/issues) to see if someone has already reported it.
2.  **Open a New Issue:** If it hasn't been reported, open a new issue.
    * **For Bugs:** Clearly describe the bug, steps to reproduce it, and the expected vs. actual behavior.
    * **For Suggestions/Features:** Describe the feature and why you think it would be beneficial.

## ✍️ Making Code Contributions (Pull Requests)

We use the "fork and pull request" model for contributions.

1.  **Fork the Repository:** Click the **Fork** button in the top right corner of the repository page.
2.  **Clone Your Fork:** Clone your forked repository to your local machine.
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    ```
3.  **Create a New Branch:** Always create a new branch for your contribution.
    ```bash
    git checkout -b feature/your-feature-name 
    # OR 
    git checkout -b bugfix/issue-number
    ```
4.  **Make Your Changes:** Write your code, commit often, and ensure your code follows the project's style guide (if one exists).
5.  **Push Changes:** Push your new branch to your forked repository on GitHub.
    ```bash
    git push origin feature/your-feature-name
    ```
6.  **Create a Pull Request (PR):**
    * Go to your forked repository on GitHub.
    * Click **Compare & pull request** next to your pushed branch.
    * Write a clear title and description explaining what your changes do.
    * Submit the Pull Request!

We will review your PR as soon as possible and may suggest changes.

## 📝 Commit Messages

Please use descriptive commit messages. A good format is:
* `feat: Added user profile picture upload` (For a new feature)
* `fix: Corrected pagination bug on home page` (For a bug fix)
