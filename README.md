# FlightGearDeepDive  
## Flightgear is a Complex Program

FlightGear is an extensive application with features written in C++, the Nasal scripting language, and data files in various formats.
Understanding the internals is somewhat daunting, simply because of its size and complexity. 
For example, examining classes in the FlightGear/SimGear codebase reveals nearly 2000 classes. 
One hundred of the classes represent the operation of individual sub-systems within Flightgear. 
Overall, there are more than 2500 individual sourcefiles in FlightGear and SimGear, 
split about evenly between header and non-header c++ files.

Because the application is so large and has a lengthy and complex development history, 
you need to establish some basic information quickly and then focus on a 
specific area of the application to acquire sufficient information to become helpful to the project.

To acquire the essential information you'll need before jumping into the deep end of the pool, 
one may need to look at the FlightGear materials from a few different perspectives. 
But you may be the type of person to just jump in. If so, come back later 
to take a look at any section of this material that interests you.

My intent is not to write in detail about every aspect of the program, 
but to provide a summary and outline information one can use to work 
effectively in a specific area.  These should provide information to
work across C++ code, Nasal Scripts, XML and other data on specific tasks. 
It should include information on the Flightgear materials and tools needed to explore and work on them.  

Initially, most of them will be short outlines with notes references 
to specific files, folders.  They'll aim to identify the major classes and highlight 
important relationships and flows of data and process between them.

Your work is to do a bit of reading, a bit of stepping through code, some reading of data and getting whatever task you've taken on in the Flightgear realm done.

One of the primary tools for investigation will be the gdb debugger, and we'll use scripts that can be
run within the debugger to highlight specific parts of FlightGear. The scripts are intended to make specific features easy to navigate through by providing breakpoints and notes about what to look for or examine closely.

another tool will be a Libre Office spreadsheet, listing FlightGear behaviors for exploration across the code, scripts and data involved in specific flightgear behaviors.

A Flightgear run script is provided, capable of running flightgear with or without a debugger, using gdb or gdbgui.  I use the same run script for flying.without starting a debugger.


