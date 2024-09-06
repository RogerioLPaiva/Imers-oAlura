Markdown
## Paisagens Sul-Matogrossenses

### Descrição
Este projeto web tem como objetivo apresentar as principais paisagens naturais do Mato Grosso do Sul, oferecendo informações detalhadas sobre cada local e um mapa para facilitar o planejamento de viagens.

### Tecnologias Utilizadas
* **HTML:** Estruturação da página.
* **CSS:** Estilização da página.
* **JavaScript:** Interatividade e busca de dados.

### Estrutura de arquivos
* **index.html:** Página principal do projeto.
* **style.css:** Arquivo de estilos CSS.
* **dados.js:** Arquivo contendo os dados das paisagens (nome, descrição, link do mapa).
* **app.js:** Lógica JavaScript para a busca e renderização dos resultados.

### Funcionamento
1. **Busca:** O usuário digita o nome da paisagem desejada no campo de pesquisa.
2. **Filtragem:** O JavaScript filtra os dados no arquivo `dados.js` e retorna os resultados correspondentes.
3. **Renderização:** Os resultados da busca são exibidos na seção "resultados-pesquisa", com o nome da paisagem, uma breve descrição e um link para o mapa no Google Maps.

### Como executar
1. **Clonar o repositório:** Se o projeto estiver em um repositório Git, clone-o para sua máquina local.
2. **Abrir o arquivo HTML:** Abra o arquivo `index.html` em um navegador web.

### Contribuições
Contribuições são bem-vindas! Para contribuir com este projeto, siga estes passos:
1. Fork este repositório.
2. Crie um novo branch para sua feature.
3. Faça as suas alterações e commit.
4. Envie um pull request.

### Próximos passos
* **Incluir mais dados:** Adicionar mais paisagens e informações detalhadas sobre cada local.
* **Melhorar a interface:** Criar um design mais atraente e intuitivo.
* **Implementar um mapa interativo:** Utilizar uma biblioteca de mapas para criar um mapa personalizado com marcadores para cada local.
* **Adicionar filtros:** Permitir que o usuário filtre os resultados por região, tipo de atividade, etc.

### Observações
* **Dados:** O arquivo `dados.js` é fundamental para o funcionamento do projeto. Nele, você pode adicionar mais paisagens e personalizar as informações.
* **Estilização:** O arquivo `style.css` é responsável por definir a aparência visual da página. Você pode personalizar as cores, fontes e layout de acordo com suas preferências.
* **JavaScript:** O arquivo `app.js` contém a lógica principal do projeto. Você pode adicionar novas funcionalidades e melhorar o desempenho do código.

**Exemplo de estrutura do arquivo `dados.js`:**

```javascript
const paisagens = [
  {
    nome: 'Serra da Bodoquena',
    descricao: '...',
    linkMapa: 'https://...'
  },
  // ... outras paisagens
];
