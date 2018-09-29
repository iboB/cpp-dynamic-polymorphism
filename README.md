# C++ Dynamic Polymorphism

List of resources about modern dynamic polymorphism in C++. 

## Libraries

Some libraries may end-up in two lists if they support multiple features

### Polymorphic type-erasure wrappers

Allow you to create a polymorphic interface which can be used without inheritance.

* Dyno: https://github.com/ldionne/dyno
* Eraserface: https://github.com/badair/eraserface
* Folly.Poly: https://github.com/facebook/folly/blob/master/folly/docs/Poly.md (This is a link to the documentation. The library itself is part of Folly)
* liberasure: https://github.com/atomgalaxy/liberasure

### Open methods

Allow you to create external polymorphic methods for existing classes.

* yomm2: https://github.com/jll63/yomm2

### Multiple dispatch

Allow you to define functions which are dispatched based on multiple arguments as opposed to one in the clasical virtual function case.

* Folly.Poly: https://github.com/facebook/folly/blob/master/folly/docs/Poly.md (This is a link to the documentation. The library itself is part of Folly)
* yomm2: https://github.com/jll63/yomm2

### Composition, components, and mixins

Allow you to create polymorphic objects from building blocks through composition over inheritance.

* DynaMix: https://github.com/iboB/dynamix

### Signals/slots and multicasts

Allow you to invoke multiple functions with a single call.

* ???

## Other resources

### Articles and papers

* Dynamic Generic Programming with Virtual Concepts
https://github.com/andyprowl/virtual-concepts
* The Interface to Component Pattern and DynaMix
 https://accu.org/index.php/journals/2487 