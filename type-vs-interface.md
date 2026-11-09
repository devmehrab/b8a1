# Type vs Interface in TypeScript

At first, I thought type and interface were the same thing in TypeScript because both can describe an object. For example, we can use both to create a User object with a name and age. But after learning more, I found some differences. Interface is mostly used for object structures. It can also extend another interface. On the other hand, type can do more things. We can use it for strings, numbers, union types and object structures too. For example, type Status = "active" | "inactive" is something we can easily do with type. Another difference is that interfaces with the same name can be merged, but type aliases cannot.

I think interface is a good choice for objects, while type is useful when we need more flexible types. Both are important, and we can use them together in the same project. Thanks.
