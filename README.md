# teste-projeto-modulo-submodulo
Teste de projeto monorepo com submodulos - Passo a passo
git clone https://github.com/sandrooscar/teste-projeto-modulo-submodulo.git
cd teste-projeto-modulo-submodulo/
git init
git submodule add https://github.com/sandrooscar/modulo2.git modulo2  #aqui o projeto modulo 2 já precisa ter algum arquivo no repositorio para evitarmos problemas
git status
git add .gitmodules modulo2  #incluindo submodulo modulo2
git commit -m "Incluindo submodules" #commit nas alterações do submodulo
git push origin main

