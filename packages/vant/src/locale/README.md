# Internationalization

### Intro

Vant uses Chinese as the default language. If you want to use other languages, please follow the instructions below.

## Usage

### Switch languages

Vant supports multiple languages with the Locale component, and the `Locale.use` method allows you to switch to different languages.

```js
import { Locale } from 'vant';
import enUS from 'vant/es/locale/lang/en-US';

Locale.use('en-US', enUS);
```

### Override default configs

Use `Locale.add` method to modify the default configs.

```js
import { Locale } from 'vant';

const messages = {
  'en-US': {
    vanPicker: {
      confirm: 'Close',
    },
  },
};

Locale.add(messages);
```

### Config files

Current supported languages:

| Language                 | Filename     | Version  |
| ------------------------ | ------------ | -------- |
| Bangla (Bangladesh)      | bn-BD        | `v3.4.5` |
| German                   | de-DE        | -        |
| German (formal)          | de-DE-formal | -        |
| English                  | en-US        | -        |
| Spanish (Spain)          | es-ES        | -        |
| French                   | fr-FR        | -        |
| Hindi                    | hi-IN        | `v3.4.3` |
| Indonesian               | id-ID        | `v3.4.5` |
| Italian                  | it-IT        | `v3.4.5` |
| Japanese                 | ja-JP        | -        |
| Korean                   | ko-KR        | `v3.4.3` |
| Norwegian                | nb-NO        | -        |
| Portuguese (Brazil)      | pt-BR        | `v3.3.3` |
| Romanian                 | ro-RO        | -        |
| Russian                  | ru-RU        | `v3.1.5` |
| Turkish                  | tr-TR        | -        |
| Thai                     | th-TH        | -        |
| Ukrainian                | uk-UA        | `v3.4.5` |
| Vietnamese               | vi-VN        | `v3.4.5` |
| Chinese                  | zh-CN        | -        |
| Traditional Chinese (HK) | zh-HK        | -        |
| Traditional Chinese (TW) | zh-TW        | -        |

> View all language configs [Here](https://github.com/youzan/vant/tree/dev/packages/vant/src/locale/lang).

### Add new language

If you can’t find the language you need, please send us a Pull Request to add the new language pack, you can refer to [Add German language pack](https://github.com/youzan/vant/pull/7245) PR.
