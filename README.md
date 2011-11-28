# To install rubygem dependencies

Run the command:

    bundle install

This should install each of the ruby gems listed in Gemfile.

# To run this static site locally

The [serve][] gem lets you quickly spin up a local web server. This command will serve the contents of the `public/` directory from [http://localhost:4000](http://localhost:4000):

    bundle exec serve public

# To deploy this static site to [Heroku][]

Replace 'rack-static-starter' with the name you want to use for your site:

    heroku create rack-static-starter
    git push heroku master

Now open up [http://rack-static-starter.heroku.com][starter] in your browser.

*Presto!*

[Heroku]: http://heroku.com
[starter]: http://rack-static-starter.heroku.com
[rack]: http://rubygems.org/gems/rack
[serve]: http://rubygems.org/gems/serve