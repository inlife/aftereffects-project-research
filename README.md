# aftereffects-project

Researching the Adobe After Effects project template file format/data.

## Description

The purpose of this repo, is to share and possibly invite people to collaborate to the research of Adobe After Effects' project and project template file formats.
As you possibly know, you can export Ae project to the XML format, which will give you some sort of easy to read human friendly format. However it won't.
If you open it, you will see a tonn of not very descriptive tag names, followed by binary attributes. Data is there, but we just need a way to read it and write it.

A long-term goal is to create a definition/description of the format, and build tools to work with this format, like **standalone** readers/generators/editors, etc.

Contributions are highly welcomed! :)

## References

There is a project, that uses internal AE scripting, to read up javascript data of the project into json: [Jam3/ae-to-json](https://github.com/Jam3/ae-to-json).
That json data, can be used as reference to understand what types of values to expect there and there.

There are few other links to help:

* <https://help.adobe.com/en_US/AfterEffects/9.0/WS10B33022-CCC9-4db9-B893-4481C7A0AF44a.html>
* <http://docs.aenhancers.com/general/project/>
* <https://download.macromedia.com/pub/developer/aftereffects/scripting/After-Effects-CS6-Scripting-Guide.pdf>
* <http://www.aenhancers.com/viewtopic.php?t=1256>
* <https://stackoverflow.com/questions/24596482>

## Structure

Repo consists maily markdown files and few other things, like actual project files, and maybe some tools.

 * [Project](project.md)
 * [Fold](fold.md)
 * [Item](item.md)
 * [Composition](composition.md)
 * [Layer](layer.md)
