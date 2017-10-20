    2  cd Pulpit/
    9  mkdir Pierwsze_repozytorium
	   11  mkdir first_repo
	   12  cd first_repo/
>
### Zabawa z GITem
>
Instalacja GIT
--------------
>
>	   16  apt-get install git
   18  mc
   19  apt-get install mc
   20  ls -al
   21  cd ..
   22  rm -rf Pierwsze_repozytorium/
   23  cd first_repo/
   24  git help
   25  touch test.txt
   26  ls
   27  mcedit test.txt 
   29  ls -al
   32  git ?
   33  git help
   35  cd Pulpit/
   36  cd first_repo/
   37  git init
   38  ls -al
   42  git status
   43  git add test.txt 
   44  git status
   45* git commit -m "pierwsza modyfikack"
   46  git config --global user.email "mojusunietyadresemail@gmail.com"
   47  git config --global user.name "Szawelski"
   48  git commit -m "utworzenie nowego pliku"
   49  git status
   50  git help
   51  git log
   52  mcedit test.txt 
   53  git status
   54  git add test.txt 
   55  git commit -m "pierwsza zmiana"
   56  git log
   57  mcedit test.txt 
   58  git status
   59  git commit -m "trzecia zmiana"
   60  git log
   61  git status
   62  git commit -m "trzecia zmiana"
   63  git add .
   64  git commit -m "trzecia zmiana"
   65  git status
   66  git log
   68  git help
   75  git push -u origin master
   80  cd ~/.git
   81  mcedit ~/.gitconfig
   84  mcedit test.txt 
   85  git status
   86  git commit -a -m "Kolejna zmiana"
   87  git status
   88  git push -u origin master
   89  history > readme.md
