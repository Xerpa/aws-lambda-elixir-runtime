# AWS Lambda Elixir Runtime

Example implementation of a custom runtime for running Elixir on AWS Lambda.

## Installation

The package can be installed by adding `aws_lambda_elixir_runtime` to your list
of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:aws_lambda_elixir_runtime, "~> 0.1.0"}
  ]
end
```

## Documentation

Documentation can be generated with
[ExDoc](https://github.com/elixir-lang/ex_doc).

## Step By Step Usage

This section is a step by step for creating the hello world example.

First, create a new mix project in a fresh directory:

```sh
> mix new --app hello_world ./hello_world
```

Now declare a dependency on `:aws_lambda_elixir_runtime` and
`:distillery`, which is used to package the OTP release.

Work in Progress
