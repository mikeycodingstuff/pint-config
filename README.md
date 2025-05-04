# PHP Pint Config

Some preferred default pint rules.

## Usage

Download the config file to your project root:

```
curl -o pint.json https://raw.githubusercontent.com/mikeycodingstuff/pint-config/main/pint.json
```

## Rules

```json
{
  "preset": "laravel",
  "rules": {
    "array_push": true,
    "array_syntax": {
      "syntax": "short"
    },
    "concat_space": {
      "spacing": "one"
    },
    "declare_strict_types": true,
    "fully_qualified_strict_types": true,
    "global_namespace_import": {
      "import_classes": true,
      "import_constants": true,
      "import_functions": true
    },
    "modernize_types_casting": true,
    "no_superfluous_elseif": true,
    "no_useless_else": true,
    "not_operator_with_successor_space": false,
    "ordered_class_elements": {
      "order": [
        "use_trait",
        "case",
        "constant",
        "constant_public",
        "constant_protected",
        "constant_private",
        "property_public",
        "property_protected",
        "property_private",
        "construct",
        "destruct",
        "magic",
        "phpunit",
        "method_abstract",
        "method_public_static",
        "method_public",
        "method_protected_static",
        "method_protected",
        "method_private_static",
        "method_private"
      ],
      "sort_algorithm": "none"
    },
    "self_accessor": true,
    "strict_comparison": true,
    "visibility_required": true
  }
}

```