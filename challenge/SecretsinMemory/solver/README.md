# Secrets In Memory

Author: sinambela_rc

---

## Writeup

#### ;tldr

- Diberikan file `mysterious_payload.dump` yang berisi data memori dan file `encrypted_payload.bin` yang berisi flag.
- Temukan key dan iv di dalam memory dump.
- Setelah menemukan key dan iv, gunakan keduanya untuk mendekripsi file `encrypted_payload.bin` dan temukan flag-nya.
- Flag yang ada di dalam file tersebut terenkripsi dan juga di-encode menggunakan Base64. Jadi, setelah berhasil mendekripsi, kalian perlu mendecode dari Base64 untuk mendapatkan flag-nya.

Flag:

> QUADRATHLON {C0ngr4ts_y0u_f1nd_th3_flag_zxcvbnm}
