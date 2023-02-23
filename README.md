# Deno arm64 Docker Container Template
How to build an docker container from a deno application with github workflows and push them to the packages section of the repository.

The build and push github action is triggered when a new release tag has been created. The finished container will be published as a package with the corresponding tag.

Big thanks to LukeChannings who created this repository https://github.com/LukeChannings/deno-arm64 which made this even possible!
