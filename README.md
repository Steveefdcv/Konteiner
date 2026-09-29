# Konteiner

Консольное C++ приложение, упакованное в Docker-контейнер.

## Сборка с GCC

docker build -f Dockerfile.gcc -t hello-gcc .

## Запуск

docker run --rm hello-gcc

## Сборка с Clang

docker build -f Dockerfile.clang -t hello-clang .

## Запуск

docker run --rm hello-clang
