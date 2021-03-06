#Reference-en#
Reference-en is the repo for the Language Reference documentation of the Arduino syntax in **English**.  
All the Reference terms files are in AsciiDoc format. Manutius, the Arduino platform to manage and publish content, turns Asciidoc documents into HTML pages, PDFs, and more.

Thank you for taking the time to contribute to Arduino content, this is really helpful to the whole Arduino Community.

##Content Creation and Editing##
If you want to contribute new content, create a new file (with any text or code editor) and save it as .adoc.  
Do not use parenthesis or any special character in the file name.  
In refernce-en/AsciiDoc_sample/AsciiDoc_Dictionary you will find an overview on the AsciiDoc syntax in use on the Manutius platform. This includes Titles, Text, Links, Images, Tables, Code and various embeds (video, slideshow, audio and code).

If you want to contribute to the Language Reference or edit existing content, you can find two templates in reference-en/AsciiDoc_sample/Reference_Terms:
* Use AsciiDoc_Template-Single_Entity.adoc for terms such as [`analogWrite`](http://arduino.cc/en/Reference/AnalogWrite).
* Use AsciiDoc_Template-Parent_Of_Entities.adoc for groups of functions such as [`Serial`](http://arduino.cc/en/Reference/Serial).

Please note that every Reference file should include as least a Description, some Example Code, and links to other relevant infos (See Also section). 

If you need to add images to the Asciidoc please create a folder called attachments in the same directory as the Asciidoc file. Images can be saved in SVG and PNG format, max size 200KB.

##Contribute Content on Github##
If you are not familiar with Git you can contribute content directly on Github via their online interface. [Follow this guide](https://help.github.com/articles/editing-files-in-another-user-s-repository/) to learn how to edit an .adoc file and propose a file change to the Arduino team.  
When suggesting a change, please follow the guidelines described in the Reference template files.

##Folder Structure
```
reference-en
├─ AsciiDoc_sample
│   ├── AsciiDoc_Dictionary
│   │   ├── AsciiDoc_Template-Dictionary.adoc
│   │   └── attachments
│   └── Reference_Terms
│       ├── AsciiDoc_Template-Parent_Of_Entities.adoc
│       ├── AsciiDoc_Template-Single_Entity.adoc
│       └── attachments
├── Language
│   ├── Functions
│   ├── Structure
│   └── Variables
├── LICENCE.md
└── README.md

```

Within the Language folder, the file tree follows the same structure as in the [Arduino Reference webpage](http://arduino.cc/en/Reference/HomePage).
