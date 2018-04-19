# znx

Atomic and differential updates for Linux distributions.

Usage: znx command args

Available commands are:

- init [DEVICE]
  Configures an initial setup on the disk. This
  should be done before attempting to run any
  other operation.

- install [PATH:NAME | URL:NAME]:
  Installs a new ISO file to the /os directory.
  Multiple paths or URLs can be specified.
  Each image must me assigned a name. If no name
  is specified, the operation is aborted. Name it
  in a way that makes sense to you.

- update [NAME]:
  Update an already installed image.

- remove [NAME]:
  Deletes an existing image.
