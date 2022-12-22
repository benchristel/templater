# Templater

Inserts content from STDIN into a template file, writing the result to STDOUT.

Usage:

```
echo Hello, world | template template.html
```

## Installation

You'll need `ruby`.

- Clone this repo.
- Put it on your `PATH`.
- You can now run `template`.

## Template format

`template` looks for the placeholder `$$1$$` in the template document and replaces it with the content from STDIN.

## Future features

Currently, `template` only supports a single placeholder. It could support multiple placeholders if the given content is in the [Verse format](https://github.com/benchristel/verse-format) (similar to the cookie-jar format described in _The Art of Unix Programming_.)
