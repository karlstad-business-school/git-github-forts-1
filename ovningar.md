**Övning 1**
Starta en git session i lämplig terminal och navigera dig till det övningsrepo du skapade i introduktionskursen. 
Har du inte kvar repot lokalt borde du kunna klona det från ditt github konto.

1. Lista dina commits [git log]
1. Skapa en tag till din senaste commit (head) [git tag {tagg-namn}]
1. Lista dina taggar [git tag]
1. Uppdatera en fil i repot och commita dina ändringar [git add . och git commit -m "{commit message}"]
1. Checka ut din tagg [git checkout {tagg-namn}]
1. Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
1. Lista din commits och checka ut samma commit som du taggade men använd hexa-hashen [git checkout {hexa}]
1. Checka ut head och återställ repot från traversering av tidslinjen [git checkout master]
1. Skapa en tag till din första commit i repot [lista dina commits och memorera hexen för första commiten, git tag {tagg-namn} {hex}]
1. Lista dina taggar [git tag]
1. Visa detaljer för en specifik tagg [git show {tagg-namn}]
1. Ta bort valfri tag [git tag -d {tagg-namn}]
1. Pusha dina taggar till github [git push origin --tags]
1. Ta bort en av taggarna från remote (ej lokalt) [git push origin --delete {tagg-namn}]

Du kan annotera en tag med mer information och evt. ett meddelande. Du använder då switchen -a för annotate och -m om du vill skriva in informationen direkt i kommandot. Utelämnar du -m kommer git att starta default editor för annoteringsinformation.
ex git tag -a v2 -m "Detta är version 1"



**Övning 2**
Starta en git session i lämplig terminal och navigera dig till det övningsrepo du skapade i introduktionskursen. 
Har du inte kvar repot lokalt borde du kunna klona det från ditt github konto.
1. Gör en förändring i en fil och stagea filen.
1. Gör en förändring till i samma fil en git status ska ge något liknande detta:
```
Illidium-Q35:git-training-kau benc$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   new.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   new.txt
```
3. Stasha alla ändringar [git stash]
1. Bekräfta att stashningen är gjord 
```
Illidium-Q35:git-training-kau benc$ git stash
Saved working directory and index state WIP on master: 23f82bd reset
HEAD is now at 23f82bd reset
Illidium-Q35:git-training-kau benc$ git status
On branch master
nothing to commit, working tree clean
Illidium-Q35:git-training-kau benc$ git stash list
stash@{0}: WIP on master: 23f82bd reset
Illidium-Q35:git-training-kau benc$ 
```
5. Återställ directoriet med din sparade stash [git stash apply]
6. Bekräfta återställning och observera att du förlorat din stagening (ändringen finns dock kvar som unstaged)
1. Ta bort stashen från stash-stacken [git stash drop] (du kan applya och droppa samtidigt genom kommandot git stash pop
1. Skapa en ny fil i directoriet (ny.txt). Bekräfta att filen är untracked.
1. Stasha ditt directory inkludera den nya filen [git stash -u]
1. Återställ, bekräfta, ta bort stashen 
1. Skapa en ignored fil (ny.eee)
1. Stasha ditt directory inkludera untracked och ignored [git stash -a]
1. Återställ, bekräfta
1. Gör valfria ändringar och gör en ny stash
1. Lista din stash-stack [git stash list]
1. Återställ din första stash [git stash apply stash@{1}]
1. Bekräfta och ta bort din första stash [git stash drop stash@{1}

**Övning 3**
Starta en git session i lämplig terminal och navigera dig till det övningsrepo du skapade i introduktionskursen. 
Har du inte kvar repot lokalt borde du kunna klona det från ditt github konto.




