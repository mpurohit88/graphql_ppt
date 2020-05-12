#HSLIDE

# GraphQL Basic

<span class="primary"><strong>Mukesh Purohit</strong></span> - 12 May 2020
 
#HSLIDE

# Cons of API

- Multiple Round Trips To Fetch Related Resources.<!-- .element: class="fragment" -->
- Over Fetching / Under Fetching.<!-- .element: class="fragment" -->
- Rapid Product Iterations on the Frontend.<!-- .element: class="fragment" -->


#HSLIDE

## What we will cover today ?
- Data Model <!-- .element: class="fragment" -->
- Components<!-- .element: class="fragment" -->
- Lifecycle<!-- .element: class="fragment" -->


#HSLIDE

## Here are two types of “model” data in React:

- props<!-- .element: class="fragment" -->
- state<!-- .element: class="fragment" -->

#HSLIDE

## state

- Only components defined as classes can have state.<!-- .element: class="fragment" -->

#HSLIDE

## props

- Props are inputs to a React component. They are data passed down from a parent component to a child component. <!-- .element: class="fragment" -->

- Remember that props are readonly. They should not be modified in any way.<!-- .element: class="fragment" -->

- Difference between state and props is that props are passed from a parent component, but state is managed by the component itself.<!-- .element: class="fragment" -->

#HSLIDE
# Components

- Components are basically just functions that return the view based on the current state.<!-- .element: class="fragment" -->

- Components let you split the UI into independent, reusable pieces, and think about each piece in isolation<!-- .element: class="fragment" -->

- Single responsibility principle, that is, a component should ideally only do one thing.<!-- .element: class="fragment" -->


#HSLIDE
## Sample Code

```
class Greeting extends React.Component {

  render() {
  
    return <h1>Hello, CompoZed!!</h1>;
    
  }
  
}
```

#HSLIDE
## More About Components

- Stateful vs Stateless<!-- .element: class="fragment" -->

- Classes and Functions<!-- .element: class="fragment" -->

- Pure and Impure<!-- .element: class="fragment" -->

- Presentational and Container Components<!-- .element: class="fragment" -->

- Composition Patterns<!-- .element: class="fragment" -->

#HSLIDE
## Lifecycle Methods

- Lifecycle methods are custom functionality that gets executed during the different phases of a component's life time.

#HSLIDE

# Demo

#HSLIDE

# Questions ?

#HSLIDE

# Thank you
