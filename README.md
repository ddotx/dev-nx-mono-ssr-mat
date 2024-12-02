# DevNxMonoSsrMat

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ Your new, shiny [Nx workspace](https://nx.dev) is ready ✨.

```shell
npx create-nx-workspace@latest
# apps/ssg-web

npx nx g @nx/angular:app apps/ssr-web --dry-run

```

## Materials
```shell
npm install @angular/material@18

nx g @angular/material:ng-add --project ssg-web
# > theme = custom
# > global typo = false
# > animations = enabled

```

### Theme from custom colors
```shell
npx nx generate @angular/material:m3Theme --directory=apps/ssg-web/

```