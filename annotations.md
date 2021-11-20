Steps:

> Install esy
> npm install -g esy || yarn add global esy
> create esy.json (it's like package.json) with dependencies
> run "esy" to create the first project build
> to show things
> esy shell
> dune --version
> ocaml --version
> ocamllsp --version
> create dune file with executable
> create projectname.opam (empty file)
> create an empty file called .ocamlformat
> esy dune build -w @runtest @check
