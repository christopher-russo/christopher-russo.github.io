Original site design by amitmerchant1990, forked from <https://github.com/amitmerchant1990/reverie>.

## Instructions for installing Ruby and Jekyll dependencies

Using Homebrew, install Ruby. This installation of Ruby will be different from the system version of Ruby, the latter of which should not be changed by the user.

``` 
brew install ruby
```

Once installed, update the system PATH variable. This will allow Ruby commands to automatically reference the user installation of Ruby, not the system installation.

```
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

Next, install Bundler to help manage Ruby gems.

```
gem install bundler
```

## Instructions for GitHub Pages setup

Fork the template repo and rename <christopher-russo.gitub.io>. Git clone onto your local machine. 

Create bundle files in this directory.

```
bundle init
```

Modify the resulting Gemfile to read

```
source "https://rubygems.org"

gem "jekyll", "VERSION1"
gem "github-pages", "~> VERSION2", group: :jekyll_plugins
```

where VERSION1 and VERSION2 are the current dependency versions for GitHub Pages. Install those gems using

```
bundle install
```

To locally serve the website, run

```
bundle exec jekyll serve
```

Make changes locally and then push onto the GitHub master branch.

## Resources

**General Instructions**

"Creating a GitHub Pages site with Jeykll" <https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll>

**Ruby and Bundler Docs**

"Ruby 101" <https://jekyllrb.com/docs/ruby-101/#gemfile>

"Bundler: Getting Started" <https://bundler.io>

**If you receive an error when trying to gem install bundler, then you may be mistakenly calling the system Ruby.**

"You don't have write permissions for the /Library/Ruby/Gems/2.3.0 directory" <https://stackoverflow.com/questions/51664716/you-dont-have-write-permissions-for-the-library-ruby-gems-2-3-0-directory>

**GitHub Dependency Versions** These are important for using versions of jeykll which will work will GitHub.

"Dependency versions" <https://pages.github.com/versions/>

