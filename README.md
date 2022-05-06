# The current state of the project (5/6/22)

The sitemap.xml file has been added and everything is currently responsive on the site. All FAQ questions have been added from the documentation1.1 excel spreadsheet and have been assigned categories based on what was provided on that document. You will notice in the post folder that there are subfolders that were created based on what that excel doc actually called categories. Categories for each page have also been assigned accordingly. I am pretty sure Jekyll will not recognize the markdown files as posts unless they have the dates formatted as seen in those files, but there might be a workaround for that. The index.html file that you see in the root directory was largely used for testing and will likely need modification or removal. There are not any index files for the other three sections as we never settled on a design for them or determined if they would be necessary. There are three layouts provided in the layout folder for prospective, new, and current students. Everything has been written in HTML/CSS and there is a bit of JavaScript as well. I was unable to figure out how to properly use categories, but I know there is a way using Jekyll front matter and liquid templating language. I trust that experienced developers could figure this out in no time. The buttons for CS/CY are also not working as intended, but it looks like the Angular demo had that solved so I imagine the same or similar code could be applied here. Best of luck! Wiley

# askrowdy-jekyll

Welcome to your new Jekyll theme! In this directory, you'll find the files you need to be able to package up your theme into a gem. Put your layouts in `_layouts`, your includes in `_includes`, your sass files in `_sass` and any other assets in `assets`.

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

TODO: Delete this and the text above, and describe your gem


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "askrowdy-jekyll"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: askrowdy-jekyll
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install askrowdy-jekyll

## Usage

TODO: Write usage instructions here. Describe your available layouts, includes, sass and/or assets.



## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `askrowdy-jekyll.gemspec` accordingly.

