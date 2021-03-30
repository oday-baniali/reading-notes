# read02b
  Git is a *DVCS* that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the database

Staged

Flagged a file’s changed version to be committed in the next snapshot

The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit.
Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.
