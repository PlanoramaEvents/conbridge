# ConBridge
## Connecting your convention
### An Identity Provider Aggregator, made specifically for convention needs

Made by Planorama Events Inc

### Goals

- hook together multiple pieces of software that all have information about a person. For example, convention registration, saved schedule preferences, program(me) schedule, discord
- provide documented configuration for many variations of known convention data
- provide a common data model for convention identity for easy consumption by other APIs
- versioned api

# Development
- backend (server) written in express with mongoose/mongodb for storage
  - can both use other IDPs and act as an IDP itself
- frontend (client) written in angular
  - currently doesn't do much - maybe some day unified convention login but that is far off. for now mostly this is backend software
