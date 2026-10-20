# PX site

Public pages for PX, served by GitHub Pages at https://espii-px.github.io/px/.
The folders mirror the PX shared drive.

```
clients/
  active/<client>/       one folder per active client (matches "All Clients" in Drive)
    audit.html           Client Audit, built from the client's "Client Audit | <Client>" Google Doc
  offboarded/<client>/   moved here when a client is offboarded (matches "Offboarded Clients")
playbooks/               later: the PX playbooks, mirroring "Playbooks" in Drive
```

Pages here are generated. Never edit them by hand: change the source doc and rebuild.
The Client Audit builder lives in `claude-sandbox/client-audit/` (`build_page.py`).
Every page carries `noindex`, so search engines don't list it, but anyone with the link can open it.
