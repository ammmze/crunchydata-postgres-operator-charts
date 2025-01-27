# [PGO](https://github.com/CrunchyData/postgres-operator), Crunchy [Postgres Operator](https://github.com/CrunchyData/postgres-operator) Examples

This repository contains examples for deploying PGO, the Postgres Operator from Crunchy Data, using a variety of examples.

For general questions or community support, we welcome you to join our [community Discord](https://discord.gg/BnsMEeaPBV). If you believe you have discovered a bug, please open an issue in the [PGO project](https://github.com/CrunchyData/postgres-operator).

The examples are grouped by various tools that can be used to deploy them.

The best way to get started is to fork this repository and experiment with the examples.

Each of the examples has its own README that guides you through the process of deploying it.

You can find the full [PGO documentation](https://access.crunchydata.com/documentation/postgres-operator/v5/) for the project here:

[https://access.crunchydata.com/documentation/postgres-operator/v5/](https://access.crunchydata.com/documentation/postgres-operator/v5/)

You can find out more information about [PGO](https://github.com/CrunchyData/postgres-operator), the [Postgres Operator](https://github.com/CrunchyData/postgres-operator) from [Crunchy Data](https://www.crunchydata.com) at the project page:

[https://github.com/CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator)

## Helm Install

### Add repository

```shell
helm repo add crunchydata-pgo-charts https://ammmze.github.io/crunchydata-postgres-operator-charts
```

### Install pgo (i.e. postgres operator)

```shell
helm install pgo crunchydata-pgo-charts/pgo
```
### Install a postgresql cluster

```shell
helm install pgo crunchydata-pgo-charts/postgrescluster
```
