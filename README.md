# 📚 Leitor de Arquivos com Índice Invertido

[![C Language](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Data Structure](https://img.shields.io/badge/Data%20Structure-Hash%20Table-green.svg)](https://en.wikipedia.org/wiki/Hash_table)

Um processador de textos desenvolvido em **C** que utiliza **tabela hash** para indexar palavras e contar frequências. Este projeto implementa um índice invertido simples para análise estatística de arquivos de texto.

## ✨ Funcionalidades

| Comando | Descrição | Parâmetros |
|---------|-----------|------------|
| `freq N ARQUIVO` | Exibe as N palavras mais frequentes | `N`: Quantidade (0 = todas)<br>`ARQUIVO`: Caminho do arquivo |
| `freq-word PALAVRA ARQUIVO` | Busca frequência de uma palavra | `PALAVRA`: Termo específico<br>`ARQUIVO`: Caminho do arquivo |
| `termo ARQUIVO` | Busca em múltiplos arquivos | `ARQUIVO`: Primeiro arquivo<br>*(interativo para demais)* |

## 🚀 Instalação e Uso

### Pré-requisitos
- Algum Compilador para C
- Sistema operacional compatível com C
