# Consul

An Elixir client for Consul's HTTP API

# Forked!

This repository is fork https://github.com/undeadlabs/consul-ex  
Thx Jamie Winsor!

## Requirements

* Elixir 1.6 or newer

## Installation

Add Consul as a dependency in your `mix.exs` file

```elixir
def application do
  [applications: [:exconsul]]
end

defp deps do
  [
    {:exconsul, "~> 1.0"}
  ]
end
```

Add in config
```elixir
config :exconsul,
  host: "123.123.123.123", # your consul host
  port: 8500
```
Then run `mix deps.get` in your shell to fetch the dependencies.

## Docs

Run `mix docs` and open `doc/index.html` to view the documentation.

## Authors

Jamie Winsor (<jamie@undeadlabs.com>)
