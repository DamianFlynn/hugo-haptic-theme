# Haptic Theme | Hugo

> **Haptic** is a **modern**, **elegant**, and **powerful** blog theme for [Hugo](https://gohugo.io/) with a focus on readability and user experience.

It is inspired by the [DoIt Theme](https://github.com/HEIGE-PCloud/DoIt) but has been completely redesigned with a new layout, custom CSS, and enhanced user interactions. The Haptic theme offers a fresh perspective while maintaining the powerful features that modern blogs require.

## Getting Started

### As a Hugo Module (recommended)

1. Initialize Hugo modules if you haven't already:
   ```bash
   hugo mod init github.com/yourusername/yoursite
   ```

2. Add the theme to your site's configuration (config.toml):
   ```toml
   [module]
     [[module.imports]]
       path = "github.com/damianflynn/hugo-haptic-theme"
   ```

3. Update your modules:
   ```bash
   hugo mod get -u
   ```

### Manual Installation

1. Add this repo as a submodule of your site directory:
   ```bash
   git submodule add https://github.com/damianflynn/hugo-haptic-theme.git themes/Haptic
   ```

2. Update the submodule when needed:
   ```bash
   git submodule update --remote --merge
   ```

3. Set the theme in your site configuration:
   ```diff
   - theme = "YourOldTheme"
   + theme = "Haptic"
   ```

## Features

### Performance and SEO

* **Optimized performance**: Built with modern web technologies for speed
* **SEO-friendly architecture** with proper metadata and structured data
* **Analytics integration**: Support for Google Analytics, Fathom Analytics, Plausible, and more
* **Robust SEO schema** based on JSON-LD for better search engine visibility
* **Fast loading times** with minified resources and optional image optimization

### Visual Design & Layout

* **Clean, minimalist design** with careful typography and spacing
* **Responsive layout** that looks excellent on all devices from mobile to wide desktop screens
* **Light/Dark mode** with smooth transitions and system preference detection
* **Reading-optimized typography** for better content consumption
* **Custom animations** that enhance the user experience without sacrificing performance
* **Accessible design** following WCAG guidelines

### Content Features

* **Article-focused layout** that prioritizes your writing
* **Advanced table of contents** that expands automatically as you scroll
* **Code syntax highlighting** with support for numerous languages
* **One-click code copying** for better developer experience
* **Image galleries** with lightbox support
* **Interactive data visualization** capabilities via shortcodes
* **Mathematical formula** support through KaTeX
* **Diagram creation** via Mermaid integration
* **Custom shortcodes** for advanced content creation

### Social Integration

* **Flexible author profiles** with Gravatar support and local avatars
* **Extensive social sharing options** with support for all major platforms
* **Multiple commenting systems** supported:
  * Disqus, Gitalk, Utterances, giscus, and more
* **Webmentions support** for IndieWeb integration

### Technical Capabilities

* **Hugo module support** for modern development workflow
* **Custom CSS framework** built for performance and flexibility
* **Tailwind CSS integration** for streamlined styling
* **Alpine.js for interactions** without the overhead of heavy JavaScript frameworks
* **Built-in table of contents** with smooth scrolling functionality
* **Multilingual ready** with i18n support
* **PWA support** for installation on mobile devices

## Why Choose Haptic?

Haptic stands out with its:

* **Focus on reading experience**: Typography and spacing designed specifically for content consumption
* **Modern aesthetics**: Clean, minimalist design that lets your content shine
* **Performance first approach**: Optimized for speed without sacrificing features
* **Developer-friendly**: Easy to customize and extend
* **Accessibility**: Built with inclusivity in mind

If you value clean design, excellent reading experience, and modern web technologies without unnecessary complexity, Haptic is the perfect theme for your Hugo site.

## Documentation

Documentation is currently under development.

For local documentation:
```bash
hugo server --source=exampleSite
```

## Multilingual Support

Haptic has basic multilingual support with:

* English

Additional languages can be added through i18n files.

## License

Haptic is licensed under the **MIT** license. See the [LICENSE file](LICENSE) for details.

## Credits

This theme would not be possible without inspiration from the [DoIt theme](https://github.com/HEIGE-PCloud/DoIt) and the incredible Hugo community.

Special thanks to all the open-source projects that make Haptic possible:
* [Tailwind CSS](https://tailwindcss.com/)
* [Alpine.js](https://alpinejs.dev/)
* [KaTeX](https://katex.org/) for math rendering
* [Mermaid](https://mermaid-js.github.io/) for diagrams
* [lightgallery.js](https://sachinchoolur.github.io/lightgallery.js/) for image galleries

## Author

[Damian Flynn](https://github.com/damianflynn)
