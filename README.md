# expz.github.io

Academic homepage generated using Jekyll and based on the [academicpages template](https://github.com/academicpages/academicpages.github.io).

## Initial Setup

It requires Ruby 2.5. (Check [GitHub](https://pages.github.com/versions/) for up-to-date required versions). On Ubuntu, follow the [directions](https://rvm.io/rvm/install) to install `rvm`. Then run
```
echo 'if test -f ~/.rvm/scripts/rvm; then [ "$(type -t rvm)" = "function" ] || source ~/.rvm/scripts/rvm; fi' >> ~/.bashrc
source ~/.bashrc
rvm list known
rvm install 2.5
rvm alias create default 2.5
rvm use 2.5
gem install bundler
```
Then from the root directory of this repository, run `bundle install`. To test the site locally, run `bundle exec jekyll serve`, and navigate to [http://localhost:4000/](http://localhost:4000).
