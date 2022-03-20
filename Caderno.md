# Curso_HTML_CSS
 Repositório para curso do Guanabara
### C01A02
Links importantes:

 * [Repositorio do Guanabara](https://github.com/gustavoguanabara/html-css)
 * [Site](https://gustavoguanabara.github.io/)

### C01A03

Bibliografia recomendada:

1. [W3C Standards](https://www.w3.org/standards/webdesign/)
2. [WHATWG Living Standard](https://html.spec.whatwg.org)
3. [W3Schools](https://www.w3schools.com)

### C01A04

A **Intenet** veio da ARPANET, que era para militares.
(Neste site)[https://www.submarinecablemap.com/] mostra quantos cabos subimarinos estão em operação atualmente.

### C02A01
 * Codigo Multibyte UTF-8(para letras)
 * 2**10 = 1024
 * De quadrada > cenoidal = modulação
   
   De cenoidal > quadrada = demodulação
   
   MOdulação + DEModulaçao = modem
 * Para descobrir seu ip, basta entrar [neste site](https://www.iplocation.net/), e no mesmo encontra o ip do servidor de outros sites.
### C03A01
 * HTML = HyperText Markup Language = Linguagem de marcação hipertexto
   * Focada em conteudo(textos, imagens, vídeos, tabelas)
 * CSS = Cascading Style Sheets = Folhas de estilo em cascata
   * Focada em design(Cores, sombras, tamanhos, posicionamento)
 * JS interatividade(menus, animações, popups, validações)
Conteudo em HTML
<img width="613" alt="image" src="https://user-images.githubusercontent.com/84166332/151681226-158d2d37-430f-4781-a98c-aa501e6f18cf.png">
Estilos em CSS
<img width="338" alt="image" src="https://user-images.githubusercontent.com/84166332/151681268-7702826c-8f88-4578-9e4b-91f895ca2a23.png">
Estrutura basica de documentos HTML
<img width="603" alt="image" src="https://user-images.githubusercontent.com/84166332/151681385-bde8346d-9cd3-4cc3-9654-368291df3faa.png">

### C03A02

 * Front-end = client-side
 * Back-end = server-side

### C04A02

<img width="229" alt="image" src="https://user-images.githubusercontent.com/84166332/151683243-53e36f15-1349-4157-b283-3e9e3d654b22.png">

### C05A01

Para quebrar linha basta utilizar o `<br>` no meio da fraze.

Sinal de < e > são feitos assim `&lt;` e `&gt;`

### C05A02

Para colocar emoges basta colocar entra no site [emojipedia](https://emojipedia.org/people/):

![Animação](https://user-images.githubusercontent.com/84166332/152274229-d01d0079-950e-41b6-90bc-1c2597b91933.gif)

### C06A01

Sites que so tem imagens de domínio público: 
 * [UnSplash](https://unsplash.com/) 
 * [Pexels](https://www.pexels.com/pt-br/) 
 * [Freepik](https://www.freepik.es/) 
 * [Rawpixel](https://www.rawpixel.com/) 
 * [Pixabay](https://pixabay.com/pt/) 
 * [Libreshot](https://libreshot.com/) 
 * [Wikimedia Commons](https://commons.wikimedia.org/wiki/Commons:Featured_pictures?uselang=pt-br) 
 * [Google images](https://www.google.com/search?q=imagens&tbm=isch&hl=pt-br&tbs=il:cl&sa=X&ved=0CAAQ1vwEahcKEwjQrrWrw-T1AhUAAAAAHQAAAAAQAg&biw=1079&bih=534) E também no google imagens o __*Licenças Creative Commons*__ ativado.
> Alguns desses sites que disponibilizam imagens de domínio
público possuem propagandas de serviços de venda de imagens e acabam te
confundindo um pouco.

### C06A02

Tipos de imagens:

tipos | compactado | transparencia | animação
:---: | ---: | :---: | :---:
JPEG | com perdas | não | não
GIF | poucas perdas | sim | sim
PNG | poucas perdas | sim | sim

### C06A05

Sites utilizados na  aula:
 * [favicon.cc](https://www.favicon.cc/)Para fazer icones
 * [iconarchive](https://iconarchive.com/)Para encontrar icones]
 * [favicon.io](https://favicon.io/)Para transformar imagens em icones

### C07A01

H1 não é letra grande, e titulo de nivel 1.

### C08A01

Para ver as tags obsoletas basta ver [este site](https://dev.w3.org/html5/pf-summary/obsolete.html)

### C08A02

Seleciona > CTR + SHIFT + P > Enter > digite a marcação.

![Comando](https://user-images.githubusercontent.com/84166332/152878879-5b5f83f3-58d8-4bca-afbb-810beec7b138.gif)

### C09A02

Para selecionar varias marcações para edição:

![selecionar com alt](https://user-images.githubusercontent.com/84166332/153084108-db1e0772-91cd-4fd4-925e-f804ab4e1734.gif)
 
### C10A01

Para abrir links em outra aba basta colocar este codigo apos a abertura da href `target="_blank" rel="external`

### C10A03

Para ver o type correto para download de links, basta entrar no [iana.org](https://www.iana.org/assignments/media-types/media-types.xhtml)

### C11A02

Para colocar imagens adapitativas ao tamanho, usando apenas o HTML5 basta:
``` 
<picture>
    <source media="(max-width: 750px)" srcset="Imagem grande" type="image/png">
    <source media="(max-width: 1000px)" srcset="Imagem media" type="image/png">
    <img src="Imagem principal" alt="Imagem flexível">
</picture>
```

### C11A03

Para conseguir musicas gratis no [Youtube](https://studio.youtube.com/channel/UC1lZeLG7SLx9y5fw8wz24hQ/music).

Uma das formas de colocar audios no HTML5 é:
```
    <audio src="audio.mp3"controls autoplay></audio>
  ```

### C11A04

Para diminuir arquivos basta usar o programa [handbreak](https://handbrake.fr/)

### C11A06

[Vimeo](https://vimeo.com/) Para vídeos autorais.

### C11A07

Site para pegar [Thumbnails](https://ferramentas.seletronic.com.br/miniaturas-youtube/)

### C12A03

 * É possível colocar mais de 1 arquivo CSS dentro do `link:css`
 * A prioridade dos Estilos são respectivamente: 
   * Inline (Tem maior excalabilidade)
     * Locais / Internos (Pequenos extilos)
       * Externos (Evite)

### C13A02

Existe 3 formas de representação de cores e estas são:

  * Pelo nome da cor 
  * Por Hexadecimal
  * Por códigos RGB
  * por HSL ((Hue, Sturation, Luminosity)Tom, Saturação, Luminozidade)
  
### C13A04

Site da [adobe](https://color.adobe.com/pt/create/color-wheel) e [Paletton](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF) para escolha de cores para desiner. 

E para algo mais inicial use o [Coolors](https://coolors.co/fffbfc-62bbc1-ec058e-0f0326-3a606e)

### C13A05

Para conseguir as cores de sites usar a extenção [ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp/related?utm_source=chrome-ntp-icon)
  * Pelo nome da cor                                
![image](https://user-images.githubusercontent.com/84166332/158719118-5a7764fc-305c-4adb-bb59-5ea9774a6563.png)

  * Por Hexadecimal                                        
![image](https://user-images.githubusercontent.com/84166332/158718943-509cf619-a0c6-4c01-8fac-45de4441a126.png)

  * Por códigos RGB                                        
![image](https://user-images.githubusercontent.com/84166332/158719001-121d0e3f-7675-497d-8576-1d98a5d92322.png)

  * por HSL ((Hue, Sturation, Luminosity)Tom, Saturação, Luminozidade) 
![image](https://user-images.githubusercontent.com/84166332/158719050-ac8cf7ac-877f-49ab-892f-0db1086f68cd.png)

Resultado:![image](https://user-images.githubusercontent.com/84166332/158719359-4b0e3ee3-38e6-47a2-81c7-40202de313a6.png)

#### Mecherndo na opacidade:
![Mecher na opacidade ](https://user-images.githubusercontent.com/84166332/158719959-e95e5dc8-5b8d-4f8e-9273-e27e640e3585.gif)

### C14A02

itens metricos de a anatomia de tipos:

![image](https://user-images.githubusercontent.com/84166332/159139602-d42f393c-5477-434a-873f-3ce2552a46bd.png)
 
Itens anatomicos:

![image](https://user-images.githubusercontent.com/84166332/159139702-e0842adc-5aa3-4fbd-b6c2-d350553e8230.png)

 * Letras = Glifos 
 * Todos as letras = fonte
 * Familias tipograficas = varias letras diferentes da original da mesma fonte(normalmente mais grossas).
   * ![image](https://user-images.githubusercontent.com/84166332/159140094-d75f09db-53b1-41dd-8d7e-094ee665b72d.png)

### C14A03

Para achar as [combinações de fontes ](http://www.w3bai.com/en-US/cssref/css_websafe_fonts.html), chamadas de safes combinations.

### C14A04

Não confundir com: wight(peso) width(largura) heitght(autura)
Ordem para o shorthand = - font-style -> font-weight -> font-size -> font-family.

### C14A06

Para achar fonts use o [Google fonts](https://fonts.google.com/)

### C14A07

Para encontrar fontes mais diferentes [dafont](https://www.dafont.com/pt/)

### C14A08

Para encontrar fonts em sites css usar a extenção [Fonts Ninja](https://chrome.google.com/webstore/detail/fonts-ninja/eljapbgkmlngdpckoiiibecpemleclhh?utm_source=chrome-ntp-icon)

### C14A09

Para encontrar fonts em imagens use os sites : [Whatfontis](https://www.whatfontis.com/), [fontsquirrel](https://www.fontsquirrel.com/), 
[myfonts](https://www.myfonts.com/).