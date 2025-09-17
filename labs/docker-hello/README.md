# Лабораторка: Docker Hello
Цель: собрать и запустить первый образ Python.

Команды:
- docker build -t hello-docker .
  # build: собрать образ
  # -t: задать тег (имя) образа -> hello-docker:latest
  # .: контекст сборки = текущая папка

- docker run --rm hello-docker
  # run: запустить контейнер из образа
  # --rm: удалить контейнер после завершения
