# Stunning Presentations
Stunning presentations using Asciidoctor and RevealJS

## Prerequisites

Ruby installed - https://ruby-lang.org

Inside the project directory, run the following commands in the command line window

```
bundle config --local path .bundle/gems
```
And then,

```
bundle
```

After than to generate the presentation as an interactive html run the following command

```
bundle exec asciidoctor-revealjs presentation.adoc
```

If you want to upgrade the revealjs to the latest version future please delete the revealjs directory and do replacing the `<version>` with the latest version number

```
git clone -b <version> --depth 1 https://github.com/hakimel/reveal.js.git
```