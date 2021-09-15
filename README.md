# Open lab git & GitHub cvicenia

## GitHub PullRequest cvicenie
Cielom tohoto cvicenia je si vyskusat ako sa vytvara a merguje pull request v GitHube.

Ako prvy krok je potrebne si vytvorit GitHub repozitar na https://github.com/new
Po vytvoreni je potrebne si ho pomocou prikazu git clone naklonovat do svojho PC.

Potom vytvorit v branchy master (git po novom dava default nazov main, takze vas master je potom main) novy textovy subor s nazvom **file.txt**, pridat nejaky text na prvy riadok tohoto suboru a urobit commit.
Dalej je potrebne vytvorit novu branchu, pre ktoru budeme neskor vytvarat pull request.

Prehodime sa na tuto novo vytvorenu branchu a pridame text do druheho riadku v subore file.txt (napr. commit from new branch).
urobime commit a tuto branchu pushneme do remote repozitara.

Nasledne sa switchneme na master (alebo main) a tu znovu pridame text (napr. commit from master branch) do druheho riadku v subore file.txt, takze mame zmenu v tom istom subore na tom istom riadku v dvoch rozdnych vetvach,
urobime commit a push a mali by sme mat v remote repozitary na githube dve branche.


Teraz je tvojou ulohou v githube vytvorit pull request z vytvorej vetvy do vetvy master, vyriesit dany konflikt na druhom riadku (bud lokalne, alebo pomocou github web editora) a uspesne ho mergnut tak aby sa zachovali vsetky zmeny z jednej aj druhej vetvy, je jedno v akom poradi
Vysledkom by mal byt v master vetve subor file.txt s 3 riadkamy textu.

## Git interaktivne cvicenia

V tejto casti pouzijeme stranku https://gitexercises.fracz.com/, ktora obsahuje interaktivne cvicenia na rozne aj pokrocile git prikazy.

Prejdite na spomenutu stranku rozbehajte si spomenuty repozitar podla sekcie How to start?.
Ked to budete mat prejdite na prve cvicenie https://gitexercises.fracz.com/exercise/master.
Po tom ako date prikaz git verify by sa v konzole mal zobrazit.
```sh
Status: PASSED
```
a na stranke v pravom stlpci by malo byt prve cvicenie oznacene ako uspesne zvladnute.
Tu je mozne sa prepinat medzi jednotlivými cviceniami, nizsie je zoznam najzaujimavejsich cviceni, ktore som nasiel:

- commit-one-file-staged
- ignore-them
- chase-branch
- merge-conflict
- save-your-work
- change-branch-history
- fix-typo
- fix-old-typo
- too-many-commits
- pick-your-features
- rebase-complex

Ak tie dokoncite dokoncite, mozete skusit aj nasledujuce
- remove-ignored
- commit-lost
- split-commit
- commit-parts
- invalid-order
- find-swearwords
