# Github Finder

This is the second Independent project for Moringa Core, angular project.
The project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12

## Description
Github Finder is a web application that uses the GitHub API to perform searches on GitHub and display the results to the user.

## Author
Morrison Njenga

## Features

1. Uses the Github API to perform searches on Github, and display the results to the users.
2. Users page searches for user profile strictly using the user name.



## Behaviour Driven Development

| Behaviour | Input | Output |
| --------- | ------| ------ |
|Show github profile|Enter the Username in the search box and cick `search`|Displays name, username, bio, number of repositories, Hireable, date of creating the repo, followers, following and public gists|
|Search gitub repositories | Navigate to Repos page click on `Repositories` and type the name of repository.|Displays a list of 10 repositories based on the query|
|Load more search Results	|Click `Load More` button on the Find Repos page |Adds 10 more results in the search results|
|Redirect to github profile on Github website | Click the `view on github` button of a Github user | Opens the profile on the Github website|
|Redirect to a specific Github Repository | Click the `view on github` button of a repository on repositories page | Opens the Repository on Github website |


## Known Bugs
There are no known bugs. Contact me if you find.

If you find a bug (the website couldn't handle the query and or gave undesired results), kindly open an issue here by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.


## Technologies Used
It is built using Angular JS, HTML, Bootstrap.
The website uses components, custom directives, custom pipes, routing modules.
The components in the application are:

## Contribute

To fix a bug or enhance an existing module, follow these steps:
- Fork the repo
- Create a new branch (git checkout -b improve-feature)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (git commit -am 'Improve feature')
- Push to the branch (git push origin improve-feature)
- Create a Pull Request

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.



## License
---------
### MIT License

Copyright (c) [2021] [Morrison Njenga Githinji]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


### Contact Information
morrison.githinji@student.moringaschool.com


