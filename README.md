# ReType
Compile types metadata from TypeScript sources so it could be used in runtime for type validation and reflection

## How
Utilizing TypeScript's AST support to extract types metadata and output it into a dedicated file. Similar to the way sourcemaps work. A complementary file with all types and thier type info will be outputted as JS file, which in turn can be imported into web application and used to properly reflect and check runtime objects against registered types.
As inspiration think about how VS Code editor identifies written objects in source files and can link them back to thier definition.
  
  
[More info TBD].
