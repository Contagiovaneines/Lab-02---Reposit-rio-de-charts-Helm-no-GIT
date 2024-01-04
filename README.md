# Comandos git
git clone <repo git>
cd <repo-dir>
mkdir charts
touch README.md
helm pull bitnami/wordpress
tar -zxvf wordpress-15.4.1.tgz
# Joque o wordpress dentro do charts
# Comandos git para enviar atualizações para o repositório git
git add .
git commit -m "repo central de helm"
git push
