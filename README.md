# website-written-tutorials

This repo contains all the written tutorials for the filledstacks.com website. This is created so that we can get contributions with translations.

## Helping with Translations?

There are two types of translations you can do. The website and then the content of the website. Lets start with the Website text itself.

### Translation Preparation

Before we do the translation itself it's important to let us know which translations you'll be working on.

1. Create an issue in the repo called "Adding Translations for [Language]". This is where you'll update us on the progress of the translations and also to make sure no one adds translations for the same language.
2. Create a new branch called language/[languageCode] for spanish it would be language/es

### Website Text Translations

All translations for this is stored in a single json file. It has a key and then the value for that key. You'll only be updating the values and not the keys.

1. Open up locales folder
2. Make a copy of the en.json file and rename it to the language code you're working on
3. Update the values of the properties to the matching phrase/word in English for the language you're working on

### Content Translations

_Note: Please do not translate the title or the tags_

1. Go into the posts folder
2. Create a new folder and use the language code as the name
3. Find a tutorial that you want to translate in the en folder
4. Copy that tutorial into your new folder
5. Update the `locale` value in the frontmatter definition (The config above the ---)
6. Change the `isFullyTranslated` to true
7. DON'T translate the tags. We have to figure out how we're going to deal with that. Since the tags are used for product names we don't want to translate that.
8. Translate the written tutorial, leave the images as it is, only translate the text and the comments in the code if there are any.
9. Post simple update in the issue from #2 . Something like "Completed translation for tutorial 043"
10. When there's enough translations / content we'll make a PR and merge into master.

If you have any questions join the [FilledStacks slack](https://join.slack.com/t/filledstacks/shared_invite/zt-mcw04u5t-dTeyH0lPONuzd9i0osk9Gw) and send a message to @filledstacks to be added to the open source channel where you can ask questions.
