# WrappedBTC
Official smart contract and documentation for Token Wrapped BTC (WBTC) on BNB Smart Chain. 1:1 Bitcoin-backed asset for seamless DeFi integration and OTC trading via Offchain Market.
# Token Wrapped BTC (WBTC) 🪙

[![Blockchain](https://img.shields.io/badge/Network-BSC-orange.svg)](https://bscscan.com/token/0x25e636B21Db00541a3646A2732e08c190d862B00)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.20-blue.svg)](https://soliditylang.org/)

**Token Wrapped BTC** adalah aset kripto berbasis BEP-20 yang dirancang untuk membawa nilai Bitcoin (BTC) ke dalam ekosistem Smart Chain secara transparan, aman, dan efisien.

---

## 📄 Spesifikasi Token
* **Nama:** Token Wrapped BTC
* **Simbol:** WBTC
* **Desimal:** 8 (Sesuai standar Bitcoin asli)
* **Total Supply:** 2.000.000 WBTC
* **Kontrak:** `0x25e636B21Db00541a3646A2732e08c190d862B00`
* **Jaringan:** BNB Smart Chain (BSC)

---

## 🛠 Fitur Utama
1. **Transferable:** Sepenuhnya kompatibel dengan standar BEP-20 untuk pengiriman antar dompet.
2. **Tradeable:** Dapat diperdagangkan di DEX (PancakeSwap) maupun melalui platform OTC **Offchain Market**.
3. **Withdrawable:** Mendukung mekanisme *burn-to-withdraw* untuk proses klaim aset dasar (BTC asli).
4. **Verified Source Code:** Kontrak telah diverifikasi di BscScan untuk transparansi publik.

---

## 🚀 Panduan Penggunaan

### Menambahkan ke MetaMask
1. Buka MetaMask dan pilih jaringan **BNB Smart Chain**.
2. Klik **Import Tokens**.
3. Tempel Alamat Kontrak: `0x25e636B21Db00541a3646A2732e08c190d862B00`.
4. Token akan otomatis muncul dengan simbol **WBTC** dan desimal **8**.

### Proses Withdrawal (Penarikan)
Untuk menarik BTC asli, pengguna dapat memanggil fungsi `withdraw` pada smart contract dengan menyertakan:
- **Amount:** Jumlah token yang ingin di-burn.
- **BTC Address:** Alamat dompet Bitcoin (Mainnet) tujuan.

---

## 👔 Tim Pengembang
Proyek ini dikelola oleh **Offchain Market** sebagai bagian dari inisiatif pengembangan likuiditas digital.
- **CEO:** Yahya SM
- **CTO:** Azhar

---

## 🛡 Keamanan
Kontrak ini dikembangkan menggunakan library **OpenZeppelin** yang telah melalui audit industri untuk memastikan keamanan fungsi `mint`, `burn`, dan kepemilikan aset (*Ownable*).

---
© 2026 Token Wrapped BTC Project. Tarakan, North Kalimantan.
