# Dygers Anarchy Resource Packs

## EN

### Overview
This folder contains resource packs for the **Dygers Anarchy** server.

### Included packs
- **Dygers-Anarch** — main server resource pack.
- **DygersCases** — cases/cosmetics resource pack.
- **Emojis!** — chat emoji UI pack.
- **Lower Fire** — lower fire overlay.

### Compatibility
- Manifests are set to `format_version: 2`.
- `min_engine_version` is set to **`[1,16,0]`** to reduce “Incompatible resource pack” errors.

### Installation / How to use
#### On a Bedrock Dedicated Server (BDS)
1. Copy the pack folders into your server `resource_packs/` folder.
2. Add them to `world_resource_packs.json` (or enable them in your world settings).
3. Restart the server.

#### On a client (single player / realms)
1. Import the `.mcpack` or place the pack into the resource packs folder.
2. Enable it in **Settings -> Global Resources** or in the world’s resource packs.

### Troubleshooting
- If you still see **“Incompatible resource pack”**:
  - Make sure your game version is **>= 1.16**.
  - Check that every pack folder contains a valid `manifest.json`.
  - Avoid duplicate UUIDs across different packs.

---

## RU

### Описание
Эта папка содержит ресурс‑паки для сервера **Dygers Anarchy**.

### Что внутри
- **Dygers-Anarch** — основной ресурс‑пак сервера.
- **DygersCases** — ресурс‑пак кейсов/косметики.
- **Emojis!** — UI‑пак с эмодзи в чате.
- **Lower Fire** — уменьшенный огонь.

### Совместимость
- В манифестах используется `format_version: 2`.
- `min_engine_version` выставлен на **`[1,16,0]`**, чтобы реже появлялась ошибка “Несовместимый ресурс‑пак”.

### Установка / Как подключить
#### Для Bedrock Dedicated Server (BDS)
1. Скопируй папки паков в `resource_packs/` на сервере.
2. Добавь их в `world_resource_packs.json` (или включи в настройках мира).
3. Перезапусти сервер.

#### Для клиента (одиночная игра / realms)
1. Импортируй `.mcpack` или положи папку в папку resource packs.
2. Включи в **Настройки -> Глобальные ресурсы** или в настройках мира.

### Если не работает
- Если всё равно пишет **“Несовместимый ресурс‑пак”**:
  - Проверь версию игры (**>= 1.16**).
  - Убедись, что в каждой папке пака есть `manifest.json`.
  - Не должно быть одинаковых UUID между разными паками.
