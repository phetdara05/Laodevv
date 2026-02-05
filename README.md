# EventEase - Event Management System

ລະບົບຈັດການງານ (Event Management System) ທີ່ສ້າງດ້ວຍ HTML, CSS, JavaScript ແບບ Single-Page Application

## ຄຸນສົມບັດ (Features)

✅ **Event Details** - ຈັດການຂໍ້ມູນງານ
- ແກ້ໄຂຊື່ງານ, ວັນທີ, ສະຖານທີ່
- ສະແດງຜົນແບບ Real-time

✅ **Registration** - ລົງທະບຽນ
- ລົງທະບຽນຜູ້ເຂົ້າຮ່ວມງານ
- ກວດສອບອີເມວຊ້ຳ

✅ **Attendance Tracker** - ຕິດຕາມການເຂົ້າຮ່ວມ
- ບັນທຶກການມາເຖິງ
- ສະແດງສະຖານະ Present/Absent

## ການຕິດຕັ້ງ (Installation)

### 1. ດາວໂຫລດໄຟລ์
```bash
# ດາວໂຫລດ index.html ນີ້
```

### 2. ເປີດໃນ Browser
- ເປີດໄຟລ์ `index.html` ດ້ວຍ Web Browser
- ບໍ່ຈຳເປັນຕ້ອງມີ Server

## ການອັບໂຫລດໃສ່ GitHub Pages

### ວິທີທີ 1: ຜ່ານ GitHub Website

1. **ສ້າງ Repository ໃໝ່**
   - ໄປທີ່ https://github.com/new
   - ຕັ້ງຊື່: `eventease` ຫຼື ຊື່ທີ່ຕ້ອງການ
   - ເລືອກ Public
   - ກົດ "Create repository"

2. **ອັບໂຫລດໄຟລ์**
   - ກົດ "uploading an existing file"
   - ລາກໄຟລ์ `index.html` ແລະ `README.md` ມາວາງ
   - ກົດ "Commit changes"

3. **ເປີດໃຊ້ GitHub Pages**
   - ໄປທີ່ Settings > Pages
   - Branch: ເລືອກ `main` > Save
   - ລໍຖ້າ 1-2 ນາທີ
   - ເວັບຈະສາມາດເຂົ້າໄດ້ທີ່: `https://username.github.io/eventease`

### ວິທີທີ 2: ຜ່ານ Command Line (Git)

```bash
# 1. ສ້າງ Repository ໃໝ່ໃນ GitHub ກ່ອນ

# 2. Clone Repository
git clone https://github.com/YOUR_USERNAME/eventease.git
cd eventease

# 3. ວາງໄຟລ์ index.html ແລະ README.md ເຂົ້າໄປ

# 4. Push ຂຶ້ນ GitHub
git add .
git commit -m "Initial commit: EventEase application"
git push origin main

# 5. ເປີດໃຊ້ GitHub Pages ຜ່ານ Settings > Pages
```

## ໂຄງສ້າງໂປຣເຈັກ (Project Structure)

```
eventease/
│
├── index.html          # ໄຟລ์ຫຼັກ
└── README.md          # ຄູ່ມືນີ້
```

## ເຕັກໂນໂລຊີ (Technologies)

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5.3

## ການນຳໃຊ້ (Usage)

1. **Event Details**: ແກ້ໄຂຂໍ້ມູນງານ ເບິ່ງການສະແດງຜົນແບບ Real-time
2. **Register**: ລົງທະບຽນດ້ວຍຊື່ ແລະ ອີເມວ
3. **Attendance**: ເຊັກການມາເຖິງຂອງຜູ້ເຂົ້າຮ່ວມ

## ຂໍ້ມູນເພີ່ມເຕີມ

- ຂໍ້ມູນຈະຖືກເກັບໄວ້ໃນ Browser (ລົບເມື່ອ Refresh)
- ເໝາະສຳລັບການເຮັດ Demo ຫຼື Prototype
- ສາມາດປັບແຕ່ງຕາມຕ້ອງການໄດ້

## License

MIT License - ໃຊ້ງານໄດ້ຟຣີ

---

Made with ❤️ for Event Management
