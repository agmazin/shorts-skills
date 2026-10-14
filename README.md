# Навыки для Claude от agmazin

Маркетплейс плагинов для Claude: подключается один раз, обновления приходят сами.

## shorts-content-velizhanin

Контент-планы и сценарии шортсов, Reels и клипов для бизнеса и экспертов: хуки первых секунд, форматы, удержание, упаковка, рецепты по нишам. Методика собрана из всех 835 шортсов продюсера Николая Велижанина - пересказ своими словами, ссылки на исходные ролики внутри.

После установки просто напишите Claude задачу, например: "Сделай контент-план шортсов на месяц для онлайн-школы вязания, снимаем 4 ролика в неделю". Навык подключится сам.

## Установка в Claude (сайт, приложение)

1. Customize -> Plugins -> Add -> Add marketplace, введите `agmazin/claude-skills`.
2. Добавьте плагин `shorts-content-velizhanin`.
3. В маркетплейсе включите Sync automatically - обновления будут приходить сами.

Навык работает в чате, в Cowork и в Claude Code под тем же аккаунтом. Если он не появился, проверьте Settings -> Capabilities -> Code execution and file creation.

## Установка в Claude Code из терминала

```
/plugin marketplace add agmazin/claude-skills
/plugin install shorts-content-velizhanin@agmazin
```

Автообновление: `/plugin` -> Marketplaces -> agmazin -> Enable auto-update.
