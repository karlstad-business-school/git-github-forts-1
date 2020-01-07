**Övning 1**
Starta en git session i lämplig terminal och navigera dig till det övningsrepo du skapade i introduktionskursen. 
Har du inte kvar repot lokalt borde du kunna klona det från ditt github konto.

1.1) Lista dina commits [git log]
1.2) Skapa en tag till din senaste commit (head) [git tag {tagg-namn}]
1.3) Lista dina taggar [git tag]
1.4) Uppdatera en fil i repot och commita dina ändringar [git add . och git commit -m "{commit message}"]
1.5) Checka ut din tagg [git checkout {tagg-namn}]
1.6) Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
1.7) Lista din commits och checka ut samma commit som du taggade men använd hexa-hashen [git checkout {hexa}]
1.8) Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
1.9) Skapa en tag till din första commit i repot [lista dina commits och memorera hexen för första commiten, git tag {tagg-namn} {hex}
1.10) Lista dina taggar [git tag]
1.11) Ta bort valfri tag [git tag -d {tagg-namn}
1.12) Pusha dina taggar till github [git push origin --tags]
1.13) Ta bort en av taggarna från remote (ej lokalt) [git push origin --delete {tagg-namn}]




2.2) klona github repot till din lokala dator

```
illidium-q35:git benc$ cd ~/git/tmp/

illidium-q35:tmp benc$ git clone https://github.com/bennchri/git-training.git


```
