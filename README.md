# redports
Redports is a continuous integration platform for FreeBSD ports.

This is a new attempt to fully automate the redports platform and
to minimize setup and administration effort.

Want to help? IRC #redports (freenode)


# TODO

This are the major TODO items before we can do a first
2.0.0 release.

redports-node port:
- needs redports-node.json file with default config
- needs rc script

node:
- poudriere integration
- business logic for building and talking to master
- setup command to create new poudriere jails

master:
- commit comments on github after end of build
- portstree upload needs to update URL for all jobs with
  that repository and revision

