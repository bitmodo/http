# Cod HTTP
The Cod HTTP API is an implementation of HTTP 1.1 for use by the [Cod Microframework](https://github.com/codmf/cod).
Just because it is meant for Cod doesn't mean it is explicitely for Cod.
The API is meant to be convenient and simple so that anyone can take advantage of it.

## Purpose
The purpose of the Cod HTTP API is to provide a clean, flexible implementation of the HTTP specification.

## Inspiration
The inspiration behind this project would be the [Cod Microframework](https://github.com/codmf/cod).
Cod is a microframework written in C, and it aims to not rely on any external dependencies.
This project is a member of the [Cod Microframework Ecosystem](https://github.com/codmf).
That means that it is an official project that is supported and used by Cod.

## Current status
Right now, we are still in extremely early development.
Things aren't expected to actually be working for a while.
Sit tight, and check back in a while!

## Usage
This project uses [Meson](https://mesonbuild.com/) as its build system.
Once you have that installed, you have two options.
You could clone this repository to make some changes, or you could use this project as a dependency.

### Making changes
If you want to make changes, first you need to clone this repository.
Once you have the code, you can run the following command to build the project:

```cmd
meson build
```
This will build the project into the `build` directory.

The rest is a work-in-progress.
Wait for more!

### Using as a dependency
If you want to use this project as a dependency, first you need to have a project.
From there, you can add this repository as a subproject using Meson's [wrap system](https://mesonbuild.com/Wrap-dependency-system-manual.html).
Your wrap file should look something like the following:

```
[wrap-git]
url = https://github.com/codmf/http.git
revision = head
```

The rest is a work-in-progress.
Wait for more!
