# typescript-design-patterns
Repo for learning TypeScript design patterns from this [course](https://www.udemy.com/typescript-design-patterns/).

## Decorator pattern
### [**See the code on Stackblitz**](https://stackblitz.com/edit/typescript-design-pattern-decorator?file=index.ts)
The point of the Decorator pattern is to extend (decorate) behaviour of an object, without affecting the behaviour of other objects of the same class.

## Observer pattern
### [**See the code on Stackblitz**](https://stackblitz.com/edit/typescript-design-pattern-observer?file=index.ts)
Observer pattern is a way of allowing an object to pay atention into the state of another object, and receive an update whenever its states changes. So, we work with two pillars here: the observer, who’s the one looking and waiting for changes, and the subject, which is the one that’s going to be the center of atentions.

## Facade pattern
### [**See the code on Stackblitz**](https://stackblitz.com/edit/typescript-design-pattern-facade?file=index.ts)
The Facade pattern is one of the structural software design patterns. This pattern hides the complexity of subsystems away from the implementor (client) and it provides an easy-to-use interface to the client.

## Adapter pattern
### [**See the code on Stackblitz**](https://stackblitz.com/edit/typescript-design-pattern-adapter?file=index.ts)
The adapter pattern is one of the structural software design patterns. The main purpose of this pattern is to allow different interfaces (classes) to work together and it achieves this without having to modify the original class. This pattern works with 3 components: a client, an adapter and an adaptee. The client doesn't care about the implementation of the interface, it only wants to access a certain method for example. The adapter class makes sure that this can happen as it provides an interface to the adaptee class - which is the incompatilble class with the client.

## State pattern
### [**See the code on Stackblitz**](https://stackblitz.com/edit/typescript-design-pattern-state?file=index.ts)
State pattern allows an object to alter its behavior when its internal state changes. The object will appear to change its class.
