# Hugo Overflow Identity

[![Example Site](https://api.netlify.com/api/v1/badges/0f92221c-7181-489d-8309-fcccc0a9fac7/deploy-status)](https://app.netlify.com/sites/hugo-overflow-identity/deploys)

This is a Hugo migration of the [Overflow Identity](https://github.com/setu4993/overflow-identity) theme, which is a mashup of two [HTML5UP](https://html5up.net) themes (unsurprisingly HTML5UP's [Overflow](https://web.archive.org/web/20210223162921/https://html5up.net/overflow) and [Identity](https://web.archive.org/web/20201027205452/https://html5up.net/identity)). It is a simple, single page theme that I originally mashed up for my website.

An example site hosted with Netlify is in [this repo](https://github.com/setu4993/hugo-overflow-identity-example).

## Usgae

The site is configured in 2 parts. Take a look at the file under `exampleSite` for an example.

### config.toml

The base configuration of the site, header and the footer are set in `config.toml`.

Footer uses [Font Awesome icons](https://fontawesome.com/) for the social profiles. Find the relevant icon code on the [FontAwesome gallery](https://fontawesome.com/v5.15/icons?d=gallery&p=1&m=free).

### Content

The content is configured in _sections_ that are expected to reside as markdown files in the `content` directory.

The frontmatter contains 4 variables that can be configured:

```yaml
title: "Section Title"
anchor: "section-anchor-link"
subheading: "Short description or subheading for the section that appears immediately below the section title."
index: 0 # Sections are sorted in increasing order of the index on the homepage.
```
