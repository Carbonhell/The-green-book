# The green book
This repository contains the markdown files used to build the green book, a Dream Maker guide to help both newbies and veterans.

## Requirements
Building the book requires [rust] and cargo, which comes pre-packaged with rust. It also requires [mdBook], which can be installed through cargo:

[rust]: https://www.rust-lang.org/en-US/
[mdBook]: https://github.com/azerupi/mdBook

```bash
$ cargo install mdbook
```

## Building
To build the book, get a copy of this repository by downloading it in any way you want. Once done, open a command prompt and `cd` in the root of the repository folder, with the src folder and the book.toml, then type:

```bash
$ mdbook build
```
The output will be in the `book` subdirectory. To check it out, open the index.html file in your web browser.

## Contributing
The book can only succeed if knowledgeable people contribute! You can make new pages in the src folder, you can follow [this format] to see how to.
Any kind of page is well accepted, but generally you should restrict yourself to explaining general concepts, used by multiple codebases, instead of very specific things such as the functionality of an item.

Possible ideas:
1) Modularization
2) Appendix explaining basic git bash commands (Pretty much done [here] already, just move the page over, and fix any issue you find.
3) Any system shared by all codebases or most of them (such as the Master Controller, how subsystems work (and, in particular, the timer subsystem), how mob attacking works, the component system...)


[this format]: https://rust-lang-nursery.github.io/mdBook/format/index.html
[here]: https://wiki.hippiestation.com/index.php/Setting_up_git