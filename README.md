# ДЗ: анализ трафика из PCAP/PCAPNG (Google Colab)

## Описание
В этом задании выполняется разбор сетевого дампа в формате `.pcapng` с помощью `scapy`.
Скрипт извлекает нужные поля из пакетов и формирует таблицу `pandas.DataFrame` для дальнейшего анализа.

## Файлы
- `dhcp.pcapng` — дамп трафика (приложение к заданию)
- `дз_*.ipynb` — ноутбук Google Colab с решением

## Требования
Проект рассчитан на запуск в **Google Colab**.

Используемые библиотеки:
- `scapy`
- `pandas`
- (опционально) `matplotlib`, `seaborn` — для визуализаций

Установка в Colab:
```python
!pip -q install scapy pandas matplotlib seaborn
