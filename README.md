https://prototipo-eight.vercel.app/

- O site apresenta algumas características de responsividade, mas há margem para melhorias. Vou detalhar a responsividade atual do site:

- Barra de navegação (navbar): A barra de navegação é responsiva, pois utiliza classes do Bootstrap que garantem que o menu de navegação seja colapsado em 
- dispositivos --de tela menores, como smartphones. Isso garante uma experiência de navegação amigável em diferentes tamanhos de tela.

- Formulário de consulta: Os elementos do formulário estão em colunas definidas pelo Bootstrap, o que permite que se adaptem ao tamanho da tela. Além disso, o estilo -- CSS personalizado adiciona margens e espaçamento adequados para diferentes dispositivos.

- Tabela de resultados: A tabela de resultados utiliza a classe table-responsive, o que permite que ela seja rolada horizontalmente em dispositivos de tela menores 
- para -evitar a quebra de layout. No entanto, a largura máxima da tabela está definida como 1000px, o que pode não ser ideal em telas menores.

- Estilo personalizado para telas menores: Há uma regra de mídia (@media) que ajusta o estilo da tabela para telas menores (menos de 768px de largura), garantindo que 
- ela ocupe 100% da largura da tela. Isso ajuda a manter a legibilidade e usabilidade em dispositivos móveis.

- No entanto, para uma responsividade mais completa, seria recomendável ajustar alguns elementos:

