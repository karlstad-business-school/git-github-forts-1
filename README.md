## Git och Github handson fortsättning 1

<!-- 
### Instruktionsfilm
https://kau.box.com/s/nj841t2mnqba3eqx6d7rajk0uj93roel
```
Tidskoder:
0:00:00 inledning/agenda
0:02:50 Introduktion till SCM och git
0:17:20 Övning 1
0:22:50 Varför terminalen för git?
0:26:50 Grunder Git 
0:29:40 Övning 2
0:51:04 Förstå och traversera tidslinjen i ett git repo
0:56:23 Övning 3
1:06:38 Vanliga misstag och hur du återställer + övning 4
1:13:00 Arbeta med remote och lokal kopia av repo + övning 5
1:29:20 Arbeta med readme och markdown + wiki + övning 6
```
-->


### Agenda
#### Git tag
* Vad är en git tag
* Varför använda taggar
* Hur använda taggar
---
##### [Övning 1](ovningar.md)
---
 
#### Git stash
* Stasha ett dirty directory (modified and staged tracked files)
* Återställa en stashning (allt blir unstaged)
* Stasha untracked (untracked, modified and staged tracked files)
* Stasha ignored (ignored, untracked, modified and staged tracked files)
* Lista alla stashningar
* Återställ från specifik stashning
* Ta bort en stash

---
##### [Övning 2](ovningar.md)
---

 
#### Git branch
* Skapa en ny lokal branch från head
* Växla mellan branches
* Skapa en ny lokal branch från en commit på tidslinjen
* Lista alla branches i ett repo
* Remote branches
* Push branches to remote
* fetch/pull remote branches 
   * git fetch command will fetch all the changes on the server that you don’t have yet, it will not modify your working  directory at all. It will simply get the data for you and let you merge it yourself.
   * git pull (fetches and merges)
   * radera en branch (utan att spara ändringar i branchen)
  
---
##### [Övning 3](ovningar.md)
---
#### Git merge
* Förbered för en merge
* Merga fast forward
* Merga recursive
* Lös merge konflikt manuellt
* Avbryt en merge
* Undo en merge
* radera en mergad branch (utan att förlora ändringar i branchen)


---
##### [Övning 4](ovningar.md)
---


