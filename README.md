# Jekyll Portfolio

A professional portfolio website built with Jekyll and the Minima theme. This portfolio showcases your projects, skills, and experience in a clean, modern design.

## Screenshots

### Home Page
![Home Page](https://github.com/user-attachments/assets/6482307b-7a04-4e81-9c6e-959f146c9998)

### Projects Page
![Projects Page](https://github.com/user-attachments/assets/f12207d2-be21-4d5e-922f-f3f0c3bde74a)

### Project Detail Page
![Project Detail](https://github.com/user-attachments/assets/06ce07ea-0a6f-4539-8390-9c80ae6d96ec)

## Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Project Showcase**: Dedicated section for displaying your portfolio projects
- **Custom Styling**: Enhanced CSS for an attractive portfolio presentation
- **SEO Optimized**: Built-in SEO tags for better search engine visibility
- **RSS Feed**: Automatic feed generation for blog posts
- **Easy Customization**: Simple configuration through `_config.yml`

## Prerequisites

- Ruby 3.0 or higher
- Bundler gem

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Scapeternam/Jekyll-Portfolio.git
   cd Jekyll-Portfolio
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

## Building the Site

To build the site:

```bash
bundle exec jekyll build
```

The generated site will be in the `_site` directory.

## Running Locally

To run the site locally with live reload:

```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

For the site to be accessible from other devices on your network:

```bash
bundle exec jekyll serve --host 0.0.0.0
```

## Customization

### Basic Configuration

Edit `_config.yml` to customize:

- Site title and description
- Your email and social media links
- SEO settings
- Navigation menu

### Adding Projects

1. Create a new markdown file in the `_projects` directory
2. Add front matter with project details:

```yaml
---
title: Your Project Name
description: Brief project description
technologies:
  - Technology 1
  - Technology 2
github: https://github.com/yourusername/project
demo: https://your-demo-url.com
---
```

3. Add your project content in markdown below the front matter

### Modifying Pages

- **Home Page**: Edit `index.md`
- **About Page**: Edit `about.md`
- **Projects List**: Edit `projects.md`

### Custom Styling

Custom styles are in `assets/css/style.scss`. This file imports the Minima theme and adds portfolio-specific styling.

## Project Structure

```
Jekyll-Portfolio/
├── _config.yml           # Site configuration
├── _layouts/             # Custom layouts
│   └── project.html      # Layout for individual projects
├── _projects/            # Portfolio project files
│   ├── ecommerce-website.md
│   ├── task-management-app.md
│   └── weather-dashboard.md
├── assets/
│   └── css/
│       └── style.scss    # Custom styles
├── about.md              # About page
├── index.md              # Home page
├── projects.md           # Projects listing page
├── Gemfile               # Ruby dependencies
└── README.md             # This file
```

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select the branch to deploy (usually `main`)
4. Your site will be available at `https://yourusername.github.io/Jekyll-Portfolio/`

### Netlify

1. Connect your GitHub repository to Netlify
2. Build command: `bundle exec jekyll build`
3. Publish directory: `_site`

### Other Hosting

Upload the contents of the `_site` directory to any static web hosting service.

## Technologies Used

- **Jekyll 4.4**: Static site generator
- **Minima Theme**: Clean, minimal theme
- **Jekyll Feed**: RSS feed generation
- **Jekyll SEO Tag**: SEO optimization
- **Sass**: CSS preprocessing

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For questions or feedback, please open an issue in this repository.