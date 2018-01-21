# composition

Composition is the biggest tag in the project file, it stores information about it's layers, settings, camera related stuff, and much more.
It always has a string name as a second child tag, describing the name of the composition.

I has few "properly" named tags inside:

`<Layr>`, which reprensents single layer in the composition. If there are N layers in compsition, there will be N chidlren <Layr> tags for each layer.
`<SLay>`, which represents camera settings
`<CLay>`, which represents a custom view's

SLay and CLay both are related to this thing:

![](https://media.discordapp.net/attachments/339179416783421460/404615345828003843/unknown.png)

There are many more tags which i don't know meaning of, but i hope that's researchable :D
