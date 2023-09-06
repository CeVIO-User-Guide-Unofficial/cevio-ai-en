---
title: Change Log (This Website)
author: 夜輪風超絶技巧変奏曲
date: 2022-11-16
category: Change Log
layout: post
---

## September 1, 2023

- Now this document is also published via Cloudflare.
- Chinese and English documents are separated into distinct GitHub repositories.
- A new domain name, en.ceviodoc.uk, has been launched.
- Removed mkdocs-static-i18n plugin.

## May 1, 2023

- Material for MkDocs is updated to 9.1.8。
- mkdocs-static-i18n plugin is updated to 0.56。

## November 21, 2022

- English translation is added.
- Language switching is enabled to switch between the English pages and Chinese pages.
    - Added mkdocs-static-i18n plugin.
    - `navigation.instant` is now disabled as it is not compatible with language switcher.
        - > mkdocs-material language switcher contextual link is not compatible with theme.features = navigation.instant
- Due to a change in the folder structure, the creation dates of all pages have been changed.
- Added image zoom function.
    - Added mkdocs-glightbox plugin.
- Material for MkDocs is updated to 9.0.0b3.

## November 16, 2022

- Material for MkDocs is updated to 8.5.10.
    - Style change of annotation took place in version 8.5.6.
- Each page will now display the date it was created at the bottom of it.
    - Applied the following setting to git-revision-date-localized plugin: `enable_creation_date: true`.

## June 7, 2022

The first version.
