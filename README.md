# VPC to C Compiler

This is a semi-compiler that can convert VPC code to C code. VPC is a custom format that allows for using Python list comprehension and functions in C.

## Installation

Project is still in development, so there is no installation yet.

## Usage

To use the VPC to C compiler, simply run the `vpc2c` command with the path to your VPC file as an argument:

```
gvpc test.vpc {-o a.out}
```

## VPC Syntax

The VPC syntax is similar to C, but with some additional features:

### List Comprehension

You can use Python-style list comprehension in VPC:

> Still in development.

### Importing Modules

You can import C modules in VPC using the `import` keyword:

```
import <stdio.h>
```

TODO: Add support for importing in the above format.

## Limitations

The VPC to C compiler is still in development and has some limitations:

- Only a subset of C syntax is supported.
- Some Python features may not work correctly in VPC.
- The generated C code may not be optimal or efficient.

## Contributing

If you find a bug or have a feature request, please open an issue on GitHub. Pull requests are also welcome.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.