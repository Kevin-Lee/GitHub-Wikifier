### What is GitHub Wikifier?

This is a script that will generate all the Table of Contents for your GitHub Wiki's.

All you need to do is stick with a directory structure (Subjects), and add files inside.

The script comes in form of a pre-commit hook, which will generate the Table of Contents for
each subject and append them to the your given commit. 

It generates:

1. A complete Table of Contents at `Home.md`
2. A root file for each subject (directory) available.
3. A `_sidebar.md` for each subject (directory) available.
4. A Label for files that are empty: (PENDING)

#### You can see an example here: 