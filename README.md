# teste-projeto-modulo-submodulo
Teste de projeto monorepo com submodulos - Passo a passo <br>
git clone https://github.com/sandrooscar/teste-projeto-modulo-submodulo.git <br>
cd teste-projeto-modulo-submodulo/ <br>
git init <br>
git submodule add https://github.com/sandrooscar/modulo2.git modulo2  #aqui o projeto modulo 2 já precisa ter algum arquivo no repositorio para evitarmos problemas <br>
git status <br>
git add .gitmodules modulo2  #incluindo alterações do stage <br>
git commit -m "Incluindo submodules" #commit nas alterações do submodulo <br>
git push origin main <br>

