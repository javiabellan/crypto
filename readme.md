Es rentable minar a un precio inferior de 5cent el KW (en España vale de 20 a 60 cents el KW)

# Monedas
Bitcoin
Ethereum
Monero
Dash
Bitcoin cash
Bitcoin voult


# GPUs
Placas base especiales (6 PCI express)
Fuente 1200 W
6 targetas AMD radeon rx 570

[Todo esto x 2]

Resultado:
- 325...328 megaHash (ethereum)
- Consumo 1500 vatios

Ganancias:
- 700€ al principio el primer mes
- luego la mitad los siguientes meses
- y al año nada

Sistema operativo: ethOS









# ASICs

antminer s17




# Hash algorithms
Hashing is the Proof of Work (POW) 


| Algorithm   | Used by coins              | Mining with  
|-------------|----------------------------|-------------
| SHA-256     | Bitcoin, Bitcoin Cash      | ASIC | Familia SHA-2
| Ethash      | Ethereum, Ethereum Classic | GPU  | Familia SHA-3 en concreto Keccak
| Equihash    | Bitcoin gold, Zcash        | GPU  | "El Problema del Cumpleaños"
| Scrypt      | Litecoin                   | ASIC |
| RandomX     | Monero                     | GPU  |
| CryptoNight | Monero ANTES               | ASIC |
| X11         | Dash                       | ASIC 
| Quark       |                            | ASIC
| X13         |
KawPow




## Minar Ethash con GPU

|                 | rx570  | 1080ti | 2080ti | Radeon VII | 12 rx570  |
|-----------------|--------|--------|--------|------------|-----------|
| Potencia (Mh/s) | 27.90  | 42.00  | 52.50  | 78.00      | 325...328 |
| Consumo (W)     | 120W   | 180W   | 180W   | 210W       | 1500W     |
| Poten/Consu     | 0.2325 | 0.2333 | 0.2916 | 0.3714     |
| Memoria         | 4Gb    | 11GB   | 11Gb   | 16Gb       |


1. Wallet
  - Mist (official Ethereum wallet) https://github.com/ethereum/mist/releases
2. GPU mining programs
  - Ethminer [ethminer](https://aur.archlinux.org/packages/ethminer)
  - Claymore
3. Pool
  - Ethpool
  - 2Miners
  - Dwarfpool

### Ejemplo ethminer con ethpool:
$ ./ethminer -G -P stratum1+tcp://YOUR_ADDRESS_HERE@us1.ethpool.org:3333


