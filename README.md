# Monokai Theme for Netbeans

Originally based on https://github.com/sickill/vim-monokai/blob/master/colors/monokai.vim


## Colour Pallete
HEX                                             | COLOUR                | USAGE
----------------------------------------------- | --------------------- | -----
[f8f8f8](http://www.color-hex.com/color/f8f8f8) | Almost White          | Text foreground, Cursor Background
[75715e](http://www.color-hex.com/color/75715e) | Light Grey            | Comments, todo, code-folding foreground
[272822](http://www.color-hex.com/color/272822) | Dark Grey             | Editor background, search cursor foreground, whitespace
[23241e](http://www.color-hex.com/color/23241e) | Slightly Darker Grey  | My own IDE background
                                                |                       |
[49483e](http://www.color-hex.com/color/49483e) | Grey                  | Special? Text Colour
[3c3d37](http://www.color-hex.com/color/3c3d37) | Deeper Grey           | Special? Background, Highlighted instances
                                                |                       |
[66d9ef](http://www.color-hex.com/color/66d9ef) | Blue                  | Identifier, StorageClass, Constant
[a6e22e](http://www.color-hex.com/color/a6e22e) | Lime Green            | Function, Css Class/ID
[fd971f](http://www.color-hex.com/color/fd971f) | Orange                | Block param, CSS url
[ae81ff](http://www.color-hex.com/color/ae81ff) | Purple                | Boolean, Character, Floats, Numbers, Special Chars, CSS Colour, CSS Value Length
[f92672](http://www.color-hex.com/color/f92672) | Pink                  | Keyword, Operator, Statement, Class, Error/Warning bg
[e6db74](http://www.color-hex.com/color/e6db74) | Straw Yellow          | Search background, Strings, labels, document headers
                                                |                       |
[2a2815](http://www.color-hex.com/color/2a2815) | [Yellow/Background Mix](http://meyerweb.com/eric/tools/color-blend/#E6DB74:23241E:10:hex) | Warnings
                                                |                       |
[46830c](http://www.color-hex.com/color/46830c) | Forest Green          | Difference - Added Text BG
[2d3e19](http://www.color-hex.com/color/2d3e19) |                       | Debugging current caret
                                                |                       |
[8b0807](http://www.color-hex.com/color/8b0807) | Blood Red             | Removed Text Colour
[491a16](http://www.color-hex.com/color/491a16) |                       | Breakpoint
                                                |                       |
[243955](http://www.color-hex.com/color/243955) | Blue                  | Changed Text BG
[232e37](http://www.color-hex.com/color/232e37) |                       | Call stack



## Syntax Tab

 CATEGORY                   | LANGUAGE      | EXPLANATION
 -------------------------- | ------------- | -----------
 Default                    | All Languages |
 Argument                   | HTML          | <tag argument="value" />
 Block Comment              | HTML          |
 Abstract Class or Method   | All Languages |
 Character                  | All Languages |
 Character                  | HTML          | &nbsp;
 Class                      | All Languages |
 Code Coverage - Covered    | PHP           |
 Code Coverage - Inferred   | PHP           |
 Code Coverage - Partial    | PHP           |
 Code Coverage - Uncovered  | PHP           |
 Comment                    | All Languages |
 Comment                    | PHP           |
 Constructor                | All Languages |
 Deprecated Element         | All Languages |
 Deprecated Element         | PHP           |
 Documentation Keyword      | PHP           | PHP Doc Keyword
 Entity Reference           | All Languages |
 Enum                       | All Languages |
 Error                      | All Languages | PHP Syntax Errors
 Expression Delimiter       | HTML          | {{ expression }} - requires Angular plugin
 Field                      | All Languages |
 Field                      | PHP           | $instance->$field
 HTML Tag                   | PHP           |
 Heredoc Delimiter          | PHP           |
 Identifier                 | All Languages | {{ identifier }}, param="identifier"
 Identifier                 | PHP           | Class Name, Traits, Method names (overridden by method declaration/invocation) etc
 Interface                  | All Languages |
 Keyword                    | All Languages |
 Keyword                    | PHP           | class, function, public, extends, return, etc
 Line Comment               | PHP           |
 Local Variable             | All Languages |
 Magic Constants            | PHP           |
 Mark Occurrences           | PHP           | Auto-highlighting of other instances of same variable, etc
 Markup Attribute           | All Languages |
 Markup Value               | All Languages |
 Markup Element (Tag)       | All Languages |
 Method                     | All Languages |
 Method Declaration         | PHP           |
 Method Invocation          | PHP           |
 Method Parameter           | All Languages |
 Number                     | All Languages |
 Number                     | PHP           |
 Operator                   | All Languages |
 Operator                   | PHP           | ->, ::
 Parameter Value            | HTML          | <tag attr="value"/>, Inherits Identifier, Overriden by CSS Selector value?
 PHP Open/Close Tag         | PHP           |
 Private Element            | All Languages |
 Protected Element          | All Languages |
 Public Element             | All Languages |
 Separator                  | All Languages |
 Separator                  | PHP           | \ between class names, ; line termination, etc
 Static Element             | All Languages |
 Static Element             | PHP           | SomeClass::staticElement()
 String                     | All Languages |
 String                     | PHP           |
 Type Declaration           | PHP           | Class TypeDeclaration
 Url                        | All Languages |
 Unused Element             | All Languages |
 Unused Element             | PHP           |
 Var Doc Keyword            | PHP           | /** @var $foo Foo */
 Warning                    | All Languages | Potential syntax error
 Whitespace                 | All Languages | All whitespace, even between words



## Highlighting Tab

 Option                                             | Explanation
 -------------------------------------------------- | -----------
 Braces matching (match, multiple characters)       | <div></div>
 Braces matching (match, single character)          | if (true) { }
 Braces matching (mismatch, multiple characters)    | <div></span>
 Braces matching (mismatch, single character)       | if (false}
 Braces outline sidebar                             | [] indicator to show start/end of braces
 Caret Colour                                       |
 Caret Colour (Overwrite mode)                      |
 Code Folding                                       |
 Code Folding Bar                                   |
 Guarded Block                                      | ???
 Highlight Caret Row                                |
 Highlight Search                                   | All search occurrences highlighted