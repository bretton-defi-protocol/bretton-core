# bretton-core

## ABI

## nToken ABI
- `mint(address _beneficiary, address _underlying, uint _amount)`
- `redeem(address _beneficiary, address _underlying, uint _amount)`
- `swap(address _beneficiary, address _underlyingFrom, uint _amountFrom, address _underlyingTo)`

## Reward Pool ABI
- `claim()` - claim outstanding rewards for msg.sender
- `rewardPerSecond()` - get rewards distributed per second
- `rewardPerShare()` - get rewards distributed per share
- `earned(address _account)` - get outstanding rewards available to claim for an account

## Heco Testnet Addresses
- BRETToken - `0xa285c8A56903407f6b643418499da22cA13bDA70`
- nUSD - `0x00d7DbD988f0Ee3C56Ba4daB7F5F9BCd9A1DCA0d`
- nUSDStakingReward - `0x0F17d13b615bF4F688EA12246de6309C39d44C1D`
- whtStakingReward - `0x19F44C75C29211c933346d5Ee7b23892E2Aca2c7`

## Heco Mainnet Addresses
- BRETToken - `0x3848a76778109E6E36FF5b9F6999A8B35C3EFe19`
- nUSD - `0x106933CE131EF1c07bccA49C945AC21cf70BF939`
- nUSDStakingReward - `0xF9E025F13884007dBbbcb6FE8B490754854691B8`
- whtStakingReward - `0x7026932602660a74F8b944e2ef9754CCe4c66aE6`
