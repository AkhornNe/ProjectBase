# ProjectBase

Базовый Unity-проект.

## Как открыть

1. Клонируйте репозиторий.
2. В Unity Hub: **Add → Add project from disk** → выберите папку репозитория.
3. Unity сама создаст `Library/`, `ProjectSettings/`, `Packages/` и `.meta`-файлы — закоммитьте `ProjectSettings/`, `Packages/` и все `.meta`.

## Структура

```
Assets/_Project/
├── Scripts/
│   ├── Runtime/          # игровой код
│   └── Editor/           # редакторские утилиты (только в Editor)
├── Scenes/
├── Prefabs/
├── Materials/
├── Textures/
├── Models/
├── Audio/
├── Animations/
├── UI/
└── ScriptableObjects/
```

Весь собственный контент лежит в `Assets/_Project`, чтобы не смешиваться с пакетами из Asset Store.

## Рекомендуемые настройки Unity

- **Edit → Project Settings → Editor → Version Control: Visible Meta Files**
- **Asset Serialization: Force Text**

`.gitkeep` в пустых папках можно удалить, когда в них появятся файлы.
