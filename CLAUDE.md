# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static memorial site for 沈賾 (Dread Lord), a CS classmate who passed away in 2014. It is hosted on GitHub Pages using Jekyll with the `jekyll-theme-minimal` theme. The primary content is in `README.md`, which serves as both the homepage and the narrative memorial.

## Site Configuration

- **Jekyll config:** `_config.yml` — sets title, description, theme
- **GitHub repository:** https://github.com/InvisibleSix/Dread_Lord_Memory
- **Hosting:** GitHub Pages (auto-built from `main` branch)

No local build environment is required. GitHub Pages builds the Jekyll site automatically on push.

## Content Structure

Media and narrative are organized chronologically by life period:

| Directory | Period |
|---|---|
| `01_入学/` | Freshman year / First meeting |
| `02_宿舍与日常/` | Dorm life & daily moments |
| `03_课程与学习/` | Courses & academic life |
| `04_社团与活动/` | Clubs, activities, trips |
| `05_毕业/` | Graduation (2013) |
| `06_工作与生活/` | Post-graduation life |
| `07_其他/` | Other miscellaneous memories |
| `Contributions/` | Community-submitted content |

## Editing Guidelines

- **All narrative content** lives in `README.md`. This file is the site homepage rendered by Jekyll.
- **Images** are referenced with relative paths from `README.md`, e.g., `./04_社团与活动/Dinning/xxx.jpg`.
- **Guestbook entries** are managed via GitHub Issues — do not store them as files.
- **Community contributions** are submitted via Pull Requests adding files to `Contributions/`.

## Sensitive Context

This repository is a deeply personal memorial. When making edits, preserve the tone, respect the subject matter, and avoid any changes that alter the emotional intent of the narrative. Prefer conservative, minimal edits.
