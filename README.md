The repository was created to show how to run services from within
a network namespace. The files within this repository are within
the directories that they would need to be in on a local system
which has been done to highlight the file structure and to provide
context.

This example repository is setup to run haproxy from within a
namespace however nothing in the systemd service units is bound to
only haproxy.

See https://cloudnull.io/running-services-in-network-name-spaces-with-systemd/
for more details on how these files are used.
