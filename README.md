# cusy-vale

A [Vale-compatible](https://github.com/errata-ai/vale) implementation of the [cusy editorial guidelines](https://www.cusy.design/de/latest/writing/index.html).

## First steps

To get started, add the package to your configuration file (see below) and run `vale sync`.

```ini
StylesPath = styles
MinAlertLevel = suggestion

Packages = https://github.com/cusyio/cusy-vale/releases/download/v0.1.0/cusy-vale.zip

[*]
BasedOnStyles = Readability
```

See [Packages](https://vale.sh/docs/topics/packages/) for more information.

## Repository Structure

<dl>
  <dt><code>./styles/config/vocabularies/</code></dt>
  <dd>The vocabularies allow us to maintain customised terminology lists independently of our cusy style.</dd>
  <dt><code>./styles/cusy-de/</code></dt>
  <dd>Our rules to enforce the cusy editorial guide in German.</dd>
</dl>

See the [Vale documentation](https://vale.sh/docs/) for more information.
