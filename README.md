# R
R Tips and snippets

# Funções criadas
"%^%" <- function(x, n) 
  with(eigen(x), vectors %*% (values^n * t(vectors))) #elevação matricial
