# Bugs

## Reports from the extension audit

### Invalid Composer metadata prevents normal package parsing

The tracked composer.json has a trailing comma inside extra. Verify strict JSON parsing and extension discovery after repair. [Source](https://github.com/phpbbmodders/tlink/blob/895b9ba8abea05064f3ee3e7f1e7e846e6c1418c/composer.json)
