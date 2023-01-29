# git-cherry-pick

## Commits log

Main branch there is four commits named as "A", "B", "C", "D".

Develop branch there is six commits named as "A", "B", "E", "F", "G", "H".

Develop branch is created from the after commit "B" of the main branch. After that ther is three new commits as "E", "F", "G".

## cherry-pick

Main branch cherry-pick the commit "E" and "G" from the develop branch.
After cherry pick there is another two commits named as "E" and "H".

### cherry-pick commands

```git cherry-pick <hash>```

```git cherry-pick -e <hash>```

In the above command you can edit the commit message. So commit message is shown as below.

![cherry-pick-edit](https://user-images.githubusercontent.com/52546856/215348576-161ae805-9e27-45ac-8eef-7166ac4b5cb8.png)

Here "H" is the commit message in the develop branch. This message was added "cherry-pick edit message (git cherry-pick -e <hash>)" when edit the message.
