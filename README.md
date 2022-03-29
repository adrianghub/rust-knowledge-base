# rust-knowledge-base
Rust described from the perspective of JavaScript developer.

### 1. Why Rust? 

_You could use C, C++, C#, Go, Java, Kotlin, Haskell or a hundred others. Rust is notoriously difficult even for system programmers to get into. Why bother with Rust? Think about your languages as tools in your toolbox. When you fill your toolbox, you don’t want 10 tools that solve similar problems. You want tools that complement each other and give you the ability to fix everything an anything. You already have JavaScript, a developer super-tool. It’s a high level language that’s good enough to run just about everything everywhere. If you’re picking up a new language, you might as well go to the extreme and pick a no-compromise, low-level powerhouse.
Also, WebAssembly.
Rust’s tooling and support for WebAssembly is better than everything else out there. You can rewrite CPU-heavy JavaScript logic into Rust and run it as WebAssembly. Which basically makes you a superhero. With JavaScript and Rust, there’s nothing you can’t handle._ - **book "From JavaScript to Rust" written by Jarrod Overson, Vino Technologies, and contributors**

In addition to that:

C/C++ level performance, with...
- nice ergonomics and a language server
- automatic memory management
- a package manager and code formatter

### 2. Why --not-- use Rust?

- Rust is a big language - there is a whole bunch of stuff to learn.
- Smaller ecosystem than C/C++ (but FFI)
- Slower iteration cycle than most languages
  - due to strict compiler
  - "fighting" the borrow checker
  - slow compile times for full builds
  - tests can take awhile to build

### 3. What makes the rust compiler slow?

There is a number of design decisions some of which are in the name of performance. (TBC)

