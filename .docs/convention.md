# Convention

## Directory & File

Directory and file names are encouraged to resemble normal sentences. except in the following cases:

> - [Image](#image)

### Image

The image directory, named **images**, should be placed at the same level as the Markdown files that reference it.

Image file names should use **snake_case** and should not consist of random strings. If a name is duplicated, add a number at the end.

Image files are recommended to be in **PNG** format.

```txt
- Databases
    - Data Backup.md
    - images
        - backup_and_resotre.png
    - PostgreSQL
        - images
            - postgres_logo_1.png
            - postgres_logo_2.png
            - postgres_logo_3.png
        - Syntax.md
```

## Markdown

### Tag

The Tags section should use a level 2 heading (`##`) and be placed above the [Reference](#reference) section.

Tags must be in **lowercase** and may include spaces. Each tag should be separated by a space.

`java` `kotlin` `spring boot`

### Reference

The Reference section should use a level 2 heading (`##`) and be placed at the bottom of the document.
