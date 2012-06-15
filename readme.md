# Consolify

A .NET library which allows quickly adding a command-line interface to your existing apps.  It uses reflection and some cleverness to figure out what you want to do.  It is attribute-free, although I do plan to add some minimal configuration via a Fluent API.

## Future Plans

* Mono support.

## Other Projects

* [ManyConsole](https://github.com/fschwiet/ManyConsole) - An extension to NDesk.Options for writing console applications with multiple commands.  More flexible but requires more work/coding.
* [TaskRunner](https://github.com/kristofclaes/TaskRunner) - Use attributes to delineate tasks which can then be run from the command line.