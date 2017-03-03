---
theme: simple
---

## Version control with `git`

Joel Goop

2017-03-09

---

## General version control

----

### A sequence of changes

![Diff sequence.](img/basic_diffs.png) <!-- .element: style="border: none; background: none; box-shadow: none" -->



---


## Git basics

----

### What is `git`?



----

### Concepts 1

- Repository
    + Working copy
- Staging <!-- .element: class="fragment" data-fragment-index="1" -->
- Commit <!-- .element: class="fragment" data-fragment-index="2" -->
    + Message
    + Hash
    + Tag

<aside class="notes">
    Explain each concept.
</aside>


----


### Concepts 2

- Branch
    + Merge
- Remote <!-- .element: class="fragment" data-fragment-index="1" -->
    + Clone
    + Push/pull

<aside class="notes">
    Explain each concept.
</aside>

----

### Basic usage

- Important commands
    + `git init`: Creating a repository
    + `git add`: Stage files for commit
    + `git commit`: Committing
- Ignoring files <!-- .element: class="fragment" data-fragment-index="1" -->
    + Add to the file `.gitignore`: 
      ```
      *.pdf
      stuff/
      ```

<aside class="notes">
    Show example repository.
</aside>

---

## Useful features

----

### `git diff`: What has changed?

Show the changes between any two commits or between current working copy and last commit

```diff
public class Hello1
{
   public static void Main()
   {
-      System.Console.WriteLine("Hello, World!");
+      System.Console.WriteLine("Rock all night long!");
   }
}
```

<aside class="notes">
    Show in example repository.
</aside>

----

### `git log`: History

```bash
commit af26e9204f344b4ed5afb1e8fbbbc528dc1f8d42
Author: Joel Goop <joel.goop@chalmers.se>
Date:   Wed Apr 20 14:18:11 2016 +0200

    Fix string compatibility with python 3

commit 8361852ca5672754a48fd3a22363031eb380f684
Author: Joel Goop <joel.goop@chalmers.se>
Date:   Wed Apr 20 13:03:48 2016 +0200

    Re-add relative imports
```

<aside class="notes">
    Show in example repository (and ELIN/EPOD?).
</aside>

---

## Linking to `bitbucket`/`github`

---

## Graphical interfaces

----

#### GitKraken

![GitKraken screenshot.](img/kraken.png)

----

#### SourceTree

![SourceTree screenshot.](img/sourcetree.png)
