# Rust Seed Project
This project is a seed to a general rust project consisting of a lib and an app.
# Visual Studio Code
Install the recommended extensions when you open the project for the first time in VSCode and you're good to go.
# Test Coverage
Only supported on Linux currently. First install `grcov` and the `llvm-tools-preview`
```
$ rustup component add llvm-tools-preview
$ cargo install grcov
```
Then run the tests with coverage enabled.
```
$ ./test_coverage.sh
```
Click the "◯ Watch" button in the status bar to show the coverage gutters besides source files. Or, open the `coverage/html/index.html` for an HTML coverage report.