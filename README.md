# No Closed Form

Source for [No Closed Form](https://higorhi.github.io), a digital garden built with [Quartz](https://quartz.jzhao.xyz).

## Writing

Add Markdown notes and their assets to `content/`. Changes pushed to `main` are built and deployed automatically with GitHub Actions.

## Local preview

Requires Node.js 22 or newer.

```shell
npm ci
npx quartz build --serve
```

## Deployment

The GitHub Pages workflow is defined in `.github/workflows/deploy-main.yaml`.
