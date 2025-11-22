# Mapa Histórico da Evolução da Hanseníase no Brasil

Este repositório contém o código Python para gerar um mapa visualizando a evolução histórica da hanseníase no Brasil, cobrindo dois períodos cruciais:

*   **Séc. XVII-XVIII: Chegada e Primeiros Focos** - Ilustra os pontos iniciais de entrada e os primeiros focos da doença no litoral brasileiro.
*   **Séc. XVIII-XIX: Interiorização e Expansão** - Apresenta a dispersão da hanseníase para o interior do país, guiada por vetores econômicos e movimentos como as Bandeiras.

O mapa é gerado utilizando a biblioteca `geopandas` para manipulação de dados geoespaciais e `matplotlib` para a visualização, com base em dados de estados do Brasil obtidos de uma fonte GeoJSON online.

## Como Usar o Notebook Google Colab

Para interagir com este projeto, você pode abrir o notebook diretamente no Google Colab:

1.  **Abrir no Colab:** Clique no botão "Open in Colab" (ou equivalente) que você configurou no seu README do GitHub, ou faça o upload do arquivo `.ipynb` diretamente no Colab.
2.  **Instalar Dependências:** Execute a primeira célula do notebook (`pip install geopandas matplotlib`) para garantir que todas as bibliotecas necessárias estejam instaladas no ambiente de execução do Colab.
3.  **Gerar o Mapa:** Execute a célula que contém a definição da função `gerar_mapa_historico()` e, em seguida, a célula que a chama (`gerar_mapa_historico()`).
4.  **Visualizar e Salvar:** O mapa será exibido diretamente no notebook. A função já está configurada para salvar o mapa como `mapa_hanseniase_fase2.png` na raiz do ambiente de execução do Colab.

## Referência Bibliográfica (ABNT)

Se você utilizar o mapa gerado por este projeto em trabalhos acadêmicos, apresentações ou publicações, por favor, utilize a seguinte formatação de referência bibliográfica em ABNT, atribuindo a mim e mencionando a base cartográfica:

Exemplo:

CARVALHO, D. C. **. Visualização de dados geoespaciais gerada via Python com GeoPandas para mapa histórico da evolução de Hanseníase no Brasil.** 
[Mapa digital]. 2024. Base cartográfica: IBGE. Disponível em: https://github.com/zincarvalho/mapa_historico_hanseniase_br. Acesso em: 15 fev. 2024.

### Observações sobre a citação:
*   **Base Cartográfica:** O IBGE é mencionado como base cartográfica por ser uma fonte confiável e padrão para dados geográficos do Brasil, mesmo que os dados tenham sido acessados via um GeoJSON de terceiros, pois estes frequentemente derivam ou são compatíveis com as bases do IBGE.
