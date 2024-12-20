# My Blog
Link : https://myblog-y0fw.onrender.com/

# MyBlog

**Link:** [https://myblog-y0fw.onrender.com/](https://myblog-y0fw.onrender.com/)

## Overview

**MyBlog** is a web application that allows users to create, manage, and share blog posts. Built with Python and Flask, it offers a simple interface for blogging.

## Features

- **User Authentication:** Register and log in to manage your blog posts.
- **Create and Edit Posts:** Write new blog entries and edit existing ones.
- **View Posts:** Browse all published blog posts.
- **Responsive Design:** Accessible on various devices.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/HiteshSharma04/MyBlog.git
   cd MyBlog
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables:**
   - Create a `.env` file in the root directory.
   - Add necessary environment variables (e.g., `SECRET_KEY`, `DATABASE_URL`).

5. **Run the Application:**
   ```bash
   flask run
   ```
   Access the app at `http://127.0.0.1:5000/`.

## Usage

- **Home Page:** View all published blog posts.
- **Register/Login:** Create an account or log in to manage posts.
- **Dashboard:** Access your posts and create new ones.
- **Create Post:** Write and publish a new blog entry.
- **Edit/Delete Post:** Modify or remove your existing posts.

## Project Structure

```
MyBlog/
├── static/
│   ├── css/
│   └── js/
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── ...
├── .gitignore
├── Procfile
├── README.md
├── forms.py
├── main.py
└── requirements.txt
```

- `main.py`: Main application file.
- `forms.py`: Contains form classes for user input.
- `templates/`: HTML templates for rendering pages.
- `static/`: Static files like CSS and JavaScript.
- `requirements.txt`: List of dependencies.
- `Procfile`: For deployment configurations.

## Deployment

The application is deployed at [https://myblog-y0fw.onrender.com/](https://myblog-y0fw.onrender.com/). For deploying your own instance, consider platforms like Heroku or Render.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

