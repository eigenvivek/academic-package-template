# academic-package-template
[![Build Status](https://github.com/eigenvivek/academic-package-template/actions/workflows/CI.yml/badge.svg?branch=main)]
Python package template for academic projects with fast and easy building / testing.

## How to use

1. Use this template
2. Create a new repository
3. Change all things in `Things to change`
4. Develop code, run experiments, write paper!

## Things to change

`src/`
- Change to whatever package name you want

`setup.py`
- Change `name` to same whatever you renamed `src/` to
- Add `description`
- Add `author`

`enviornment.py`
- Add whatever dependencies your package needs

## Other notes

- We use `micromamba` with download/environment caching to massively speed up the build times for CI. In my experience, this can be as much as a 3-5X speedup!
