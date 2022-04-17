<h1 align="center">enmity-theme-schema</h1>

A schema to aid in writing themes for [Enmity](https://github.com/enmity-mod).

## Usage
- Assign the theme file to the schema:

<details>
    <summary>Visual Studio Code</summary>

```json
// .vscode/settings.json
{
    "json.schemas": [
        {
            "fileMatch": [
                "/theme.json"
            ],  
            "url": "https://beerpiss.github.io/enmity-theme-schema/enmity-theme.schema.json"
        }
    ]
}
```
</details>

<details>
    <summary>Sublime Text (with LSP-json plugin)</summary>

```json
// LSP-json.sublime-settings
{
    "settings": {
        "userSchemas": [
            {
                "fileMatch": [
                    "/theme.json"
                ],
                "url": "https://beerpiss.github.io/enmity-theme-schema/enmity-theme.schema.json"
            }
        ]
    }
}
```
</details>

- Use an [online JSON schema validator](https://www.jsonschemavalidator.net/).


