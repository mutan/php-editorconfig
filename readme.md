## Installation

1. Add to `composer.json`:
```json
"repositories": [
    {
        "type": "vcs",
        "url": "ssh://git@github.com:22/mutan/php-editorconfig.git",
        "reference": "master"
    }
]
```

2. Install package
```bash
composer require mutan/php-editorconfig:^1.0
```

3. Make symlink in project root dir
```bash
ln -s vendor/mutan/php-editorconfig/.editorconfig .
```

4. Enable `.editorconfig` in PhpStorm: Settings - Editor - Code Style - check Enable EditorConfig support.  

5. Use `Ctrl+Alt+L` to reformat the code.
