# Tamil Translations for react-admin

Tamil translations for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST services.


## Installation

```sh
npm install --save ra-language-tamil
```

## Usage

```js
import tamilMessages from 'ra-language-tamil';

const messages = {
    'ta': tamilMessages,
};
const i18nProvider = locale => messages[locale];

<Admin locale="ta" i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).