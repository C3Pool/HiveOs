mo_xmrig is HiveOS custom CPU miner package based on https://github.com/C3Pool/xmrig
fork of xmrig that allows auto switching to the most profitable CPU algo
if used to mine to C3Pool (c3pool.com or c3pool.org) pool and get paid in XMR.
If you mine directly to c3pool.com or c3pool.org pool then there is no miner fee.

List of supported algos:

    rx/0
    rx/wow
    rx/arq
    panthera
    cn-heavy/xhv
    cn-pico/trtl
    cn/half
    cn/gpu
    cn/r
    cn/0
    cn/rwz
    argon2/chukwav2
    astrobwt

For large farms (>20 CPU) to avoid difficulty issues it is adviced to use
https://github.com/C3Pool/xmrig-proxy fork of xmrig-proxy
that allows algo switching as well.

Miner differs from stock xmrig by adding algo benchmark for each suported algo
during its first run and reporting that algo_perf data to the pool that in case of
c3pool.com or c3pool.org pool allows it to offer the most profitable algo jobs for your miner
based on current coin prices and difficulties.
