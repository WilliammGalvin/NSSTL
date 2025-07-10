# NSSTL (Not So Standard Library)

This project is just for my own educational benefit. I'll be remaking many of the features from C++'s standard library (STL).  
The goal is to deepen my understanding of templates, memory management, move semantics, iterators, and modern C++ design patterns.
Feel free to join along and try for yourself! :)

---

## 🟢 Easy

> Great for building intuition with templates and value semantics.

- `optional<T>` — A container for values that may or may not be present.
- `unique_ptr<T>` — A simple, move-only smart pointer with single ownership.
- `pair<T1, T2>` — Lightweight 2-field data structure.
- `initializer_list<T>` — Mimics how `{}` list initialization works in functions and classes.
- `span<T>` — A non-owning view into a contiguous block of memory (like an array or vector).

---

## 🟡 Medium

> Involves dynamic memory, iterators, and templates. Helps build core STL knowledge.

- `vector<T>` — A dynamic array with growth, reallocation, and iterator support.
- `stack<T>` — Container adapter built over another container like `vector`.
- `shared_ptr<T>` — A reference-counted smart pointer with shared ownership.
- `function<Signature>` — A type-erased callable wrapper (similar to lambdas).
- `find()` — A generic algorithm that searches a container using iterators and equality.

---

## 🔴 Hard

> Advanced data structures, memory control, and generic algorithm design.

- `map<K, V>` — A tree-structured associative container with key-based lookups.
- `string_view` — A lightweight, non-owning string abstraction with slicing.
- `allocator<T>` — A customizable memory allocator used by containers like `vector`.
- `sort()` — A generic, efficient sorting algorithm (quicksort, mergesort, or introsort).
- Custom `iterator` hierarchy — Implement input/output/forward/random-access iterator categories.
