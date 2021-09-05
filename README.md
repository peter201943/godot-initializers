

[![MIT License](https://img.shields.io/github/license/peter201943/InStructEd.svg?style=flat)](https://opensource.org/licenses/MIT)
[![Godot Engine](https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=flat&logo=godot-engine&color=grey)](https://godotengine.org/)

[![Initializers Logo](resources/logo.png)](https://github.com/peter201943/godot-initializers)


# Godot Initializers


Experimenting with different ways of initializing Custom Nodes in Godot


## Contents
- [Contents](#contents)
- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Vocabulary](#vocabulary)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
  - [Primary Maintainer](#primary-maintainer)
  - [Project](#project)
- [Acknowledgements](#acknowledgements)


## About

Experimenting with different ways of initializing Custom Nodes in Godot.
Expanding upon [InStructEd](https://github.com/peter201943/InStructEd)'s JSON data structure.
Also exploring better interfaces in Godot for these kinds of constructions.

### Built With
[Godot](https://godotengine.org/)


## Getting Started

### Prerequisites
[Godot v3.3.3](https://godotengine.org/download)

### Installation
1. Clone the Repo
  ```bash
  git clone https://github.com/peter201943/InStructEd.git
  ```
2. "Import" the Project from Godot's Launcher

### Usage
Visit each "method" folder (numbered) and press `F6` to launch the scene to test it.


## Vocabulary

(TODO Resolve difference of "used in" and "part of" and problems inherent therein with sorting combinators into categories)

### Accept
Existing property requiring no work to take advantage of.  
Includes None.  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Add
Work required to enable something else.  
Includes None.  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Assignment
How a structure is built.  
Includes [Exported Variable Assignment](#exported-variable-assignment), [Node Tree Assignment](#node-tree-assignment), [Scene Expansion Assignment](#scene-expansion-assignment).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Automatic Feedback
User can immediately see consequences of a change.  
Includes None.  
Part of [Feedback](#feedback).  
Uses None.  

### Briefly
Quickly describe something.  
Includes None.  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Code Complexity
How difficult something is to implement.  
Includes [High Code Complexity](#high-code-complexity), [Low Code Complexity](#low-code-complexity), [Medium Code Complexity](#medium-code-complexity), [No Code Complexity](#no-code-complexity).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Consequence
Happens as a result of other factors. Can be deliberate or incidental.  
Includes None.  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Difficult Error Recovery
Changes that are hard to revert.  
Includes None.  
Part of [Error Recovery](#error-recovery).  
Uses None.  

### Easy Error Recovery
Changes that require only some or no work to revert.  
Includes None.  
Part of [Error Recovery](#error-recovery).  
Uses None.  

### Exported Variable Assignment
Using the inspector to refer to members of a tree. Medium intensity edits.  
Includes None.  
Part of [Assignment](#assignment).  
Uses None.  

### Error Recovery
How hard it is to recover from a mistake and revert a change.  
Includes [Difficult Error Recovery](#difficult-error-recovery), [Easy Error Recovery](#easy-error-recovery), [Impossible Error Recovery](#impossible-error-recovery).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Feedback
Seeing immediate effects/easily understanding what the consequences of a change are.  
Includes [Automatic Feedback](#automatic-feedback), [Inherent Feedback](#inherent-feedback), [No Feedback](#no-feedback).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Final Setup
Last steps taken before a node is ready.  
Includes [No Final Setup](#no-final-setup), [Script Final Setup](#script-final-setup).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Heavy User Ceremony
User must perform several repeated steps to achieve a change.  
Includes None.  
Part of [User Ceremony](#user-ceremony).  
Uses None.  

### High Code Complexity
Something that is difficult to make.  
Includes None.  
Part of [Code Complexity](#code-complexity).  
Uses None.  

### Impossible Error Recovery
Changes that cannot be reverted.  
Includes None.  
Part of [Error Recovery](#error-recovery).  
Uses None.  

### Includes
Subtypes to a Vocabulary Term.  
Includes None.  
Part of [Vocabulary Properties](#vocabulary-properties).  
Uses None.  

### Inherent Feedback
User can immediately see consequences of a change inherently from pre-existing conditions.  
Includes None.  
Part of [Feedback](#feedback).  
Uses None.  

### Low Code Complexity
Something that is relatively easy to make.  
Includes None.  
Part of [Code Complexity](#code-complexity).  
Uses None.  

### Low User Ceremony
User must perform few repeated steps to achieve a change.  
Includes None.  
Part of [User Ceremony](#user-ceremony).  
Uses None.  

### Medium Code Complexity
Something that requires some difficulty to make.  
Includes None.  
Part of [Code Complexity](#code-complexity).  
Uses None.  

### Method Design Properties
Used to measure each goal of this project. Explicitly designed for.  
Includes [Assignment](#assignment), [Code Complexity](#code-complexity), [Error Recovery](#error-recovery), [Feedback](#feedback), [Final Setup](#final-setup), [User Ceremony](#user-ceremony).  
Part of [Methods](#methods), [Roadmap](#roadmap).  
Uses [Accept](#accept), [Add](#add), [Briefly](#briefly), [Consequence](#consequence).  

### Methods
Goal of this project is to implement each of these.  
Includes [Method 1](#method-1), [Method 2](#method-2), [Method 3](#method-3), [Method 4](#method-4), [Method 5](#method-5).  
Part of None.  
Uses [Method Design Properties](#method-design-properties).  

### No Code Complexity
Something that requires no effort to make.  
Includes None.  
Part of [Code Complexity](#code-complexity).  
Uses None.  

### No Feedback
There is no indication of the consequences of a change.  
Includes None.  
Part of [Feedback](#feedback).  
Uses None.  

### No Final Setup
No further steps are needed for the structure.  
Includes None.  
Part of [Final Setup](#final-setup).  
Uses None.  

### No User Ceremony
User must not perform any repeated steps to achieve a change.  
Includes None.  
Part of [User Ceremony](#user-ceremony).  
Uses None.  

### Node Tree Assignment
Building a tree through regular assembly of a scene tree. Low intensity edits.  
Includes None.  
Part of [Assignment](#assignment).  
Uses None.  

### Part Of
One things is used by another to describe it.  
Includes None.  
Part of [Vocabulary Properties](#vocabulary-properties).  
Uses None.  

### Scene Expansion Assignment
Extensively modifying the scene tree instead of building a tree. High intensity edits.  
Includes None.  
Part of [Assignment](#assignment).  
Uses None.  

### Script Final Setup
Further steps are needed for the structure, done through code.  
Includes None.  
Part of [Final Setup](#final-setup).  
Uses None.  

### User Ceremony
Work required on the user's part to make this thing work.  
Includes [Heavy User Ceremony](#heavy-user-ceremony), [Low User Ceremony](#low-user-ceremony), [No User Ceremony](#no-user-ceremony).  
Part of [Method Design Properties](#method-design-properties).  
Uses None.  

### Uses
One things uses another.  
Includes None.  
Part of [Vocabulary Properties](#vocabulary-properties).  
Uses None.  

### Vocabulary
Describes ideas as seen throughout this project.  
Includes [All](#vocabulary).  
Part of None.  
Uses [Vocabulary Properties](#vocabulary-properties).  

### Vocabulary Properties
The properties which capture the basic semantic relationships between terms relative to this project.  
Includes [Includes](#includes), [Part Of](#part-of), [Uses](#uses).  
Part of [Vocabulary](#vocabulary-2).  
Uses None.  


## Roadmap

### [x] Basic GitHub Setup
- Project
- Readme

### [x] Advanced GitHub Setup
- Very Detailed Readme

### [ ] Basic Godot Setup
- Project Files
- Exports
- Folders

### [ ] Advanced Godot Setup
- Copy Files from InStructEd

### [ ] Method 1 
- Briefly build up scenes manually using *Instance Child Scene*, *Expand Child Nodes*, *...*
- Accept Scene-Expansion-Assignment
- Consequence No-Final-Setup
- Consequence Difficult-Error-Recovery
- Consequence Inherent-Feedback
- Consequence Heavy-User-Ceremony
- Consequence No-Code-Complexity

### [ ] Method 2 
- Briefly describe structure in terms of scene-tree nodes and construct the intended structure *after* scene is running
- Accept Node-Tree-Assignment
- Add Init-Final-Setup
- Consequence Script-Final-Setup
- Consequence No-Feedback
- Consequence Easy-Error-Recovery
- Consequence Low-User-Ceremony
- Consequence Low-Code-Complexity

### [ ] Method 3
- Briefly describe structure in terms of inspector exported variable assignments
- Add Exported-Variable-Assignment
- Add Init-Final-Setup
- Consequence Script-Final-Setup
- Consequence No-Feedback
- Consequence Easy-Error-Recovery
- Consequence No-User-Ceremony
- Consequence Medium-Code-Complexity

### [ ] Method 4
- Briefly describe structure in terms of scene-tree nodes and immediately act upon any changes, permanently, do not use any hidden nodes to render anything
- Accept Node-Tree-Assignment 
- Add Tool-Mode-Preview-And-Setup
- Consequence No-Final-Setup
- Consequence Inherent-Feedback
- Consequence Impossible-Error-Recovery
- Consequence Heavy-User-Ceremony
- Consequence High-Code-Complexity

### [ ] Method 5
- Briefly describe structure in terms of scene-tree nodes but render consequences of arrangement in editor using hidden ui nodes
- Accept Node-Tree-Assignment 
- Add Tool-Mode-Preview 
- Add Init-Final-Setup
- Consequence Script-Final-Setup
- Consequence Automatic-Feedback
- Consequence Easy-Error-Recovery
- Consequence No-User-Ceremony
- Consequence High-Code-Complexity


## Contributing
This is a low-priority project for @peter201943 and as such pull requests are not likely to be accepted.
You will be better served by forking it and continuing development of it on your own.


## License
Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.


## Contact

### Primary Maintainer
Peter James Mangelsdorf  
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=flat&logo=microsoft-outlook&logoColor=white&label=peter.j.mangelsdorf)](mailto:peter.j.mangelsdorf@outlook.com)  
[![Discord](https://img.shields.io/badge/%3CServer%3E-%237289DA.svg?style=flat&logo=discord&logoColor=white&label=peter201943%238017)](https://discord.com/)  
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white&label=peter201943)](https://github.com/peter201943/)  
[![Itch.io](https://img.shields.io/badge/Itch-%23FF0B34.svg?style=flat&logo=Itch.io&logoColor=white&label=peter201943)](https://peter201943.itch.io/)  

### Project
Godot Initializers  
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white&label=peter201943%2Fgodot-initializers)](https://github.com/peter201943/godot-initializers)  


## Acknowledgements
None, currently.




