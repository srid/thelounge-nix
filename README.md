# Nix package for thelounge

This repo holds the nix files for deploying [thelounge](https://github.com/thelounge/lounge) IRC web client. The .nix files were generated using [node2nix](https://github.com/svanderburg/node2nix) for the "thelounge" npm package.

To install, run: `nix-env -f default.nix -iA thelounge`
