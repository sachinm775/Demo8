# Demo8
experiment8
<br>
To cherry-pick a range of commits from "source-branch" to the current branch, use the following command:

$ git cherry-pick <start-commit>^..<end-commit>

Replace <start-commit> with the SHA-1 of the first commit in the range and <end-commit> with the SHA-1 of the last commit. The ^ symbol excludes <start-commit> itself, applying all commits after it up to and including <end-commit>.

Example:
$ git cherry-pick ABC123^..DEF456

Ensure you are on the branch where you want to apply the changes before running this command.

