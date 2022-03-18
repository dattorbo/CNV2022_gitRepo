# CNV2022_gitRepo
**************************************************************************
CREATE PROJECT FROM GITHUB
inserire tutti gli utenti del progetto

da fork:
init new repository

gestione gitignore (attenzione al file *.isopen se copiato da altri progetti)

add remote origin da console fork (push exsisting folder OR push exsisting repository)

make first commit

push first init

***************************************************************************
FOR GET NEW BRANCH
Repository >> GitFlow >> Initialize
accept all feature, add log, ecc..........
after that should be present develop branch

**************************************************************************
FOR PICK UP A SINGLE COMMIT IN A SPECIFIC BRANCH
use the function Cherry-Pick commit

**************************************************************************
FOR MERGE MORE BRANCHES
only merge:
	goes on last commit >> right click >> Merge into.. (branche selected)

merge with tag (for implement version o revision):
	goes on last commit >> right click >> Git Flow >> Start Release
	write version and comment >> Start
	** complete release, commits and other changes **
	goes on last commit >> right click >> Git Flow >> Finish release.

*****************************************************************************
FOR ROLL BACK STATE IN AN EARLIER COMMIT
use the function Checkout commit

*****************************************************************************
FOR DISCARDE LAST COMMIT
use the function Revert Commit
in this way you delete the changes of the last commit 

