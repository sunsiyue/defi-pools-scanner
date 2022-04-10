# defi-pools-scanner

## How it works
1. get all pools from uniswap
2. for each pool, get
  - 7d vol
  - pool fee
  - TVL
3. get APY = 7d_vol / 7 / TVL * pool_fee * 365
4. rank by APY desc
