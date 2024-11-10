<p align = "center">
<img src="https://ufal.br/ufal/resolveuid/458d5fb68aa7459bb9ec4ac2ce59c6b4/@@images/image/mini" alt="Logo da UFAL" width="150">
</p>

<h1 align = "center">
<b>Projeto de Criptografia RSA</b>
</h1>

Este repositório contém o programa de criptografia baseado no algoritmo de RSA desenvolvido pelos autores para a disciplina de matemática discreta, ministrada pelo professor Bruno Pimentel no Instituto de Computação da UFAL (IC/UFAL).

## Instruções de Uso
### Baixando o arquivo .zip direto do GitHub
1. Na barra do lado direito navegue até ```releases``` e selecione a mais recente ```latest```.
2. Desça a página e clique em ```Source code (zip)```.
3. Após o download, extraia todos os arquivos em uma mesma pasta.
4. Execute o arquivo executável ```cripto_rsa.exe```.

**ou**

1. Clique em ```code``` no canto superior.
  - Em seguida clique em ```download ZIP```.
2. Após o download, extraia todos os arquivos em uma mesma pasta.
3. Execute o arquivo executável ```cripto_rsa.exe```.

### Clonando o repositório

1. Clone o repositório usando o git.
   ```
   git clone https://github.com/erasmo-junior-dev/Projeto-Criptografia-RSA-Matematica-Discreta.git
   ```
2. Navegue até a pasta do projeto.
   ```
   cd caminho/da/pasta
   ```
3. Execute o arquivo executável ```cripto_rsa.exe```.

Em caso de dúvidas, você pode seguir este manual de instruções: [Manual de Instruções](https://docs.google.com/document/d/1v1mLUwItjrb9E2OQbRLOgDU-GP0jsxHTi8m_-9Un1uA/)

## Autores:
| Nome                                   | Número de Matrícula | E-mail                  | Curso               |
|----------------------------------------|---------------------|-------------------------|---------------------|
| Erasmo da Silva Sá Junior              | 202407358           | essj@ic.ufal.br        | Ciência da Computação |
| Artur Ferreira Marques da Silva        | 202437820           | afms@ic.ufal.br        | Ciência da Computação |
| Caio Henrique Gavazza Patriota         | 202407231           | chgp@ic.ufal.br        | Ciência da Computação |
| José Riquelme Teixeira da Silva        | 202407400           | jrts@ic.ufal.br        | Ciência da Computação |
| Daniel de Araujo Albuquerque           | 202407311           | daa@ic.ufal.br         | Ciência da Computação |
| Victor André Lopes Brasileiro          | 202407269           | valb1@ic.ufal.br       | Ciência da Computação |
| Pablo Levy Fernandes Alcântara         | 202407429           | plfa1@ic.ufal.br       | Ciência da Computação |

## Contribuições Especiais

Gostaríamos de agradecer especialmente aos colaboradores que contribuíram para o desenvolvimento do design visual do ícone do nosso projeto!

- 🎨 **Ingrid Laryssa Freitas Silva (FAUD/UFAL)** – Contribuiu com o design do ícone da aplicação, trazendo uma identidade visual moderna e intuitiva.
- 🎨 **José Avelino Freire Júnior (FDA/UFAL)** – Contribuiu com o design do ícone da aplicação, trazendo uma identidade visual moderna e intuitiva.

Essas contribuições foram fundamentais para tornar nosso projeto mais familiar ao usuário final!

## Licença

Este projeto é licenciado pelos autores sob a **Licença MIT**.

### Bibliotecas e Dependências

- **Qt Community Edition (Open Source)**: Licenciado sob a [LGPL](https://www.qt.io/licensing/). Consulte o link para mais detalhes.
- **GMP (GNU MP Library)**: Licenciado sob a [LGPL](https://gmplib.org/). Este projeto utiliza uma versão **estática** da biblioteca GMP.

### Informações sobre a GMP

Este projeto usa a **GMP (GNU MP Library)**, uma biblioteca matemática de precisão arbitrária, sob a licença **LGPL v3**. A biblioteca GMP foi vinculada estaticamente ao projeto para fornecer funcionalidades de criptografia baseadas no algoritmo RSA. Como a GMP está vinculada estaticamente, os usuários têm o direito de substituir a biblioteca GMP, conforme os termos da LGPL.

#### Substituindo a Biblioteca GMP

Se você deseja substituir a versão da GMP usada neste projeto, você pode:

1. Obter o código-fonte da GMP na versão mais recente em [https://gmplib.org/](https://gmplib.org/).
2. Substituir a versão da biblioteca na pasta `gmp/` ou, se necessário, modificar o caminho de linkagem.
3. Recompilar o projeto para vincular a nova versão da GMP.

#### Código-Fonte da GMP

Se você deseja acessar o código-fonte da GMP ou modificar a biblioteca, você pode obter a versão mais recente em [https://gmplib.org/](https://gmplib.org/).

### Requisitos de Licença

A LGPL exige que você forneça aos usuários as opções para substituir a biblioteca GMP, mesmo quando ela está vinculada estaticamente. Para garantir a conformidade com a licença, você deve:

- Incluir o código-fonte da GMP se você tiver modificado a biblioteca. Caso contrário, forneça informações claras de como os usuários podem acessar o código-fonte original da GMP.
- Incluir os arquivos de objetos ou permitir a substituição do código-fonte da GMP para permitir que o usuário relink o programa com outra versão da biblioteca.
- Incluir uma nota informando sobre o uso da GMP e a licença LGPL, como descrito acima.

#### Arquivo de Licença

Este projeto inclui um arquivo de licença que deve ser distribuído com o código-fonte, conforme exigido pela Licença MIT e a LGPL para a biblioteca GMP. O arquivo de licença pode ser encontrado no repositório e deve ser incluído junto com qualquer redistribuição do código-fonte.

Se você tiver alguma dúvida sobre os termos da licença ou precisar de mais informações sobre a substituição das dependências, consulte os links mencionados na seção "Bibliotecas e Dependências".
