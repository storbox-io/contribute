![Logo](https://puu.sh/CYnPt/086676ab65.png)

# Information for contributors

## Introduction

You may have come to this point, because you want to help us out in developing or something else.
No problem, we have enough to do. :thumbsup:

In the following, the different repositories of storBox are quickly explained and how you can contribute:

## Modules

### Core

[![Todo](https://img.shields.io/badge/Core-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/1)

The core application manages many different things - for example the loading of modules, abstraction layers for different parts of the application like databases, caches, filesystem integration etc.
It also performs basic actions used by the other modules - e.g. copying files, verifying users and much more.

### Web-UI

[![Todo](https://img.shields.io/badge/Web--UI-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/2)

The Web-UI module handles the complete web interface - which is built up upon Angular and the Socket.IO as the communication method for the backend. It includes the user panel which helps the user to manage his storage online and the admin panel which allows the admins to create new spaces, users, etc.
The web interface can be adapted with web modules.

### FTPS

[![Todo](https://img.shields.io/badge/FTPS-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/3)

This is the transfer module for the protocol FTPS. It enables the user to connect to his storage with a FTPS client. Of course it can also be used for server applications to connect to the storage box.

### Samba

[![Todo](https://img.shields.io/badge/Samba-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/4)

This is the transfer module for the usage of Samba, an implementation of the Server Message Block protocol. With this package, the user has the ability to connect to the storage by connecting to as a network drive like a NAS in the local network. It makes it possible to view your contents within for example the Windows Explorer without using an extra client.

### SFTP

[![Todo](https://img.shields.io/badge/SFTP-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/5)

This is the transfer module for the protocol SFTP. SFTP is a file transfer based on SSH. It enables the user to connect to his storage with a SSH client. This can be easily used to transfer backups to your storage box.

### storBox CE

[![Todo](https://img.shields.io/badge/storBox CE-Todo-Green.svg)](https://github.com/storbox-io/contribute/projects/6)

This application is the Community Edition of storBox which includes all of the modules above and is the product the users will download and execute.

## How to contribute

All of the features that have to be implemented in the module are documented in the respective files above.

If you want to contribute, you can lookup the Projects tab in this repository. In most of the cases there is a kanban-style to-do board which is used to keep track on things that are needed.
When you find a feature that is not marked as "In Progress", you can fork the project and make a pull request in the repository to let it merge into the master branch.

It is important that you copy the license header found in the root directory of every repository (file "HEADER") into the beginning of every source file you write.

Don't pull request a completely new feature - start an issue in the repository of the module instead. When it is approved, it will be added to the project board and you can start working on it.