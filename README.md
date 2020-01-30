# J8Unit :: Developer Settings

Hi there,

if you want to support the j8unit team you should be aware of the code styles, conventions and formatter rules.

In order to keep the code consistent, to prevent encoding problems, to understand new code more quickly and thoroughly,
to avoid arguing over syntax, naming standards, and style preferences
[we must insist on consistent code](https://www.google.de/search?q=coding+style+matters).

Avowedly, good style is a subjective matter and the perception of beauty is subjective.
However, these are the rules which we think are fine for us:

## Eclipse ([2019-12](https://projects.eclipse.org/releases/2019-12))

- Window -> Preference -> General -> Editors -> Structured Text Editors -> Task Tags
    - Settings according to [J8Unit Task Tags](./eclipse/j8unit_general_editors_structured-text-editors_task-tags.md)
- Window -> Preference -> General -> Workspace
    - Settings according to [J8Unit Workspace Settings](./eclipse/j8unit_general_workspace.md)
- Window -> Preference -> Java -> Code Style -> Clean Up
    - Import the [J8Unit Clean-Up Profile](./eclipse/j8unit_java_code-style_clean-up.xml)
- Window -> Preference -> Java -> Code Style -> Formatter
    - Import the [J8Unit Code Formatter Profile](./eclipse/j8unit_java_code-style_formatter.xml)
- Window -> Preference -> Java -> Code Style -> Organize Imports
    - Import the [J8Unit Import Order](./eclipse/j8unit_java_code-style_organize_imports.importorder)
    - Further settings according to [J8Unit Organize Imports](j8unit_java_code-style_organize_imports.md)
- Window -> Preference -> Java -> Editor -> Save Actions
    - Settings according to [J8Unit Save Actions](./eclipse/j8unit_java_editor_save-actions.md)
- Window -> Preference -> XML -> XML Files -> Editor
    - Settings according to [J8Unit XML Files](./eclipse/j8unit_xml_xml-files_editor.md)

## Maven

Preliminarily, Maven runs much smarter with [Maven Bash Auto Completion](https://github.com/juven/maven-bash-completion).

Further, we (most of the time) respect the
[Maven's convention over configuration concept](http://books.sonatype.com/mvnref-book/reference/installation-sect-conventionConfiguration.html).
In particular, we use the
[Standard Directory Layout](http://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html).
