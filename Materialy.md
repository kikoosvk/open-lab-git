
# Git merge
[git merge][git-merge] sluzi na spojenie dvoch alebo viacerych vetiev do jednej.
![N|Solid](https://i.stack.imgur.com/zGYUk.png)
# Git stash
Pomocou [git stash][git-stash] si mozeme ulozit nase doteraz vykonane zmeny v nejakom externom stash "priecinku".
git stash list - ukaze nam zoznam doteraz ulozenych zmien
git stash apply - vezme poslednu ulozenu zmenu a aplikuje ju
git stash push - zoberie vsetky zmeny a ulozi ich do stash priecinka.
# Git rebase
[git rebase][git-rebase] je proces presuvania alebo kombinovania skupiny commitov do nejakeho noveho commitu.
Viac informacii sa mozete docitaj aj v [tomto tutoriali][git-rebase-tutorial].
Na obrazku bol pouzity prikaz bud **git rebase Main** alebo **git rebase Main Feature**, ktory presunul predchadzajuce commity z Feature vetvy tak, aby  vychadzali z Main vetvy.
![N|Solid](https://wac-cdn.atlassian.com/dam/jcr:4e576671-1b7f-43db-afb5-cf8db8df8e4a/01%20What%20is%20git%20rebase.svg?cdnVersion=1807)
# Git cherry-pick
[git cherry-pick][git-cherry-pick] nam umoznuje vybrat lubovolny commit a aplikovat ho na aktualnu poziciu (git HEAD). Je to process, ktory vezme jeden commit z nejaky lubovolnej vetvy a aplikuje ho na inu vetvu. 
Viac informacii je k dispozicii v [tomto tutoriali][git-cherry-pick-tutorial],
![N|Solid](https://res.cloudinary.com/practicaldev/image/fetch/s--jmZDSObz--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/dmb185yxo5umin72abyr.jpg)

   [git-merge]: <https://git-scm.com/docs/git-merge>
   [git-stash]: <https://git-scm.com/docs/git-stash>
   [git-rebase]: <https://git-scm.com/docs/git-rebase>
   [git-rebase-tutorial]: <https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase>
   [git-cherry-pick]: <https://git-scm.com/docs/git-cherry-pick>
   [git-cherry-pick-tutorial]: <https://www.atlassian.com/git/tutorials/cherry-pick>
   
