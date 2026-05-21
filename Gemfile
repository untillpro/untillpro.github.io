source "https://rubygems.org"

# Jekyll — минимально необходимый набор для локальной сборки.
gem "jekyll", "~> 4.3"

# В Ruby 3.0+ webrick исключён из стандартной библиотеки — нужен явно для
# `jekyll serve`.
gem "webrick", "~> 1.8"

# Windows не поставляет zoneinfo по умолчанию.
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
