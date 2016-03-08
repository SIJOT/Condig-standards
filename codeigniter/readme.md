# Codeigniter Coding Standards

The codeigniter coding standards used on the old codeigniter repo's. 

## Table of Contents

- [PHP Style Guide]()
  - [File Format]()
    - [TextMate]()
    - [BBEdit]()
  - [PHP Closing Tag]()
  - [File Naming]()
  - [Class and Method Naming]() 
  - [Variable Names]()
  - [Commenting]()
  - [Constants]()
  - [TRUE, FALSE and NULL]()
  - [Logical Operators]()
  - [Comparing return values and typecasting]()
  - [Debugging code]()
  - [Whitespace in Files]()
  - [Compatibility]()
  - [One File per Class]()
  - [Whitespace]()
  - [Line Breaks]()
  - [Code indenting]()
  - [Bracket and Perentic spacing]()
  - [Localized text]()
  - [Private Methods and variables]()
  - [PHP Errors]()
  - [Short Open Tags]()
  - [One statement per line]()
  - [Strings]()
  - [SQL Queries]()
  - [Default Function Arguments]()
  
## File format

Files should saved with Unicode (UTF-8) encoding. The BOM should *not* be used. 
Unlike UTF-16 and UTF-32, there"s no buyte order to indicate in a UTF-8 encoded file, 
and the BOM can have a negative side effect in PHP of sending output, 
preventing the application from being able to set its own headers. Unix line endings should be used (LF).

Here is how to apply these settings in some of the more common text editors. Instructions for your text editor may vary; check your text editor’s documentation.

### TextMate

1. Open the Application Preferences. 
2. Click Advanced, and then the “Saving” tab
3. In “Default text encoding for new documents”, select “Unicode (UTF-8, no BOM)”
4. Optional: In “If file’s encoding can’t be guessed, use”, select “Unicode (UTF-8, no BOM)”
5 .Select “Text Files” on the left.
6. In “Default line breaks”, select “Mac OS X and Unix (LF)”

### BBEdit

1. Open the Application Preferences
2. Select “Text Encodings” on the left.
3. In “Default text encoding for new documents”, select “Unicode (UTF-8, no BOM)”
4. Optional: In “If file’s encoding can’t be guessed, use”, select “Unicode (UTF-8, no BOM)”
5. Select “Text Files” on the left.
6. In “Default line breaks”, select “Mac OS X and Unix (LF)”

