<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

ແນະນໍາໃຫ້ຕິດຕັ້ງ nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) ທໍາອິດ, ແລະຫຼັງຈາກນັ້ນ `direnv allow` ຫຼັງຈາກເຂົ້າໄປໃນໄດເລກະທໍລີ ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ຈະຖືກປະຕິບັດໂດຍອັດຕະໂນມັດຫຼັງຈາກເຂົ້າໄປໃນໄດເລກະທໍລີ).

ຄວາມຫມາຍຄື: ການແປພາສາຈີນເປັນພາສາຍີ່ປຸ່ນ, ພາສາເກົາຫຼີ, ພາສາອັງກິດ, ການແປພາສາອັງກິດເປັນພາສາອື່ນໆທັງຫມົດ. ຖ້າທ່ານຕ້ອງການສະຫນັບສະຫນູນພາສາຈີນແລະພາສາອັງກິດ, ທ່ານພຽງແຕ່ສາມາດຂຽນ `zh: en` .

ຄວາມຫມາຍຄື: ການແປພາສາຈີນເປັນພາສາຍີ່ປຸ່ນ, ພາສາເກົາຫຼີ, ພາສາອັງກິດ, ການແປພາສາອັງກິດເປັນພາສາອື່ນໆທັງຫມົດ. ຖ້າທ່ານຕ້ອງການສະຫນັບສະຫນູນພາສາຈີນແລະພາສາອັງກິດ, ທ່ານພຽງແຕ່ສາມາດຂຽນ `zh: en` .

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

### ຄໍາແນະນໍາອັດຕະໂນມັດການແປພາສາເອກະສານ

ເບິ່ງລະຫັດ repository [xxai-art/doc](https://github.com/xxai-art/doc)

ແນະນໍາໃຫ້ຕິດຕັ້ງ nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) ທໍາອິດ, ແລະຫຼັງຈາກນັ້ນ `direnv allow` ຫຼັງຈາກເຂົ້າໄປໃນໄດເລກະທໍລີ ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ຈະຖືກປະຕິບັດໂດຍອັດຕະໂນມັດຫຼັງຈາກເຂົ້າໄປໃນໄດເລກະທໍລີ).

ເພື່ອຫຼີກເວັ້ນການພື້ນຖານລະຫັດຂະຫນາດໃຫຍ່ທີ່ຖືກແປເປັນຫຼາຍຮ້ອຍພາສາ, ຂ້າພະເຈົ້າໄດ້ສ້າງຖານລະຫັດແຍກຕ່າງຫາກສໍາລັບແຕ່ລະພາສາແລະສ້າງອົງການຈັດຕັ້ງເພື່ອເກັບຮັກສາພື້ນຖານລະຫັດ.

ການຕັ້ງຄ່າຕົວແປສະພາບແວດລ້ອມ `GITHUB_ACCESS_TOKEN` ແລະຈາກນັ້ນແລ່ນ [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ຈະສ້າງບ່ອນເກັບລະຫັດອັດຕະໂນມັດ.

ແນ່ນອນ, ທ່ານຍັງສາມາດວາງມັນໄວ້ໃນຖານລະຫັດ.

ການແປເອກະສານອ້າງອີງ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

ລະຫັດສະຄຣິບຖືກຕີຄວາມໝາຍດັ່ງນີ້:

[bunx](https://bun.sh/docs/cli/bunx) ແມ່ນການທົດແທນ npx, ເຊິ່ງໄວກວ່າ. ແນ່ນອນ, ຖ້າທ່ານບໍ່ໄດ້ຕິດຕັ້ງ bun, ທ່ານສາມາດນໍາໃຊ້ `npx` ແທນ.

`bunx mdt zh` renders `.mdt` ໃນ zh directory ເປັນ `.md` , ເບິ່ງ 2 ໄຟລ໌ທີ່ເຊື່ອມຕໍ່ຂ້າງລຸ່ມນີ້

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ແມ່ນລະຫັດຫຼັກສໍາລັບການແປພາສາ (ຖ້າທ່ານພຽງແຕ່ຕິດຕັ້ງ `nodejs` , ແຕ່ `bun` ແລະ `direnv` ບໍ່ໄດ້ຖືກຕິດຕັ້ງ, ທ່ານຍັງສາມາດເອີ້ນໃຊ້ `npx i18n` ເພື່ອແປພາສາ).

ມັນຈະວິເຄາະ [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , ການຕັ້ງຄ່າຂອງ `i18n.yml` ໃນເອກະສານນີ້ແມ່ນດັ່ງຕໍ່ໄປນີ້:

```
en:
zh: ja ko en
```

ຄວາມຫມາຍຄື: ການແປພາສາຈີນເປັນພາສາຍີ່ປຸ່ນ, ພາສາເກົາຫຼີ, ພາສາອັງກິດ, ການແປພາສາອັງກິດເປັນພາສາອື່ນໆທັງຫມົດ. ຖ້າທ່ານຕ້ອງການສະຫນັບສະຫນູນພາສາຈີນແລະພາສາອັງກິດ, ທ່ານພຽງແຕ່ສາມາດຂຽນ `zh: en` .

ສຸດທ້າຍແມ່ນ [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , ເຊິ່ງສະກັດເນື້ອໃນລະຫວ່າງຫົວຂໍ້ຕົ້ນຕໍແລະຄໍາບັນຍາຍທໍາອິດຂອງແຕ່ລະພາສາຂອງ `README.md` ເພື່ອສ້າງລາຍການ `README.md` . ລະຫັດແມ່ນງ່າຍດາຍຫຼາຍ, ທ່ານສາມາດເບິ່ງມັນຕົວທ່ານເອງ.

Google API ຖືກນໍາໃຊ້ສໍາລັບການແປພາສາຟຣີ. ຖ້າທ່ານບໍ່ສາມາດເຂົ້າຫາ Google ໄດ້, ກະລຸນາຕັ້ງຄ່າ ແລະຕັ້ງຕົວແທນ, ເຊັ່ນ:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

ສະຄຣິບການແປຈະສ້າງ cache ທີ່ຖືກແປຢູ່ໃນໄດເລກະທໍລີ `.i18n` , ກະລຸນາກວດເບິ່ງມັນດ້ວຍ `git status` ແລະເພີ່ມມັນໃສ່ບ່ອນເກັບຂໍ້ມູນລະຫັດເພື່ອຫຼີກເວັ້ນການແປຊ້ຳໆ.

ກະລຸນາແລ່ນ `bunx i18n` ທຸກໆຄັ້ງທີ່ທ່ານດັດແປງການແປເພື່ອອັບເດດ cache.

ຖ້າຂໍ້ຄວາມຕົ້ນສະບັບແລະການແປພາສາຖືກດັດແກ້ໃນເວລາດຽວກັນ, cache ຈະສັບສົນ, ດັ່ງນັ້ນຖ້າທ່ານຕ້ອງການດັດແກ້, ທ່ານພຽງແຕ່ສາມາດດັດແປງຫນຶ່ງ, ແລະຫຼັງຈາກນັ້ນດໍາເນີນການ `bunx i18n` ເພື່ອປັບປຸງ cache.
