# Matematicar

**Uma ferramenta de ensino de matemática básica.**

Criado por: **Prof. Me. Rodrigo Gonçalves (Prof Oswy)**

O Matematicar é um aplicativo para quem quer aprender, recuperar ou reforçar a matemática básica que deveria ter ficado da escola: das quatro operações até trigonometria. Serve para estudantes do ensino fundamental e médio, para calouros de cursos de exatas e para qualquer adulto que queira retomar o assunto.

Tudo funciona num único arquivo HTML, direto no navegador, sem instalação, sem cadastro e sem internet depois de carregado.

---

## O que tem

### 10 temas, 57 habilidades

| Tema | Habilidades |
|---|---|
| **Quatro operações** | Adição · Subtração · Multiplicação · Divisão |
| **Equações do 1º grau** | O que é uma equação · Multiplicação e divisão · Dois passos · x dos dois lados · Parênteses · Frações · Problemas com equações |
| **Potenciação** | O que é potência · Expoentes 0 e 1 · Potências de 10 · Propriedades · Base negativa · Expoente negativo |
| **Radiciação** | O que é raiz · Raízes não exatas · Raiz de uma soma · Produto e quociente de raízes · Simplificar radicais |
| **Frações** | Conceito · Equivalentes · Simplificação · Comparação · Soma e subtração (mesmo denominador e denominadores diferentes) · Multiplicação · Divisão |
| **Números decimais** | Conceito · Comparação · Soma e subtração · Multiplicação · Divisão · Arredondamento |
| **Ordem das operações** | Prioridade · Parênteses · Colchetes e chaves · Expressões com potências |
| **Razão, proporção e porcentagem** | Razão · Regra de três direta · Grandezas inversas · Porcentagem · Aumentos e descontos · Escala |
| **Geometria básica** | Ângulos · Ângulos do triângulo · Perímetro · Área · Círculo e circunferência · Teorema de Pitágoras |
| **Trigonometria** | Seno, cosseno e tangente · Ângulos notáveis · Calcular um lado · Descobrir o ângulo · Inclinação e rampas |

Os temas são independentes: dá para abrir qualquer habilidade direto, sem precisar passar pelas outras. Dentro de cada tema, a lista mostra a ordem sugerida.

### Problemas complexos

Questões com texto que juntam várias habilidades, no estilo de concursos, ENEM e provas: custo de piso com desconto, latas de tinta para uma parede, conta de luz de um chuveiro, comprimento de rampa, área real a partir de uma planta em escala, entre outras.

### Competição

Gamificação para a turma, sem servidor e sem cadastro:

1. **O professor monta a competição**: escolhe os temas (por padrão, Problemas complexos), a quantidade de questões (5, 10, 15 ou 20), o nível e se a calculadora é permitida. O app gera um **código da competição**.
2. **Os alunos digitam o código** no próprio celular e todos recebem **as mesmas questões, na mesma ordem**. Uma tentativa por questão, sem dicas, com cronômetro.
3. **Pontuação**: 100, 125 ou 150 pontos por acerto, conforme o nível, mais bônus de até 50 pontos por acertos seguidos. Desempate por acertos e depois pelo menor tempo.
4. Ao terminar, cada aluno recebe um **código de resultado**. O professor digita nome e código, e o app monta o **ranking com pódio**. Códigos de outra competição ou repetidos são recusados.

O ranking fica salvo no aparelho do professor; o código da competição pode ser reaberto depois.

### Em cada habilidade

- **Explicação curta** com desenhos e um **exemplo resolvido** passo a passo (com botão para gerar outro exemplo).
- **Folhas de exercícios** com 6, 10 ou 15 questões e o botão **Gerar novos exercícios**, que cria uma folha nova com a mesma quantidade.
- **Dicas em três níveis**: duas dicas e, por fim, a resolução completa.
- **Diagnóstico de erros**: o app reconhece os erros mais comuns de cada assunto (somar denominadores, esquecer o "vai um", inverter a regra de três, usar o perímetro no lugar da área…) e explica o que aconteceu.
- **Rascunho com feedback**: cada exercício tem linhas para resolver aos poucos. O app confere cada passo, inclusive equações com x, e mostra ✓, o valor da conta ou onde está a diferença.
- **Domínio**: a habilidade fica dominada com 5 acertos sem dica nas últimas 6 questões. A dificuldade sobe conforme o aluno acerta.

### Outras ferramentas

- **Termos**: 32 verbetes com as palavras técnicas (base, expoente, denominador, quociente, hipotenusa…), com exemplos e desenhos. As palavras aparecem sublinhadas em todo o app; basta tocar para ver o significado.
- **Calculadora** com frações exatas, potências, raízes, porcentagem, π, seno, cosseno e tangente (em graus). Fica desligada em Quatro operações, porque ali a conta é o próprio treino.
- **Imprimir folha**: monta listas em papel escolhendo assuntos, nível e quantidade (até 50 por assunto), com gabarito em página separada.
- **Modo claro** (caderno pautado) e **modo escuro** (azul quadriculado).

### Como o app lê o que é digitado

- `x`, `X`, `*`, `·` e ponto valem como multiplicação entre números (`3 x 4`).
- `x` sozinho ou colado a um número é a incógnita (`2x + 5 = 17`).
- `/` e `:` são divisão; `^` é potência; vírgula é a marca decimal (`2,5`).
- Também são aceitos `√`, `raiz de 64`, `10% de 200`, `sen(30)`, `mmc(4; 6)` e `mdc(12; 18)`.

---

## Como usar

**Online:** acesse a página publicada no GitHub Pages.

**No computador, sem internet:** baixe o arquivo `index.html` e abra no navegador (Chrome, Edge, Firefox ou Safari). As fontes manuscritas são carregadas da internet; sem conexão, o navegador usa uma letra substituta.

---

## Progresso e privacidade

- O progresso fica salvo **no próprio navegador** do aparelho. Nada é enviado para servidor nenhum, e o app não pede nome, e-mail nem cadastro.
- Para continuar em outro aparelho, use o **Código de progresso** (no topo da tela): anote o código e digite-o no outro navegador. Ele guarda quais habilidades foram dominadas.
- Limpar os dados do navegador ou usar o modo anônimo apaga o progresso salvo.

---

## Publicação no GitHub Pages

1. Crie um repositório e envie os arquivos `index.html`, `README.md` e `LICENSE.md`.
2. Em **Settings → Pages**, escolha a branch principal e a pasta raiz (`/`).
3. O endereço fica no formato `https://<usuário>.github.io/<repositório>/`.

---

## Créditos e contato

**Prof. Me. Rodrigo Gonçalves (Prof Oswy)**

- YouTube: [youtube.com/@ProfOswy](https://www.youtube.com/@ProfOswy)
- Instagram: [@rodrigo.osw](https://www.instagram.com/rodrigo.osw)
- E-mail: [profoswy@gmail.com](mailto:profoswy@gmail.com)

---

## Licença

Uso livre para fins pessoais, acadêmicos e educacionais, e compartilhamento do link permitido. Redistribuição, obras derivadas, remoção dos créditos e uso comercial dependem de autorização por escrito. Veja os termos completos em [LICENSE.md](LICENSE.md).
