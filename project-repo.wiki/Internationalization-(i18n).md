## Internationalization intro
> _Internationalized software supports the languages and cultural customs of people throughout the world. The Web reaches all parts of the world. Internationalized web apps provide a great user experience for people everywhere._

We use a collection of libraries to support internationalization (i18n for short) of this application. To become familiar and gain an understanding of this process, read through [these basic internationalization principles](https://formatjs.io/guides/basic-i18n/).

## Process
We use three tools to support i18n:
- `react-intl` - a library that adds onto the Intl browser API to provide a series of helper components and an API for formatting language/dates/numbers into proper locales.
- `babel-plugin-react-intl` - a babel plugin that extracts all the messages from our components, putting them into organized `.json` files to support a straightforward workflow when working with translators/translation services.
- `react-intl-translations-manager` - a CLI tool that helps to support the management of multiple languages. This helps us track if there are duplicate message IDs, strings that are untranslated, among other low-level issues.

It's recommended to get familiar with the documentation of `react-intl` so that you can properly implement translatable messages when working on the UI.   

**When creating or updating any of the UI, you must use the components or the API provided by `react-intl` for all strings that must be translated.**