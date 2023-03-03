# Multi-IO Library

This library enables Java programs to conduct IO operations (create, read, move, delete, download, etc.) over an abstract IO implementation. Microservice-style architecture.

This project is a pair assignment conducted as part of the [Software Components (4025)](https://raf.edu.rs/knjiga-predmeta/softverske-komponente/) course at the [School of Computing, Union University](https://raf.edu.rs/?pismo=lat).

**NOTE:** Please note that all of the project's documentation is in Serbian.

The project consists of the following submodules:

| Component | Description |
| --- | --- |
| [sk.core](./sk.core/) | The "main" part of the library that glues the components together. |
| [sk.specification](./sk.specification/) | The shared specification used for developing concrete implementations of IO ops. |
| [sk.localImplementation](./sk.localImplementation/) | An implementation of IO functionalities based on local storage. |
| [sk.remoteImplementation](./sk.remoteImplementation/) | An implementation of IO functionalities based on Google Drive. |
| [sk.cli](./sk.cli/) | CLI program for accessing the library. |

## Authors

[![Andreja Nesic](https://andrejanesic.com/git-signature-sm.png)](https://andrejanesic.com)

Aleksa Stojanovic<br>
Student @ [School of Computing, Union University](https://raf.edu.rs/?pismo=lat)<br>
https://github.com/Aleksa0308