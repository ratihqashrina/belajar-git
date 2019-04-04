## Belajar Git 

### Perintah Dasar Git
- Membuat Repository Baru
	`git ini`
- Melihat status working folder 
	`git status`
- Menambah perubahan ke staging area 
	`git add nama-file / get nama-file . (semua file)
- Menyimpan perubahan ke local repo
	`git commit -m "Pesan/keterangan commit`
- Mendaftarkan Remote repo
	`git remote add nama-remote url-remote`
	`git remote add github https://github.com/ratihqashrina/belajar-git.git
- Mengaupload repo lokal ke remote
	`git push -u nama-remote nama-branch`
- Mendownload/mengambil perubahan dari remote ke working folder
	`git pull nama-remote nama branch`
- Menghapus perubahan di staging
	`git reset`
- Menghapus perubahan di staging dan working folder
	`git reser --hard`
- Melihat daftar branch
	`git branch --all`
- Membuat branch baru 
	`git branch nama-branch`
- Pindah ke branch tertentu 
	`git checkout nama-branch
- Merge branch tertentu ke master 
	`git checkout master git merge nama-brach`
- Menghapus branch tertentu di lokal 
	`git branch -d nama-branch`
- Menghapus branch tertentu di remote
	`git branch nama-remote nama-branch`

