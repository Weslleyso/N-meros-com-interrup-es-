soma = cont = 0
while True:
    n = (int(input('Insira um valor(999 para parar): ')))
    
    if n == 999:
        break
    cont = cont +1
    soma += n
    
print(f'a soma dos números deu {soma} e foram digitados {cont} números.')
  
    
