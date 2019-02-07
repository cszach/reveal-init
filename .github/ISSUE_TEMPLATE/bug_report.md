---
name: Bug report
about: Create a bug report
title: ''
labels: ''
assignees: ''

---

Description
-----------

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

    - Operating system: Your operating system with release number and
    (optionally) operating system family (e.g. Ubuntu 18.10 GNU/Linux)
    - Shell interpreter: All Shell interpreters (and their versions) that, when
    the steps to reproduce are done, the bug gets triggered (e.g. bash 4.4.21)
    - Program version: All versions of `reveal-init` that have the bug (e.g 1.0,
    1.1 Alpha, 1.1-rc) (hint: run `reveal-init --version`)
-->

- **Operating system**:
- **Shell interpreter**:
- **Program version**:
