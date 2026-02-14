# Graphs

A repository of graphs created using various technologies and database softwares.

## Obsidian Databases
Below is a render of a graph database made with Obsidian, based on my PSYCH 377 notes. Each note is a node on the graph, and each edge is a reference between two notes. 
For example, node (26.5)Tumors, mentions meningioma, which is a tumor originating in the meninges. This note contains an Obsidian backlink to the node (3.7)Meninges, creating an edge between them.

Furthermore, use of the "path" function in Obsidian allow me to organize nodes by chapter. Visually, each node is colour-coded according to the chapter to which it belongs.
For example, Ch3_NervousSystemOrganization, is coloured red (rgb(224, 82, 82)), while Ch13_OccipitalLobesAndNetworks, is coloured pink (rgb(224, 82, 117)).
Seamless integration of the nodes on the graph render allows the user to recognize how chapters connect at a glance.

Lastly, notes/nodes such as my to-do lists, while part of the vault, were excluded from the render by going through settings to "Files and links" then the "Advanced" tab, and adding the "Misc" folder under "Excluded files."

<img width="1793" height="1535" alt="PSYCH377_GraphDatabase" src="https://github.com/user-attachments/assets/760e6db8-a65e-43c5-b24b-81e84a6ad70a" />

## Graphs in R

I've siphoned data from a CSV databse into an R project created using JupyterColab through Google Colab.
I then visually rendered the data to form a graph which showcases the progression of my current manuscript (work in progress).

![Manuscript_WordCount_2025](https://github.com/user-attachments/assets/7d5d7126-b303-47f3-9e55-af812b7ea0e5)
