# Module 2 Assessment
1. In Git, what is modeled as a directed acyclic graph?

        A. The staging area.
        B. The working tree.
        C. The commit history.

        Ans: C
        This is covered in 'Git's Graph Model'.


2. How are Git commits connected?
        
        A. A commit references its parent(s).
        B. A commit object contains the SHA-1 of its child or children.
        C. The staging area lists the connections.

        Ans: A
        This is covered in 'Git's Graph Model'.

3. What is a Git ID?

        
        A. The ID of the local repository.
        B. The user's name and email address.
        C. The name of a Git object.

        Ans: C
        This is covered in 'Git IDs'.


4. If a large file changes by one character, what would you expect to happen to its corresponding SHA-1 value?

        A. It would slightly change.
        B. It would not change.
        C. It would change drastically.

        Ans: C
        This is covered in 'Git IDs'.


5. What do branch labels point to?

        
        A. The initial commit of a branch.
        B. Every commit of a branch.
        C. The most recent commit of a branch.

        Ans: C
        This is covered in 'References'.


6. How many HEAD references are in a local repository?

        A. One for each branch label.
        B. One.
        C. One for each commit.

        Ans: B
        This is covered in 'References'.


7. Which one of these statements is correct?
        
        A. A tag is another name for a branch label.
        B. The HEAD reference always points to a tag.
        C. A tag always points to a specific commit.

        Ans: C
        This is covered in 'References'.


8. What happens when a branch is created?

        A. A branch label is created.
        B. The HEAD reference changes.
        C. Commits are copied.

        Ans: A
        This is covered in 'Branches'.


9. Which one of these statements is correct?

        
        A. Checkout prevents others from changing a branch.
        B. Checkout updates the working tree and HEAD reference.
        C. Checkout retrieves content from the remote repository.

        Ans: B
        This is covered in 'Branches'.


10. What does a detached HEAD mean?

        A. The HEAD reference does not point to anything.
        B. The HEAD reference points to a branch label.
        C. The HEAD reference points directly to a commit SHA-1.

        Ans: C
        This is covered in 'Branches'.


11. What does "deleting a branch" immediately do?

        A. Deletes all of the commits of the branch.
        B. Deletes a branch label.
        C. Deletes only the commits that are unique to the branch.

        Ans: B
        This is covered in 'Branches'.


12. Which one of the following statements is true?

        A. A commit can only belong to one branch at a time.
        B. A merge always creates a new commit.
        C. Merging combines the work of branches.

        ANs: C
        This is covered in 'Merging'.


13. Which one of the following statements about fast-forward merges is true?

        A. The merge moves a branch label.
        B. The merge may change some commits.
        C. The merge may result in a merge conflict.

        Ans: A
        This is covered in 'Merging'.

14. If Git informs you that a fast-forward merge is not possible, which one of these statements is probably true?

        A. The merge has merge conflicts.
        B. The checked out commit has multiple parents.
        C. A commit was made on the base branch after the topic branch was created.

        Ans: C
        This is covered in 'Merging'.


15. Which one of these statements is true?

        A. The files in the working tree change after a fast-forward merge.
        B. A fast-forward merge results in a non-linear commit history.
        C. To perform a fast-forward merge, checkout the topic branch.

        Ans: A
        This is covered in 'Merging'.


16. Which one of these statements about a merge involving a merge commit is true?

        A. A merge commit results in a linear commit history.
        B. The merge is aborted if there are merge conflicts.
        C. Git places the result of the merge into a new commit.

        Ans: C
        This is covered in 'Merging'.
