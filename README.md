# snippetsCss

The main goal of this little project is to provide a usefull package of [snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_creating-your-own-snippets) for CSS developers. This package will save you a lot of time by providing you with many shortcuts for common code structures in css such as comments, initial reset of the document, creation of classes with predefinity properties  and so on.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Be sure to have [Visual studio code](https://code.visualstudio.com/download) installed.


### Downloading
If you just need to use the Snippets just clone the repository. Then you will find 2 files:

A JSON file with all the css Snippets: `snippetsCss.code-snippets`
A BAT file to help you get the JSON into the right directory: UpdateSnippetsCssIntoLocal.bat
Execute the BAT file by double clicking or from Bash by running:
```
./UpdateSnippetsCssIntoLocal.bat
```
This will create/replace the snippetsCss.code-snippets file in the right directory so that Visual Studio Code would be ready to use it. Now you are ready to open a CSS file and type 'css' as main keyword and start seeing all availabe Snippets.

### Contributing
If you are an CSS developer and want to propose new Snippets to be added into this project please feel free to:

Fork
Create a new local branch with your specific change.
Create a pull request so that I can review it and merge it into `development` branch. Eventually it will be merge into `ready` branch to be used.
