# Study Journal Template

88888

The repo is now mine. Prepare for an onslaught of notes.

To Publish:  
* Type "./scripts/publish.sh" from terminal in your Journal directory

Concepts GitBook:
* Your GitBook will look [something like this](https://elewa-academy.github.io/study-journal-template/).

Quizzes:
* This is the [quiz plugin](https://github.com/chudaol/gitbook-plugin-quiz). The quizzes will be live and interactive on your journal's url.

Directory Structure Explained:
```
study-journal
|-- /xx-yy_aa-bb
|   * A folder for each week, labeled by date
|   * There will be one file per day, that day's notes
|   * Or maybe one file every few days. you'll find what works
|
|-- /concepts
|   * Contains one file for each important concept
|   * You get to decide what these are
|   * Each one of these will become a page in your GitBook
|   * These will link to the days you studied that topic
|
|-- /docs
|   * The publis.sh script will buid the GitBook into this folder
|   * GitHub Pages will build from this folder
|
|-- /node_modules
|   |-- /gitbook-plugin-collapsible-chapters
|   |-- /gitbook-plugin-quiz
|   |-- /jquery
|   |-- /underscore
|
|-- /quizes
|   * You will have one integrated quiz for each conept
|   * The quizes will be built with gitbook-plugin-quiz
|   * You will add to these quizes regulary as you learn more about this concept
|
|-- /scripts
|   |-- build.sh    - Build the GitBook into /docs without publishing
|   |-- publish.sh  - Build & push the new notes GitBook to GitHub
|   |-- serve.sh    - Preview your GitBook at localhost:4000 without building
|
|-- .gitignore  - Tell Git not to push your node_modules folder to GitHub
|-- book.json   - A file written in JSON format that configures your GitBook
|-- CONTRIBUTING.md - Guidelines for people who'd like to contribut to your notes
|-- LICENSE.md  - A license, so people can respect your wishes
|-- README.md   - The "cover page" of your repo & GitBook
|-- SUMMARY.md  - Determines what will show up in your GitBook index


```


___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
