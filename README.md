# Sistema de Gestão Comercial via Internet

Este é um sistema de gestão comercial desenvolvido em PHP para ser executado via navegador. O sistema permite a gestão de pedidos, recebimentos, envio de e-mails automáticos e controle de fornecedores.

## 📁 Estrutura do Projeto

Sistema de Gestão Comercial via Internet/
├── concluirpedido.php # Finaliza um pedido
├── recebido.php # Processa o recebimento
├── recebidofornecedor.php # Processa recebimento de fornecedor
├── fpag.php # Formulário de pagamento
├── util.inc # Arquivo de funções auxiliares
├── tituloemail.txt # Título padrão de e-mails
├── recebidoctxt.txt # Modelo de texto para e-mail de recebimento
├── recebidoftxt.txt # Modelo de texto para e-mail de recebimento (formato diferente)
├── recebidofornecedorctxt.txt # Modelo de e-mail para fornecedor
├── recebidofornecedorftxt.txt # Modelo alternativo de e-mail para fornecedor

## ⚙️ Requisitos

- Servidor Web (Apache ou similar)
- PHP 5.6 ou superior
- Banco de Dados (caso aplicável; não foi identificado nas primeiras inspeções)
- Navegador moderno para acesso à interface

## 🚀 Como Utilizar

1. **Instale um servidor local**, como [XAMPP](https://www.apachefriends.org/index.html) ou [WampServer](http://www.wampserver.com/).
2. **Coloque a pasta do projeto** dentro do diretório `htdocs` (no caso do XAMPP).
3. **Acesse no navegador**:

http://localhost/Sistema%20de%20Gestao%20Comercial%20via%20Internet/

4. **Utilize os scripts PHP** conforme o fluxo desejado: finalizar pedidos, processar recebimentos, etc.

## ✉️ Envio de E-mails

O sistema possui modelos de e-mails prontos (`.txt`) e títulos padrão para automação. Os scripts PHP fazem uso destes arquivos para compor o corpo dos e-mails enviados.

## 🛠 Personalização

- Edite os arquivos `.txt` para alterar os modelos de e-mail.
- Edite `util.inc` para ajustar ou adicionar funções auxiliares ao sistema.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para modificar e reutilizar conforme necessário.
