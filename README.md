# Trabalhando em Equipe com GIT

## Introdução

Nessa entrega vocês terão de usar todo seu conhecimento em GIT para trabalhar em equipe.

Vocês deverão descrever um pouco mais sobre o seu relacionamento com a TI. Comente algo como "Escolhi a TI porque..." ou "Meu conhecimento em TI é..." para que seus colegas entendam seu relacionamento com a área.

## Tarefa

1. Cada membro da equipe deverá clonar o Repositório criado pelo líder;
2. Cada membro deve criar um branch para sua funcionalidade;
3. Depois de feita as alterações, os branches devem se unir no branch main;
4. O líder deve subir as alterações para o branch remoto;
5. Gerar o Github Pages;
6. Enviar o link do Repositório e do GithubPages no Canvas.

## Passo a Passo

### 1 — Preparando o repositório

Antes de começar a escrever linhas de código, cada membro do grupo deverá criar um branch para sua funcionalidade usando o código abaixo:

```bash
git checkout -b comentario-kenzinho
```

### 2 — Alterando o Código

Depois de criado o repo e os Branches, cada membro da equipe deve copiar o bloco de código de exemplo e alterar com os seus dados.

```Markdown
# Entrega: Trabalhando em equipe com git.

## Fato sobre <nome do dev>

1. O seu Nome;
2. Um pouco sobre você;
3. Comentário sobre o seu relacionamento com a TI;
```
Cada entrada deverá ter ao menos:

1. O seu nome;
2. Pequeno trecho falando sore você;
3. Comentário sobre o seu relacionamento com a TI.

__O uso de Branches é obgrigatório.__

### Finalizando o Projeto

Depois de finalizar as alterações, todos os membros devem subir as mudanças do seu Branch local para o Branch remoto usando um ``push``.

```bash
git push -u origin
```

Só então o líder deverá executar a junção dos branches entrando na branch Main e executando um `merge`.

```bash
git merge origin/nome_do_branch
git push origin
```

Este código pode gerar conflitos. Se acontecer, tente resolver com seus colegas e caso não seja possível, chame seu Facilitador.