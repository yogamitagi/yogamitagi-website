# Yoga mit Agi Website

A static website for Yoga mit Agi, built with Hugo.

## Technical Stack

- **Hugo** (v0.141.0 or higher, max v0.148.2) - Static site generator with extended mode enabled
- **Blowfish Theme** - Modern, responsive Hugo theme for the site design
- **Node.js/npm** - For build and asset management
- **CSS/JavaScript** - Frontend styling and interactivity
- **Markdown** - Content files for pages and blog posts
- **TOML** - Configuration files

## How to Run Locally

### Prerequisites

- **Hugo Extended** (v0.141.0 - v0.148.2) installed on your system
- **Git** for version control
- (Optional) **Node.js** if you need to build or manage dependencies

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd yogamitagi-website
   ```

2. **Install Hugo**
   - Download and install the extended version of Hugo from [hugo.io](https://gohugo.io/installation/)
   - Verify the installation:
     ```bash
     hugo version
     ```

3. **Start the development server**
   ```bash
   hugo server
   ```
   The site will be available at `http://localhost:1313`

4. **Build for production**
   ```bash
   hugo
   ```
   This generates the static site in the `public/` directory

### Project Structure

- `content/` - Markdown files for pages and content
- `themes/blowfish/` - Hugo theme files
- `config/_default/` - Configuration files (Hugo, languages, menus, etc.)
- `static/` - Static assets (images, etc.)
- `public/` - Generated static site (build output)
- `resources/` - Hugo resource cache