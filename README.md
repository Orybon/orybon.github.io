local run :

brew install ruby 
sudo gem install bundler
gem install --user-install bundler jekyll

sudo gem install http_parser.rb -v '0.6.0' --source 'https://rubygems.org/'

bundle install

bundle exec jekyll serve

open http://localhost:4000