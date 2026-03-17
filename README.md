# wramdemark.se

This is the source code for my personal website, hosted on GitHub Pages and built using Jekyll.

## 🚀 Local Development

Since this project uses Jekyll and Ruby, follow these steps to run the site locally on macOS (optimized for Apple Silicon/M2).

### Prerequisites
- **Ruby 3.3.0+** (Managed via `rbenv`)
- **Bundler** (Ruby gem manager)

### 1. Setup Environment
If you haven't configured your Mac yet, ensure `rbenv` is initialized in your shell and install the dependencies:

```bash
# Install the specific Ruby version
rbenv install 3.3.0
rbenv global 3.3.0

# Install Bundler
gem install bundler

# Install project dependencies
bundle install
```

### 2. Run the Site
To start the site for local development

```bash
bundle exec jekyll serve --livereload
```
