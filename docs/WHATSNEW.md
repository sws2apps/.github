# Process for Localizing the What’s New Content for CPE

This document will explain the process for publishing What’s New content for all CPE applications. Translations will be made on Crowdin, under the [sws2apps](https://crowdin.com/project/sws2apps) project.

## Source Text

1. An administrator will create the what’s new content in the source translation. For each item, two text strings will be created. For example: `lmmo-20230215-01-title` and `lmmo-20230215-02-body`. These identifiers will be used to verify for which application the content will be delivered, and to know when the content was created.
2. After both texts have been added, they will be available for all applicable applications within on hour. We hope that most of the needed translations can be achieved within that time frame.

## Translation

1. As explained above, find the two text needed for the what’s new content you would like to translate.
2. If no translation was provided, or the translation was not yet approved, the source text will be used as default.
3. All approved translations will appear immediately, only if the source text was already showing in the applications. Otherwise, they will wait until the source will be published.