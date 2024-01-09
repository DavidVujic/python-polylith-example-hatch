# Python Polylith Example

This is a repository with an example `Python` setup of the Polylith Architecture using `hatch`.
Here you will find examples of code being shared between different kind of projects, and the developer tooling setup.

## Developer experience

### Mypy
Have a look at the `mypy.ini` configuration file, to make `Mypy` work really well with this type of architecture.

``` ini
[mypy]
mypy_path = components, bases
namespace_packages = True
explicit_package_bases = True
```

### Tooling support
Currently, there's tooling support for using Polylith in Python for `Poetry`.

__Currently working on tooling support for Hatch too!__

Have a look at this repository:
[Python tools for the Polylith Architecture](https://github.com/DavidVujic/python-polylith)
