- primeira coisa que tem que fazer no JAVASCRIP  e fazer que o submit nao envie o formulario e recarregue a pagina para bloquear o carregamento da pagina ( para fazer isso precisa desse funçao abaixo) 
      - form.onsubmit = function(event) {
           event.preventDefault()
           }

      - preventDefault (siginifica evite o padrao)
    
- segunda coisa pegar o valor dos dois campos e fazer o calculo do imc

# querySelector (significa pesquisa pelo seletor) é para selecionar a tag que preciso

# handle em ingles quer dizer manipular

# 3 maneiras de criar e atribuir funçao a um evento

form.onsubmit = function() {}

form.onsubimit = () => {}

form.onsubmit = handleSubmit

function handleSubmit() {
  
}

form.onsubmit = function(event) {
  event.preventDefault()

  const weight = inputWeight.value 
  const height = inputHeight.value
}

- fazer aparecer o modal
- fazer o botao para fechar e mudar o valor do imc

# modalMessage.innerText = "Qualquer coisa" // esse é para trocar a mensagem

# modalWrapper.classList.add("open") // esse e para adicionar o open

# const modalMessage = document.querySelector('.modal .title span') // modalMessage e para o texto que tem que ser trocado

# const modalBtnClose = document.querySelector('.modal button.close') // essa variavel e para o botao de fechamento

