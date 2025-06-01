# Api para o Jogo da Forca

## Como funciona?
### Esse json é separado em "temas", essas sendo:
- Transporte
- Comida
- Profissão
- País
- Esporte
- Instrumento musical
- Animal

### Cada palavra presente nos temas possuem 2 atributos:
- palavra (A palavra a ser mostrada no jogo)
- palavra_filtro (A palavra sem acentuação gráfica)

### Para que serve a palavra_filtro?
Não seria prático adicionar as teclas com acentuações gráficas no teclado do jogo, portanto o teclado lê o atributo  ```palavra_filtro``` para validar a palavra e usa ```palavra``` para retornar o resultado para o usuário 
- Exemplo: ônibus (palavra) / onibus (palavra_filtro)

## Ajudar com o repositório
Todos tem a permissão de utilizar a api e enviar Pull Request para atualizações na api sobre os seguintes critérios:
- Ser coerente com o tema
- Não repetir palavras já presentes
- Utilizar adequadamente os atributos (palavra/palavra_filtro)

Bom jogo! :)
