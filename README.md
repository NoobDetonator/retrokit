# RetroKit

Um começo de design system inspirado no **Windows 95 / XP**, modernizado — mantendo a essência (barras de título em degradê, botões biselados, taskbar) mas com cantos suaves, sombras em camadas e foco acessível.

## Componentes (v0.1)
Janela · Botões (primário/danger/disabled) · Inputs & Select · Checkbox/Radio · Barra de progresso · Badge · Taskbar

## Tokens
Tudo controlado por CSS custom properties no `:root` do `style.css` (cores, tipografia, espaçamento, raio, sombras). Trocar o tema = mudar as variáveis.

## Rodar
Site estático, sem build. Abra `index.html` ou sirva a pasta:
```
npx serve .
```
