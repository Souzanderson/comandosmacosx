
# Comandos úteis para zsh do Mac

Um breve apanhado de comandos para MacOS, visando facilitar o acesso a funcionalidades do terminal:

## Criar diretório

```bash
mkdir nome_do_diretorio
```

## Remover Diretório

```bash
rm -rf nome_do_diretorio
```

## Renomear Arquivo:

```bash
mv nome_antigo novo_nome
```

## Mudar permissão para o usuário atual

* Este comando é interessante em casos como quando o diretório node_modules do projeto nega a permissão de escrita para o usuário atual.

```bash
sudo chown -R ${USER} arquivo_ou_diretorio
```

## Mudar arquivo para executável

* Este comando é interessante em casos como quando você possui um batch file e quer fazêlo executável

```bash
chmod +x nome_do_arquivo
```
