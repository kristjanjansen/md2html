# Markdown to HTML converter

By Kristjan Jansen
http://kika.trip.ee

## About

md2html utility converts [Markdown](http://daringfireball.net/projects/markdown/syntax) files to HTML with some additional niceties:

* Print-optimized CSS stylesheet with separate title page
* URL autolinking
* Github-style linebreaks
* Extra typographic conversions such as -- 
* Easy image linking using ```img:filename ``` tag, just place your images to ```img/``` folder and they will be picked from there

## Requirements

* Ruby
* Redcarpet gem: https://github.com/tanoku/redcarpet

## Get started

```
gem install redcarpet
git clone https://github.com/kristjanjansen/md2html.git
cd md2html
ruby md2html README.md README.html (optional.erb)
```

## Thanks 

Nando Vieira and his awesome https://github.com/fnando/kitabu for inspiration