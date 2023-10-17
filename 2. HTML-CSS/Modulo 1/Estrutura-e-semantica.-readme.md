A estrutura semântica do HTML5 é uma das características mais importantes dessa versão, pois introduziu várias novas tags que descrevem a estrutura do conteúdo de uma página de forma mais significativa. Essas tags ajudam os mecanismos de busca e leitores de tela a entenderem melhor o conteúdo da página, tornando-a mais acessível e compreensível para humanos e máquinas. Aqui estão algumas das principais tags de estrutura semântica em HTML5:

<header>: Essa tag representa a introdução de uma seção ou de todo o conteúdo da página e geralmente contém o logotipo, título, links de navegação e outros elementos de cabeçalho.

<nav>: Usada para definir uma seção de navegação, contendo links para outras páginas ou partes do site.

<article>: Define uma seção de conteúdo independente que pode ser distribuída e reutilizada separadamente do restante da página. Pode ser um artigo, uma postagem de blog, uma notícia, etc.

<section>: Essa tag agrupa conteúdo relacionado dentro de uma página e pode ter seu próprio cabeçalho e ser usada para dividir o conteúdo em partes organizadas.

<aside>: Usado para conteúdo relacionado, mas que é separado do conteúdo principal, como barras laterais, informações relacionadas, anúncios ou widgets.

<footer>: Define o rodapé da página ou de uma seção, geralmente contendo informações de copyright, links para políticas de privacidade, informações de contato, etc.

Aqui está um exemplo de uso dessas tags:

<br>

``` html
<!DOCTYPE html>
<html>
<head>
    <title>Exemplo de Estrutura Semântica</title>
</head>
<body>
    <header>
        <h1>Meu Site</h1>
        <nav>
            <ul>
                <li><a href="/">Página Inicial</a></li>
                <li><a href="/sobre">Sobre</a></li>
                <li><a href="/contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section>
        <h2>Artigo Principal</h2>
        <article>
            <h3>Meu Primeiro Artigo</h3>
            <p>Este é um artigo sobre algo importante.</p>
        </article>
        
        <article>
            <h3>Outro Artigo</h3>
            <p>Este é outro artigo relacionado.</p>
        </article>
    </section>
    
    <aside>
        <h3>Barra Lateral</h3>
        <p>Conteúdo da barra lateral...</p>
    </aside>
    
    <footer>
        <p>&copy; 2023 Meu Site</p>
    </footer>
</body>
</html>
```