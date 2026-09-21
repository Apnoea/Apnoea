### Hi there 👋

<!--
**Apnoea/Apnoea** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Пишу на Vue 3 - в основном интерфейсы, где много состояния и графики: редакторы,
холсты, схемы. До этого 3 года техлидом: собрал фронтенд-отдел с нуля, вёл code
review и менторство, настроил CI/CD; 10+ проектов полного цикла для банков
и страховых.

AI-инструменты (Claude Code, Cursor) - основной рабочий инструмент.

---

### Чем занят сейчас

**[TMS IDE](https://github.com/Apnoea/tms-ide-vue)** · [живое демо](https://apnoea.github.io/tms-ide-vue/)

Веб-среда визуального проектирования SVG-мнемосхем для SCADA-систем - энергообъекты,
технологические процессы, инженерные сети. Разработал с нуля, единственный фронтенд
проекта. Инженер собирает схему мышью и получает файлы для исполняемой среды.

Что внутри:

- **Графический редактор схем** на JointJS - палитра с перетаскиванием, соединение
  элементов через порты, направляющие с примагничиванием, группы, слои, выравнивание,
  undo/redo, автосохранение в IndexedDB
- **Собственный векторный редактор элементов** - рисование примитивов, порты со снапом,
  декларативная анимация состояний; правка элемента доезжает до всех схем проекта
  одной операцией
- **Расширяемая библиотека** - новый элемент описывается парой «SVG-шаблон + JSON»
  и подхватывается автоматически, без изменений в коде
- **Симуляция** - предпросмотр анимации по заданным значениям тегов, с паузой
  и пошаговым прогоном, без подключения к реальной системе
- **1к+ тестов** (Vitest), CI с гейтом на формат → линт → тесты → мёртвый код → сборку
- **Десктопная сборка** на Electron из той же кодовой базы

`Vue 3` `Pinia` `Vite` `Tailwind CSS 4` `PrimeVue` `JointJS` `SVG` `IndexedDB` `Vitest` `Electron`

---

### Стек

**Основное** - JavaScript, Vue 3 (Composition API), Vite, Tailwind CSS, SCSS, SVG

**Тесты и качество** - Vitest, @vue/test-utils, ESLint, Prettier, Knip

**Инфраструктура** - GitLab CI, GitHub Actions, Docker, Git Flow, Conventional Commits

**Осваиваю под задачу** - React, Next.js, TypeScript

---

### Ещё в профиле

- **[vite-bem-template](https://github.com/Apnoea/vite-bem-template)** - стартовый
  шаблон вёрстки на Pug + SCSS по БЭМ, сборка на Vite

---

### Связь

[Telegram](https://t.me/Apnoea)
