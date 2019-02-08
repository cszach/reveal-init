---
name: Bug report
about: Create a bug report
title: ''
labels: bug
assignees: ''

---

Description
-----------

<!-- Describe and specify the problem, the expected and actual behaviors. -->

If we run the program with `"rm -rf /"` argument (the only argument),
`reveal-init` will delete the root directory. However, it is expected that a
directory named "`rm -rf /`" will be created.

Steps to reproduce
------------------

```shell
su
reveal-init "rm -rf /"
```

Environment
-----------

<!--
    NOTE: Delete this comment when you're done.

    - Program version: All versions of `reveal-init` that have the bug (e.g 1.0,
    1.1 Alpha, 1.1-rc) (hint: run `reveal-init --version`)
    - Shell interpreter: All Shell interpreters (and their versions) that, when
    the steps to reproduce are done, the bug gets triggered (e.g. bash 4.4.21)

    Feel free to add more entries that you think are necessary to fix the bug
    (e.g. Operating system).
-->

- **Program version**:
- **Shell interpreter**:
