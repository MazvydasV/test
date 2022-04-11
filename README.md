# Pirmoji GIT repozitorija

## Repozitorijos parsiuntimas
    git clone <repozitorijos-nuoroda>
## Pagrindines komandos
    git add - failu paruosimas patvirtinimui
        git add <failo-pavadinimas> -> prideda faila nurodytu pavadinimu
        git add . -> Prideda visus pakitusius failus
    git diff - skirtas tarp dvieju failu, ar dvieju to paties failo versiju
        git diff <failo-pavadinimas> ->failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o
    git status - parodo pakitusiu failu busena
    git branch - komanda, kuri naudoja operacijas su sakomis
        git branch -a -> parodo visas parsiustas sakas ir siuo metu aktyvia saka
    git commit -> komanda skirta uztikrinti projekto pakitimui
        git commit -m "zinute apibudinanti komita"
    git push -> komandaskirta paviesinti commit'us i atitinkama globalia saka