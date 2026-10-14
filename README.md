# Next.js Codespaces Setup Experiment

An early learning repository for starting a minimal Next.js application in a GitHub Codespaces environment.

The current source consists of a small page displaying a test heading and a package manifest with a development-server command. It records environment setup practice.

## Source versions

- Next.js `^13.1.6`
- React `^18.2.0`
- React DOM `^18.2.0`

These are the versions declared in the repository. They are not a recommendation for a new application.

## Run the development page

Prerequisites: Node.js and npm compatible with the declared dependencies.

```bash
git clone https://github.com/cesaints/settings.codespace.git
cd settings.codespace
npm ci
npm run dev
```

In Codespaces, open the forwarded development port from the Ports panel. A public port is unnecessary for a personal preview.

The package manifest defines only `dev`. Build, test and deployment commands are not provided by this repository.

## Current state

The tracked tree includes generated `.next` output and dependency artifacts. These should be reviewed and removed from version control in a separate cleanup change.

The repository demonstrates a setup exercise. It does not contain evidence of a scalable application architecture or a tested reusable development template.

The commands above were checked against source and were not executed for this documentation review.

## Rights

No license file was present in the reviewed revision.
