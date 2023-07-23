# Fuzzy com exemplos nas gorjetas

Este é um exercício de um curso que aborda o cálculo de gorjetas em restaurantes utilizando a lógica fuzzy. A lógica fuzzy é uma abordagem matemática que permite trabalhar com valores imprecisos e incertos, tornando-a adequada para lidar com o raciocínio humano em situações onde as regras são vagas e subjetivas, como é comum em questões relacionadas à qualidade da comida e ao serviço prestado

##
<h2><strong>Dependências</strong></h2>

    pip install scikit-fuzzy

##
<strong>Regras do projeto</strong>

O algoritmo de cálculo de gorjetas utiliza as seguintes regras fuzzy:

- Se a qualidade da comida for *ruim* ou o serviço for *ruim* então a gorjeta será *baixa*
- Se o serviço for *médio* então a gorjeta será *média*
- Se o serviço for *bom* e a qualidade da comida for *saborosa* então a gorjeta será *alta*

Essas regras são fundamentadas em critérios subjetivos, mas comumente adotados na prática de cálculo de gorjetas em restaurantes.
##

<h3>Exemplo de uso</h3>

    # Exemplo 1: Serviço e qualidade da comida são considerados ruins
    calcular_gorjeta("ruim", "ruim")  # Saída: "Baixa gorjeta"
    
    # Exemplo 2: Serviço é classificado como médio
    calcular_gorjeta("médio", "saborosa")  # Saída: "Gorjeta média"
    
    # Exemplo 3: Serviço é classificado como bom e qualidade da comida é saborosa
    calcular_gorjeta("bom", "saborosa")  # Saída: "Alta gorjeta"
##

<h3>Conclusão</h3>

O código desenvolvido neste projeto é uma demonstração simples de como aplicar a lógica fuzzy para calcular gorjetas em restaurantes. É importante notar que a definição das regras fuzzy é subjetiva e pode variar de acordo com as preferências individuais. Portanto, esse sistema pode ser aprimorado e ajustado para melhor se adequar às necessidades específicas de um determinado estabelecimento ou contexto. A lógica fuzzy é uma poderosa ferramenta para lidar com incertezas e informações imprecisas, tornando-a uma abordagem valiosa em uma ampla gama de aplicações práticas.
