# 🔐 Gerador De Senhas

# Descrição

Este projeto é um gerador de senhas simples, desenvolvido em C#, que permite ao usuário escolher diferentes tipos de senhas e especificar o tamanho desejado. O programa também salva a senha gerada em um arquivo de texto.

# Funcionalidades

**Geração de senhas com diferentes critérios:**

- [x] Somente números
- [x] Somente letras
- [x] Letras e números misturados
- [x] Letras, números e caracteres especiais
- [x] Opção para salvar a senha gerada em um arquivo de texto (senha.txt).
- [x] Interface de console colorida para uma melhor experiência do usuário.

# Requisitos

 - [x] **.NET Framework ou .NET Core/5/6 (dependendo de sua versão do C#).**
[Download .NET SDK](https://dotnet.microsoft.com/download)
- [x] **Visual Studio Code.**
[Download Visual Studio Code](https://code.visualstudio.com/download)

# Como Usar:
1. Clone o repositório ou baixe o arquivo Program.cs para o seu computador.
2. Abra o terminal ou o prompt de comando e navegue até o diretório onde o arquivo Program.cs está salvo.
3. Execute o programa:
* **dotnet run**

4. Escolha uma opção para gerar a senha:

* **Digite 1** para somente números.
* **Digite 2** para somente letras.
* **Digite 3** para letras e números misturados.
* **Digite 4** para letras, números e caracteres especiais.

Digite o tamanho da senha que você deseja gerar. O tamanho deve ser um número inteiro positivo.

A senha gerada será exibida no console e também será salva no arquivo **senha.txt** no mesmo diretório do programa.

* **Sair:**  Para sair, pressione qualquer tecla quando solicitado.

# Aplicativos Utilizados

 - [x] **.NET Framework ou .NET Core/5/6 (dependendo de sua versão do C#).**
[Download .NET SDK](https://dotnet.microsoft.com/download)
- [x] **Visual Studio Code.**
[Download Visual Studio Code](https://code.visualstudio.com/download)

# Estrutura do Código

* O código utiliza a biblioteca System.IO para manipulação de arquivos.
* O método GerarSenha é responsável por criar a senha baseada na escolha do usuário e no tamanho especificado.
* As senhas geradas são armazenadas em um arquivo senha.txt com a data e hora da criação.

# Observações

* Certifique-se de ter permissões de escrita no diretório onde o programa está sendo executado, pois o arquivo senha.txt será criado ou atualizado nesse local.
O programa verifica se a entrada do usuário é válida e exibe mensagens apropriadas para entradas inválidas.

# Conclusão

* Este gerador de senhas é uma ferramenta útil para quem precisa de senhas seguras e variadas. Sinta-se à vontade para modificar e expandir o código conforme suas necessidades!

<img width="150" alt="image" src="https://github.com/user-attachments/assets/e79b6d69-8fc8-49db-bb7d-300c26cac54f" />
