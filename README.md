# The Wizard Amigos Guide 🧙

To know more about the project, please visit the [Wizard Amigos website](http://wizardamigos.com/).

## How to collaborate

The _Wizard Amigos Guide_ is built with [mdBook](https://github.com/rust-lang-nursery/mdBook), an open-source tool to write documentations in markdown which is then magically transformed into html/css/js.

For a complete guide on how to use mdBook, please have a look at the [mdBook User Guide](https://rust-lang-nursery.github.io/mdBook/).

1. In order to be able to use mdBook, you have to install [Rust](https://www.rust-lang.org/) first (at least version 1.20).

Copy the following command in your terminal:

```sh
curl https://sh.rustup.rs -sSf | sh
```

2. After Rust has been installed, please install mdBook:

```sh
cargo install mdbook
```

3. Now clone the repository locally:

```sh
git clone https://github.com/nicco88/wizard-amigos-guide.git
```

4. Go into the directory you just cloned and run the following command in order to see changes live:

```sh
mdbook serve --open
```

5. If you want to add chapters or subchapters just add a line into `src/SUMMARY.md` like this:

```md
- [Chapter Title](./file_name.md)
  - [Sub-chapter Title](./file_name.md)
```

Then save and mdBook will create a corrisponding md file for you into the `/src/` folder

6. Now you can edit your md files and watch them changing live.

7. When you are happy with your changes, just commit them, and that's it! 😎