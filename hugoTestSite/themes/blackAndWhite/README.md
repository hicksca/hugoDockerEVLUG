# blackAndWhite

blackAndWhite is a small black and white theme for [Hugo](https://github.com/spf13/hugo) (a fast and modern static website engine).

*blackAndWhite is a fork from the Liquorice theme by [Markus Eliasson](https://github.com/eliasson) I've made a few changes for different behavior.

### Dependencies

blackAndWhite needs at least version 0.12 of Hugo, as it uses features such as partials.


### Partials

There are a few partials that is of great interest to override


#### author

The author partial is added at the end of each single page (such as blog posts) and by default only prints the name of the author registered in the site params, e.g. in your `config.toml`

    [params]
        author = "Kalevala"

In order to override and have your own markup appended to single pages, just create the file `layouts/partials/author.html` and roll your own.


### Shortcodes

blackAndWhite comes with these additional shortcodes:


#### gist

Include a Github gist using their JavaScript include.

    {{% gist a4aa0b7427723af60b47 %}}

Where the first parameter is the gist id.


### Building

There is not much to build, but the theme CSS is minified using the node tool [clean-css](https://github.com/GoalSmashers/clean-css).

    cleancss -o static/css/liquorice.min.css static/css/liquorice.css

*Any change in styles needs to result in a minification!*


# License

blackAndWhite is released under the MIT license, see [LICENSE](https://github.com/hicksca/blackAndWhite/blob/master/LICENSE) for details.
