# Ransoware em Python

Este repositório contém dois scripts Python que demonstram o processo básico de criptografia e descriptografia de arquivos usando o algoritmo AES (Advanced Encryption Standard) no modo CTR (Counter).

## Estrutura

O projeto consiste em dois scripts principais:

### 1. Encrypter (encrypter.py)

Script responsável pela criptografia de arquivos. Suas principais funcionalidades são:

- Lê o conteúdo de um arquivo chamado "teste.txt"
- Remove o arquivo original por segurança
- Utiliza uma chave predefinida para criptografia ("testeransomwares")
- Cria um novo arquivo com extensão ".ransomwaretroll" contendo o conteúdo criptografado

### 2. Decrypter (decrypter.py)

Script responsável pela descriptografia. Suas principais funcionalidades são:

- Lê o arquivo criptografado com extensão ".ransomwaretroll"
- Utiliza a mesma chave para descriptografar o conteúdo
- Remove o arquivo criptografado
- Restaura o arquivo original com o conteúdo descriptografado

## Dependências

- Python 3.x
- Biblioteca `pyaes`

## Observações Importantes

- Este é um projeto demonstrativo para fins educacionais
- A chave de criptografia está hardcoded nos scripts
- Os scripts trabalham especificamente com um arquivo chamado "teste.txt"
- Certifique-se de ter backup dos arquivos antes de testar, pois os scripts removem arquivos durante o processo
