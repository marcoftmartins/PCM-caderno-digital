# PCM-caderno-digital
Caderno digital para a disciplina de Produção de Conteúdos Multimédia.

---

## Compressão de Imagens
Existem essencialmente dois tipos de compressão de imagens : 
* *Sem perda de dados*
* *Com perda de dados*

### Compressão sem perdas
Devemos aplicar uma compressão sem perda de dados quando a ***elevada qualidade*** é um fator determinante, como por exemplo para um fotógrafo profissional ou uma rádiografia, quanto mais detalhe na imagem houver, melhor.  
Exemplos de formatos : PNG , TIFF

### Compressão com perdas
A compressão com perda de dados deve ser usada quando o fator de ***portabilidade ou redução do tamanho*** da mesma é mais importante. Por exemplo para usar numa rede social.  
Exemplos de formatos : JPEG , GIFF

### Comparação entre *PNG* e *JPEG*

| PNG | JPEG |
|------|-------|
|![image](https://www.infowester.com/img_art/form_img/comppng.png)|![image](https://www.infowester.com/img_art/form_img/compjpeg.jpg)|

---
## Canais de Cor
Cada imagem é formada por um conjunto de pixeis, e cada pixel é uma combinação de cores, mais precisamente cores primárias. Existem dois grandes tipos de imagem: Imagens ***Grayscale*** e imagens ***RGB***.

### Imagens Grayscale
As imagens ***Grayscale*** são constituidas apenas por um canal, cada pixel da imagem contém a informação relativamente à luminosidade. São imagens exclusivamente feitas com diferentes tons de cinza. A intensidade da luz poderá variar entre o valor 0 e o valor 255, sendo que 0 representa o preto e 255 o branco.  

| Exemplo imagem grayscale |
| ---- |
![image](https://cdn.pixabay.com/photo/2017/12/27/03/06/birch-3041856_960_720.jpg)

### Imagens RGB
As imagens ***RGB*** são constituidadas por três canais, R de *Red*/Vermelho, G de *Green*/Verde e B de *Blue*/Azul. Neste caso o valor das cores variam entre 0 e 255, sendo este o valor da intensidade da cor, 0 representa a ausência da cor (preto) e 255 representa ao tom mais brilhante de cada cor. Geralmente a cada cor é dividida em 8 *bits*, sendo assim possível os 256 tons para cada cor.

Existe ainda o ***RGBA***, que funciona da mesma maneira que o ***RBG*** porém usa mais um canal, A de *Alpha*, para representar a transparência. Os valores variam também de 0 a 255, onde 0 é a transparência total do pixel e 255 é totalmente opaco. O formato *PNG* usa o sistema ***RGBA***

| Exemplo imagem RBG |
| ---- |
![image](https://cdn.pixabay.com/photo/2020/08/05/20/56/keyboard-5466431_960_720.jpg)

---

## Bitmaps
