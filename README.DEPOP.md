# Django 1.4 Fork

This is Depop's fork of Django 1.4.22

# Deployment

There is a user configured with access rights to this repository, you can use
it in your requirements file like (pointing at our "master" branch in this example):

`git+https://depop_backend_deploy:NiSwojlujCewpAmeic@bitbucket.org/depop/django.git@depop-1.4.22`

Or to point to a specific tag:

`git+https://depop_backend_deploy:NiSwojlujCewpAmeic@bitbucket.org/depop/django.git@1.4.22-depop1`

# Git Branching

We're using git flow for development; but with the following changes:

* "develop" branch should map to "depop-1.4.22-dev"
* "master" branch should map to "depop-1.4.22"
* tagging for releases should have a -depopX postfix (e.g 1.4.22-depop1,
  1.4.22-depop2 etc)

```
⇒  git flow init
Which branch should be used for bringing forth production releases?
   - depop-1.4.22
   - depop-1.4.22-dev
   - master
Branch name for production releases: [master] depop-1.4.22
Which branch should be used for integration of the "next release"?
   - depop-1.4.22-dev
   - master
Branch name for "next release" development: [master] depop-1.4.22-dev
How to name your supporting branch prefixes?
Feature branches? [feature/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
```