# walkingtrailproperties.github.io
Walking Trail Properties - Static Webpage 

# Setup

Ubuntu 20.04 LTS

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install -y build-essential make libxml2 zlib1g zlib1g-dev
sudo apt-get install -y ruby ruby-dev
sudo gem install jekyll bundler
sudo gem update --system
sudo bundle update --bundler
sudo gem update
sudo gem install jekyll-feed
sudo gem install jekyll-avatar
sudo gem install jekyll-sitemap
sudo gem install jekyll-paginate
sudo gem install jekyll-seo-tag
sudo gem install jekyll-gist
sudo gem install html-pipeline

cd /mnt/c/Users/tim/Documents/walkingtrailproperties.github.io/
sudo bundle install
sudo bundle exec jekyll serve --trace -P 4001
http://127.0.0.1:4001/
```