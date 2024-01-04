# README - Repositório de Charts Helm no GIT

Este guia fornece instruções básicas sobre como criar um repositório de charts Helm no GIT, baixar um chart (no exemplo, usaremos o WordPress) e enviar atualizações para o repositório git.

## Criar Repositório no Git

1. Crie um repositório no seu provedor de Git preferido (GitHub, GitLab, Bitbucket, etc.).

## Clonar o Repositório

```bash
git clone <repo-git-url>
cd <repo-dir>
```

Substitua `<repo-git-url>` pelo URL do seu repositório git.

## Estrutura Padrão Apps do Rancher

```bash
mkdir charts
touch README.md
```

## Baixar o Chart do WordPress para o Repositório

```bash
helm pull bitnami/wordpress
tar -zxvf wordpress-15.4.1.tgz -C charts/
```

Substitua `15.4.1` pela versão específica do chart que você deseja baixar.

## Adicionar Atualizações ao Repositório Git

```bash
git add .
git commit -m "repo central de helm"
git push
```

=======
# README - Repositório de Charts Helm no GIT

Este guia fornece instruções básicas sobre como criar um repositório de charts Helm no GIT, baixar um chart (no exemplo, usaremos o WordPress) e enviar atualizações para o repositório git.

## Criar Repositório no Git

1. Crie um repositório no seu provedor de Git preferido (GitHub, GitLab, Bitbucket, etc.).

## Clonar o Repositório

```bash
git clone <repo-git-url>
cd <repo-dir>
```

Substitua `<repo-git-url>` pelo URL do seu repositório git.

## Estrutura Padrão Apps do Rancher

```bash
mkdir charts
touch README.md
```

## Baixar o Chart do WordPress para o Repositório

```bash
helm pull bitnami/wordpress
tar -zxvf wordpress-15.4.1.tgz -C charts/
```

Substitua `15.4.1` pela versão específica do chart que você deseja baixar.

## Adicionar Atualizações ao Repositório Git

```bash
git add .
git commit -m "repo central de helm"
git push
```
