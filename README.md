1. Jadi, sebelum kamu edit source, pastikan kamu berada di branch master,
[git checkout master]
2. kemudian update source mu telebih dahulu dari repo kulina,
[git pull --rebase kulina master]
kalau ada conflict segera perbaiki ya :)
3. bikin branch baru sesuai apa yang dikerjakan
[git checkout -b namaBranch]
4. Setelah melakukan perubahan source, commit terlebih dahulu,
[git add satu-satu atau git add . (kalau mau dicommit semuanya) atau pake git cola untuk add nya)]
5. terus lakukan update source, agar mendapatkan perubahan source terbaru
[git pull --rebase kulina master]
6. push ke editan remote repository pribadi
[git push origin namaBranch]
7. terus lakukan pull request di web github
8. pastikan pull request-mu sudah close/merged
9. lakukan update source
[git pull --rebase kulina master]
10. pindah ke branch master
[git checkout master]
11. lakukan update source
[git pull --rebase kulina master]
12. delete branch yang sudah merged (optional)
[git branch -d revise-matching-algorithm]
13. done
