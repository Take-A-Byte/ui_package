# ui_package

> [!NOTE]  
> This repo is forked from https://github.com/gianfrancopapa/bricks/tree/main/ui_package - [301091](https://github.com/gianfrancopapa/bricks/commit/3010912729ac5a3f63268226ba2bd84845905d6c)

A mason brick to create a new UI package containing the design system.

## Usage 🚀

```
mason make ui_package --package_name flutter project --short_name FP
```

## Variables ✨

| variable           | description                  | default | type      |
| ------------------ | ---------------------------- | ------- | --------- |
| `package_name`     | name of the package          | ui      | `string`  |
| `short_name`       | short name of the package    | ui      | `string`  |

## Output 📦

```
├── flutter_project_ui
│   ├── gallery
│   ├── lib
│   │   └── src
│   │       ├── colors
│   │       ├── icons
│   │       ├── spacing
│   │       ├── theme
│   │       ├── typography
│   │       └── widgets
│   ├── flutter_project_ui.dart
│   ├── .gitignore
│   ├── analysis_options.yaml
│   └── pubspec.yaml
└── ...
```
