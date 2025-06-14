# Manutenção Preditiva com ESP32 (Simulação)

## Objetivo
Criar um sistema de manutenção preditiva usando sensores virtuais com ESP32 para identificar falhas antes que as máquinas parem de funcionar.

## Sensores Utilizados
- DHT22 (temperatura e umidade)
- MPU6050 (vibração)
- Potenciômetro (simulação analógica)

## Funcionamento
- Os sensores simulados enviam dados ao ESP32 via Wokwi.
- Os dados são exibidos no Monitor Serial e salvos para análise.
- Um script em Python no Google Colab gera gráficos e estatísticas iniciais.

## Análise Exploratória
- Foram observadas variações nos sinais que representam possíveis anomalias.
- Aceleração excessiva ou temperatura fora do padrão indicam necessidade de manutenção.

## Prints
Veja a pasta `/imagens/` com prints da simulação, console e gráfico.

## Organização
- `codigo_esp32.ino`: código do microcontrolador.
- `dados/`: contém os dados exportados.
- `colab_analise_exploratoria.ipynb`: análise no Google Colab.
