
---

````markdown
# 🎬 AngularJS IMDB Movie Browser

This is a single-page movie browsing web application built with **AngularJS 1.x**, **Bootstrap 3**, and the **IMDB API**. It allows users to explore trending movies, view detailed movie information, and see cast and crew credits — all styled with a responsive UI.

---

## 🌐 Features

- Browse movies with posters, titles, and ratings.
- View detailed information (plot, release date, genres, trailers).
- See full cast and crew credits.
- Search movies in real-time.
- Responsive design powered by Bootstrap.

---

## 🛠 Tech Stack

- AngularJS 1.x
- Angular Route
- Bootstrap 3
- IMDB API (via RapidAPI or TMDb depending on your setup)
- Custom directives, components, and templates

---

## 🚀 Getting Started

Follow these steps to set up the project on your local machine.

### 1. 📦 Clone the Repository

```bash
git clone https://github.com/alakhirnayan/Imdb_website-using-IMDB-API.git
cd Imdb_website-using-IMDB-API
````

### 2. 🧩 Prerequisites

Ensure you have a basic HTTP server. If not, install one:

**Option 1: Python**

```bash
# Python 3.x
python -m http.server 8000
```

**Option 2: Node.js (http-server)**

```bash
npm install -g http-server
http-server
```

> ⚠️ *Don't open index.html directly in the browser as Angular routing requires a server.*

### 3. 🔑 Set Up the API Key

This project uses the IMDB (or TMDb) API. To enable it:

* Sign up at [https://rapidapi.com](https://rapidapi.com) or [https://www.themoviedb.org](https://www.themoviedb.org) to get your API key.
* Open `connectionModule.js` (not yet uploaded here).
* Locate the section where HTTP requests are configured.
* Replace the placeholder API key with your own:

```javascript
headers: {
  'X-RapidAPI-Key': 'YOUR_API_KEY',
  'X-RapidAPI-Host': 'imdb-api-host-name'
}
```

---

## 🧱 Project Structure

```
├── index.html                  # Main app file with ng-view
├── /resources
│   ├── /angular                # AngularJS libraries
│   ├── /bootstrap              # Bootstrap CSS & JS
│   ├── /custom
│   │   ├── imdbModule.js       # Main Angular module and routing
│   │   ├── connectionModule.js # Service that connects to the IMDB API
│   │   └── ngimdb.css          # Custom styles
│   └── ...
├── /templates
│   ├── home.html
│   ├── movieItems.html
│   ├── movieDetails.html
│   ├── credit.html
│   ├── navigation.html
│   └── ...
```

---


---

## ✨ Credits

Developed by **\[AL-AKHIR NAYAN]**
Powered by IMDB API, AngularJS, and Bootstrap.

---

## 📄 License

This project is licensed under the MIT License.
Feel free to modify and share!

```

