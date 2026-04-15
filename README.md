# atividade-4
algoritmo "CategoriasLoL"

var
   idade : inteiro

   inicio
      Escreva("Digite a idade do jogador: ")
         Leia(idade)

            Se (idade >= 12) E (idade <= 14) Entao
                  EscrevaL("Categoria: Mirim")
                     Senao
                           Se (idade >= 15) E (idade <= 17) Entao
                                    EscrevaL("Categoria: Junior")
                                          Senao
                                                   Se (idade >= 18) E (idade <= 25) Entao
                                                               EscrevaL("Categoria: Profissional")
                                                                        Senao
                                                                                    Se (idade > 25) Entao
                                                                                                   EscrevaL("Categoria: Master")
                                                                                                               Senao
                                                                                                                              EscrevaL("Idade fora das categorias competitivas.")
                                                                                                                                          FimSe
                                                                                                                                                   FimSe
                                                                                                                                                         FimSe
                                                                                                                                                            FimSe
                                                                                                                                                            fimalgoritmo

