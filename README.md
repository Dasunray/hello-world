By default my repository has one branch named main which is considered to be the definitive(අවසාන,නියත,ස්ථිර) branch. 
People can use branches to experiment and make edits before committing them to main definitive(අවසාන,නියත,ස්ථිර) branch

After several branches has been made. Say we edit the main branch by typing something like this. Then, when you try to do pull requests, that means merge the branches to the main, the GitHub says “can't automatically merge”?

Let's say there is your-branch and the master branch. You want to merge changes from your-branch into the master for others to see them, but someone else did conflicting changes to the master (e.g. merging their PR) in the meantime. It is often useful to merge master into your-branch (i.e. do the merge the other way round) before creating the PR.

