# Setup

This site runs on Jekyll, an opensource static site generating platform.

- Clone or download a zip of this project to your computer and navigate to the
  project directory in your terminal
- Download Ruby [here](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller)

- To ensure Ruby is installed, from the command line type:

  ```
  ruby -v
  ```

- Install the Jekyll bundler from the commandline:

  ```
  gem install jekyll bundler
  ```

  For more information about installing Jekyll, refer to the [Jekyll website](https://jekyllrb.com/docs/quickstart/)

    <br>

- Additionally, you may need to update the bundler using the following:

  ```
  bundle update --bundler
  ```

- Install Gem dependencies in the by running:
  ```
  bundle install
  ```
- To run the server in your local environment run:
  ```
  bundle exec jekyll server
  ```
- Go to http://localhost:4000/ in your browser
- To compile a static build run:
  ```
  bundle exec jekyll build
  ```

<br>

<br>

# General information

- Static website
- Optimised for efficient [PageSpeed Insights benchmarks](https://developers.google.com/speed/pagespeed/insights/?url=himatt.com) (still more to do in this space)
- No Jekyll plugin dependancies (previously used Bourbon and Neat, now uses CSS Grid and CSS Custom properties)
- Continuously deployed using Netlify

## Licenses

### Underlying source code

[GNU General Public License v3.0](LICENSE) (open source)

# Additional Information on the Theme

## Project List Image Resolution

Plist images (the thumbnails used on the Projects page) are at a ratio 600 x 450.
