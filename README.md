# Rust Undefined Behavior Example

This repository demonstrates a common error in Rust: using raw pointers to modify data after the original owner's scope has ended.  This leads to undefined behavior because Rust's ownership system is violated.

The `bug.rs` file contains the erroneous code. The `bugSolution.rs` file demonstrates a safe and correct alternative.