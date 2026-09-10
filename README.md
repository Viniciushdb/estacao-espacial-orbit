# Missão Espacial: Protocolo de Homologação em Camadas

Repositório da estação espacial **estacao-espacial-orbit**, usado para praticar o fluxo corporativo de desenvolvimento em três ambientes.

## Camadas do ambiente

| Branch | Ambiente | Função |
| --- | --- | --- |
| `develop` | Desenvolvimento | Onde o módulo é implementado e evoluído. |
| `stage` | Homologação / testes | Onde o código é validado antes da produção. |
| `main` | Produção | Versão estável liberada para operação da estação. |

Fluxo: **develop → stage → main**.

## Módulo de suporte de vida

O arquivo `SuporteVida.java` monitora os níveis do ambiente da estação (oxigênio, pressão e reciclagem de água).

Para executar:

```bash
javac SuporteVida.java
java SuporteVida
```

## Tripulantes

- Vinicius (Viniciushdb)
