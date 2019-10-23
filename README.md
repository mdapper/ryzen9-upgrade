# Ryzen 9 Upgrade Benchmarks

## Development Benchmarks

| Name       | Command            | Ryzen 9 3900X | Intel i7 4770K | Macbook Pro (13-inch 2017) |
| ---------- | ------------------ | ------------- | -------------- | -------------------------- |
| Monolith   | `yarn prod`        | 59.50s        | 158.72s        | 140.01s                    |
| Monolith   | `yarn jest`        | 6.735s        | 33.049s        | 55.56s                     |
| Monolith   | `yarn cypress:run` | 16m20s        | 35m02s         | Xs                         |
| React      | `yarn build`       | 87.10s        | 123.95s        | 107.36s                    |
| React      | `yarn test`        | 36.387s       | 151.798s       | 304.585s                   |
| Components | `yarn components`  | 8.10s         | 8.39s          | 13.70s                     |
| Components | `yarn build`       | 7m13s         | 92.09s         | 534.93s                    |
| Components | `yarn test`        | 4.125s        | 10.271s        | 32.695s                    |
| Auth API   | `mix compile`      | 29.708s       | 33.372s        | Xs                         |

## Builds

### AMD Ryzen 9 3900X

| Type         | Description                                                                                  | Specs                                                                                                                                                                                                     | Review                                                                                                           |
| ------------ | -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Processor    | AMD Ryzen 9 3900X, 12 Cores, 24 Threads, 3.8GHz, Max Boost Clock 4.6GHz, Total L3 Cache 64MB | [specs](https://www.amd.com/en/products/cpu/amd-ryzen-9-3900x)                                                                                                                                            | [review](https://www.guru3d.com/articles_pages/amd_ryzen_7_3700x_ryzen_9_3900x_review,1.html)                    |
| Motherboard  | Gigabyte X570 AORUS PRO WIFI                                                                 | [specs](https://www.gigabyte.com/us/Motherboard/X570-AORUS-PRO-WIFI-rev-10/sp#sp)                                                                                                                         | [review](https://www.tomshardware.com/reviews/gigabyte-x570-aorus_pro-wi-fi-review,6285.html)                    |
| Memory       | 32GB (2x16GB) Corsair Vengeance LPX DDR4 DRAM 3000MHz                                        | [specs](<https://www.corsair.com/us/en/Categories/Products/Memory/VENGEANCE%C2%AE-LPX-16GB-(1-x-16GB)-DDR4-DRAM-3000MHz-C16-Memory-Kit---Black/p/CMK16GX4M1D3000C16>)                                     | [review](https://thepcenthusiast.com/corsair-vengeance-lpx-ddr4-3000mhz-memory-review/)                          |
| Graphics     | XFX Radeon Rx 5700 XT 8GB GDDR6                                                              | [specs](https://www.xfxforce.com/gpus/radeon-tm-rx-5700-xt-8gb-gddr6-3xdp-hdmi)                                                                                                                           | [review](https://www.guru3d.com/articles-pages/amd-radeon-rx-5700-and-5700-xt-review,1.html)                     |
| Storage      | Samsung 970 EVO Plus 1TB SSD NVME M.2                                                        | [specs](https://www.samsung.com/semiconductor/minisite/ssd/product/consumer/970evoplus/)                                                                                                                  | [review](<https://www.guru3d.com/articles-pages/samsung-970-evo-plus-nvme-m-2-(1tb)-ssd-review,1.html>)          |
| Power Supply | CORSAIR RM750x White 750 Watt                                                                | [specs](https://www.corsair.com/eu/en/Categories/Products/Power-Supply-Units/RMx-White-Series%E2%84%A2-RM750x-%E2%80%94-750-Watt-80-PLUS%C2%AE-Gold-Certified-Fully-Modular-PSU-%28EU%29/p/CP-9020155-EU) | [review](https://www.tomshardware.com/reviews/corsair-rm750x-v2-psu,5585.html)                                   |
| Case         | NZXT H510 White Compact ATX Mid-Tower Case                                                   | [specs](https://www.nzxt.com/products/h510-matte-white)                                                                                                                                                   | [review](https://www.youtube.com/watch?v=7HK5Aulw7YI)                                                            |
| Case Fans    | 32 x Corsair LL140 RGB 140mm, 1 x Corsair LL120 RGB 120mm                                    | [specs](https://www.corsair.com/us/en/Categories/Products/Fans/ml-config/p/CO-9050073-WW)                                                                                                                 | [review](https://www.tweaktown.com/reviews/8386/corsair-ll140-dual-light-loop-rgb-led-fan-kit-review/index.html) |
| OS           | Ubuntu 18.04                                                                                 |                                                                                                                                                                                                           |

### Intel Core i7 4770K

| Type                 | Description                                                                                   | Link                                                                                                                                                        |
| -------------------- | --------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Processor            | Intel Core i7-4770K, 4 Cores, 8 Threads, 3.50 GHz, Turbo Max Clock, 3.90 GHz, 8 MB SmartCache | [specs](https://ark.intel.com/content/www/us/en/ark/products/75123/intel-core-i7-4770k-processor-8m-cache-up-to-3-90-ghz.html)                              |
| Motherboard          | Gigabyte Z87X-UD3H                                                                            | [specs](https://www.gigabyte.com/us/Motherboard/GA-Z87X-UD3H-rev-1x#ov)                                                                                     |
| Memory               | 32GB (4x8GB) Corsair Vengeance DDR3 DRAM 1600MHz                                              | [specs](https://www.corsair.com/us/en/Categories/Products/Memory/High-Performance-Memory/Vengeance%C2%AE-%E2%80%94-8GB-DDR3-Memory-Kit/p/CMZ8GX3M1A1600C10) |
| Graphics             |
| EVGA GeForce GTX 780 |                                                                                               |
| Storage              | OCZ Agility 4 120 GB                                                                          |                                                                                                                                                             |
| Power Supply         | CORSAIR HX620W                                                                                | [specs](https://www.corsair.com/us/en/Categories/Products/Power-Supply-Units/Professional-Series%E2%84%A2-HX620/p/CMPSU-620HX)                              |
| Case                 | Cooler Master CM 690 II                                                                       | [specs](https://www.coolermaster.com/catalog/cases/mid-tower/cm-690-ii-ver-2/)                                                                              |
| OS                   | Ubuntu 18.04                                                                                  |                                                                                                                                                             |

### Macbook Pro (13-inch 2017)

| Type      | Description                                                                  |
| --------- | ---------------------------------------------------------------------------- |
| Processor | 2.3GHz dual-core Intel Core i5, Turbo Boost up to 3.6GHz, with 64MB of eDRAM |
| Storage   | 256GB SSD                                                                    |
| Memory    | 8GB of 2133MHz LPDDR3 onboard memory                                         |
| Graphics  | Intel Iris Plus Graphics 640 1536 MB                                         |
