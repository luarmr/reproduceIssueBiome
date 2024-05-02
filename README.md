# Issue Reproduction - Biome.js

This Repo provides an explanation for an issue open in the biome.js repository. The issue causes the biome command to become unresponsive when executing certain commands.


## Reproduction Steps

To reproduce the issue, follow these steps with this repo:

1. Run `yarn install --frozen-lockfile` to install the dependencies.
2. Run `yarn biome check --apply .` to execute the biome command, you will be stuck.
3. Replace `noreferer` with the correct code `noreferrer` in index.tsx
4. Save the file and execute `yarn biome check --apply .` will perform nicely.
