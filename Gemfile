# source "https://rubygems.org"
 
# gem 'sass', "3.4.12"
# gem 'sass-globbing', ">= 1.1.0"
# gem 'compass', "1.0.3"
# gem 'breakpoint',  "2.5.0"
# gem 'singularitygs', "< 2.0.0"
# gem 'guard', "2.12.1"

source 'https://rubygems.org'

group :development do

  # Sass, Compass and extensions.
  gem 'sass'                    # Sass.
  gem 'sass-globbing'           # Import Sass files based on globbing pattern.
  gem 'compass'                 # Framework built on Sass.
  gem 'compass-validator'       # So you can `compass validate`.
  gem 'compass-normalize'       # Compass version of normalize.css.
  gem 'compass-rgbapng'         # Turns rgba() into .png's for backwards compatibility.
  gem 'susy'                    # Susy grid framework.
  gem 'singularitygs'           # Alternative to the Susy grid framework.
  gem 'toolkit'                 # Compass utility from the fabulous Snugug.
  gem 'breakpoint'              # Manages CSS media queries.
  gem 'oily_png'                # Faster Compass sprite generation.
  gem 'css_parser'              # Helps `compass stats` output statistics.
  gem 'terminal-notifier'

  # Guard
  gem 'guard'                   # Guard event handler.
  gem 'guard-compass'           # Compile on sass/scss change.
  gem 'guard-shell'             # Run shell commands.
  gem 'guard-livereload'        # Browser reload.
  gem 'yajl-ruby'               # Faster JSON with LiveReload in the browser.
  gem 'terminal-notifier-guard', '~> 1.6.1'

  # Dependency to prevent polling. Setup for multiple OS environments.
  # Optionally remove the lines not specific to your OS.
  # https://github.com/guard/guard#efficient-filesystem-handling
  gem 'rb-inotify', '~> 0.9', :require => false      # Linux
  gem 'rb-fsevent', :require => false                # Mac OSX
  gem 'rb-fchange', :require => false                # Windows

end