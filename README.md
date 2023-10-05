# Mesclador de PDFs
É comum que empresas tenham muitos arquivos em PDF oriundos de sua operação e manipularem eles, são fundamentais nos negócios. Dentre os manejos destes arquivos está a mesclagem, ou seja, uma fusão de arquivos para formar um novo.

Para tal atividade é comum o uso de sites que ofertem esse serviço, para o uso diário da empresa acaba sendo extremamente disfuncional, normalmente são limitados a número de arquivos, são lentos no processamento e possuem inúmeros anúncios em todo o canto.

Por isso desenvolvi uma automação para mesclar PDF utilizando Python, é um projeto simples mas útil, a intenção é conseguir utilizá-lo no dia a dia.

Com a utilização do projeto de mesclar PDFs as limitações e lentidões apresentadas pelos sites não serão mais necessárias. 

# Passo a passo para a criar do “Mesclador” de PDFs

*Premissas: Os arquivos devem estrar na ordem exata da mesclagem para o resultado ser o esperado. Dica: numerar os arquivos 01,02,03 etc.* 

## Antes dos arquivos

![](https://github.com/AmandaAntonio/Mesclar_Pdf/blob/main/01.%20Primeiro%20Arquivo.png)

## Projeto

Em uma IDE para Python instalar a Biblioteca PyPDF2

imagem

Depois carrega as Bibliotecas necessárias 

imagem

Agora é só criar o “mesclador” 

imagem

Criar um listador para percorrer a pasta com arquivos em PDF e atribuir a uma variável 

imagem

Utilizar um laço de repetição com objetivo de mesclar os arquivos

Imagem

Salva o novo arquivo criado

imagem

## Depois dos arquivos

