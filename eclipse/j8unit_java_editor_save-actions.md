[x] Perform the selected actions on save
    [x] Format source code
        (o) Format edited lines

[x] Organize imports

[x] Additional actions

+++++++++ Configure... +++++++++
"Code Organizing" -> "Formatter"
    [x] Remove trailing whitespace
        (o) All lines
    [x] Correct indentation

"Code Organizing" -> "Members"
    [ ] Sort members

"Code Style" -> "Control statements"
    [x] Use block in if/for/do statements
        (o) Always
    [x] Convert 'for' loops to enhanced

"Code Style" -> "Expressions"
    [x] Use parentheses in expressions
        (o) Always

"Code Style" -> "Variable declarations"
    [x] Use modifier 'final' where possible
        [x] Private fields
        [x] Parameter
        [x] Local variables

"Code Style" -> "Functional interface instances"
    [x] Convert functional interface instances
        (o) Use lambda where possible

"Member access" -> "Non static accesses"
    [x] Use 'this' qualifier for field accesses
        (o) Always
    [x] Use 'this' qualifier for method accesses
        (o) Always

"Member access" -> "Static accesses"
    [x] Use declaring class as qualifier
        [ ] Qualify field accesses
        [ ] Qualify method accesses
        [x] Change all accesses through subtypes
        [x] Change all accesses through instances

"Missing Code" -> "Annotations"
    [x] Add missing Annotations
        [x] '@Override'
            [x] Implementations of interface methods (1.6 or higher)
        [x] '@Deprecated'

"Unnecessary Code" -> "Unused code"
    [x] Remove unused imports
    [ ] Remove unused private members
    [ ] Remove unused local variables

"Unnecessary Code" -> "Unnecessary code"
    [x] Remove unnecessary casts
    [ ] Remove unnecessary '$NON-NL$' tags
    [x] Remove redundant type Arguments (1.7 or highter)
 
