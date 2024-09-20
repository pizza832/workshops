---
title: "Бөлмө 2: Өзгөрүүлөр Уюгу"
description: "Өзгөртүүлөрдү жасоону жана репозиторийге сактоону үйрөнүңүз."
difficulty: "Башталгыч"
weight: 2
---

# Бөлмө 2: Өзгөрүүлөр Уюгу

{{< figure src="../images/room2_commit.jpg" title="Коддун үзүндүлөрү борбордук терминалдын айланасында калкып, иреттөөнү күтүп турушат" >}}

Экинчи бөлмөгө киргенде, код үзүндүлөрү абада калкып жүрөт. Борбордо турган терминалда "Тартипти орнот, өзгөртүүлөрүңдү сактоо үчүн" деген кабар бар.

## Сиздин Миссияңыз

1. Жергиликтүү репозиторияңызда `solution.md` деген жаңы файл түзүңүз.
2. Биринчи бөлмөдөн сырдуу кодду бул файлга кошуңуз.
3. Өзгөртүүлөрдү этапка коюп, сактаңыз.

## Нускамалар

1. Терминалда `escape-room` папкасында экениңизге ишениңиз.
2. Файлды түзүп, кодду кошуңуз:

```
echo "Secret Code: GITHUB_BASICS_101" > solution.md
```

3. Өзгөртүүлөрдү этапка коюп, сактаңыз:

```
git add solution.md
git commit -m "Add solution for Room 1"
```

{{< notice warning >}}
**Кеңеш:** Ар дайым так жана түшүнүктүү өзгөртүү билдирүүлөрүн жазып туруңуз. Бул сизге жана башкаларга долбоордун тарыхын түшүнүүгө жардам берет.
{{< /notice >}}

{{< expand "Тест: Билимиңизди Текшерүү" >}}

**Суроо 1: Өзгөртүүлөрдү этапка коюу үчүн кайсы буйрукту колдонсо болот?**

{{< button href="#" >}}git stage{{< /button >}}
{{< button href="#" >}}git add{{< /button >}}
{{< button href="#" >}}git commit{{< /button >}}

**Суроо 2: commit буйругундагы -m желеги эмнени жасайт?**

{{< button href="#" >}}Өзгөртүүнү маанилүү деп белгилейт{{< /button >}}
{{< button href="#" >}}Өзгөртүүнү дароо бириктирет{{< /button >}}
{{< button href="#" >}}Өзгөртүү билдирүүсүн кошууга мүмкүндүк берет{{< /button >}}

{{< /expand >}}

Өзгөртүүңүздү сактап бүткөндө, колдонгон билдирүүңүздү киргизиңиз:

[Өзгөртүү билдирүүсү үчүн киргизүү талаасы]

{{< notice info >}}
Эскертүү: Чыныгы киргизүү талаасы жана шифрлөө функциясы өзүнчө ишке ашырылышы керек, анткени Hugo муну өзүнөн чыгарбайт.
{{< /notice >}}