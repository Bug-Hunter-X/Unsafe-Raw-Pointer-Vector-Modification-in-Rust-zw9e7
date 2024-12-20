# Unsafe Raw Pointer Vector Modification in Rust

This repository demonstrates a potential bug in Rust involving unsafe raw pointer manipulation of a vector.  Modifying a vector via a raw pointer can lead to memory corruption or undefined behavior if not done correctly.  The example showcases how to modify the first element of a vector using unsafe code and raw pointers and a safer alternative.

## Bug
The `bug.rs` file contains code that directly modifies the first element of a vector using a raw pointer. This approach bypasses Rust's memory safety guarantees.  The example shows how to modify the first element of a vector using unsafe code and raw pointers.

## Solution
The `bugSolution.rs` demonstrates a safer way to modify the vector, using standard library functions, avoiding unsafe code.