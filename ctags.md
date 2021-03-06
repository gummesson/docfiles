# ctags

[Ctags](http://ctags.sourceforge.net/) generates an index (or tag) file of
language objects found in source files that allows these items to be quickly and
easily located by a text editor or other utility.

## Configuration

### Add support for a language

```
--langdef=markdown
--langmap=markdown:.md
--langmap=markdown:+.txt
--regex-markdown=/^#{1,6}[ \t](.*$)/\1/h,heading,headings/
```

## Usage

### Generate tags recursively

```
ctags -R .
```

## Patterns

- [JavaScript](https://github.com/romainl/ctags-patterns-for-javascript)
