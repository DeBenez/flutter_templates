# Mason Templates

This repository contains ready to use templates using the [Mason CLI](https://github.com/felangel/mason).

First to get started with Mason CLI, follow the instructions in the [Mason Documentation](https://github.com/felangel/mason/blob/main/README.md#installation).

After installing Mason CLI, run the following command to get all bricks:

```sh
mason get
```

After that you can run the following command to view all available templates:

```sh
mason list
```

To use a template, run the following command:

```sh
mason make template_name --output-dir /path/to/output
```

Replace `template_name` with the name of the template you want to use.

Replace `/path/to/output` with the path where you want the template to be generated.

## Available Templates

| Template Name | Description |
| --- | --- |
| [flutter_initial_setup](flutter_initial_setup) | A brick to implement in a new Flutter project a basic setup with most used plugins already configured.|
| [flutter_lints_rules](flutter_lints_rules) | A brick to implement a customized set of flutter lints rules instead of the default ones.|
