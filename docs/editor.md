# Editor

## Margins

### Line Numbers

When enabled, displays the index number of each document line.

If word wrap is also enabled, the index number will span a taller area for wrapped lines.

Line Numbers can be enabled/disabled in the [View](menus.md#line-numbers) menu.

### Bookmarks

When enabled, displays a clickable margin for marking document lines. Useful when working on very long document, and you need to scroll back to a specific line(s).

Bookmarks can be enabled/disabled in the [View](menus.md#bookmarks) menu.

### Code Folding

When enabled, displays `+` and `-` symbols to expand/collapse code blocks.

Code Folding can be enabled/disabled in the [View](menus.md#code-folding) menu.

## Find & Replace

A panel to perform finding and replacing operations.

See the [Find & Replace](find-and-replace.md) page for details.

## Indicators

### Errors

Code errors are underlined with red squiggles.

### Matches from Find

[Find](find-and-replace.md) matches are highlighted in orange.

### Object Highlight

Highlights all usages of the object under the text caret.

## Indicator Map

This replaces the standard vertical scrollbar. It displays the indicator marks for the entire document.

The Indicator Map can be enabled/disabled in the [View](menus.md#indicator-map) menu, or with ++ctrl+m++.

## Go To Definition

Pressing the ++f12++ key goes to the definition of the object under the text caret.

If it is a Type defined in the .NET Framework, the associated page on docs.microsoft.com is open.

If it defined in the current document (for example a variable), the text caret is scrolled to that position.

## Rename Variable

When renaming an existing variable, a dotted box will appear around the variable, and will provide access to the light bulb menu. The light bulb menu has an option to rename all instances of that variable.

## Tooltips

Display information of the Object at the location of the mouse cursor, such as: Type, Return type, Member type, namespace, ect.

If there is an error at the location of the mouse cursor, then the error message is displayed instead.
