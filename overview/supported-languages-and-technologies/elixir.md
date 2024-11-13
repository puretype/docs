---
description: Details about the support for Elixir within PureType
---

# Elixir

[Elixir](https://elixir-lang.org/) is a dynamic, functional language for building scalable and maintainable applications, running on the Erlang virtual machine.

## Checks

Examples of checks for the language include the following areas:

* **if conditions vs guards** - guards are a concept not always familiar to new engineers. Suggesting a rewrite of a function whose body is surrounded by an if condition is helpful for introducing the concept and spotting the pattern later on
* **comprehensions vs Enum pipelines** - filter + map + reduce pipelines are easier to read and faster; pipelines can evolve into this form over time but typically are not spotted by those not familiar with the form
* **Map lookup** - there are many different forms of map lookup, suitable for various forms. Given enough context, PureType can analyze and suggest the best option and ensure developers are familiar with all forms
* **bang vs non-bang functions** - the intended error behaviour of using the incorrect form of the function can be surprising, or result in more error handling code than strictly necessary

## Supported versions

All versions of Elixir are supported. Because only the structure of the code is reviewed, there is no issues with code intended to be run using an older Elixir version.

## File extensions

`.ex`, `.exs`

`.heex` is currently not supported.
