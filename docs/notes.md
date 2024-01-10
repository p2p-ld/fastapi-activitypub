# Notes

Notes-ice how there is nothing in this package yet! keeping track of ideas while doing some initial
sketching.

## Data organization

- whole instance is an RDF dataset
- one graph for each actor

## Desired functionality

Basically want to make it so the only thing you need to do to make an activitypub
server is define what happens when you get actions

- Event/hook driven AP system: be able to register callbacks on events
- Easily daemonized with socket-based cli interface