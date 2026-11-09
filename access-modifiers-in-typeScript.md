# Access Modifiers in TypeScript

When I started learning TypeScript classes, I found access modifiers a little confusing. There are three main access modifiers: public, private and protected.

Public means we can use a property from anywhere. Private means we can only use it inside the same class. For example a password should be private because we dont want to access it directly outside. Protected is almost like private, but child classes can also use it. We also have readonly, which means a value cannot be changed after it is set. I think these features make class code easier to control and understand.
