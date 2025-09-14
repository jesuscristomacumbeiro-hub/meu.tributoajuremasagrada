<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tributo à Jurema e Meu Juremeiro</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family: 'Roboto', sans-serif; scroll-behavior: smooth; overflow-x: hidden; }

    /* MENU LATERAL */
    nav {
        position: fixed;
        left: 0;
        top: 0;
        height: 100%;
        width: 200px;
        background: #2c7a7b;
        display: flex;
        flex-direction: column;
        padding-top: 50px;
        z-index: 999;
    }
    nav a {
        color: white;
        padding: 15px 20px;
        text-decoration: none;
        font-weight: 700;
        transition: background 0.3s;
    }
    nav a:hover { background: #4fd1c5; color: #000; }

    /* CONTEUDO PRINCIPAL */
    main { margin-left: 200px; }

    section {
        width: 100%;
        min-height: 100vh;
        padding: 60px 40px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        opacity: 0;
        transform: translateY(50px);
        transition: all 1s ease;
    }

    section.visible { opacity: 1; transform: translateY(0); }

    h1, h2, h3 { margin-bottom: 20px; }
    p { margin-bottom: 15px; font-size: 1.2em; max-width: 900px; }

    img { max-width: 700px; width: 100%; border-radius: 20px; margin: 20px 0; }

    iframe { width: 100%; max-width:700px; height:400px; border-radius:20px; margin:20px 0; }

    /* CORES DAS PAGINAS */
    #pagina-inicial { background: #f0fff0; color: #2c7a7b; position: relative; }
    #jurema { background: #ffffff; color: #2c7a7b; }
    #malunguinho { background: #8b0000; color: #fff; }
    #pena-branca { background: #ffffff; color: #2c7a7b; background-image: url('https://i.ibb.co/1TtK7nR/penas-brancas.png'); background-repeat: repeat; }
    #familia { background: #d0f0c0; color: #2c7a7b; }
    #rodape { background: #fff3c0; color: #333; padding: 40px 20px; }

    button { padding: 15px 30px; font-size: 1.2em; border:none; border-radius:10px; background:#2c7a7b; color:white; cursor:pointer; margin-top:20px; }
    button:hover { background:#4fd1c5; }

    /* CORAÇÕES ANIMADOS */
    .heart {
        position: absolute;
        width: 20px;
        height: 20px;
        background: red;
        transform: rotate(45deg);
        animation: float 2s linear forwards;
    }
    .heart:before, .heart:after {
        content: "";
        position: absolute;
        width: 20px; height: 20px;
        background: red;
        border-radius: 50%;
    }
    .heart:before { top: -10px; left: 0; }
    .heart:after { left: 10px; top: 0; }
    @keyframes float {
        0% { transform: translateY(0) rotate(45deg); opacity: 1; }
        100% { transform: translateY(-200px) rotate(45deg); opacity: 0; }
    }

    @media(max-width:768px){
        main { margin-left: 0; }
        nav { width: 100%; height: auto; flex-direction: row; padding: 10px; }
        nav a { padding: 10px; font-size: 0.9em; }
        section { padding: 40px 20px; }
        p{font-size:1em;}
    }
</style>
</head>
<body>

<!-- MENU LATERAL -->
<nav>
    <a href="#pagina-inicial">Início</a>
    <a href="#jurema">Jurema</a>
    <a href="#malunguinho">Malunguinho</a>
    <a href="#pena-branca">Caboclo Pena Branca</a>
    <a href="#familia">Família</a>
    <a href="#rodape">Música & Documentários</a>
</nav>

<main>
<!-- PAGINA INICIAL -->
<section id="pagina-inicial">
    <h1>Bem-vindo ao meu tributo</h1>
    <p id="texto-inicial" style="display:none;">Eu, Brayan Matos, discípulo de Caboclo Pena Branca, faço esse site para homenagear a Jurema, meu Juremeiro e meus irmãos de santo. Quero dizer que amo todos vocês.</p>
    <button onclick="mostrarTexto()">Clique aqui</button>
</section>

<!-- PAGINA JUREMA -->
<section id="jurema">
    <h2>🌳 A Árvore da Jurema Sagrada</h2>
    <img src="https://jeffcelophane.wordpress.com/wp-content/uploads/2011/08/161-008.jpg" alt="Árvore Jurema">
    <p>Essa árvore é sagrada em meu culto, diria que amo ela mais que muitos em minha volta.</p>
    <p>A bebida preparada a partir de sua casca, chamada de Jurema ou "vinho da jurema", permite contato com o mundo espiritual e a obtenção de sabedoria, sendo um elemento central da religião conhecida como Jurema Sagrada.</p>
</section>

<!-- PAGINA MALUNGUINHO -->
<section id="malunguinho">
    <h2>Malunguinho – Guardião da Jurema</h2>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAChpw1-VZN_emmD5vpSgT50wovxthmg5xuA&s" alt="Malunguinho">
    <p>Malunguinho, ou Mestre Malunguinho, é uma entidade espiritual e figura histórica de resistência afro-indígena, cultuado na Jurema Sagrada, Catimbó e Umbanda no Nordeste do Brasil. É um guardião, rei encantado e mensageiro de três mundos (Mata, Jurema e Encruzilhada), associado à força, sabedoria das ervas e proteção contra opressão e energias negativas.</p>
</section>

<!-- PAGINA CABOCLO PENA BRANCA -->
<section id="pena-branca">
    <h2>Caboclo Pena Branca – Meu Guia Chefe</h2>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ7QKEVN2teqZePCp4ESYYE0Vo1wef0kDw_Q&s" alt="Caboclo Pena Branca">
    <p>Esse caboclo é o dono da minha vida, meu guia chefe. Ele é o dono dos meus maiores feitos, sem ele não estaria aqui para contar nenhuma história. Ele se apresenta na Jurema Sagrada como um caboclo com energia calma e leve, sua força está ligada às matas e florestas.</p>
</section>

<!-- PAGINA FAMILIA DE JUREMA -->
<section id="familia">
    <h2>Minha Família de Jurema</h2>
    <p>Essa última página é dedicada à minha família de Jurema. Sem vocês eu não estaria aqui. Quero agradecer muito ao meu Juremeiro Kaue de Mestra Geraldina, ele é o melhor Juremeiro do mundo para mim.</p>
    <p><strong>Discipula de Farrapo:</strong> Eu nunca tive contato muito forte com ela, mas de longe sempre observo as melhores coisas, a felicidade, a mudança de vida e a melhor coisa, a felicidade.</p>
    <p><strong>Discipulo de Simbamba:</strong> Pedro, você para mim é um belo amigo, a gente já passou por altos e baixos diversas vezes, espero tudo de bom na sua vida e que nada falte para você e sua mãe.</p>
    <p><strong>Discipula de Pena Vermelha:</strong> Irmã, nenhum texto é capaz de descrever o quanto eu te amo, você me salvou diversas vezes sem perceber, desejo tudo de bom, que Pai Tupã abençoe seus caminhos sempre!</p>
    <p><strong>Discipula de Bagaço:</strong> Eu nunca me imaginaria sendo seu irmão de santo, tantas brigas por causa de times.. Não dá para negar que o Palmeiras é a sua marca registrada, mas a Bagaço e a Dama também, desejo tudo de melhor, e que nunca falte sua amada cerveja.</p>
    <p><strong>Discipula de Leviana:</strong> Para a discipula de Leviana eu desejo tudo de bom e de melhor, que ela nunca perca a essência de chorar toda vez e fazer seus dramas com o pai. Que Leviana sempre abençoe seus caminhos.</p>
    <p><strong>Discipula de Zé Pelintra:</strong> Que você sempre seja essa menina sorridente, espero que seus caminhos sejam lindos na Jurema.</p>
    <p><strong>Discipula de Ritinha:</strong> Você chegou de repente e todos gostaram de você, é bem engraçada quando faz caretas. Espero que a Ritinha te dê coisas boas e caminhos prósperos.</p>
    <p><strong>Discipula de Luziara:</strong> Eu não te conheço muito, mas você é bem gente boa e divertida, espero que a Luziara te dê muitas coisas boas na Jurema.</p>
    <p><strong>Discipulo de Malunguinho:</strong> Cipa, saiba que você é um amigo muito querido, que sempre seja esse menino travesso e bem humorado. Espero que Malunguinho te dê muitas coisas boas.</p>
    <p><strong>Brayan, Discipulo de Pena Branca ama a todos.</strong></p>
</section>

<!-- RODAPE -->
<section id="rodape">
    <h2>Música e Documentários</h2>
    <iframe src="https://www.youtube.com/embed/V6M57I3zwrE" frameborder="0" allowfullscreen></iframe>
    <p><a href="https://youtu.be/AxbohCVQYOo?si=P1jKFDRiKCBTixHH" target="_blank">Documentário 1 – Jurema Sagrada</a></p>
    <p><a href="https://youtu.be/eTPuF2pLIhU?si=RzGtFgz9gQJZQpfC" target="_blank">Documentário 2 – Encantados</a></p>
</section>

</main>

<script>
    // Mostrar texto inicial e corações
    function mostrarTexto(){
        const texto = document.getElementById('texto-inicial');
        texto.style.display = 'block';
        for(let i=0;i<30;i++){
            let heart = document.createElement('div');
            heart.classList.add('heart');
            heart.style.left = Math.random()*window.innerWidth + 'px';
            heart.style.top = Math.random()*window.innerHeight + 'px';
            document.body.appendChild(heart);
            setTimeout(()=>heart.remove(),2000);
        }
    }

    // Fade-in nas seções ao scroll
    const sections = document.querySelectorAll('section');
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            if(entry.isIntersecting){ entry.target.classList.add('visible'); }
        });
    }, { threshold: 0.2 });
    sections.forEach(section => observer.observe(section));
</script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tributo à Jurema e Meu Juremeiro</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family: 'Roboto', sans-serif; scroll-behavior: smooth; overflow-x: hidden; }

    /* MENU LATERAL */
    nav {
        position: fixed;
        left: 0;
        top: 0;
        height: 100%;
        width: 200px;
        background: #2c7a7b;
        display: flex;
        flex-direction: column;
        padding-top: 50px;
        z-index: 999;
    }
    nav a {
        color: white;
        padding: 15px 20px;
        text-decoration: none;
        font-weight: 700;
        transition: background 0.3s;
    }
    nav a:hover { background: #4fd1c5; color: #000; }

    /* CONTEUDO PRINCIPAL */
    main { margin-left: 200px; }

    section {
        width: 100%;
        min-height: 100vh;
        padding: 60px 40px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        opacity: 0;
        transform: translateY(50px);
        transition: all 1s ease;
    }

    section.visible { opacity: 1; transform: translateY(0); }

    h1, h2, h3 { margin-bottom: 20px; }
    p { margin-bottom: 15px; font-size: 1.2em; max-width: 900px; }

    img { max-width: 700px; width: 100%; border-radius: 20px; margin: 20px 0; }

    iframe { width: 100%; max-width:700px; height:400px; border-radius:20px; margin:20px 0; }

    /* CORES DAS PAGINAS */
    #pagina-inicial { background: #f0fff0; color: #2c7a7b; position: relative; }
    #jurema { background: #ffffff; color: #2c7a7b; }
    #malunguinho { background: #8b0000; color: #fff; }
    #pena-branca { background: #ffffff; color: #2c7a7b; background-image: url('https://i.ibb.co/1TtK7nR/penas-brancas.png'); background-repeat: repeat; }
    #familia { background: #d0f0c0; color: #2c7a7b; }
    #rodape { background: #fff3c0; color: #333; padding: 40px 20px; }

    button { padding: 15px 30px; font-size: 1.2em; border:none; border-radius:10px; background:#2c7a7b; color:white; cursor:pointer; margin-top:20px; }
    button:hover { background:#4fd1c5; }

    /* CORAÇÕES ANIMADOS */
    .heart {
        position: absolute;
        width: 20px;
        height: 20px;
        background: red;
        transform: rotate(45deg);
        animation: float 2s linear forwards;
    }
    .heart:before, .heart:after {
        content: "";
        position: absolute;
        width: 20px; height: 20px;
        background: red;
        border-radius: 50%;
    }
    .heart:before { top: -10px; left: 0; }
    .heart:after { left: 10px; top: 0; }
    @keyframes float {
        0% { transform: translateY(0) rotate(45deg); opacity: 1; }
        100% { transform: translateY(-200px) rotate(45deg); opacity: 0; }
    }

    @media(max-width:768px){
        main { margin-left: 0; }
        nav { width: 100%; height: auto; flex-direction: row; padding: 10px; }
        nav a { padding: 10px; font-size: 0.9em; }
        section { padding: 40px 20px; }
        p{font-size:1em;}
    }
</style>
</head>
<body>

<!-- MENU LATERAL -->
<nav>
    <a href="#pagina-inicial">Início</a>
    <a href="#jurema">Jurema</a>
    <a href="#malunguinho">Malunguinho</a>
    <a href="#pena-branca">Caboclo Pena Branca</a>
    <a href="#familia">Família</a>
    <a href="#rodape">Música & Documentários</a>
</nav>

<main>
<!-- PAGINA INICIAL -->
<section id="pagina-inicial">
    <h1>Bem-vindo ao meu tributo</h1>
    <p id="texto-inicial" style="display:none;">Eu, Brayan Matos, discípulo de Caboclo Pena Branca, faço esse site para homenagear a Jurema, meu Juremeiro e meus irmãos de santo. Quero dizer que amo todos vocês.</p>
    <button onclick="mostrarTexto()">Clique aqui</button>
</section>

<!-- PAGINA JUREMA -->
<section id="jurema">
    <h2>🌳 A Árvore da Jurema Sagrada</h2>
    <img src="https://jeffcelophane.wordpress.com/wp-content/uploads/2011/08/161-008.jpg" alt="Árvore Jurema">
    <p>Essa árvore é sagrada em meu culto, diria que amo ela mais que muitos em minha volta.</p>
    <p>A bebida preparada a partir de sua casca, chamada de Jurema ou "vinho da jurema", permite contato com o mundo espiritual e a obtenção de sabedoria, sendo um elemento central da religião conhecida como Jurema Sagrada.</p>
</section>

<!-- PAGINA MALUNGUINHO -->
<section id="malunguinho">
    <h2>Malunguinho – Guardião da Jurema</h2>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAChpw1-VZN_emmD5vpSgT50wovxthmg5xuA&s" alt="Malunguinho">
    <p>Malunguinho, ou Mestre Malunguinho, é uma entidade espiritual e figura histórica de resistência afro-indígena, cultuado na Jurema Sagrada, Catimbó e Umbanda no Nordeste do Brasil. É um guardião, rei encantado e mensageiro de três mundos (Mata, Jurema e Encruzilhada), associado à força, sabedoria das ervas e proteção contra opressão e energias negativas.</p>
</section>

<!-- PAGINA CABOCLO PENA BRANCA -->
<section id="pena-branca">
    <h2>Caboclo Pena Branca – Meu Guia Chefe</h2>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ7QKEVN2teqZePCp4ESYYE0Vo1wef0kDw_Q&s" alt="Caboclo Pena Branca">
    <p>Esse caboclo é o dono da minha vida, meu guia chefe. Ele é o dono dos meus maiores feitos, sem ele não estaria aqui para contar nenhuma história. Ele se apresenta na Jurema Sagrada como um caboclo com energia calma e leve, sua força está ligada às matas e florestas.</p>
</section>

<!-- PAGINA FAMILIA DE JUREMA -->
<section id="familia">
    <h2>Minha Família de Jurema</h2>
    <p>Essa última página é dedicada à minha família de Jurema. Sem vocês eu não estaria aqui. Quero agradecer muito ao meu Juremeiro Kaue de Mestra Geraldina, ele é o melhor Juremeiro do mundo para mim.</p>
    <p><strong>Discipula de Farrapo:</strong> Eu nunca tive contato muito forte com ela, mas de longe sempre observo as melhores coisas, a felicidade, a mudança de vida e a melhor coisa, a felicidade.</p>
    <p><strong>Discipulo de Simbamba:</strong> Pedro, você para mim é um belo amigo, a gente já passou por altos e baixos diversas vezes, espero tudo de bom na sua vida e que nada falte para você e sua mãe.</p>
    <p><strong>Discipula de Pena Vermelha:</strong> Irmã, nenhum texto é capaz de descrever o quanto eu te amo, você me salvou diversas vezes sem perceber, desejo tudo de bom, que Pai Tupã abençoe seus caminhos sempre!</p>
    <p><strong>Discipula de Bagaço:</strong> Eu nunca me imaginaria sendo seu irmão de santo, tantas brigas por causa de times.. Não dá para negar que o Palmeiras é a sua marca registrada, mas a Bagaço e a Dama também, desejo tudo de melhor, e que nunca falte sua amada cerveja.</p>
    <p><strong>Discipula de Leviana:</strong> Para a discipula de Leviana eu desejo tudo de bom e de melhor, que ela nunca perca a essência de chorar toda vez e fazer seus dramas com o pai. Que Leviana sempre abençoe seus caminhos.</p>
    <p><strong>Discipula de Zé Pelintra:</strong> Que você sempre seja essa menina sorridente, espero que seus caminhos sejam lindos na Jurema.</p>
    <p><strong>Discipula de Ritinha:</strong> Você chegou de repente e todos gostaram de você, é bem engraçada quando faz caretas. Espero que a Ritinha te dê coisas boas e caminhos prósperos.</p>
    <p><strong>Discipula de Luziara:</strong> Eu não te conheço muito, mas você é bem gente boa e divertida, espero que a Luziara te dê muitas coisas boas na Jurema.</p>
    <p><strong>Discipulo de Malunguinho:</strong> Cipa, saiba que você é um amigo muito querido, que sempre seja esse menino travesso e bem humorado. Espero que Malunguinho te dê muitas coisas boas.</p>
    <p><strong>Brayan, Discipulo de Pena Branca ama a todos.</strong></p>
</section>

<!-- RODAPE -->
<section id="rodape">
    <h2>Música e Documentários</h2>
    <iframe src="https://www.youtube.com/embed/V6M57I3zwrE" frameborder="0" allowfullscreen></iframe>
    <p><a href="https://youtu.be/AxbohCVQYOo?si=P1jKFDRiKCBTixHH" target="_blank">Documentário 1 – Jurema Sagrada</a></p>
    <p><a href="https://youtu.be/eTPuF2pLIhU?si=RzGtFgz9gQJZQpfC" target="_blank">Documentário 2 – Encantados</a></p>
</section>

</main>

<script>
    // Mostrar texto inicial e corações
    function mostrarTexto(){
        const texto = document.getElementById('texto-inicial');
        texto.style.display = 'block';
        for(let i=0;i<30;i++){
            let heart = document.createElement('div');
            heart.classList.add('heart');
            heart.style.left = Math.random()*window.innerWidth + 'px';
            heart.style.top = Math.random()*window.innerHeight + 'px';
            document.body.appendChild(heart);
            setTimeout(()=>heart.remove(),2000);
        }
    }

    // Fade-in nas seções ao scroll
    const sections = document.querySelectorAll('section');
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            if(entry.isIntersecting){ entry.target.classList.add('visible'); }
        });
    }, { threshold: 0.2 });
    sections.forEach(section => observer.observe(section));
</script>

</body>
</html>
