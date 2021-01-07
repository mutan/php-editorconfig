## Installation

1. Add to `composer.json`
```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/mutan/php-editorconfig.git",
        "reference": "master"
    }
]
```

2. Install package
```bash
composer require --dev mutan/php-editorconfig:^1.0
```

3. Make symlink in project root dir
```bash
ln -s vendor/mutan/php-editorconfig/.editorconfig .
```

4. Add to `.gitignore`
```bash
.editorconfig
```

5. Enable `.editorconfig` in PhpStorm: Settings - Editor - Code Style - check Enable EditorConfig support.

6. Use `Ctrl+Alt+L` to reformat the code.
