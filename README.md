# Zen Framework


```
 _____
|__  /___ _ __
  / // _ \ '_ \
 / /|  __/ | | |
/____\___|_| |_|

```

> :warning: Projeto em Desenvolvimento :)

[See how it works](http://igorfelipee.github.io/zen-framework) -

## About

Zen Framework, as the name says, is a css framework tha uses a extremely simple semantic and provides a readable css code. It does not provides JS yet, but in futures updates it'll.

## Objective

The main objective is create a framework that anyone can underestand and use it in their projects. In this first version, it will only have a css document.
The css document is separated in usage parts.

E.g:

```
/* Global */
.wrapper{
  margin: 0 auto;
}
```

## Structure

```
zen-framework/
  ├── zen.scss
  ├── zen.css
  ├── zen.min.css
  │
  └── scss/
      ├── settings/
      │   ├── _variables.scss
      │   ├── _mixins.scss
      │   ├── _functions.scss
      │   └── _placeholders.scss
      │
      ├── globals/
      │   ├── _globals.scss
      │   ├── _grid.scss
      │   ├── _text-tags.scss
      │   └── _block-tags.scss
      │
      ├── helpers/
      │
      └── vendor/
```

## How to use

1. clone the repo: `git clone https://github.com/igorfelipee/zen-framework.git`
2. install the [sass lang](http://sass-lang.com/): `[sudo] gem install sass`
3. rum sass command: `sass zen.scss:zen.css --style expanded` or `sass zen.scss:zen.min.css --style compressed`
4. enjoy!

## Bugs and Sugestions

The Zen Framework is an **Open Source** project. Anyone can (and should) help us to improve it.

Report bugs or do suggestions using the [Issues/Project Forum](https://github.com/zen-team/zen-framework/issues)

## Contribute to the Project

To contribute, just click on the **Fork** button, create a *Branch*, improve the code and send it with a **Pull Request**.

More details about how to contribute and send Pull Requests in [GitHub Collaborating](https://help.github.com/categories/63/articles).

[How to colaborate to opensource projects on GitHub](http://www.youtube.com/watch?v=H3olaBo83As)

## License

InitSCSS is free under the [open-source MIT license](/LICENSE).
