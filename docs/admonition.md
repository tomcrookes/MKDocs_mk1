# Admonitions

## Installation
in your `.yml` file, include:
```sql
markdown_extension:
    - admonition
```

to allow implemeting blocl-styled side content to your document. 


## Usage

For syntax, include 3 explamation marks followed my the style of markdown you want. Options include:
- note
- summary
- info
- tip
- success
- question
- failure
- warning
- danger
- bug
- quote

A physical example of each of these styles can be viewed at <a href= "https://yakworks.github.io/docmark/extensions/admonition/">this link</a>

## Syntax

Use 3 explamation marks followed by the keyword. the next line should be indentedd and contain the text inside the markdown.

Example:
```sql
!!! note
    This is a note.
```

!!! note 
    This is a note.

You can change the title of the note by including a quoted string following the keyword:

Example:
```sql
!!! note "My new note"
    This is a note.
```

!!! note "My new note"
    This is a note.

You can remove all titles by having no string in between the quotation marks.