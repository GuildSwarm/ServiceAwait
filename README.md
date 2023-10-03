# ServiceAwait
This open-source repository contains the needed bash scripts deal with dependencies between Linux docker containers by running a bash server that dependent containers can ask if the service they depend on is ready or not. This allow us to define when the service is ready to be consumed by dependent containers in a flexible way and speeding up the whole docker-compose startup process. 
This system composed by the server script and the awaiter functions implemented in a second file.
