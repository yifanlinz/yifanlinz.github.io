# Yifan Lin - Academic Website

This is my personal academic website built with Jekyll and hosted on GitHub Pages.

## About This Website

This website showcases my research, publications, teaching experience, and academic journey. It's designed to be:
- **Modern and Professional**: Clean, responsive design that works on all devices
- **Easy to Maintain**: Built with Jekyll for simple content management
- **Academic-Focused**: Optimized for showcasing research and academic achievements
- **SEO-Friendly**: Built-in search engine optimization features

## Features

- 📚 **Research Section**: Detailed information about my research interests and projects
- 📄 **Publications**: Complete list of journal articles, conference papers, and preprints
- 🎓 **Teaching**: Information about courses taught and teaching philosophy
- 👨‍💼 **CV**: Comprehensive curriculum vitae
- 📞 **Contact**: Multiple ways to get in touch
- 🔗 **Social Links**: Integration with academic and professional profiles

## Technology Stack

- **Jekyll**: Static site generator
- **GitHub Pages**: Free hosting
- **Markdown**: Easy content creation
- **HTML/CSS**: Custom styling and layout
- **Font Awesome**: Icons
- **Academic Icons**: Specialized academic icons

## Local Development

To run this website locally:

1. **Install Ruby and Jekyll**:
   ```bash
   gem install jekyll bundler
   ```

2. **Install dependencies**:
   ```bash
   bundle install
   ```

3. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser** and go to `http://localhost:4000`

## Customization

### Personal Information
Update the following files with your information:
- `_config.yml`: Site title, description, social links, navigation
- `index.md`: Homepage content
- `about.md`: Personal information and background
- `research.md`: Research interests and projects
- `publications.md`: Your publications
- `teaching.md`: Teaching experience and philosophy
- `cv.md`: Your curriculum vitae
- `contact.md`: Contact information

### Styling
The website uses custom CSS in `_layouts/default.html`. You can modify:
- Colors in the `:root` CSS variables
- Fonts and typography
- Layout and spacing
- Responsive design breakpoints

### Content Structure
- Add new pages by creating `.md` files in the root directory
- Use the `default` layout for most pages
- Add social links in `_config.yml`
- Update navigation in `_config.yml`

## Deployment

This website is automatically deployed to GitHub Pages when you push to the `main` branch. No additional configuration is needed.

## License

This website template is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Icons by [Font Awesome](https://fontawesome.com/) and [Academic Icons](https://jpswalsh.github.io/academicons/)
- Inspired by modern academic website designs

---

*Last updated: January 2024*