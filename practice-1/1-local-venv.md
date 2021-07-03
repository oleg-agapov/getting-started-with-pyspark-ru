# Установка Pyspark локально из pip

## Предварительные требования

1. Python 3.6+

2. Установленная Java/OpenJDK версии 11 или выше.

   Проверить установку из терминала (Linux/macOs):

   ```bash
   java -version

   openjdk version "15.0.1" 2020-10-20
   OpenJDK Runtime Environment (build 15.0.1+9)
   OpenJDK 64-Bit Server VM (build 15.0.1+9, mixed mode, sharing)
   ```

## Установка Apache Spark

1. Делаем виртуальное окружение Python:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Активируем окружение:

   ```bash
   source venv/bin/activate
   ```

3. Ставим pyspark из `pip`:

   ```bash
   (venv) pip install pyspark
   ```
