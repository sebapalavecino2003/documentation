# Documentation (LaTeX)

## Compilar en Windows
1) Instalar MiKTeX
2) En la carpeta del repo:
   pdflatex -interaction=nonstopmode -file-line-error main.tex
   pdflatex -interaction=nonstopmode -file-line-error main.tex

## Overleaf
- Opción A: usar la Git URL de Overleaf como remoto:
  git remote add overleaf https://git.overleaf.com/<id>
  git push overleaf master
  git pull overleaf master

- Opción B: crear proyecto Overleaf “From GitHub”.
