/* Reset de estilos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Definição de fontes */
body {
    font-family: Arial, sans-serif; /* Primeira opção de fonte */
}

h1, h2, h3 {
    font-family: 'Times New Roman', Times, serif; /* Segunda opção de fonte */
}

p {
    font-family: Georgia, serif; /* Terceira opção de fonte */
}

/* Tamanho de fontes e elementos */
body {
    font-size: 16px;
}

h1 {
    font-size: 24px;
}

h2 {
    font-size: 20px;
}

h3 {
    font-size: 18px;
}

img {
    max-width: 100%;
    height: auto;
}

/* Alinhamentos */
.text-center {
    text-align: center;
}

.text-right {
    text-align: right;
}

/* Espaçamentos */
p, h1, h2, h3 {
    margin-bottom: 10px;
}

/* Posicionamento */
.container {
    width: 80%;
    margin: 0 auto;
}

/* Exemplo de classe para posicionamento absoluto */
.absolute-center {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
