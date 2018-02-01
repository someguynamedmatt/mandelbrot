# Mandelbrot in Rust
> Taken from Chapter 2 of "Programming Rust" (O'Reilly 2018)
____

This demonstrates concurrency in Rust, as well as a good intro into some common highlights of the language, moving, borrowing, and more. The program requires four command-line arguments be passed to it: file name (and location, e.g. ~/Pictures/mandel.png), bounds (image size), beginning point (upper left), and beginning point (lower right).



To run from the command line:
- `cargo build --release`
- `target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20`

On my machine this ran in a little over one second, generating this image:

![fractal](https://user-images.githubusercontent.com/17413539/35662071-eacef040-06ca-11e8-9f93-34ac1853a9b0.png)
