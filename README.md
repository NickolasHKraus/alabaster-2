# Alabaster 2

A simple documentation theme for Hugo. Alabaster 2 is a port of [Sphinx](http://www.sphinx-doc.org/en/master/) to [Hugo](https://gohugo.io/), JavaScript-free, and fully open-source.

## Quick Start

Installation:

```bash
git clone git@github.com:NickolasHKraus/alabaster-2.git themes/alabaster-2
```

> This theme uses the latest development version of Hugo. Therefore, it doesn't work with the official releases. Look [here](https://github.com/spf13/hugo#build-and-install-the-binaries-from-source-advanced-install) if you want to know how to build Hugo from source.

Next, take a look at the `exampleSite` folder. This directory contains an example `config.toml` and the `content` directory for the demo website. It serves as an example setup for your documentation.

Copy at least the `config.toml` in the root directory of your website. Overwrite the existing `config.toml` file if necessary.

Hugo includes a development server, so you can view your changes as you go - very handy. Spin it up with the following command:

```bash
hugo server -D
```

**Note**: Include the `-D` flag to include content marked as draft.

Now you can go to [localhost:1313](http://localhost:1313) and the Alabaster 2 theme should be visible.

For detailed installation instructions visit the [demo website](https://alabaster-2.hugo-themes.io).

## Acknowledgements

Last, but not least, I want to give a big shout-out to [Jeff Forcier](https://github.com/bitprophet), [Kenneth Reitz](https://github.com/kennethreitz), and [Armin Ronacher](https://github.com/mitsuhiko). Their work and modifications on the original code base made this port possible.

Furthermore, thanks to [Steve Francia](https://gihub.com/spf13) for creating Hugo and the [awesome community](https://github.com/spf13/hugo/graphs/contributors) around the project.

## License

This theme is released under the BSD license. Read the [license](https://github.com/NickolasHKraus/alabaster-2/blob/master/LICENSE) for more information.
