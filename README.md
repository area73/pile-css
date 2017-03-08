# pile-css


## Single responsability principe
The term was introduced by Robert C. Martin in an article by the same name as part of his Principles of Object Oriented Design made popular by his book Agile Software Development, Principles, Patterns, and Practices.

The single responsibility principle states that every module or class should have responsibility over a single part of the functionality provided by the software, and that responsibility should be entirely encapsulated by the class. All its services should be narrowly aligned with that responsibility.

In other words this principle states that everything you create should be created for a single, focused reason. The styles you apply to a given selector should be created for a single purpose, and should do that single purpose extremely well.

This doesn’t mean you should have individual classes for padding-10, font-size-20, and color-green. The single purpose we’re talking about is not the styles that they apply, but rather where the styles are applied

## Single source of truth principe

The single source of truth approach takes the single responsibility theory to the next level in that not only is a class created for a single purpose, but also the styles applied to that class come from one single source. In a modular design, the design of any component must be determined by the component itself, and never imposed on it by a parent class.

## Gitflow
[http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/)
