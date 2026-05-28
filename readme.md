- git config --global user.email ""
- git config --global user.name ""

# ini cuman dilakukan satu kali aja

git init

# ---- ini yang biasanya akan dilakukan berkali kali

(save)

git add readme.md # <----- tapi ini cara repot

# (save) cara gampang
git add .
git commit -m "menambahkan readme.md"

## kalau misalnya ada salah message commit
git commit -m "message barunya apa" --amend

''' sh
git status

## -- ini akan kita pakai untuk lihat udah simpen apa aja sih?

''' sh
git log