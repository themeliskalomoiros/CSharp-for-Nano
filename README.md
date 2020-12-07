C# for Nano
======
**Syntax highlighting** for the C# language in the Nano editor.

```
syntax csharp "\.cs$"
magic "C# " 
comment "//"
color green "\<(bool|byte|sbyte|char|decimal|double|float|int|uint|long|ulong|new|object|short|ushort|string|base|this|void)\>" 
color red "\<(as|break|case|catch|checked|continue|default|do|else|finally|fixed|for|foreach|goto|if|is|lock|return|switch|throw|try|unchecked|while)\>" 
color cyan "\<(abstract|class|const|delegate|enum|event|explicit|extern|implicit|in|internal|interface|namespace|operator|out|override|params|private|protected|public|readonly|ref|sealed|sizeof|static|struct|typeof|using|virtual|volatile)\>" 
color red ""[^\"]*"" color yellow "\<(true|false|null)\>" 
color blue "//.*" 
color blue start="/\*" end="\*/" 
color brightblue start="/\*\*" end="\*/"
color brightgreen,green " +$"
```

## Usage
Append the configuration to `~/.nanorc` (create the file if it doesn't exist).
