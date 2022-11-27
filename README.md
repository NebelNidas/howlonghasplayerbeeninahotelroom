# How long has Player been in a hotel room?
This repository contains the source code and content for [https://howlonghasplayerbeeninahotelroom.today/](https://howlonghasplayerbeeninahotelroom.today/). Jekyll is used as the static site generator. Contributions are welcome, but keep in mind that this is just a silly side project. 😉


## License
The code is licensed as MIT as detailed in `LICENSE`, unless otherwise indicated.

The contents of this website, unless otherwise indicated, are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).


## Develop and Build

### Prerequisites
- [Ruby 2.7 *with* DevKit](https://rubyinstaller.org/downloads/)


### Install Jekyll
Ensure that the Ruby dependencies are installed locally, not system-wide:

```
bundle config set --local path 'vendor/bundle'
bundle install
```

From then on, run Jekyll using `bundle exec jekyll <args>` to use the local version.


### Build Site
```
bundle exec jekyll build
```

This will build the site into the `_site` folder.


### Developing the Site
To run a local development server to more comfortably edit the site, run:

```
bundle exec jekyll serve
```

Then open http://localhost:4000 in your browser of choice. The site should update automatically as you change the files.

