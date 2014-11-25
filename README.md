rust-test
=========

Some rust examples, nothing important

1. Install Rust
  ```bash
    curl -s https://static.rust-lang.org/rustup.sh | sudo sh
  ```

2. Add /usr/local/lib to your LD_LIBRARY_PATH

  Open Gedit (or other text editor)
  ```bash
    gedit ~/.bashrc
  ```
  Include a new line
  ```bash
    export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:/usr/local/lib
  ```

4. Clone the Repository
  ```bash
    git clone https://github.com/yuripourre/rust-test.git
  ```

5. Build the project
  ```bash
    cd rust-test
    cargo build
  ```
