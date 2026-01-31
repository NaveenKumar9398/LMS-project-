# LearnHub - Learning Management System

A modern, responsive Learning Management System (LMS) frontend built with HTML, CSS, and JavaScript.

## Features

### User Authentication
- **Login Page** - Secure user login with email and password
- **Registration Page** - New user registration with role selection (Student/Instructor/Admin)
- Session management with localStorage

### Dashboard
- Overview statistics (Enrolled Courses, Learning Hours, Completed Courses, Certificates)
- Continue learning section with progress tracking
- Recent activity feed
- Upcoming deadlines

### Video Management
- **Video Upload** - Drag & drop video upload with progress tracking
- **Video Library** - Browse and filter all courses
- Video player integration ready
- Thumbnail upload support
- Category and tag management

### Student Management
- Student profile with personal details
- Education and skills sections
- Student list with search and filter
- Progress tracking per student
- CRUD operations for student records

### Certificates
- Beautiful certificate design with print support
- Certificate preview modal
- Download and share functionality
- Progress tracking for pending certificates

## Project Structure

```
lms/
├── index.html          # Landing page
├── login.html          # Login page
├── register.html       # Registration page
├── dashboard.html      # User dashboard
├── videos.html         # Course/Video library
├── video-upload.html   # Video upload page
├── students.html       # Student management
├── certificates.html   # Certificates page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # Main JavaScript file
└── README.md           # This file
```

## Getting Started

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **Register** a new account or **login** to access the dashboard

### Demo Credentials
You can register with any email and password (min 8 characters) to explore the system.

## Pages Overview

| Page | Description |
|------|-------------|
| `index.html` | Public landing page with features and courses |
| `login.html` | User authentication |
| `register.html` | New user registration |
| `dashboard.html` | Main user dashboard |
| `videos.html` | Video course library |
| `video-upload.html` | Upload new video content |
| `students.html` | Student profiles and management |
| `certificates.html` | View and download certificates |

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Flexbox, Grid
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome 6** - Icons
- **Google Fonts (Inter)** - Typography

## Features Highlights

### Responsive Design
- Mobile-first approach
- Works on desktop, tablet, and mobile devices
- Collapsible sidebar for smaller screens

### Modern UI/UX
- Clean, professional design
- Smooth animations and transitions
- Intuitive navigation
- Consistent color scheme with CSS variables

### Interactive Elements
- Drag & drop file upload
- Progress bars with animations
- Modal dialogs
- Tab navigation
- Filter buttons
- Pagination

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

### Colors
Edit the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #0ea5e9;
    --accent-color: #f59e0b;
    /* ... more variables */
}
```

### Adding New Pages
1. Create a new HTML file
2. Include the CSS and JS files
3. Copy the navbar and sidebar structure from existing pages
4. Add your content

## Future Enhancements

- [ ] Dark mode theme
- [ ] Video player integration
- [ ] Real-time notifications
- [ ] Chat/messaging system
- [ ] Quiz and assessment module
- [ ] Payment integration
- [ ] Backend API integration

## License

This project is open source and available for educational purposes.

## Author

Created for LearnHub LMS - A Modern Learning Platform

---

Made with ❤️ for learners worldwide
