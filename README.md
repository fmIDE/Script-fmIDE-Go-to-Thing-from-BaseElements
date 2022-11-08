![fmIDE Logo](https://raw.githubusercontent.com/wiki/fmIDE/fmIDE/images/fmide.png)
# fmIDE
[A FileMaker Integrated Development Environment]

[fmIDE](https://github.com/fmIDE/fmIDE) is a module for FileMaker files which it makes it possible for tools to 'deep link' into the FileMaker Development Environment.

# BaseElements

![BaseElements Logo](https://baseelements.com/wp-content/uploads/2016/05/logo_BaseElements.png)

[BaseElements](http://www.fm-crosscheck.com) is a FileMaker analysis tool from [Goya](https://goya.com.au/).

# Script "fmIDE-Go to Thing from BaseElements"

[The `fmIDE-Go to Thing from BaseElements` script](Script-fmIDE-Go-to-Thing-from-BaseElements.txt) is the bridge between BaseElements and your database solutions (using the [fmIDE-'Name-that-Thing' API](https://github.com/fmIDE/fmIDE/wiki/fmIDE-'Name-that-Thing'-API))

In one click it jumps from the thing you are currently looking at in BaseElements directly to that thing in your database.

# Installing

1. Get the tools
   - Get the [latest version of BaseElements](https://baseelements.com/downloads/) - get a free [trial licence](https://baseelements.com/free-trial/) or [purchase a licence](https://baseelements.com/buy-now/)
   - Get the [latest version of fmIDE](https://github.com/fmIDE/fmIDE/releases) - [free](http://fmworkmate.com/donate)

2. Prepare your databases for fmIDE-Integration
   - Follow the [fmIDE Installation instructions](https://github.com/fmIDE/fmIDE/wiki/Home#installing-fmide) to
     - paste the `fmIDE` script into your database files
     - tell fmIDE how you name your tables & layouts
     - tweak security
     

3. Prepare BaseElements for fmIDE-Integration
   - Create a new script in BaseElements named `fmIDE-Go to Thing`
     - (or  delete the existing script's contents if you are updating)
   - Paste the steps into it
     - Copy the xml contents of the [fmxmlsnippet.xml](fmxmlsnippet.xml) script steps file
     - Convert the xml to FileMaker objects with any FM-XML conversion tool like [fmWorkMate's fmCheckMate](https://github.com/mrwatson-de/fmWorkMate/releases/latest), or [fmAutoMate's PaXte function](https://github.com/mrwatson-de/fmAutoMate/releases/latest), or whatever your favourite clipboard conversion tool is.
     - Paste the steps into the script.

4. Perform a BaseElements analysis of your database
   - Create a DDR of your database
   - Import the DDR into BaseElements

5. Click, 💥 Bang! 👀 Goggle!
   - Navigate to any record in the analysis in BaseElements, for example to a script step
   - Run the "fmIDE-Go to Thing" script
     - or press the shortcut key
   - You suddenly find yourself (more or less) looking at that thing in FileMaker, for example in the Script Workspace editing the script at exactly the script step.

Cool? Find out more about [fmIDE](https://github.com/fmIDE/fmIDE/wiki)

Enjoy & be productive!

MrWatson

---

P.S. Do you have a developer tool you'd like to integrate closer into the FileMaker Developer environment? Learn More about the [fmIDE-'Name-that-Thing'-Project](https://github.com/fmIDE/fmIDE/wiki/fmIDE-'Name-that-Thing'-Project)
