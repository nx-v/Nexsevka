# Nexsevka

![Nexsevka Cover](assets/SocialPreview.png)

The goal of this project is to configure Iosevka based on my personal style. The name "Nexsevka" is a combination of my name, Nexo, and Iosevka.

This font is my primary programming font, which is shown on my GitHub pages, and my programming language [Ruko](https://github.com/nx-v/ruko).

It uses Iosevka's build options to mimic the look and feel of Berkeley Mono, while incorporating my own preferences for character variants and metrics.

This repository uses GitHub Actions to automatically build the font files whenever the configuration is updated.

A separate branch, `propo`, contains a version of Nexsevka with quasi-proportional spacing, which I swap for writing documentation and prose.

---

## Installation

Since this uses the `dev` build of Iosevka, you would need to have a copy of the Iosevka `dev` source files to build it locally, then copy the `private-build-plans.toml` file and the [ttfautohint](https://freetype.org/ttfautohint/) binary into the root directory.

However, you can also download pre-built font files directly from this page, by going to `Code` > `Download ZIP`.

### Configuration Choices

This configuration uses specific character variants and custom metrics to closely match the look and feel of Berkeley Mono.

The font's vertical proportions, letter spacing, parenthesis size and arc ratio have been adjusted based on Ioskeley Mono, which gives the letterforms a squarer and more geometric appearance, while still retaining the overall design of Iosevka.

Many glyphs also have unconventional serifs, and unique shapes that give it a distinct personality while maintaining readability.

---

### License & Credits

**Credits**: Nexsevka is a custom configuration of the Iosevka typeface. All credit for the original design and build system goes to Belleve Invis and the Iosevka contributors.

Because this is a derivative of Iosevka, it is licensed under the same **SIL Open Font License 1.1**. See the `LICENSE` file for full details.
