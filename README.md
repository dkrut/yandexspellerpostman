# YandexSpellerPostman
Posman tests for [yandexspeller](https://yandex.ru/dev/speller/). More 100 requests and about 700 tests.

To use tests, import _**collection**_ `YandexSpeller.postman_collection.json` and _**environment**_ `YandexSpeller.postman_environment.json`

If you want to use CI or run tests without an interface, use [newman](https://github.com/postmanlabs/newman). Example:

`newman run YandexSpeller.postman_collection.json -e YandexSpeller.postman_environment.json`

If need reports, use [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra) . Example:

`newman run YandexSpeller.postman_collection.json -e YandexSpeller.postman_environment.json -r htmlextra`
