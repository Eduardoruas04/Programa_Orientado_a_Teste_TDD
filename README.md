-> O programa simula um jogo da velha usando a estratégia de programação orientada a teste

-> O programa pode ser compilado apenas com o comando "make all".

-> Para compilar o verificador de cobertura "make gcov".

-> Variáveis do Makefile para facilitar alterações futuras:
CXX = g++
CXXFLAGS = -std=c++11 -Wall
COVERAGE_FLAGS = -fprofile-arcs -ftest-coverage
DEBUG_FLAGS = -g
LDFLAGS = 
TARGET = testa_velha
OBJS = velha.o

-> As regras estão no arquivo Makefile

-> link do repósitorio github: https://github.com/Eduardo-ruas/Trabalho-1---MP.git

    codigo do arquivo velha.cpp desenvolvido

commit f3b90be7b01a2cf3d316ff078d927e9f96b0569c
Author: eduardoruas <eduardobritoruas@gmail.com>
Date:   Mon Dec 2 19:27:21 2024 -0300

    arquivos velha.cpp, velha.h e  testa_velha.cpp criados
