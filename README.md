<div align="center">

# 🌾 AGRO LINK CENTER

### ຕົ້ນແບບຕະຫຼາດກະສິກຳຫຼາຍມືແຫ່ງຊາດ · National Multi-hand Agri-Commodity Marketplace

**ລາວ · English** — ຕົ້ນແບບຄລິກໄດ້ຈິງ (clickable prototype) · ບໍ່ຕ້ອງຕິດຕັ້ງ · ບໍ່ຕ້ອງລົງທະບຽນ

[![Open the demo](./qr.png)](https://jadesadao-blip.github.io/agro-link-prototype/)

**🔗 Live demo:** **https://jadesadao-blip.github.io/agro-link-prototype/**

_ສแกน QR ຫຼືกดลิงก์เพื่อเปิดใช้งาน · Scan the QR or click the link_

</div>

---

## ✨ ນີ້ແມ່ນຫຍັງ / What is this

ຕົ້ນແບບຂອງ **ລະບົບຕະຫຼາດຊື້ຂາຍສິນຄ້າກະສິກຳແບບສົ່ງຕໍ່ຫຼາຍມື** ສຳລັບ ສປປ ລາວ —
ໂອນ **ກຳມະສິດ** ຜ່ານ **ໃບຝາກສາງ (warehouse receipt)** ໂດຍທີ່ຂອງຈິງຍັງຢູ່ໃນສາງ,
ເຮັດໃຫ້ **Trade Volume** ເໜັງຕີງແຍກຈາກ **Physical Stock**.

A clickable prototype of a **multi-hand agricultural commodity exchange**: ownership moves
through **warehouse receipts** while the physical goods stay put — so trade volume grows
independently of physical stock, with a full farm→inspect→warehouse→trade→export chain of custody.

---

## 🧭 ວິທີລອງໃຊ້ / How to try (2 ນາທີ)

1. **ເປີດລິงก์ demo** ຂ້າງເທິງ (ຫຼື `index.html`)
2. ໜ້າ Landing → **Login (demo)** → **ເລືອກ role** (ມີ 12 ບົດບາດ / user tester)
3. ລອງເດີນ **ຂະບວນການເຕັມ** ຕາມບົດບາດຂອງທ່ານ:
   - 🧑‍🌾 **ຊາວສວນ** — ລົງທະບຽນທີ່ດິນ → ຂໍກວດ → ເກັບກ່ຽວ → ຂໍຝາກສາງ → ຕັ້ງຂາຍ
   - 🧪 **ເຈົ້າໜ້າທີ່ພາກສະໜາມ** — ຮັບຄຳຂໍກວດ → ອອກໃບຮັບຮອງ Zero-Burn
   - 🏬 **ສາງ** — ຮັບຝາກ → ອອກໃບຝາກ · 🏭 **ໂຮงงาน** — ສັ່งຊื้อ → ແປຮูป 5:1
   - 🚢 **ຜู้ส่งออก** — ຂໍໂຄຕ້າ → ຊื้อ → ສົ່ງອອກ · 🏛 **ພາກລັດ** — ຕັ້ງ Floor / ໂຄຕ້າ / ອອກລາຍງານ
4. ສະຫຼັບ **ລາວ/English** ແລະ **Dark/Light** ໄດ້ທຸກເມື່ອ (ປຸ່ມມຸມຂວາເທິງ)

> 💡 ທຸກ role ມີ **ກ່ອງຄຳຂໍ (Inbox)** — ຄຳຂໍຈາກບົດບາດອື່ນຈະມາທີ່ນີ້ ໃຫ້ກົດ **ຮັບ / ປະຕິເສດ**

---

## 🔄 ຫົວໃຈ: ຂະບວນການຫຼາຍມື / The multi-hand loop

```
ຊາວສວນ ──ຂໍກວດ──▶ ເຈົ້າໜ້າທີ່ ──ຮັບຮอง──▶ ຊາວສວນ ──ຝາກສາງ──▶ ສາງ
   │                                                              │
   └────────────────  ໃບຝາກສາງ (ໂອນກຳມະສິດ)  ◀───────────────────┘
                              │
        ພໍ່ค้า / ໂຮງງານ / ຜู้ส่งออก ──ຊื้อ-ຂາຍ ຫຼາຍທອດ──▶ ແປຮูป / ສົ່ງອອກ
```

- **3 ໂມเดลราคา:** Spot (ໂອນທັນທີ) · Contract 50/50 (มัดจำ escrow → settle) · Future (ຍິງເມื่อຕลาด ≤ trigger)
- **4 ຄັນບັງคับ:** Floor Price · Escrow/ค่าปรับ · ໂຄຕ້າສົ່ງອອກ · Traceability ຮອດ SLId ຕົ້ນທາງ
- **ການເງินจริง:** payout ຂยับกระเป๋าເงิน · escrow · report HTML/PDF (พิมพ์ได้)

---

## 🛠 ເຕັກນິກ / Tech

- **ໄຟล์ HTML ດ່ຽວ self-contained** — vanilla JS, ບໍ່ມี framework / build / backend
- ເປີດໄຟล์ตรง ๆ ຫຼື host ບ່ອນໃດກໍ່ໄດ້ (GitHub Pages / Netlify / Vercel)
- ຟอนต์: Bai Jamjuree · Noto Sans Lao · IBM Plex Mono (Google Fonts)

---

## ⚠️ ໝາຍເหตุ / Notes

- **Demo ເທົ່ານັ້น** — state ຢູ່ໃນ browser ຂອງແຕ່ລະຄົນ (ບໍ່ບັນທຶກ / ບໍ່ sync ຂ້າມກັນ)
- ບໍ່ມีการเก็บ credential ຈິງ — ໜ້າ login ເປັນ demo
- ຂໍ້ຄວາມພາສາລາວບາງส่วนอาจต้องให้เจ้าของภาษา proofread

---

<div align="center">
<sub>ATECH × ກระຊວงกสิกรรมและสิ่งแวดล้อม · Prototype</sub>
</div>
