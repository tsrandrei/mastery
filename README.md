# Mastery

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `mastery` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:mastery, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/mastery](https://hexdocs.pm/mastery).

## Idea behind
 We have Quizzes made up of Tempaltes and Questions. Users answer questions with Responses.

Do Fun Things with Big Loud Worker-Bees ( Data Functions Tests Boundaries (processes) Lifecycle (supervisors) Workers (pools and dependencies)

### Data Layer
 - Our application run on Data, so data will define how application will work

### Functional Core
 - Build single-purpose functions
 - Where possible, bring functions to data rather than data to functions
 - Name concepts with functions
 - Shape functions for composition
 - Build functions at a **single** level of **abstraction**
 - Make decisions in functions head where possible
 - Complexity and Business Logic should be stored into Functional Core
