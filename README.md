# Test_009
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Initial Commit
* Commit updating ReadMe
* Commit Before Merging Feature Branch conflicting with Feature
* Commit Merging the feature and the main brnach

## Changes Made In This Repo

* Create a feature branch from main and make a commit on that branch.
* Create a second commit on the main branch.
* Create a sub-feature branch based on the feature branch and make a commit on the sub-feature branch
* Make a commit on the sub-feature that will conflict with feature.
* Make a commit on the feture branch that also conflicts with sub-feature
* Then merge it with the sub-feature branch using a PR. Resolve conflicts
* Create a third commit on the main branch that conflicts with the sub feature branch.
* Create multiple on the feature branch and then  merge the feature branch with the main branch without PR.
* Create a commit on feature branch that updates the expected result JSON and use a PR to merge the 2.
