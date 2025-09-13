# 🎬 Netflix Clone 2025

A modern, responsive Netflix clone built with React and Vite, featuring a sleek UI that mimics the original Netflix experience with movie and TV show browsing capabilities.

![Netflix Clone](https://img.shields.io/badge/Netflix-Clone-red?style=for-the-badge&logo=netflix)
![React](https://img.shields.io/badge/React-19.1.1-blue?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.1.2-purple?style=for-the-badge&logo=vite)

## ✨ Features

- 🎭 **Movie & TV Show Browsing** - Browse through popular movies and TV shows
- 🎬 **Netflix Originals** - Dedicated section for Netflix original content
- 🏆 **Top Rated Content** - Discover highly-rated movies and shows
- 🎭 **Genre-based Categories** - Action, Comedy, Horror, Romance, and Documentaries
- 📺 **TV Shows Section** - Popular TV shows with dedicated browsing
- 🎥 **Movie Trailers** - Watch trailers directly in the app using YouTube integration
- 📱 **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern UI/UX** - Clean, Netflix-inspired interface with smooth animations
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and builds

## 🚀 Live Demo

**[View Live Demo](https://ekhlas61.github.io/movie-stream-clone-2025/)**

## 🛠️ Tech Stack

- **Frontend Framework**: React 19.1.1
- **Build Tool**: Vite 7.1.2
- **Styling**: CSS3 with custom components
- **HTTP Client**: Axios
- **Video Player**: React YouTube
- **Trailer Integration**: Movie Trailer
- **UI Components**: Material-UI (MUI)
- **API**: The Movie Database (TMDB)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ekhlas61/movie-stream-clone-2025.git
   cd movie-stream-clone-2025/netflix-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   VITE_REACT_APP_API_KEY=your_tmdb_api_key_here
   ```
   
   Get your free API key from [The Movie Database (TMDB)](https://www.themoviedb.org/settings/api)

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
netflix-clone/
├── public/
│   └── vite.svg
├── src/
│   ├── Components/
│   │   ├── Banner/
│   │   │   ├── Banner.css
│   │   │   └── Banner.jsx
│   │   ├── Footer/
│   │   │   ├── Footer.css
│   │   │   └── Footer.jsx
│   │   ├── Header/
│   │   │   ├── Header.css
│   │   │   └── Header.jsx
│   │   └── Rows/
│   │       ├── Row/
│   │       │   ├── Row.css
│   │       │   └── Row.jsx
│   │       └── RowList/
│   │           └── RowList.jsx
│   ├── pages/
│   │   └── Home/
│   │       └── Home.jsx
│   ├── utils/
│   │   ├── axios.jsx
│   │   └── requests.jsx
│   ├── assets/
│   │   └── images/
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── dist/
├── package.json
├── vite.config.js
└── README.md
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run deploy` - Deploy to GitHub Pages
- `npm run lint` - Run ESLint

## 🌐 API Integration

This project uses The Movie Database (TMDB) API to fetch:
- Trending movies and TV shows
- Netflix originals
- Top-rated content
- Genre-specific movies
- Popular TV shows
- Movie trailers

## 🎨 Key Components

### Banner Component
- Displays featured content with large backdrop images
- Includes title, description, and call-to-action buttons

### Row Component
- Displays horizontal scrolling lists of movies/shows
- Supports both regular and large poster formats
- Integrated trailer functionality

### Header Component
- Navigation bar with Netflix branding
- Responsive design for different screen sizes

### Footer Component
- Additional navigation links and information

## 🚀 Deployment

The project is configured for GitHub Pages deployment:

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```

The site will be available at: `https://ekhlas61.github.io/movie-stream-clone-2025/`

## 🔧 Configuration

### Vite Configuration
The project uses a custom base path for GitHub Pages:
```javascript
export default defineConfig({
  plugins: [react()],
  base: "/movie-stream-clone-2025/",
});
```

### Package.json Configuration
```json
{
  "homepage": "https://ekhlas61.github.io/movie-stream-clone-2025"
}
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is for educational purposes only. Netflix is a trademark of Netflix, Inc.

## 🙏 Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the API
- [React](https://reactjs.org/) for the amazing framework
- [Vite](https://vitejs.dev/) for the fast build tool
- [Material-UI](https://mui.com/) for the UI components
- [Netflix](https://netflix.com/) for the design inspiration

## 📞 Contact

**Ekhlas** - [@Ekhlas61](https://github.com/Ekhlas61)

Project Link: [https://github.com/Ekhlas61/movie-stream-clone-2025](https://github.com/Ekhlas61/movie-stream-clone-2025)

---

⭐ Star this repository if you found it helpful!