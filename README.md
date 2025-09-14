# 🦋 Borboletas - Simulação Interativa

Uma experiência web interativa com borboletas animadas em 3D que respondem aos movimentos do usuário.

## ✨ Características

- **Simulação 3D Realista**: Borboletas animadas com física de voo natural
- **Interatividade**: Arraste, zoom e deslize para interagir com as borboletas
- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela e dispositivos
- **Efeitos Visuais**: Iluminação e animações suaves
- **Modo Tela Cheia**: Experiência imersiva com botão de tela cheia

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização com animações e efeitos visuais
- **JavaScript**: Lógica de interação e controle
- **Three.js**: Biblioteca para renderização 3D no navegador
- **threejs-toys**: Módulo para efeitos especiais 3D

## 📦 Estrutura do Projeto

```
borboletas/
├── borboleta.html     # Página principal
├── borboleta.css      # Estilos e animações
├── borboleta.js       # Lógica da simulação 3D
└── README.md           # Este arquivo
```

## 🚀 Como Utilizar

1. Abra o arquivo `borboleta.html` em qualquer navegador moderno
2. Interaja com a simulação:
   - **Arraste**: Mova o cursor para influenciar o movimento das borboletas
   - **Zoom**: Use o scroll do mouse para aproximar/afastar
   - **Deslize**: Em dispositivos touch, use gestos para interagir

3. Use o botão de tela cheia para uma experiência imersiva

## 🎨 Personalização

O arquivo `borboletas.js` contém parâmetros configuráveis:

```javascript
const pc = butterfliesBackground({
  background: 0x88CEFF,           // Cor de fundo
  textureCount: 4,                // Número de texturas diferentes
  wingsScale: [2, 2, 2],          // Escala das asas
  wingsSpeed: 0.75,               // Velocidade do bater de asas
  noiseIntensity: 0.0025,         // Intensidade do movimento aleatório
  maxVelocity: 0.1                // Velocidade máxima das borboletas
});
```

## 🌐 Compatibilidade

- Navegadores modernos (Chrome, Firefox, Safari, Edge)
- Dispositivos desktop e móveis
- Suporte a touch gestures em tablets e smartphones

## 📝 Licença

Este projeto utiliza bibliotecas de código aberto e está disponível para fins educacionais e de entretenimento.

## 🔧 Desenvolvimento

Para modificar o projeto:

1. Edite `borboleta.css` para alterar estilos visuais
2. Ajuste os parâmetros em `borboleta.js` para modificar o comportamento das borboletas
3. Personalize o texto em `borboleta.html` conforme necessário

---

⭐ Se você gostou desta simulação, compartilhe com outros amantes da natureza e tecnologia!
