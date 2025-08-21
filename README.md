# 🎮 Kárita10 - Portal de Jogos

Um portal de jogos completo e moderno com 100 jogos variados em diferentes categorias e níveis de dificuldade.

## ✨ Características

- **100 Jogos Variados**: Puzzle, Ação, Estratégia, Arcade, Memória, Matemática, Palavras, Música, Esportes e Aventura
- **Interface Moderna**: Design responsivo com tema claro/escuro
- **Sistema de Ranking**: Leaderboard global, semanal e mensal
- **Perfil do Usuário**: Estatísticas, conquistas e progresso
- **Filtros Avançados**: Busca por nome, categoria e dificuldade
- **Jogos Funcionais**: Alguns jogos já implementados (Memória, Snake, Matemática)
- **Animações Suaves**: Efeitos visuais e transições fluidas
- **Notificações**: Sistema de notificações em tempo real
- **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile

## 🚀 Como Usar

1. **Clone ou baixe** os arquivos do projeto
2. **Abra** o arquivo `index.html` em seu navegador
3. **Explore** as diferentes seções do portal
4. **Jogue** os jogos disponíveis
5. **Personalize** sua experiência com temas e configurações

## 📁 Estrutura do Projeto

```
karita10-game/
├── index.html              # Página principal
├── styles/
│   ├── main.css           # Estilos principais
│   └── games.css          # Estilos específicos dos jogos
├── js/
│   ├── games-data.js      # Dados dos 100 jogos
│   ├── app.js             # Aplicação principal
│   ├── games.js           # Implementações dos jogos
│   └── ui.js              # Funcionalidades de UI
├── games/                 # Diretório para jogos adicionais
└── README.md              # Documentação
```

## 🎯 Categorias de Jogos

### 🧩 Puzzle (10 jogos)
- Quebra-Cabeça Mágico
- Sudoku Pro
- Cubo Mágico 3D
- Labirinto Infinito
- Torres de Hanoi
- E mais...

### ⚡ Ação (10 jogos)
- Corrida Espacial
- Ninja Runner
- Tiro ao Alvo
- Batalha de Naves
- Pulador Infinito
- E mais...

### ♟️ Estratégia (10 jogos)
- Xadrez Mestre
- Construtor de Cidades
- Guerra de Reinos
- Fazenda Sustentável
- Comerciante Astuto
- E mais...

### 🕹️ Arcade (10 jogos)
- Snake Clássico
- Tetris Master
- Pac-Man Moderno
- Breakout Pro
- Space Invaders
- E mais...

### 🧠 Memória (10 jogos)
- Jogo da Memória
- Sequência de Cores
- Memória de Números
- Padrões Visuais
- Memória de Sons
- E mais...

### 🧮 Matemática (10 jogos)
- Calculadora Mental
- Tabuada Master
- Geometria Divertida
- Frações Fáceis
- Álgebra Básica
- E mais...

### 📝 Palavras (10 jogos)
- Forca Digital
- Palavras Cruzadas
- Anagramas
- Sinônimos e Antônimos
- Palavras Escondidas
- E mais...

### 🎵 Música (10 jogos)
- Piano Virtual
- Ritmo Perfeito
- Identificador de Notas
- Karaokê Online
- Compositor Musical
- E mais...

### ⚽ Esportes (10 jogos)
- Futebol Virtual
- Basquete 3D
- Tênis de Mesa
- Golfe Mini
- Corrida de Carros
- E mais...

### 🗺️ Aventura (10 jogos)
- Explorador de Cavernas
- Caçador de Tesouros
- Aventura Espacial
- Mundo Submarino
- Floresta Encantada
- E mais...

## 🎮 Jogos Implementados

### Jogo da Memória
- **Como jogar**: Clique nas cartas para encontrar pares iguais
- **Objetivo**: Encontrar todos os pares no menor tempo possível
- **Controles**: Mouse

### Snake (Cobra)
- **Como jogar**: Use as setas do teclado para controlar a cobra
- **Objetivo**: Comer a comida para crescer sem bater nas paredes
- **Controles**: Setas do teclado

### Calculadora Mental
- **Como jogar**: Resolva problemas matemáticos rapidamente
- **Objetivo**: Acertar o máximo de problemas em 30 segundos
- **Controles**: Teclado numérico + Enter

## 🎨 Personalização

### Temas
- **Tema Claro**: Interface clara e limpa
- **Tema Escuro**: Interface escura para uso noturno
- **Toggle**: Clique no botão de tema no header

### Som
- **Ativar/Desativar**: Controle de som no header
- **Efeitos Sonoros**: Sons para interações e jogos

## 📱 Responsividade

O portal é totalmente responsivo e funciona em:
- **Desktop**: Interface completa com todas as funcionalidades
- **Tablet**: Layout adaptado para telas médias
- **Mobile**: Interface otimizada para smartphones

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com variáveis CSS e Flexbox/Grid
- **JavaScript ES6+**: Funcionalidades interativas
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia (Orbitron, Roboto)

## 🚀 Funcionalidades Avançadas

### Sistema de Notificações
```javascript
showNotification('Jogo iniciado com sucesso!', 'success', 3000);
```

### Confirmações
```javascript
showConfirmation('Deseja reiniciar o jogo?', 
    () => restartGame(), 
    () => console.log('Cancelado')
);
```

### Loading States
```javascript
const loading = showLoading('Carregando jogo...');
// ... operação
hideLoading(loading);
```

## 🎯 Próximas Melhorias

- [ ] Implementação completa de todos os 100 jogos
- [ ] Sistema de login e cadastro
- [ ] Multiplayer online
- [ ] Chat em tempo real
- [ ] Sistema de amigos
- [ ] Conquistas desbloqueáveis
- [ ] Modo offline
- [ ] PWA (Progressive Web App)
- [ ] Integração com redes sociais
- [ ] Sistema de monetização

## 🤝 Contribuição

Para contribuir com o projeto:

1. **Fork** o repositório
2. **Crie** uma branch para sua feature
3. **Implemente** suas melhorias
4. **Teste** todas as funcionalidades
5. **Envie** um pull request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 👨‍💻 Desenvolvedor

**Kárita10** - Portal de Jogos
- **Versão**: 1.0.0
- **Data**: 2024
- **Linguagem**: Português Brasileiro

## 🎉 Agradecimentos

- Comunidade de desenvolvedores web
- Font Awesome pelos ícones
- Google Fonts pela tipografia
- Todos os jogadores que testaram o portal

---

**Divirta-se jogando no Kárita10! 🎮✨**
