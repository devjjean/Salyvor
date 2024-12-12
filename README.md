DESCRIÇÃO:

Salyvor é um modelo moderno e bonito, bem elaborado e responsivo, criado para exibir seu software e aplicativo móvel. Construído com código limpo e organizado em CSS3 e HTML5, este template é muito fácil de personalizar. É pronto para dispositivos móveis e compatível com telas retina/hi-dpi, o que significa que ficará ótimo em qualquer dispositivo, desde celulares até desktops, com resoluções e displays nítidos e nítidos. Este modelo elegante é perfeito para exibir seu software e aplicativo móvel.

==================================================================================================

USANDO O FORMULÁRIO DO MAILCHIMP:

Para usar o formulário do Mailchimp, você precisa de uma URL do Mailchimp. Para obter a URL do Mailchimp, faça login na sua conta Mailchimp, clique no menu "Listas", depois clique em "Estatísticas" e selecione "Formulários de inscrição". Então, escolha "Formulários incorporados" e selecione "Formulário nu". No código gerado do formulário, obtenha o valor do atributo "ACTION" e use-o como sua URL do Mailchimp. Abra o arquivo "main.js" localizado na pasta "js" do template e procure por esta linha de código:

javascript
Copiar código
var cfg = {
    scrollDuration: 800, // duração do smoothscroll
    mailChimpURL: 'https://facebook.us8.list-manage.com/subscribe/post?u=cdb7b577e41181934ed6a6a44&amp;id=e6957d85dc' // URL do mailchimp
},
Substitua o valor de "mailChimpURL" pela sua URL do Mailchimp e certifique-se de descomentar a chamada da função ssAjaxChimp() dentro da função ssInit():

javascript
Copiar código
(function ssInit() {

    ssPreloader();
    ssMobileMenu();
    ssFitVids();
    ssOwlCarousel();
    ssWaypoints();
    ssSmoothScroll();
    ssPlaceholder();
    ssAlertBoxes();
    ssAOS();
    ssBackToTop();

    // Para usar o formulário do Mailchimp, descomente a 
    // chamada da função ssAjaxChimp() abaixo:
    // ssAjaxChimp(); 

})();
LICENÇA:

Salyvor é liberado sob a Licença Creative Commons Atribuição 3.0 (http://creativecommons.org/licenses/by/3.0/). Isso significa que você pode:

Compartilhar - copiar, distribuir, exibir e realizar a obra
Remixar - criar obras derivadas
Fazer uso comercial da obra
Sob as seguintes condições:

Atribuição - Você deve atribuir a obra da maneira especificada pelo autor ou licenciante (mas não de forma que sugira que eles endossam você ou o uso da obra).

Para qualquer reutilização ou distribuição, você deve deixar claro para os outros os termos de licença desta obra.

Qualquer uma dessas condições pode ser dispensada se você obter permissão do titular dos direitos autorais.

Atribuição:
Você deve incluir um link de crédito para o nosso site (http://www.Styleshout.com) em algum lugar do seu site. Preferimos o crédito no rodapé que vem com o template, mas você pode movê-lo para outro lugar.

REMOVENDO O LINK:

Entendemos que há situações em que você deseja usar o template sem a obrigação de atribuição. Se for o seu caso, você pode enviar uma taxa de remoção do crédito de 10 USD através do PayPal. Isso permitirá que você use o template sem o link de atribuição/crédito em UM NOME DE DOMÍNIO.

Você pode enviar seus pagamentos pelo PayPal para o seguinte endereço: ealigam@gmail.com

Se possível, envie-nos a URL do site onde o template está sendo usado. Além disso, guarde o recibo do PayPal como comprovante de pagamento e está tudo certo.

SUPORTE:

Como o Salyvor é distribuído gratuitamente, o suporte não é oferecido. O Salyvor é codificado de acordo com os padrões atuais da web e fizemos o nosso melhor para tornar o template fácil de usar e modificar. Se você tem alguma experiência mínima em desenvolvimento web, pode modificar facilmente o template. No entanto, se você ainda é iniciante em HTML e CSS, sugerimos que você visite os seguintes tutoriais:

http://tutsplus.com/course/30-days-to-learn-html-and-css/
http://learn.shayhowe.com/html-css/
Esses tutoriais ensinarão os conceitos essenciais de HTML e CSS. Além disso, se você quiser incluir o jQuery em seu conjunto de habilidades, pode conferir esses tutoriais:

http://code.tutsplus.com/courses/30-days-to-learn-jquery
http://try.jquery.com/
FONTES E CRÉDITOS:

Eu usei os seguintes recursos, conforme listado.

Fontes:

Montserrat Font (https://www.google.com/fonts/specimen/Montserrat)
Muli Font (https://fonts.google.com/specimen/Muli)
Ícones:

Font Awesome (http://fortawesome.github.io/Font-Awesome/)
Micons Free Icons (http://geticonjar.com/freebies/231-micons/)
Webfont gerado pelo ICOMOON (https://icomoon.io/)
Fotos e Gráficos de Estoque:

Unsplash.com (https://unsplash.com/)
Relate UI Kit (https://www.invisionapp.com/relate)
Arquivos Javascript:

JQuery (http://jquery.com/)
Modernizr (http://modernizr.com/)
Waypoints (http://imakewebthings.com/jquery-waypoints/)
jQuery Placeholder (https://github.com/mathiasbynens/jquery-placeholder)
FitVids (http://fitvidsjs.com/)
pace js (http://github.hubspot.com/pace/)
Masonry (http://masonry.desandro.com/)
ajaxChimp (https://github.com/scdoshi/jquery-ajaxchimp)
animate on scroll (https://michalsnik.github.io/aos/)
parallax.js (http://pixelcog.github.io/parallax.js/)
Owl Carousel (https://owlcarousel2.github.io/OwlCarousel2/)
