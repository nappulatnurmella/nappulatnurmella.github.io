Setup (once, or if ruby version changes):

```
gem install bundler
export PATH=~/.gem/ruby/2.6.0/bin:$PATH
bundle update --bundler
bundle install
```

Run the site locally:

```
export PATH=~/.gem/ruby/2.6.0/bin:$PATH
bundle exec jekyll serve
```

Open http://127.0.0.1:4000/ in browser.
