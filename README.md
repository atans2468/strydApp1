# STRYD App

_Note: This application requires Ionic CLI 3._

The STRYD app description here...fill out later

## Table of Contents

1. [Getting Started](#getting-started)
2. [Pages](#pages)
3. [Providers](#providers)
4. [i18n](#i18n) (adding languages)

## <a name="getting-started"></a>Getting Started

To test this app, install the latest version of the Ionic CLI, clone this git repo, navigate into your local project and run:

```bash
ionic serve --lab
```

## Pages

Right now there are two primary pages for the app...the 'Events' page which is simply displaying all the available events in individual cards. And then a 'Details' page which will show the details of that respective event.



## i18n

The STRYD app has imported internationalization (i18n) with [ngx-translate](https://github.com/ngx-translate/core). This makes it easy to change the text used in the app by modifying only one file...have not spent any time modifying this file yet but allows us to do so once the time is right.

### Adding Languages

To add new languages, add new files to the `src/assets/i18n` directory, following the pattern of LANGCODE.json where LANGCODE is the language/locale code (ex: en/gb/de/es/etc.).

### Changing the Language

To change the language of the app, edit `src/app/app.component.ts` and modify `translate.use('en')` to use the LANGCODE from `src/assets/i18n/`
