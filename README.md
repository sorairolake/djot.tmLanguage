# Djot.tmLanguage

[![CI][ci-badge]][ci-url]

TextMate grammar files for [djot][djot-url].

This is a fork of [VS Code Markdown Grammar][based-repo-url].

## Contributing

The main grammar is stored in `syntax/djot.tmLanguage`.
This file is generated from `djot.tmLanguage.base.yaml`.

### Building

To generate the main grammar:

```sh
npm install
npm run build
```

## License

The code and documentation are distributed under the terms of the _MIT License_.

See [LICENSE](LICENSE) for more details.

[ci-badge]: https://github.com/sorairolake/djot.tmLanguage/workflows/CI/badge.svg
[ci-url]: https://github.com/sorairolake/djot.tmLanguage/actions?query=workflow%3ACI
[djot-url]: https://djot.net/
[based-repo-url]: https://github.com/microsoft/vscode-markdown-tm-grammar
