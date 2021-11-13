# URVCS

Your Simple Version Control System(URVCS) is an experimental, lightweight and simple version control solution.

## Releases

### For Windows

https://google.com

## Installation Guide

1) Download the release.
2) Extract it to any desired location(Eg: C:\URVCS).
3) Add URVCS to PATH.

## Usage Guide

### Initialize

To use URVCS in your project, you will need to initialize the project.

#### Syntax

> urvcs init project_directory

#### Example

> urvcs init MyProject

### Commit

To make a commit.

#### Syntax

> urvcs commit "Commit message."

#### Example

> urvcs commit "Added index file."

### Log

View all the commits.

#### Syntax

> urvcs log

#### Example

> urvcs log

### Tag

Tag a certain commit.

#### Syntax

> urvcs tag commit_id desired_tag

#### Example

> urvcs tag 17 "Release Build"

### Restore

Restore or fallback to any other build/commit/snapshot.

#### Syntax

> urvcs restore commit_id

#### Example

> urvcs restore 7

## FAQ

### Why does URVCS exist?

URVCS exists because I wanted to learn how version control works.

### Can URVCS replace Git or any other VCS?

No. Absolutely not. URVCS simply cannot stand against Git or any other VCS's features.

### Can URVCS be used for a project?

Absolutely. But, it is recommended that you go through the disclaimer first.

### What operating systems does URVCS support?

As of this time, only the Microsoft Windows operating system family is supported(tested on Microsoft Windows 10 and Microsoft Windows 11).

### Have any suggestions, and/or found any bug(s)/issue(s)?

Please feel free to contact me at hello@udayrajoriya.com.

## Disclaimer

URVCS is an experimental software, and hence it may behave unexpectedly. So, it is recommended that you first try it on a dummy project, experiment and check it's behavior then only move onto using it with any real projects.
