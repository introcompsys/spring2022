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
```



## Added Files

```{list-table}
:header-rows: 1

* - file
  - content (link to instructions)
  - type (prepare/practice)
  - zone
* - README
  - the chart, (or usage)
  - default
  - all
* -  gitoffline.md
  - [reflection (extra exercises, add & commit out of order)](../notes/2022-02-01)
  - prepare (and practice)
  - grade free
* -  terminal.md
  - [reflection](../notes/2022-02-03)
  - prepare
  - grade free
* -  software.md
  - [examine a software project](../notes/2022-02-03)
  - prepare
  - grade free
* -  abstraction.md
  - [how you think about abstraction](../notes/2022-02-08) and [updates (and reconcilation)](../notes/2022-02-10)
  - prepare (practice)
  - grade free
* -  chart.md
  - [your chart (from README)](../notes/2022-02-08)
  - practice
  - grade free
* -  reorg.md
  - [ntoes/troubleshooting ](../notes/2022-02-08)
  - practice
  - grade free  
* -  stdinouterr.md
  - [ echo and redirect practice](../notes/2022-02-08)
  - practice
  - grade free  
* - hardwaresurvey.md
  - [challenges & reminders (more exercises)](../notes/2022-02-10) [reflection](../notes/2022-02-10)
  - prepare and (practice)
  - grade free
* - gitlog.txt
  - [git log output](../notes/2022-02-15)
  - prepare
  - graded
* - workflows.md
  - [compare git workflows](../notes/2022-02-15)
  - practice
  - graded
* -  gitplumbing.md
  - [map plumbing to porcelain (and memory device)](../notes/2022-02-17)
  - prepare (and practice)
  - graded
* -  gitunderstanding.md
  - [how your undersanding has changed](../notes/2022-02-17)
  - prepare
  - graded
* -  idethoughts.md
  - [notes on ide usage](../notes/2022-02-17)
  - prepare
  - graded
* -  numbers.md
  - [usage of nondecimal number systems (and number conversions)](../notes/2022-02-22)
  - prepare
  - graded
* -  hexspeak.md
  - [summarize & generate](../notes/2022-02-22)
  - prepare
  - graded
* -  gitstory.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - prepare
  - graded
* - gitstory2.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - practice
  - graded
* -  donotcommit.md
  - [tutorial of using git for a challenge](../notes/2022-02-24)
  - practice
  - graded
* -  jupyterbooktroubleshooting.md
  - [problems with jupyterbook](../notes/2022-03-01)
  - prepare
  - graded
* - templating.md
  - [how template based engines work](../notes/2022-03-01)
  - prepare
  - graded
* - docs.md
  - [documentation ecosystem of a language other than python](../notes/2022-03-01)
  - prepare
  - graded
* - shell_scripting.md
  - [Basic Shell Scripting](../notes/2022-03-03)
  - prepare
  - graded
* - remote_server.md
  - [How to access and work on a remote server](../notes/2022-03-08)
  - prepare
  - graded
* - ssh_basics.md
  - [Creating ssh keys and using them](../notes/2022-03-10)
  - prepare
  - graded
* - gccnotes.md
  - []

```
