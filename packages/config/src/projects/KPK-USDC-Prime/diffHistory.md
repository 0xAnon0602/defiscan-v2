Generated with discovered.json: 0x9d701a00f3b5e7c2db956d0ea3a35be1393409d4

# Diff at Fri, 22 May 2026 22:10:10 GMT:

- author: 0xAnon (<utkarshshail005@protonmail.com>)
- comparing to: main@fff796d84f33ecabd5f943e9629ebe2473a814a5 block: 1779209489
- current timestamp: 1779487728

## Description

Provide description of changes. This section will be preserved.

## Watched changes

```diff
    contract MorphoMarketV1AdapterV2 (eth:0x1d511811ACA9d8817a3e50F29CadFf6243A02902) {
    +++ description: None
      values.realAssets:
-        21353196014110
+        22409572440189
    }
```

```diff
    contract VaultV2 (eth:0x4Ef53d2cAa51C447fdFEEedee8F07FD1962C9ee6) {
    +++ description: None
      values._totalAssets:
-        21354523920980
+        22408742131782
      values.accrueInterestView.0:
-        21354963433301
+        22409572440189
      values.lastUpdate:
-        1779190235
+        1779460235
    }
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 1779209489 (main branch discovery), not current.

```diff
    contract VaultV2 (eth:0x4Ef53d2cAa51C447fdFEEedee8F07FD1962C9ee6) {
    +++ description: None
      values.marketOracles:
-        ["eth:0x36Cb058364a811636685ef15a71E8ea99043f815","eth:0xE8aDfF9117151fb5ad7313873780b87cC56EEDB0","eth:0xA6D6950c9F177F1De7f7757FB33539e3Ec60182a","eth:0xDddd770BADd886dF3864029e4B377B5F6a2B6b83","eth:0x48F7E36EB6B826B2dF4B2E630B62Cd25e89E40e2","eth:0x57bfdF6aB73995C5af58A95A16798190e366CA5b","eth:0xDCc04fFaCD7B49035cCdBbbA59a5f955944129DB","eth:0x0F948CBa8231Db7898ef36A4212581Ad7b1B4580"]
    }
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0x36Cb058364a811636685ef15a71E8ea99043f815)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0xE8aDfF9117151fb5ad7313873780b87cC56EEDB0)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0xA6D6950c9F177F1De7f7757FB33539e3Ec60182a)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0xDddd770BADd886dF3864029e4B377B5F6a2B6b83)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0x48F7E36EB6B826B2dF4B2E630B62Cd25e89E40e2)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0x57bfdF6aB73995C5af58A95A16798190e366CA5b)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0xDCc04fFaCD7B49035cCdBbbA59a5f955944129DB)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MorphoChainlinkOracleV2 (eth:0x0F948CBa8231Db7898ef36A4212581Ad7b1B4580)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0x8200f6622bb906a78896a3da4ddc81ebc8a08458)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0x5f4ec3df9cbd43714fe2740f5e3616155c5b8419)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0x8fffffd4afb6115b954bd326cbe7b4ba576818f6)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0xf4030086522a5beea4988f8ca5b36dbc97bee88c)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0xfdfd9c85ad200c506cf9e21f1fd8dd01932fbb23)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0x4f67e4d9bd67efa28236013288737d39aef48e79)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0x986b5e1e1755e3c2440e960477f25201b0a8bbd4)
    +++ description: None
```

```diff
-   Status: DELETED
    contract PriceFeed (eth:0xcf17f459f4d1d9e6fb5aa5013bd2d7eb6083bd45)
    +++ description: None
```

```diff
-   Status: DELETED
    contract PriceFeed (eth:0x6a5a24455e5c9c288632944a88cea923e0496024)
    +++ description: None
```

```diff
-   Status: DELETED
    contract PriceFeed (eth:0xb415eaa355d8440ac7ecb602d3fb67ccc1f0bc81)
    +++ description: None
```

```diff
-   Status: DELETED
    contract EACAggregatorProxy (eth:0xc0053f3fbccd593758258334dfce24c2a9a673ad)
    +++ description: None
```

Generated with discovered.json: 0xd373cef450295caa4959b15f11052c5393c6b4af

# Diff at Tue, 19 May 2026 16:52:34 GMT:

- author: 0xAnon0602 (<utkarshshail005@protonmail.com>)
- current timestamp: 1779209489

## Description

Discovery rerun on the same block number with only config-related changes.

## Initial discovery

```diff
+   Status: CREATED
    contract MetaMorphoV1_1Factory (eth:0x1897A8997241C1cD4bD0698647e4EB7213535c24)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoMarketV1AdapterV2 (eth:0x1d511811ACA9d8817a3e50F29CadFf6243A02902)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoMarketV1AdapterV2Factory (eth:0x32BB1c0D48D8b1B3363e86eeB9A0300BAd61ccc1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Safe (eth:0x354C92aF243d53A24feb3dFF20372Af7b7c47478)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RegistryList (eth:0x3696c5eAe4a7Ffd04Ea163564571E9CD8Ed9364e)
    +++ description: None
```

```diff
+   Status: CREATED
    contract VaultV2 (eth:0x4Ef53d2cAa51C447fdFEEedee8F07FD1962C9ee6)
    +++ description: None
```

```diff
+   Status: CREATED
    contract AdaptiveCurveIrm (eth:0x870aC11D48B15DB9a138Cf899d20F13F79Ba00BC)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Safe (eth:0x9F230218cf7FDe6A9246e6f8CB0b888377E92639)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoMarketV1Registry (eth:0xa31788949D0FE443D3D1033222Fc9479499Bc3f5)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MetaMorphoFactory (eth:0xA9c3D3a366466Fa809d1Ae982Fb2c46E5fC41101)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoMarketV1AdapterFactory (eth:0xb049465969ac6355127cDf9E88deE63d25204d5D)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Morpho (eth:0xBBBBBbbBBb9cC5e90e3b3Af64bdAF62C37EEFFCb)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoVaultV1Registry (eth:0xcA38e878439E02f2FEb364a2B36B52789F983727)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (eth:0xcBa28b38103307Ec8dA98377ffF9816C164f9AFa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoVaultV1Registry (eth:0xCef9Ee779Ef9428f50bB7a21B3E3b4eFdbc33844)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoVaultV1AdapterFactory (eth:0xD1B8E2dee25c2b89DCD2f98448a7ce87d6F63394)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Roles (eth:0xD5b66FD462b46B9A08c427ddAf7DC50C05a8dF7d)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Safe (eth:0xf8182E5827c06a47A985eC565A3bcd56437a97bE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MorphoMarketV1RegistryV2 (eth:0xFb4d38d93736A040993C50AAAc776a2Be2cff8Be)
    +++ description: None
```
