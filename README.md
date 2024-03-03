# Github Actions Playground
Repository for exploring Github Actions capabilities

- [Github Actions Docs](https://github.com/features/actions)

## Run Github Actions locally
[act](https://github.com/nektos/act) - CLI tool for emulating Github workflows

### Command structure 
`act [<event>] [options]`

*If no event name passed, will default to "on: push"*\
*If actions handles only one event it will be used as deault instead of "on: push"*

Examples:
- `act -s` - list all actions for all events
- `act workflow_dispatch -l` - list the actions for a specific event
- `act pull_request` - run a specific event
- `act -j test` - run a specific job
