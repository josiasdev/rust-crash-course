# Rust Crash Course

[contributors-shield]: https://img.shields.io/github/contributors/josiasdev/rust-crash-course.svg?style=for-the-badge
[contributors-url]: https://github.com/josiasdev/rust-crash-course/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/josiasdev/rust-crash-course.svg?style=for-the-badge
[forks-url]: https://github.com/josiasdev/rust-crash-course/network/members
[stars-shield]: https://img.shields.io/github/stars/josiasdev/rust-crash-course.svg?style=for-the-badge
[stars-url]: https://github.com/josiasdev/rust-crash-course/stargazers
[issues-shield]: https://img.shields.io/github/issues/josiasdev/rust-crash-course.svg?style=for-the-badge
[issues-url]: https://github.com/josiasdev/rust-crash-course/issues

<div align="center">

[![Stargazers][stars-shield]][stars-url] [![Forks][forks-shield]][forks-url] [![Contributors][contributors-shield]][contributors-url] [![Issues][issues-shield]][issues-url]

</div>

Repositório de estudos do curso [**Rust Programming Basics**](https://updraft.cyfrin.io/courses/rust-programming-basics) da Cyfrin Updraft.

Este repositório reúne recursos, notas e exercícios do curso. O conteúdo original do curso é hospedado na Cyfrin Updraft.

## Links

- [Course](https://updraft.cyfrin.io/courses/rust-programming-basics) - Curso Rust Programming Basics na Cyfrin Updraft
- [Website](https://updraft.cyfrin.io) - 50+ horas de cursos de smart contract development
- [Twitter](https://twitter.com/CyfrinUpdraft) - Últimos lançamentos de cursos
- [LinkedIn](https://www.linkedin.com/school/cyfrin-updraft/) - Adicione Updraft ao seu aprendizado
- [Discord](https://discord.gg/cyfrin) - Comunidade de 3000+ desenvolvedores e auditores
- [Codehawks](https://codehawks.com) - Competições de auditoria de smart contracts

## O que você vai aprender

- Introduction to the Rust programming language
- Rust variables and functions
- Scalar types, arrays, strings, enum, structs, vectors, and hash maps in Rust
- Rust control flows: If / else, if let and let else, loop, match
- Rust ownership, including borrow and references
- Rust error handling
- Rust Modules
- Rust Traits

## Course intro

- [Course intro](./notes/course_intro.md)
- [Setup](./notes/course_setup.md)

## Rust intro

- [Install cargo](./notes/install.md)
- [Hello world](./topics/hello/README.md)
- [Variable](./topics/variable/README.md)
- [Function](./topics/function/README.md)

## Data types

- [Scalar types](./topics/scalar/README.md)
- [Tuple](./topics/tuple/README.md)
- [Array](./topics/array/README.md)
- [`String` and `&str`](./topics/string/README.md)
- [Enum](./topics/enum_type/README.md)
- [Struct](./topics/struct_type/README.md)
- [Vector](./topics/vector/README.md)
- [Hash map](./topics/hash_map/README.md)

## Control flow

- [If / else](./topics/if_else/README.md)
- [Loop](./topics/for_loop/README.md)
- [Match](./topics/pattern_match/README.md)
- [If let](./topics/if_let/README.md)

## Ownership

- [Stack and heap](./topics/stack_heap/README.md)
- [Ownership](./topics/ownership/README.md)
- [Borrowing rules](./topics/borrowing_rules/README.md)

## Error handling

- [Error handling](./topics/error/README.md)
- [`unwrap` and `expect`](./topics/unwrap/README.md)
- [`?`](./topics/question/README.md)

## Modules

- [Mod](./topics/modules/README.md)

## Generic types and traits

- [Generic types](./topics/generic_type/README.md)
- [Methods](./topics/method/README.md)
- [Trait](./topics/trait_basic/README.md)
- [Generic trait](./topics/generic_trait/README.md)
- [Trait bound](./topics/trait_bound/README.md)
- [Lifetime](./topics/lifetime/README.md)
- [Iterator](./topics/iterator_adaptors/README.md)
- [Iterator adaptors](./topics/iterator_adaptors/README.md)

## Concurrency

- [`async` / `await`](./topics/async_await/README.md)
- [Thread vs `async` / `await`](./topics/async_await/README.md)
- [`join!` and `select!` macros](./topics/join_select/README.md)

## App

- [Merkle tree algorithms](./topics/merkle/README.md)

## Resources

- [Rust](https://www.rust-lang.org/)
- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [rustlings](https://github.com/rust-lang/rustlings/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust playground](https://play.rust-lang.org/)
- [Rust Cheatsheet](https://cheats.rs/)

## Notes

Execute all tests in `solutions` folder:

```shell
find topics -type d -name solutions -exec bash -c 'cd "$0" && cargo test' {} \;
```
