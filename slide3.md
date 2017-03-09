Docker Engine is a client-server application with these major components:
A server which is a type of long-running program called a daemon process.


A REST API which specifies interfaces that programs can use to talk to the daemon and instruct it what to do.

A command line interface (CLI) client.


The CLI uses the Docker REST API to control or interact with the Docker daemon through scripting or direct CLI commands. Many other Docker applications use the underlying API and CLI.
The daemon creates and manages Docker objects, such as images, containers, networks, and data volumes.