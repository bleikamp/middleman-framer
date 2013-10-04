# middleman-framer

A basic template for Framer applications with Middleman.

### Start a new Framer app

```
gem install middleman
git clone https://github.com/bleikamp/middleman-framer ~/.middleman/framer
middleman init my_new_framer_project --template=framer
cd my_new_framer_project
```

Run the application with `middleman server`

Start editing `my_new_framer_project/source/app.coffee` to start adding views.

### Why is this interesting?

[Middleman](http://middlemanapp.com/) gets you a ton of things for free that will help organize your Framer prototypes:

* Use CoffeeScript, Sass, ERB or anything else that you like that works with [Sprockets](https://github.com/sstephenson/sprockets) (which is almost everything).
* Break up JavaScript into small, reusable components and use `require` to include what you need in `app.coffee`
* Publish to GitHub Pages (or anywhere using Jekyll) and send your team URLs for mocks and prototypes.
