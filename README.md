# Tabs

The `tabs` object is a simple abstraction for force a series of elements
(usually a list) into an equal-width, tab-like format.

## Dependencies

The `tabs` object depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `tabs` object using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

You can install `tabs` object via Bower, npm, Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-tabs --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-tabs/object.tabs";
```

### Install using npm:

```sh
$ npm install tree-tabs --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.tabs.git
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "object.tabs/object.tabs";
```

### Install via file download

The least recommended option for installation is to simply download
`_object.tabs.scss` into your project and `@import` it into your project in its
Object layer.

## Usage

Basic usage of the `tabs` object uses the required classes:

```html
<ul class="o-tabs">
    <li class="o-tabs__item">
        <a class="o-tabs__link" href="#">Foo</a>
    </li>
    <li class="o-tabs__item">
        <a class="o-tabs__link" href="#">Bar</a>
    </li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
