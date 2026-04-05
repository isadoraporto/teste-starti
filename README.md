# Documento de Requisitos
## Sistema para gestão simples de lojas pequenas

**Autora:** Isadora Porto de Lira Gomes

---

## Mini escopo estrutural do sistema Gestor Fácil

O sistema deve permitir a gestão de lojas de pequeno e médio porte, englobando comércio local e de bairro, facilitando o cadastro de produtos de forma completa.

Entre as funcionalidades principais incluem:

- Código do produto
- Nome do produto
- Data de entrada
- Quantidades disponíveis (considerando controle de estoque quinzenal)
- Variações de cores
- Preço

O segundo objetivo é permitir a **listagem de produtos** em formato de **lista ou tabela**, contendo todos os aspectos citados acima.  
Além disso, o sistema deve possuir:

- Mecanismo de busca
- Filtro
- Ordenação

Essas funcionalidades facilitam a consulta e o gerenciamento de dados.

A solução foi pensada para atender o **controle básico de produtos em pequenas lojas**, oferecendo uma **interface intuitiva e de fácil visualização**, considerando que possam existir usuários de todos os níveis técnicos.

A aplicação será composta por **três telas principais**:

1. **Tela de listagem de produtos**
   - Permite visualizar rapidamente os itens cadastrados.

2. **Tela de cadastro**
   - Destinada à inserção de novos produtos.

3. **Tela de detalhes**
   - Apresenta informações completas de um produto selecionado.

O foco principal do sistema é o **cadastramento de produtos**.  
No entanto, para garantir a organização dos dados, **cada produto deve estar vinculado a uma loja previamente cadastrada**.

Dessa forma, o cadastro de lojas funciona como uma **etapa complementar do sistema**, permitindo identificar a origem dos produtos e manter a consistência das informações.

---

# Campos e Botões do Sistema

## Campos de texto

- Código do produto
- Nome do produto
- Data de chegada na loja
- Cores disponíveis
- Quantidade em estoque
- Preço

## Botões principais

- Cadastrar
- Cancelar
- Salvar
- Editar produto
- Excluir produto
- Filtrar
- Ordenar
- Modificar cor do produto

---

# Organização de elementos na tela (Experiência do Usuário)

## 1. Tela de Listagem de Produtos

- Botões de **busca e filtros** no topo da tela, grandes e claros do lado esquerdo
- Exibição dos produtos em formato de **lista ou tabela**
- Possibilidade de **imagens dos produtos (opcional)**
- Ações simples ao lado de cada item:
  - Editar
  - Excluir
  - Modificar cor
- Rodapé com opção de **contato para feedbacks e melhorias do sistema**

---

## 2. Tela de Cadastro de Produto

- Botão **"NOVO PRODUTO"** centralizado e em destaque
- **Login e usuário** no topo direito
- Formulário centralizado na tela

### Campos do formulário

- Código do produto
- Nome do produto
- Data de entrada
- Quantidade em estoque
- Preço
- Cores disponíveis
- (Opcional) Imagem do produto

### Ações

- **Salvar** (em destaque)
- **Cancelar**

---

## 3. Tela de Detalhes do Produto

- Título da página: **"Detalhes do Produto"**
- Informações do usuário (login) no canto superior direito

### Informações exibidas

- **Nome do produto** (em destaque)
- Código do produto
- Data de entrada
- Quantidade em estoque
- Preço
- Cores disponíveis (representadas visualmente, se possível)
- Imagem do produto (caso cadastrada)

### Ações disponíveis

- **Editar produto** (redireciona para tela de edição)
- **Excluir produto**
- **Voltar** (retorna para listagem)

---

# 4. Tela Complementar — Cadastro de Loja

Campos necessários:

- Nome da loja
- CNPJ
- Descrição da loja (resumo + o que a loja oferece)
- Fotos reais atualizadas  
  - Atualização anual
  - Limite de fotos
- Localização
  - Rua
  - Número
  - Bairro
  - Cidade
  - CEP
  - Link de localização (Google Maps)
- Data de abertura (opcional)
- Seção de personalização (layout / tema)
- Telefone / WhatsApp
- Email
- Horário de funcionamento
- Categoria da loja (com opções limitadas)
- Nome do dono / sócios
- Telefone profissional do dono / sócios

---

# Interface do Usuário

A identidade visual do sistema foi definida com foco em **clareza, acessibilidade e experiência do usuário**, priorizando um design **moderno, limpo e intuitivo**.

A paleta de cores utiliza **tons suaves e profissionais**, evitando excesso de estímulos visuais e proporcionando uma navegação confortável.

A **instintividade e acessibilidade** são extremamente importantes para os mecanismos de busca e para tornar o sistema fácil de usar, tanto para o usuário quanto para o programador compreender o código de forma mais semântica e organizada.

---

# Paleta de Cores

### Azul profundo — `#1E2A44`
Utilizado no **cabeçalho e elementos estruturais principais**.  
Transmite **confiança, estabilidade e profissionalismo**.

### Laranja vibrante — `#F97316`
Utilizado em **botões de destaque** como:
- Novo Produto
- Filtrar

Serve para **chamar atenção do usuário para ações importantes**.

### Verde moderno — `#22C55E`
Aplicado em botões de **confirmação**, como **Salvar**.  
Representa **ações positivas e sucesso**.

### Off-white — `#F9FAFB`
Utilizado como **cor de fundo principal da aplicação**.  
Reduz o cansaço visual e melhora a leitura.

### Cinza médio — `#6B7280`
Utilizado em **textos secundários e descrições**.

### Cinza escuro — `#111827`
Aplicado em **textos principais**, garantindo **alta legibilidade**.
