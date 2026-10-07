First Initial upload of Assignment 1 documents

The branching and merging workflow of our team was as follows:

each member would work on their own files, and upload or commit them to their own Dev branch. Promptly named "MemberName-Dev".

From here we would manage our own pull requests to main as we completed our work, and leave them in the pull requests menu until we were available to look over each change and manually merge them to main. This resulted in most of our merges lacking any conflicts or errors.

We did encounter one error (that we had to force) wherein we both worked on the same individual file in our dev branches, and created individual pull requests before either one was merged to main properly. This resulted in both being merged at once and the discrepancy between the files causing a merge conflict. We resolved this by looking at the errors in the conflict manager, and manually selecting the corrected changes, and merging them to main. Confirming once we were done.

As for our Strategy,

Blue Green would be the best system to use for our deployment. With our smaller size app and team, setting up monitoring tools and constantly monitoring with canary would take away resources from later feature development. We would minimize risks of downtime of the app if any issues were to present themselves, and with a focus on testing our features fully before deployment, we will be creating more trust in using our app from the users. We would have our stable release swap out with our tested recent release for all users and have user reporting continue with the existing feedback system we will use. We will be keeping the versions on two separate github branches for ease of development and rollback.

- Hayden and Austin
