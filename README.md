# Docker action "Hola Mundo"

This actions prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a quien saludar. Por defecto "Mundo"

## Outputs

### `time`

La fecha en la que te salude

## Example

```
uses: armestlinks/hello-world-docker-actions@v1
with:
  who-to-greet: 'Nordics'
```
# hello-world-docker-action
