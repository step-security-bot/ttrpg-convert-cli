# QuteBase

Defines attributes inherited by other Qute templates.

Notes created from `QuteBase` (or a derivative) will use a specific template for the type. For example, `QuteBackground` will use `background2md.txt`.

## Attributes

[hasSections](#hassections), [name](#name), [source](#source), [tags](#tags), [text](#text), [vaultPath](#vaultpath)


### hasSections

True if the content (text) contains sections

### name

Note name

### source

Formatted string describing the content's source(es)

### tags

Collected tags for inclusion in frontmatter

### text

Formatted text. For most templates, this is the bulk of the content.

### vaultPath

Path to this note in the vault