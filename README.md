# DevQuotes

## Prepare

Checkout the repository:

    git clone git@github.com:renuo/dev_quotes.git
    cd dev_quotes

Install the prerequisites to have a running *elixir* installation:

    brew install erlang exenv elixir-build
    exenv install

## Setup

To start your Phoenix app:

```
bin/setup
```

You may need to adjust `config/secret.exs`.

Some more explanations:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
