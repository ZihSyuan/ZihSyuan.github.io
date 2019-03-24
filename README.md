## Self practice project
A simple practice for static website using **Jekyll**

## Developing

We use `jekyll` to do the templating and generating of static website files.

### Install `jekyll`

Follow this guide to install `jekyll` on your Mac:
https://jekyllrb.com/docs/installation/macos/

```
xcode-select --install

sudo gem install --user-install bundler jekyll
```

### Run `jekyll` dev server

```
bundle install
bundle exec jekyll serve
```

Then you can see the local instance at `http://localhost:4000`.

**Note:**
If you change `_config.yml`, due to technical reasons you will need to restart the process again to see the update.
All other file changes should be hot-reloaded.

## Credit
The material used in this project
- Template - [QBOOTSTRAP](http://qbootstrap.com/)
- Image - [Unsplash](http://unsplash.com/)
- Image - [PNGtree](https://zh.pngtree.com)
