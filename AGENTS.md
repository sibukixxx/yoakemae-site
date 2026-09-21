# YoakeMae Site

Public site for the YoakeMae project. Treat tracked content/site configuration as the source of truth.

## Commands
- Use the package manager and scripts declared by the root manifest/lockfile.
- Run the repository's build and content validation before reporting site changes complete.

## Shared rules
- Public product claims must reflect implemented/current YoakeMae behavior; do not publish roadmap items as shipped features.
- Keep public-site content separate from private application/user data.
- Do not introduce a new framework/package manager solely for a small content/component change.
- Deployment is a separate action from local build validation.

## Change-dependent checks
- Content/component: build the site.
- Routes/metadata: verify generated links/metadata with existing checks.
- Deployment config: validate locally; deploy only when explicitly requested.

## Done
- Site build/validation passes.
- Public claims match current implementation status.
- No private app data or secret is exposed.
