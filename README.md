## Serasa

## Substituir os arquivos PNG por WebP

![Screenshot](https://github.com/willysilva/serasa-desc/blob/main/webp.jpeg?raw=true)

O WebP oferece tamanhos de arquivo 26% menores que o PNG, enquanto ainda oferece transparência e a mesma qualidade.

O WebP carrega mais rápido (devido ao tamanho do arquivo) do que as imagens PNG.

fonte: [InsaneLab](https://insanelab.com/blog/web-development/webp-web-design-vs-jpeg-gif-png/)

## Utilizar Clean Architecture

![Screenshot](https://blog.cleancoder.com/uncle-bob/images/2012-08-13-the-clean-architecture/CleanArchitecture.jpg)

A clean Architecture quando bem utilizada organiza o código e facilita o trabalho em equipes grandes
pela independência de camadas.

Vantagens: Desacoplar o código e tornar as camadas independentes, reaproveitamento de código

Ponto de atenção: a mudança estrutural para se adaptar
a clean architecture seria extremamente trabalhosa e custosa, e o time precisaria de muita maturidade para lidar com isso.

fonte: [Uncle Bob](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

## Utilizar Islands Architecture

![Screenshot](https://res.cloudinary.com/ddxwdqwkr/image/upload/v1633284886/patterns.dev/theislandsarch--avuxy9rrkk8.png)

A Island Architecture incentiva pequenos pedaços "Chunks" focados em páginas da Web renderizadas pelo servidor.

Vantagens:
Diminui significativamente a quantidade de javascript para renderizar a página.

O código enviado consiste apenas no script necessário para componentes interativos, que é muito menos do que o script necessário para recriar o DOM virtual para a página inteira e renderizar todos os elementos da página.

É possível definir prioridades e carregar o que for mais importante primeiro.

Melhora Acessibilidade, O uso de links HTML estáticos padrão para acessar outras páginas ajuda a melhorar a acessibilidade do site.

fonte: [Patterns](https://www.patterns.dev/posts/islands-architecture/)
