This is a NixOS flake that defines both my system and user configuration declaratively. Follows `nixpkgs-unstable`.

From within this directory:
- Regenerate NixOS using `sudo nixos-rebuild switch --flake .`
- Home-manage using `home-manager switch --flake .`
- Update software repository using `nix flake update .`

The aliases `nixr`, `nixh`, and `nixu` are defined respectively, and can be ran from anywhere. The `nixu` alias also performs a full system regeneration. 
