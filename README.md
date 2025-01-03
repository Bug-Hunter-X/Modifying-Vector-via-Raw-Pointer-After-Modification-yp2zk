This repository contains an example of a common error in Rust: modifying a vector through a raw pointer after the vector has been modified.  The `bug.rs` file demonstrates the incorrect code, which leads to undefined behavior. The `bugSolution.rs` file shows how to avoid this problem by using safe Rust methods.