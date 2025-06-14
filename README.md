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
Veja os arquivos 
-'Mostrando Sereal Print.png' : Contém uma imagem mostrando os dados sendo printados no seral print no Wokwi
-'Mostrando sensores.png': Mostra os sensores que foram utulizados funcionando.
-'Gráfico análise exploratória.png' : Mostra o gráfico simples da análise exploratória

## Organização
- 'codigo_esp32.ino': código do microcontrolador.
- 'analise_exploratoria_hermes_reply_sprint_2.ipynb': análise no Google Colab.
- 'sensores.md' : Markdown contendo a explicação do porque usar cada sensor.
- 'todos_os_dados_sensores.csv': Banco de dados simulado.
