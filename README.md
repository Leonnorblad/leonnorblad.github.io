# Leonard Norblad - Personal Website

This is my personal website built with Jekyll using the [resume theme](https://github.com/sproogen/resume-theme).

## 🚀 Quick Start - Local Development

### Prerequisites

Make sure you have the following installed on your system:

- **Ruby** (version 2.6 or higher)
- **Bundler** (Ruby gem manager)

#### Check if you have Ruby installed:
```bash
ruby --version
```

#### Install Bundler if you don't have it:
```bash
gem install bundler
```

### Setup Instructions

1. **Clone the repository** (if you haven't already):
```bash
git clone <your-repo-url>
cd leonnorblad.github.io
```

2. **Install dependencies**:
```bash
bundle install
```

3. **Start the development server**:
```bash
bundle exec jekyll serve --livereload
```

4. **Open your browser** and navigate to:
   - **Local**: http://localhost:4000
   - **Network**: http://127.0.0.1:4000

### Development Options

#### Option 1: LiveReload (Recommended)
Automatically refreshes your browser when files change:
```bash
bundle exec jekyll serve --livereload
```

#### Option 2: Watch Mode
Rebuilds on file changes, but requires manual browser refresh:
```bash
bundle exec jekyll serve --watch
```

#### Option 3: Incremental Builds
Faster rebuilds for large sites:
```bash
bundle exec jekyll serve --livereload --incremental
```

#### Option 4: Verbose Output
For debugging issues:
```bash
bundle exec jekyll serve --livereload --verbose
```

### Troubleshooting LiveReload

If LiveReload isn't working automatically:

1. **Clear browser cache**: Press `Cmd+Shift+R` (Mac) or `Ctrl+Shift+R` (Windows/Linux)
2. **Try a different browser**: Some browser extensions can interfere
3. **Check browser console**: Open Developer Tools (F12) for any JavaScript errors
4. **Manual refresh**: Use `--watch` instead and manually refresh the browser

### File Structure

```
leonnorblad.github.io/
├── _config.yml          # Main configuration (personal info, projects, etc.)
├── index.md             # Home page content
├── assets/
│   └── main.scss        # Custom styling
├── images/              # Profile pictures and other images
├── Gemfile              # Ruby dependencies
└── _site/               # Generated site (don't edit directly)
```

### Making Changes

#### Personal Information
Edit `_config.yml` to update:
- Name, title, email
- Social media links
- About section content
- Projects and experience
- Education details

#### Content
- **Home page**: Edit `index.md`
- **Styling**: Edit `assets/main.scss`
- **Images**: Add files to `images/` directory

#### Important Notes
- Changes to `_config.yml` may require a server restart
- The server will automatically rebuild when you save files
- Use `Ctrl+C` in the terminal to stop the development server

### Deployment

This site is configured for GitHub Pages. Simply push your changes to the main branch and GitHub will automatically build and deploy your site.

### Theme Information

This site uses the [resume theme](https://github.com/sproogen/resume-theme) by sproogen, which provides:
- Professional resume layout
- Dark/light mode support
- Responsive design
- Easy customization through `_config.yml`