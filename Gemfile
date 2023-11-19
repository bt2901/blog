source "https://rubygems.org"
gem "jekyll", "~> 4.3.2"


# github v.3.0, latest build is 2.5.1
# in some versions, you'll need to use :git => "git@github.com:jekyll/minima.git"  instead of :github
# see: https://stackoverflow.com/questions/6648870/is-not-checked-out-bundle-install-does-not-fix-help
# see also: https://stackoverflow.com/questions/75912209/build-error-while-trying-to-publish-my-github-pages
# To use this theme, you have to switch to publishing your site using GitHub Actions
gem "minima", :github => 'jekyll/minima' 


group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
