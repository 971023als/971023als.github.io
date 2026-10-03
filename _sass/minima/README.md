# minima

This directory holds a customized copy of the Minima Jekyll theme's Sass files, used to style 971023als's security portfolio site (`971023als.github.io`). The site's `_config.yml` loads the theme via the `github-pages` gem, while these local `_sass/minima` partials provide the site-specific style overrides.

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "minima"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: minima
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install minima

## Usage

The Sass partials here (`_base.scss`, `_layout.scss`, `_syntax-highlighting.scss`, `_variables.scss`) are imported by `_sass/minima.scss` to style the site's layouts and pages. Edit these partials to change fonts, colors, spacing, and syntax highlighting for the portfolio site.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/minima. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `minima.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
