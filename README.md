# systemd + celestia

## celestia.service
- Not sure if the `PATH` is actually necessary

## eq-service.service

- I pass all the environment variables by a list of `Environment` statements. This is probably bad.
- I hardcode a user called "ubuntu" and a bunch of paths. This is also bad.

Nevertheless, I can copy-paste this instead of rewriting it every time i spin up a box.
