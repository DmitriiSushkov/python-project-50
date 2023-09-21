### Hexlet tests and linter status:
[![Actions Status](https://github.com/DmitriiSushkov/python-project-50/workflows/hexlet-check/badge.svg)](https://github.com/DmitriiSushkov/python-project-50/actions)

### CI check
[![Python CI](https://github.com/DmitriiSushkov/python-project-50/actions/workflows/main.yml/badge.svg)](https://github.com/DmitriiSushkov/python-project-50/actions/workflows/main.yml)

### Maintainability status
[![Maintainability](https://api.codeclimate.com/v1/badges/31e690ee183998f3ee0c/maintainability)](https://codeclimate.com/github/DmitriiSushkov/python-project-50/maintainability)

### Test Coverage status
[![Test Coverage](https://api.codeclimate.com/v1/badges/31e690ee183998f3ee0c/test_coverage)](https://codeclimate.com/github/DmitriiSushkov/python-project-50/test_coverage)


# DESCRIPTION:

**Вычислитель отличий**

Запускается из командной строки и вычисляет отличия между двумя файлами. На данный момент работает с JSON и YAML.

**Установка**
Через клонирование репозитория
```
$ git clone git@github.com:kazyamov/python-project-50.git
```
And install dependencies
```
$ make install
```

or

```
$ poetry install
```

**Запуск справки:**

`gendiff -h`

**Запуск скрипта c настройками по-умолчанию:**

`gendiff <file_path1> <file_path2>`

**Сравнение двух плоских файлов: JSON.**
[![asciicast](https://asciinema.org/a/BT3cK40zjQEyVxcaMmG9YR8RP.svg)](https://asciinema.org/a/BT3cK40zjQEyVxcaMmG9YR8RP)

**Сравнение двух плоских файлов: YAML(YML).**
[![asciicast](https://asciinema.org/a/1L2oH9hnEnOBWdp99QDLRqS6G.svg)](https://asciinema.org/a/1L2oH9hnEnOBWdp99QDLRqS6G)

**Сравнение двух файлов c рекурсивной структурой: YAML(YML) или JSON.**
[![asciicast](https://asciinema.org/a/lCXRxTLZmdTaDrQSG9bWdlqff.svg)](https://asciinema.org/a/lCXRxTLZmdTaDrQSG9bWdlqff)

**Плоский формат отображения - cравнение двух файлов c рекурсивной структурой YAML(YML) или JSON.**
[![asciicast](https://asciinema.org/a/BD4Z7VK4Q3ifbQcLvSFqklLcP.svg)](https://asciinema.org/a/BD4Z7VK4Q3ifbQcLvSFqklLcP)

**Вывод результата сравнения в формате JSON.**
[![asciicast](https://asciinema.org/a/GZ0vltCybm0pwTLHRwokvmsyC.svg)](https://asciinema.org/a/GZ0vltCybm0pwTLHRwokvmsyC)