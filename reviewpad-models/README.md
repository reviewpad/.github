# Reviewpad Models

This folder contains the set of models used by Reviewpad.

## Development

If you wish to update the models, please make sure your VSCode is configured to use the latest version of the Reviewpad JSON Schema.

You can do this by opening the `settings.json` file and adding the following line:

```json
{
    "yaml.schemas": {
        "https://raw.githubusercontent.com/reviewpad/schemas/main/latest/schema.json": [
            "reviewpad-models/*.yml",
        ]
    },
}
```
