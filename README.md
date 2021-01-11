# wfmr
Wells Fargo mortgage rates tracker with Github Actions

![Fetch mortgage rates from Wells Fargo and store output as text](https://github.com/0xedward/wfmr/workflows/Fetch%20mortgage%20rates%20from%20Wells%20Fargo%20and%20store%20output%20as%20text/badge.svg)

`fetch.yml` workflow fetches and stores:
 - The [current rates from Wells Fargo](https://www.wellsfargo.com/mortgage/rates/) from Wells Fargo
 - The current rate information for a [30 year fixed rate purchase conforming loan from Wells Fargo](https://www.wellsfargo.com/mortgage/rates/purchase-assumptions?prod=1)
 - The current rate information for a [15 year fixed rate purchase conforming loan from Wells Fargo](https://www.wellsfargo.com/mortgage/rates/purchase-assumptions?prod=4)

For a BitBar plugin that tracks Wells Fargo's mortgage rates and sends you a text message when rates drop, check out [wfmr-bitbar](https://github.com/0xedward/wfmr-bitbar).
