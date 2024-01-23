Mixins é um tipo de arquivo onde você poderá fazer funções.

Ex.: @mixin flex-container
    display: flex
    height: 100vh
    flex-direction: row
    justify-content: center
    align-self: center


E para usar, se usa:  @include mixins.flex-container (depois de importar o arquivo)