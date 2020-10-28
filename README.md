# Professional Summary

Engineering professional with 4 years of experience in Software development.
Mastering/Leading in the development of applications/tools using Python for 4+ years.
Worked on several python packages like FastApi, Django, Flask etc..
Good Experience in C/C development of multi-threaded applications in a Linux Environment.
Good Experience in debugging the issues using debuggers like gdb, pdb.
Familiarity with development best practices such as code reviews and unit testing.
Experience with Version Control, ideally SVN, CVS and GIT.
Experience in writing test plans, test cases, test specifications and test coverage.
Leading, guiding and helping the team members with the challenges faced during the project development process and problem solving.
Have flexibility and ability to learn and use new technologies and also to work in team environment as wells as independently to get things done.


# Technology Skills

- Languages: C, go, python, AT&T Assembly language
- Operating Systems: Linux, MAC, Docker, GCP, AWS
- Developer Tools: Vim, GCC, Make, SSH, Atom, pyCharm
- Databases: MySQL, Redis, Mongo, Elastic
- Programming Methodologies: Waterfall, Iterative
- Debuggers: gdb, pdb
- Code maintenance Tools: CVS, GIT
- Server: Nginx, uwsgi, asgi
- Markup Languages: Html and XML
- Other: k8s, compose

# Professional Experience

**Project:** Application to inject errors in memory

The project is to develop an application which injects different kinds of errors in the memory/memory interface and performs reads to see if the error gets corrected by the hardware.

_Responsibilities:_

1. Understood the injection mechanism of the memory hardware and developed several flows that needs to be implemented.
2. Developed framework to inject single, double and multiple bit injections
3. Developed the application in C language in Linux environment
4. Came up with several options to the application to support one shot injection, continuous injection to mimic the real world scenario.
5. Checked out the hardware correction algorithm by running with different memory patterns
6. Maintaining the application revisions using CVS
7. Wrapper developed in Python to run this application along with other applications
8. Ported the application from Linux to Windows

_Environment:_ C, Python, Linux, Windows, CVS, gdb

Python 

> QPI Quick Path Interconnect is a point-to-point processor interconnect developed by Intel replacing the shared FSB technology. It is a five layer architecture. The physical layer is the lowest level which has the actual wiring to connect to the other peer agents. The task involved in checking out the various flows in physical layer initialization, functionalities and error handling.








<details>
  <summary>点击时的区域标题</summary>
```
这是折叠的代码1
这是折叠的代码2
```
</details>



### Responsibilities:

> Individual contributor in understanding the QPI physical layer spec and developing the test algorithms using the processor hooks and get them reviewed
Implementation of the test algorithms in focused tool with self-checking methodology
Sanitization of the test by running in RTL, previous generation processors
Execution of the tests on the silicon and finding the bugs in the physical layer functionality
Development of test framework using the Python
Development of Assembly instructions for initializing the processor
Automation for execution of tests in batch using Shell scripting
Environment: Python, Assembly language, Shell scripting, SVN

Confidential

Virtualization Technology is the latest technology in the upcoming processors which allows processor to support virtualization for different virtual machines. This is the emerging technology which helps to run multiple OS on single Processor. The validation of this feature is a difficult task which involved in developing algorithms to check the processor behavior while switching among different virtual machines/OSs.

### Responsibilities

> Lead the team in developing the test algorithms for covering all the scenarios during the virtual machine switching
Implementation and sanity check of tests by running on previous generation processors
Sanitization and debugging the failures during the execution of tests on the new Processor
Enhancing the tests to support 16 threads and run in MP environment
Development of user-defined data structures and library functions using C and C languages
Intel compilers to generate test objs using Assembly language and user- defined data structures
Debugging using the gdb and hardware break points
Environment: C, C , Assembly Language, SVN

Confidential

RAS features are the critical in server market. Missing of any error condition validation will directly impact the Intel Server market segment. These features are spread across all the processor components. This project involved in developing the test conditions for generating the specific scenarios by injecting the errors using different processor defeatures/hooks for validating the processor behavior in error handling/reporting.

### Responsibilities

> Development of the test plan to cover all the RAS features
Preparation of the test conditions/scenarios which cause the errors similar to real world scenarios seen during the Processor execution
Implementation of procedures across the various validation tools that enable to cause the error conditions in Server Processor and process of self-checking
Guided Intern to implement handlers to handle the error condition seen in Processor
Execution of the tests developed on the processor and figure out the anomalies in the error flows
Developed generic framework for RAS test development using XML
Developed user defined error handlers using C language
Developed tests for focused test environment tool for creating various error conditions using C and assembly language
Environment: XML, C, Assembly Language

Confidential

Fuses are the PROM bits in processors which are programmable at the sort. The Fuses are used for enabling/disabling certain features in the Processor at the time of manufacturing. Now these fuses have been moved on to flash ROM on the package which can be flashed many times. The fuses gets downloaded on to the processor during the booting. This project involved in developing tool for implementing the process of flashing the fuses on ROM multiple times.

### Responsibilities:

> Understand the fuse layout in the flash ROM
Came up with the different usage models for flashing the ROM with different values and documented the same in the Product Release Documentation.
Developed Fuse tool using Perl based on usage model from several teams.
Supported the issues seen in the tool across all the teams till the product launch.
Enhanced the tool and supported for 3 generations of the processors
Graphical User Interface development using Tcl/Tk which provides various usage models/options to user by exposing several buttons
Maintaining user data using Microsoft Excel
Backend scripting/parsing using Perl and Python
Enhanced the GUI using Java APIs and added features to tracking the fuse revision of several processors
Environment: Perl, Python, Tcl/Tk, Microsoft Excel, Java

Confidential

This project involved developing the framework for System Validation debug tools and coverage tools for FSB based Server Multi Processors. It involved debugging test failures which involved figuring out whether the test failure seen is silicon/environment issue. It involved taking FSB traces using Logic Analyzer to analyze the processor behavior at the failure point and report to the design team for rout causing the failure behavior.

### Responsibilities:

> Proposed Breakpoint and Array Dump tool for debug which reduces the time to debug
Interacted with designers to discuss various flows of debug and coverage methods, design the tool framework
Implemented and validated these tools which helped in getting the functional coverage and triaging the failures quickly
Development of Python APIs to dump the array structures in the Processor at the failure point for debugging
Development of the break point tool using Perl and Java User Interface
Documented the simulation steps for debug using Shell scripting
Environment: Perl, Python, JavaScript, Shell scripting

## Confidential

This project involved in debugging the failures seen in execution of focused tests for the validation of features like cache coherency, power management, legacy core features. The tests are run with different configurations and defeatures across the platforms repeatedly for certain hours to figure out the issues seen during the stress testing.

## Responsibilities:

> Leading the team members to look into all the failures seen in execution and categorize to various signature buckets
To conduct the debug team meetings and providing directions to the team for the next level debugging of the different failure signatures to environment/silicon/BIOS issues
Debugging the failure issues by capturing the array and register dumps using Python scripts, traces and performing several experiments by interacting with the design team
Perl Scripts for bucketing the failures
Automating the hardware flow using the batch files and shell scripting
Usage of several internal debug tools for the root cause of the failure
Maintaining the scripts using the SVN version Control
Environment: Perl, Python, shell scripting, SVN

## Confidential

This is new technology introduced with QPI based Intel processors. This technology introduced the NUMA architecture. Each processor can be connected with set of memory modules and are interconnected with other processor. This NUMA architecture involves complex flows of RAS features like Mirroring, Migration, Patrolling, scrubbing, device correction. It involves developing framework to generate memory reads and writes and several error conditions to checkout memory controller features.

## Responsibilities:

> Understand the memory controller functionality and developing the test plan for covering the memory controller functionalities
Developing/Running the stress test in C to cover the memory controller flows, DIMM manufacturers and NUMA architecture
Developing the Python APIs which represent the memory subsystem.
Lead the team in development of the harassers using the Python which involved development of several flows and state machines in the memory controller.
Launching harasser across several threads along with memory stress test using the python wrapper.
Lead the team regarding the failure signature, debugging using Python.
Debugging/Root-causing the failures issues by capturing the DDR3/DDR4 traces using Logic analyzers
Running and debugging the Python harassers on the Linux environment
## Environment: C, Python, Linux

## Project: Validation and Debug environment tool for Intel next generation processor debug

Intel next generation Processor has several components which need to function properly. Each component has several registers with different fields which can be read and programmed for knowing the behavior/functionality. This project involved in developing tool which abstracts the components, several registers, fields and descriptions to the user and provides user friendly debug environment. The tool should be comprehensive enough to hide the confidential and IP of the Intel so that it is given to customers which help in debugging the customer issues.

## Responsibilities:

> Understanding the several Processor components
Analyzing the data in design database.
Maintaining the data with different levels of access privileges
Coordinating with the design team members to provide the data in required format
Collecting the several usage models and functions from the team members
Developing and maintenance of the tool that abstracts the information for the user
Parsers written in Python for extracting useful data from the design data base.
Development of XMLs for several components which maintains data for several registers
Development of data structures, xml parsing using Python.
Usage of advance features like pickle/unpickle in python for sharing the information across the applications
Representation of the system in hierarchy form by defining the components, subcomponents using Python and developed set of library functions over the system based on the user needs.
Development of several Python APIs and harassers that works both in Linux and windows and maintaining them using the revision control SVN
## Environment: Perl, Python, XML, SVN



Python Developer

### Responsibilities:

> Understand the business process variants and created the process flow for automating the adhoc request.
Working closely with team members in developing the PowerShell scripts for automating the several steps in Microsoft HDinsight environment.
Developed the map-reduce flows in Microsoft HDInsight hadoop environment using python.
Explored different implementations in hadoop environment for data extraction and summarization by using packages like Hive, Pig.
Developed Hive UDFs and Pig UDFs using Python in Microsoft HDInsight environment.
Reporting the issues and resolve the issues that arise out of the testing process with different type of systems.
Environment: Python, Powershell, Hive, Pig

Golang

### Responsibilities:

> Developed several algorithms for generating several data patterns
Added several options to the application to choose particular algorithm for data and address generation.
Developed separate flows to support different kinds of memory access
Developed the application using C language and Assembly instructions
Maintaining the versions using CVS and sending the release notes for each release.
Wrapper developed in Python for instantiating multi-threaded application and running with other applications
Supported the issues seen in the tool across all the teams for several projects.

Environment: C, Assembly Language, CVS, Python, Linux, gdb







### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dropthemasquerade/dropthemasquerade.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
