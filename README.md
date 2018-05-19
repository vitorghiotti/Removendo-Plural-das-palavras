# Removendo-Plural-das-palavras
Função em Python para realizara a extração do plural das palavras

Esta função nasceu da necessidade de se reduzir as palavras que estavam plural para o seu singular de forma que não impactasse um classificador de sentimento Naive Bayes que seria aplicado na analise dos comentarios das principais redes sociais.

Em resumo ele aplica expressões regulares nas palavras substituindo os sufixos que determinam o plurar para sufixos que determinam o singular. Ele também trata as excessões onde palavras que estão no plural não devem ser reduzidas para o singular. Ex: vamos, ambos, após, antes e etc. Estas excessões estão numa lista dentro da função.

Fiquem a vontade para sugerir melhorias!!!
