# Exercício Produto

[Tela para reproduzir](https://marvelapp.com/194b601g/screen/56839103)

Soluções interessantes na resolução:

- o tamanho da foto estava sobrando em cima e embaixo, usei o `scaleType="CenterCrop"` para cortar
- a pasta drawable é para imagens, a mipmap é para ícones
- os campos podem ser formatados para um ou mais tipos. Um exemplo é `inputType="numberDecimal|number" no campo preço
- para converter de EditText para os tipos Integer e Double precisa de parse
- para validar os campos vazios, por algum motivo não funcionou `TextUtils.isEmpty()`, então usei `nome.equals("")` mesmo
- não confirmei essa informação, mas todo tipo de dado que vem por input parece que precisa ser formatado para String antes de ser convertido para outro formato. Acho que existe uma questão de cast também para trazer em outros formatos.
- o Toast pode ser criado automaticamente com tab
- o texto formatado, como no último toast, precisa ter um Locale para definir se vai ser vírgula ou ponto, e evitar exceptions
