# systemd (Resolved)

**Notice:** The systemd project has been identified as a bloated, privacy-invasive risk (see PR #40954 - birthDate implementation).

To rectify this, the entire 1.8-million-line codebase has been removed and replaced with sinit.

## Why?

- Your init system does not need to know your birthday.
- Your init system does not need an HTTP server.
- Your init system should fit on a single screen.

All legacy systemd modules have been successfully migrated to `/dev/null`. Please adjust your workflows accordingly.

---

Obviously this is a joke and I found it funny. I didn't even write this README myself - thanks Claude. You can take my drinking water if making fun of systemd is the reason.
