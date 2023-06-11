`nix flake show`: shows what is in the nix flake
`nix run`: will build and run what outputs from the build
`nix develop`: will provide a shell in which has all of the dependencies installed and we can just use our normal build workflow of making the build dir, running `cmake` and `make`

`nix build --rebuild` will force a rebuild of a flake

`-L`: big logs instead of single line log