# YouTube Clone

A responsive YouTube homepage clone built with HTML and CSS, featuring a modern layout with header navigation, sidebar, and video grid.

## 🎯 Overview

This project is a pixel-perfect recreation of YouTube's homepage interface, built as a follow-along project from [supersimple.dev](https://supersimple.dev/exercises/youtube). It demonstrates modern CSS techniques including CSS Grid, Flexbox, and responsive design principles.

## ✨ Features

### Header Navigation

- **Logo and hamburger menu** - YouTube branding with navigation toggle
- **Search functionality** - Search bar with voice search option
- **User controls** - Upload, apps, notifications, and profile sections
- **Interactive tooltips** - Hover tooltips for all navigation buttons

### Sidebar Navigation

- **Quick access links** - Home, Explore, Subscriptions, etc.
- **Fixed positioning** - Sidebar remains visible during scroll
- **Hover effects** - Visual feedback on link interaction

### Video Grid

- **Responsive video cards** - Thumbnail, title, author, and stats
- **Channel profile tooltips** - Hover tooltips showing channel info
- **Video duration badges** - Time stamps on thumbnails
- **Clickable elements** - Links to YouTube videos and channels

### Interactive Elements

- **Hover effects** - Smooth transitions on buttons and cards
- **Tooltips** - Informative hover tooltips throughout the interface
- **Responsive behavior** - Adapts to different screen sizes

## 🏗️ Project Structure

```
youtube-clone/
├── youtube.html              # Main HTML file
├── styles/
│   ├── general.css          # Global styles and typography
│   ├── header.css           # Header navigation styles
│   ├── sidebar.css          # Sidebar navigation styles
│   ├── video.css            # Video grid and card styles
│   └── footer.css           # Footer styles
├── icons/                   # SVG icons for navigation
├── channel-pictures/        # Channel profile images
├── thumbnails/             # Video thumbnail images
├── README.md               # Project documentation
└── .gitignore             # Git ignore file
```

## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd youtube-clone
   ```

## 💻 Usage

### Viewing the Project

- Open [`youtube.html`](youtube.html) in any modern web browser

## 📱 Responsive Design

The project includes responsive breakpoints for optimal viewing:

- **Tablet** (751px-999px): 3-column video grid
- **Desktop** (≥1000px): 4-column video grid

Key responsive features:

- Flexible video grid layout
- Responsive typography
- optimized spacing
- Adaptive image sizing

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling and layout
  - CSS Grid for video layout
  - Flexbox for navigation
  - Custom properties for consistency
  - Responsive design techniques
- **Google Fonts** - Roboto font family

## 📁 File Structure

### HTML Structure

- **Header**: Navigation bar with search and user controls
- **Sidebar**: Navigation menu with quick links
- **Main**: Video grid with responsive cards
- **Footer**: Additional content area

### CSS Organization

- [`styles/general.css`](styles/general.css) - Global styles, typography, body layout
- [`styles/header.css`](styles/header.css) - Header navigation, search bar, tooltips
- [`styles/sidebar.css`](styles/sidebar.css) - Sidebar navigation, fixed positioning
- [`styles/video.css`](styles/video.css) - Video grid, cards, responsive layout
- [`styles/footer.css`](styles/footer.css) - Footer styling

### Assets

- **Icons**: SVG files for navigation elements
- **Images**: Channel profile pictures and video thumbnails
- **Fonts**: Google Fonts integration for Roboto

## 🎨 Key CSS Features

### Layout Techniques

- **CSS Grid** - Responsive video grid layout
- **Flexbox** - Header and sidebar navigation
- **Fixed positioning** - Persistent header and sidebar

### Interactive Elements

- **Hover effects** - Smooth transitions and feedback
- **Tooltips** - Positioned absolute elements with opacity transitions
- **Responsive images** - Flexible sizing with object-fit

### Design Patterns

- **Component-based styling** - Modular CSS organization
- **Consistent spacing** - Systematic margin and padding

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📝 Acknowledgments

- [**supersimple.dev**](https://supersimple.dev/) - Original tutorial and project guidance

---

**Live Demo**: Open [`youtube.html`](youtube.html) in your browser to see the project in action!

**Note**: This is a static clone for educational purposes. No actual YouTube functionality is implemented.
