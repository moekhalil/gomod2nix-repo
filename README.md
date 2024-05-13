
# Nix + Go + gomod2nix

## Directions for working with Go repo in Nix using gomod2nix
  
@moekhalil - 05/13/2024  

----------------------------------------------------------------

## Editing

Modifying the code is normal; just edit main.go

## Adding dependencies
 
 a) Add them to go.mod  
 b) Jump into a devShell with `nix develop`  
 c) Run `gomod2nix generate` to update the toml file  

## Building

In the root folder, run `nix build`.


## Running

In the root folder, run `nix run`.
