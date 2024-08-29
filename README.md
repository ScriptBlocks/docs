# docs

Documentation for ScriptBlocks IDE.

## Contributing

Please feel free to contribute to our documentation! The format of our repository is very simple:

```
docs/
│
├── docs/
│   ├── en/ # English documentation
│   │   ├── index.md
│   │   └── ...
│   ├── es/ # Spanish documentation
│   │   ├── index.md
│   │   └── ...
│   └── fr/ # French documentation
│       ├── index.md
│       └── ...
│
├── mkdocs.yml
└── requirements.txt
```

### Directory Structure

- **`docs/`**: The root directory for documentation files.
  - **`en/`**: Contains the English version of the documentation.
  - **`es/`**: Contains the Spanish version of the documentation.
  - **`fr/`**: Contains the French version of the documentation.
- **`mkdocs.yml`**: The configuration file for MkDocs, where you define site settings, themes, plugins, and translation options.
- **`requirements.txt`**: Lists Python dependencies for MkDocs and any additional plugins.

### How to Contribute

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ScriptBlocks/docs.git
   cd your-repo
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Add or Edit Documentation**
- Navigate to the appropriate language directory (`en/`, `es/`, `fr/`).
- Edit or create Markdown files (`.md`) as needed.

4. **Test Locally**
   ```bash
   mkdocs serve
   ```
   This command starts a local server at `http://127.0.0.1:8000` where you can preview your changes.

5. **Submit a Pull Request**
- Commit your changes and push to your fork.
- Open a pull request in the main repository.

### Notes

- **Translation Folders**: The folder names for translations are based on their respective country codes (e.g., `en` for English, `es` for Spanish, `fr` for French).
- **MkDocs Configuration**: The `mkdocs.yml` file contains configuration settings, including theme choices, plugin settings, and translation configurations. Make sure to review and update this file as needed to reflect any structural changes.

Thank you for contributing to the ScriptBlocks IDE documentation!
