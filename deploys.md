# Deployment addresses

The latest version of `@uniswap/v3-core`, `@uniswap/v3-periphery` are deployed to Ethereum mainnet and all testnets
at the same addresses.

The source code is verified with Etherscan on all networks, for all contracts except `UniswapV3Pool`.
We are working on getting the `UniswapV3Pool` contract verified with Etherscan.

These addresses are final and were deployed from these npm package versions:

- `@uniswap/v3-core`: [`1.0.0`](https://github.com/Uniswap/uniswap-v3-core/tree/v1.0.0)
- `@uniswap/v3-periphery`: [`1.0.0`](https://github.com/Uniswap/uniswap-v3-periphery/tree/v1.0.0)

| Contract                           | Address                                      | Source Code                                                                                                                   |
| ---------------------------------- | -------------------------------------------- | 
fuji wavax 0xd00ae08403B9bbb9124bB305C09058E32C39A48c |
| UniswapV3Factory                   | `0x1F98431c8aD98523631AE4a59f267346ea31F984` | https://github.com/Uniswap/uniswap-v3-core/blob/v1.0.0/contracts/UniswapV3Factory.sol                                         |
fuji 0xF0e8A2197Bf142f509f0c78B88E62C7036c0AB80

poolhash   0x186da2ca5cb5f33ab5c3616ce6556c89189334469dfcb0cc757d410929b1ade0

| Multicall2                         | `0x5BA1e12693Dc8F9c48aAD8770482f4739bEeD696` | https://etherscan.io/address/0x5BA1e12693Dc8F9c48aAD8770482f4739bEeD696#code                                                  |
fuji 0x7a94E80Aa49449272f11cbBd2F3883c2e13d0E0F

| ProxyAdmin                         | `0xB753548F6E010e7e680BA186F9Ca1BdAB2E90cf2` | https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v3.4.1-solc-0.7-2/contracts/proxy/ProxyAdmin.sol                  |

Fuji   0x44245D5301F5B966138BAeE9Ff670032Ce9fBAbf      not flat 200 runs    not active


| TickLens                           | `0xbfd8137f7d1516D3ea5cA83523914859ec47F573` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/lens/TickLens.sol                                       |
fuji 0x091B37F669E5D0AFeEa9B5cB9E2F06dEed1bF9c9


| Quoter                             | `0xb27308f9F90D607463bb33eA1BeBb41C27CE5AB6` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/lens/Quoter.sol                                         |
Fuji QuoterV2  0x27cfa516190c8ba6CC39E3Cfa54F6E7A7A85Bccd 

| SwapRouter                         | `0xE592427A0AEce92De3Edee1F18E0157C05861564` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/SwapRouter.sol                                          |
Fuji 0xA4DCf4082A2270e95BB60Db0C5Ff4BBB63e29178

| NFTDescriptor                      | `0x42B24A95702b9986e82d421cC3568932790A48Ec` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/libraries/NFTDescriptor.sol                             |
fuji  0x300308F52D87Da59DD96d6B7c01437feabBef872   not flat   deploy account 2 ,  runs 800



| NonfungibleTokenPositionDescriptor | `0x91ae842A5Ffd8d12023116943e72A606179294f3` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/NonfungibleTokenPositionDescriptor.sol                  |
fuji 0xE03901AfEB14EbD7B628c18C1e6D3A73C54133d2       run 800


| TransparentUpgradeableProxy        | `0xEe6A57eC80ea46401049E92587E52f5Ec1c24785` | https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v3.4.1-solc-0.7-2/contracts/proxy/TransparentUpgradeableProxy.sol |
FUJI 0x5ffB86A51813c2134C1bFcb48e8aaa89d76eBE5f      not flat.  setup   logic to 		           NonfungibleTokenPositionDescriptor   admin to proxyadmin.sol   

| NonfungiblePositionManager         | `0xC36442b4a4522E871399CD717aBDD847Ab11FE88` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/NonfungiblePositionManager.sol                          |
fuji 0xE6b4FB9500cd7a3696027753E3a177e0B75AC5E4
new 0xc33615ba069b5AebdFf3814c3BD7A029fce3f3aD     runs 2000

| V3Migrator                         | `0xA5644E29708357803b5A882D272c41cC0dF92B34` | https://github.com/Uniswap/uniswap-v3-periphery/blob/v1.0.0/contracts/V3Migrator.sol                                          |
