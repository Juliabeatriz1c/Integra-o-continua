# Válido
caminhos:
  -'**/README.md'

  # Inválido - cria um erro de análise que
  # Impede a execução do seu fluxo de trabalho.
  caminhos:
    -'**/README.md
    

  # Válido
  branches: [ main, 'realse/v[0-9].[0-9]' ]

# Inválido - gera um erro de análise
branches [ main, realse/v[0-9].[0-9]
  
