# javascript-to-elixir

cheatsheet to help Javascript developers picking up Elixir by providing a map of equivalent

> packages listed here are not necessary the best in its kind but typical ones, suggestions are welcome

## general toolings

|          category           |      javascript       |         elixir        |
|-----------------------------|-----------------------|-----------------------|
| package manager | [npm](https://github.com/npm/cli) | [mix](https://github.com/elixir-lang/elixir) |
| code linter | [eslint](https://github.com/eslint/eslint) | [credo](https://github.com/rrrene/credo) |
| code formatter | [prettier](https://github.com/prettier/prettier) | [mix format](https://hexdocs.pm/mix/master/Mix.Tasks.Format.html) |
| static type checker | [flow](https://github.com/facebook/flow) | [dialyxir](https://github.com/jeremyjh/dialyxir) |
| unit test runner | [jest](https://github.com/facebook/jest) | [mix test](https://github.com/elixir-lang/elixir), [mix-test.watch](https://github.com/lpil/mix-test.watch) |
| mock | [jest](https://github.com/facebook/jest) | [mock](https://github.com/jjh42/mock) |
| logger | [winston](https://github.com/winstonjs/winston) | [logger](https://github.com/elixir-lang/elixir) |
| tracing | | [recon](https://github.com/tatsuya6502/recon_ex), [tap](https://github.com/eproxus/tap) |
| benchmark | | [benchee](https://github.com/PragTob/benchee) |
| git commit hook | [husky](https://github.com/typicode/husky)/[pre-commit](https://github.com/observing/pre-commit) | [pre-commit](https://github.com/dwyl/elixir-pre-commit) |
| docs | | [ex_doc](https://github.com/elixir-lang/ex_doc) |

## web framework and toolings

|          category           |      javascript       |         elixir        |
|-----------------------------|-----------------------|-----------------------|
| runtime | [Chrome V8](https://developers.google.com/v8/) | [Erlang VM](https://elixir-lang.org/) |
| web server | [node](https://github.com/nodejs/node) | [phoenix](https://github.com/phoenixframework/phoenix) |
| http server | [express](https://github.com/expressjs/express) | [cowboy](https://github.com/ninenines/cowboy)  |
| http client | [node-fetch]() | [httppoison](https://github.com/edgurgel/httpoison) |
| live reload | [webpack]()  | [phoenix_live_reload](https://github.com/phoenixframework/phoenix_live_reload) |
| i18n i10n | | [gettext](https://github.com/elixir-lang/gettext) |
| graphql toolkit | [apollo-server](https://github.com/apollographql/apollo-server), [graphql-tools](https://github.com/apollographql/graphql-tools) | [absinthe](https://github.com/absinthe-graphql/absinthe), [absinthe_plug](https://github.com/absinthe-graphql/absinthe_plug) |


## syntax

[syntax map](https://github.com/chattes/javascript_to_elixir/wiki)
