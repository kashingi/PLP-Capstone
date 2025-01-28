# Modern Blog Website

A modern, responsive blog website with advanced UI/UX features, 3D effects, and dynamic content loading. Built with HTML, CSS, and JavaScript.

## Project Architecture

```mermaid
graph TD
    A[Photo Hub] --> B[Frontend]
    B --> C[app module]
    B --> D[Album Module]
    B --> E[Authentication Module]
    B --> F[Photo Module]
    B --> G[User Module]
    C --> H[footer]
    C --> I[header]
    C --> J[not found]
    D --> K[album detail]
    D --> L[album list]
    D --> M[album service]
    E --> N[register]
    E --> O[login]
    E --> P[auth service]
    F --> Q[photo list]
    F --> R[photo detail]
    F --> S[photo service]
    F --> T[contact.html]
    G --> U[user lis]
    G --> V[user detail]
    G --> W[user service]
```

## Features

### Visual Effects & Animations
- 3D card flipping effects with smooth transitions
- Parallax scrolling in hero section
- Glass morphism effects in navigation
- Advanced button animations with 3D transforms
- Floating animations for text elements
- Gradient text with glow effects
- Custom scrollbar with gradient design
- Loading animations and spinners
- Ripple effects on interactive elements
- Shine effects on hover states

```mermaid
mindmap
  root((Visual Effects))
    3D Effects
      Card Flip
      Button Transform
      Parallax
    Animations
      Floating
      Loading
      Scroll
    Styling
      Glass Morphism
      Gradients
      Shadows
    Interactions
      Hover Effects
      Ripple
      Shine
```

### Layout & Design
- Responsive masonry grid layout
- Modern card designs with hover effects
- Advanced typography with Google Fonts (Inter & Poppins)
- Dark/Light theme toggle
- Glass morphism navigation
- Gradient borders and shadows
- Custom scrollbar styling

### User Experience Flow

```mermaid
flowchart LR
    A[User Visit] --> B[Home Page]
    B --> C[Theme Toggle]
    B --> D[Navigation]
    D --> E[About]
    D --> F[Blog]
    D --> G[Contact]
    F --> H[Read Post]
    H --> I[Dynamic Loading]
    G --> J[Form Submit]
    J --> K[Validation]
```

### Performance
- Lazy loading images
- Optimized animations
- Efficient CSS variables
- Smooth transitions
- Mobile-first approach

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/PLP-WebTechnologies/Saf-Hook-Capstone-Web.git
```

2. Open `index.html` in your browser to view the website.

## Project Structure

```mermaid
graph LR
    A[Project Root] --> B[assets/]
    A --> C[HTML Pages]
    B --> D[css/]
    B --> E[js/]
    D --> F[styles.css]
    D --> G[advanced.css]
    E --> H[main.js]
    C --> I[index.html]
    C --> J[about.html]
    C --> K[blog.html]
    C --> L[contact.html]
```

## CSS Variables

The project uses CSS variables for consistent styling. Key variables include:

```css
:root {
    --primary-color: #4f46e5;
    --secondary-color: #818cf8;
    --accent-color: #8b5cf6;
    /* ... other variables */
}
```

## JavaScript Features

```mermaid
classDiagram
    class ThemeManager {
        +toggleTheme()
        +persistTheme()
    }
    class ScrollManager {
        +smoothScroll()
        +scrollReveal()
        +parallaxEffect()
    }
    class CardEffects {
        +init3DCards()
        +handleHover()
        +flipCard()
    }
    class ContentLoader {
        +loadPosts()
        +renderPost()
        +handleInfiniteScroll()
    }
    class FormHandler {
        +validateForm()
        +submitForm()
        +showFeedback()
    }
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Development Workflow

```mermaid
gitGraph
    commit
    branch develop
    checkout develop
    commit
    branch feature
    checkout feature
    commit
    commit
    checkout develop
    merge feature
    checkout main
    merge develop
    commit
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Fonts from [Google Fonts](https://fonts.google.com) 