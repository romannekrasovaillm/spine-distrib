# Spine (arch) — дистрибутив

Бинарь `arch` в релизах + инструкции по развёртыванию с нуля.
Spine — доменный харнесс solution-архитектора: spine-инварианты, ADR, рубрики
с LLM-судьёй, fitness functions, handoff-пакеты кодовым харнессам, библиотека
скиллов/плагинов, фоновые субагенты, губернанс. Один бинарь: TUI + CLI + library.
Исходники редакций семейства: [spine](https://github.com/romannekrasovaillm/spine) (generic),
[spine-bank](https://github.com/romannekrasovaillm/spine-bank) (Banking Edition),
[spine-aiml](https://github.com/romannekrasovaillm/spine-aiml) (AI/ML Edition).

## Быстрый старт

1. Скачайте `arch-linux-x86_64` из последнего релиза, `chmod +x`, положите в `~/.local/bin/arch`.
2. Сверьте контрольную сумму по `SHA256SUMS.txt`.
3. Ключи — только через окружение (`DEEPSEEK_API_KEY`, `ZHIPU_API_KEY`, `KIMI_API_KEY`), конфиг — `arch init`.

Проверка без ключей: `arch mermaid examples/mermaid/flow.mmd`, `arch control score --trigger new_component=true`, `arch doctor`.
