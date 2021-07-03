# Запуск Spark из Docker

## Предварительные требования

Установленный Docker.

## Установка Spark

Будем использовать образ [Jupyter notebooks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html) с установленным Apache Spark.

```bash
docker run -it -p 8888:8888 -p 4040:4040 -p 4041:4041 -v $(pwd):/home/jovyan/work jupyter/pyspark-notebook
```
