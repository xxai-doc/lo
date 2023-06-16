<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

ສ່ວນຫນຶ່ງຂອງລະຫັດເວັບໄຊທ໌ແມ່ນແຫຼ່ງເປີດ, ຍິນດີຕ້ອນຮັບເພື່ອຊ່ວຍເພີ່ມປະສິດທິພາບການແປພາສາ.

## ລະຫັດທາງຫນ້າ

* [ລະຫັດທາງຫນ້າ](https://github.com/xxai-art/web)
* [ຊຸດພາສາສໍາລັບເວັບໄຊທ໌ທັງຫມົດ](https://github.com/xxai-art/web/tree/main/i18n)
* [ຊຸດພາສາສໍາລັບໂມດູນເຂົ້າສູ່ລະບົບ](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [ເວັບໄຊທ໌ເອກະສານຫຼາຍພາສາ](https://github.com/xxai-doc)

ພາສາການຂຽນໂປລແກລມດ້ານຫນ້າແມ່ນ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , ເຊິ່ງເພີ່ມຄຸນສົມບັດບາງຢ່າງໂດຍອີງໃສ່ syntax coffeescript, ເບິ່ງ [./coffee_plus.md](./coffee_plus.md) .

## Internationalization ຂອງເວັບໄຊທ໌ແລະເອກະສານ

ກໍ່ສ້າງໃນ 3 ໂຄງການຕໍ່ໄປນີ້

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  ຄຳຕໍ່ທ້າຍແມ່ນ `.mdt` , ທ່ານສາມາດໃຊ້ syntax ທີ່ຄ້າຍກັບ `<+ ./coffee_plus/import.js>` ເພື່ອອ້າງອີງເຖິງໄຟລ໌ພາຍນອກ, ແລະສ້າງ markdown ດ້ວຍຄຳຕໍ່ທ້າຍ `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  ການແປ Markdown ຈະບໍ່ແປລະຫັດ ແລະການເຊື່ອມຕໍ່, ແລະຈະ cache ປະໂຫຍກທີ່ແປແລ້ວ. ຖ້າການແປພາສາຖືກດັດແກ້ແຕ່ຂໍ້ຄວາມຕົ້ນສະບັບບໍ່ໄດ້ຖືກດັດແກ້, ການດໍາເນີນການອີກເທື່ອຫນຶ່ງຈະບໍ່ຂຽນທັບການແກ້ໄຂການແປພາສາ.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  ໄຟລ໌ພາສາສໍາລັບການແປເວັບໄຊທ໌ທີ່ສ້າງຂຶ້ນ `yaml` .
