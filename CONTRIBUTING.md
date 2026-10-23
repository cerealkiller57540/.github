# Contributing

Thanks for your interest in the Neon Cards.

## How the project is organised

- Each card lives in its own repository, so HACS can install and update it on its own. The full list is in [Home-Assistant-Neon-Cards](https://github.com/cerealkiller57540/Home-Assistant-Neon-Cards).
- A card is a single JavaScript file with no build step: the `.js` file in the repository is the source.

## Reporting bugs and ideas

- **Bug**: open an issue in the repository of the card, using the bug form. The card version, the Home Assistant version and the card YAML make all the difference.
- **Idea**: use the feature request form.
- **Question**: ask in [Discussions](https://github.com/cerealkiller57540/Home-Assistant-Neon-Cards/discussions).

## Pull requests

1. For anything bigger than a typo or a small fix, **open an issue first** so we can agree on the approach.
2. Keep a pull request to one change.
3. Test on a real dashboard, ideally on both a desktop browser and a phone or tablet. Several cards use WebGL: check that the card still works when WebGL is not available.
4. Use the theme variables (`--primary-color`, `--rgb-*`, …) rather than hard-coded colours, so the card follows the user's theme.
5. Do not bump the version number: it is set at release time.

By contributing, you agree that your contribution is published under the licence of the repository (MIT).
