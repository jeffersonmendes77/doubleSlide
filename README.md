Quando o botão “Inscreva-se” é clicado, 
o código adiciona a classe “right-panel-active” ao 
elemento do container, o que aciona uma transição CSS
e animação para exibir o formulário de inscrição.

Da mesma forma, quando o botão “Entrar” é clicado, 
o código remove a classe “right-panel-active” do elemento 
container, fazendo com que o formulário de login seja exibido.

Este código usa o addEventListenermétodo para escutar o 
evento “click” nos botões e modifica a lista de classes 
do elemento container usando a classListpropriedade. 
O classList.addmétodo adiciona a classe especificada 
ao elemento, enquanto o classList.removemétodo remove
a classe especificada.

Observe que o código pressupõe a existência de elementos 
HTML com os IDs “signUp”, “signIn” e “container” no 
documento HTML.
