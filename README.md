# Detecção de Pessoas usando YOLOv5

Este é um código Python que utiliza o modelo YOLOv5 para realizar a detecção de pessoas em uma imagem. O YOLOv5 é uma arquitetura eficiente para detecção de objetos em tempo real, e neste caso, estamos focando na identificação de pessoas.

## Pré-requisitos

Antes de executar o código, certifique-se de ter as seguintes dependências instaladas:

- PyTorch: `pip install torch`
- OpenCV: `pip install opencv-python`
- Google Colab: Se você estiver executando este código no Google Colab, algumas bibliotecas específicas do Colab serão necessárias.

## Executando o Código

No Google Colab, simplesmente abra o notebook e execute as células.

## Descrição do Código

- **Conexão ao Google Drive:** O código se conecta ao Google Drive para acessar a imagem que será processada.

- **Carregamento do Modelo YOLOv5:** Utiliza o PyTorch Hub para carregar o modelo YOLOv5s pré-treinado.

- **Movendo o Modelo para GPU :** Move o modelo para a GPU para aceleração de hardware.

- **Definindo o Modelo para Modo de Inferência:** Coloca o modelo no modo de inferência, desativando camadas como dropout.

- **Realizando Inferência:** Passa a imagem pelo modelo YOLOv5 e obtém os resultados da detecção.

- **Extraindo Bounding Boxes:** Extrai as coordenadas das bounding boxes detectadas no formato DataFrame do Pandas.

- **Contando Pessoas Detectadas:** Itera sobre as bounding boxes, conta o número de pessoas e imprime o resultado.

- **Desenhando Bounding Boxes na Imagem:** Desenha retângulos delimitadores nas posições das bounding boxes na imagem original.

# Colaborador 
<table>
<table>
  <tr>
    <td align="center"><a href="https://github.com/guiaech"><img src="https://avatars.githubusercontent.com/u/83043492?v=4" width="100px;" alt=""/><br /><sub><b>Guilherme Andrade</b></sub></a></td>
  </tr>
</table>

