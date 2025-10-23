# THE TEAM PORTFOLIO PROJECT 

#Project Title: raskala - market place to sell used items 

Team members:    ---------------            GitHub usernames
- Hadil Lafrid     ---------------             HadeelLafrid
- kaouther tazgart  ------------         kaoutertazgart 
- Mehdi Bouzoul     --------------            Mehdi Bouzoul
- Ahmed Bendjebbara -------------         Ahmed-bjr
- Ibtihal Djezzar    --------------
ibtihal07741

# Website URL : https://hadeellafrid.github.io/team-portfolio-project/


### Team Retrospective

Throughout this collaborative assignment, our team experienced a realistic simulation of distributed software development using Git and GitHub. The most significant technical challenge we faced occurred when one teammate accidentally merged their feature branch directly into the `master` branch instead of merging into `develop` through a pull request. This violated the intended workflow and created an inconsistency between the branches. As team lead, I had to create a new feature branch, synchronize it with the updated `master`, and then apply the fix properly by merging back into `develop`. This situation forced us to carefully manage branches and respect the process, which highlighted the importance of discipline when working with Git in a team.

A specific merge conflict also occurred in the `index.html` file, since multiple members were modifying the same section to add hyperlinks to their personal pages. To resolve this, the conflicting branch was first synchronized by pulling the latest `develop` changes, and then the conflict markers were manually reviewed. The correct final version was reconstructed by keeping all team entries, the file was staged, committed with a conventional `fix:` commit message, and pushed again before merging.

Overall, using pull requests and peer code reviews significantly improved the quality of our final project. Pull requests acted as control points that prevented direct mistakes and allowed for human inspection before integrating code. Code reviews helped catch errors early, ensured consistency in formatting and commit style, and created a clear history of decisions. This process not only reinforced best practices of collaborative development but also ensured that the final deployed product was stable, traceable, and professionally structured.
