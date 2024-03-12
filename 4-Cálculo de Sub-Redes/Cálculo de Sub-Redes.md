# Cálculo de Sub-Redes
### O cálculo de sub-redes é uma etapa importante na configuração de redes de computadores. Aqui está um resumo dos passos envolvidos:

1. **Identificar o endereço IP da rede**: Determine o endereço IP da rede e a máscara de sub-rede fornecida.

2. **Converter a máscara de sub-rede para binário**: Converta a máscara de sub-rede de decimal para binário. Por exemplo, uma máscara de sub-rede 255.255.255.0 é igual a 11111111.11111111.11111111.00000000 em binário.

3. **Identificar o número de bits de host**: Conte o número de bits de host na máscara de sub-rede. Isso determinará quantos hosts podem ser acomodados em cada sub-rede.

4. **Calcular o número de sub-redes**: Com base no número de bits de host, calcule quantas sub-redes podem ser criadas a partir do endereço IP da rede.

5. **Determinar o tamanho de cada sub-rede**: Calcule o número de endereços IP disponíveis em cada sub-rede, incluindo o endereço de rede e o de broadcast.

6. **Identificar os intervalos de endereços IP de cada sub-rede**: Determine os intervalos de endereços IP disponíveis para cada sub-rede, garantindo que o endereço de rede e o de broadcast sejam reservados.

Esses são os passos básicos envolvidos no cálculo de sub-redes. É importante entender esses conceitos para projetar e configurar redes de computadores de forma eficaz.