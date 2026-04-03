# 🟡 Intermediate Projects

> These projects bridge the gap between beginner exercises and advanced applications. They require combining multiple skills, working with APIs, and thinking more carefully about structure and design.

---

## 🐍 Python Intermediate Projects

### 1. 🌤️ Weather App with API
**Skills:** `requests`, JSON parsing, API keys, error handling
**Description:** Fetch real-time weather data from the OpenWeatherMap API. Display temperature, humidity, wind speed, and a 5-day forecast for any city.

**Features to implement:**
- Accept city name as input
- Call OpenWeatherMap API and parse JSON response
- Display current weather and 5-day forecast
- Handle errors (invalid city, network issues)
- Cache recent results to avoid repeated API calls

---

### 2. 📊 CSV Data Analyzer
**Skills:** Pandas, Matplotlib/Seaborn, file I/O
**Description:** Build a tool that reads a CSV file, cleans the data, generates summary statistics, and creates visualizations (bar charts, histograms, scatter plots).

**Features to implement:**
- Load any CSV and display column info and data types
- Detect and handle missing values
- Summary statistics (mean, median, std dev, quartiles)
- Generate and save at least 3 chart types
- Export a basic HTML or PDF report

---

### 3. 🔐 Password Manager (CLI)
**Skills:** Encryption (`cryptography` library), file I/O, hashing
**Description:** Build a secure command-line password manager that encrypts stored passwords with a master key. Users can add, retrieve, and delete entries.

**Features to implement:**
- Master password to unlock the vault (hashed with `bcrypt`)
- Encrypt passwords with AES via the `cryptography` library
- Store entries in an encrypted file or SQLite database
- Search and retrieve credentials by service name
- Generate strong random passwords

---

### 4. 🤖 Web Scraper with Data Storage
**Skills:** `BeautifulSoup`, `requests`, SQLite or CSV, scheduling
**Description:** Scrape structured data from a website (e.g., news headlines, job listings, or product prices) and store it persistently for trend tracking.

**Features to implement:**
- Scrape a target website with proper headers and rate limiting
- Parse HTML to extract structured data
- Store results in SQLite with timestamps
- Detect and skip duplicate entries
- Schedule to run periodically with `schedule` library

---

### 5. 📝 Blog Platform (Flask)
**Skills:** Flask, SQLite/SQLAlchemy, Jinja2 templates, HTML/CSS
**Description:** Build a minimal blog website with Flask. Users can create, read, update, and delete posts via a browser UI.

**Features to implement:**
- CRUD operations for posts
- Jinja2 templating for HTML pages
- SQLite database with SQLAlchemy ORM
- Simple authentication (admin login with hashed password)
- Pagination for post listings
- Markdown rendering for post content

---

## 🌐 Web Development Intermediate Projects

### 6. 🌤️ Weather Dashboard
**Skills:** React, Fetch API, localStorage, CSS animations
**Description:** A visually polished weather app that displays current weather and a 5-day forecast using the OpenWeatherMap API. Add search history with localStorage.

**Features to implement:**
- City search with autocomplete suggestions
- Current weather (icon, temperature, description, humidity, wind)
- 5-day forecast cards
- Toggle between Celsius and Fahrenheit
- Persist last 5 searches in localStorage
- Animated weather icons or backgrounds

---

### 7. 📝 Full-Stack Notes App
**Skills:** React, Node.js/Express, MongoDB, REST API, JWT
**Description:** A notes application with user accounts. Each user can create, read, update, and delete their own notes, with full authentication.

**Features to implement:**
- User registration and login (JWT stored in httpOnly cookies)
- Create, view, edit, delete notes
- Search and filter notes by title or tag
- Rich text editor (Quill.js or `react-quill`)
- Responsive design for mobile and desktop

---

### 8. 🎬 Movie Search & Watchlist
**Skills:** React, OMDB or TMDB API, localStorage, React Router
**Description:** Let users search for movies, view details, and manage a personal watchlist. All watchlist data persists in localStorage.

**Features to implement:**
- Search movies with debounced input
- Display results with poster, year, and rating
- Movie detail page (plot, cast, runtime, genre)
- Add/remove from watchlist
- Filter watchlist by genre or status (watched/unwatched)

---

### 9. 💬 Real-Time Chat App
**Skills:** React, Node.js, Socket.io, MongoDB
**Description:** Build a real-time group chat application where multiple users can join named rooms and exchange messages instantly.

**Features to implement:**
- Join/create named chat rooms
- Real-time message delivery with Socket.io
- Show connected users list
- Message timestamps
- Store message history in MongoDB
- Notify when users join or leave

---

### 10. 🛒 Shopping Cart with Checkout
**Skills:** React, Context API or Redux, localStorage
**Description:** A product listing page with a shopping cart. Users can add/remove items, adjust quantities, and see a running total.

**Features to implement:**
- Product catalog with images, prices, and categories
- Filter by category and sort by price
- Add to cart, adjust quantity, remove from cart
- Cart persists across page reloads (localStorage)
- Subtotal, tax, and total calculation
- Mock checkout flow (form validation)

---

## 🤖 AI / ML Intermediate Projects

### 11. 😊 Sentiment Analysis on Real Data
**Skills:** Hugging Face Transformers, Pandas, Streamlit
**Description:** Analyze sentiment (positive/negative/neutral) in real text data (tweets, reviews) using a pre-trained transformer model. Visualize the results.

**Features to implement:**
- Load a dataset of tweets or product reviews
- Run sentiment classification with a Hugging Face model
- Visualize sentiment distribution with Seaborn/Plotly
- Build a Streamlit UI to analyze custom text in real time
- Export results to CSV

---

### 12. 🖼️ Image Classifier (Transfer Learning)
**Skills:** TensorFlow/PyTorch, Transfer Learning (MobileNet or ResNet), Streamlit
**Description:** Use transfer learning to fine-tune a pre-trained CNN on a custom dataset (e.g., cats vs dogs, or a dataset of your choice). Deploy as a web app.

**Features to implement:**
- Load and preprocess a custom image dataset
- Fine-tune a pre-trained model (freeze base layers, train head)
- Plot training/validation accuracy and loss curves
- Build a Streamlit app to upload and classify new images
- Display top-3 predictions with confidence scores

---

### 13. 📰 News Headline Classifier
**Skills:** Scikit-learn, TF-IDF, Pandas, text preprocessing
**Description:** Train a multi-class text classifier that categorizes news headlines into topics (e.g., sports, politics, tech, entertainment).

**Features to implement:**
- Use a public news dataset (e.g., AG News or BBC News)
- Preprocess text (lowercase, remove stopwords, tokenize)
- TF-IDF feature extraction
- Train and compare at least 3 models (Naive Bayes, Logistic Regression, SVM)
- Evaluate with accuracy, precision, recall, F1-score
- Build a simple prediction interface

---

## 🏗️ System Design / Backend Intermediate Projects

### 14. 🔗 RESTful Task Manager API
**Skills:** Node.js/Express or FastAPI, PostgreSQL, JWT, Swagger
**Description:** Build a well-structured REST API for managing tasks and projects. Focus on API design principles, authentication, and documentation.

**Features to implement:**
- User authentication with JWT (register, login, refresh tokens)
- CRUD for projects and tasks
- Assign tasks to users, set priorities and due dates
- Filter and sort tasks by status, priority, or assignee
- Swagger/OpenAPI documentation
- Input validation and proper HTTP status codes

---

### 15. 📊 Personal Finance Tracker
**Skills:** React, Node.js, PostgreSQL, Recharts/Chart.js
**Description:** Build a full-stack app to track income and expenses. Display spending trends with interactive charts.

**Features to implement:**
- Add, edit, delete transactions with category and date
- Dashboard with monthly summary (income, expenses, balance)
- Category breakdown pie chart
- Monthly spending trend line chart
- Filter transactions by date range or category
- Export data to CSV

---

## 💡 Tips for Intermediate Developers

- 🏛️ **Plan before coding** — sketch your data models and component structure first.
- 🔐 **Never store secrets in code** — use `.env` files and add them to `.gitignore`.
- 📖 **Read error messages carefully** — they almost always tell you exactly what's wrong.
- 🧪 **Write at least basic tests** — test your API endpoints and critical functions.
- 🔁 **Refactor often** — clean code is as important as working code.
- 🌐 **Deploy your projects** — even a free-tier deployment on Railway, Vercel, or Render counts.
- 💬 **Show your work** — write a short README for every project explaining what it does and how to run it.

---

[⬅️ Back to Main README](../README.md) | [🟢 Beginner Projects ←](beginner-projects.md) | [🔴 Advanced Projects →](advanced-projects.md)
