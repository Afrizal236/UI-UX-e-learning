# BersamaRamy Learning Platform

## Overview

BersamaRamy is an online learning platform that has evolved from a general programming course website to a specialized SNBT (Seleksi Nasional Berdasarkan Tes) preparation platform called "RuangRamy Belajar SNBT". The platform offers interactive courses, professional mentors, and comprehensive study materials.

## Project Structure

```
├── index.html          # Original light theme version
├── index2.html         # Dark theme version with embedded CSS
├── index3.html         # Final SNBT-focused version
├── style.css           # Stylesheet for original version
├── style2.css          # Stylesheet for second version
├── style3.css          # Dark theme stylesheet for SNBT version
└── video.js            # JavaScript for video controls
```

## Features

### Core Functionality
- **Responsive Design**: Mobile-friendly layout that adapts to different screen sizes
- **Multi-theme Support**: Light and dark theme options
- **Interactive Navigation**: Sticky navigation bar with smooth scrolling
- **Video Integration**: Embedded YouTube videos for learning content
- **User Registration**: Sign-up form with validation
- **Mentor Showcase**: Professional mentor profiles with images
- **Partner Display**: University and institution partnerships

### Page Sections
1. **Home**: Hero section with main value proposition
2. **Courses**: Course offerings with video content
3. **Mentors**: Professional mentor profiles
4. **Partners**: Partner institutions and universities
5. **Contact**: Footer with contact information
6. **Sign Up**: User registration form

## Versions

### Version 1 (index.html)
- Light theme design
- Basic programming course focus
- External CSS styling
- Classic web design approach

### Version 2 (index2.html)
- Dark theme implementation
- Embedded CSS for better performance
- Enhanced visual effects
- Modern color palette

### Version 3 (index3.html - Final)
- SNBT exam preparation focus
- Enhanced video integration
- Advanced user registration
- Complete dark theme experience
- Sign up and logout functionality

## Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **YouTube API**: Video embedding
- **Google Fonts**: Typography (Roboto)

## Installation & Setup

1. Clone or download the project files
2. Open any of the HTML files in a web browser
3. For the complete experience, use `index3.html` (latest version)
4. Ensure internet connection for external resources (fonts, images, videos)

```bash
# Simple setup - no build process required
# Just open in browser:
open index3.html
```

## CSS Variables (Dark Theme)

The project uses CSS custom properties for consistent theming:

```css
:root {
    --bg-color: #121212;
    --primary-color: #1E1E1E;
    --secondary-color: #2C2C2C;
    --accent-color: #BB86FC;
    --text-color: #E0E0E0;
    --secondary-text: #A0A0A0;
}
```

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## Form Fields (Registration)

The sign-up form includes:
- **Nama**: Student name
- **Kelas**: Class/Grade level
- **Materi SNBT**: Subject selection (dropdown)
  - Literasi Bindo
  - Penalaran Umum
  - Literasi Big
  - Penalaran Matematika
  - Tes Potensi Skolastik
- **Gender**: Radio button selection
- **Umur**: Age input (10-100 range)

## External Dependencies

- Google Fonts (Roboto)
- YouTube embedded videos
- External images from various CDNs
- University logos and partner images

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different browsers
5. Submit a pull request

## Future Enhancements

- [ ] Backend integration for form submissions
- [ ] User authentication system
- [ ] Progress tracking for courses
- [ ] Interactive quizzes and assessments
- [ ] Mobile app version
- [ ] Multi-language support
- [ ] Payment integration for premium courses

## License

This project is created for educational purposes. All external images and videos belong to their respective owners.

## Contact

For questions or support regarding the RuangRamy platform:
- **Address**: Jl. WR. Supratman Surabaya, Kode Pos: 34523
- **YouTube**: RuangRamy
- **Instagram**: RuangRamy SNBT

---

© 2024 RuangRamy Belajar SNBT. All Rights Reserved.
