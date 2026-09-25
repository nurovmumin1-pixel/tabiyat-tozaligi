# ECO HERO — Mobile-first frontend

Bu versiya demo emas, ishlaydigan frontend prototip sifatida qayta tuzilgan.

## Qo'shilganlar
- Mobile-first 360–430px dizayn, desktop ham responsive
- Tepasi sticky/fixedga yaqin header: scroll qilganda yuqorida qoladi
- Birinchi kirishda ism + telefon + til kiritish
- 5 til: O'zbek, Rus, Qozoq, Ingliz, Tojik
- 0 EcoCoin bilan boshlash
- 1-rasm tasdiqlanmaguncha 2-rasm yopiq
- Har qanday rasm frame ichida qoladi: object-fit: contain, overflow-x hidden
- 2 ta rasm tasdiqlangandan keyin +5 EcoCoin
- Kunlik mukofot limiti 100 EcoCoin
- Kunlik limit tugagach balansdagi mavjud coinlar yo'qolmaydi; yangi kun kelganda kunlik limit 0/100 dan qayta ochiladi
- Profilga rasm qo'yish
- Ism/telefonni keyin o'zgartirish
- Bildirishnoma yoqish/o'chirish, interval 1 soat 50 daqiqa
- Ilova rangini almashtirish
- Effekt animatsiyasi
- Xarita, reyting, sovg'alar, wallet, badge va streak
- localStorage orqali demo holatni saqlash

## Muhim texnik izoh
Brauzer ochiq turganida 1:50 timer ishlaydi. Brauzer yoki telefon tizimi sahifani to'xtatsa, oddiy JavaScript timer kafolatli push yubora olmaydi. Haqiqiy mobil ilovada local notification/push notification uchun native/PWA yoki backend xizmat ulash kerak.

## Ishga tushirish
ZIPni oching va `eco-hero/index.html`ni Chrome orqali oching.
