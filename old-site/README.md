## Start here:

<https://linguistics.github.io/>


## Disclaimer

This repository and all others under the GitHub [@linguistics](https://github.com/linguistics) organization are not the official representation of the University of Texas at Austin, nor the College of Liberal Arts, nor the Linguistics Department, nor do they pretend to be.

<!-- I merely found the standard documentation lacking and the Confluence wiki unusable, and wanted to help any others who might be likewise confused while navigating UT's electronic presence. Chris -->


## Development

Use `gem` to install `github-pages` and its dependencies, which includes the `jekyll` command:

    ARCHFLAGS="-arch x86_64" gem install github-pages

The `ARCHFLAGS` environment variable may not be necessary, or correct, on your platform.
On macOS 10.11 El Capitan, it is.

When working on the site, run `jekyll` from this directory to preview your changes:

    jekyll serve --watch

Go to [localhost:4000](http://127.0.0.1:4000) to view.
