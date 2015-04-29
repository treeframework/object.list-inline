# List-inline

The `list-inline` object simply displays a list as one horizontal row.

## Dependencies

The `list-inline` object depend on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `list-inline` object using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install the `list-inline` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-list-inline --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-list-inline/object.list-inline";
```

### Install using npm:

```sh
$ npm install tree-list-inline --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.list-inline.scss` into your project and `@import` it into your project
in its Objects layer.

## Usage

Basic usage of the `list-inline` object uses the required classes:

```html
<ul class="o-list-inline">
    <li>...</li>
    <li>...</li>
    <li>...</li>
</ul>
```

The only valid children of the `.o-list-inline` node are `li`s.

## Options

Other, optional classes can supplement the required base classes:

* `.o-list-inline--delimeter`: add character to delimit list items.

For example:

```html
<ul class="o-list-inline  o-list-inline--delimited">
    <li>...</li>
    <li>...</li>
    <li>...</li>
</ul>
```

If you wish to completely remove the whitespace between items, omit the closing
`</li>` tag:

```html
<ul class="o-list-inline">
    <li>...
    <li>...
    <li>...
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
