# sensor-pthreads

Software desenvolvido em C utilizando **Pthreads** para processamento paralelo e análise de dados em arquivos JSON.

Os dados analisados incluem informações de:

- Temperatura
- Umidade
- Nível de bateria
- Pressão atmosférica

As informações foram coletadas por sensores do projeto :contentReference[oaicite:0]{index=0} nas cidades de :contentReference[oaicite:1]{index=1} e :contentReference[oaicite:2]{index=2}.

---

## Tecnologias Utilizadas

- Linguagem: **C**
- Biblioteca de Parsing JSON: **cJSON**
- Programação concorrente com **Pthreads**

---

## Compilação

Utilize o comando abaixo para compilar o projeto:

```bash
gcc principal.c cJSON.c -o sensores -lm -pthread
```

---

## Execução

Após a compilação, execute o programa com:
```bash
./sensores
```
---

## Objetivo do Projeto

O objetivo deste software é realizar o processamento paralelo de grandes volumes de dados de sensores IoT, utilizando múltiplas threads para melhorar o desempenho na análise das informações coletadas.

---

## Estrutura Esperada
- principal.c → Código principal da aplicação
- cJSON.c → Implementação da biblioteca cJSON
- cJSON.h → Cabeçalho da biblioteca cJSON
- Arquivos .json → Dados coletados pelos sensores

---

## Requisitos
- GCC instalado
- Sistema operacional Linux
- Biblioteca pthread disponível no sistema
