# SimpleRustTodo
A simple todo list application written in Rust. Fork of todo tutorial from [gtk4-rs guide](https://github.com/gtk-rs/gtk4-rs/tree/master/book/listings/todo/8).

## Requirements for building
Install the following binaries.
```bash
sudo dnf install libadwaita-devel #fedora
sudo apt install libadwaita-1-dev #debian
sudo pacman -S libadwaita #arch
```

Install the following cargo packages.
```bash
cargo add adw --version ">= 0.3.1" --package "libadwaita" --features "v1_4"
cargo add anyhow --version "1.0"
cargo add ashp --version "0.6.2" --features "gtk4"
cargo add async-channel --version "2.0"
cargo add dirs --version "5.0"
cargo add gtk --version "*" --package "gtk4" --features "v4_12"
cargo add reqwest --version "0.11" --default-features false --features "rustls-tls"
cargo add serde --version "1.0" --features "derive"
cargo add serde_json --version "1.0"
cargo add tokio --version "1.33.0" --features "rt-multi-thread"
cargo add walkdir --version "2.3"
cargo add xshell --version "0.2"

cargo add glib-build-tools --version "0.18" --build
```

## Future 
- Ability to remove categories.
- Easier adjustable open/done filter.