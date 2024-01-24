Para separar as pastas do Sass e do Css coloca no terminal: sass --watch sass/styles.sass:css/styles.css

Para funcionar, tem que estar no diretório.

Para compilar novamente, se usa o mesmo comando, caso use a extensão "Watch Sass" vai criar os arquivos no mesmo diretório Sass.

Para criar outros arquivos, pode criar uma pasta chamada "partials" e dentro dela o nome dos arquivos vão ter _ + nome do arquivo.

Para importar arquivos use o "@use" e não "@import". O "@import" será decapreciado no futuro, o recomendado é o "@use"