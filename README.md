# SiteDisco-de-Vinil
Site Criado para apresentação de trabalho em HTML
Esse site tem como objetico criar, atulizar, editar e excluir discos de vinil em um catalogo online

https://drive.google.com/drive/folders/1XykiXYe912a3w0mAZug6jhupCXvQb5jl?usp=drive_link

# Algumas Explicações de funções utlizadas
Element.addEventListener() = Para registrar mais de uma espera de evento como alvo, chame addEventListener()para o mesmo alvo mas com diferentes tipos de evento ou captura de parâmetros.

Documento.createElement() = Este código cria uma nova <div>e é inserido antes do elemento com ID "

Elemento.classList = Usar classList é uma alternativa conveniente para acessar uma lista de classes de um elemento como uma sequência delimitada pelo espaço

 Node.appendChild = Adicionado um nó ao final da lista de filhos de um nó especificado. Se o nó já não existir nenhum documento, ele será removido do seu nó pai atual antes de ser adicionado ao novo pai.

Documento.querySelector() = Retorna o primeiro elemento dentro do documento (usando ordenação em profundidade, pré-ordenada e transversal a nós do documento) que corresponde ao grupo especificado de seletores.
# ----------------------------------------- Imagem de Capa --------------------------------------------------
item.innerHTML = `
    <img src="${capa}" /> <br>
    <strong>${nome}</strong> - ${artista} <br>
    ${ano} <br>
    ${genero} <br>
    ${qtfaixas} <br>
    <button onclick="removeItem('${itemId}')">Remover</button>
    <button onclick="editItem('${itemId}')">Editar</button>
  `;
Na linha <img src="${capa}" />, a variável ${capa} contém a URL da imagem. Quando essa linha é renderizada, ela cria um elemento de imagem <img> com o atributo src definido como a URL fornecida em ${capa}, o que faz com que a imagem seja carregada e exibida na página.

Essa imagem é estilizada na classe CSS "item"



