Caso eu tenha uma class com o nome da tag  pai + alguma coisa, em vez de repetir o nome ".header-container"(exemplo) e emito o .header com um "&"

header
    text-align: center

    &-container
        @include mixins.flex-container