# Infográfico Interativo: O Panorama das Fraudes Bancárias no Brasil

## 📖 Sobre o Projeto

Este projeto é uma **Single-Page Application (SPA)** em formato de infográfico interativo, projetada para apresentar de forma clara e impactante os dados e as nuances do cenário de fraudes bancárias e engenharia social no Brasil.

O objetivo é servir como uma ferramenta de apoio visual e informativa para a apresentação na **Comissão de Direito Bancário da OAB/RN**, além de funcionar como base para a criação de uma cartilha educativa para o público geral.

## ✨ Funcionalidades

O infográfico está estruturado para contar uma história, guiando o usuário desde a dimensão do problema até as soluções práticas e legais.

* **Visualização de Dados Dinâmica:** Gráficos interativos (Barras e Roscas) criados com **Chart.js** para exibir estatísticas de prejuízos, taxas de crescimento e recuperação de valores.
* **Conteúdo Estruturado:** Seções detalhadas sobre:
    * O impacto econômico bilionário.
    * A migração do crime do ambiente físico para o virtual.
    * O custo da defesa para as instituições financeiras.
    * A "anatomia" dos golpes mais comuns.
    * O ecossistema e a profissionalização do crime organizado.
    * A vulnerabilidade de grupos sociais específicos, como os idosos.
    * O cenário jurídico, incluindo a responsabilidade objetiva dos bancos (Súmula 479 do STJ).
    * Dicas práticas de prevenção e ação pós-golpe.
* **Assistente com Inteligência Artificial (Gemini API):** Uma ferramenta interativa chamada **"Assistente de Ação Pós-Fraude"** que permite ao usuário descrever um golpe sofrido e receber um plano de ação detalhado e personalizado, gerado em tempo real pela API do Gemini.
* **Design Moderno e Responsivo:** Desenvolvido com **Tailwind CSS**, o infográfico possui um design moderno (dark mode), profissional e se adapta a diferentes tamanhos de tela, de desktops a celulares.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica do conteúdo.
* **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.
* **JavaScript (ES6+):** Manipulação do DOM e lógica para interatividade.
* **Chart.js:** Biblioteca para criação dos gráficos interativos.
* **Gemini API:** Modelo de linguagem para a funcionalidade do assistente de ação.

## 🚀 Como Executar

Por ser um projeto autocontido em um único arquivo, a execução é extremamente simples:

1.  Clone ou baixe este repositório.
2.  Abra o arquivo `index.html` (ou o nome que você deu ao arquivo principal) em qualquer navegador de internet moderno (Google Chrome, Firefox, Microsoft Edge, etc.).

### Configuração da API do Gemini

Para que a funcionalidade do **"Assistente de Ação Pós-Fraude"** funcione, você precisa de uma chave de API do Google AI Studio.

1.  Obtenha sua chave de API em [Google AI Studio](https://aistudio.google.com/).
2.  Abra o arquivo HTML em um editor de código.
3.  Procure pela seguinte linha no bloco `<script>` no final do arquivo:

    ```javascript
    const apiKey = ""; 
    ```

4.  Insira a sua chave de API entre as aspas:

    ```javascript
    const apiKey = "SUA_CHAVE_DE_API_AQUI"; 
    ```

5.  Salve o arquivo. Agora, a funcionalidade estará ativa no seu navegador.

**Aviso:** Não exponha sua chave de API em repositórios públicos. Para um projeto em produção, o ideal seria gerenciar essa chave do lado do servidor.

---
*Desenvolvido para a Comissão de Direito Bancário da OAB/RN - Julho/Agosto de 2025*