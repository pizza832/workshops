---
title: "Көнүгүү 1 - Веб редактор менен таанышуу"
date: 2019-09-03T17:53:41-07:00
draft: false
weight: 4
---

## Көнүгүү 1 - Жөнөкөй веб-сайтты жасоо

Азыр болсо жөнөкөй веб-сайтты курууга убакыт келди. Бул көнүгүүнү аяктоо үчүн сиз төмөнкү кадамдарды аткарышыңыз керек:

1. Веб редакторду ачып (төмөндөгү "Өзүңүз байкап көрүңүз!" баскычын басыңыз)
2. Аталышын кошуу үчүн баш тегдерди, ал эми Бенжи жөнүндө абзац жазуу үчүн абзац тегдерин колдонуңуз
3. Эгер убактыңыз болсо: Бенжинин сүйүктүү тамактарынын тизмесин жазыңыз: үндүк, жержаңгак майы жана жип сыры

<a class="my-2 mx-4 btn btn-info" href="https://codepen.io/Sunny-Dee/pen/exxyYL" target="_blank">Өзүңүз байкап көрүңүз!</a>

Кээ бир HTML тегдерин өз алдынча колдонуп көрүү үчүн бул маалымдама диаграммасын колдонуңуз.

Тег | Түшүндүрмө | Мисал
---|--------------|----------
`<html></html>`                         | HTML документин көрсөтөт. Ар бир веб-сайт <html> ачылыш теги менен башталып, </html> жабуу теги менен аякташы керек. | Жогорудагы Code Pen мисалын караңыз. 
`<!-- -->`                              | Комментарийди көрсөтөт. Комментарийлер башка программисттер үчүн, алар веб-сайтта көрсөтүлбөйт. |`<!-- Бул сап браузерде көрүнбөйт -->`
`<head></head>`                         | Веб-сайтты туура көрсөтүү үчүн браузерге маалымат берген бардык HTML элементтерин камтыйт. <head> жана </head> тегинин ортосундагы HTML элементтери сайтта көрсөтүлбөйт. | Жогорудагы Code Pen мисалын караңыз.
`<title></title>`                       | Браузер өтмөгүнө атоо үчүн колдонула турган веб-сайттын аталышын камтыйт. | &lt;head&gt;<br>&lt;title&gt; Менин веб-сайтым &lt;/title&gt;<br>&lt;/head&gt;
`<body></body>`                         | Текст жана сүрөттөр сыяктуу веб баракчада көрсөтүлгөн бардык HTML элементтерди камтыйт. | Жогорудагы Code Pen мисалын караңыз.
`<h1></h1>`<br> ... <br> `<h6></h6>`    | Баракчанын баш аталышын/темасын аныктайт. &lt;h1&gt; эң маанилүү (эң чоң) аталышты/теманы аныктайт, ал эми &lt;h6&gt; эң мааниси төмөн (эң кичине) аталышты/теманы аныктайт. | &lt;h1&gt;Бул чоң аталыш болот&lt;/h1&gt;<br> &lt;h4&gt;Бул кичинекей аталыш болот&lt;/h4&gt;
`<p></p>`                               | Абзацты аныктайт. | &lt;p&gt;Иттер адамдарды сүйүүгө уйронушкон. Азыр ит адамдын эң жакын досу.&lt;/p&gt;
`<div></div>`                           | Сайттагы бөлүмдү аныктайт. | &lt;div&gt;<br>&lt;h1&gt;Мен жөнүндө бардык нерсе&lt;/h1&gt;<br>&lt;/div&gt;
`<img>`                                 | Сүрөт. Бул өзүн-өзү жапкан тег, бирок сиз сүрөттү кайдан алууну билиш үчүн браузерге сүрөттүн булагын көрсөтүшүңүз керек. | &lt;img src="aka.ms/Benji-the-dog"&gt;
`<hr>`                                  | Горизонталдык сызыкты тартат. Баракчадагы контентти бөлүп койгунуз келсе, пайдалуу дагы бир өзүн-өзү жапкан тег. | ... <br> &lt;hr&gt; <br> ...
`<ul>`<br>`<li>`<br>`</li>`<br>`</ul>`  | Тизме. Тизмени баштоо үчүн &lt;ul&gt; тегин колдонуңуз. Тизмеге кошула турган ар бир нерсе үчүн &lt;li&gt; жана &lt;/li&gt;тегин колдонуңуз. Тизмени &lt;/ul&gt; теги менен бүтүрүңүз. | &lt;ul&gt;<br>&lt;li&gt;Бул тизмедеги нерсе.&lt;/li&gt;<br>&lt;/ul&gt;