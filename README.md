## EngineApp
Name : EngineApp

Ticker : EAPP

Maximum Supply : 21.000.000 EAPP

Liquidity Staking : 25%

Emission Fee Perblock : 100 - 1000 byte

TPS : 200-2000

Transaction Load(consensus) : 7.150.000 Transaction Speed

Block Reward : 100 EAPP

Halving : Yes

Modular : MuBdI Core

NickMod : MUB-00

SmartChain : MSC(Coming Soon)

## Requirement Installation

- Ubuntu/Debian OS latest version(12)
- Server

Specification Server

- Core : 2 core
- Ram : 4 GB
- Storage : 80 GB
- Traffic : Unlimited

## Guide

<details>
<summary>
Installation
</summary>
create folder blockchain at ~/

```sh
mkdir coins
```

Install Depedencies(choose maintainer)

```sh
apt install -y software-properties-common net-tools build-essential
```

Chmod all inside(skip if you using root)

```sh
chmod 777 -R /builder/plugins.sh &&
chmod 777 -R /builder/core.sh &&
chmod 777 -R /builder/core_qt.sh &&
chmod 777 -R fresh_install_core.sh &&
chmod 777 -R fresh_install_qt.sh &&
chmod 777 -R upgrade_core.sh &&
chmod 777 -R upgrade_qt.sh
```

Run the fresh install

```sh
./fresh_install_core.sh
```

Run the fresh install qt

```sh
./fresh_install_qt.sh
```

</details>

# COMPABILITY OS ##

| OS NAME     | COMPABILITY       |
| ----------- | ----------------- |
| Ubuntu 18.x | Deprecated        |
| Ubuntu 20.x | OK[No Bug/Glitch] |
| Ubuntu 22.x | OK[No Bug/Glitch] |
| Debian 10   | Deprecated        |
| Debian 11   | Deprecated        |
| Debian 12   | OK[No Bug/Glitch] |
| MuBdI  0.1  | Deprecated        |
| MuBdI  0.2  | Deprecated        |
| MuBdI  0.3  | Deprecated        |
| MuBdI  0.4  | Deprecated        |
| MuBdI  0.5  | OK[No Bug/Glitch] |
| MuBdI  0.6  | OK[No Bug/Glitch] |
| Armbian64   | OK[No Bug/Glitch] |

# License ##

Copyright (c) 2010-2022, Nur1labs
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

*   Redistributions of source code must retain the above copyright notice, this
    list of conditions and the following disclaimer.

*   Redistributions in binary form must reproduce the above copyright notice,
    this list of conditions and the following disclaimer in the documentation
    and/or other materials provided with the distribution.

*   Neither the name of Nur1Labs Technology nor the names of its
    contributors may be used to endorse or promote products derived from
    this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
