# LanguageLearner
### ***A simple language learning aid to help anyone hoping to escape the fast impending coronavirus brexit apocalypse***

My intention in creating this application is to build a tool to practice a language. It is still at a very early stage, however I plan for it to take the form of a game a user can play. I would also like a user with administrator permissions to be able to alter the configuration and contents of the game without altering the codebase, in a manner that is persisted.

Although my initial description is admittedly vague in nature, this section will be updated as the nature and scope of the application becomes more clear. A kanban board of stories describing features in development can be found [here][kanban].

# Features

Currently in the earliest of possible stages. The application will build, and that's the extent of it's capabilities.

# Build

To build this application via the command line, clone or download the source code and navigate to the LanguageLearner directory, and then run the following command:

```bash
C:\Windows\Microsoft.NET\Framework\v4.0.30319\msbuild "LanguageLearner.sln" /P:Configuration=Release
```

# Run

To run the built console version of the project, navigate to the *LanguageLearner* directory and then run the following command:

```bash
start PresentationLayer\ConsoleView\bin\release\ConsoleView
```

# Development

# Project Links

- [Kanban Board][kanban]
- [Architectural Decisions][architecture] 



<!-- Links -->

[kanban]: https://github.com/ThomasCarling/LanguageLearner/projects/2
[architecture]: ArchitecturalDecisions.md