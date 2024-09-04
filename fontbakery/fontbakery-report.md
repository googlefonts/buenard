## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] Buenard[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some base glyphs were missing: ẞ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some auxiliary glyphs were missing: ẞ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x1E9E (LATIN CAPITAL LETTER SHARP S)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 460 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 469:
less, greater</p>
<p>Width = 567:
logicalnot</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- CR
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: math, glagolitic, gothic, coptic, elbasan</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, math, old-permic, coptic, canadian-aboriginal, tifinagh, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: kaithi, hanunoo, hanifi-rohingya, tamil, devanagari, tai-le, dogra, grantha, coptic, brahmi, new-tai-lue, miao, myanmar, psalter-pahlavi, bassa-vah, newa, meetei-mayek, tagalog, bengali, zanabazar-square, ahom, old-permic, tirhuta, marchen, khmer, manichaean, kharoshthi, nko, buhid, oriya, batak, saurashtra, bhaiksuki, hebrew, tai-tham, telugu, takri, sharada, osage, sogdian, khojki, khudawadi, cham, gunjala-gondi, math, modi, mende-kikakui, yi, phags-pa, rejang, lao, tai-viet, armenian, thai, sundanese, buginese, lepcha, masaram-gondi, balinese, tifinagh, malayalam, soyombo, thaana, mongolian, chakma, canadian-aboriginal, mahajani, limbu, duployan, mandaic, caucasian-albanian, music, adlam, sinhala, wancho, gurmukhi, syriac, kannada, siddham, gujarati, elbasan, tagbanwa, symbols, javanese, kayah-li, tibetan, pahawh-hmong, warang-citi, syloti-nagri</li>
<li>U+1FA9D HOOK: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ ị̅ i̥̅ i̦̅ i̧̅ j̅ j̣̅ j̥̅ j̦̅ j̧̅ j̨̅ į̅ į̣̅ į̥̅ į̦̅ į̧̅ į̨̅</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Lugbara (Latn, 2,200,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Kom (Latn, 360,685 speakers), Nzakara (Latn, 50,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Ma’di (Latn, 584,000 speakers), Aghem (Latn, 38,843 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Dii (Latn, 71,000 speakers), Basaa (Latn, 332,940 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Igbo (Latn, 27,823,640 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Ebira (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
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
| 0 | 0 | 2 | 9 | 98 | 8 | 134 | 0 | 
| 0% | 0% | 1% | 4% | 39% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
