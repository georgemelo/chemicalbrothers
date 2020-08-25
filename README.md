# chemicalbrothers
Site desenvolvido em HTML5 e CSS3 Responsivo, o mesmo foi validado pela W3C. 
Não foi utilizado framework e sim um sistema de Grids e conceitos de OOCSS. 
Foi inseridoo SHIV JS para reconhecer Tags do HTML5 em navegadores antigos, 
e a utilização das meta tags, animate.css no menu e logo. Media Queries 
para formatação adequada em diversos dispositivos.


#Web Design Responsivo

##Biblioteca, recursos e tecnologias utilizados:

- Meta tag para visualização em qualquer dispositivo e compatibilidade em navegadores antigos (IE 9) e SEO.
- animate.css (https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css)
- Media Queries.
- html5shiv.js (https://github.com/aFarkas/html5shiv/blob/master/dist/html5shiv.js)
- CSS Sprites Optimization.

Imagem com fundo transparente que aceitará qualquer cor, ex.:

```css
.fundoTopo {
	background-image: url("img/line.png");
	background-repeat: no-repeat;
	background-position: bottom center;
	background-size: 100%
}
.verde {
	background-color: #609E1B;
	color: #fff;
}
.preto {
	background-color: #333;
	color: #ccc
}
```
<p>
**Markup and CSS Validation Service: W3C**(https://validator.w3.org/)
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="CSS válido!" />
    </a>
</p>

- Slide Animation: Opacidade e tempo de transição de uma imagem para outra.

```css
.slide {
	height: 350px;
	border: 5px solid #fff;
	position: relative;
	text-align: left
}
.slideImagem {
	position: absolute;
	opacity: 0;
	animation: animaSlide 15s infinite;
	-webkit-animation: animaSlide 15s infinite;	
}
@keyframes animaSlide {
	25% {
		opacity: 1
	}
	75% {
		opacity: 0
	}
}
.slideImagem:nth-child(0) {
	animation-delay: 0s
}
.slideImagem:nth-child(1) {
	animation-delay: 5s
}
.slideImagem:nth-child(2) {
	animation-delay: 10s
}
```
- **Utilização das tags: video, audio, iframe e address.**
- **Inserção de mapa via Google Maps.**

####Markdown editor: pandao.github.io/

####Provedor de imagem: imgur.com
![Topo](https://i.imgur.com/fIn6EaX.png "Topo")![meio](https://i.imgur.com/sP4asxn.png "meio")![Audios e videos](https://i.imgur.com/8B3IGZj.png "Audios e videos")![Footer](https://i.imgur.com/UEyannl.png "Footer")
