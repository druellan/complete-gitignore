# Definitive .gitignore

Sometimes, when starting a new project, you need to be absolutely sure that you are not forgetting to include something on the .gitignore file. Many editors have an annoying tendency for storing sensitive data on the root and, if you are not careful, this information can end on a public repository (check [this Ars Technica article](http://arstechnica.com/security/2013/01/psa-dont-upload-your-important-passwords-to-github/) if you don't believe me).

This list is by no means complete, but it is a good default to include in your first commit. It is also not intended to be used as is, since file extensions could collide with other files on your project. Just delete the sections you know you are not going to use.

#### You know a filename/filetype that needs to be on the list?
Fork it! And send me a pull request. I'm interested on files that can contain sensitive information, but the list also includes many temporal and trash files.
