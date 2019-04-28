# Trabalho-Terminal
## Linux terminal

### Problema 1
``` bash
echo "Leandro Machado da Silva"
```

### Problema 2
``` bash
echo "Leandro Machado da Silva" > cliente01.txt
```

### Problema 3
``` bash
echo "Joinville" >> cliente01.txt
```

### Problema 4
``` bash
mkdir clientes
ls
```

### Problema 5
``` bash
mv cliente01.txt clientes
ls
cd clientes
```

### Problema 6
``` bash
cp cliente01.txt cliente01.txt.bkp
ls
cat cliente01.txt
cat cliente01.txt.bkp
```
### Problema 7
```bash
rm cliente01.txt
ls
```
### Problema 8
```bash
vi cliente.script
echo "Leandro Machado da Silva"
echo "Leandro Machado da Silva" > cliente01.txt
echo "Joinville" >> cliente01.txt
mkdir clientes
ls
mv cliente01.txt clientes
ls
cd clientes
cp cliente01.txt cliente01.txt.bkp
ls
cat cliente01.txt
cat cliente01.txt.bkp
rm cliente01.txt
ls
```
### Problema 9
```bash
chmod +x cliente.script
sh cliente.script
```
### Problema 10
```bash
cal
echo|cal>hoje.txt
```
> O operador | cria um conteúdo de calendário dentro do arquivo hoje.txt

### Problema 11
```bash
wget https://gist.githubusercontent.com/leandersonandre/c8cba982f42262591be628e5397d1c3f/raw/bd13a3e13823708e477f99f9285f845b292714c6/cidades_sc.txt
ls
```

### Problema 12
```bash
grep Balneario cidades_sc.txt
```
> Este comando lista todas as cidades da lista cidades_sc.txt que tenham "Balneário" em seu nome.

### Problema 13
```bash
grep balneario cidades_sc.txt
```
> O comando não lista as cidades, pelo fato de que não há cidades que tenham "balneario" com letra minúscula.

### Problema 14
```bash
grep "do Sul" cidades_sc.txt
```
> Este comando lista as cidades que tem "do Sul" no final de seus nomes.

### Problemas 15
```bash
cat cidades_sc.txt|grep Balneario
```
### Problema 16
```bash
echo|cat cidades_sc.txt|grep Balneario > balneario.txt
```
### Problema 17
```bash
tar -c balneario.txt > compactado.tar
```

### Problema 18
```bash
tar -x compactado.tar
```
## Shell Script

### Problema 1
```bash
#!/usr/bash
echo "Digite o seu nome:"
read nome_usuario;
echo "Seu nome e :$nome_usuario"
```
### Problema 2
```bash
#!/usr/bash
echo "Digite o primeiro numero"
read num1;
echo "Digite o segundo numero"
read num2;
resultado=$((num1*num2));
echo "Resultado e: $resultado"
```
### Problema 3
```bash
#!/usr/bash
echo "Digite um  numero"
read num1;
if [ "$num1" -gt 0 ]; then
        echo "Positivo"
elif [ "$num1" -lt 0 ]; then
        echo "negativo"
else
        echo "zero"
```

### Problema 4
```bash
