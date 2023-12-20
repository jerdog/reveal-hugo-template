# RevealJS + Hugo Default Presentation

***fork from [Reveal-Hugo by @dzello](https://github.com/dzello/reveal-hugo)***

## Basics

This template has the following in place from @dzello's Hugo theme:

1. Installed [Hugo](https://gohugo.io/getting-started/installing/) and then created a new Hugo site via:

```shell
hugo new site my-presentation
cd my-presentation
```

2. Initialized the theme as a Hugo module (i.e. `hugo mod init github.com/jerdog/reveal-hugo-template`)

3. Declared the Reveal+Hugo theme module as a dependency (i.e. `hugo mod get github.com/dzello/reveal-hugo`)

4. Added the basic presentation starter file to `/content/_index.md`

5. Added `.gitkeep` to the base Hugo folders so that the full structure comes over in the repo

## Updates you need to make

1. Update the `go.mod` file with the correct location of your GitHub repo:

```go
// update the below to reflect your github repo location
module github.com/jerdog/reveal-hugo-template
```

2. Update the Hugo theme module to the latest version:

```shell
hugo mod get -u github.com/dzello/reveal-hugo
```

## Documentation

To get up to speed on all other elements and usage of Reveal.js with Hugo, visit @dzello's [README](https://github.com/dzello/reveal-hugo/blob/master/README.md)