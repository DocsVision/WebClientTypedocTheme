# Typedoc theme for WebClient JavaScript API.

See it in action [there](https://docsvision.github.io/WebClient-JsDocApi/index.html).

Read more about typedoc [there](https://github.com/TypeStrong/typedoc).

Theme contains:
1. Fixed show inherited/protected checkboxes;
2. Original dark header;
3. Hidden source file link in symbol description;
4. Hidden TOC for index;
5. Other small modifications.

Typical documentation building command:

    typedoc --theme WebClientTypedocTheme  --name "Docsvision 5 Web-client. JavaScript API"  --readme ..\README.md --includeDeclarations --excludePrivate --mode file --entryPoint WebClient --excludeExternals --logger none --ignoreCompilerErrors --out ../docs TypeScriptDefinitions/