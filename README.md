# pmgodata i18next locales

i18n translation for pmgodata.app and implemented with [i18next](https://www.i18next.com/)

## Available Languages

- English
- 繁體中文

## Project Structure

```
i18next-locales
├── .gitignore
├── README.md
└── en
    ├── evolutionItemNames.json
    ├── moveNames.json
    ├── pokemonNames.json
    ├── pokemonTypes.json
    └── translation.json
```

Each locale folder contains several translation files, and each file is a `namespace` in [i18next](https://www.i18next.com/principles/namespaces).

## Contributing

We would love for you to contribute to this project and help do translation of other languages! As a contributor, here are the guidelines we would like you to follow:

- [Code Rules](#code-rules)
- [GitHub Flow](#github-flow)
- [Commit Message Guidelines](#commit-message-guidelines)

### Code Rules

- JSON key must sorted alphabetically
- Add final new line in each file
- Indentation: 4 spaces

### GitHub flow

We use GitHub flow. Please read the [article](https://guides.github.com/introduction/flow/) before contributing. Branch `develop` will be the development branch and do pull request against it.

### Commit Message Guidelines

https://www.conventionalcommits.org/en/v1.0.0/
