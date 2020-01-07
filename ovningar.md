**Övning 1**
Starta en git session i lämplig terminal och navigera dig till det övningsrepo du skapade i introduktionskursen. 
Har du inte kvar repot lokalt borde du kunna klona det från ditt github konto.

. Lista dina commits [git log]
. Skapa en tag till din senaste commit (head) [git tag {tagg-namn}]
. Lista dina taggar [git tag]
. Uppdatera en fil i repot och commita dina ändringar [git add . och git commit -m "{commit message}"]
. Checka ut din tagg [git checkout {tagg-namn}]
. Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
. Lista din commits och checka ut samma commit som du taggade men använd hexa-hashen [git checkout {hexa}]
. Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
. Skapa en tag till din första commit i repot [lista dina commits och memorera hexen för första commiten, git tag {tagg-namn} {hex}
. Lista dina taggar [git tag]
. Ta bort valfri tag [git tag -d {tagg-namn}
. Pusha dina taggar till github [git push origin --tags]
. Ta bort en av taggarna från remote (ej lokalt) [git push origin --delete {tagg-namn}]




2.2) klona github repot till din lokala dator

```
illidium-q35:git benc$ cd ~/git/tmp/

illidium-q35:tmp benc$ git clone https://github.com/bennchri/git-training.git


```
