# Duke QCD bibliography

The Duke QCD group's master bibtex database.

If you are developing a paper in a git repository, the bibliography may be included as a git subtree.  This
will include the file and enable pulling in future changes.

Add this repository as a remote:

    git remote add Bibliography https://github.com/Duke-QCD/Bibliography.git

Now add the subtree:

    git subtree add --squash --prefix duke-qcd-refs Bibliography master

Later, the bibliography may be updated with

    git subtree pull --squash --prefix duke-qcd-refs Bibliography master
