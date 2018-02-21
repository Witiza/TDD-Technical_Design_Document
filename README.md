“I am [Lorién Portella López](https://www.linkedin.com/in/lori%C3%A9n-portella-2144b2159/), student of the
[Bachelor’s Degree in Video Games by UPC at CITM](https://www.citm.upc.edu/ing/estudis/graus-videojocs/). This content is generated for the second year’s
subject Project 2, under supervision of lecturer
[Ricard Pillosu](https://es.linkedin.com/in/ricardpillosu).”

## What's a Tech Design Document and why it is important

A TDD is a organic document created by a studio when facing a new project. Its function is to set standards to the coding style and structure, normalize workflows and data management, and have a list of all the software that will be used during the project with its purpose, while providing a general overview of the project to any member of the team. Even though the document is mainly used for coding and engineering purposes, it can fit the specific needs of the team such as acting as an art gallery, or including a calendar with the milestones.
Having your project well documented and the goals stablished since the beggining is essential, because without it, there will be conflicts and misunderstandings within the team, as everyone has their different ideas on how the game needs to be done, and when it needs to be finished. Also, as various programmers will be working on the same code, having a standarized coding style for everyone will ensure that sections of the code can be shared and exchanged between members without any problems.

# Differences between TDD and GDD

Both a Tech Design Document and a Game Design Document serve a similar purpose, explaining how the game is done. But unlike the GDD, that explains the mentioned game from a designer point of view, the TDD does it from an engineer point of view, explaining how mechanics should be coded, instead of how they are balanced, and, in general, leaving behind all the subjective points, and centering only in the engineering and technology behind the game.

# TDD Essential Sections
- Summary: Acts as an introduction to the TDD, and an overview of the project, both from design point of view and technology point of view.

- Goals and risks: 
When doing a project, in addition to explain what the project is about, it is important to talk and set the different goals of the team, as it will help
- Technical goals: Describe and give a small explanation for any new technology or code innovation that is going to be used in the project.
- Project goals: What the team wants to reach with this project. This goals can also be named "general goals", as they serve for the entire project.
- Finished project goals: Any improvements or additional content that could be implemented once the project goals have been acomplished.
When describing the goals, we also need to describe the risks or problems that this goals may cause. Since we are writing the TDD, a detailed description of the technical goals is key, in order to keep all the members aware, and help to detect this problems earlier.

- Hardware and Software: List of all the software that will be used, and its purpose. Aside from visual studio or engine software, this list should include programs such as Photoshop, Audacity, or even Excel. Also, the minimum and optimal hardware needed to run the game should be listed here. Because the TDD is an organic document, these requirements can be added in an update.

- Programming Policies: The core of the TDD, even more important as we are doing a project without using an engine. The level of specification is up to the team coders, but this section should include at least: 
  - UML: Various UML diagrams about the game structure and hierarchy (UI, entities, modules). The UML's should include the relevant functions that each module or class is going to use, and should be updated as the development of the game progresses.
  - Code style: Concepts such as variable and function naming, spacing or structure should be defined here, in order to keep the code homogeneous and readable.
  - Branching Policy: This section defines the frequency of the branches, and why they should be done.
  - Comment Policy: Description about when the code should have comments, and the nature of these.
  - Version Lists and Policy: How each version is going to be labelled, and when do versions change.
  - External Libraries: Which external libraries are going to be used, and their purpose.
  - Build Delivery Policies: Explain how each build is going to be delivered, which system is going to be used, the day they are going to be delivered and the team member.

- Data sharing: Specify the system that is going to be used to share data between the team members, including a description for each of the programs that are going to be used in each data type, and the organization of the mentioned data.

- File Formats and naming: Specify the different file formats that are going to be used when sharing data, and their purpose. Set rules to how files should be labelled. These can be as specific as the team desires. 

- Changelog: Page with all the changes to the TDD, the date, and the member that has done the changes.

## Additional Features
- Features from the GDD: A more extensive summary of the GDD, that includes features that might afect the development of the project

- Level layouts: The scheme of the different levels and how they should be navigated. Level specific code or other observations need to be mentioned here

- Asset lists: A list with the names and images(opional) of all the assets that will be used. Asset specific code or other observations need to be mentioned here.

- Development plan: A description of the development calendar and milestone plan of the team. Member-specifi tasks related to code can be described here.

- Definitions, acronyms and abreviations: All the previously mentioned should figure here with their meaning.

- References: All the other webpages or videogames used to elaborate the TDD.


