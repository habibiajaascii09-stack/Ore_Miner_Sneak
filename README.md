# ⛏️ Ore Miner Pro (Vein Miner)

Optimized mining logistics for Minecraft Bedrock.

## 👁️ How it works
Tired of mining ores one-by-one? Sneak (crouch) while mining an ore block and the surrounding vein will be harvested instantly.

## 🛠️ Features
- **Sneak Trigger:** Only activates when you intentionally sneak.
- **Auto-Destroy:** Breaks adjacent ores in the vein and drops them as items.
- **Multi-Ore Support:** Diamond, Gold, Iron, and Coal are supported by default.
- **Lightweight:** Designed for Bedrock-compatible servers and single-player worlds.

---

# ⛏️ Ore Miner Pro

Logistik pertambangan teroptimasi untuk Minecraft Bedrock.

## 👁️ Cara kerja
Capek menambang ore satu-satu? Cukup jongkok (sneak) saat menambang ore, dan seluruh urat ore di sekitar akan dihancurkan instan.

## 🛠️ Fitur
- **Pemicu Sneak:** Hanya aktif saat kamu sengaja jongkok.
- **Hancur Otomatis:** Menghancurkan ore yang menempel dan menjatuhkannya sebagai item.
- **Dukungan Multi-Ore:** Diamond, Gold, Iron, dan Coal didukung secara bawaan.
- **Ringan:** Dirancang agar cocok untuk server Bedrock dan dunia single-player.

---

## Installation / Instalasi
1. Download the latest release .mcpack or .mcaddon from the Releases page or build the pack and export it.
2. Import the pack into Minecraft Bedrock (double-click the .mcpack / .mcaddon or move the files into the `com.mojang/behavior_packs` and `resource_packs` folders as instructed).
3. Enable the behavior/resource pack in the world settings where you want Ore Miner Pro to run.

1. Download file .mcpack atau .mcaddon dari halaman Releases atau bangun pack dari source.
2. Import pack ke Minecraft Bedrock (klik ganda .mcpack / .mcaddon atau pindahkan file ke folder `com.mojang/behavior_packs` dan `resource_packs`).
3. Aktifkan behavior/resource pack di Settings dunia yang diinginkan.

## Usage / Cara Pakai
- Sneak (crouch) while breaking an ore block to trigger vein-mining on adjacent connected ore blocks of the same type.
- The effect is local to the player who triggered it (no server-wide global toggle unless configured).

- Jongkok saat memecah ore untuk memicu vein-mining pada ore yang tersambung dengan tipe yang sama.
- Efeknya bekerja untuk pemain yang memicu (tidak otomatis global kecuali dikonfigurasi).

## Configuration / Konfigurasi
(If the pack includes a config file, list its path and options here. If not, consider adding a JSON config to allow customizing: supported ores, radius, performance limits, and toggles.)

Suggested options:
- supportedOres: list of block ids (e.g., "minecraft:iron_ore")
- maxBlocksPerActivation: integer limit to avoid lag
- fortuneAffectsDrops: boolean (whether Fortune enchantment modifies drops)
- enableInNether: boolean

## Supported Ores / Ore yang Didukung
- Diamond
- Gold
- Iron
- Coal

(If your implementation supports more ores like Redstone, Lapis, or Copper, update this list.)

## Compatibility / Kompatibilitas
- Tested on: Minecraft Bedrock version: Please update with the Bedrock versions you tested (e.g., 1.20+).
- Should work in single-player and Bedrock dedicated servers, but performance depends on server hardware and config.

## Permissions & Requirements / Izin & Persyaratan
- No special permissions required for single-player.
- On servers, OP or appropriate permissions might be needed to install/enable behavior packs.

## Known Issues / Masalah yang Diketahui
- Large veins may cause temporary lag; use `maxBlocksPerActivation` to limit impact.
- Fortune/XP behavior depends on how drops are handled in the implementation—please test and report.

## Contributing / Kontribusi
Contributions are welcome. Please open an issue to discuss features or submit a pull request.

## License / Lisensi
This project is licensed under the MIT License - see the LICENSE file for details.

## Credits
Original author / maintainer: habibiajaascii09-stack
