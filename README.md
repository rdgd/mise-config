On a new computer you must create `~/.docker/cli-plugins/` and symlink your mise install of docker-compose plugin here.
e.g. `ln -sf ~/.local/share/mise/installs/docker-compose/2.39.2/docker-cli-plugin-docker-compose ~/.docker/cli-plugins/docker-compose`

ls should be symlinked to eza 

on ubuntu, must `sudo apt update` and `sudo apt install bison` so that yacc is available to build tmux
