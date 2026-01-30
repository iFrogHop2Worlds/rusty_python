# Rusty Python
A transpiler that lets you write python code using a modified syntax and inherits some of rust safety gurantees making your python code more reliable and correct.


# Just transpile to Python and print to stdout
cargo run -- -i example.bython

# Transpile and save to file
cargo run -- -i example.bython -o output.py

# Transpile, save to file, and run immediately
cargo run -- -i example.bython -o output.py --run

# Transpile and run directly (without saving to file)
cargo run -- -i example.bython --run

# Use a specific Python interpreter
cargo run -- -i example.bython --run --python-interpreter python3

This is a work in progress
