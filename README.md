# tortoisegit-colons
This is a test repo to demonstrate the failure of tortoisegit and Windows to support colons in the filename.

To test, fork and `git clone` this repo in your local tortoisegit. `git commit` without any changes. You should notice a changeset with delete files (the ones with colons). `git push` to your repo. Verify the files were removed upstream. Now `git revert` and `git push` your changeset. You should notice that removed files are not restored.

cf. https://groups.google.com/forum/#!topic/tortoisegit-users/w9t79l_HFRw

cf. https://groups.google.com/forum/#!topic/msysgit/D4HcHRpxPgU

(msysgit seems to be the correct place to fix the issue)

cf. https://msysgit.github.io/

cf. https://code.google.com/p/tortoisegit/
