<p align="center">
<img src="./assets/ciberseguranca-logo.png" alt="Criptografia" width="150" /> <br /> <b>Criando um Ransomware com Python</b> <br /> <sub><sup><b>(RANSOMWARE-PYTHON)</b></sup></sub> <br /> </p> <p align="center"> Este projeto demonstra a criação de um ransomware simples utilizando Python, com funcionalidades de criptografia e descriptografia de arquivos. O objetivo é educacional, mostrando como esses ataques podem ser realizados e como proteger-se contra eles. <br /> </p>

## Estrutura do Projeto

### Arquivos Principais

- [`encrypter.py`](encrypter.py): Script para criptografar um arquivo.
- [`decrypter.py`](decrypter.py): Script para descriptografar um arquivo.
- [`teste.txt`](teste.txt): Arquivo de texto exemplo que será criptografado e descriptografado.
- [`README.md`](README.md): Documentação do projeto.

### Estrutura de Pastas
```
criando-um-ransomware-com-python
├── prints
│   ├── criptografia.png
│   └── descriptografia.png
├── decrypter.py
├── encrypter.py
├── README.md
└── teste.txt
```

### Funcionalidades

- **Criptografia de Arquivos**: O script [`encrypter.py`](encrypter.py) lê um arquivo de texto, criptografa seu conteúdo e salva o resultado em um novo arquivo com a extensão `.ransomwaretroll`.
- **Descriptografia de Arquivos**: O script [`decrypter.py`](decrypter.py) lê o arquivo criptografado, descriptografa seu conteúdo e salva o resultado em um novo arquivo de texto.
- **Remoção de Arquivos Originais**: Ambos os scripts removem os arquivos originais após a criptografia ou descriptografia.

### Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver os scripts.
- **PyAES**: Biblioteca utilizada para realizar a criptografia e descriptografia dos arquivos.

### O que é um Ransomware?

Um ransomware é um tipo de malware que criptografa os arquivos da vítima, tornando-os inacessíveis, e exige um resgate (ransom) para restaurar o acesso. Esses ataques são uma ameaça significativa à segurança cibernética, afetando tanto indivíduos quanto organizações.

### Resultados do arquivo teste.txt

Após rodar o [`encrypter.py`](encrypter.py):
<img src="./prints/criptografia.png">


após rodar o [`decrypter.py`](decrypter.py):
<img src="./prints/descriptografia.png">
### Licença

Este software é licenciado sob os termos da MIT License.

⌨️ Desenvolvido por [Vitor Bittencourt](https://github.com/VitorVBD)