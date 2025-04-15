# Hackboat 2025

This is the website for Hackboat 2025 - an infosec unconference on the high seas. Join us for a one-day pirate-themed infosec unconference on a boat in Portland, OR on June 6th, 2025.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (version 2.5.0 or higher recommended)
- [RubyGems](https://rubygems.org/pages/download)
- [Bundler](https://bundler.io/)

## Installation

1. Clone this repository to your local machine

   ```
   git clone <repository-url>
   cd hackboat2025
   ```

2. Install the required gems
   ```
   bundle install
   ```

## Running Locally

To start the site locally:

```bash
bundle exec jekyll serve
```

This will start a local server, typically at `http://localhost:4000`. You can view the site by opening this URL in your web browser.

If you want to see draft posts and make the server watch for changes:

```bash
bundle exec jekyll serve --drafts --livereload
```

## Project Structure

- `_config.yml`: Configuration settings for the Jekyll site
- `_posts/`: Blog posts in Markdown format
- `_layouts/`: HTML templates for different page types
- `_includes/`: Reusable HTML components
- `_sass/`: SCSS stylesheets
- `assets/`: Static files like images, CSS, and JavaScript
- `index.markdown`: The main landing page

## Event Details

- **Date**: June 6th, 2025
- **Location**: 110 SE Caruthers St, Portland, Oregon, 97214 (by OMSI)
- **Contact**: hackboat@bsidespdx.org or (503) 560 3551
- **Twitter**: [@hackboatpdx](https://twitter.com/hackboatpdx)

## Making Changes

After making changes to the site:

1. Test your changes locally using the instructions above
2. Commit your changes to the repository
3. Push to the main branch (or create a pull request)

## Deployment

This site is built with Jekyll, which generates static HTML files. The deployment process will depend on your hosting provider.

For more information on using Jekyll, refer to the [Jekyll documentation](https://jekyllrb.com/docs/).
