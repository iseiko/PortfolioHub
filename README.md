# PortfolioHUB

[![Pages](https://img.shields.io/badge/Pages-Published-brightgreen)](https://iseiko.github.io/PortfolioHub/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Um portfólio acadêmico e profissional desenvolvido com HTML5, CSS3 e JavaScript, integrado com GitHub API para exibição automática de projetos.**

---

## 📋 Sobre o Projeto

O **PortfolioHUB** é uma plataforma de portfólio pessoal que centraliza projetos acadêmicos e pessoais, oferecendo uma experiência responsiva e moderna. A plataforma integra-se diretamente com a API pública do GitHub, permitindo que os projetos cadastrados sejam exibidos automaticamente, mantendo o portfólio sempre atualizado sem necessidade de alterações manuais.

### 📚 Contexto Acadêmico
- **Estudante:** Kauan Vinicius Oliveira Silva
- **Curso/Disciplina:** Ciência da Computação / Bootcamp
- **Data de Entrega:** 13/06/2026
- **Defesa do Projeto:** [YouTube](https://youtu.be/3ec-44QhYsk?si=5-VnYRl21jtq9NBF)

---

## 🏗️ Estrutura do Sistema

```
PortfolioHub/
│
├── README.md                          # Documentação principal
├── .gitignore                         # Exclusões de versionamento
│
└── projetos-academicos/
    └── site-pessoal/
        ├── index.html                 # Página principal do portfólio
        ├── style.css                  # Estilos e responsividade
        ├── script.js                  # Lógica e integração com GitHub API
        └── README.md                  # Documentação específica do projeto
```

### Componentes Principais
- **index.html** - Estrutura semântica da página
- **style.css** - Design responsivo com media queries
- **script.js** - Integração com GitHub API para buscar repositórios públicos

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|-----------|--------|-----|
| HTML5 | - | Estrutura e semântica |
| CSS3 | - | Estilos e responsividade |
| JavaScript | - | Lógica e integração com API |
| Git | - | Controle de versão |
| GitHub | - | Hospedagem e versionamento |
| GitHub Pages | - | Deploy automático |
| GitHub API | v3 | Integração de dados de repositórios |

---

## 📦 Funcionalidades

### ✅ Funcionalidades Implementadas
- 📱 **Responsividade completa** - Funciona em smartphones, tablets e desktops
- 🔗 **Links sociais** - Integração com GitHub e LinkedIn
- 📧 **Contato por email** - Link `mailto` para comunicação direta
- 🎨 **Design limpo** - Interface moderna e intuitiva
- 🔄 **Integração GitHub API** - Exibição automática de repositórios públicos
- 📝 **Documentação** - README completo e bem estruturado

### 🚀 Possíveis Extensões Futuras
- Dashboard dinâmico com projetos destacados
- Filtro de projetos por linguagem
- Sistema de comentários
- Portfolio em múltiplas línguas

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com a internet (para integração com GitHub API)
- Git (opcional, apenas para clonar o repositório)

### Passos para Execução Local

#### Opção 1: Clonar o Repositório
```bash
# Clonar o repositório
git clone https://github.com/iseiko/PortfolioHub.git

# Navegar até a pasta do projeto
cd PortfolioHub/projetos-academicos/site-pessoal

# Abrir no navegador
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

#### Opção 2: Direto pelo GitHub
1. Acesse [PortfolioHub no GitHub](https://github.com/iseiko/PortfolioHub)
2. Navegue até `projetos-academicos/site-pessoal/`
3. Clique em `index.html`
4. Clique em "View raw" e depois use `Ctrl+S` para salvar

#### Opção 3: Versão Online
Acesse diretamente: https://iseiko.github.io/PortfolioHub/

---

## 🔌 Integração com GitHub API

### Como Funciona
O arquivo `script.js` consulta a **GitHub API v3** para obter automaticamente a lista de repositórios públicos. Isso significa:

- ✅ Não é necessário atualizar manualmente a lista de projetos
- ✅ Novos repositórios aparecem automaticamente no portfólio
- ✅ Dados sempre atualizados (nome, descrição, linguagem, link)
- ✅ Sem necessidade de credenciais para repositórios públicos

### Endpoint Utilizado
```
https://api.github.com/users/iseiko/repos
```

### Exemplo de Resposta
```json
{
  "id": 1241518247,
  "name": "PortfolioHub",
  "full_name": "iseiko/PortfolioHub",
  "description": "Portfólio acadêmico e pessoal",
  "html_url": "https://github.com/iseiko/PortfolioHub",
  "language": "HTML"
}
```

---

## 🔒 Segurança e Boas Práticas

### Medidas de Segurança Implementadas

#### 1. Gerenciamento de Arquivos Sensíveis
- ✅ Arquivo `.gitignore` configurado
- ✅ Exclusão de credenciais e configurações privadas
- ✅ Nenhuma informação sensível no controle de versão

#### 2. Proteção da Branch Principal
- ✅ Regras de proteção ativadas na branch `main`
- ✅ Todas as alterações passam por Pull Request
- ✅ Pushes diretos bloqueados
- ✅ Revisão de código obrigatória

#### 3. Monitoramento de Dependências
- ✅ Dependabot habilitado
- ✅ Verificação automática de vulnerabilidades
- ✅ Alertas de segurança em tempo real
- ✅ Sugestões de atualização automáticas

#### 4. Controle de Acesso
- ✅ Apenas o proprietário tem permissões de escrita
- ✅ Redução de riscos de alterações não autorizadas
- ✅ Princípio do menor privilégio aplicado

---

## 📊 Versionamento e Fluxo de Trabalho

### Estratégia de Branches

```
main (branch estável e protegida)
  ↑
  │ (Pull Request)
  │
develop (branch de desenvolvimento)
  ↑
  ├── feature/nova-funcionalidade
  ├── bugfix/correcao-bug
  └── docs/atualizacao-documentacao
```

### Práticas Adotadas
- 📝 Commits com mensagens claras e objetivas
- 🔄 Pull Requests para todo código novo
- 📚 Documentação atualizada junto com código
- ✅ Testes de responsividade antes de merge

---

## 🧪 Testes e Validação

### Testes de Responsividade
O projeto foi testado nos seguintes dispositivos e resoluções:
- 📱 Smartphones (320px - 480px)
- 📱 Tablets (481px - 768px)
- 💻 Desktops (769px+)

### Verificação de Funcionalidades
- ✅ Links sociais funcionam corretamente
- ✅ Email mailto abre cliente de email padrão
- ✅ Integração com GitHub API retorna dados
- ✅ Interface responsiva em todas as resoluções
- ✅ GitHub Pages Deploy automático

---

## 📖 Documentação Complementar

### Arquivos de Documentação
- [`projetos-academicos/site-pessoal/README.md`](projetos-academicos/site-pessoal/README.md) - Documentação específica do projeto
- [`.gitignore`](.gitignore) - Arquivos e pastas ignorados pelo Git

### Links Importantes
- 🌐 **Site Publicado:** https://iseiko.github.io/PortfolioHub/
- 💾 **Repositório GitHub:** https://github.com/iseiko/PortfolioHub
- 📹 **Vídeo de Defesa:** https://youtu.be/3ec-44QhYsk?si=5-VnYRl21jtq9NBF

---

## 👤 Autor

**Kauan Vinicius Oliveira Silva**

- 💼 [LinkedIn](https://www.linkedin.com/in/kauan-silva-25009035a)
- 🐙 [GitHub](https://github.com/iseiko)
- 📧 [Email](mailto:spam.kvncs@gmail.com)

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Abra uma issue ou envie um pull request.

---

## 📅 Histórico de Atualizações

### v1.0 - 13/06/2026
- ✅ Implementação inicial do PortfolioHub
- ✅ Integração com GitHub API
- ✅ Design responsivo
- ✅ Documentação completa
- ✅ Deploy em GitHub Pages
- ✅ Segurança e boas práticas implementadas

---

**Desenvolvido como parte do Bootcamp de Ciência da Computação**

Última atualização: 14/06/2026
