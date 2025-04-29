# Analisador de Regras de Associação

Projeto web interativo para explorar, pesquisar e exportar **regras de associação** baseadas em datasets de diferentes áreas (Aeronáutica, Incidentes, Saúde, Educação, etc.).

---

## 📚 Sobre o Projeto

Este sistema permite:

- 📂 Carregar arquivos `.xlsx` contendo regras de associação (Apriori / FP-Growth).
- 🔍 Pesquisar regras específicas usando termos-chave (Antecedentes e Consequentes).
- 📊 Visualizar as melhores regras ordenadas por:
  - **Lift**
  - **Confiança**
  - **Suporte**
- 📥 Exportar os resultados filtrados diretamente para um arquivo `.xlsx`, personalizado com o nome do dataset.

O projeto foi desenvolvido em HTML5, CSS3 e JavaScript moderno, utilizando a biblioteca **SheetJS** para manipulação de planilhas Excel.

---

## 🚀 Como Usar

1. Faça o clone ou download do projeto:
    ```bash
    git clone https://github.com/seu-usuario/projeto-regras-associacao.git
    ```

2. Estrutura de arquivos:
    ```
    /projeto-regras-associacao/
    ├── index.html
    ├── regras_associacao_acidente.xlsx
    ├── regras_associacao_incidente.xlsx
    ├── regras_associacao_incidente_grave.xlsx
    ├── regras_associacao_todas_variaveis.xlsx
    └── README.md
    ```

3. Abra o arquivo `index.html` diretamente no navegador.

4. Selecione um dos datasets disponíveis.

5. Digite termos de pesquisa (separados por vírgula) para encontrar regras.

6. Visualize os resultados nas categorias **Lift**, **Confiança** e **Suporte**.

7. Clique em **Exportar Resultado** para baixar as regras encontradas em Excel.

---

## 📦 Tecnologias Utilizadas

- **HTML5** – Estrutura da página.
- **CSS3** – Estilo responsivo e moderno.
- **JavaScript (Vanilla)** – Lógica de carregamento, busca e exportação.
- **SheetJS (xlsx.full.min.js)** – Manipulação de planilhas `.xlsx`.

---

## 📄 Estrutura dos Datasets Esperados

Cada planilha `.xlsx` deve conter, pelo menos, as seguintes colunas:

| Coluna         | Descrição                                  |
|:---------------|:-------------------------------------------|
| Antecedentes   | Itens ou eventos que precedem.             |
| Consequentes   | Itens ou eventos resultantes.              |
| Lift           | Grau de associação entre antecedente e consequente. |
| Confiança      | Probabilidade condicional entre antecedente e consequente. |
| Suporte        | Frequência relativa da regra no dataset.   |

---

## 📋 Funcionalidades

- ✅ Carregamento dinâmico de arquivos Excel.
- ✅ Pesquisa de regras por múltiplos termos (case insensitive).
- ✅ Ordenação automática dos melhores resultados.
- ✅ Exportação dos 15 melhores resultados filtrados.
- ✅ Nome de arquivo dinâmico conforme o dataset selecionado.

---

## 📢 Observações

- Todos os dados são carregados localmente no navegador.  
  **Nenhuma informação é enviada para servidores externos.**
- A aplicação é compatível com Google Chrome, Mozilla Firefox e Microsoft Edge.
- Funciona 100% offline após o carregamento inicial.

---

## 🧑‍💻 Desenvolvido por

**[Seu Nome ou Organização]**  
Especialista em Ciência de Dados, Análise Estatística e Aprendizado de Máquina.

[LinkedIn](https://www.linkedin.com/in/seu-usuario) | [GitHub](https://github.com/seu-usuario)

---

## 📜 Licença

Este projeto é licenciado sob a Licença MIT.  
Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
