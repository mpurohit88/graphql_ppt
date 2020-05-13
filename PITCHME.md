#HSLIDE

# GraphQL Basic

<span class="primary"><strong>Mukesh Purohit</strong></span> - 12 May 2020
 
#HSLIDE

## Challenges with REST

- Multiple Round Trips To Fetch Related Resources.<!-- .element: class="fragment" -->
- Over Fetching / Under Fetching.<!-- .element: class="fragment" -->
- Rapid Product Iterations on the Frontend.<!-- .element: class="fragment" -->

#HSLIDE
## GraphQL to Rescue

![filter=saturate, skewx=20, skewy=-35](img/superGraphQL.jpg)

#HSLIDE

## GraphQL to Rescue

![filter=saturate, skewx=20, skewy=-35](img/self.jpg)

#HSLIDE

## GraphQL to the rescue
- GraphQL is a query language for your API, and a server-side runtime for executing queries by using a type system you define for your data <!-- .element: class="fragment" -->
- With GraphQL we describe in the client which data we want to have instead of just asking all the data.<!-- .element: class="fragment" -->

#HSLIDE

## GraphQL query
```
{
  me {
    name
  }
}

```

## JSON result
```
{
  "me": {
    "name": "Luke Skywalker"
  }
}
```

#HSLIDE

## Similarities and Differences:

- Both are based on the concept of a resource and can specify IDs for resources.<!-- .element: class="fragment" -->
- Both can be fetched via an HTTP request.<!-- .element: class="fragment" -->
- Both can return JSON data in the request.<!-- .element: class="fragment" -->

#HSLIDE

## Some Differences b/w GraphQL and REST:

- Data fetching with REST causes over- and under-fetching issues whereas this simply isn’t possible with GraphQL.<!-- .element: class="fragment" -->
- in REST you define the object on Backend and on GraphQL you "define" this object on Frontend.<!-- .element: class="fragment" -->
- With REST, the server determines the shape and size of the resource whereas, in GraphQL, the server simply declares the available resources and the client can ask for exactly what it needs.<!-- .element: class="fragment" -->
- REST automatically puts caching into effect whereas GraphQL has no automatic caching system..<!-- .element: class="fragment" -->

#HSLIDE

## More About GraphQL

- GraphQL is a language that enables you to provide a complete and understandable description of the data in your API.<!-- .element: class="fragment" -->
- GraphQL is an API syntax that defines how to fetch data from one or many databases.<!-- .element: class="fragment" -->
- GraphQL is declarative: Query responses are decided by the client rather than the server. A GraphQL query returns exactly what a client asks for and no more.<!-- .element: class="fragment" -->
- GraphQL is compositional: A GraphQL query itself is a hierarchical set of fields. The query is shaped just like the data it returns. It is a natural way for product engineers to describe data requirements.<!-- .element: class="fragment" -->
- GraphQL is strongly-typed: A GraphQL query can be ensured to be valid within a GraphQL type system at development time allowing the server to make guarantees about the response. This makes it easier to build high-quality client tools.<!-- .element: class="fragment" -->

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
