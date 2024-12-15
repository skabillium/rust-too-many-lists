# Learning Rust With Entirely Too Many Linked Lists

This repository is a companion to the book **[Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)**. It contains the implementations and exercises covered in the book, along with any additional experimentation or extensions as I progress through the material.

## About the Book

[Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) is a practical guide to learning Rust by building and exploring the various implementations of linked lists. The book is designed to help you gain deeper insights into Rust's ownership model, error handling, enums, lifetimes, and more by tackling a complex yet approachable data structure.

## Project Overview

This repository includes:

- Implementations of different types of linked lists, such as:
  - Singly linked lists
  - Doubly linked lists
  - Persistent (immutable) linked lists
- Step-by-step commits that align with the chapters in the book.
- Experimentation with additional concepts to solidify understanding.

Each folder or module corresponds to a specific type of linked list and builds upon the knowledge gained in earlier chapters.

---

## Getting Started

### Prerequisites

To work with this repository, you need:

- **Rust** installed on your system. You can install Rust using [rustup](https://rustup.rs/):

  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  ```

- A basic understanding of Rust syntax and concepts. If you're new to Rust, check out the official [Rust Book](https://doc.rust-lang.org/book/) before diving in.

### Cloning the Repository

Clone this repository to your local machine:

```bash
git clone skabillium/rust-too-many-lists
cd rust-too-many-lists
```

### Setting Up the Environment

1. Ensure that Rust is installed and up-to-date:
   ```bash
   rustup update
   ```

2. Navigate to the folder for the specific implementation you want to explore:
   ```bash
   cd src/singly_linked_list
   ```

3. Build the project:
   ```bash
   cargo build
   ```

4. Run the tests to verify the implementation:
   ```bash
   cargo test
   ```

5. Execute the example programs:
   ```bash
   cargo run
   ```

---

## Folder Structure

- `src/singly_linked_list`: Implementation of a singly linked list.
- `src/doubly_linked_list`: Implementation of a doubly linked list.
- `src/persistent_list`: Implementation of a persistent (immutable) linked list.
- Additional folders correspond to chapters and experiments.

---

## Contributing

The purpose of this repository is only for personal use (and backup) so no need to open any pull requests. Feel free to fork if you want to make any changes.

---

## Resources

- [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)
- [Rust Programming Language Official Documentation](https://doc.rust-lang.org/)
- [The Rust Book](https://doc.rust-lang.org/book/)

---

## License

This repository is provided under the MIT License. See the [LICENSE](LICENSE) file for more details.
