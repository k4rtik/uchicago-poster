[![Overleaf Template](https://img.shields.io/badge/Overleaf-Template-success?logo=overleaf)](https://www.overleaf.com/latex/templates/unofficial-poster-template-for-uchicago-computer-science/kbbmbdxwbypb)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/k4rtik/uchicago-poster)](https://github.com/k4rtik/uchicago-poster/releases)


# Unofficial Poster Template for UChicago Computer Science

A fork of [Gemini](https://github.com/anishathalye/gemini). Also available on [Overleaf](https://www.overleaf.com/latex/templates/unofficial-poster-template-for-uchicago-computer-science/kbbmbdxwbypb).

## Dependencies

* A TeX installation that includes [LuaTeX]
  * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemeuchicago.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## FAQ

See the [gemini FAQ] for answers to frequently asked questions.

[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[gemini FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
