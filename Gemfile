source "https://rubygems.org"

# Совместимая с GitHub Pages версия Jekyll и плагинов
gem "github-pages", group: :jekyll_plugins

# Для удалённой темы pages-themes/cayman
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-relative-links"
  gem "jekyll-seo-tag"
  gem "jekyll-feed"
end

# Windows и JRuby не имеют zoneinfo — добавляем пакет
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster для просмотра локально
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Kramdown как процессор Markdown
gem "kramdown-parser-gfm"

# HTTP Parser для Ruby 3
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# webrick больше не входит в Ruby 3+ по умолчанию
gem "webrick", "~> 1.7"
