# Guia de Contribuição - Desafios 30 Dias de CSS

Este guia descreve o processo para criar uma branch para cada desafio e como submeter um Pull Request (PR) para o repositório.

## 1. Atualizar o Repositório Local

Antes de iniciar um novo desafio, certifique-se de que seu repositório local está atualizado com a branch principal (`main`).

```bash
git checkout main
git pull origin main
```

## 2. Criar uma Branch para o Desafio

Para manter o projeto organizado, crie uma branch específica para cada desafio que você for desenvolver. Recomenda-se usar um padrão de nomenclatura claro, como `desafio/dia-XX`.

**Exemplo para o Dia 01:**

```bash
git checkout -b desafio/dia-01
```

Isso cria e muda automaticamente para a nova branch.

## 3. Desenvolver o Desafio

Navegue até a pasta correspondente ao desafio dentro de `Desafios_30diasdeCSS`.

**Exemplo:**
Se você está fazendo o desafio do dia 01, seus arquivos devem estar em:
`Desafios_30diasdeCSS/Semana-01/Dia-01/`

Crie arquivos HTML e CSS necessários (ex: `index.html`, `style.css`).

## 4. Commitar as Alterações

Após finalizar o desenvolvimento, adicione os arquivos e faça o commit.

```bash
git add .
git commit -m "Adiciona solução do desafio do dia 01"
```

## 5. Enviar para o Repositório Remoto

Envie sua branch para o repositório remoto (GitHub/GitLab, etc).

```bash
git push origin desafio/dia-01
```

## 6. Criar o Pull Request (PR)

1.  [Acesse o repositório no GitHub.](https://github.com/Micael-Macedo/30diasDeCSS)
2.  Normalmente, você verá um aviso de que uma nova branch foi enviada ("Compare & pull request").
3.  Clique no botão para criar o Pull Request.
4.  No título, coloque algo como: `Desafio Dia 01 - [Breve Descrição]`.
5.  Na descrição, você pode adicionar detalhes sobre o que foi feito ou observações.
6.  Verifique se a branch de origem é a sua (`desafio/dia-01`) e a de destino é a `main`.
7.  Clique em "Create Pull Request".

---

Parabéns! Você submeteu seu desafio. 🚀