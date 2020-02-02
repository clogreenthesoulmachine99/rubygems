# rubygems
Authenticate
echo ":github: Bearer GH_TOKEN" >> ~/.gem/credentials


gem build repository-name.gemspec


gem push --key github --host https://rubygems.pkg.github.com/clogreenthesoulmachine99 repository-name-1.0.0.gem
