# Hack80 registration site mirror

A static, local mirror of the registration portal UI, assembled from captured page markup and public static assets. Personal and participant identifying details have been replaced with sample values. The original authenticated HTML dumps, API data, and screenshots are not included.

## Run locally

```sh
npm start
```

Open http://localhost:4173/register. The local pages are static snapshots; submitting forms and account/API actions are disabled.

## Pages

- `/register` — registration
- `/logIn` — sign-in
- `/todo` — dashboard
- `/owndata/` — participant profile
- `/teams/my` — team
- `/teams/application` — team application
- `/submitsolution` — solution submission
- `/tasks` — tasks

## Attribution

Visual and static resources originate from [reg.hack80.phystech-union.org](https://reg.hack80.phystech-union.org/). This mirror is for interface review and does not connect to or submit data to the original service.
