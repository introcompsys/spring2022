# KWL Chart


<!-- ```{important}
This is not currently complete but will contain a listing with links to recommendations
``` -->

(kwlworkflows)=
## Working with this repo

```{important}
- Treat your main branch as what will "published" if you choose to use this as a portoflio of sorts.  
- The feedback branch should only contain material that has been reviewed and approved by the instructors.
```

````{margin}
```{tip}
You could apply branch protections on your feedback branch if you like
```
````

You may mix these workflows as long as feedback only contains work that has been reviewed and approved.

### Workflow 1

1. When you are working on things that are not ready for feedback make a
new branch to work on them.  
1. If you are working on things that you want feedback on right away you can work directly on main.
1. When work is ready for feedback merge it into main
1. Create a pull request from main into feedback.
1. When PRs are approved, merge them into feedback

### Workflow 2

1. work on a specific branch
1. when it is ready for review, create a PR from the item-specifc branch to feedback.
1. when it is approved, merge into feedback, then merge feedback into main.


```{tip}
After your KWL repo is a jupyterbook, you may want to move your chart into a chart.md from the README. You could then put content from this section in the README to have an in-place reminder.
```

(kwlmin)=
## Minimum Rows




```Markdown
# KWL Chart


<!-- replace the  _ in the table or add new rows as needed -->

| Topic | Know | Want to Know | Learned |
| ------| ------- | ------ | ------- |
| Git | _ | _ | _ |
| GitHub | _ | _ | _ |
| Terminal | _ | _ | _ |
| IDE | _ | _ | _ |
| text editors | _ | _ | _ |
|file system | _ | _ |_ |
|bash | _ | _ | _ |
|abstraction | _ | _ | _ |
|programming languages | _ | _ | _ |
|git workflows | _ | _ | _ |
| git branches | _ | _ | _ |
| bash redirects | _ | _ | _ |
|number systems | _ | _ | _ |
| merge conflicts | _ | _ | _ |
| documentation | _ | _ | _ |
| templating | _ | _ | _ |
|bash scripting | _ | _ | _ |
| developer tools | _ | _ | _ |
| networking | _ | _ | _ |
|ssh | _ | _ | _ |
| ssh keys | _ | _ | _ |
|compiling | _ | _ | _ |
| linking   | _ | _ | _ |
| building | _ | _ | _ |
| machine representation  | _ | _ | _ |
| integers   | _ | _ | _ |
| floating point  | _ | _ | _ |
|logic gates | _ | _ | _ |
| ALU | _ | _ | _ |
| binary operations | _ | _ | _ |
| memory | _ | _ | _ |
| cache | _ | _ | _ |
| register | _ | _ | _ |
| clock | _ | _ | _ |
| Concurrency | _ | _ | _ |
```



## Added Files

```{list-table}
:header-rows: 1

* - file
  - content (link to instructions)
  - type (prepare/practice)
  - zone
  - date
* - README.md
  - the chart, (or usage)
  - default
  - all
  - 2022-01-25
* -  gitoffline.md
  - [reflection (extra exercises, add & commit out of order)](../notes/2022-02-01)
  - prepare (and practice)
  - grade free
  - 2022-02-01
* -  terminal.md
  - [reflection](../notes/2022-02-03)
  - prepare
  - grade free
  - 2022-02-03
* -  software.md
  - [examine a software project](../notes/2022-02-03)
  - prepare
  - grade free
  - 2022-02-03
* -  abstraction.md
  - [how you think about abstraction](../notes/2022-02-08) and [updates (and reconcilation)](../notes/2022-02-10)
  - prepare (practice)
  - grade free
  - 2022-02-10
* -  chart.md
  - [your chart (from README)](../notes/2022-02-08)
  - practice
  - grade free
  - 2022-02-08
* -  reorg.md
  - [ntoes/troubleshooting ](../notes/2022-02-08)
  - practice
  - grade free  
  - 2022-02-08
* -  stdinouterr.md
  - [ echo and redirect practice](../notes/2022-02-08)
  - practice
  - grade free
  - 2022-02-08  
* - hardwaresurvey.md
  - [challenges & reminders (more exercises)](../notes/2022-02-10) [reflection](../notes/2022-02-10)
  - prepare and (practice)
  - grade free
  - 2022-02-10
* - gitlog.txt
  - [git log output](../notes/2022-02-15)
  - prepare
  - graded
  - 2022-02-15
* - workflows.md
  - [compare git workflows](../notes/2022-02-15)
  - practice
  - graded
  - 2022-02-15
* -  gitplumbing.md
  - [map plumbing to porcelain (and memory device)](../notes/2022-02-17)
  - prepare (and practice)
  - graded
  - 2022-02-17
* -  gitunderstanding.md
  - [how your undersanding has changed](../notes/2022-02-17)
  - prepare
  - graded
  - 2022-02-17
* -  idethoughts.md
  - [notes on ide usage](../notes/2022-02-17)
  - prepare
  - graded
  - 2022-02-17
* -  numbers.md
  - [usage of nondecimal number systems (and number conversions)](../notes/2022-02-22)
  - prepare
  - graded
  - 2022-02-22
* -  hexspeak.md
  - [summarize & generate](../notes/2022-02-22)
  - prepare
  - graded
  - 2022-02-22
* -  gitstory.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - prepare
  - graded
  - 2022-02-24
* - gitstory2.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - practice
  - graded
  - 2022-02-24
* -  donotcommit.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - practice
  - graded
  - 2022-02-24
* -  jupyterbooktroubleshooting.md
  - [problems with jupyterbook](../notes/2022-03-01)
  - prepare
  - graded
  - 2022-03-01
* - templating.md
  - [how template based engines work](../notes/2022-03-01)
  - practice
  - graded
  - 2022-03-01
* - docs.md
  - [documentation ecosystem of a language other than python](../notes/2022-03-01)
  - prepare
  - graded
  - 2022-03-01
* - octal.md
  - [pracitce with octal numbers in file permissions](../notes/2022-03-08)
  - practice
  - graded
  - 2022-03-08
* - hpc.md
  - [reflect on HPC systems](../notes/2022-03-08)
  - practice
  - graded
  - 2022-03-08
* - ide.md
  - [featrures in most used ide](../notes/2022-03-24)
  - prepare
  - graded
  - 2022-03-24
* - languages.md
  - [compare two languages](../notes/2022-03-24)
  - prepare
  - graded
  - 2022-03-24
* - favoriteide.md
  - [compare three ides](../notes/2022-03-24)
  - practice
  - graded
  - 2022-03-24
* - `gcctips.md`
  - [c compilation notes](../notes/2022-03-31)
  - prepare
  - graded
  - 2022-03-31
* - `operators.md`
  - [operators in programming and math](../notes/2022-03-31)
  - prepare
  - graded
  - 2022-03-31
* - `bitwise.md`
  - [practice with bitwise operations](../notes/2022-04-05)
  - prepare
  - graded
  - 2022-04-05
* - `readingbytes.md`
  - [review how reading bytes works](../notes/2022-04-05)
  - prepare
  - graded
  - 2022-04-05
* - `overflow.md`
  - [compare integer overflow](../notes/2022-04-05)
  - prepare
  - graded
  - 2022-04-05
* - `overflow.md`
  - [compare integer overflow](../notes/2022-04-05)
  - practice
  - graded
  - 2022-04-05
* - `cdouble.md`
  - [c program with double comparison](../notes/2022-04-07)
  - prepare
  - graded
  - 2022-04-07
* - `readingbytes.md`
  - [c program with double comparison](../notes/2022-04-07)
  - practice
  - graded
  - 2022-04-07
* - `floatexp.md`
  - [c program with double comparison](../notes/2022-04-07)
  - practice
  - graded
  - 2022-04-07
* - `multiplication.md`
  - [interpret mulitplication as addition](../notes/2022-04-12)
  - prepare
  - graded
  - 2022-04-12
* - `addertypes.md`
  - [compare adders](../notes/2022-04-12)
  - practice
  - graded
  - 2022-04-12
* - `systemsabstractions.md`
  - [reflect on an article](../notes/2022-04-14)
  - prepare
  - graded
  - 2022-04-14
* - `history-<event>.md`
  - [summarize and evaluate an aspect of computer history](../notes/2022-04-14)
  - practice
  - graded
  - 2022-04-14
* - `hardwaremap.md`
  - [visualize current hardware knowledge](../notes/2022-04-14)
  - practice
  - graded
  - 2022-04-14
* - `systemsprogramming.md`
  - [learn about systemsvs application programming](../notes/2022-04-19)
  - prepare
  - graded
  - 2022-04-19
* - `timing.md`
  - [experiment with timing of operations](../notes/2022-04-19)
  - practice
  - graded
  - 2022-04-19
* - `kernelproc.md`
  - [check your processes](../notes/2022-04-19)
  - practice
  - graded
  - 2022-04-19
* - `singlevmultithread.md`
  - [compare single vs multi threaded program](../notes/2022-04-21)
  - prepare
  - graded
  - 2022-04-21
* - `systeminteraction.md`
  - [compare systems libraries in multiple languages](../notes/2022-04-21)
  - practice
  - graded
  - 2022-04-21
* - `whymultithread.md`
  - [learn more applications of threads](../notes/2022-04-21)
  - practice
  - graded
  - 2022-04-21
* - `review.md`
  - review questions from class [April 26](../notes/2022-04-26) AND [April 28](../notes/2022-04-28)
  - prepare
  - graded
  - 2022-04-26
* - `filesystem.md`
  - [compare and contrast the two file systems we saw in class](../notes/2022-04-26)
  - practice
  - graded
  - 2022-04-26
* - `whypointers.md`
  - [explain why the concept of pointers is important with examples](../notes/2022-04-26)
  - practice
  - graded
  - 2022-04-26
* - `skillup.md`
  - [Reflect on how thise course impacts programming/debugging skills](../notes/2022-04-26)
  - practice
  - graded
  - 2022-04-26
* - `surprisingfacts.md`
  - [explain contradictions we saw](../notes/2022-04-28)
  - practice
  - graded
  - 2022-04-28
* - `projectplanning.md`
  - [compare languages and git workflows](../notes/2022-04-28)
  - practice
  - graded
  - 2022-04-28
```
