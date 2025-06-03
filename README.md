# Controle de Gastos Mensais

Uma aplicação simples e funcional desenvolvida em Python com interface gráfica, voltada para o registro de entradas e saídas mensais.

---

## Objetivo

Facilitar o controle financeiro pessoal de forma **offline, leve e sem complicações**, com:
- Registro rápido de entradas e saídas
- Geração automática de relatórios `.txt`
- Armazenamento seguro e local dos dados
- Executável `.exe` que roda mesmo sem Python instalado

---

## Interface

A interface foi desenvolvida com foco na simplicidade:
- Menu suspenso para escolher **Entrada** ou **Saída**
- Campo de **categoria** livre
- Campo de **valor** com validação
- Botões para:
  - Salvar os registros
  - Ver resumo do mês
  - Gerar relatório anual com insights

---

## Estrutura dos Arquivos Gerados

- Uma pasta `dados/` será criada automaticamente ao rodar o programa
- Dentro dela, o sistema salva:
  - `junho_2025.csv` — um arquivo por mês com os lançamentos
  - `relatorio_junho_2025.txt` — relatório detalhado com entradas, saídas e saldo
  - `relatorio_anual_2025.txt` — resumo anual com top categorias e sugestão

---

## Como Usar

1. Crie uma pasta na Área de Trabalho chamada `Controle de Gastos`
2. Coloque o `ControleDeGastos.exe` e o arquivo `LEIA-ME.txt` dentro dela
3. Dê dois cliques no executável
4. Pronto! Agora é só preencher seus gastos e entradas com facilidade

> ⚠️ Obs: Sempre execute o programa dentro da mesma pasta, para manter os dados organizados

---

## Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Tkinter](https://docs.python.org/3/library/tkinter.html) (GUI)
- [Pandas](https://pandas.pydata.org/) (manipulação de dados)
- [PyInstaller](https://www.pyinstaller.org/) (para gerar o `.exe`)

---

## Funcionalidades

- ✔ Registro de entradas e saídas com data automática
- ✔ Armazenamento por mês em `.csv`
- ✔ Resumo financeiro mensal em `.txt`
- ✔ Relatório anual com:
  - Total de entradas/saídas
  - Top 3 categorias com mais gastos
  - Sugestão baseada no comportamento
- ✔ Interface intuitiva e leve

---

## Autor

**Agatha Rodrigues**

Se quiser me conhecer melhor ou ver outros projetos:

- GitHub: [github.com/htarod](https://github.com/htarod)

## Distribuição

Este projeto pode ser compartilhado livremente. Apenas lembre-se de incluir o arquivo `LEIA-ME.txt` junto com o `.exe` para uma melhor experiência do usuário. Se te ajudar e quiser pagar um cafezinho. chave pix: agatharod@gmail.com 
Valeu!
