# FERRIMOJI :crab: :heart_on_fire:

![GitHub CI](https://github.com/angeldollface/ferrimoji/actions/workflows/rust.yml/badge.svg)

***When Ferris wants pictures. :crab: :heart_on_fire:***

## ABOUT

Some time ago, I wrote a small Dart library to use emojis in the console.
That library was called [termstyle](https://github.com/angeldollface/termstyle). This is the Rust implementation of that library.

## INSTALLATION

To use ***Ferrimoji*** in your Rust projects, add this line to your project's `Cargo.toml`:

```TOML
ferrimoji = { git = "https://github.com/angeldollface/ferrimoji", version = "1.1.0" }
```

## USAGE
To import ***Ferrimoji***'s functions, put this line of code inside your Rust code:

```Rust

// Get a map of Ferrimoji's emojis.
use ferrimoji::unicode_pool;

// Print or manipulate an emoji as a string.
use ferrimoji::get_emoji;

```

To refer to ***Ferrimoji***'s functions, please click [here](https://github.com/angeldollface/ferrimoji/blob/main/src/lib.rs).

Here's a small example:

```Rust
use ferrimoji::get_emoji;

// Prints a crab to the console.
fn main(){
  println!("{}", get_emoji("crab"));
}
```

## CHANGELOG

### Version 1.0.0

- Initial release.
- Upload to GitHub.

### Version 1.1.0

- The Doll Update.
- Updated, published, and uploaded under my new name.

## NOTE

- *Ferrimoji :crab: :heart_on_fire:* by Alexander Abraham :black_heart: a.k.a. *"Angel Dollface" :dolls: :ribbon:*
- Licensed under the MIT license.
