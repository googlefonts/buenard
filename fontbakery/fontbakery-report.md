## FontBakery report

fontbakery version: 0.13.0







## Check results



<details><summary>[10] Buenard[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 460 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 469:
greater, less</p>
<p>Width = 567:
logicalnot</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- CR
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: coptic, elbasan, glagolitic, gothic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, duployan, tai-le, old-permic, todhri, hebrew, tifinagh, canadian-aboriginal, malayalam, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: khudawadi, new-tai-lue, cham, syriac, saurashtra, hanifi-rohingya, myanmar, miao, hebrew, khmer, buhid, osage, sharada, thaana, caucasian-albanian, tagalog, rejang, hanunoo, nko, zanabazar-square, tai-tham, psalter-pahlavi, kaithi, adlam, sinhala, malayalam, grantha, gurmukhi, mahajani, manichaean, phags-pa, sogdian, takri, wancho, music, pahawh-hmong, mongolian, masaram-gondi, kharoshthi, old-permic, javanese, devanagari, gujarati, meetei-mayek, yi, warang-citi, telugu, lepcha, balinese, kannada, syloti-nagri, siddham, batak, lao, dogra, mandaic, tirhuta, elbasan, duployan, bhaiksuki, tai-le, armenian, gunjala-gondi, chakma, thai, limbu, tamil, tai-viet, brahmi, buginese, coptic, soyombo, tagbanwa, ahom, modi, mende-kikakui, khojki, math, symbols, bassa-vah, oriya, tifinagh, canadian-aboriginal, sundanese, kayah-li, bengali, marchen, tibetan, newa</li>
<li>U+1FA9D HOOK: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ ỉ ị̅ ị̉ i̥̅ ỉ̥ i̦̅ ỉ̦ i̧̅ ỉ̧ j̅ j̉ j̣̅ j̣̉ j̥̅ j̥̉ j̦̅ j̦̉ j̧̅ j̧̉</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Keliko (Latn, 63,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Longto (Latn, 5,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Cicipu (Latn, 44,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Aghem (Latn, 38,843 speakers), Southern Tutchone (Latn, 65 speakers), Mango (Latn, 77,000 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Basaa (Latn, 332,940 speakers), Mfumte (Latn, 79,000 speakers), Abua (Latn, 25,000 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), Zapotec (Latn, 490,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bafut (Latn, 158,146 speakers), Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Han (Latn, 6 speakers), Western Krahn (Latn, 97,800 speakers), Fur (Latn, 1,230,163 speakers), South Central Banda (Latn, 244,000 speakers), Avokaya (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Ebira (Latn, 2,200,000 speakers), Ekpeye (Latn, 226,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Northern Tutchone (Latn, 85 speakers), Ikwere (Latn, 717,000 speakers), Navajo (Latn, 166,319 speakers), Kaska (Latn, 125 speakers), Heiltsuk (Latn, 300 speakers), Nateni (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ma’di (Latn, 584,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* Agrave (U+00C0) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* backslash (U+005C) has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* breve (U+02D8) has a counter-clockwise outer contour

* caron (U+02C7) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ebreve (U+0115) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* gravecomb (U+0300) has a counter-clockwise outer contour

* gravecomb.case has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* obreve (U+014F) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* ubreve (U+016D) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* uni01F0 (U+01F0) has a counter-clockwise outer contour

* uni0306 (U+0306) has a counter-clockwise outer contour

* uni030c (U+030C) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 10 | 90 | 7 | 131 | 0 | 
| 0% | 0% | 0% | 4% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
