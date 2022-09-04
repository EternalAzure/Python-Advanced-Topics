# Python-Advanced-Topics
A brief summarization of some advanced topics in Python.
- Language
- Techniques
- Architecture

## Language
How Python is build and how it works under the hood.

### Dunder Metdods
Dunder methods allow adding built-in laguage features to custom classes such as an add-operator or to customize existing behavior such as __str__ and __repr__.
Dunder methods are just methods named with double unders front and back. They are also called magic methods because they are called implicitly.

### Everything is an Object in Python
Everything you can place on the right side of the equals symbol is an object. Classes and functions are objects as well as primitives. A blueprint such as a class becomes an object through instantiation. Object is the keeper of identity and value.

### Method Resolution Order
Method Resolution Order or MRO for short is a concept used in inheritance. It is the order in which a method is searched for in a classes hierarchy and is especially useful in Python because Python supports multiple inheritance. MRO is crusial for understanding how super-method works. Super-method does not call behavior from a parent, but from netx-in-line.

### Scope Resolution
Python has objects within objects. Accessing variables requires scope resolution. Scope resolution starts from nearest and narrowest and ends to farthest and broadest.
- Local(L): Defined inside function/class
- Enclosed(E): Defined inside enclosing functions(Nested function concept)
- Global(G): Defined at the uppermost level
- Built-in(B): Reserved names in Python built-in modules

Closure is a function that encloses other. Closures maintain references to objects from earlier scopes. Closures are used in decorators.

## Techniques
Advanced techniques on a code level.

### Comprehension
Comprehensions are shorthand syntax for creating collections and iterable objects.

### Extended Keyword Arguments (*args, **kwargs)

### Decorators
Decorators are synta

### Generators and Iterators Protocol
### Context Managers
### @staticmethod and @classmethod
### Inheritance and Encapsulation
### Operator Overloading
### Python Packages and Program layout

## Architecture
Design patterns and guidelines.

### Factory pattern





