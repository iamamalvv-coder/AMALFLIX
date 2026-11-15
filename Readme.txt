# 🎬 AMALFLIX – Must Watch Movies

**AMALFLIX** is a Netflix-inspired movie discovery website featuring a curated collection of 10 must-watch movies. It provides a cinematic browsing experience with a modern dark-themed interface, movie posters, ratings, genre filters, search functionality, and a personal watchlist.

Built using HTML, CSS, and JavaScript, AMALFLIX is a lightweight, responsive web application that can be deployed on AWS S3 Static Website Hosting.

---

## 🌟 Project Overview

AMALFLIX brings together a collection of highly recommended movies in a simple and visually appealing streaming-platform-style interface.

Users can explore movies, view descriptions, check ratings, filter by genre, search for their favourite titles, and save movies to their personal watchlist.

## ✨ Features

- 🎥 **Netflix-Inspired UI:** Modern dark-themed cinematic interface.
- 🍿 **Top 10 Movies:** Curated collection of 10 must-watch movies.
- 🔍 **Movie Search:** Search movies by title.
- 🎭 **Genre Filters:** Filter movies by Sci-Fi, Drama, Action, Thriller, and Animation.
- ⭐ **Movie Ratings:** Display movie ratings and release years.
- ❤️ **My Watchlist:** Add or remove favourite movies.
- 📖 **Movie Details:** View descriptions, directors, genres, and duration.
- ▶️ **Trailer Access:** Find official movie trailers through YouTube.
- 📱 **Responsive Design:** Compatible with desktop, tablet, and mobile devices.
- 💾 **Local Storage:** Save watchlist preferences in the browser.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling, layout and responsive design |
| JavaScript | Interactive functionality |
| Local Storage | Watchlist persistence |
| TMDB Image CDN | Movie poster images |
| YouTube | Movie trailer discovery |
| AWS S3 | Static website hosting |

## 🎞️ Featured Movies

The website currently includes:

1. Inception (2010)
2. Interstellar (2014)
3. The Dark Knight (2008)
4. The Shawshank Redemption (1994)
5. Parasite (2019)
6. Pulp Fiction (1994)
7. The Matrix (1999)
8. Spirited Away (2001)
9. Gladiator (2000)
10. Whiplash (2014)

## 📂 Project Structure

```text
AMALFLIX/
│
├── index.html
│
└── README.md
```

The project uses a single HTML file containing the website structure, CSS styling, and JavaScript functionality.

## 🚀 How to Run Locally

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/AMALFLIX.git
```

**Step 2: Navigate to the project directory**

```bash
cd AMALFLIX
```

**Step 3: Open the website**

Open `index.html` directly in your browser.

Alternatively, use the VS Code Live Server extension.

## ☁️ AWS Deployment – S3 Static Website Hosting

AMALFLIX can be deployed using Amazon S3 static website hosting.

**Deployment steps:**

1. Log in to the AWS Management Console.
2. Navigate to Amazon S3.
3. Create a new S3 bucket.
4. Upload the `index.html` file.
5. Open the bucket's Properties section.
6. Navigate to Static Website Hosting.
7. Enable static website hosting.
8. Set `index.html` as the index document.
9. Configure the required bucket access permissions if public website access is intended.
10. Access the website using the S3 static website endpoint.

**Optional enhancement:** Use Amazon CloudFront with S3 to distribute the website through a CDN and support HTTPS.

## 🖥️ Application Functionality

| Component | Description |
|---|---|
| Hero Section | Featured movie introduction |
| Navigation | AMALFLIX branding and search |
| Movie Grid | Displays all 10 movies |
| Genre Filters | Filters movies by category |
| Movie Details | Displays detailed movie information |
| Watchlist | Saves favourite movies |
| Trailer Button | Opens YouTube trailer search |
| Footer | Website branding and copyright information |

## 🔮 Future Enhancements

- User registration and authentication.
- Backend integration using Node.js.
- Database integration using MySQL or MongoDB.
- Admin dashboard to manage movie collections.
- Dynamic movie information using TMDB API.
- Personalized movie recommendations.
- CloudFront CDN integration.
- Movie watch history and user profiles.

## 📌 Important Notes

- AMALFLIX is a movie discovery and recommendation website, not a full-length movie streaming service.
- Movie trailers are accessed through YouTube search results.
- Movie poster images are loaded from an external image CDN.
- Watchlist information is stored locally in the user's browser.
- No backend or database is currently required.

## 👨‍💻 Author

**Amal V V**

Cybersecurity | AWS Cloud | DevOps | Web Development

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)

---

⭐ If you like this project, consider giving the repository a star!

**AMALFLIX – Your next favourite movie is waiting.** 🍿