# scalable-app
Dynamic JavaScript Application Builder

builder + building blocks

## building blocks
1. app builder API hooks - builder not included and is intended (TODO: find and integrate with popular builder)
2. app - container of widgets and state
  1. app config - compiletime changed by widgets
  2. app state - runtime changed by widgets
3. widgets - UI unit
  1. APIs: onCreate, onDelete
  2. config state (as 1st level cache?)


Note... for app to scale: runtime is the only stuff. builder is different...
TODO: another package for the adaptors
