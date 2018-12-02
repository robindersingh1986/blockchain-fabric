# blockchain-fabric



startf to start fabric dev server
stopf to stop fabric dev server
cplay to run composer-playground


Add the following to .bash_profile for having commnds shortcut/alias

alias startf=~/fabric-dev-servers/startFabric.sh
alias stopf=~/fabric-dev-servers/stopFabric.sh
alias cplay=composer-playground

docker kill $(docker ps -q)
docker rm $(docker ps -aq)
docker rmi $(docker images dev-* -q)
