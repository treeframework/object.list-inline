# List-inline

The List-inline object simply displays a list as one horizontal row.

## Dependencies

The List-inline object depend on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the List-inline object using Bower, you will get these
dependencies at the same time. If not using Bower, please be sure to install and
`@import` these dependencies in the relevant way.

## Installation

The recommended installation method is Bower, but you can install the
List-inline module via npm, Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-list-inline --save
```

### Install using npm:

```sh
$ npm install tree-list-inline --save
```

Once installed, `@import` into your project in its Objects layer:

```scss
@import "bower_components/tree-list-inline/object.list-inline";
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.list-inline.git
```

Once installed, `@import` into your project in its Objects layer:

```scss
@import "object.list-inline/object.list-inline";
```

### Install via file download

The least recommended option for installation is to simply download
`_object.list-inline.scss` into your project and `@import` it into your project
in its Objects layer.

## Usage

Basic usage of the List-inline object uses thr required classes:

```html
<ul class="list-inline">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

The only valid children of the `.list-inline` node are `li`s.

## Options

Other, optional classes can supplement the required base classes:

* `.list-inline--delimeter`: add character to delimit list items.

For example:

```html
<ul class="list-inline  list-inline--delimited">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

If you wish to completely remove the whitespace between items, omit the closing
`</li>` tag:

```html
<ul class="list-inline">
    <li>Foo
    <li>Bar
    <li>Baz
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
