# avalanche
A fullstack, modern, crazy fast development platform for TypeScript, React, GraphQL, MongoDB

This platform will make it easy to develop, deploy, test full stack apps. 

## Features

* INSANELY FAST dev env on both client and server thanks to Snowpack & ESBuild
* Seriously the ui reload times are 50ms and the full server production builds are >1sec 🙀
* No lock in - ui and api folders can be used independantly of Avalanche.
* Use as a starterkit or a framework
* Easy deployment via GH ACtions & https://render.com
* Built in CI/CD via GH Actions
* Generate all your GraphQl React Hooks
* Super cute CLI with interactive menus instead of having to memorize flags.


### Testing

Tests are written as .test.tsx or .test.ts

#### Mockmang

Mockmang is a uility for quickly generating fake data for mocks in graphql components



### Codegen

####  Step 1.

Wrtie all of your graphql queries, mutations and schemas in .graphql files.

#### Step 2.

Run avalanche and select Codegen or Codegen Watch

`node avalanche`

Select codegen. This creates all of your React Hooks as well as TS types. 



### Building for Production


### Hosting

We have run our setup on https://render.com and can provide detailed instructions on how to get up and running. 
