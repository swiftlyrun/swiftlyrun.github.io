# swiftly.run

Swiftly.run is a collection of commands for a variety of programs.

[swiftly.run](https://www.swiftly.run)

## Examples
Examples should be useful to those who are coming back to a program after a while and are considered good to know when starting out with a program.

## Contributing
Contributing is easy. Pages are markdown files following a very simple layout. Have a look at the examples in this repository to see how easy it is.

### Page layout
The mardown contents for `example.md` would be:

``````markdown
---
layout: page
title: example
docs: https://example.org/docs
---
Use Example to modify file `somefile`
```bash
example -m somefile
```
``````

#### Page variables
The variables `layout`, `title`, and `docs` are mandatory. Note the `---` around these variables.

| var      | description                                                  |
| :---     | :---                                                         |
| `layout` | The page layout type, should always be `page`            |
| `title`  | The title, should match the *filename* part of `filename.md` |
| `docs`   | URL to (when available, official) program documentation      |

#### Example formatting
Examples follow a simple structure:
1. Description
2. Example

The *description* is a simple line that explains what the example does.

The *example* should be the example. Examples should be put in *code blocks* (`````` ```example goes here``` ``````). Whenever possible, the example language should be included to enable syntax highlighting.

For an example, look at the example above or take a peek into one of the `.md` files in this repository (excluding `index.md`, which is the homepage).

### index.md
When adding a new page, it should be manualy added to `index.md`.

If you are somewhat familiar with markdown, the layout of `syntax.md` should speak for itself.
