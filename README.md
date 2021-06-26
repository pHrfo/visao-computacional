# MAC0417/5768 - Visão e Processamento de Imagens (2021)

Repositório para o código e documentação do projeto da disciplina MAC5768 - Visão e Processamento de Imagens.


# Links Importantes

- [Google Drive](https://drive.google.com/drive/folders/1h32IZ0kYQigYiCt4KmdtZNXUOOX8Rd3D?usp=sharing)
- [Google Colab - EP1](https://colab.research.google.com/drive/1bKeuS6A_Wby7FViM4tVIsU6HrG-0nFqZ#scrollTo=ky7hClV8Ge7u)

# Grupo

* **Andreza Lukosiunas** - [@andrezasp](https://github.com/andrezasp) (nusp: 7157922)
* **Juliano Garcia** - [@robotenique](https://github.com/robotenique) (nusp: 9277086)
* **Pedro Carvalho** - [@pHrfo](https://github.com/pHrfo) (nusp: 11376164)

# EP1

A base de dados criada para o EP1 está disponível na pasta do Google Drive. O notebook com a tabela sumarizada e visualização da base está disponível tanto na pasta [ep1](ep1/) como no link do Google Colab exibido na seção de **Links Importantes**.

Para executar o notebook visao_computacional_ep1.ipynb, basta rodar as células na ordem. A função plot_mnist requer entrada True (padrão) ou False. True mostra a classe desejada. False, todas as classes.

O metadados.csv com todos as especificações das imagems está na pasta metadados do google drive.

# EP2

O EP2 consiste em 2 notebooks, a parte 1 e a parte 2.

### Parte 1
Nas primeiras células, as funções para geração das imagens que serão salvas nos folders originalGrayDataset, augmentedDataSet e normalizedDataset são declaradas. Em seguida, o metadados do EP1 é carregado. 
A descrição das funções segue abaixo. 
OBS.: run_all = True, roda todas as 3 funções da célula, caso run_all = False, não roda, esse declaração serve como uma trava. Para rodar determinada função, run=True, cc, run=False
* new_folder - deleta os folders originalGrayDataset, augmentedDataSet e normalizedDataset, caso existam, para criação de novos
* create_img_filtered - cria todas as imagens para o originalGrayDataset e augmentedDataSet, essas imagens são filtradas com os métodos: rgb2gray, soma de fundo com gradiente em níveis de cinza, logaritmo da imagem, exponencial da imagem e filtro da média com convolução. Essa funçao também cria os metadados metadados_originalGrayDataset e metadados_augmentedDataset e salva-os em .csv
* create_img_normalized - cria todas as imagens para o normalizedDataset provenientes do folder augmentedDataSet com o método de equalização. Essa funçao também cria o metadados metadados_normalizedDataset e salva-os em .csv
Logo após a criação das imagens, os novos metadados são carregados e cruzados com o metadados principal (EP1). 
A célula final contém os plots das imagens filtradas.




# EP3

TBD
