# bioinformatics-tool

## THE SMALL TOOLS **MANIFESTO** FOR BIOINFORMATICS

This **MANIFESTO** describes motives, rules and recommendations for designing software and pipelines for current day biological and biomedical research.

Large scale data acquisition in research has led to fundamental challenges in scaling of calculations, full data integration and data interaction and visualisation. We think that, because of researchers reaching out to turn-key solutions, the research community is losing sight of the importance of building software on the shoulders of giants and providing solutions in a modular, flexible and open way.

This **MANIFESTO** counters current trends in bioinformatics where institutes and companies are creating monolithic software solutions aimed at end-users. This **MANIFESTO** builds on the Unix computer tradition of providing small tools that can be used in a modular and pluggable way to create efficient computational solutions where individual parts can be easily replaced. The manifesto also encounters current trends in software licensing which are not truly free and open source (FOSS). We think such a **MANIFESTO** is necessary, even though history suggests that software created with true FOSS licenses will ultimately prevail over less open licenses, including those licenses that are for academic use only.


* Small tools for bioinformatics* is concerned about the reinvention of the wheel across research projects and for example the lack of reproducible scripted solutions in sequencing pipelines.

* Small tools for bioinformatics* is all about small collaborating tools and software solutions in the Unix tradition.

* Small tools for bioinformatics* allows the building of modular solutions where individual tools can easily be understood, tested and replaced.

* Small tools for bioinformatics* creates free and open source software, shares software solutions, and encourages transparency and reproducibility of results.

* Small tools for bioinformatics* is a rescue plan and forward looking central effort to bring together solutions suitable for big data analysis and create ways of having these tools interact with each other.


The following simple rules apply to anyone signing up to *Small tools for bioinformatics*
* Every single tool should do the smallest possible task really well

* Every single tool lives in its own public source code repository

* All tools are free and open source software (FOSS) and come with a license approved by the Free Software Foundation (FSF).

* Source code should be easy to read and understand by any competent software developer.

* Error conditions and exceptions should be descriptive and handled in a clear way.

* When possible tools should support (Unix) pipes

* When possible tools provide a useful command line interface

* Tools should avoid system dependencies, such as named (absolute) file paths

* Every single tool comes with a simple build protocol, at least for Linux

* Software installation and deployment dependencies are handled through external package management systems

The following are recommendations:

* Use distributed revision control and sites promoting social coding for hosting source code such as Github.

* Provide a package definition for the [GNU package system](https://www.gnu.org/software/guix/) (GUIX).

* All tools that match the criteria of the **MANIFESTO** will be part of the standard bioinformatics pipelines across the world.











































