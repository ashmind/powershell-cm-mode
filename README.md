powershell-cm-mode
==================

Powershell mode for CodeMirror

Now it actually works!

What it has:

  1. All standard PowerShell syntax
  2. Highlighting of built-in functions and variables (e.g. Test-Path or Write-Warning)
  3. Highlighting of string interpolation in single-line strings
  
What it does not have:

  1. Highlighting of string interpolation in here-strings
  2. Any special handling of attributes (e.g. `[switch]` would be highlighted as a keyword in braces)