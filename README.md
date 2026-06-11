# Wright Lab Website

<p align="center">
  <img src="./assets/media/lab_logo.png" alt="Wright Lab logo" width="220">
</p>

Source code for the Wright Lab website:  
<https://galenwrightlab.com>

The Wright Lab is a neurogenomics research group at the University of Manitoba focused on human genetic variation, neurological disease modifiers, DNA repair, precision genomics, and human cellular models of brain disease.

## Theme

This website is based on the Hugo Blox Research Group theme:  
<https://github.com/HugoBlox/theme-research-group>

It uses Hugo modules and includes local configuration, content, and template overrides specific to the Wright Lab site.

## Repository overview

This repository contains the Hugo source files used to build and deploy the Wright Lab website.

Main directories:

```text
config/       Hugo and Hugo Blox configuration
content/      Website pages, posts, people, publications, and project content
assets/       Site assets processed by Hugo
static/       Static files copied directly to the built site
layouts/      Local template overrides
```

## Common content updates

Most routine website updates should be made in `content/`. Changes to `config/`, `layouts/`, `go.mod`, or `netlify.toml` should be treated as site-configuration changes and tested carefully before pushing.

| Update type | Location |
|---|---|
| People profiles | `content/authors/` |
| News posts | `content/post/` |
| Publications | `content/publication/` |
| Site-wide configuration | `config/_default/` |
| Local template overrides | `layouts/` |

After editing content, preview the site locally using the instructions in **Local development** below.

## Local development

Install Hugo Extended, then run:

```bash
hugo server --cleanDestinationDir --gc
```

The local site will be available at:

```text
http://localhost:1313/
```

For a full rebuild without fast render mode:

```bash
hugo server --disableFastRender --cleanDestinationDir --gc
```

## Production build

To build the site locally:

```bash
hugo --gc --minify
```

## Hugo version

This site has been tested with:

```text
hugo v0.127.0+extended
```

Using the extended version of Hugo is recommended.

## Deployment checklist

Before pushing website updates:

```bash
git status
hugo server --cleanDestinationDir --gc
hugo --gc --minify
git status
```

Then commit and push:

```bash
git add <changed-files>
git commit -m "Describe change"
git push
```

## Common files to avoid committing

The following files are local or generated and should not be committed:

```text
.DS_Store
.hugo_build.lock
public/
resources/
```

These are excluded in `.gitignore`.

## License and reuse

Website content, images, logos, and lab materials belong to the Wright Lab unless otherwise noted. Reuse of source code, configuration, or content should follow the repository license if one is added.

