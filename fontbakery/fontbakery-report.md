## FontBakery report

fontbakery version: 1.0.0







## Check results



<details><summary>[11] MozillaText[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* u1F409 (U+1F409): L&lt;&lt;288.0,198.0&gt;--&lt;234.0,198.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;288.0,333.0&gt;--&lt;234.0,333.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;453.0,149.0&gt;--&lt;453.0,199.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;288.0,387.0&gt;--&lt;234.0,387.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;453.0,235.0&gt;--&lt;453.0,285.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;288.0,562.0&gt;--&lt;234.0,562.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;478.0,494.0&gt;--&lt;439.0,531.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;532.0,624.0&gt;--&lt;478.0,624.0&gt;&gt; has the same coordinates as a previous segment.

* u1F409 (U+1F409): L&lt;&lt;580.0,410.0&gt;--&lt;580.0,464.0&gt;&gt; has the same coordinates as a previous segment.

* u1F432 (U+1F432): L&lt;&lt;288.0,198.0&gt;--&lt;234.0,198.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni004A0301

- uni006A0301

- uni0308.case.narrow
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, math, coptic, tai-le, canadian-aboriginal, duployan, old-permic, malayalam, hebrew, syriac, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: math, yi, symbols, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* acircumflex (U+00E2): X=272.0,Y=692.0 (should be at cap-height 690?)

* acircumflex (U+00E2): X=260.0,Y=692.0 (should be at cap-height 690?)

* amacron (U+0101): X=126.0,Y=691.0 (should be at cap-height 690?)

* amacron (U+0101): X=406.0,Y=691.0 (should be at cap-height 690?)

* atilde (U+00E3): X=276.5,Y=688.0 (should be at cap-height 690?)

* ecircumflex (U+00EA): X=307.0,Y=692.0 (should be at cap-height 690?)

* ecircumflex (U+00EA): X=295.0,Y=692.0 (should be at cap-height 690?)

* emacron (U+0113): X=161.0,Y=691.0 (should be at cap-height 690?)

* emacron (U+0113): X=441.0,Y=691.0 (should be at cap-height 690?)

* icircumflex (U+00EE): X=169.0,Y=692.0 (should be at cap-height 690?)

* icircumflex (U+00EE): X=157.0,Y=692.0 (should be at cap-height 690?)

* imacron (U+012B): X=45.0,Y=691.0 (should be at cap-height 690?)

* imacron (U+012B): X=281.0,Y=691.0 (should be at cap-height 690?)

* ntilde (U+00F1): X=313.5,Y=688.0 (should be at cap-height 690?)

* ocircumflex (U+00F4): X=309.0,Y=692.0 (should be at cap-height 690?)

* ocircumflex (U+00F4): X=297.0,Y=692.0 (should be at cap-height 690?)

* omacron (U+014D): X=163.0,Y=691.0 (should be at cap-height 690?)

* omacron (U+014D): X=443.0,Y=691.0 (should be at cap-height 690?)

* otilde (U+00F5): X=313.5,Y=688.0 (should be at cap-height 690?)

* ucircumflex (U+00FB): X=301.0,Y=692.0 (should be at cap-height 690?)

* ucircumflex (U+00FB): X=289.0,Y=692.0 (should be at cap-height 690?)

* umacron (U+016B): X=155.0,Y=691.0 (should be at cap-height 690?)

* umacron (U+016B): X=435.0,Y=691.0 (should be at cap-height 690?)

* wcircumflex (U+0175): X=437.0,Y=692.0 (should be at cap-height 690?)

* wcircumflex (U+0175): X=425.0,Y=692.0 (should be at cap-height 690?)

* ycircumflex (U+0177): X=288.0,Y=692.0 (should be at cap-height 690?)

* ycircumflex (U+0177): X=276.0,Y=692.0 (should be at cap-height 690?)

* acircumflex.ss01: X=298.0,Y=692.0 (should be at cap-height 690?)

* acircumflex.ss01: X=286.0,Y=692.0 (should be at cap-height 690?)

* amacron.ss01: X=152.0,Y=691.0 (should be at cap-height 690?)

* amacron.ss01: X=432.0,Y=691.0 (should be at cap-height 690?)

* aogonek.ss01: X=466.0,Y=-2.0 (should be at baseline 0?)

* atilde.ss01: X=302.5,Y=688.0 (should be at cap-height 690?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* uni0302 (U+0302): X=206.0,Y=692.0 (should be at cap-height 690?)

* uni0302 (U+0302): X=194.0,Y=692.0 (should be at cap-height 690?)

* tildecomb (U+0303): X=210.5,Y=688.0 (should be at cap-height 690?)

* uni0304 (U+0304): X=0.0,Y=691.0 (should be at cap-height 690?)

* uni0304 (U+0304): X=280.0,Y=691.0 (should be at cap-height 690?)

* uni0304.narrow: X=22.0,Y=691.0 (should be at cap-height 690?)

* uni0304.narrow: X=258.0,Y=691.0 (should be at cap-height 690?)

* circumflex (U+02C6): X=206.0,Y=692.0 (should be at cap-height 690?)

* circumflex (U+02C6): X=194.0,Y=692.0 (should be at cap-height 690?)

* uni02C9 (U+02C9): X=78.0,Y=692.0 (should be at cap-height 690?)

* uni02C9 (U+02C9): X=322.0,Y=692.0 (should be at cap-height 690?)

* tilde (U+02DC): X=210.5,Y=688.0 (should be at cap-height 690?)

* macron (U+00AF): X=78.0,Y=692.0 (should be at cap-height 690?)

* macron (U+00AF): X=322.0,Y=692.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



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
| 0 | 0 | 0 | 11 | 89 | 7 | 129 | 0 | 
| 0% | 0% | 0% | 5% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
