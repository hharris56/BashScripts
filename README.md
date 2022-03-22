## Command Descriptions

### generateMake \<filename\>
generates a make file for Haskell to be run with the make command
compiler options are intended for the [CIS 194](https://www.seas.upenn.edu/~cis194/spring13/lectures.html) course, but are suitable for most simple use cases.

Note: Do not include the file extension in the *filename* arument

`generateMake haskellCode`

### md \<dirname\>
creates a new directory using the provided name and navigates into it

NOTE: md must be run in the current process using the source (.) operator

`. md newfolder`
