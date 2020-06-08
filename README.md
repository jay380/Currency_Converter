# LT_Project
Currency convertor 
Compilation steps :
       yacc -d currency.y
       lex currency.l
       cc lex.yy.c y.tab.c -o currency_convertor.exe
       ./currency_convertor.exe
