Nockminer 0.2.0 🔥 New version out!
-----------------------------------
More than 100% performance improvement over the previous version. Grab the latest version here [Releases](https://github.com/nostalgia-mining/NOCKminer/releases)

👉🏼 this version supports only v1 wallets

👉🏼 custom HiveOS wrapper that supports Flight Sheets for easy deployment on HiveOS rigs.

Features:

✅ supports HiveOS wallets via %WAL%

✅ supports GPU selection via argument --gpu

✅ all normal goldenminer arguments (for example proxy) work as hiveos extra config arguments

✅ supports CPU thread selection via argument --threads-per-card

✅ all GPU stats working properly on hiveos worker page: telemetry, accepted shares, hashrate (per GPU and total)

✅ added option to donate hashrate to me via --donate argument. Usage: --donate X where X = any number from 1 to 100 (in percentage %).

      Example: --donate 5 will donate 5% of your mining time to my wallet.
      
🫱🏼‍🫲🏽 If you like my work please consider donating, as it gives me motivation to keep working on more features. Any number is welcome!

🫱🏼‍🫲🏽 If you don't like what I'm building, you can turn it off by adding --donate 0 and I will still love you. 😊

💎 New feature: Miner stats on miner screen 📊
-----------------------------------------------
✅ Full GPU stats (hashrate, watts, temp, fan, clocks)

✅ Accepted Shares counters

✅ Block metrics

✅ Stats can be turned off by adding --nostats in the flight sheet custom config arguments. But why would you? 😊

HiveOs Flight Sheet Extra config arguments:
-------------------------------------------
    --gpu <gpu number>
        which GPUs to use while mining (comma separated).
        example: --gpu 0,2,5 will use GPUs 0, 2 and 5 (as listed on HiveOS).

    --threads-per-card <threads number>
        how many CPU threads to use while mining.
        Tip: for older CPUs use --threads-per-card 1

    --donate <donate percentage> (0-100)
        how much from your mining time you will donate to me.
        example: --donate 5 will donate 5% of your mining time.
                 --donate 0 will turn donations completely off.

    --nostats
        turns the miner stats off, so they don't appear on screen.
