# Gedit Rails Extensions

Here are some extensions for Ruby/Rails developers using gedit.


## Install

The contained Makefile installs the MIME packages and syntax files to the system directories.

    sudo make install

For manually installing MIME packages:

    sudo cp <package>.xml /usr/share/mime/packages/
    sudo update-mime-database /usr/share/mime
 
For manually installing syntax files (.lang):

    sudo cp <syntax>.lang /usr/share/gtksourceview-2.0/language-specs/
    sudo cp <syntax>.lang /usr/share/gtksourceview-3.0/language-specs/

Restart gedit if it's already running.


## MIME packages

rails.xml:

- RHTML Template (*.rhtml, *.erb)
- Ruby JavaScript (*.rjs)
- Ruby Rakefile (Rakefile)
- Ruby Rake Task (*.rake)
- Ruby XML Template (*.rxml, *.builder)
- YAML Document (*.yml)
- Haml Template (*.haml)
- Sass Stylesheet (*.sass)


## Language Specs

- haml.lang: Specs for the Haml templating language
- rhtml.lang: Specs for the old Ruby HTML file type
- sass.lang: Specs for the Sass Stylesheet language 
