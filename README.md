## Command Descriptions

### generateMake \<filename\>
Generates a make file for Haskell. Compiler options are intended for the [CIS 194](https://www.seas.upenn.edu/~cis194/spring13/lectures.html) course, but they are suitable for most simple use cases.

Note: Do not include the file extension in the *filename* arument

`generateMake haskellCode`

### md \<dirname\>
Creates a new directory using the provided name and navigates into it

NOTE: md must be run in the current process using the source (.) operator

`. md newfolder`
