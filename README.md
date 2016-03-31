# Middleman Base

This is my go-to scaffolding for frontend prototyping of apps and websites.

**Features:**

* [Middleman](http://middlemanapp.com) for static site generation
  * Including [live reloading](https://github.com/middleman/middleman-livereload), [Sprockets](https://github.com/rails/sprockets) for asset generation and [automatic deploys to FTP](https://github.com/middleman-contrib/middleman-deploy)
* Twitter Bootstrap, 3.3.x - [Sass version](https://github.com/twbs/bootstrap-sass)
* [Pow](http://pow.cx) configuration for easy local server (no manually running `middleman server`)
* [HTML5 Boilerplate](https://html5boilerplate.com/) ready to go
  * (Including Modernizr, Respond.js and jQuery via global CDN)

**Important notes**

- The project uses Middleman 3.3.x
- It should/will be updated to use Middleman 4.x, but it is not currently planned

## Getting Started

1. Install **middleman-base** as a Middleman template.

    ```bash
    git clone https://github.com/cabgfx/middleman-base.git ~/.middleman/middleman-base

2.  Initialize a new Middleman project with your new **middleman-base** template (that you've just installed in Step 1)

    ```bash
    middleman init project_name --template=middleman-base
    cd project_name
    ```

3. Install required gems: `bundle install`

4. Link a pow: `powder link`

5. Open `http://project_name.dev` and get cranking!


### Customize and/or clean up

When you've have successfully set up your new project with this template, you'll likely want to remove some shit you don't need, and add shit you do need. Other than that, everything should be good to go.

Get shit done. 🚀
