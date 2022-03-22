## Command Descriptions

### generateMake \<filename\>
generates a make file for Haskell to be run with the make command
compiler options are intended for 

  ex: `generateMake haskellCode`

### md \>dirname\>
creates a new directory using the provided name and navigates into it
NOTE: md must be run in the current process using the source (.) operator

  ex: `. md newfolder`
