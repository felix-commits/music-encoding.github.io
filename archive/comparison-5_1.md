---
layout: default
title: "Comparison of MEI v5.1 and v5.0"
---
<div>
   <link rel="stylesheet" href="resources/css/main.css">
   <div id="headingArea">
      <h1>MEI Comparison <br><small><span class="">Version 5.1</span><span class=""> vs </span><span class="">Version 5.0</span></small></h1>
   </div>
   <div id="chartArea">
      <div id="chartsBox">
         <div id="elementsChart" class="chartBox"><label>Elements</label></div>
         <div id="attClassesChart" class="chartBox"><label>Attribute Classes</label></div>
         <div id="modelClassesChart" class="chartBox"><label>Model Classes</label></div>
         <div id="macroChart" class="chartBox"><label>Macro Groups</label></div>
         <div id="dataChart" class="chartBox"><label>Data Types</label></div>
         <div style="margin-top: -.5rem;"><span class="added sample">added content</span><span class="changed sample">changed content</span><span class="removed sample">removed content</span><span class="unchanged sample">unchanged content</span><span class="sample">|</span><span class="sample">click slice to go to section</span></div>
      </div>
   </div>
   <h2>Element Comparison</h2>
   <h3 id="elementsAdded">5 new elements:</h3>
   <table class="added">
      <tr class="a" id="tuning">
         <td class="element ident"><a href="https://music-encoding.org/guidelines/v5/elements/tuning.html" target="_blank">tuning</a></td>
         <td class="module">MEI.shared</td>
         <td>Describes the tuning of an instrument.</td>
         <td><a href="https://music-encoding.org/guidelines/v5/elements/tuning.html" target="_blank">visit guidelines</a></td>
      </tr>
      <tr class="a" id="course">
         <td class="element ident"><a href="https://music-encoding.org/guidelines/v5/elements/course.html" target="_blank">course</a></td>
         <td class="module">MEI.stringtab</td>
         <td>Describes the tuning of a course on a stringed instrument ( e.g. , guitar, lute).</td>
         <td><a href="https://music-encoding.org/guidelines/v5/elements/course.html" target="_blank">visit guidelines</a></td>
      </tr>
      <tr class="a" id="string">
         <td class="element ident"><a href="https://music-encoding.org/guidelines/v5/elements/string.html" target="_blank">string</a></td>
         <td class="module">MEI.stringtab</td>
         <td>Used to modify tuning information given by the course element. Describes the tuning
            of an individual string within a course on a stringed instrument ( e.g. , guitar,
            lute).</td>
         <td><a href="https://music-encoding.org/guidelines/v5/elements/string.html" target="_blank">visit guidelines</a></td>
      </tr>
      <tr class="a" id="tabDurSym">
         <td class="element ident"><a href="https://music-encoding.org/guidelines/v5/elements/tabDurSym.html" target="_blank">tabDurSym</a></td>
         <td class="module">MEI.stringtab</td>
         <td>A visual indication of the duration of a  tabGrp .</td>
         <td><a href="https://music-encoding.org/guidelines/v5/elements/tabDurSym.html" target="_blank">visit guidelines</a></td>
      </tr>
      <tr class="a" id="tabGrp">
         <td class="element ident"><a href="https://music-encoding.org/guidelines/v5/elements/tabGrp.html" target="_blank">tabGrp</a></td>
         <td class="module">MEI.stringtab</td>
         <td>A group of simultaneous tab notes, comparable to a  chord  in CMN. Rarely, may also
            contain rests, as in some "German" lute tablatures.</td>
         <td><a href="https://music-encoding.org/guidelines/v5/elements/tabGrp.html" target="_blank">visit guidelines</a></td>
      </tr>
   </table>
   <h3 id="elementsRemoved">0 removed elements:</h3>
   <table class="removed"></table>
   <h3 id="elementsChanged">42 modified elements:</h3>
   <table>
      <tr class="c" id="attacca">
         <td class="element ident">attacca</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">An instruction to begin the next section or movement of a composition without pause.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.attacca.anl</li>
               <li class="unchanged">att.attacca.ges</li>
               <li class="unchanged">att.attacca.log</li>
               <li class="unchanged">att.attacca.vis</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">target</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/attacca.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">vgrp</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="beam">
         <td class="element ident">beam</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">A container for a series of explicitly beamed events that begins and ends entirely
            within a measure.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.beam.log</li>
               <li class="unchanged">att.beam.vis</li>
               <li class="unchanged">att.beam.ges</li>
               <li class="unchanged">att.beam.anl</li>
               <li class="unchanged">model.eventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.eventLike</li>
               <li class="unchanged">model.eventLike.cmn</li>
               <li class="unchanged">model.appLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">beam.with</span></li>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/beam.html" target="_blank">place</a></span></li>
               <li class="unchanged"><span class="attribute">slash</span></li>
               <li class="unchanged"><span class="attribute">slope</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">cue</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">visible</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="beamSpan">
         <td class="element ident">beamSpan</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(beam span) – Alternative element for explicitly encoding beams, particularly those
            which extend across bar lines.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.beamSpan.log</li>
               <li class="unchanged">att.beamSpan.vis</li>
               <li class="unchanged">att.beamSpan.ges</li>
               <li class="unchanged">att.beamSpan.anl</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">beam.with</span></li>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/beamSpan.html" target="_blank">place</a></span></li>
               <li class="unchanged"><span class="attribute">slash</span></li>
               <li class="unchanged"><span class="attribute">slope</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">cue</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">visible</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="bend">
         <td class="element ident">bend</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">A variation in pitch (often micro-tonal) upwards or downwards during the course of
            a note.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.bend.log</li>
               <li class="unchanged">att.bend.vis</li>
               <li class="unchanged">att.bend.ges</li>
               <li class="unchanged">att.bend.anl</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">amount</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">bezier</span></li>
               <li class="unchanged"><span class="attribute">bulge</span></li>
               <li class="unchanged"><span class="attribute">curvedir</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/bend.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">startvo</span></li>
               <li class="unchanged"><span class="attribute">endvo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">x2</span></li>
               <li class="unchanged"><span class="attribute">y2</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="bracketSpan">
         <td class="element ident">bracketSpan</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">Marks a sequence of notational events grouped by a bracket.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.bracketSpan.log</li>
               <li class="unchanged">att.bracketSpan.vis</li>
               <li class="unchanged">att.bracketSpan.ges</li>
               <li class="unchanged">att.bracketSpan.anl</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/bracketSpan.html" target="_blank">func</a></span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">startvo</span></li>
               <li class="unchanged"><span class="attribute">endvo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">x2</span></li>
               <li class="unchanged"><span class="attribute">y2</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="breath">
         <td class="element ident">breath</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(breath mark) – An indication of a point at which the performer on an instrument requiring
            breath (including the voice) may breathe.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.breath.log</li>
               <li class="unchanged">att.breath.vis</li>
               <li class="unchanged">att.breath.ges</li>
               <li class="unchanged">att.breath.anl</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">loc</span></li>
               <li class="unchanged"><span class="attribute">ploc</span></li>
               <li class="unchanged"><span class="attribute">oloc</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/breath.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="fermata">
         <td class="element ident">fermata</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">An indication placed over a note or rest to indicate that it should be held longer
            than its written value. May also occur over a bar line to indicate the end of a phrase
            or section. Sometimes called a 'hold' or 'pause'.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.fermata.log</li>
               <li class="unchanged">att.fermata.vis</li>
               <li class="unchanged">att.fermata.ges</li>
               <li class="unchanged">att.fermata.anl</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/fermata.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">shape</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="halfmRpt">
         <td class="element ident">halfmRpt</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(half-measure repeat) – A half-measure repeat in any meter.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.halfmRpt.log</li>
               <li class="unchanged">att.halfmRpt.vis</li>
               <li class="unchanged">att.halfmRpt.ges</li>
               <li class="unchanged">att.halfmRpt.anl</li>
               <li class="unchanged">model.eventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">expand</span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/halfmRpt.html" target="_blank">dur</a></span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="harpPedal">
         <td class="element ident">harpPedal</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(harp pedal) – Harp pedal diagram.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.harpPedal.log</li>
               <li class="unchanged">att.harpPedal.vis</li>
               <li class="unchanged">att.harpPedal.ges</li>
               <li class="unchanged">att.harpPedal.anl</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">c</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">d</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">e</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">f</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">g</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">a</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">b</a></span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harpPedal.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="meterSigGrp">
         <td class="element ident">meterSigGrp</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(meter signature group) – Used to capture alternating, interchanging, mixed or other
            non-standard meter signatures.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.meterSigGrp.anl</li>
               <li class="unchanged">att.meterSigGrp.ges</li>
               <li class="unchanged">att.meterSigGrp.log</li>
               <li class="unchanged">att.meterSigGrp.vis</li>
               <li class="unchanged">model.meterSigLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="added" title="added content"><a href="#model.meterSigLike">model.meterSigLike</a></li>
               <li class="added" title="added content"><a href="#model.meterSigLike">model.meterSigLike</a></li>
               <li class="removed" title="removed content"><a href="#meterSig">meterSig</a></li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">func</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/meterSigGrp.html" target="_blank">enclose</a></span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/meterSigGrp.html" target="_blank">visible</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="octave">
         <td class="element ident">octave</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">An indication that a passage should be performed one or more octaves above or below
            its written pitch.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.octave.log</li>
               <li class="unchanged">att.octave.vis</li>
               <li class="unchanged">att.octave.ges</li>
               <li class="unchanged">att.octave.anl</li>
               <li class="unchanged">model.controlEventLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">coll</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">dis</span></li>
               <li class="unchanged"><span class="attribute">dis.place</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/octave.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="repeatMark">
         <td class="element ident">repeatMark</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">(repetition mark) – An instruction expressed as a combination of text and symbols
            – segno and coda – typically above, below, or between staves, but not on the staff.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.repeatMark.log</li>
               <li class="unchanged">att.repeatMark.vis</li>
               <li class="unchanged">att.repeatMark.ges</li>
               <li class="unchanged">att.repeatMark.anl</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/repeatMark.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">func</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">vgrp</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="mordent">
         <td class="element ident">mordent</td>
         <td class="module">MEI.cmnOrnaments</td>
         <td class="desc">An ornament indicating rapid alternation of the main note with a secondary note, usually
            a step below, but sometimes a step above.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.mordent.anl</li>
               <li class="unchanged">att.mordent.ges</li>
               <li class="unchanged">att.mordent.log</li>
               <li class="unchanged">att.mordent.vis</li>
               <li class="unchanged">model.ornamentLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">long</span></li>
               <li class="unchanged"><span class="attribute">accidupper</span></li>
               <li class="unchanged"><span class="attribute">accidlower</span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">accidupper.ges</span></li>
               <li class="unchanged"><span class="attribute">accidlower.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/mordent.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="trill">
         <td class="element ident">trill</td>
         <td class="module">MEI.cmnOrnaments</td>
         <td class="desc">Rapid alternation of a note with another (usually at the interval of a second above).</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.trill.anl</li>
               <li class="unchanged">att.trill.ges</li>
               <li class="unchanged">att.trill.log</li>
               <li class="unchanged">att.trill.vis</li>
               <li class="unchanged">model.ornamentLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">accidupper</span></li>
               <li class="unchanged"><span class="attribute">accidlower</span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">accidupper.ges</span></li>
               <li class="unchanged"><span class="attribute">accidlower.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/trill.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="turn">
         <td class="element ident">turn</td>
         <td class="module">MEI.cmnOrnaments</td>
         <td class="desc">An ornament consisting of four notes — the upper neighbor of the written note, the
            written note, the lower neighbor, and the written note.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.turn.anl</li>
               <li class="unchanged">att.turn.ges</li>
               <li class="unchanged">att.turn.log</li>
               <li class="unchanged">att.turn.vis</li>
               <li class="unchanged">model.ornamentLike.cmn</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">accidupper</span></li>
               <li class="unchanged"><span class="attribute">accidlower</span></li>
               <li class="unchanged"><span class="attribute">delayed</span></li>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">accidupper.ges</span></li>
               <li class="unchanged"><span class="attribute">accidlower.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/turn.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="meiCorpus">
         <td class="element ident">meiCorpus</td>
         <td class="module">MEI.corpus</td>
         <td class="desc">(MEI corpus) – A group of related MEI documents, consisting of a header for the group,
            and one or more mei elements, each with its own complete header.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.meiVersion</li>
               <li class="unchanged">model.startLike.corpus</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">meiHead</li>
               <li class="unchanged">mei</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/meiCorpus.html" target="_blank">meiversion</a></span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="cpMark">
         <td class="element ident">cpMark</td>
         <td class="module">MEI.edittrans</td>
         <td class="desc">(copy/colla parte mark) – A verbal or graphical indication to copy musical material
            written elsewhere.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.cpMark.log</li>
               <li class="unchanged">att.cpMark.vis</li>
               <li class="unchanged">att.cpMark.ges</li>
               <li class="unchanged">att.cpMark.anl</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">dis</span></li>
               <li class="unchanged"><span class="attribute">dis.place</span></li>
               <li class="unchanged"><span class="attribute">origin.layer</span></li>
               <li class="unchanged"><span class="attribute">origin.staff</span></li>
               <li class="unchanged"><span class="attribute">origin.startid</span></li>
               <li class="unchanged"><span class="attribute">origin.endid</span></li>
               <li class="unchanged"><span class="attribute">origin.tstamp</span></li>
               <li class="unchanged"><span class="attribute">origin.tstamp2</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/cpMark.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="metaMark">
         <td class="element ident">metaMark</td>
         <td class="module">MEI.edittrans</td>
         <td class="desc">A graphical or textual statement with additional / explanatory information about the
            musical text. The textual consequences of this intervention are encoded independently
            via other means; that is, with elements such as add , del , etc.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.metaMark.log</li>
               <li class="unchanged">att.metaMark.vis</li>
               <li class="unchanged">att.metaMark.ges</li>
               <li class="unchanged">att.metaMark.anl</li>
               <li class="unchanged">att.pointing</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.sectionLike</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">function</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">instant</span></li>
               <li class="unchanged"><span class="attribute">state</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/metaMark.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">decls</span></li>
               <li class="unchanged"><span class="attribute">cert</span></li>
               <li class="unchanged"><span class="attribute">evidence</span></li>
               <li class="unchanged"><span class="attribute">hand</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">xlink:actuate</span></li>
               <li class="unchanged"><span class="attribute">xlink:role</span></li>
               <li class="unchanged"><span class="attribute">xlink:show</span></li>
               <li class="unchanged"><span class="attribute">target</span></li>
               <li class="unchanged"><span class="attribute">targettype</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">seq</span></li>
               <li class="unchanged"><span class="attribute">source</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/metaMark.html" target="_blank">vgrp</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="surface">
         <td class="element ident">surface</td>
         <td class="module">MEI.facsimile</td>
         <td class="desc">Defines a writing surface in terms of a rectangular coordinate space, optionally grouping
            one or more graphic representations of that space, and rectangular zones of interest
            within it.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.coordinated</li>
               <li class="unchanged">att.dataPointing</li>
               <li class="unchanged">att.metadataPointing</li>
               <li class="unchanged">att.startId</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.figDescLike</li>
               <li class="unchanged">model.graphicLike</li>
               <li class="unchanged">zone</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">lrx</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/surface.html" target="_blank">lry</a></span></li>
               <li class="unchanged"><span class="attribute">rotate</span></li>
               <li class="unchanged"><span class="attribute">ulx</span></li>
               <li class="unchanged"><span class="attribute">uly</span></li>
               <li class="unchanged"><span class="attribute">data</span></li>
               <li class="unchanged"><span class="attribute">decls</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="zone">
         <td class="element ident">zone</td>
         <td class="module">MEI.facsimile</td>
         <td class="desc">Defines an area of interest within a surface or graphic file.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.coordinated</li>
               <li class="unchanged">att.dataPointing</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.figDescLike</li>
               <li class="unchanged">model.graphicLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">lrx</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/zone.html" target="_blank">lry</a></span></li>
               <li class="unchanged"><span class="attribute">rotate</span></li>
               <li class="unchanged"><span class="attribute">ulx</span></li>
               <li class="unchanged"><span class="attribute">uly</span></li>
               <li class="unchanged"><span class="attribute">data</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="fing">
         <td class="element ident">fing</td>
         <td class="module">MEI.fingering</td>
         <td class="desc">(finger) – An individual finger in a fingering indication.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.fing.anl</li>
               <li class="unchanged">att.fing.ges</li>
               <li class="unchanged">att.fing.log</li>
               <li class="unchanged">att.fing.vis</li>
               <li class="unchanged">model.fingeringLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/fing.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/fing.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="fingGrp">
         <td class="element ident">fingGrp</td>
         <td class="module">MEI.fingering</td>
         <td class="desc">(finger group) – A group of individual fingers in a fingering indication.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.fingGrp.anl</li>
               <li class="unchanged">att.fingGrp.ges</li>
               <li class="unchanged">att.fingGrp.log</li>
               <li class="unchanged">att.fingGrp.vis</li>
               <li class="unchanged">model.fingeringLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.fingeringLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/fingGrp.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/fingGrp.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
               <li class="unchanged"><span class="attribute">orient</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="chordDef">
         <td class="element ident">chordDef</td>
         <td class="module">MEI.harmony</td>
         <td class="desc">(chord definition) – Chord tablature definition.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.chordDef.anl</li>
               <li class="unchanged">att.chordDef.ges</li>
               <li class="unchanged">att.chordDef.log</li>
               <li class="unchanged">att.chordDef.vis</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">chordMember</li>
               <li class="unchanged">barre</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">tab.pos</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordDef.html" target="_blank">tab.strings</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordDef.html" target="_blank">tab.courses</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="chordMember">
         <td class="element ident">chordMember</td>
         <td class="module">MEI.harmony</td>
         <td class="desc">An individual pitch in a chord defined by a chordDef element.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.chordMember.anl</li>
               <li class="unchanged">att.chordMember.ges</li>
               <li class="unchanged">att.chordMember.log</li>
               <li class="unchanged">att.chordMember.vis</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">inth</span></li>
               <li class="unchanged"><span class="attribute">accid.ges</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">oct</span></li>
               <li class="unchanged"><span class="attribute">pname</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordMember.html" target="_blank">tab.fing</a></span></li>
               <li class="unchanged"><span class="attribute">tab.fret</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordMember.html" target="_blank">tab.line</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordMember.html" target="_blank">tab.string</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/chordMember.html" target="_blank">tab.course</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="f">
         <td class="element ident">f</td>
         <td class="module">MEI.harmony</td>
         <td class="desc">(figure) – Single element of a figured bass indication.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.f.anl</li>
               <li class="unchanged">att.f.ges</li>
               <li class="unchanged">att.f.log</li>
               <li class="unchanged">att.f.vis</li>
               <li class="unchanged">model.fLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/f.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="harm">
         <td class="element ident">harm</td>
         <td class="module">MEI.harmony</td>
         <td class="desc">(harmony) – An indication of harmony, e.g. , chord names, tablature grids, harmonic
            analysis, figured bass.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.harm.anl</li>
               <li class="unchanged">att.harm.ges</li>
               <li class="unchanged">att.harm.log</li>
               <li class="unchanged">att.harm.vis</li>
               <li class="unchanged">model.harmLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
               <li class="unchanged">model.figbassLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">inth</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">chordref</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harm.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/harm.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">rendgrid</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="meiHead">
         <td class="element ident">meiHead</td>
         <td class="module">MEI.header</td>
         <td class="desc">(MEI header) – Supplies the descriptive and declarative metadata prefixed to every
            MEI-conformant text.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.basic</li>
               <li class="unchanged">att.bibl</li>
               <li class="unchanged">att.labelled</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.meiVersion</li>
               <li class="unchanged">att.responsibility</li>
               <li class="unchanged">model.startLike.header</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">altId</li>
               <li class="unchanged">fileDesc</li>
               <li class="unchanged">encodingDesc</li>
               <li class="unchanged">workList</li>
               <li class="unchanged">manifestationList</li>
               <li class="unchanged">extMeta</li>
               <li class="unchanged">revisionDesc</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">analog</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/meiHead.html" target="_blank">meiversion</a></span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="instrDef">
         <td class="element ident">instrDef</td>
         <td class="module">MEI.midi</td>
         <td class="desc">(instrument definition) – MIDI instrument declaration.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.basic</li>
               <li class="unchanged">att.labelled</li>
               <li class="unchanged">att.linking</li>
               <li class="unchanged">att.metadataPointing</li>
               <li class="unchanged">att.nInteger</li>
               <li class="unchanged">att.responsibility</li>
               <li class="unchanged">att.typed</li>
               <li class="unchanged">att.instrDef.anl</li>
               <li class="unchanged">att.instrDef.ges</li>
               <li class="unchanged">att.instrDef.log</li>
               <li class="unchanged">att.instrDef.vis</li>
               <li class="unchanged">model.instrDefLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">azimuth</span></li>
               <li class="unchanged"><span class="attribute">elevation</span></li>
               <li class="unchanged"><span class="attribute">midi.channel</span></li>
               <li class="unchanged"><span class="attribute">midi.duty</span></li>
               <li class="unchanged"><span class="attribute">midi.port</span></li>
               <li class="unchanged"><span class="attribute">midi.track</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/instrDef.html" target="_blank">midi.instrnum</a></span></li>
               <li class="unchanged"><span class="attribute">midi.instrname</span></li>
               <li class="unchanged"><span class="attribute">midi.pan</span></li>
               <li class="unchanged"><span class="attribute">midi.patchname</span></li>
               <li class="unchanged"><span class="attribute">midi.patchnum</span></li>
               <li class="unchanged"><span class="attribute">midi.volume</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">decls</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="caesura">
         <td class="element ident">caesura</td>
         <td class="module">MEI.shared</td>
         <td class="desc">Break, pause, or interruption in the normal tempo of a composition. Typically indicated
            by "railroad tracks", i.e. , two diagonal slashes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.caesura.anl</li>
               <li class="unchanged">att.caesura.ges</li>
               <li class="unchanged">att.caesura.log</li>
               <li class="unchanged">att.caesura.vis</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">loc</span></li>
               <li class="unchanged"><span class="attribute">ploc</span></li>
               <li class="unchanged"><span class="attribute">oloc</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/caesura.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="dir">
         <td class="element ident">dir</td>
         <td class="module">MEI.shared</td>
         <td class="desc">(directive) – An instruction expressed as a combination of text and symbols, typically
            above, below, or between staves, but not on the staff — that is not encoded elsewhere
            in more specific elements, like tempo , dynam or repeatMark .</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.dir.anl</li>
               <li class="unchanged">att.dir.ges</li>
               <li class="unchanged">att.dir.log</li>
               <li class="unchanged">att.dir.vis</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/dir.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">vgrp</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="dynam">
         <td class="element ident">dynam</td>
         <td class="module">MEI.shared</td>
         <td class="desc">(dynamic) – Indication of the volume of a note, phrase, or section of music.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.dynam.anl</li>
               <li class="unchanged">att.dynam.ges</li>
               <li class="unchanged">att.dynam.log</li>
               <li class="unchanged">att.dynam.vis</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">val</span></li>
               <li class="unchanged"><span class="attribute">val2</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/dynam.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">vgrp</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="mei">
         <td class="element ident">mei</td>
         <td class="module">MEI.shared</td>
         <td class="desc">Contains a single MEI-conformant document, consisting of an MEI header and a musical
            text, either in isolation or as part of an meiCorpus element.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.id</li>
               <li class="unchanged">att.meiVersion</li>
               <li class="unchanged">att.responsibility</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">meiHead</li>
               <li class="unchanged">music</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/mei.html" target="_blank">meiversion</a></span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="music">
         <td class="element ident">music</td>
         <td class="module">MEI.shared</td>
         <td class="desc">Contains a single musical text of any kind, whether unitary or composite, for example,
            an etude, opera, song cycle, symphony, or anthology of piano solos.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.meiVersion</li>
               <li class="unchanged">att.metadataPointing</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.resourceLike</li>
               <li class="unchanged">macro.musicPart</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">decls</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/music.html" target="_blank">meiversion</a></span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="note">
         <td class="element ident">note</td>
         <td class="module">MEI.shared</td>
         <td class="desc">A single pitched event.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.note.anl</li>
               <li class="unchanged">att.note.ges</li>
               <li class="unchanged">att.note.log</li>
               <li class="unchanged">att.note.vis</li>
               <li class="unchanged">model.chordPart</li>
               <li class="unchanged">model.eventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.noteModifierLike</li>
               <li class="unchanged">model.verseLike</li>
               <li class="unchanged">model.sylLike</li>
               <li class="unchanged">model.appLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
               <li class="unchanged">plica</li>
               <li class="unchanged">stem</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">deg</span></li>
               <li class="unchanged"><span class="attribute">intm</span></li>
               <li class="unchanged"><span class="attribute">mfunc</span></li>
               <li class="unchanged"><span class="attribute">pclass</span></li>
               <li class="unchanged"><span class="attribute">psolfa</span></li>
               <li class="unchanged"><span class="attribute">beam</span></li>
               <li class="unchanged"><span class="attribute">breaksec</span></li>
               <li class="unchanged"><span class="attribute">gliss</span></li>
               <li class="unchanged"><span class="attribute">grace</span></li>
               <li class="unchanged"><span class="attribute">grace.time</span></li>
               <li class="unchanged"><span class="attribute">lv</span></li>
               <li class="unchanged"><span class="attribute">stem.with</span></li>
               <li class="unchanged"><span class="attribute">ornam</span></li>
               <li class="unchanged"><span class="attribute">glyph.auth</span></li>
               <li class="unchanged"><span class="attribute">glyph.uri</span></li>
               <li class="unchanged"><span class="attribute">glyph.name</span></li>
               <li class="unchanged"><span class="attribute">glyph.num</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">accid.ges</span></li>
               <li class="unchanged"><span class="attribute">artic.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">extremis</span></li>
               <li class="unchanged"><span class="attribute">oct.ges</span></li>
               <li class="unchanged"><span class="attribute">pname.ges</span></li>
               <li class="unchanged"><span class="attribute">pnum</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">dur.quality</span></li>
               <li class="unchanged"><span class="attribute">lig</span></li>
               <li class="unchanged"><span class="attribute">stem.form</span></li>
               <li class="unchanged"><span class="attribute">instr</span></li>
               <li class="unchanged"><span class="attribute">vel</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">accid</span></li>
               <li class="unchanged"><span class="attribute">artic</span></li>
               <li class="unchanged"><span class="attribute">dots</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">colored</span></li>
               <li class="unchanged"><span class="attribute">cue</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">num</span></li>
               <li class="unchanged"><span class="attribute">numbase</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">fermata</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">head.altsym</span></li>
               <li class="unchanged"><span class="attribute">head.auth</span></li>
               <li class="unchanged"><span class="attribute">head.color</span></li>
               <li class="unchanged"><span class="attribute">head.fill</span></li>
               <li class="unchanged"><span class="attribute">head.fillcolor</span></li>
               <li class="unchanged"><span class="attribute">head.mod</span></li>
               <li class="unchanged"><span class="attribute">head.rotation</span></li>
               <li class="unchanged"><span class="attribute">head.shape</span></li>
               <li class="unchanged"><span class="attribute">head.visible</span></li>
               <li class="unchanged"><span class="attribute">oct</span></li>
               <li class="unchanged"><span class="attribute">pname</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">slur</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">loc</span></li>
               <li class="unchanged"><span class="attribute">stem.dir</span></li>
               <li class="unchanged"><span class="attribute">stem.len</span></li>
               <li class="unchanged"><span class="attribute">stem.mod</span></li>
               <li class="unchanged"><span class="attribute">stem.pos</span></li>
               <li class="unchanged"><span class="attribute">stem.sameas</span></li>
               <li class="unchanged"><span class="attribute">stem.visible</span></li>
               <li class="unchanged"><span class="attribute">stem.x</span></li>
               <li class="unchanged"><span class="attribute">stem.y</span></li>
               <li class="unchanged"><span class="attribute">syl</span></li>
               <li class="unchanged"><span class="attribute">tie</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tuplet</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">fontfam</span></li>
               <li class="unchanged"><span class="attribute">fontname</span></li>
               <li class="unchanged"><span class="attribute">fontsize</span></li>
               <li class="unchanged"><span class="attribute">fontstyle</span></li>
               <li class="unchanged"><span class="attribute">fontweight</span></li>
               <li class="unchanged"><span class="attribute">letterspacing</span></li>
               <li class="unchanged"><span class="attribute">lineheight</span></li>
               <li class="unchanged"><span class="attribute">visible</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/note.html" target="_blank">tab.fing</a></span></li>
               <li class="unchanged"><span class="attribute">tab.fret</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/note.html" target="_blank">tab.line</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/note.html" target="_blank">tab.string</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/note.html" target="_blank">tab.course</a></span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="ornam">
         <td class="element ident">ornam</td>
         <td class="module">MEI.shared</td>
         <td class="desc">An element indicating an ornament that is not a mordent, turn, or trill.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.ornam.anl</li>
               <li class="unchanged">att.ornam.ges</li>
               <li class="unchanged">att.ornam.log</li>
               <li class="unchanged">att.ornam.vis</li>
               <li class="unchanged">model.controlEventLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">accidupper</span></li>
               <li class="unchanged"><span class="attribute">accidlower</span></li>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">dur.ges</span></li>
               <li class="unchanged"><span class="attribute">dots.ges</span></li>
               <li class="unchanged"><span class="attribute">dur.metrical</span></li>
               <li class="unchanged"><span class="attribute">dur.ppq</span></li>
               <li class="unchanged"><span class="attribute">dur.real</span></li>
               <li class="unchanged"><span class="attribute">dur.recip</span></li>
               <li class="unchanged"><span class="attribute">accidupper.ges</span></li>
               <li class="unchanged"><span class="attribute">accidlower.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp2.real</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">color</span></li>
               <li class="unchanged"><span class="attribute">dur</span></li>
               <li class="unchanged"><span class="attribute">enclose</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/ornam.html" target="_blank">vgrp</a></span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
               <li class="unchanged"><span class="attribute">altsym</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="scoreDef">
         <td class="element ident">scoreDef</td>
         <td class="module">MEI.shared</td>
         <td class="desc">(score definition) – Container for score meta-information.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.scoreDef.anl</li>
               <li class="unchanged">att.scoreDef.ges</li>
               <li class="unchanged">att.scoreDef.log</li>
               <li class="unchanged">att.scoreDef.vis</li>
               <li class="unchanged">model.scoreDefLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.chordTableLike</li>
               <li class="unchanged">model.symbolTableLike</li>
               <li class="unchanged">model.keySigLike</li>
               <li class="unchanged">model.meterSigLike</li>
               <li class="unchanged">pgHead</li>
               <li class="unchanged">pgFoot</li>
               <li class="unchanged">instrGrp</li>
               <li class="unchanged">model.staffGrpLike</li>
               <li class="unchanged">grpSym</li>
               <li class="unchanged">ambitus</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">key.accid</span></li>
               <li class="unchanged"><span class="attribute">key.mode</span></li>
               <li class="unchanged"><span class="attribute">key.pname</span></li>
               <li class="unchanged"><span class="attribute">beam.group</span></li>
               <li class="unchanged"><span class="attribute">beam.rests</span></li>
               <li class="unchanged"><span class="attribute">pedal.style</span></li>
               <li class="unchanged"><span class="attribute">reh.enclose</span></li>
               <li class="unchanged"><span class="attribute">slur.lform</span></li>
               <li class="unchanged"><span class="attribute">slur.lwidth</span></li>
               <li class="unchanged"><span class="attribute">tie.lform</span></li>
               <li class="unchanged"><span class="attribute">tie.lwidth</span></li>
               <li class="unchanged"><span class="attribute">proport.num</span></li>
               <li class="unchanged"><span class="attribute">proport.numbase</span></li>
               <li class="unchanged"><span class="attribute">modusmaior</span></li>
               <li class="unchanged"><span class="attribute">modusminor</span></li>
               <li class="unchanged"><span class="attribute">prolatio</span></li>
               <li class="unchanged"><span class="attribute">tempus</span></li>
               <li class="unchanged"><span class="attribute">divisio</span></li>
               <li class="unchanged"><span class="attribute">midi.channel</span></li>
               <li class="unchanged"><span class="attribute">midi.duty</span></li>
               <li class="unchanged"><span class="attribute">midi.port</span></li>
               <li class="unchanged"><span class="attribute">midi.track</span></li>
               <li class="unchanged"><span class="attribute">midi.bpm</span></li>
               <li class="unchanged"><span class="attribute">midi.mspb</span></li>
               <li class="unchanged"><span class="attribute">ppq</span></li>
               <li class="unchanged"><span class="attribute">bar.len</span></li>
               <li class="unchanged"><span class="attribute">bar.method</span></li>
               <li class="unchanged"><span class="attribute">bar.place</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">clef.shape</span></li>
               <li class="unchanged"><span class="attribute">clef.line</span></li>
               <li class="unchanged"><span class="attribute">clef.dis</span></li>
               <li class="unchanged"><span class="attribute">clef.dis.place</span></li>
               <li class="unchanged"><span class="attribute">dir.dist</span></li>
               <li class="unchanged"><span class="attribute">dynam.dist</span></li>
               <li class="unchanged"><span class="attribute">harm.dist</span></li>
               <li class="unchanged"><span class="attribute">reh.dist</span></li>
               <li class="unchanged"><span class="attribute">tempo.dist</span></li>
               <li class="unchanged"><span class="attribute">dur.default</span></li>
               <li class="unchanged"><span class="attribute">num.default</span></li>
               <li class="unchanged"><span class="attribute">numbase.default</span></li>
               <li class="unchanged"><span class="attribute">ending.rend</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">keysig</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">lyric.align</span></li>
               <li class="unchanged"><span class="attribute">lyric.fam</span></li>
               <li class="unchanged"><span class="attribute">lyric.name</span></li>
               <li class="unchanged"><span class="attribute">lyric.size</span></li>
               <li class="unchanged"><span class="attribute">lyric.style</span></li>
               <li class="unchanged"><span class="attribute">lyric.weight</span></li>
               <li class="unchanged"><span class="attribute">mnum.visible</span></li>
               <li class="unchanged"><span class="attribute">meter.count</span></li>
               <li class="unchanged"><span class="attribute">meter.unit</span></li>
               <li class="unchanged"><span class="attribute">meter.sym</span></li>
               <li class="unchanged"><span class="attribute">mm</span></li>
               <li class="unchanged"><span class="attribute">mm.unit</span></li>
               <li class="unchanged"><span class="attribute">mm.dots</span></li>
               <li class="unchanged"><span class="attribute">multi.number</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">music.name</span></li>
               <li class="unchanged"><span class="attribute">music.size</span></li>
               <li class="unchanged"><span class="attribute">oct.default</span></li>
               <li class="unchanged"><span class="attribute">ontheline</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/scoreDef.html" target="_blank">optimize</a></span></li>
               <li class="unchanged"><span class="attribute">page.height</span></li>
               <li class="unchanged"><span class="attribute">page.width</span></li>
               <li class="unchanged"><span class="attribute">page.topmar</span></li>
               <li class="unchanged"><span class="attribute">page.botmar</span></li>
               <li class="unchanged"><span class="attribute">page.leftmar</span></li>
               <li class="unchanged"><span class="attribute">page.rightmar</span></li>
               <li class="unchanged"><span class="attribute">page.panels</span></li>
               <li class="unchanged"><span class="attribute">page.scale</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">spacing.packexp</span></li>
               <li class="unchanged"><span class="attribute">spacing.packfact</span></li>
               <li class="unchanged"><span class="attribute">spacing.staff</span></li>
               <li class="unchanged"><span class="attribute">spacing.system</span></li>
               <li class="unchanged"><span class="attribute">aboveorder</span></li>
               <li class="unchanged"><span class="attribute">beloworder</span></li>
               <li class="unchanged"><span class="attribute">betweenorder</span></li>
               <li class="unchanged"><span class="attribute">system.leftline</span></li>
               <li class="unchanged"><span class="attribute">system.leftmar</span></li>
               <li class="unchanged"><span class="attribute">system.rightmar</span></li>
               <li class="unchanged"><span class="attribute">system.topmar</span></li>
               <li class="unchanged"><span class="attribute">text.fam</span></li>
               <li class="unchanged"><span class="attribute">text.name</span></li>
               <li class="unchanged"><span class="attribute">text.size</span></li>
               <li class="unchanged"><span class="attribute">text.style</span></li>
               <li class="unchanged"><span class="attribute">text.weight</span></li>
               <li class="unchanged"><span class="attribute">trans.diat</span></li>
               <li class="unchanged"><span class="attribute">trans.semi</span></li>
               <li class="unchanged"><span class="attribute">tune.Hz</span></li>
               <li class="unchanged"><span class="attribute">tune.pname</span></li>
               <li class="unchanged"><span class="attribute">tune.temper</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">beam.color</span></li>
               <li class="unchanged"><span class="attribute">beam.rend</span></li>
               <li class="unchanged"><span class="attribute">beam.slope</span></li>
               <li class="unchanged"><span class="attribute">clef.color</span></li>
               <li class="unchanged"><span class="attribute">clef.visible</span></li>
               <li class="unchanged"><span class="attribute">grid.show</span></li>
               <li class="unchanged"><span class="attribute">keysig.cancelaccid</span></li>
               <li class="unchanged"><span class="attribute">keysig.visible</span></li>
               <li class="unchanged"><span class="attribute">mensur.color</span></li>
               <li class="unchanged"><span class="attribute">mensur.dot</span></li>
               <li class="unchanged"><span class="attribute">mensur.form</span></li>
               <li class="unchanged"><span class="attribute">mensur.loc</span></li>
               <li class="unchanged"><span class="attribute">mensur.orient</span></li>
               <li class="unchanged"><span class="attribute">mensur.sign</span></li>
               <li class="unchanged"><span class="attribute">mensur.size</span></li>
               <li class="unchanged"><span class="attribute">mensur.slash</span></li>
               <li class="unchanged"><span class="attribute">meter.form</span></li>
               <li class="unchanged"><span class="attribute">meter.showchange</span></li>
               <li class="unchanged"><span class="attribute">meter.visible</span></li>
               <li class="unchanged"><span class="attribute">vu.height</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="staffDef">
         <td class="element ident">staffDef</td>
         <td class="module">MEI.shared</td>
         <td class="desc">(staff definition) – Container for staff meta-information.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.basic</li>
               <li class="unchanged">att.labelled</li>
               <li class="unchanged">att.linking</li>
               <li class="unchanged">att.metadataPointing</li>
               <li class="unchanged">att.nInteger</li>
               <li class="unchanged">att.responsibility</li>
               <li class="unchanged">att.typed</li>
               <li class="unchanged">att.staffDef.anl</li>
               <li class="unchanged">att.staffDef.ges</li>
               <li class="unchanged">att.staffDef.log</li>
               <li class="unchanged">att.staffDef.vis</li>
               <li class="unchanged">model.staffDefLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">model.labelLike</li>
               <li class="unchanged">model.instrDefLike</li>
               <li class="unchanged">model.layerDefLike</li>
               <li class="unchanged">model.staffDefPart</li>
               <li class="unchanged">ambitus</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">notationtype</span></li>
               <li class="unchanged"><span class="attribute">notationsubtype</span></li>
               <li class="unchanged"><span class="attribute">key.accid</span></li>
               <li class="unchanged"><span class="attribute">key.mode</span></li>
               <li class="unchanged"><span class="attribute">key.pname</span></li>
               <li class="unchanged"><span class="attribute">beam.group</span></li>
               <li class="unchanged"><span class="attribute">beam.rests</span></li>
               <li class="unchanged"><span class="attribute">pedal.style</span></li>
               <li class="unchanged"><span class="attribute">reh.enclose</span></li>
               <li class="unchanged"><span class="attribute">slur.lform</span></li>
               <li class="unchanged"><span class="attribute">slur.lwidth</span></li>
               <li class="unchanged"><span class="attribute">tie.lform</span></li>
               <li class="unchanged"><span class="attribute">tie.lwidth</span></li>
               <li class="unchanged"><span class="attribute">proport.num</span></li>
               <li class="unchanged"><span class="attribute">proport.numbase</span></li>
               <li class="unchanged"><span class="attribute">modusmaior</span></li>
               <li class="unchanged"><span class="attribute">modusminor</span></li>
               <li class="unchanged"><span class="attribute">prolatio</span></li>
               <li class="unchanged"><span class="attribute">tempus</span></li>
               <li class="unchanged"><span class="attribute">divisio</span></li>
               <li class="unchanged"><span class="attribute">instr</span></li>
               <li class="unchanged"><span class="attribute">ppq</span></li>
               <li class="unchanged"><span class="attribute">bar.len</span></li>
               <li class="unchanged"><span class="attribute">bar.method</span></li>
               <li class="unchanged"><span class="attribute">bar.place</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">clef.shape</span></li>
               <li class="unchanged"><span class="attribute">clef.line</span></li>
               <li class="unchanged"><span class="attribute">clef.dis</span></li>
               <li class="unchanged"><span class="attribute">clef.dis.place</span></li>
               <li class="unchanged"><span class="attribute">decls</span></li>
               <li class="unchanged"><span class="attribute">dir.dist</span></li>
               <li class="unchanged"><span class="attribute">dynam.dist</span></li>
               <li class="unchanged"><span class="attribute">harm.dist</span></li>
               <li class="unchanged"><span class="attribute">reh.dist</span></li>
               <li class="unchanged"><span class="attribute">tempo.dist</span></li>
               <li class="unchanged"><span class="attribute">dur.default</span></li>
               <li class="unchanged"><span class="attribute">num.default</span></li>
               <li class="unchanged"><span class="attribute">numbase.default</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">keysig</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">lyric.align</span></li>
               <li class="unchanged"><span class="attribute">lyric.fam</span></li>
               <li class="unchanged"><span class="attribute">lyric.name</span></li>
               <li class="unchanged"><span class="attribute">lyric.size</span></li>
               <li class="unchanged"><span class="attribute">lyric.style</span></li>
               <li class="unchanged"><span class="attribute">lyric.weight</span></li>
               <li class="unchanged"><span class="attribute">meter.count</span></li>
               <li class="unchanged"><span class="attribute">meter.unit</span></li>
               <li class="unchanged"><span class="attribute">meter.sym</span></li>
               <li class="unchanged"><span class="attribute">multi.number</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">music.name</span></li>
               <li class="unchanged"><span class="attribute">music.size</span></li>
               <li class="unchanged"><span class="attribute">oct.default</span></li>
               <li class="unchanged"><span class="attribute">ontheline</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">scale</span></li>
               <li class="unchanged"><span class="attribute">lines</span></li>
               <li class="unchanged"><span class="attribute">aboveorder</span></li>
               <li class="unchanged"><span class="attribute">beloworder</span></li>
               <li class="unchanged"><span class="attribute">betweenorder</span></li>
               <li class="unchanged"><span class="attribute">text.fam</span></li>
               <li class="unchanged"><span class="attribute">text.name</span></li>
               <li class="unchanged"><span class="attribute">text.size</span></li>
               <li class="unchanged"><span class="attribute">text.style</span></li>
               <li class="unchanged"><span class="attribute">text.weight</span></li>
               <li class="unchanged"><span class="attribute">trans.diat</span></li>
               <li class="unchanged"><span class="attribute">trans.semi</span></li>
               <li class="unchanged"><span class="attribute">tune.Hz</span></li>
               <li class="unchanged"><span class="attribute">tune.pname</span></li>
               <li class="unchanged"><span class="attribute">tune.temper</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">visible</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/staffDef.html" target="_blank">tab.align</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/staffDef.html" target="_blank">tab.anchorline</a></span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/staffDef.html" target="_blank">tab.strings</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/staffDef.html" target="_blank">tab.courses</a></span></li>
               <li class="unchanged"><span class="attribute">beam.color</span></li>
               <li class="unchanged"><span class="attribute">beam.rend</span></li>
               <li class="unchanged"><span class="attribute">beam.slope</span></li>
               <li class="unchanged"><span class="attribute">clef.color</span></li>
               <li class="unchanged"><span class="attribute">clef.visible</span></li>
               <li class="unchanged"><span class="attribute">grid.show</span></li>
               <li class="unchanged"><span class="attribute">keysig.cancelaccid</span></li>
               <li class="unchanged"><span class="attribute">keysig.visible</span></li>
               <li class="unchanged"><span class="attribute">mensur.color</span></li>
               <li class="unchanged"><span class="attribute">mensur.dot</span></li>
               <li class="unchanged"><span class="attribute">mensur.form</span></li>
               <li class="unchanged"><span class="attribute">mensur.loc</span></li>
               <li class="unchanged"><span class="attribute">mensur.orient</span></li>
               <li class="unchanged"><span class="attribute">mensur.sign</span></li>
               <li class="unchanged"><span class="attribute">mensur.size</span></li>
               <li class="unchanged"><span class="attribute">mensur.slash</span></li>
               <li class="unchanged"><span class="attribute">meter.form</span></li>
               <li class="unchanged"><span class="attribute">meter.showchange</span></li>
               <li class="unchanged"><span class="attribute">meter.visible</span></li>
               <li class="unchanged"><span class="attribute">layerscheme</span></li>
               <li class="unchanged"><span class="attribute">lines.color</span></li>
               <li class="unchanged"><span class="attribute">lines.visible</span></li>
               <li class="unchanged"><span class="attribute">spacing</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="tempo">
         <td class="element ident">tempo</td>
         <td class="module">MEI.shared</td>
         <td class="desc">Text and symbols descriptive of tempo, mood, or style, e.g. , "allarg.", "a tempo",
            "cantabile", "Moderato", "♩=60", "Moderato ♩ =60").</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.bibl</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.tempo.anl</li>
               <li class="unchanged">att.tempo.ges</li>
               <li class="unchanged">att.tempo.log</li>
               <li class="unchanged">att.tempo.vis</li>
               <li class="unchanged">model.controlEventLike</li>
               <li class="unchanged">model.workIdent</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike.limited</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">model.editLike</li>
               <li class="unchanged">model.transcriptionLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">tstamp.ges</span></li>
               <li class="unchanged"><span class="attribute">tstamp.real</span></li>
               <li class="unchanged"><span class="attribute">midi.bpm</span></li>
               <li class="unchanged"><span class="attribute">midi.mspb</span></li>
               <li class="unchanged"><span class="attribute">when</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">analog</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/tempo.html" target="_blank">color</a></span></li>
               <li class="unchanged"><span class="attribute">extender</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">layer</span></li>
               <li class="unchanged"><span class="attribute">lendsym</span></li>
               <li class="unchanged"><span class="attribute">lendsym.size</span></li>
               <li class="unchanged"><span class="attribute">lstartsym</span></li>
               <li class="unchanged"><span class="attribute">lstartsym.size</span></li>
               <li class="unchanged"><span class="attribute">lform</span></li>
               <li class="unchanged"><span class="attribute">lwidth</span></li>
               <li class="unchanged"><span class="attribute">lsegs</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">mm</span></li>
               <li class="unchanged"><span class="attribute">mm.unit</span></li>
               <li class="unchanged"><span class="attribute">mm.dots</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">part</span></li>
               <li class="unchanged"><span class="attribute">partstaff</span></li>
               <li class="unchanged"><span class="attribute">place</span></li>
               <li class="unchanged"><span class="attribute">plist</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">staff</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">evaluate</span></li>
               <li class="unchanged"><span class="attribute">func</span></li>
               <li class="unchanged"><span class="attribute">tstamp</span></li>
               <li class="unchanged"><span class="attribute">tstamp2</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">vgrp</span></li>
               <li class="unchanged"><span class="attribute">ho</span></li>
               <li class="unchanged"><span class="attribute">to</span></li>
               <li class="unchanged"><span class="attribute">vo</span></li>
               <li class="unchanged"><span class="attribute">startho</span></li>
               <li class="unchanged"><span class="attribute">endho</span></li>
               <li class="unchanged"><span class="attribute">startto</span></li>
               <li class="unchanged"><span class="attribute">endto</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="barre">
         <td class="element ident">barre</td>
         <td class="module">MEI.stringtab</td>
         <td class="desc">A barre in a chord tablature grid.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.startEndId</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">empty</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">endid</span></li>
               <li class="unchanged"><span class="attribute">startid</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/barre.html" target="_blank">fret</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="q">
         <td class="element ident">q</td>
         <td class="module">MEI.text</td>
         <td class="desc">(quoted) – Contains material which is distinguished from the surrounding phrase-level
            text using quotation marks or a similar method. Use quote for block-level quotations.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.basic</li>
               <li class="unchanged">att.classed</li>
               <li class="unchanged">att.labelled</li>
               <li class="unchanged">att.lang</li>
               <li class="unchanged">att.linking</li>
               <li class="unchanged">att.nNumberLike</li>
               <li class="unchanged">att.responsibility</li>
               <li class="added" title="added class"><a href="#att.textRendition">att.textRendition</a></li>
               <li class="unchanged">model.qLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.textPhraseLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/q.html" target="_blank">altrend</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/q.html" target="_blank">rend</a></span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="quote">
         <td class="element ident">quote</td>
         <td class="module">MEI.text</td>
         <td class="desc">(quoted material) – Contains a paragraph-like block of text attributed to an external
            source, normally set off from the surrounding text by spacing or other typographic
            distinction.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.facsimile</li>
               <li class="unchanged">att.lang</li>
               <li class="added" title="added class"><a href="#att.textRendition">att.textRendition</a></li>
               <li class="unchanged">att.xy</li>
               <li class="unchanged">model.quoteLike</li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">text</li>
               <li class="unchanged">model.paracontentPart</li>
               <li class="unchanged">model.pLike</li>
               <li class="unchanged">sp</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">facs</span></li>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">xml:lang</span></li>
               <li class="unchanged"><span class="attribute">translit</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/quote.html" target="_blank">altrend</a></span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/quote.html" target="_blank">rend</a></span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
               <li class="unchanged"><span class="attribute">x</span></li>
               <li class="unchanged"><span class="attribute">y</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="symbolDef">
         <td class="element ident">symbolDef</td>
         <td class="module">MEI.usersymbols</td>
         <td class="desc">(symbol definition) – Declaration of an individual symbol in a symbolTable.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.common</li>
               <li class="unchanged">att.coordinated</li>
               <li class="added" title="added class"><a href="#att.dataSelecting">att.dataSelecting</a></li>
            </ul>
         </td>
         <td class="content">Content:<br><ul>
               <li class="unchanged">symName</li>
               <li class="unchanged">symProp</li>
               <li class="unchanged">mapping</li>
               <li class="unchanged">svg_svg</li>
               <li class="unchanged">model.graphicPrimitiveLike</li>
               <li class="unchanged">symbol</li>
               <li class="unchanged">graphic</li>
               <li class="unchanged">model.annotLike</li>
            </ul>
         </td>
         <td class="atts">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">xml:base</span></li>
               <li class="unchanged"><span class="attribute">class</span></li>
               <li class="unchanged"><span class="attribute">lrx</span></li>
               <li class="changed" title="changed attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/symbolDef.html" target="_blank">lry</a></span></li>
               <li class="unchanged"><span class="attribute">rotate</span></li>
               <li class="unchanged"><span class="attribute">ulx</span></li>
               <li class="unchanged"><span class="attribute">uly</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/elements/symbolDef.html" target="_blank">select</a></span></li>
               <li class="unchanged"><span class="attribute">xml:id</span></li>
               <li class="unchanged"><span class="attribute">label</span></li>
               <li class="unchanged"><span class="attribute">copyof</span></li>
               <li class="unchanged"><span class="attribute">corresp</span></li>
               <li class="unchanged"><span class="attribute">follows</span></li>
               <li class="unchanged"><span class="attribute">next</span></li>
               <li class="unchanged"><span class="attribute">precedes</span></li>
               <li class="unchanged"><span class="attribute">prev</span></li>
               <li class="unchanged"><span class="attribute">sameas</span></li>
               <li class="unchanged"><span class="attribute">synch</span></li>
               <li class="unchanged"><span class="attribute">n</span></li>
               <li class="unchanged"><span class="attribute">resp</span></li>
               <li class="unchanged"><span class="attribute">type</span></li>
            </ul>
         </td>
      </tr>
   </table>
   <h3 id="elementsUnchanged">374 unchanged elements:</h3>
   <table>
      <tr class="u">
         <td class="element ident">arpeg</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Indicates that the notes of a chord are to be performed successively
            rather than simultaneously, usually from lowest to highest. Sometimes called a "roll".</td>
      </tr>
      <tr class="u">
         <td class="element ident">beatRpt</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">An indication that material on a preceding beat should be repeated.</td>
      </tr>
      <tr class="u">
         <td class="element ident">bTrem</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A rapid alternation on a single pitch or chord.</td>
      </tr>
      <tr class="u">
         <td class="element ident">fTrem</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A rapid alternation between a pair of notes (or chords or perhaps
            between a note and a chord) that are (usually) farther apart than a major second.</td>
      </tr>
      <tr class="u">
         <td class="element ident">gliss</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A continuous or sliding movement from one pitch to another, usually
            indicated by a straight or wavy line.</td>
      </tr>
      <tr class="u">
         <td class="element ident">graceGrp</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A container for a sequence of grace notes.</td>
      </tr>
      <tr class="u">
         <td class="element ident">hairpin</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Indicates continuous dynamics expressed on the score as wedge-shaped graphics,  e.g.
            , &lt;
            and &gt;.</td>
      </tr>
      <tr class="u">
         <td class="element ident">lv</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A "tie-like" indication that a note should ring beyond its written duration.</td>
      </tr>
      <tr class="u">
         <td class="element ident">measure</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Unit of musical time consisting of a fixed number of note values of a given type,
            as
            determined by the prevailing meter, and delimited in musical notation by bar lines.</td>
      </tr>
      <tr class="u">
         <td class="element ident">meterSig</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Written meter signature.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mNum</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Designation, name, or label for a measure, often but not always
            consisting of digits. Use this element when the  n  attribute on  measure  does not
            adequately capture the appearance or placement of the measure
            number/label.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mRest</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Complete measure rest in any meter.   </td>
      </tr>
      <tr class="u">
         <td class="element ident">mRpt</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">An indication that the previous measure should be repeated.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mRpt2</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">An indication that the previous two measures should be
            repeated.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mSpace</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A measure containing only empty space in any meter.</td>
      </tr>
      <tr class="u">
         <td class="element ident">multiRest</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Multiple full measure rests compressed into a single bar, 
            frequently found in performer parts.</td>
      </tr>
      <tr class="u">
         <td class="element ident">multiRpt</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Multiple repeated measures.</td>
      </tr>
      <tr class="u">
         <td class="element ident">oLayer</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A layer that contains an alternative to material in another layer.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ossia</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Captures original notation and a differently notated version  *present in
            the source being transcribed* .</td>
      </tr>
      <tr class="u">
         <td class="element ident">oStaff</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A staff that holds an alternative passage which may be played instead of
            the original material.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pedal</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Piano pedal mark.</td>
      </tr>
      <tr class="u">
         <td class="element ident">reh</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">In an orchestral score and its corresponding parts, a mark indicating a
            convenient point from which to resume rehearsal after a break.</td>
      </tr>
      <tr class="u">
         <td class="element ident">slur</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Indication of 1) a "unified melodic idea" or 2) performance technique.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tie</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">An indication that two notes of the same pitch form a single note with their combined
            rhythmic values.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tuplet</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">A group of notes with "irregular" (sometimes called "irrational") rhythmic values,
            for
            example, three notes in the time normally occupied by two or nine in the time of five.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tupletSpan</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Alternative element for encoding tuplets, especially useful for tuplets
            that extend across bar lines.</td>
      </tr>
      <tr class="u">
         <td class="element ident">app</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Contains one or more alternative encodings.</td>
      </tr>
      <tr class="u">
         <td class="element ident">lem</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Contains the lemma, or base text, of a textual variation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">rdg</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Contains a single reading within a textual variation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sp</td>
         <td class="module unchanged">MEI.drama</td>
         <td class="unchanged">Contains an individual speech in a performance text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">stageDir</td>
         <td class="module unchanged">MEI.drama</td>
         <td class="unchanged">Contains any kind of stage direction within a dramatic text or
            fragment.</td>
      </tr>
      <tr class="u">
         <td class="element ident">abbr</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">A generic element for 1) a shortened form of a word, including an acronym
            or 2) a shorthand notation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">add</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Marks an addition to the text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">choice</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups a number of alternative encodings for the same point in a text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">corr</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains the correct form of an apparent erroneous passage.</td>
      </tr>
      <tr class="u">
         <td class="element ident">damage</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains an area of damage to the physical medium.</td>
      </tr>
      <tr class="u">
         <td class="element ident">del</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains information deleted, marked as deleted, or otherwise indicated as
            superfluous or spurious in the copy text by an author, scribe, annotator, or corrector.</td>
      </tr>
      <tr class="u">
         <td class="element ident">expan</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains the expansion of an abbreviation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">gap</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Indicates a point where material has been omitted in a transcription, whether as part
            of
            sampling practice or for editorial reasons described in the MEI header.</td>
      </tr>
      <tr class="u">
         <td class="element ident">handShift</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Marks the beginning of a passage written in a new hand, or of a change in the scribe,
            writing style, ink or character of the document hand.</td>
      </tr>
      <tr class="u">
         <td class="element ident">orig</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains material which is marked as following the original, rather than
            being normalized or corrected.</td>
      </tr>
      <tr class="u">
         <td class="element ident">reg</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains material which has been regularized or normalized in some
            sense.</td>
      </tr>
      <tr class="u">
         <td class="element ident">restore</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Indicates restoration of material to an earlier state by cancellation of an editorial
            or
            authorial marking or instruction.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sic</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains apparently incorrect or inaccurate material.</td>
      </tr>
      <tr class="u">
         <td class="element ident">subst</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups transcriptional elements when the combination is to be regarded as
            a single intervention in the text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">supplied</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains material supplied by the transcriber or editor for any reason.</td>
      </tr>
      <tr class="u">
         <td class="element ident">unclear</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Contains material that cannot be transcribed with certainty because it is illegible
            or
            inaudible in the source.</td>
      </tr>
      <tr class="u">
         <td class="element ident">facsimile</td>
         <td class="module unchanged">MEI.facsimile</td>
         <td class="unchanged">Contains a representation of a written source in the form of a set of images rather
            than
            as transcribed or encoded text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">fig</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Groups elements representing or containing graphic information such as an
            illustration or figure.</td>
      </tr>
      <tr class="u">
         <td class="element ident">figDesc</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Contains a brief prose description of the appearance or content of
            a graphic figure, for use when documenting an image without displaying it.</td>
      </tr>
      <tr class="u">
         <td class="element ident">graphic</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Indicates the location of an inline graphic.</td>
      </tr>
      <tr class="u">
         <td class="element ident">table</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Contains text displayed in tabular form.</td>
      </tr>
      <tr class="u">
         <td class="element ident">td</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Designates a table cell that contains data as opposed to a cell that
            contains column or row heading information.</td>
      </tr>
      <tr class="u">
         <td class="element ident">th</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Designates a table cell containing column or row heading information as
            opposed to one containing data.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tr</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">A formatting element that contains one or more cells (intersection of a row
            and a column) in a  table .</td>
      </tr>
      <tr class="u">
         <td class="element ident">expression</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Intellectual or artistic realization of a work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">expressionList</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Gathers bibliographic expression entities.</td>
      </tr>
      <tr class="u">
         <td class="element ident">item</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Single instance or exemplar of a source/manifestation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">itemList</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Gathers bibliographic item entities.</td>
      </tr>
      <tr class="u">
         <td class="element ident">manifestation</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">A bibliographic description of a physical embodiment of an expression of a work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">manifestationList</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">A container for the descriptions of physical embodiments of an expression of a
            work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">genDesc</td>
         <td class="module unchanged">MEI.genetic</td>
         <td class="unchanged">Bundles information about the textual development of a
            work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">genState</td>
         <td class="module unchanged">MEI.genetic</td>
         <td class="unchanged">Describes a distinctive state in the textual development of a work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">chordTable</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Chord/tablature look-up table.</td>
      </tr>
      <tr class="u">
         <td class="element ident">fb</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Symbols added to a bass line that indicate harmony. Used to improvise a
            chordal accompaniment. Sometimes called Generalbass, thoroughbass, or basso continuo.</td>
      </tr>
      <tr class="u">
         <td class="element ident">accessRestrict</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes the conditions that affect the accessibility of
            material.</td>
      </tr>
      <tr class="u">
         <td class="element ident">acquisition</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Records information concerning the process by which an item was acquired by the holding
            institution.</td>
      </tr>
      <tr class="u">
         <td class="element ident">altId</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">May contain a bibliographic identifier that does not fit within
            the meiHead element’s id attribute, for example because the identifier does not fit
            the
            definition of an XML id or because multiple identifiers are needed.</td>
      </tr>
      <tr class="u">
         <td class="element ident">appInfo</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups information about applications which have acted upon
            the MEI file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">application</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Provides information about an application which has acted upon the current
            document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">attUsage</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Documents the usage of a specific attribute of the element.</td>
      </tr>
      <tr class="u">
         <td class="element ident">audience</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Defines the class of user for which the work is intended, as defined by age group
            ( e.g. ,
            children, young adults, adults, etc.), educational level ( e.g. , primary, secondary,
            etc.), or
            other categorization.</td>
      </tr>
      <tr class="u">
         <td class="element ident">availability</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that describe the availability of and access to a bibliographic item,
            including an MEI-encoded document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">bifolium</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes a folded sheet of paper.</td>
      </tr>
      <tr class="u">
         <td class="element ident">byline</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains the primary statement of responsibility given for a work on its title
            page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">captureMode</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The means used to record notation, sound, or images in the production of
            a source/manifestation ( e.g. , analogue, acoustic, electric, digital, optical etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">carrierForm</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The specific class of material to which the physical carrier of the
            source/manifestation belongs ( e.g. , sound cassette, videodisc, microfilm cartridge,
            transparency, etc.). The carrier for a manifestation comprising multiple physical
            components
            may include more than one form ( e.g. , a filmstrip with an accompanying booklet,
            a separate
            sound disc carrying the sound track for a film, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">category</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains an individual descriptive category in a user-defined taxonomy, possibly nested
            within a superordinate category.</td>
      </tr>
      <tr class="u">
         <td class="element ident">catRel</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains the name, i.e., label, of a related
            category.</td>
      </tr>
      <tr class="u">
         <td class="element ident">change</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Individual change within the revision description.</td>
      </tr>
      <tr class="u">
         <td class="element ident">changeDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Description of a revision of the MEI file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">classDecls</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups information which describes the nature or topic of an entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">classification</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups information which describes the nature or topic of an entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">componentList</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for intellectual or physical component parts of a bibliographic entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">condition</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The physical condition of an item, particularly any variances between the physical
            make-up
            of the item and that of other copies of the same item ( e.g. , missing pages or plates,
            brittleness, faded images, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">contentItem</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains a single entry within a content description element.</td>
      </tr>
      <tr class="u">
         <td class="element ident">contents</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">List of the material contained within a resource.</td>
      </tr>
      <tr class="u">
         <td class="element ident">context</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The historical, social, intellectual, artistic, or other context within which the
            work was
            originally conceived ( e.g. , the 17th century restoration of the monarchy in England,
            the
            aesthetic movement of the late 19th century, etc.) or the historical, social, intellectual,
            artistic, or other context within which the expression was realized.</td>
      </tr>
      <tr class="u">
         <td class="element ident">correction</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">States how and under what circumstances corrections have been made in the text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">cutout</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">A cutout is a section of a document sheet that has been removed and is now missing.</td>
      </tr>
      <tr class="u">
         <td class="element ident">dedication</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains a dedicatory statement.</td>
      </tr>
      <tr class="u">
         <td class="element ident">domainsDecl</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Indicates which domains are included in the encoding.</td>
      </tr>
      <tr class="u">
         <td class="element ident">editionStmt</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for meta-data pertaining to a particular edition of the
            material being described.</td>
      </tr>
      <tr class="u">
         <td class="element ident">editorialDecl</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Used to provide details of editorial principles and practices
            applied during the encoding of musical text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">encodingDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Documents the relationship between an electronic file and the
            source or sources from which it was derived as well as applications used in the
            encoding/editing process.</td>
      </tr>
      <tr class="u">
         <td class="element ident">exhibHist</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">A record of public exhibitions, including dates, venues,
            etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">extMeta</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Provides a container element for non-MEI metadata formats.</td>
      </tr>
      <tr class="u">
         <td class="element ident">fileChar</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Standards or schemes used to encode the file ( e.g. , ASCII, SGML,
            etc.), physical characteristics of the file ( e.g. , recording density, parity, blocking,
            etc.),
            and other characteristics that have a bearing on how the file can be processed.</td>
      </tr>
      <tr class="u">
         <td class="element ident">fileDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains a full bibliographic description of the MEI file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">foliaDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes the order of folia and bifolia making up the text block of a manuscript
            or
            print.</td>
      </tr>
      <tr class="u">
         <td class="element ident">folium</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes a single leaf of paper.</td>
      </tr>
      <tr class="u">
         <td class="element ident">hand</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Defines a distinct scribe or handwriting style.</td>
      </tr>
      <tr class="u">
         <td class="element ident">handList</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for one or more hand elements.</td>
      </tr>
      <tr class="u">
         <td class="element ident">history</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Provides a container for information about the history of a resource other than the
            circumstances of its creation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">incipCode</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Incipit coded in a non-XML, plain text format, such as Plaine &amp; Easie Code.</td>
      </tr>
      <tr class="u">
         <td class="element ident">incipText</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Opening words of a musical composition.</td>
      </tr>
      <tr class="u">
         <td class="element ident">inscription</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">An inscription added to an item, such as a bookplate, a note designating the item
            as a
            gift, and/or the author’s signature.</td>
      </tr>
      <tr class="u">
         <td class="element ident">interpretation</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes the scope of any analytic or interpretive information added to the transcription
            of the music.</td>
      </tr>
      <tr class="u">
         <td class="element ident">key</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Key captures information about tonal center and mode.</td>
      </tr>
      <tr class="u">
         <td class="element ident">language</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Description of a language used in the document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">langUsage</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements describing the languages, sub-languages, dialects,
            etc., represented within the encoded resource.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mensuration</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Captures information about mensuration within bibliographic descriptions.</td>
      </tr>
      <tr class="u">
         <td class="element ident">meter</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Captures information about the time signature within bibliographic descriptions.</td>
      </tr>
      <tr class="u">
         <td class="element ident">namespace</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Supplies the formal name of the namespace to which the elements documented by its
            children
            belong.</td>
      </tr>
      <tr class="u">
         <td class="element ident">normalization</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Indicates the extent of normalization or regularization of the original source carried
            out
            in converting it to electronic form.</td>
      </tr>
      <tr class="u">
         <td class="element ident">notesStmt</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Collects any notes providing information about a text additional to
            that recorded in other parts of the bibliographic description.</td>
      </tr>
      <tr class="u">
         <td class="element ident">otherChar</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Any characteristic that serves to differentiate a
            work or expression from another.</td>
      </tr>
      <tr class="u">
         <td class="element ident">patch</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes a physical writing surface attached to the original document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">perfDuration</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Used to express the duration of performance of printed or
            manuscript music or the playing time for a sound recording, videorecording, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">perfMedium</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Indicates the number and character of the performing forces used in
            a musical composition.</td>
      </tr>
      <tr class="u">
         <td class="element ident">perfRes</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Name of an instrument on which a performer plays, a performer's
            voice range, or a standard performing ensemble designation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">perfResList</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Several instrumental or vocal resources treated as a group.</td>
      </tr>
      <tr class="u">
         <td class="element ident">physDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for information about the appearance, construction, or
            handling of physical materials, such as their dimension, quantity, color, style, and
            technique
            of creation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">physMedium</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Records the physical materials used in the source, such as ink and
            paper.</td>
      </tr>
      <tr class="u">
         <td class="element ident">plateNum</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Designation assigned to a resource by a music publisher, usually printed
            at the bottom of each page, and sometimes appearing also on the title page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">playingSpeed</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Playing speed for a sound recording is the speed at which the carrier must be operated
            to
            produce the sound intended ( e.g. , 33 1/3 rpm, 19 cm/s, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">price</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The cost of access to a bibliographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">projectDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Project-level meta-data describing the aim or purpose for which
            the electronic file was encoded, funding agencies, etc. together with any other relevant
            information concerning the process by which it was assembled or collected.</td>
      </tr>
      <tr class="u">
         <td class="element ident">provenance</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The record of ownership or custodianship of an item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pubStmt</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for information regarding the publication or
            distribution of a bibliographic item, including the publisher’s name and address,
            the date of
            publication, and other relevant details.</td>
      </tr>
      <tr class="u">
         <td class="element ident">revisionDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for information about alterations that have been made
            to an MEI file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">samplingDecl</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains a prose description of the rationale and methods used in
            sampling texts in the creation of a corpus or collection.</td>
      </tr>
      <tr class="u">
         <td class="element ident">scoreFormat</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes the type of score used to represent a musical composition ( e.g. , short
            score,
            full score, condensed score, close score, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">segmentation</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Describes the principles according to which the musical text has been segmented, for
            example into movements, sections, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">seriesStmt</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups information about the series, if any, to which a publication
            belongs.</td>
      </tr>
      <tr class="u">
         <td class="element ident">soundChan</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Reflects the number of apparent sound channels in the playback of a
            recording (monaural, stereophonic, quadraphonic, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">source</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">A bibliographic description of a source used in the creation of the electronic
            file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sourceDesc</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">A container for the descriptions of the source(s) used in the
            creation of the electronic file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">specRepro</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">The equalization system, noise reduction system,
            etc. used in making the recording ( e.g. , NAB, DBX, Dolby, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">stdVals</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Specifies the format used when standardized date or number values are
            supplied.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sysReq</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">System requirements for using the electronic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tagsDecl</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Provides detailed information about the tagging applied to a
            document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">tagUsage</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Documents the usage of a specific element within the document.</td>
      </tr>
      <tr class="u">
         <td class="element ident">taxonomy</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Defines a typology either implicitly, by means of a bibliographic citation, or explicitly
            by a structured taxonomy.</td>
      </tr>
      <tr class="u">
         <td class="element ident">termList</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Collection of text phrases which describe a resource.</td>
      </tr>
      <tr class="u">
         <td class="element ident">titleStmt</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for title and responsibility meta-data.</td>
      </tr>
      <tr class="u">
         <td class="element ident">trackConfig</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Number of physical/input tracks on a sound medium ( e.g. , eight
            track, twelve track).</td>
      </tr>
      <tr class="u">
         <td class="element ident">treatHist</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">A record of the treatment the item has undergone ( e.g. ,
            de-acidification, restoration, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">treatSched</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Scheduled treatment,  e.g. , de-acidification, restoration, etc., for
            an item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">unpub</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Used to explicitly indicate that a bibliographic resource is
            unpublished.</td>
      </tr>
      <tr class="u">
         <td class="element ident">useRestrict</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Container for information about the conditions that affect use of a
            bibliographic item after access has been granted.</td>
      </tr>
      <tr class="u">
         <td class="element ident">watermark</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Contains a description of a watermark or similar device.</td>
      </tr>
      <tr class="u">
         <td class="element ident">work</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Provides a detailed description of a work — a distinct intellectual or artistic creation
            —
            specifically its history, language use, and high-level musical attributes ( e.g. ,
            key, tempo,
            meter, medium of performance, and intended duration).</td>
      </tr>
      <tr class="u">
         <td class="element ident">workList</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Grouping mechanism for information describing non-bibliographic aspects of a
            text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">refrain</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Recurring lyrics, especially at the end of each verse or stanza of a poem or song
            lyrics;
            a chorus.</td>
      </tr>
      <tr class="u">
         <td class="element ident">verse</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Division of a poem or song lyrics, sometimes having a fixed length, meter or rhyme
            scheme;
            a stanza.</td>
      </tr>
      <tr class="u">
         <td class="element ident">volta</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Sung text for a specific iteration of a repeated section of music.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ligature</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">A mensural notation symbol that combines two or more notes into a single sign.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mensur</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Collects information about the metrical relationship between a note value
            and the next smaller value; that is, either triple or duple.</td>
      </tr>
      <tr class="u">
         <td class="element ident">plica</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Plica</td>
      </tr>
      <tr class="u">
         <td class="element ident">proport</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Description of note duration as arithmetic ratio.</td>
      </tr>
      <tr class="u">
         <td class="element ident">stem</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">A stem element.</td>
      </tr>
      <tr class="u">
         <td class="element ident">cc</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI parameter/control change.</td>
      </tr>
      <tr class="u">
         <td class="element ident">chan</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI channel assignment.</td>
      </tr>
      <tr class="u">
         <td class="element ident">chanPr</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI channel pressure/after touch.</td>
      </tr>
      <tr class="u">
         <td class="element ident">cue</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI cue point.</td>
      </tr>
      <tr class="u">
         <td class="element ident">hex</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Arbitrary MIDI data in hexadecimal form.</td>
      </tr>
      <tr class="u">
         <td class="element ident">instrGrp</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Collects MIDI instrument definitions.</td>
      </tr>
      <tr class="u">
         <td class="element ident">marker</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI marker meta-event.</td>
      </tr>
      <tr class="u">
         <td class="element ident">metaText</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI text meta-event.</td>
      </tr>
      <tr class="u">
         <td class="element ident">midi</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Container for elements that contain information useful when generating MIDI output.</td>
      </tr>
      <tr class="u">
         <td class="element ident">noteOff</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI note-off event.</td>
      </tr>
      <tr class="u">
         <td class="element ident">noteOn</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI note-on event.</td>
      </tr>
      <tr class="u">
         <td class="element ident">port</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI port.</td>
      </tr>
      <tr class="u">
         <td class="element ident">prog</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI program change.</td>
      </tr>
      <tr class="u">
         <td class="element ident">seqNum</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI sequence number.</td>
      </tr>
      <tr class="u">
         <td class="element ident">trkName</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI track/sequence name.</td>
      </tr>
      <tr class="u">
         <td class="element ident">vel</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI Note-on/off velocity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">accMat</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Holds a description of any additional material bound with an item, such as
            non-contemporaneous documents or fragments.</td>
      </tr>
      <tr class="u">
         <td class="element ident">addDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Provides a description of significant additions found within an
            item, such as marginalia or other annotations.</td>
      </tr>
      <tr class="u">
         <td class="element ident">binding</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a description of one binding,  i.e. , type of covering, boards, etc.
            applied to an item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">bindingDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes the present and former bindings of an item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">catchwords</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes the system used to ensure correct ordering of the quires making up an item,
            typically by means of annotations at the foot of the page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">collation</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Records a description of how the leaves or bifolia of an item are physically
            arranged.</td>
      </tr>
      <tr class="u">
         <td class="element ident">colophon</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a statement providing information regarding the date, place, agency, or reason
            for production of the item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">decoDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a description of the decoration of an item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">decoNote</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a description of one or more decorative features of an
            item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">explicit</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains the explicit of a manuscript item; that is, the closing words of the text
            proper,
            exclusive of any rubric or colophon which might follow it.</td>
      </tr>
      <tr class="u">
         <td class="element ident">foliation</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes the numbering system or systems used to count the leaves or pages in a
            codex.</td>
      </tr>
      <tr class="u">
         <td class="element ident">heraldry</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a heraldic formula or phrase, typically found as part of a blazon, coat of
            arms,
            etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">layout</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes how text is laid out on the page, including information about any ruling,
            pricking, or other evidence of page-preparation techniques.</td>
      </tr>
      <tr class="u">
         <td class="element ident">layoutDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Collects layout descriptions.</td>
      </tr>
      <tr class="u">
         <td class="element ident">locus</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Defines a location within a manuscript or manuscript component, usually as a (possibly
            discontinuous) sequence of folio references.</td>
      </tr>
      <tr class="u">
         <td class="element ident">locusGrp</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Groups locations which together form a distinct but discontinuous item
            within a manuscript or manuscript part, according to a specific foliation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">rubric</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a string of words through which a manuscript signals the beginning or end
            of a
            text division, often with an assertion as to its author and title, which is in some
            way set
            off from the text itself, usually in red ink, or by use of different size or type
            of script,
            or some other such visual device.</td>
      </tr>
      <tr class="u">
         <td class="element ident">scriptDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a description of the letters or characters used in an
            autographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">scriptNote</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes a particular script distinguished within the description of an
            autographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">seal</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">A single seal or similar attachment.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sealDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes the seals or similar external attachments applied to an
            item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">secFolio</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Marks the word or words taken from a fixed point in a codex (typically
            the beginning of the second leaf) in order to provide a unique identifier for the
            item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">signatures</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Provides a description of the leaf or quire signatures found within a codex.</td>
      </tr>
      <tr class="u">
         <td class="element ident">stamp</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a word or phrase describing an official mark indicating ownership, genuineness,
            validity, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">support</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Provides a description of the physical support material of a written item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">supportDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Groups elements describing the physical support material of an
            item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">typeDesc</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Contains a description of the typefaces or other aspects of the
            printing of a printed source.</td>
      </tr>
      <tr class="u">
         <td class="element ident">typeNote</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Describes a particular font or other significant typographic feature of a
            printed resource.</td>
      </tr>
      <tr class="u">
         <td class="element ident">addName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains an additional name component, such as a nickname, epithet, or
            alias, or any other descriptive phrase used within a personal name.</td>
      </tr>
      <tr class="u">
         <td class="element ident">bloc</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains the name of a geopolitical unit consisting of two or more nation states or
            countries.</td>
      </tr>
      <tr class="u">
         <td class="element ident">corpName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Identifies an organization or group of people that acts as a single
            entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">country</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains the name of a geopolitical unit, such as a nation, country, colony, or
            commonwealth, larger than or administratively superior to a region and smaller than
            a
            bloc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">district</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains the name of any kind of subdivision of a settlement, such as a parish, ward,
            or
            other administrative or geographic unit.</td>
      </tr>
      <tr class="u">
         <td class="element ident">famName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a family (inherited) name, as opposed to a given, baptismal, or
            nick name.</td>
      </tr>
      <tr class="u">
         <td class="element ident">foreName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a forename, given or baptismal name.</td>
      </tr>
      <tr class="u">
         <td class="element ident">genName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a name component used to distinguish otherwise
            similar names on the basis of the relative ages or generations of the persons named.</td>
      </tr>
      <tr class="u">
         <td class="element ident">geogFeat</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a common noun identifying a geographical
            feature.</td>
      </tr>
      <tr class="u">
         <td class="element ident">geogName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">The proper noun designation for a place, natural feature, or political
            jurisdiction.</td>
      </tr>
      <tr class="u">
         <td class="element ident">nameLink</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a connecting phrase or link used within a name but not regarded as
            part of it, such as "van der" or "of", "from", etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">periodName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">A label that describes a period of time, such as 'Baroque' or '3rd Style
            period'.</td>
      </tr>
      <tr class="u">
         <td class="element ident">persName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Designation for an individual, including any or all of that individual's
            forenames, surnames, honorific titles, and added names.</td>
      </tr>
      <tr class="u">
         <td class="element ident">postBox</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a number or other identifier for some postal
            delivery point other than a street address.</td>
      </tr>
      <tr class="u">
         <td class="element ident">postCode</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a numerical or alphanumeric code used as part of a postal address
            to simplify sorting or delivery of mail.</td>
      </tr>
      <tr class="u">
         <td class="element ident">region</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains the name of an administrative unit such as a state, province, or county,
            larger
            than a settlement, but smaller than a country.</td>
      </tr>
      <tr class="u">
         <td class="element ident">roleName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains a name component which indicates that the referent has a particular
            role or position in society, such as an official title or rank.</td>
      </tr>
      <tr class="u">
         <td class="element ident">settlement</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Contains the name of a settlement such as a city, town, or village identified as a
            single
            geopolitical or administrative unit.</td>
      </tr>
      <tr class="u">
         <td class="element ident">street</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">full street address including any name or number identifying a building as well as
            the
            name of the street or route on which it is located.</td>
      </tr>
      <tr class="u">
         <td class="element ident">styleName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">A label for a characteristic style of writing or performance, such as
            'bebop' or 'rock-n-roll'.</td>
      </tr>
      <tr class="u">
         <td class="element ident">episema</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Episema.</td>
      </tr>
      <tr class="u">
         <td class="element ident">hispanTick</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Hispanic tick.</td>
      </tr>
      <tr class="u">
         <td class="element ident">liquescent</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Liquescent.</td>
      </tr>
      <tr class="u">
         <td class="element ident">nc</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Sign representing a single pitched event, although the exact pitch may not be
            known.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ncGrp</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Collection of one or more neume components.</td>
      </tr>
      <tr class="u">
         <td class="element ident">neume</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Sign representing one or more musical pitches.</td>
      </tr>
      <tr class="u">
         <td class="element ident">oriscus</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Oriscus.</td>
      </tr>
      <tr class="u">
         <td class="element ident">quilisma</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Quilisma.</td>
      </tr>
      <tr class="u">
         <td class="element ident">signifLet</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Significantive letter(s).</td>
      </tr>
      <tr class="u">
         <td class="element ident">strophicus</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Strophicus.</td>
      </tr>
      <tr class="u">
         <td class="element ident">syllable</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Neume notation can be thought of as "neumed text". Therefore, the syllable element
            provides high-level organization in this repertoire.</td>
      </tr>
      <tr class="u">
         <td class="element ident">divLine</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Represents a division (divisio) in neume notation. Divisions indicate short, medium,
            or long pauses
            similar to breath marks in modern notation.</td>
      </tr>
      <tr class="u">
         <td class="element ident">avFile</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">References an external digital audio or video file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">clip</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">Defines a time segment of interest within a recording or within a digital audio or
            video
            file.</td>
      </tr>
      <tr class="u">
         <td class="element ident">performance</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">A presentation of one or more musical works.</td>
      </tr>
      <tr class="u">
         <td class="element ident">recording</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">A recorded performance.</td>
      </tr>
      <tr class="u">
         <td class="element ident">when</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">Indicates a point in time either absolutely (using the absolute attribute), or relative
            to
            another when element (using the since, interval and inttype attributes).</td>
      </tr>
      <tr class="u">
         <td class="element ident">ptr</td>
         <td class="module unchanged">MEI.ptrref</td>
         <td class="unchanged">Defines a traversible pointer to another location, using only attributes to
            describe the destination.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ref</td>
         <td class="module unchanged">MEI.ptrref</td>
         <td class="unchanged">Defines a traversible reference to another location. May contain text and
            sub-elements that describe the destination.</td>
      </tr>
      <tr class="u">
         <td class="element ident">accid</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Records a temporary alteration to the pitch of a note.</td>
      </tr>
      <tr class="u">
         <td class="element ident">actor</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Name of an actor appearing within a cast list.</td>
      </tr>
      <tr class="u">
         <td class="element ident">address</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a postal address, for example of a publisher, an organization, or an
            individual.</td>
      </tr>
      <tr class="u">
         <td class="element ident">addrLine</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Single line of a postal address.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ambitus</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Range of a voice, instrument or piece.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ambNote</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Highest or lowest pitch in a score, staff, or layer.</td>
      </tr>
      <tr class="u">
         <td class="element ident">analytic</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains bibliographic elements describing an item ( e.g. , an article or
            poem) published within a monograph or journal and not as an independent publication.</td>
      </tr>
      <tr class="u">
         <td class="element ident">annot</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides a statement explaining the text or indicating the basis for an
            assertion.</td>
      </tr>
      <tr class="u">
         <td class="element ident">arranger</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A person or organization who transcribes a musical composition, usually for a different
            medium from that of the original; in an arrangement the musical substance remains
            essentially
            unchanged.</td>
      </tr>
      <tr class="u">
         <td class="element ident">artic</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An indication of how to play a note or chord.</td>
      </tr>
      <tr class="u">
         <td class="element ident">author</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">The name of the creator of the intellectual content of a non-musical, literary
            work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">barLine</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Vertical line drawn through one or more staves that divides musical notation into
            metrical
            units.</td>
      </tr>
      <tr class="u">
         <td class="element ident">bibl</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides a loosely-structured bibliographic citation in which
            the sub-components may or may not be explicitly marked.</td>
      </tr>
      <tr class="u">
         <td class="element ident">biblList</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">List of bibliographic references.</td>
      </tr>
      <tr class="u">
         <td class="element ident">biblScope</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Defines the scope of a bibliographic reference, for example as a
            list of page numbers, or a named subdivision of a larger work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">biblStruct</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a bibliographic citation in which
            bibliographic sub-elements must appear in a specified order.</td>
      </tr>
      <tr class="u">
         <td class="element ident">body</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains the whole of a single musical text, excluding any front or back matter.</td>
      </tr>
      <tr class="u">
         <td class="element ident">caption</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A label which accompanies an illustration or a table.</td>
      </tr>
      <tr class="u">
         <td class="element ident">castGrp</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups one or more individual castItem elements within a cast list.</td>
      </tr>
      <tr class="u">
         <td class="element ident">castItem</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a single entry within a cast list, describing either a single role or a list
            of
            non-speaking roles.</td>
      </tr>
      <tr class="u">
         <td class="element ident">castList</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a single cast list or dramatis personae.</td>
      </tr>
      <tr class="u">
         <td class="element ident">cb</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An empty formatting element that forces text to begin in a new
            column.</td>
      </tr>
      <tr class="u">
         <td class="element ident">chord</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A simultaneous sounding of two or more notes in the same layer *with the same
            duration*.</td>
      </tr>
      <tr class="u">
         <td class="element ident">clef</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Indication of the exact location of a particular note on the staff and, therefore,
            the
            other notes as well.</td>
      </tr>
      <tr class="u">
         <td class="element ident">clefGrp</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A set of simultaneously-occurring clefs.</td>
      </tr>
      <tr class="u">
         <td class="element ident">colLayout</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An empty formatting element that signals the start of columnar
            layout.</td>
      </tr>
      <tr class="u">
         <td class="element ident">composer</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">The name of the creator of the intellectual content of a musical work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">contributor</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Names of individuals, institutions, or organizations responsible for contributions
            to the
            intellectual content of a work, where the specialized elements for authors, editors,
            etc. do
            not suffice or do not apply.</td>
      </tr>
      <tr class="u">
         <td class="element ident">creation</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Non-bibliographic details of the creation of an intellectual entity, in narrative
            form,
            such as the date, place, and circumstances of its composition. More detailed information
            may
            be captured within the history element.</td>
      </tr>
      <tr class="u">
         <td class="element ident">custos</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Symbol placed at the end of a line of music to indicate the first note of the next
            line.
            Sometimes called a "direct".</td>
      </tr>
      <tr class="u">
         <td class="element ident">date</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A string identifying a point in time or the time period between two such points.</td>
      </tr>
      <tr class="u">
         <td class="element ident">dedicatee</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Entity to whom a creative work is formally offered.</td>
      </tr>
      <tr class="u">
         <td class="element ident">depth</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Description of a measurement taken through a three-dimensional object.</td>
      </tr>
      <tr class="u">
         <td class="element ident">desc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Container for text that briefly describes the feature to which it is
            attached, including its intended usage, purpose, or application as appropriate.</td>
      </tr>
      <tr class="u">
         <td class="element ident">dim</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Any single dimensional specification.</td>
      </tr>
      <tr class="u">
         <td class="element ident">dimensions</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Information about the physical size of an entity; usually includes numerical data.</td>
      </tr>
      <tr class="u">
         <td class="element ident">distributor</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Person or agency, other than a publisher, from which access (including electronic
            access)
            to a bibliographic entity may be obtained.</td>
      </tr>
      <tr class="u">
         <td class="element ident">div</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Major structural division of text, such as a preface, chapter or
            section.</td>
      </tr>
      <tr class="u">
         <td class="element ident">dot</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Dot of augmentation or division.</td>
      </tr>
      <tr class="u">
         <td class="element ident">edition</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A word or text phrase that indicates a difference in either
            content or form between the item being described and a related item previously issued
            by the
            same publisher/distributor ( e.g. , 2nd edition, version 2.0, etc.), or simultaneously
            issued by
            either the same publisher/distributor or another publisher/distributor ( e.g. , large
            print
            edition, British edition, etc.).</td>
      </tr>
      <tr class="u">
         <td class="element ident">editor</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">The name of the individual(s), institution(s) or organization(s) acting in an editorial
            capacity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">ending</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Alternative ending for a repeated passage of music;  i.e. , prima volta, seconda volta,
            etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">event</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a free-text event description.</td>
      </tr>
      <tr class="u">
         <td class="element ident">eventList</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains historical information given as a sequence of significant past events.</td>
      </tr>
      <tr class="u">
         <td class="element ident">expansion</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Indicates how a section may be programmatically expanded into its 'through-composed'
            form.</td>
      </tr>
      <tr class="u">
         <td class="element ident">extent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Used to express size in terms other than physical dimensions, such as number of pages,
            records, bytes, physical components, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">extData</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides a container element for non-MEI data formats.</td>
      </tr>
      <tr class="u">
         <td class="element ident">funder</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Names of individuals, institutions, or organizations responsible for funding. Funders
            provide financial support for a project; they are distinct from sponsors, who provide
            intellectual support and authority.</td>
      </tr>
      <tr class="u">
         <td class="element ident">genre</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Term or terms that designate a category characterizing a particular style, form, or
            content.</td>
      </tr>
      <tr class="u">
         <td class="element ident">group</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a composite musical text, grouping together a sequence of distinct musical
            texts
            (or groups of such musical texts) which are regarded as a unit for some purpose, for
            example,
            the collected works of a composer.</td>
      </tr>
      <tr class="u">
         <td class="element ident">grpSym</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A brace or bracket used to group two or more staves of a score or
            part.</td>
      </tr>
      <tr class="u">
         <td class="element ident">head</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains any heading, for example, the title of a section of text, or the
            heading of a list.</td>
      </tr>
      <tr class="u">
         <td class="element ident">height</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Description of the vertical size of an object.</td>
      </tr>
      <tr class="u">
         <td class="element ident">identifier</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An alpha-numeric string that establishes the identity of the described material.</td>
      </tr>
      <tr class="u">
         <td class="element ident">imprint</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Information relating to the publication or distribution of a bibliographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">incip</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">The opening music and/or words of a musical or textual work.</td>
      </tr>
      <tr class="u">
         <td class="element ident">keyAccid</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Accidental in a key signature.</td>
      </tr>
      <tr class="u">
         <td class="element ident">keySig</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Written key signature.</td>
      </tr>
      <tr class="u">
         <td class="element ident">label</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A container for document text that identifies the feature to which it is attached.
            For a
            "tool tip" or other generated label, use the  label  attribute.</td>
      </tr>
      <tr class="u">
         <td class="element ident">labelAbbr</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A label on the pages following the first.</td>
      </tr>
      <tr class="u">
         <td class="element ident">layer</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An independent stream of events on a staff.</td>
      </tr>
      <tr class="u">
         <td class="element ident">layerDef</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Container for layer meta-information.</td>
      </tr>
      <tr class="u">
         <td class="element ident">lb</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An empty formatting element that forces text to begin on a new
            line.</td>
      </tr>
      <tr class="u">
         <td class="element ident">lg</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">May be used for any section of text that is organized as a group of lines;
            however, it is most often used for a group of verse lines functioning as a formal
            unit,  e.g. , a
            stanza, refrain, verse paragraph, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">librettist</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Person or organization who is a writer of the text of an opera, oratorio, etc.</td>
      </tr>
      <tr class="u">
         <td class="element ident">lyricist</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Person or organization who is a writer of the text of a song.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mdiv</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a subdivision of the body of a musical text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">monogr</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains bibliographic elements describing an item, for example, a
            published book or journal, score, recording, or an unpublished manuscript.</td>
      </tr>
      <tr class="u">
         <td class="element ident">name</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Proper noun or noun phrase.</td>
      </tr>
      <tr class="u">
         <td class="element ident">num</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Numeric information in any form.</td>
      </tr>
      <tr class="u">
         <td class="element ident">p</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">One or more text phrases that form a logical prose passage.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pad</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An indication of extra visual space between notational elements.</td>
      </tr>
      <tr class="u">
         <td class="element ident">part</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An alternative visual rendition of the score from the point of view of a particular
            performer (or group of performers).</td>
      </tr>
      <tr class="u">
         <td class="element ident">parts</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides a container for performers' parts.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pb</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An empty formatting element that forces text to begin on a new
            page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pgDesc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a brief prose description of the appearance or description
            of the content of a physical page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pgFoot</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A running footer.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pgHead</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A running header.</td>
      </tr>
      <tr class="u">
         <td class="element ident">phrase</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Indication of 1) a "unified melodic idea" or 2) performance technique.</td>
      </tr>
      <tr class="u">
         <td class="element ident">physLoc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups information about the current physical location of a
            bibliographic item, such as the repository in which it is located and its shelf mark(s),
            and
            its previous locations.</td>
      </tr>
      <tr class="u">
         <td class="element ident">publisher</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Name of the organization responsible for the publication of a bibliographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">pubPlace</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Name of the place where a bibliographic item was published.</td>
      </tr>
      <tr class="u">
         <td class="element ident">recipient</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">The name of the individual(s), institution(s) or organization(s) receiving
            correspondence.</td>
      </tr>
      <tr class="u">
         <td class="element ident">relatedItem</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains or references another bibliographic item which is related to the
            present one.</td>
      </tr>
      <tr class="u">
         <td class="element ident">relation</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Describes a relationship or linkage amongst entities.</td>
      </tr>
      <tr class="u">
         <td class="element ident">relationList</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Gathers relation elements.</td>
      </tr>
      <tr class="u">
         <td class="element ident">rend</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A formatting element indicating special visual rendering,  e.g. , bold or
            italicized, of a text word or phrase.</td>
      </tr>
      <tr class="u">
         <td class="element ident">repository</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Institution, agency, or individual which holds a bibliographic item.</td>
      </tr>
      <tr class="u">
         <td class="element ident">resp</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A phrase describing the nature of intellectual responsibility.</td>
      </tr>
      <tr class="u">
         <td class="element ident">respStmt</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Transcription of text that names one or more individuals,
            groups, or in rare cases, mechanical processes, responsible for creation, realization,
            production, funding, or distribution of the intellectual or artistic content.</td>
      </tr>
      <tr class="u">
         <td class="element ident">rest</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A non-sounding event found in the source being transcribed.</td>
      </tr>
      <tr class="u">
         <td class="element ident">role</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Name of a dramatic role, as given in a cast list.</td>
      </tr>
      <tr class="u">
         <td class="element ident">roleDesc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Describes a character’s role in a drama.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sb</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An empty formatting element that forces musical notation to begin on
            a new line.</td>
      </tr>
      <tr class="u">
         <td class="element ident">score</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Full score view of the musical content.</td>
      </tr>
      <tr class="u">
         <td class="element ident">section</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Segment of music data.</td>
      </tr>
      <tr class="u">
         <td class="element ident">series</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains information about the serial publication in which a bibliographic item has
            appeared.</td>
      </tr>
      <tr class="u">
         <td class="element ident">space</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A placeholder used to fill an incomplete measure, layer, etc. most often so that the
            combined duration of the events equals the number of beats in the measure.</td>
      </tr>
      <tr class="u">
         <td class="element ident">speaker</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a specialized form of heading or label, giving the name of one or more speakers
            in a dramatic text or fragment.</td>
      </tr>
      <tr class="u">
         <td class="element ident">sponsor</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Names of sponsoring individuals, organizations or institutions. Sponsors give their
            intellectual authority to a project; they are to be distinguished from funders, who
            provide
            the funding but do not necessarily take intellectual responsibility.</td>
      </tr>
      <tr class="u">
         <td class="element ident">stack</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">An inline table with a single column.</td>
      </tr>
      <tr class="u">
         <td class="element ident">staff</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A group of equidistant horizontal lines on which notes are placed in order to represent
            pitch or a grouping element for individual 'strands' of notes, rests, etc. that may
            or may not
            actually be rendered on staff lines; that is, both diastematic and non-diastematic
            signs.</td>
      </tr>
      <tr class="u">
         <td class="element ident">staffGrp</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A group of bracketed or braced staves.</td>
      </tr>
      <tr class="u">
         <td class="element ident">syl</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Individual lyric syllable.</td>
      </tr>
      <tr class="u">
         <td class="element ident">symbol</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">A reference to a previously defined symbol.</td>
      </tr>
      <tr class="u">
         <td class="element ident">term</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Keyword or phrase which describes a resource.</td>
      </tr>
      <tr class="u">
         <td class="element ident">textLang</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Identifies the languages and writing systems within the work described
            by a bibliographic description, not the language of the description.</td>
      </tr>
      <tr class="u">
         <td class="element ident">title</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Title of a bibliographic entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">titlePage</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a transcription of the title page of a text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">titlePart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Contains a subsection or division of the title of a bibliographic entity.</td>
      </tr>
      <tr class="u">
         <td class="element ident">width</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Description of the horizontal size of an object.</td>
      </tr>
      <tr class="u">
         <td class="element ident">argument</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Contains a formal list or prose description of topics addressed.</td>
      </tr>
      <tr class="u">
         <td class="element ident">back</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Contains any appendixes, advertisements, indexes, etc. following the main
            body of a musical text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">epigraph</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Contains a quotation, anonymous or attributed, appearing on a title page.</td>
      </tr>
      <tr class="u">
         <td class="element ident">front</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Bundles prefatory text found before the start of the musical text.</td>
      </tr>
      <tr class="u">
         <td class="element ident">imprimatur</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Contains a formal statement authorizing the publication of a work, sometimes required
            to
            appear on a title page or its verso.</td>
      </tr>
      <tr class="u">
         <td class="element ident">l</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Contains a single line of text within a line group.</td>
      </tr>
      <tr class="u">
         <td class="element ident">li</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Single item in a  list .</td>
      </tr>
      <tr class="u">
         <td class="element ident">list</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">A formatting element that contains a series of items separated from one another and
            arranged in a linear, often vertical, sequence.</td>
      </tr>
      <tr class="u">
         <td class="element ident">seg</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">represents any segmentation of text below the "text component" level.</td>
      </tr>
      <tr class="u">
         <td class="element ident">anchoredText</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Container for text that is fixed to a particular page location, regardless of changes
            made
            to the layout of the measures around it.</td>
      </tr>
      <tr class="u">
         <td class="element ident">curve</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">A curved line that cannot be represented by a more specific element, such as a
            slur.</td>
      </tr>
      <tr class="u">
         <td class="element ident">line</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">A visual line that cannot be represented by a more specific;  i.e. , semantic,
            element.</td>
      </tr>
      <tr class="u">
         <td class="element ident">mapping</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">One or more characters which are related to the parent symbol in some respect, as
            specified by the type attribute.</td>
      </tr>
      <tr class="u">
         <td class="element ident">propName</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Name of a property of the symbol.</td>
      </tr>
      <tr class="u">
         <td class="element ident">propValue</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">A single property value.</td>
      </tr>
      <tr class="u">
         <td class="element ident">symName</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Contains the name of a symbol, expressed following Unicode
            conventions.</td>
      </tr>
      <tr class="u">
         <td class="element ident">symProp</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Provides a name and value for some property of the parent
            symbol.</td>
      </tr>
      <tr class="u">
         <td class="element ident">symbolTable</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Contains a set of user-defined symbols.</td>
      </tr>
   </table>
   <h2>Attribute Class Comparison</h2>
   <h3 id="attClassesAdded">19 new attribute classes:</h3>
   <table class="added">
      <tr class="a" id="att.course.anl">
         <td class="attClass ident">att.course.anl</td>
         <td class="module">MEI.analytical</td>
         <td>Analytical domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabDurSym.anl">
         <td class="attClass ident">att.tabDurSym.anl</td>
         <td class="module">MEI.analytical</td>
         <td>Analytical domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabGrp.anl">
         <td class="attClass ident">att.tabGrp.anl</td>
         <td class="module">MEI.analytical</td>
         <td>Analytical domain attributes.</td>
      </tr>
      <tr class="a" id="att.tuning.anl">
         <td class="attClass ident">att.tuning.anl</td>
         <td class="module">MEI.analytical</td>
         <td>Analytical domain attributes.</td>
      </tr>
      <tr class="a" id="att.course.ges">
         <td class="attClass ident">att.course.ges</td>
         <td class="module">MEI.gestural</td>
         <td>Gestural domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabDurSym.ges">
         <td class="attClass ident">att.tabDurSym.ges</td>
         <td class="module">MEI.gestural</td>
         <td>Gestural domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabGrp.ges">
         <td class="attClass ident">att.tabGrp.ges</td>
         <td class="module">MEI.gestural</td>
         <td>Gestural domain attributes.</td>
      </tr>
      <tr class="a" id="att.tuning.ges">
         <td class="attClass ident">att.tuning.ges</td>
         <td class="module">MEI.gestural</td>
         <td>Gestural domain attributes.</td>
      </tr>
      <tr class="a" id="att.dataSelecting">
         <td class="attClass ident">att.dataSelecting</td>
         <td class="module">MEI.shared</td>
         <td>Attributes for selecting data.</td>
      </tr>
      <tr class="a" id="att.tuning.log">
         <td class="attClass ident">att.tuning.log</td>
         <td class="module">MEI.shared</td>
         <td>Logical domain attributes for tuning.</td>
      </tr>
      <tr class="a" id="att.course.log">
         <td class="attClass ident">att.course.log</td>
         <td class="module">MEI.stringtab</td>
         <td>Logical domain attributes.</td>
      </tr>
      <tr class="a" id="att.scoreDef.vis.tablature">
         <td class="attClass ident">att.scoreDef.vis.tablature</td>
         <td class="module">MEI.stringtab</td>
         <td>Visual domain attributes for scoreDef in the tablature repertoire.</td>
      </tr>
      <tr class="a" id="att.staffDef.vis.tablature">
         <td class="attClass ident">att.staffDef.vis.tablature</td>
         <td class="module">MEI.stringtab</td>
         <td>Visual domain attributes for staffDef in the tablature repertoire.</td>
      </tr>
      <tr class="a" id="att.tabDurSym.log">
         <td class="attClass ident">att.tabDurSym.log</td>
         <td class="module">MEI.stringtab</td>
         <td>Logical domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabGrp.log">
         <td class="attClass ident">att.tabGrp.log</td>
         <td class="module">MEI.stringtab</td>
         <td>Logical domain attributes.</td>
      </tr>
      <tr class="a" id="att.course.vis">
         <td class="attClass ident">att.course.vis</td>
         <td class="module">MEI.visual</td>
         <td>Visual domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabDurSym.vis">
         <td class="attClass ident">att.tabDurSym.vis</td>
         <td class="module">MEI.visual</td>
         <td>Visual domain attributes.</td>
      </tr>
      <tr class="a" id="att.tabGrp.vis">
         <td class="attClass ident">att.tabGrp.vis</td>
         <td class="module">MEI.visual</td>
         <td>Visual domain attributes.</td>
      </tr>
      <tr class="a" id="att.tuning.vis">
         <td class="attClass ident">att.tuning.vis</td>
         <td class="module">MEI.visual</td>
         <td>Visual domain attributes.</td>
      </tr>
   </table>
   <h3 id="attClassesRemoved">0 removed attribute classes:</h3>
   <table class="removed"></table>
   <h3 id="attClassesChanged">27 modified attributes classes:</h3>
   <table>
      <tr class="c" id="att.halfmRpt.log">
         <td class="attClass ident">att.halfmRpt.log</td>
         <td class="module">MEI.cmn</td>
         <td class="desc">Logical domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.event</li>
               <li class="added" title="added class"><a href="#att.duration.additive">att.duration.additive</a></li>
               <li class="removed" title="removed class"><a href="#att.duration.log">att.duration.log</a></li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.stringtab">
         <td class="attClass ident">att.stringtab</td>
         <td class="module">MEI.stringtab</td>
         <td class="desc">String tablature string and fret information.</td>
         <td class="classes">Classes:<br><ul></ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">tab.fing</span></li>
               <li class="unchanged"><span class="attribute">tab.fret</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/attribute-classes/att.stringtab.html" target="_blank">tab.line</a></span></li>
               <li class="unchanged"><span class="attribute">tab.string</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/attribute-classes/att.stringtab.html" target="_blank">tab.course</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.stringtab.tuning">
         <td class="attClass ident">att.stringtab.tuning</td>
         <td class="module">MEI.stringtab</td>
         <td class="desc"><span class="removed block">String tablature tuning information.</span><span class="added block">This collection of attributes is deprecated in favor of the new  tuning  element and
               will be removed in a future version. String tablature tuning information.</span></td>
         <td class="classes">Classes:<br><ul></ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">tab.strings</span></li>
               <li class="added" title="added attribute"><span class="attribute"><a href="https://music-encoding.org/guidelines/v5/attribute-classes/att.stringtab.tuning.html" target="_blank">tab.courses</a></span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.attacca.vis">
         <td class="attClass ident">att.attacca.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.verticalGroup</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.bend.vis">
         <td class="attClass ident">att.bend.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes. If the bulge or bezier attributes are present, the bend
            should
            be rendered as a curve. Otherwise, it should be rendered using lines. The ho and vo
            attributes
            describe the visual offset of the entire rendered bend. The endho, endvo and startho,
            startvo
            attribute pairs may be used to encode start and end points relative to their programmatic
            placement. For exact placement of the endpoints of the bend, use the x and y
            attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.curvature</li>
               <li class="unchanged">att.lineRend.base</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2</li>
               <li class="unchanged">att.xy</li>
               <li class="unchanged">att.xy2</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.breath.vis">
         <td class="attClass ident">att.breath.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.staffLoc</li>
               <li class="unchanged">att.staffLoc.pitched</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.caesura.vis">
         <td class="attClass ident">att.caesura.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.staffLoc</li>
               <li class="unchanged">att.staffLoc.pitched</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.cpMark.vis">
         <td class="attClass ident">att.cpMark.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.dir.vis">
         <td class="attClass ident">att.dir.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.verticalGroup</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.dynam.vis">
         <td class="attClass ident">att.dynam.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.verticalGroup</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.f.vis">
         <td class="attClass ident">att.f.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.fermata.vis">
         <td class="attClass ident">att.fermata.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">form</span></li>
               <li class="unchanged"><span class="attribute">shape</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.fing.vis">
         <td class="attClass ident">att.fing.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.fingGrp.vis">
         <td class="attClass ident">att.fingGrp.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">orient</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.harm.vis">
         <td class="attClass ident">att.harm.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">rendgrid</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.harpPedal.vis">
         <td class="attClass ident">att.harpPedal.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.metaMark.vis">
         <td class="attClass ident">att.metaMark.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.meterSigGrp.vis">
         <td class="attClass ident">att.meterSigGrp.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.enclosingChars">att.enclosingChars</a></li>
               <li class="added" title="added class"><a href="#att.visibility">att.visibility</a></li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.mordent.vis">
         <td class="attClass ident">att.mordent.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.octave.vis">
         <td class="attClass ident">att.octave.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.extender</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.ornam.vis">
         <td class="attClass ident">att.ornam.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.repeatMark.vis">
         <td class="attClass ident">att.repeatMark.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.verticalGroup</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.scoreDef.vis">
         <td class="attClass ident">att.scoreDef.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes for scoreDef in the CMN repertoire.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.barring</li>
               <li class="unchanged">att.cleffing.vis</li>
               <li class="unchanged">att.distances</li>
               <li class="unchanged">att.endings</li>
               <li class="unchanged">att.keySigDefault.vis</li>
               <li class="unchanged">att.lyricStyle</li>
               <li class="unchanged">att.measureNumbers</li>
               <li class="unchanged">att.meterSigDefault.vis</li>
               <li class="unchanged">att.multinumMeasures</li>
               <li class="unchanged">att.notationStyle</li>
               <li class="unchanged">att.oneLineStaff</li>
               <li class="unchanged">att.optimization</li>
               <li class="unchanged">att.pages</li>
               <li class="unchanged">att.spacing</li>
               <li class="unchanged">att.staffItems</li>
               <li class="unchanged">att.systems</li>
               <li class="unchanged">att.textStyle</li>
               <li class="unchanged">att.scoreDef.vis.cmn</li>
               <li class="unchanged">att.scoreDef.vis.mensural</li>
               <li class="added" title="added class"><a href="#att.scoreDef.vis.tablature">att.scoreDef.vis.tablature</a></li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">vu.height</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.staffDef.vis">
         <td class="attClass ident">att.staffDef.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes for staffDef.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.barring</li>
               <li class="unchanged">att.cleffing.vis</li>
               <li class="unchanged">att.distances</li>
               <li class="unchanged">att.guitarGrid.vis</li>
               <li class="unchanged">att.keySigDefault.vis</li>
               <li class="unchanged">att.lyricStyle</li>
               <li class="unchanged">att.meterSigDefault.vis</li>
               <li class="unchanged">att.multinumMeasures</li>
               <li class="unchanged">att.notationStyle</li>
               <li class="unchanged">att.oneLineStaff</li>
               <li class="unchanged">att.scalable</li>
               <li class="unchanged">att.staffItems</li>
               <li class="unchanged">att.textStyle</li>
               <li class="unchanged">att.visibility</li>
               <li class="unchanged">att.staffDef.vis.cmn</li>
               <li class="unchanged">att.staffDef.vis.mensural</li>
               <li class="added" title="added class"><a href="#att.staffDef.vis.tablature">att.staffDef.vis.tablature</a></li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul>
               <li class="unchanged"><span class="attribute">layerscheme</span></li>
               <li class="unchanged"><span class="attribute">lines.color</span></li>
               <li class="unchanged"><span class="attribute">lines.visible</span></li>
               <li class="unchanged"><span class="attribute">spacing</span></li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="att.tempo.vis">
         <td class="attClass ident">att.tempo.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="added" title="added class"><a href="#att.color">att.color</a></li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.verticalGroup</li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.trill.vis">
         <td class="attClass ident">att.trill.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.extender</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.visualOffset2.ho</li>
               <li class="unchanged">att.visualOffset2.to</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
      <tr class="c" id="att.turn.vis">
         <td class="attClass ident">att.turn.vis</td>
         <td class="module">MEI.visual</td>
         <td class="desc">Visual domain attributes.</td>
         <td class="classes">Classes:<br><ul>
               <li class="unchanged">att.altSym</li>
               <li class="unchanged">att.color</li>
               <li class="unchanged">att.enclosingChars</li>
               <li class="unchanged">att.extSym</li>
               <li class="unchanged">att.placementRelStaff</li>
               <li class="unchanged">att.typography</li>
               <li class="added" title="added class"><a href="#att.verticalGroup">att.verticalGroup</a></li>
               <li class="unchanged">att.visualOffset</li>
               <li class="unchanged">att.xy</li>
            </ul>
         </td>
         <td class="content">Attributes:<br><ul></ul>
         </td>
      </tr>
   </table>
   <h3 id="attClassesUnchanged">683 unchanged attribute classes:</h3>
   <table>
      <tr class="u" id="att.notationType">
         <td class="attClass ident">att.notationType</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Attributes that provide for classification of notation.</td>
      </tr>
      <tr class="u" id="att.accid.anl">
         <td class="attClass ident">att.accid.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambitus.anl">
         <td class="attClass ident">att.ambitus.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambNote.anl">
         <td class="attClass ident">att.ambNote.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.anchoredText.anl">
         <td class="attClass ident">att.anchoredText.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.annot.anl">
         <td class="attClass ident">att.annot.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.arpeg.anl">
         <td class="attClass ident">att.arpeg.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.artic.anl">
         <td class="attClass ident">att.artic.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.attacca.anl">
         <td class="attClass ident">att.attacca.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.barLine.anl">
         <td class="attClass ident">att.barLine.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beam.anl">
         <td class="attClass ident">att.beam.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beamSpan.anl">
         <td class="attClass ident">att.beamSpan.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beatRpt.anl">
         <td class="attClass ident">att.beatRpt.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bend.anl">
         <td class="attClass ident">att.bend.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bracketSpan.anl">
         <td class="attClass ident">att.bracketSpan.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.breath.anl">
         <td class="attClass ident">att.breath.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bTrem.anl">
         <td class="attClass ident">att.bTrem.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.caesura.anl">
         <td class="attClass ident">att.caesura.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.chord.anl">
         <td class="attClass ident">att.chord.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordDef.anl">
         <td class="attClass ident">att.chordDef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordMember.anl">
         <td class="attClass ident">att.chordMember.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.clef.anl">
         <td class="attClass ident">att.clef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.clefGrp.anl">
         <td class="attClass ident">att.clefGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.cpMark.anl">
         <td class="attClass ident">att.cpMark.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.curve.anl">
         <td class="attClass ident">att.curve.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.custos.anl">
         <td class="attClass ident">att.custos.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mdiv.anl">
         <td class="attClass ident">att.mdiv.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.dir.anl">
         <td class="attClass ident">att.dir.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.dot.anl">
         <td class="attClass ident">att.dot.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.dynam.anl">
         <td class="attClass ident">att.dynam.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ending.anl">
         <td class="attClass ident">att.ending.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.episema.anl">
         <td class="attClass ident">att.episema.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.f.anl">
         <td class="attClass ident">att.f.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fermata.anl">
         <td class="attClass ident">att.fermata.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fing.anl">
         <td class="attClass ident">att.fing.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fingGrp.anl">
         <td class="attClass ident">att.fingGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fTrem.anl">
         <td class="attClass ident">att.fTrem.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.gliss.anl">
         <td class="attClass ident">att.gliss.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.grpSym.anl">
         <td class="attClass ident">att.grpSym.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.hairpin.anl">
         <td class="attClass ident">att.hairpin.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.halfmRpt.anl">
         <td class="attClass ident">att.halfmRpt.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.harm.anl">
         <td class="attClass ident">att.harm.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.graceGrp.anl">
         <td class="attClass ident">att.graceGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.harmonicFunction">
         <td class="attClass ident">att.harmonicFunction</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes describing the harmonic function of a single pitch.</td>
      </tr>
      <tr class="u" id="att.harpPedal.anl">
         <td class="attClass ident">att.harpPedal.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.hispanTick.anl">
         <td class="attClass ident">att.hispanTick.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.instrDef.anl">
         <td class="attClass ident">att.instrDef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.intervalHarmonic">
         <td class="attClass ident">att.intervalHarmonic</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes that describe harmonic intervals.</td>
      </tr>
      <tr class="u" id="att.intervalMelodic">
         <td class="attClass ident">att.intervalMelodic</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes that provide for description of intervallic content.</td>
      </tr>
      <tr class="u" id="att.keyAccid.anl">
         <td class="attClass ident">att.keyAccid.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySig.anl">
         <td class="attClass ident">att.keySig.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySigDefault.anl">
         <td class="attClass ident">att.keySigDefault.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the analytical
            domain that are related to key signatures.</td>
      </tr>
      <tr class="u" id="att.layer.anl">
         <td class="attClass ident">att.layer.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.layerDef.anl">
         <td class="attClass ident">att.layerDef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ligature.anl">
         <td class="attClass ident">att.ligature.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.line.anl">
         <td class="attClass ident">att.line.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.liquescent.anl">
         <td class="attClass ident">att.liquescent.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.lv.anl">
         <td class="attClass ident">att.lv.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.lyrics.anl">
         <td class="attClass ident">att.lyrics.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.measure.anl">
         <td class="attClass ident">att.measure.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.melodicFunction">
         <td class="attClass ident">att.melodicFunction</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes describing melodic function.</td>
      </tr>
      <tr class="u" id="att.mensur.anl">
         <td class="attClass ident">att.mensur.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.metaMark.anl">
         <td class="attClass ident">att.metaMark.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSig.anl">
         <td class="attClass ident">att.meterSig.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSigGrp.anl">
         <td class="attClass ident">att.meterSigGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.midi.anl">
         <td class="attClass ident">att.midi.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mNum.anl">
         <td class="attClass ident">att.mNum.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mordent.anl">
         <td class="attClass ident">att.mordent.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRest.anl">
         <td class="attClass ident">att.mRest.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.mRpt.anl">
         <td class="attClass ident">att.mRpt.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt2.anl">
         <td class="attClass ident">att.mRpt2.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mSpace.anl">
         <td class="attClass ident">att.mSpace.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire. Use the n attribute to explicitly
            encode this measure’s position in a string of measures containing only  mRest  elements.</td>
      </tr>
      <tr class="u" id="att.multiRest.anl">
         <td class="attClass ident">att.multiRest.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRpt.anl">
         <td class="attClass ident">att.multiRpt.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.nc.anl">
         <td class="attClass ident">att.nc.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ncGrp.anl">
         <td class="attClass ident">att.ncGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.neume.anl">
         <td class="attClass ident">att.neume.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.note.anl">
         <td class="attClass ident">att.note.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.octave.anl">
         <td class="attClass ident">att.octave.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ornam.anl">
         <td class="attClass ident">att.ornam.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.oriscus.anl">
         <td class="attClass ident">att.oriscus.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ossia.anl">
         <td class="attClass ident">att.ossia.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pad.anl">
         <td class="attClass ident">att.pad.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.part.anl">
         <td class="attClass ident">att.part.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.parts.anl">
         <td class="attClass ident">att.parts.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pb.anl">
         <td class="attClass ident">att.pb.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pedal.anl">
         <td class="attClass ident">att.pedal.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.phrase.anl">
         <td class="attClass ident">att.phrase.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pitchClass">
         <td class="attClass ident">att.pitchClass</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes that describe pitch class.</td>
      </tr>
      <tr class="u" id="att.plica.anl">
         <td class="attClass ident">att.plica.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes that describe the properties of a plica in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.proport.anl">
         <td class="attClass ident">att.proport.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.quilisma.anl">
         <td class="attClass ident">att.quilisma.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.rdg.anl">
         <td class="attClass ident">att.rdg.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.refrain.anl">
         <td class="attClass ident">att.refrain.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.reh.anl">
         <td class="attClass ident">att.reh.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.repeatMark.anl">
         <td class="attClass ident">att.repeatMark.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.rest.anl">
         <td class="attClass ident">att.rest.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.sb.anl">
         <td class="attClass ident">att.sb.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.score.anl">
         <td class="attClass ident">att.score.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.anl">
         <td class="attClass ident">att.scoreDef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.section.anl">
         <td class="attClass ident">att.section.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.slur.anl">
         <td class="attClass ident">att.slur.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.signifLet.anl">
         <td class="attClass ident">att.signifLet.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.solfa">
         <td class="attClass ident">att.solfa</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Attributes that specify pitch using sol-fa.</td>
      </tr>
      <tr class="u" id="att.sp.anl">
         <td class="attClass ident">att.sp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.space.anl">
         <td class="attClass ident">att.space.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.staff.anl">
         <td class="attClass ident">att.staff.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffDef.anl">
         <td class="attClass ident">att.staffDef.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffGrp.anl">
         <td class="attClass ident">att.staffGrp.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.stageDir.anl">
         <td class="attClass ident">att.stageDir.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.stem.anl">
         <td class="attClass ident">att.stem.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes that describe the properties of a stem in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.strophicus.anl">
         <td class="attClass ident">att.strophicus.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.syl.anl">
         <td class="attClass ident">att.syl.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.syllable.anl">
         <td class="attClass ident">att.syllable.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.symbol.anl">
         <td class="attClass ident">att.symbol.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tempo.anl">
         <td class="attClass ident">att.tempo.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tie.anl">
         <td class="attClass ident">att.tie.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.trill.anl">
         <td class="attClass ident">att.trill.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tuplet.anl">
         <td class="attClass ident">att.tuplet.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tupletSpan.anl">
         <td class="attClass ident">att.tupletSpan.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.turn.anl">
         <td class="attClass ident">att.turn.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.verse.anl">
         <td class="attClass ident">att.verse.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.volta.anl">
         <td class="attClass ident">att.volta.anl</td>
         <td class="module unchanged">MEI.analytical</td>
         <td class="unchanged">Analytical domain attributes.</td>
      </tr>
      <tr class="u" id="att.arpeg.log">
         <td class="attClass ident">att.arpeg.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beam.log">
         <td class="attClass ident">att.beam.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beamedWith">
         <td class="attClass ident">att.beamedWith</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes indicating cross-staff beaming.</td>
      </tr>
      <tr class="u" id="att.beaming.log">
         <td class="attClass ident">att.beaming.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Used by layerDef, staffDef, and scoreDef to provide default values for attributes
            in the
            logical domain related to beaming.</td>
      </tr>
      <tr class="u" id="att.beamPresent">
         <td class="attClass ident">att.beamPresent</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that indicate whether an event lies under a beam.</td>
      </tr>
      <tr class="u" id="att.beamRend">
         <td class="attClass ident">att.beamRend</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that record the visual rendition of beams.</td>
      </tr>
      <tr class="u" id="att.beamSecondary">
         <td class="attClass ident">att.beamSecondary</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that capture information about secondary beaming.</td>
      </tr>
      <tr class="u" id="att.beamSpan.log">
         <td class="attClass ident">att.beamSpan.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.beatRpt.log">
         <td class="attClass ident">att.beatRpt.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bend.log">
         <td class="attClass ident">att.bend.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bracketSpan.log">
         <td class="attClass ident">att.bracketSpan.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.breath.log">
         <td class="attClass ident">att.breath.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bTrem.log">
         <td class="attClass ident">att.bTrem.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.chord.anl.cmn">
         <td class="attClass ident">att.chord.anl.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.chord.ges.cmn">
         <td class="attClass ident">att.chord.ges.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Gestural domain attributes for CMN features.</td>
      </tr>
      <tr class="u" id="att.chord.log.cmn">
         <td class="attClass ident">att.chord.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.chord.vis.cmn">
         <td class="attClass ident">att.chord.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes for chord. The slur, slur.dir, slur.rend, tie, tie.dir, and
            tie.rend attributes here are "syntactic sugar" for these attributes on each of the
            chord's
            individual notes. The values here apply to all the notes in the chord. If some notes
            are
            slurred or tied while others aren't, then the individual note attributes must be used.</td>
      </tr>
      <tr class="u" id="att.cutout">
         <td class="attClass ident">att.cutout</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that indicate how to render the staff lines of the measure containing an
            element belonging to this attribute class.</td>
      </tr>
      <tr class="u" id="att.mNum.log">
         <td class="attClass ident">att.mNum.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.expandable">
         <td class="attClass ident">att.expandable</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that indicate whether to render a repeat symbol or the source material
            to which
            it refers.</td>
      </tr>
      <tr class="u" id="att.fermata.log">
         <td class="attClass ident">att.fermata.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fTrem.log">
         <td class="attClass ident">att.fTrem.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.glissPresent">
         <td class="attClass ident">att.glissPresent</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that indicate whether an event participates in a glissando.</td>
      </tr>
      <tr class="u" id="att.gliss.log">
         <td class="attClass ident">att.gliss.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.graced">
         <td class="attClass ident">att.graced</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that mark a note or chord as a "grace", how it should "steal" time, and
            how
            much time should be allotted to the grace note/chord.</td>
      </tr>
      <tr class="u" id="att.graceGrp.log">
         <td class="attClass ident">att.graceGrp.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.hairpin.log">
         <td class="attClass ident">att.hairpin.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.harpPedal.log">
         <td class="attClass ident">att.harpPedal.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes. The pedal setting,  i.e. , flat, natural, or sharp, for
            each
            diatonic pitch name is indicated by the seven letter-named attributes.</td>
      </tr>
      <tr class="u" id="att.layerDef.log.cmn">
         <td class="attClass ident">att.layerDef.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.lv.log">
         <td class="attClass ident">att.lv.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.lvPresent">
         <td class="attClass ident">att.lvPresent</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that indicate the presence of an l.v. (laissez vibrer) marking attached
            to a
            feature. If visual information about the lv sign needs to be recorded, then an  lv
            element should be employed.</td>
      </tr>
      <tr class="u" id="att.measure.log">
         <td class="attClass ident">att.measure.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes. The n attribute contains a name or number associated with
            the
            measure (Read, p. 445). Often, this is an integer, but not always. For example, some
            measures,
            especially incomplete measures or those under an ending mark, may have labels that
            contain an
            integer plus a suffix, such as '12a'. Measures may even have labels, especially in
            editorial
            or analytical uses of MEI, that are entirely non-numeric strings. Measure numbers
            may be
            machine-generated instead of encoding them in the markup. However, an explicit measure
            number
            should restart numbering with the given value. The join attribute may be used to indicate
            another measure which metrically completes the current, incomplete one.</td>
      </tr>
      <tr class="u" id="att.meterSigGrp.log">
         <td class="attClass ident">att.meterSigGrp.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRest.log">
         <td class="attClass ident">att.mRest.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt.log">
         <td class="attClass ident">att.mRpt.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt2.log">
         <td class="attClass ident">att.mRpt2.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mSpace.log">
         <td class="attClass ident">att.mSpace.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.multiRest.log">
         <td class="attClass ident">att.multiRest.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRpt.log">
         <td class="attClass ident">att.multiRpt.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.note.anl.cmn">
         <td class="attClass ident">att.note.anl.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.note.log.cmn">
         <td class="attClass ident">att.note.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.note.vis.cmn">
         <td class="attClass ident">att.note.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.numbered">
         <td class="attClass ident">att.numbered</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that record numbers to be displayed with a feature.</td>
      </tr>
      <tr class="u" id="att.numberPlacement">
         <td class="attClass ident">att.numberPlacement</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that record the placement and visibility of numbers that accompany a bowed
            tremolo or tuplet.</td>
      </tr>
      <tr class="u" id="att.octave.log">
         <td class="attClass ident">att.octave.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ossia.log">
         <td class="attClass ident">att.ossia.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pedal.log">
         <td class="attClass ident">att.pedal.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.phrase.vis.cmn">
         <td class="attClass ident">att.phrase.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.pianoPedals">
         <td class="attClass ident">att.pianoPedals</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Used by scoreDef and staffDef to provide default description of piano pedal
            rendition.</td>
      </tr>
      <tr class="u" id="att.reh.log">
         <td class="attClass ident">att.reh.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.rehearsal">
         <td class="attClass ident">att.rehearsal</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes used by scoreDef and staffDef to provide default information about rehearsal
            numbers/letters.</td>
      </tr>
      <tr class="u" id="att.rest.anl.cmn">
         <td class="attClass ident">att.rest.anl.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.rest.log.cmn">
         <td class="attClass ident">att.rest.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.rest.vis.cmn">
         <td class="attClass ident">att.rest.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.log.cmn">
         <td class="attClass ident">att.scoreDef.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.vis.cmn">
         <td class="attClass ident">att.scoreDef.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.slur.log">
         <td class="attClass ident">att.slur.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.slurRend">
         <td class="attClass ident">att.slurRend</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that describe the rendition of slurs.</td>
      </tr>
      <tr class="u" id="att.space.anl.cmn">
         <td class="attClass ident">att.space.anl.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Analytical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.space.log.cmn">
         <td class="attClass ident">att.space.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.staffDef.log.cmn">
         <td class="attClass ident">att.staffDef.log.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes for staffDef in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.staffDef.vis.cmn">
         <td class="attClass ident">att.staffDef.vis.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Visual domain attributes for staffDef in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.stems.cmn">
         <td class="attClass ident">att.stems.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that describe the properties of stemmed features; that is, chords and
            notes.</td>
      </tr>
      <tr class="u" id="att.tie.log">
         <td class="attClass ident">att.tie.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tieRend">
         <td class="attClass ident">att.tieRend</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that describe the rendition of ties.</td>
      </tr>
      <tr class="u" id="att.tremForm">
         <td class="attClass ident">att.tremForm</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes describing the form of a tremolo.</td>
      </tr>
      <tr class="u" id="att.tremMeasured">
         <td class="attClass ident">att.tremMeasured</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Attributes that describe measured tremolandi.</td>
      </tr>
      <tr class="u" id="att.tuplet.log">
         <td class="attClass ident">att.tuplet.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.tupletSpan.log">
         <td class="attClass ident">att.tupletSpan.log</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mordent.log">
         <td class="attClass ident">att.mordent.log</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ornamentAccid">
         <td class="attClass ident">att.ornamentAccid</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Accidentals associated with ornaments.</td>
      </tr>
      <tr class="u" id="att.ornamPresent">
         <td class="attClass ident">att.ornamPresent</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Attributes for marking the presence of an ornament.</td>
      </tr>
      <tr class="u" id="att.trill.log">
         <td class="attClass ident">att.trill.log</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.turn.log">
         <td class="attClass ident">att.turn.log</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.crit">
         <td class="attClass ident">att.crit</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Attributes common to all elements representing variant readings.</td>
      </tr>
      <tr class="u" id="att.rdg.log">
         <td class="attClass ident">att.rdg.log</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.sp.log">
         <td class="attClass ident">att.sp.log</td>
         <td class="module unchanged">MEI.drama</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.stageDir.log">
         <td class="attClass ident">att.stageDir.log</td>
         <td class="module unchanged">MEI.drama</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.agentIdent">
         <td class="attClass ident">att.agentIdent</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Attributes for the identification of a causative agent.</td>
      </tr>
      <tr class="u" id="att.cpMark.log">
         <td class="attClass ident">att.cpMark.log</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.edit">
         <td class="attClass ident">att.edit</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Attributes describing the nature of an encoded scholarly intervention or
            interpretation.</td>
      </tr>
      <tr class="u" id="att.metaMark.log">
         <td class="attClass ident">att.metaMark.log</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.reasonIdent">
         <td class="attClass ident">att.reasonIdent</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Attributes that identify the reason why an editorial feature is used.</td>
      </tr>
      <tr class="u" id="att.trans">
         <td class="attClass ident">att.trans</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Attributes for elements encoding authorial or scribal intervention when transcribing
            manuscript or similar sources.</td>
      </tr>
      <tr class="u" id="att.extSym.auth">
         <td class="attClass ident">att.extSym.auth</td>
         <td class="module unchanged">MEI.externalsymbols</td>
         <td class="unchanged">Attributes that point to an external symbol authority.</td>
      </tr>
      <tr class="u" id="att.extSym.names">
         <td class="attClass ident">att.extSym.names</td>
         <td class="module unchanged">MEI.externalsymbols</td>
         <td class="unchanged">Attributes that specify names or values taken from an external symbol authority.</td>
      </tr>
      <tr class="u" id="att.extSym">
         <td class="attClass ident">att.extSym</td>
         <td class="module unchanged">MEI.externalsymbols</td>
         <td class="unchanged">Attributes used to associate MEI features with corresponding glyphs in an
            externally-defined standard such as SMuFL.</td>
      </tr>
      <tr class="u" id="att.facsimile">
         <td class="attClass ident">att.facsimile</td>
         <td class="module unchanged">MEI.facsimile</td>
         <td class="unchanged">Attributes that associate a feature corresponding with all or part of an image.</td>
      </tr>
      <tr class="u" id="att.tabular">
         <td class="attClass ident">att.tabular</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Attributes shared by table cells.</td>
      </tr>
      <tr class="u" id="att.fing.log">
         <td class="attClass ident">att.fing.log</td>
         <td class="module unchanged">MEI.fingering</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.fingGrp.log">
         <td class="attClass ident">att.fingGrp.log</td>
         <td class="module unchanged">MEI.fingering</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.geneticState">
         <td class="attClass ident">att.geneticState</td>
         <td class="module unchanged">MEI.genetic</td>
         <td class="unchanged">Attributes that pertain to a genetic state.</td>
      </tr>
      <tr class="u" id="att.accid.ges">
         <td class="attClass ident">att.accid.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.accidental.ges">
         <td class="attClass ident">att.accidental.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes for capturing momentary pitch inflection in the gestural domain.</td>
      </tr>
      <tr class="u" id="att.ambitus.ges">
         <td class="attClass ident">att.ambitus.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambNote.ges">
         <td class="attClass ident">att.ambNote.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.anchoredText.ges">
         <td class="attClass ident">att.anchoredText.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.annot.ges">
         <td class="attClass ident">att.annot.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.arpeg.ges">
         <td class="attClass ident">att.arpeg.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.artic.ges">
         <td class="attClass ident">att.artic.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.articulation.ges">
         <td class="attClass ident">att.articulation.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes describing the method of performance.</td>
      </tr>
      <tr class="u" id="att.attacca.ges">
         <td class="attClass ident">att.attacca.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.attacking">
         <td class="attClass ident">att.attacking</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes whether an element is performed "attacca".</td>
      </tr>
      <tr class="u" id="att.barLine.ges">
         <td class="attClass ident">att.barLine.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.beam.ges">
         <td class="attClass ident">att.beam.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.beamSpan.ges">
         <td class="attClass ident">att.beamSpan.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.beatRpt.ges">
         <td class="attClass ident">att.beatRpt.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.bend.ges">
         <td class="attClass ident">att.bend.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.bracketSpan.ges">
         <td class="attClass ident">att.bracketSpan.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.breath.ges">
         <td class="attClass ident">att.breath.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.bTrem.ges">
         <td class="attClass ident">att.bTrem.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.caesura.ges">
         <td class="attClass ident">att.caesura.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.chord.ges">
         <td class="attClass ident">att.chord.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordDef.ges">
         <td class="attClass ident">att.chordDef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordMember.ges">
         <td class="attClass ident">att.chordMember.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.clef.ges">
         <td class="attClass ident">att.clef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.clefGrp.ges">
         <td class="attClass ident">att.clefGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.cpMark.ges">
         <td class="attClass ident">att.cpMark.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.curve.ges">
         <td class="attClass ident">att.curve.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.custos.ges">
         <td class="attClass ident">att.custos.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mdiv.ges">
         <td class="attClass ident">att.mdiv.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.dir.ges">
         <td class="attClass ident">att.dir.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.dot.ges">
         <td class="attClass ident">att.dot.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.duration.ges">
         <td class="attClass ident">att.duration.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes that record performed duration that differs from a feature’s written
            duration.</td>
      </tr>
      <tr class="u" id="att.dynam.ges">
         <td class="attClass ident">att.dynam.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ending.ges">
         <td class="attClass ident">att.ending.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.episema.ges">
         <td class="attClass ident">att.episema.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.f.ges">
         <td class="attClass ident">att.f.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.fermata.ges">
         <td class="attClass ident">att.fermata.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.fing.ges">
         <td class="attClass ident">att.fing.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.fingGrp.ges">
         <td class="attClass ident">att.fingGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.fTrem.ges">
         <td class="attClass ident">att.fTrem.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.gliss.ges">
         <td class="attClass ident">att.gliss.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.graceGrp.ges">
         <td class="attClass ident">att.graceGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.grpSym.ges">
         <td class="attClass ident">att.grpSym.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.hairpin.ges">
         <td class="attClass ident">att.hairpin.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.halfmRpt.ges">
         <td class="attClass ident">att.halfmRpt.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.harm.ges">
         <td class="attClass ident">att.harm.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.harpPedal.ges">
         <td class="attClass ident">att.harpPedal.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.hispanTick.ges">
         <td class="attClass ident">att.hispanTick.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.instrDef.ges">
         <td class="attClass ident">att.instrDef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.keyAccid.ges">
         <td class="attClass ident">att.keyAccid.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySig.ges">
         <td class="attClass ident">att.keySig.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.layer.ges">
         <td class="attClass ident">att.layer.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.layerDef.ges">
         <td class="attClass ident">att.layerDef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ligature.ges">
         <td class="attClass ident">att.ligature.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.line.ges">
         <td class="attClass ident">att.line.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes for describing the performed components of a line.</td>
      </tr>
      <tr class="u" id="att.liquescent.ges">
         <td class="attClass ident">att.liquescent.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.lv.ges">
         <td class="attClass ident">att.lv.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.lyrics.ges">
         <td class="attClass ident">att.lyrics.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.measure.ges">
         <td class="attClass ident">att.measure.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes. The tstamp.ges and tstamp.real attributes encode the onset
            time of the measure. In reality, this is usually the same as the onset time of the
            first event
            in the measure.</td>
      </tr>
      <tr class="u" id="att.mensur.ges">
         <td class="attClass ident">att.mensur.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.metaMark.ges">
         <td class="attClass ident">att.metaMark.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSig.ges">
         <td class="attClass ident">att.meterSig.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSigGrp.ges">
         <td class="attClass ident">att.meterSigGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.midi.ges">
         <td class="attClass ident">att.midi.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mNum.ges">
         <td class="attClass ident">att.mNum.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mordent.ges">
         <td class="attClass ident">att.mordent.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRest.ges">
         <td class="attClass ident">att.mRest.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt.ges">
         <td class="attClass ident">att.mRpt.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt2.ges">
         <td class="attClass ident">att.mRpt2.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.mSpace.ges">
         <td class="attClass ident">att.mSpace.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRest.ges">
         <td class="attClass ident">att.multiRest.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRpt.ges">
         <td class="attClass ident">att.multiRpt.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.nc.ges">
         <td class="attClass ident">att.nc.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ncGrp.ges">
         <td class="attClass ident">att.ncGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.neume.ges">
         <td class="attClass ident">att.neume.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.note.ges">
         <td class="attClass ident">att.note.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.octave.ges">
         <td class="attClass ident">att.octave.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.oriscus.ges">
         <td class="attClass ident">att.oriscus.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ornam.ges">
         <td class="attClass ident">att.ornam.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.ornamentAccid.ges">
         <td class="attClass ident">att.ornamentAccid.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural accidentals associated with ornaments.</td>
      </tr>
      <tr class="u" id="att.ossia.ges">
         <td class="attClass ident">att.ossia.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.pad.ges">
         <td class="attClass ident">att.pad.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.part.ges">
         <td class="attClass ident">att.part.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.parts.ges">
         <td class="attClass ident">att.parts.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.pb.ges">
         <td class="attClass ident">att.pb.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.pedal.ges">
         <td class="attClass ident">att.pedal.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.phrase.ges">
         <td class="attClass ident">att.phrase.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.pitch.ges">
         <td class="attClass ident">att.pitch.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural attributes about pitch.</td>
      </tr>
      <tr class="u" id="att.plica.ges">
         <td class="attClass ident">att.plica.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes that describe the properties of a plica in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.proport.ges">
         <td class="attClass ident">att.proport.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.quilisma.ges">
         <td class="attClass ident">att.quilisma.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.rdg.ges">
         <td class="attClass ident">att.rdg.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.refrain.ges">
         <td class="attClass ident">att.refrain.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.reh.ges">
         <td class="attClass ident">att.reh.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.repeatMark.ges">
         <td class="attClass ident">att.repeatMark.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.rest.ges">
         <td class="attClass ident">att.rest.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.sb.ges">
         <td class="attClass ident">att.sb.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.score.ges">
         <td class="attClass ident">att.score.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.ges">
         <td class="attClass ident">att.scoreDef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes for scoreDef. The values set in these attributes act as
            score-wide defaults for attributes that are not set in descendant elements. For example,
            the
            grace attribute value here applies to all the grace attribute values in the score
            (or, more
            accurately, until the next  scoreDef  element) without having to
            individually set each note’s grace attribute value. The midi.* attributes function
            as default
            values when creating sounding output. The tune.* attributes provide the capability
            of
            recording a tuning reference pitch.</td>
      </tr>
      <tr class="u" id="att.section.ges">
         <td class="attClass ident">att.section.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.signifLet.ges">
         <td class="attClass ident">att.signifLet.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.slur.ges">
         <td class="attClass ident">att.slur.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.soundLocation">
         <td class="attClass ident">att.soundLocation</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes that locate a sound source within 3-D space.</td>
      </tr>
      <tr class="u" id="att.sp.ges">
         <td class="attClass ident">att.sp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.space.ges">
         <td class="attClass ident">att.space.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.staff.ges">
         <td class="attClass ident">att.staff.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffDef.ges">
         <td class="attClass ident">att.staffDef.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes for staffDef in the CMN repertoire.</td>
      </tr>
      <tr class="u" id="att.staffGrp.ges">
         <td class="attClass ident">att.staffGrp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.stageDir.ges">
         <td class="attClass ident">att.stageDir.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.stem.ges">
         <td class="attClass ident">att.stem.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes that describe the properties of a stem in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.strophicus.ges">
         <td class="attClass ident">att.strophicus.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.syl.ges">
         <td class="attClass ident">att.syl.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.syllable.ges">
         <td class="attClass ident">att.syllable.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.symbol.ges">
         <td class="attClass ident">att.symbol.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.tempo.ges">
         <td class="attClass ident">att.tempo.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.tie.ges">
         <td class="attClass ident">att.tie.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.timestamp.ges">
         <td class="attClass ident">att.timestamp.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes that record a performed (as opposed to notated) time stamp.</td>
      </tr>
      <tr class="u" id="att.timestamp2.ges">
         <td class="attClass ident">att.timestamp2.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Attributes that record a performed (as opposed to notated) time stamp for the end
            of an
            event.</td>
      </tr>
      <tr class="u" id="att.trill.ges">
         <td class="attClass ident">att.trill.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.tuplet.ges">
         <td class="attClass ident">att.tuplet.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.tupletSpan.ges">
         <td class="attClass ident">att.tupletSpan.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.turn.ges">
         <td class="attClass ident">att.turn.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.verse.ges">
         <td class="attClass ident">att.verse.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.volta.ges">
         <td class="attClass ident">att.volta.ges</td>
         <td class="module unchanged">MEI.gestural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordDef.log">
         <td class="attClass ident">att.chordDef.log</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordMember.log">
         <td class="attClass ident">att.chordMember.log</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.f.log">
         <td class="attClass ident">att.f.log</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.harm.log">
         <td class="attClass ident">att.harm.log</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.bifoliumSurfaces">
         <td class="attClass ident">att.bifoliumSurfaces</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that link a bifolium element with a  surface 
            element.</td>
      </tr>
      <tr class="u" id="att.foliumSurfaces">
         <td class="attClass ident">att.foliumSurfaces</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that link a folium element with a  surface  element.</td>
      </tr>
      <tr class="u" id="att.perfRes">
         <td class="attClass ident">att.perfRes</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that define the characteristics and components of the performance resource.</td>
      </tr>
      <tr class="u" id="att.perfRes.basic">
         <td class="attClass ident">att.perfRes.basic</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that define the characteristics and components of the performance resource
            or a performance resource list.</td>
      </tr>
      <tr class="u" id="att.adlibitum">
         <td class="attClass ident">att.adlibitum</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that describe a performance resource as ad libitum (optional).</td>
      </tr>
      <tr class="u" id="att.recordType">
         <td class="attClass ident">att.recordType</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that define the characteristics and components of the bibliographic
            description.</td>
      </tr>
      <tr class="u" id="att.regularMethod">
         <td class="attClass ident">att.regularMethod</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Attributes that describe correction and normalization methods.</td>
      </tr>
      <tr class="u" id="att.lyrics.log">
         <td class="attClass ident">att.lyrics.log</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.refrain.log">
         <td class="attClass ident">att.refrain.log</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Logical domain attributes. The n attribute should be used for verse numbers. Numbers
            need
            not be consecutive; they may also be expressed as ranges,  e.g. , 2-3,6.</td>
      </tr>
      <tr class="u" id="att.verse.log">
         <td class="attClass ident">att.verse.log</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Logical domain attributes. The n attribute should be used for verse numbers. Numbers
            need
            not be consecutive; they may also be expressed as ranges,  e.g. , 2-3,6.</td>
      </tr>
      <tr class="u" id="att.volta.log">
         <td class="attClass ident">att.volta.log</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Logical domain attributes. The n attribute should be used for repetition numbers.
            Numbers
            need not be consecutive; they may also be expressed as ranges,  e.g. , 2-3,6.</td>
      </tr>
      <tr class="u" id="att.duration.quality">
         <td class="attClass ident">att.duration.quality</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Attribute that expresses duration for a given mensural note symbol.</td>
      </tr>
      <tr class="u" id="att.ligature.log">
         <td class="attClass ident">att.ligature.log</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.mensural.log">
         <td class="attClass ident">att.mensural.log</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the logical
            domain related to mensuration. The tempus, prolatio, modusmaior, and modusminor attributes
            (from the att.mensural.shared class) specify the relationship between the four principle
            levels of note value,  i.e. , the long, breve, semibreve and minim, in mensural notation.
            Modusminor describes the long-breve relationship, while tempus describes the breve-semibreve,
            and prolatio the semibreve-minim relationship, respectively. Modusmaior is for the
            maxima-long
            relationship. The proport.* attributes describe augmentation or diminution of the
            normal value
            of the notes in mensural notation.</td>
      </tr>
      <tr class="u" id="att.mensural.shared">
         <td class="attClass ident">att.mensural.shared</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Shared attributes in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.note.anl.mensural">
         <td class="attClass ident">att.note.anl.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Analytical domain attributes in the Mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.note.ges.mensural">
         <td class="attClass ident">att.note.ges.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Gestural domain attributes in the Mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.note.log.mensural">
         <td class="attClass ident">att.note.log.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes in the Mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.note.vis.mensural">
         <td class="attClass ident">att.note.vis.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Visual domain attributes in the Mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.plica.log">
         <td class="attClass ident">att.plica.log</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes that describe the properties of a plica in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.proport.log">
         <td class="attClass ident">att.proport.log</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes. These attributes describe augmentation or diminution of
            the
            normal value of the notes in mensural notation as a ratio.</td>
      </tr>
      <tr class="u" id="att.rest.ges.mensural">
         <td class="attClass ident">att.rest.ges.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Gestural domain attributes.</td>
      </tr>
      <tr class="u" id="att.rest.vis.mensural">
         <td class="attClass ident">att.rest.vis.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.log.mensural">
         <td class="attClass ident">att.scoreDef.log.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes for a score in the mensural repertoire. The values set in
            these
            attributes act as score-wide defaults for attributes that are not set in descendant
            elements.</td>
      </tr>
      <tr class="u" id="att.scoreDef.vis.mensural">
         <td class="attClass ident">att.scoreDef.vis.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Visual domain attributes for scoreDef in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.staffDef.log.mensural">
         <td class="attClass ident">att.staffDef.log.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes for staffDef in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.staffDef.vis.mensural">
         <td class="attClass ident">att.staffDef.vis.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Visual domain attributes for the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.stem.log">
         <td class="attClass ident">att.stem.log</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical domain attributes that describe the properties of a stem in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.stems.mensural">
         <td class="attClass ident">att.stems.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Attributes that describe the properties of stemmed features specific to mensural repertoires.</td>
      </tr>
      <tr class="u" id="att.channelized">
         <td class="attClass ident">att.channelized</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record MIDI channel information.</td>
      </tr>
      <tr class="u" id="att.instrDef.log">
         <td class="attClass ident">att.instrDef.log</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.instrumentIdent">
         <td class="attClass ident">att.instrumentIdent</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes which identify a MIDI instrument.</td>
      </tr>
      <tr class="u" id="att.midi.event">
         <td class="attClass ident">att.midi.event</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes common to MIDI events.</td>
      </tr>
      <tr class="u" id="att.midi.log">
         <td class="attClass ident">att.midi.log</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.midiInstrument">
         <td class="attClass ident">att.midiInstrument</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record MIDI instrument information.</td>
      </tr>
      <tr class="u" id="att.midiNumber">
         <td class="attClass ident">att.midiNumber</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record MIDI numbers.</td>
      </tr>
      <tr class="u" id="att.midiTempo">
         <td class="attClass ident">att.midiTempo</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record MIDI tempo information.</td>
      </tr>
      <tr class="u" id="att.midiValue">
         <td class="attClass ident">att.midiValue</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record MIDI values.</td>
      </tr>
      <tr class="u" id="att.midiValue2">
         <td class="attClass ident">att.midiValue2</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record terminal MIDI values.</td>
      </tr>
      <tr class="u" id="att.midiVelocity">
         <td class="attClass ident">att.midiVelocity</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">MIDI attributes pertaining to key velocity.</td>
      </tr>
      <tr class="u" id="att.timeBase">
         <td class="attClass ident">att.timeBase</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Attributes that record time-base information.</td>
      </tr>
      <tr class="u" id="att.componentType">
         <td class="attClass ident">att.componentType</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Attributes that express the relationship between a component and its host.</td>
      </tr>
      <tr class="u" id="att.foliation.scheme">
         <td class="attClass ident">att.foliation.scheme</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Attributes that describe foliation schemes.</td>
      </tr>
      <tr class="u" id="att.divLine.log">
         <td class="attClass ident">att.divLine.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.episema.log">
         <td class="attClass ident">att.episema.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.hispanTick.log">
         <td class="attClass ident">att.hispanTick.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.liquescent.log">
         <td class="attClass ident">att.liquescent.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.nc.log">
         <td class="attClass ident">att.nc.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ncForm">
         <td class="attClass ident">att.ncForm</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Attributes that record visual details of neume notation.</td>
      </tr>
      <tr class="u" id="att.ncGrp.log">
         <td class="attClass ident">att.ncGrp.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.neume.log">
         <td class="attClass ident">att.neume.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.neumeType">
         <td class="attClass ident">att.neumeType</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Attributes that specify the type of neumes.</td>
      </tr>
      <tr class="u" id="att.oriscus.log">
         <td class="attClass ident">att.oriscus.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.quilisma.log">
         <td class="attClass ident">att.quilisma.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.signifLet.log">
         <td class="attClass ident">att.signifLet.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.strophicus.log">
         <td class="attClass ident">att.strophicus.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.syllable.log">
         <td class="attClass ident">att.syllable.log</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.alignment">
         <td class="attClass ident">att.alignment</td>
         <td class="module unchanged">MEI.performance</td>
         <td class="unchanged">Temporal alignment attributes.</td>
      </tr>
      <tr class="u" id="att.accid.log">
         <td class="attClass ident">att.accid.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.accidental">
         <td class="attClass ident">att.accidental</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for capturing momentary pitch inflection.</td>
      </tr>
      <tr class="u" id="att.ambitus.log">
         <td class="attClass ident">att.ambitus.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambNote.log">
         <td class="attClass ident">att.ambNote.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.annot.log">
         <td class="attClass ident">att.annot.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes for annot. Values for the type attribute can be taken from
            any
            convenient typology of annotation suitable to the work in hand;  e.g. , annotation,
            gloss,
            citation, digression, preliminary, temporary, etc.</td>
      </tr>
      <tr class="u" id="att.artic.log">
         <td class="attClass ident">att.artic.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.articulation">
         <td class="attClass ident">att.articulation</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for capturing the written signs that describe the method of performance.</td>
      </tr>
      <tr class="u" id="att.attacca.log">
         <td class="attClass ident">att.attacca.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.audience">
         <td class="attClass ident">att.audience</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe the intended audience.</td>
      </tr>
      <tr class="u" id="att.augmentDots">
         <td class="attClass ident">att.augmentDots</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the number of dots of augmentation.</td>
      </tr>
      <tr class="u" id="att.authorized">
         <td class="attClass ident">att.authorized</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe the source of a controlled value.</td>
      </tr>
      <tr class="u" id="att.barLine.log">
         <td class="attClass ident">att.barLine.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.barring">
         <td class="attClass ident">att.barring</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture the placement of bar lines.</td>
      </tr>
      <tr class="u" id="att.basic">
         <td class="attClass ident">att.basic</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that form the basis of the att.common class.</td>
      </tr>
      <tr class="u" id="att.bibl">
         <td class="attClass ident">att.bibl</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Bibliographic attributes.</td>
      </tr>
      <tr class="u" id="att.caesura.log">
         <td class="attClass ident">att.caesura.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.calendared">
         <td class="attClass ident">att.calendared</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that indicate the calendar system of a date or other datable element.</td>
      </tr>
      <tr class="u" id="att.canonical">
         <td class="attClass ident">att.canonical</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that can be used to associate a representation such as a name or title
            with
            canonical information about the object being named or referenced.</td>
      </tr>
      <tr class="u" id="att.chord.log">
         <td class="attClass ident">att.chord.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes for chord. The artic, dots, and dur attributes encode the
            written articulations, augmentation dots, and duration values. The beam, fermata,
            lv, slur,
            syl, tie, and tuplet attributes may be used to indicate the attachment of these things
            to this
            chord. If visual information about these things needs to be recorded, then either
            the elements
            corresponding to these attributes or the attributes available in the att.vis.chord
            class
            should be employed.</td>
      </tr>
      <tr class="u" id="att.classed">
         <td class="attClass ident">att.classed</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes which can be used to classify features.</td>
      </tr>
      <tr class="u" id="att.clef.log">
         <td class="attClass ident">att.clef.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.cleffing.log">
         <td class="attClass ident">att.cleffing.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the logical
            domain related to clefs.</td>
      </tr>
      <tr class="u" id="att.clefGrp.log">
         <td class="attClass ident">att.clefGrp.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.clefShape">
         <td class="attClass ident">att.clefShape</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the shape of a clef.</td>
      </tr>
      <tr class="u" id="att.color">
         <td class="attClass ident">att.color</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Visual color attributes.</td>
      </tr>
      <tr class="u" id="att.coloration">
         <td class="attClass ident">att.coloration</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Indication of coloration.</td>
      </tr>
      <tr class="u" id="att.common">
         <td class="attClass ident">att.common</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes common to many elements.</td>
      </tr>
      <tr class="u" id="att.contemporary">
         <td class="attClass ident">att.contemporary</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes specifying whether a feature is contemporary or historical.</td>
      </tr>
      <tr class="u" id="att.controlEvent">
         <td class="attClass ident">att.controlEvent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes shared by events which rely on other events for their existence. For example,
            a
            slur/phrase marking must be drawn between or over a group of notes. The slur is therefore
            a
            control event.</td>
      </tr>
      <tr class="u" id="att.coordinated">
         <td class="attClass ident">att.coordinated</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">This attribute class records the position of a feature within a two-dimensional coordinate
            system.</td>
      </tr>
      <tr class="u" id="att.coordinated.ul">
         <td class="attClass ident">att.coordinated.ul</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">This attribute class records the upper left position of a feature within a two-dimensional
            coordinate
            system.</td>
      </tr>
      <tr class="u" id="att.cue">
         <td class="attClass ident">att.cue</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe "cue-ness".</td>
      </tr>
      <tr class="u" id="att.curvature">
         <td class="attClass ident">att.curvature</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe curvature.</td>
      </tr>
      <tr class="u" id="att.custos.log">
         <td class="attClass ident">att.custos.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.datable">
         <td class="attClass ident">att.datable</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes common to dates.</td>
      </tr>
      <tr class="u" id="att.dataPointing">
         <td class="attClass ident">att.dataPointing</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for linking metadata to data.</td>
      </tr>
      <tr class="u" id="att.mdiv.log">
         <td class="attClass ident">att.mdiv.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.metadataPointing">
         <td class="attClass ident">att.metadataPointing</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides attributes for elements which may be associated with particular contextual
            elements within the header.</td>
      </tr>
      <tr class="u" id="att.dimensions">
         <td class="attClass ident">att.dimensions</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture the dimensions of an entity.</td>
      </tr>
      <tr class="u" id="att.dir.log">
         <td class="attClass ident">att.dir.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.distances">
         <td class="attClass ident">att.distances</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe distance from the staff.</td>
      </tr>
      <tr class="u" id="att.dot.log">
         <td class="attClass ident">att.dot.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.duration.additive">
         <td class="attClass ident">att.duration.additive</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that permit total duration to be represented by multiple values.</td>
      </tr>
      <tr class="u" id="att.duration.default">
         <td class="attClass ident">att.duration.default</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that provide a durational default value.</td>
      </tr>
      <tr class="u" id="att.duration.log">
         <td class="attClass ident">att.duration.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that express duration in musical terms.</td>
      </tr>
      <tr class="u" id="att.duration.ratio">
         <td class="attClass ident">att.duration.ratio</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe duration as a ratio.</td>
      </tr>
      <tr class="u" id="att.dynam.log">
         <td class="attClass ident">att.dynam.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.enclosingChars">
         <td class="attClass ident">att.enclosingChars</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture characters used to enclose symbols having a cautionary or
            editorial function.</td>
      </tr>
      <tr class="u" id="att.ending.log">
         <td class="attClass ident">att.ending.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.endings">
         <td class="attClass ident">att.endings</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record ending style information</td>
      </tr>
      <tr class="u" id="att.event">
         <td class="attClass ident">att.event</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that apply to all written events,  e.g. , note, chord, rest, etc.</td>
      </tr>
      <tr class="u" id="att.evidence">
         <td class="attClass ident">att.evidence</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes describing the support for and the certainty of an assertion.</td>
      </tr>
      <tr class="u" id="att.extender">
         <td class="attClass ident">att.extender</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe extension symbols, typically lines. Members of this class
            are
            also typically members of the att.lineRend class.</td>
      </tr>
      <tr class="u" id="att.extent">
         <td class="attClass ident">att.extent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides attributes for describing the size of an entity.</td>
      </tr>
      <tr class="u" id="att.fermataPresent">
         <td class="attClass ident">att.fermataPresent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes indicating the attachment of a fermata to the feature.</td>
      </tr>
      <tr class="u" id="att.filing">
         <td class="attClass ident">att.filing</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that deal with string filing characteristics.</td>
      </tr>
      <tr class="u" id="att.formework">
         <td class="attClass ident">att.formework</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the function (i.e., placement) of forme work elements.</td>
      </tr>
      <tr class="u" id="att.grpSym.log">
         <td class="attClass ident">att.grpSym.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.handIdent">
         <td class="attClass ident">att.handIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes which identify a document hand.</td>
      </tr>
      <tr class="u" id="att.height">
         <td class="attClass ident">att.height</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe vertical size.</td>
      </tr>
      <tr class="u" id="att.horizontalAlign">
         <td class="attClass ident">att.horizontalAlign</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record horizontal alignment.</td>
      </tr>
      <tr class="u" id="att.id">
         <td class="attClass ident">att.id</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that uniquely identify an element.</td>
      </tr>
      <tr class="u" id="att.internetMedia">
         <td class="attClass ident">att.internetMedia</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes which record the type of an electronic resource.</td>
      </tr>
      <tr class="u" id="att.joined">
         <td class="attClass ident">att.joined</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes indicating that elements are semantically linked; that is, while the parts
            are
            encoded separately, together they may be thought of as a single intellectual object.</td>
      </tr>
      <tr class="u" id="att.keyAccid.log">
         <td class="attClass ident">att.keyAccid.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.keyMode">
         <td class="attClass ident">att.keyMode</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for describing key mode.</td>
      </tr>
      <tr class="u" id="att.keySig.log">
         <td class="attClass ident">att.keySig.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySigDefault.log">
         <td class="attClass ident">att.keySigDefault.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the logical
            domain that are related to key signatures.</td>
      </tr>
      <tr class="u" id="att.labelled">
         <td class="attClass ident">att.labelled</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged"></td>
      </tr>
      <tr class="u" id="att.lang">
         <td class="attClass ident">att.lang</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Language attributes common to text elements.</td>
      </tr>
      <tr class="u" id="att.layer.log">
         <td class="attClass ident">att.layer.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.layerDef.log">
         <td class="attClass ident">att.layerDef.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.layerIdent">
         <td class="attClass ident">att.layerIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify the layer to which a feature applies.</td>
      </tr>
      <tr class="u" id="att.lineLoc">
         <td class="attClass ident">att.lineLoc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for identifying the staff line with which a feature is associated.</td>
      </tr>
      <tr class="u" id="att.lineRend">
         <td class="attClass ident">att.lineRend</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the visual rendition of lines.</td>
      </tr>
      <tr class="u" id="att.lineRend.base">
         <td class="attClass ident">att.lineRend.base</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the basic visual rendition of lines.</td>
      </tr>
      <tr class="u" id="att.linking">
         <td class="attClass ident">att.linking</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that specify element-to-element relationships.</td>
      </tr>
      <tr class="u" id="att.lyricStyle">
         <td class="attClass ident">att.lyricStyle</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe default typography of lyrics.</td>
      </tr>
      <tr class="u" id="att.measurement">
         <td class="attClass ident">att.measurement</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the unit of measurement in which a value is expressed.</td>
      </tr>
      <tr class="u" id="att.measureNumbers">
         <td class="attClass ident">att.measureNumbers</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes pertaining to measure numbers</td>
      </tr>
      <tr class="u" id="att.mediaBounds">
         <td class="attClass ident">att.mediaBounds</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that establish the boundaries of a media object.</td>
      </tr>
      <tr class="u" id="att.medium">
         <td class="attClass ident">att.medium</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes describing a writing medium, such as pencil or ink.</td>
      </tr>
      <tr class="u" id="att.meiVersion">
         <td class="attClass ident">att.meiVersion</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record the version of MEI in use.</td>
      </tr>
      <tr class="u" id="att.mensur.log">
         <td class="attClass ident">att.mensur.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterConformance">
         <td class="attClass ident">att.meterConformance</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that provide information about a structure’s conformance to the prevailing
            meter.</td>
      </tr>
      <tr class="u" id="att.meterConformance.bar">
         <td class="attClass ident">att.meterConformance.bar</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that provide information about a measure’s conformance to the prevailing
            meter.</td>
      </tr>
      <tr class="u" id="att.meterSig.log">
         <td class="attClass ident">att.meterSig.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSigDefault.log">
         <td class="attClass ident">att.meterSigDefault.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the logical
            domain related to meter signature.</td>
      </tr>
      <tr class="u" id="att.mmTempo">
         <td class="attClass ident">att.mmTempo</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record tempo in terms of beats per minute.</td>
      </tr>
      <tr class="u" id="att.multinumMeasures">
         <td class="attClass ident">att.multinumMeasures</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that indicate programmatic numbering.</td>
      </tr>
      <tr class="u" id="att.name">
         <td class="attClass ident">att.name</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes shared by names.</td>
      </tr>
      <tr class="u" id="att.nInteger">
         <td class="attClass ident">att.nInteger</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes used to supply an integer number designation for an element.</td>
      </tr>
      <tr class="u" id="att.nNumberLike">
         <td class="attClass ident">att.nNumberLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes used to supply a number-like designation for an element.</td>
      </tr>
      <tr class="u" id="att.notationStyle">
         <td class="attClass ident">att.notationStyle</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture music font name and size.</td>
      </tr>
      <tr class="u" id="att.note.log">
         <td class="attClass ident">att.note.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.noteHeads">
         <td class="attClass ident">att.noteHeads</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes pertaining to the notehead part of a note.</td>
      </tr>
      <tr class="u" id="att.octave">
         <td class="attClass ident">att.octave</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record written octave.</td>
      </tr>
      <tr class="u" id="att.octaveDefault">
         <td class="attClass ident">att.octaveDefault</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record a default value for octave.</td>
      </tr>
      <tr class="u" id="att.octaveDisplacement">
         <td class="attClass ident">att.octaveDisplacement</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes describing the amount and direction of octave displacement.</td>
      </tr>
      <tr class="u" id="att.oneLineStaff">
         <td class="attClass ident">att.oneLineStaff</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record placement of notes on a single-line staff.</td>
      </tr>
      <tr class="u" id="att.optimization">
         <td class="attClass ident">att.optimization</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes pertaining to layout optimization.</td>
      </tr>
      <tr class="u" id="att.origin.layerIdent">
         <td class="attClass ident">att.origin.layerIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify the layer associated with a distant feature.</td>
      </tr>
      <tr class="u" id="att.origin.staffIdent">
         <td class="attClass ident">att.origin.staffIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for identifying the staff associated with a distant feature.</td>
      </tr>
      <tr class="u" id="att.origin.startEndId">
         <td class="attClass ident">att.origin.startEndId</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes recording the identifiers of the first and last elements of a sequence
            of
            distant elements.</td>
      </tr>
      <tr class="u" id="att.origin.timestamp.log">
         <td class="attClass ident">att.origin.timestamp.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify a musical range in terms of musical time.</td>
      </tr>
      <tr class="u" id="att.ornam.log">
         <td class="attClass ident">att.ornam.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pad.log">
         <td class="attClass ident">att.pad.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pages">
         <td class="attClass ident">att.pages</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record page-level layout information.</td>
      </tr>
      <tr class="u" id="att.part.log">
         <td class="attClass ident">att.part.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.partIdent">
         <td class="attClass ident">att.partIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for identifying the part in which the current feature appears.</td>
      </tr>
      <tr class="u" id="att.parts.log">
         <td class="attClass ident">att.parts.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pb.log">
         <td class="attClass ident">att.pb.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.phrase.log">
         <td class="attClass ident">att.phrase.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.pitch">
         <td class="attClass ident">att.pitch</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record written pitch name.</td>
      </tr>
      <tr class="u" id="att.pitched">
         <td class="attClass ident">att.pitched</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record written pitch name and octave number.</td>
      </tr>
      <tr class="u" id="att.placementOnStaff">
         <td class="attClass ident">att.placementOnStaff</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes capturing placement on a staff.</td>
      </tr>
      <tr class="u" id="att.placementRelEvent">
         <td class="attClass ident">att.placementRelEvent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes capturing placement information with respect to an event.</td>
      </tr>
      <tr class="u" id="att.placementRelStaff">
         <td class="attClass ident">att.placementRelStaff</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes capturing placement information with respect to the staff.</td>
      </tr>
      <tr class="u" id="att.plist">
         <td class="attClass ident">att.plist</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes listing the active participants in a user-defined collection.</td>
      </tr>
      <tr class="u" id="att.pointing">
         <td class="attClass ident">att.pointing</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes common to all pointing/linking elements.</td>
      </tr>
      <tr class="u" id="att.quantity">
         <td class="attClass ident">att.quantity</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that specify a measurement in numerical terms.</td>
      </tr>
      <tr class="u" id="att.ranging">
         <td class="attClass ident">att.ranging</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups attributes that describe a numerical range.</td>
      </tr>
      <tr class="u" id="att.repeatMark.log">
         <td class="attClass ident">att.repeatMark.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.responsibility">
         <td class="attClass ident">att.responsibility</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes capturing information regarding responsibility for some aspect of the text's
            creation, transcription, editing, or encoding.</td>
      </tr>
      <tr class="u" id="att.rest.log">
         <td class="attClass ident">att.rest.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.restduration.log">
         <td class="attClass ident">att.restduration.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that express duration of rests in musical terms.</td>
      </tr>
      <tr class="u" id="att.sb.log">
         <td class="attClass ident">att.sb.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.scalable">
         <td class="attClass ident">att.scalable</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe relative size.</td>
      </tr>
      <tr class="u" id="att.score.log">
         <td class="attClass ident">att.score.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.scoreDef.log">
         <td class="attClass ident">att.scoreDef.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes for scoreDef in the CMN repertoire. The values set in these
            attributes act as score-wide defaults for attributes that are not set in descendant
            elements.</td>
      </tr>
      <tr class="u" id="att.section.log">
         <td class="attClass ident">att.section.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.sequence">
         <td class="attClass ident">att.sequence</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe order within a collection of features.</td>
      </tr>
      <tr class="u" id="att.slashCount">
         <td class="attClass ident">att.slashCount</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for recording the number of slashes that accompany a feature.</td>
      </tr>
      <tr class="u" id="att.slurPresent">
         <td class="attClass ident">att.slurPresent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for marking the presence of a slur.</td>
      </tr>
      <tr class="u" id="att.source">
         <td class="attClass ident">att.source</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes common to elements that may refer to a source.</td>
      </tr>
      <tr class="u" id="att.space.log">
         <td class="attClass ident">att.space.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.spacing">
         <td class="attClass ident">att.spacing</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture notation spacing information.</td>
      </tr>
      <tr class="u" id="att.staff.log">
         <td class="attClass ident">att.staff.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffDef.log">
         <td class="attClass ident">att.staffDef.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes for staffDef.</td>
      </tr>
      <tr class="u" id="att.staffGroupingSym">
         <td class="attClass ident">att.staffGroupingSym</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe the symbol used to group a set of staves.</td>
      </tr>
      <tr class="u" id="att.staffGrp.log">
         <td class="attClass ident">att.staffGrp.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffIdent">
         <td class="attClass ident">att.staffIdent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for identifying the staff associated with the current feature.</td>
      </tr>
      <tr class="u" id="att.staffItems">
         <td class="attClass ident">att.staffItems</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe items printed near (above, below, or between) staves</td>
      </tr>
      <tr class="u" id="att.staffLoc">
         <td class="attClass ident">att.staffLoc</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify location on a staff in terms of lines and spaces.</td>
      </tr>
      <tr class="u" id="att.staffLoc.pitched">
         <td class="attClass ident">att.staffLoc.pitched</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify location on a staff in terms of pitch and octave.</td>
      </tr>
      <tr class="u" id="att.startEndId">
         <td class="attClass ident">att.startEndId</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes recording the identifiers of the first and last elements of a sequence
            of
            elements to which the current element is associated.</td>
      </tr>
      <tr class="u" id="att.startId">
         <td class="attClass ident">att.startId</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that identify a relative starting point.</td>
      </tr>
      <tr class="u" id="att.stems">
         <td class="attClass ident">att.stems</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe the properties of stemmed features; that is, chords and
            notes.</td>
      </tr>
      <tr class="u" id="att.syl.log">
         <td class="attClass ident">att.syl.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.sylText">
         <td class="attClass ident">att.sylText</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that hold associated sung text syllables.</td>
      </tr>
      <tr class="u" id="att.symbol.log">
         <td class="attClass ident">att.symbol.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.systems">
         <td class="attClass ident">att.systems</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that capture system layout information.</td>
      </tr>
      <tr class="u" id="att.targetEval">
         <td class="attClass ident">att.targetEval</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that deal with resolution of values in plist or target attributes.</td>
      </tr>
      <tr class="u" id="att.tempo.log">
         <td class="attClass ident">att.tempo.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.textRendition">
         <td class="attClass ident">att.textRendition</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record renditional characteristics.</td>
      </tr>
      <tr class="u" id="att.textStyle">
         <td class="attClass ident">att.textStyle</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe default text typography.</td>
      </tr>
      <tr class="u" id="att.tiePresent">
         <td class="attClass ident">att.tiePresent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that indicate the presence of a tie.</td>
      </tr>
      <tr class="u" id="att.timestamp.log">
         <td class="attClass ident">att.timestamp.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record a time stamp in terms of musical time,  i.e. , beats[.fractional
            beat
            part].</td>
      </tr>
      <tr class="u" id="att.timestamp2.log">
         <td class="attClass ident">att.timestamp2.log</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record a time stamp for the end of an event in terms of musical
            time.</td>
      </tr>
      <tr class="u" id="att.transposition">
         <td class="attClass ident">att.transposition</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe transposition.</td>
      </tr>
      <tr class="u" id="att.tuning">
         <td class="attClass ident">att.tuning</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe tuning.</td>
      </tr>
      <tr class="u" id="att.tupletPresent">
         <td class="attClass ident">att.tupletPresent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes for indicating the presence of a tuplet.</td>
      </tr>
      <tr class="u" id="att.typed">
         <td class="attClass ident">att.typed</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes which can be used to classify features.</td>
      </tr>
      <tr class="u" id="att.typography">
         <td class="attClass ident">att.typography</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Typographical attributes.</td>
      </tr>
      <tr class="u" id="att.verticalAlign">
         <td class="attClass ident">att.verticalAlign</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record vertical alignment.</td>
      </tr>
      <tr class="u" id="att.verticalGroup">
         <td class="attClass ident">att.verticalGroup</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that record grouping of vertically aligned elements.</td>
      </tr>
      <tr class="u" id="att.visibility">
         <td class="attClass ident">att.visibility</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes describing whether a feature should be displayed.</td>
      </tr>
      <tr class="u" id="att.visualOffset">
         <td class="attClass ident">att.visualOffset</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Visual offset attributes. Some items may have their location recorded in terms of
            offsets
            from their programmatically-determined location. The ho attribute records the horizontal
            offset while vo records the vertical. The to attribute holds a timestamp offset, the
            most
            common use of which is as an alternative to the ho attribute.</td>
      </tr>
      <tr class="u" id="att.visualOffset.ho">
         <td class="attClass ident">att.visualOffset.ho</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Horizontal offset attributes.</td>
      </tr>
      <tr class="u" id="att.visualOffset.to">
         <td class="attClass ident">att.visualOffset.to</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Horizontal offset attributes specified in terms of time.</td>
      </tr>
      <tr class="u" id="att.visualOffset.vo">
         <td class="attClass ident">att.visualOffset.vo</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Vertical offset attributes.</td>
      </tr>
      <tr class="u" id="att.visualOffset2">
         <td class="attClass ident">att.visualOffset2</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Visual offset attributes. Some items may have their location recorded in terms of
            pairs of
            offsets from their programmatically-determined location. The startho and endho attributes
            record the horizontal offsets of the start and end points of the item, respectively.
            Similarly, the startvo and endvo attributes record the vertical offsets of the start
            and end
            points of the item. The startto and endto attributes hold timestamp offsets, the most
            common
            use of which is as alternatives to the ho attributes.</td>
      </tr>
      <tr class="u" id="att.visualOffset2.ho">
         <td class="attClass ident">att.visualOffset2.ho</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Horizontal offset requiring a pair of attributes.</td>
      </tr>
      <tr class="u" id="att.visualOffset2.to">
         <td class="attClass ident">att.visualOffset2.to</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Horizontal offset attributes requiring a pair of attributes specified in terms of
            time.</td>
      </tr>
      <tr class="u" id="att.visualOffset2.vo">
         <td class="attClass ident">att.visualOffset2.vo</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Vertical offset attributes requiring a pair of attributes.</td>
      </tr>
      <tr class="u" id="att.voltaGroupingSym">
         <td class="attClass ident">att.voltaGroupingSym</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe the symbol used to group volta elements.</td>
      </tr>
      <tr class="u" id="att.whitespace">
         <td class="attClass ident">att.whitespace</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that address whitespace processing.</td>
      </tr>
      <tr class="u" id="att.width">
         <td class="attClass ident">att.width</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Attributes that describe horizontal size.</td>
      </tr>
      <tr class="u" id="att.xy">
         <td class="attClass ident">att.xy</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Output coordinate attributes. Some elements may have their exact rendered *output*
            coordinates recorded. x and y attributes indicate where to place the rendered output.
            Recording the coordinates of a feature in a facsimile requires the use of the facs
            attribute.</td>
      </tr>
      <tr class="u" id="att.xy2">
         <td class="attClass ident">att.xy2</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Output coordinate attributes. Some elements may need 2 coordinate pairs to record
            their
            rendered *output* coordinates. The attributes indicate where to place the rendered
            output.
            Recording the coordinates of a feature in a facsimile requires the use of the facs
            attribute.</td>
      </tr>
      <tr class="u" id="att.stringtab.position">
         <td class="attClass ident">att.stringtab.position</td>
         <td class="module unchanged">MEI.stringtab</td>
         <td class="unchanged">String tablature position information.</td>
      </tr>
      <tr class="u" id="att.altSym">
         <td class="attClass ident">att.altSym</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Attributes supplying pointers to user-defined symbols.</td>
      </tr>
      <tr class="u" id="att.anchoredText.log">
         <td class="attClass ident">att.anchoredText.log</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.curve.log">
         <td class="attClass ident">att.curve.log</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Logical domain attributes.</td>
      </tr>
      <tr class="u" id="att.line.log">
         <td class="attClass ident">att.line.log</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Attributes for describing the logical behavior of a line.</td>
      </tr>
      <tr class="u" id="att.accid.vis">
         <td class="attClass ident">att.accid.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambitus.vis">
         <td class="attClass ident">att.ambitus.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ambNote.vis">
         <td class="attClass ident">att.ambNote.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.anchoredText.vis">
         <td class="attClass ident">att.anchoredText.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.annot.vis">
         <td class="attClass ident">att.annot.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.arpeg.vis">
         <td class="attClass ident">att.arpeg.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.artic.vis">
         <td class="attClass ident">att.artic.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.barLine.vis">
         <td class="attClass ident">att.barLine.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.beam.vis">
         <td class="attClass ident">att.beam.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.beaming.vis">
         <td class="attClass ident">att.beaming.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Used by layerDef, staffDef, and scoreDef to provide default values for attributes
            in the
            visual domain related to beaming.</td>
      </tr>
      <tr class="u" id="att.beamSpan.vis">
         <td class="attClass ident">att.beamSpan.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.beatRpt.vis">
         <td class="attClass ident">att.beatRpt.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.bracketSpan.vis">
         <td class="attClass ident">att.bracketSpan.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.bTrem.vis">
         <td class="attClass ident">att.bTrem.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.chord.vis">
         <td class="attClass ident">att.chord.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes for chord. The slur, slur.dir, slur.rend, tie, tie.dir, and
            tie.rend attributes here are syntactic sugar for these attributes on each of the chord's
            individual notes. The values here apply to all the notes in the chord. If some notes
            are
            slurred or tied while others aren't, then the individual note attributes must be used.</td>
      </tr>
      <tr class="u" id="att.chordDef.vis">
         <td class="attClass ident">att.chordDef.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.chordMember.vis">
         <td class="attClass ident">att.chordMember.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.clef.vis">
         <td class="attClass ident">att.clef.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.cleffing.vis">
         <td class="attClass ident">att.cleffing.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the visual
            domain related to clefs.</td>
      </tr>
      <tr class="u" id="att.clefGrp.vis">
         <td class="attClass ident">att.clefGrp.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.curvatureDirection">
         <td class="attClass ident">att.curvatureDirection</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Attributes describing the direction of curvature.</td>
      </tr>
      <tr class="u" id="att.curve.vis">
         <td class="attClass ident">att.curve.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.custos.vis">
         <td class="attClass ident">att.custos.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mdiv.vis">
         <td class="attClass ident">att.mdiv.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.dot.vis">
         <td class="attClass ident">att.dot.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ending.vis">
         <td class="attClass ident">att.ending.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.episema.vis">
         <td class="attClass ident">att.episema.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.fTrem.vis">
         <td class="attClass ident">att.fTrem.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.gliss.vis">
         <td class="attClass ident">att.gliss.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.graceGrp.vis">
         <td class="attClass ident">att.graceGrp.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.guitarGrid.vis">
         <td class="attClass ident">att.guitarGrid.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes</td>
      </tr>
      <tr class="u" id="att.grpSym.vis">
         <td class="attClass ident">att.grpSym.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.hairpin.vis">
         <td class="attClass ident">att.hairpin.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes. The startho and startvo attributes record the horizontal
            and
            vertical offsets of the left end, endho and endvo record the horizontal and vertical
            offsets
            of the right end, and the opening attribute records the width of the opening in staff
            inter-line units. The x and y attributes give the absolute coordinates of the left
            end point,
            and x2 and y2 the right end point, of an imaginary line that defines the length of
            the hairpin
            and horizontally bifurcates it. The so-called "pitch" of hairpin may be controlled
            by use of
            the startho, endho, startvo, and endvo attributes, while the placement of the entire
            rendered
            mark may be controlled by use of the ho and vo attributes.</td>
      </tr>
      <tr class="u" id="att.halfmRpt.vis">
         <td class="attClass ident">att.halfmRpt.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.hispanTick.vis">
         <td class="attClass ident">att.hispanTick.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.instrDef.vis">
         <td class="attClass ident">att.instrDef.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.keyAccid.vis">
         <td class="attClass ident">att.keyAccid.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySig.vis">
         <td class="attClass ident">att.keySig.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.keySigDefault.vis">
         <td class="attClass ident">att.keySigDefault.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the visual
            domain related to key signatures.</td>
      </tr>
      <tr class="u" id="att.layer.vis">
         <td class="attClass ident">att.layer.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.layerDef.vis">
         <td class="attClass ident">att.layerDef.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ligature.vis">
         <td class="attClass ident">att.ligature.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.line.vis">
         <td class="attClass ident">att.line.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Attributes for describing the visual appearance of a line.</td>
      </tr>
      <tr class="u" id="att.liquescent.vis">
         <td class="attClass ident">att.liquescent.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.lv.vis">
         <td class="attClass ident">att.lv.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes. The vo attribute is the vertical offset (from its normal
            position) of the entire rendered tie. The startho, startvo, endho, and endvo attributes
            describe the horizontal and vertical offsets of the start and end points of the sign
            in terms
            of staff interline distance; that is, in units of 1/2 the distance between adjacent
            staff
            lines. Startto and endto describe the start and end points in terms of time; that
            is,
            beats.</td>
      </tr>
      <tr class="u" id="att.lyrics.vis">
         <td class="attClass ident">att.lyrics.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.measure.vis">
         <td class="attClass ident">att.measure.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mensur.vis">
         <td class="attClass ident">att.mensur.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes. These attributes describe the physical appearance of the
            mensuration sign/time signature of mensural notation.</td>
      </tr>
      <tr class="u" id="att.mensural.vis">
         <td class="attClass ident">att.mensural.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the visual
            domain related to mensuration.</td>
      </tr>
      <tr class="u" id="att.meterSig.vis">
         <td class="attClass ident">att.meterSig.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.meterSigDefault.vis">
         <td class="attClass ident">att.meterSigDefault.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Used by staffDef and scoreDef to provide default values for attributes in the visual
            domain related to meter signature.</td>
      </tr>
      <tr class="u" id="att.mNum.vis">
         <td class="attClass ident">att.mNum.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRest.vis">
         <td class="attClass ident">att.mRest.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt.vis">
         <td class="attClass ident">att.mRpt.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mRpt2.vis">
         <td class="attClass ident">att.mRpt2.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.mSpace.vis">
         <td class="attClass ident">att.mSpace.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRest.vis">
         <td class="attClass ident">att.multiRest.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.multiRpt.vis">
         <td class="attClass ident">att.multiRpt.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.nc.vis">
         <td class="attClass ident">att.nc.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ncGrp.vis">
         <td class="attClass ident">att.ncGrp.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.neume.vis">
         <td class="attClass ident">att.neume.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.note.vis">
         <td class="attClass ident">att.note.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.oriscus.vis">
         <td class="attClass ident">att.oriscus.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.ossia.vis">
         <td class="attClass ident">att.ossia.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.pad.vis">
         <td class="attClass ident">att.pad.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.part.vis">
         <td class="attClass ident">att.part.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.parts.vis">
         <td class="attClass ident">att.parts.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.pb.vis">
         <td class="attClass ident">att.pb.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.pedal.vis">
         <td class="attClass ident">att.pedal.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes. The place attribute captures the placement of the pedal
            marking
            with respect to the staff with which it is associated. Modern publishing standards
            require the
            place to be  below ; however, for transcriptions of manuscript works, this attribute
            class
            allows the full range of values.</td>
      </tr>
      <tr class="u" id="att.phrase.vis">
         <td class="attClass ident">att.phrase.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.plica.vis">
         <td class="attClass ident">att.plica.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes that describe the properties of a plica stem in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="att.proport.vis">
         <td class="attClass ident">att.proport.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.quilisma.vis">
         <td class="attClass ident">att.quilisma.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.rdg.vis">
         <td class="attClass ident">att.rdg.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.refrain.vis">
         <td class="attClass ident">att.refrain.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.reh.vis">
         <td class="attClass ident">att.reh.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.rest.vis">
         <td class="attClass ident">att.rest.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.sb.vis">
         <td class="attClass ident">att.sb.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.score.vis">
         <td class="attClass ident">att.score.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.section.vis">
         <td class="attClass ident">att.section.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.signifLet.vis">
         <td class="attClass ident">att.signifLet.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.slur.vis">
         <td class="attClass ident">att.slur.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes for slur. The vo attribute is the vertical offset (from its
            normal position) of the entire rendered slur/phrase mark.</td>
      </tr>
      <tr class="u" id="att.sp.vis">
         <td class="attClass ident">att.sp.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.space.vis">
         <td class="attClass ident">att.space.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.staff.vis">
         <td class="attClass ident">att.staff.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.staffGrp.vis">
         <td class="attClass ident">att.staffGrp.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.stageDir.vis">
         <td class="attClass ident">att.stageDir.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.stem.vis">
         <td class="attClass ident">att.stem.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes that describe the properties of a stem in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="att.strophicus.vis">
         <td class="attClass ident">att.strophicus.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.syl.vis">
         <td class="attClass ident">att.syl.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.syllable.vis">
         <td class="attClass ident">att.syllable.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.symbol.vis">
         <td class="attClass ident">att.symbol.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.tie.vis">
         <td class="attClass ident">att.tie.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes. The vo attribute is the vertical offset (from its normal
            position) of the entire rendered tie. The startho, startvo, endho, and endvo attributes
            describe the horizontal and vertical offsets of the start and end points of the tie
            in terms
            of staff interline distance; that is, in units of 1/2 the distance between adjacent
            staff
            lines. Startto and endto describe the start and end points in terms of time; that
            is,
            beats.</td>
      </tr>
      <tr class="u" id="att.tuplet.vis">
         <td class="attClass ident">att.tuplet.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.tupletSpan.vis">
         <td class="attClass ident">att.tupletSpan.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.verse.vis">
         <td class="attClass ident">att.verse.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
      <tr class="u" id="att.volta.vis">
         <td class="attClass ident">att.volta.vis</td>
         <td class="module unchanged">MEI.visual</td>
         <td class="unchanged">Visual domain attributes.</td>
      </tr>
   </table>
   <h2>Model Class Comparison</h2>
   <h3 id="modelClassesAdded">1 new model classes:</h3>
   <table class="added">
      <tr class="a" id="$model.tuningPart">
         <td class="modelClass ident">model.tuningPart</td>
         <td class="module">MEI.shared</td>
         <td>Groups elements that may appear inside the  tuning  element.</td>
      </tr>
   </table>
   <h3 id="modelClassesRemoved">0 removed model classes:</h3>
   <table class="removed"></table>
   <h3 id="modelClassesChanged">0 modified model classes:</h3>
   <table></table>
   <h3 id="modelClassesUnchanged">143 unchanged model classes:</h3>
   <table>
      <tr class="u" id="model.controlEventLike.cmn">
         <td class="modelClass ident">model.controlEventLike.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups control events that appear in CMN.</td>
      </tr>
      <tr class="u" id="model.eventLike.cmn">
         <td class="modelClass ident">model.eventLike.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups events that appear in CMN.</td>
      </tr>
      <tr class="u" id="model.eventLike.measureFilling">
         <td class="modelClass ident">model.eventLike.measureFilling</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups events that completely fill a CMN measure.</td>
      </tr>
      <tr class="u" id="model.layerPart.cmn">
         <td class="modelClass ident">model.layerPart.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups notated events that may appear at the layer level in CMN.</td>
      </tr>
      <tr class="u" id="model.measureLike">
         <td class="modelClass ident">model.measureLike</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups CMN measure-like elements.</td>
      </tr>
      <tr class="u" id="model.measurePart">
         <td class="modelClass ident">model.measurePart</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups elements that may appear within a CMN measure.</td>
      </tr>
      <tr class="u" id="model.ossiaLike">
         <td class="modelClass ident">model.ossiaLike</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups elements that function like ossia.</td>
      </tr>
      <tr class="u" id="model.sectionPart.cmn">
         <td class="modelClass ident">model.sectionPart.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Groups elements that may appear as part of a section.</td>
      </tr>
      <tr class="u" id="model.ornamentLike.cmn">
         <td class="modelClass ident">model.ornamentLike.cmn</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">Groups CMN ornament elements.</td>
      </tr>
      <tr class="u" id="model.startLike.corpus">
         <td class="modelClass ident">model.startLike.corpus</td>
         <td class="module unchanged">MEI.corpus</td>
         <td class="unchanged">Groups elements that may be document elements when the corpus module is invoked.</td>
      </tr>
      <tr class="u" id="model.appLike">
         <td class="modelClass ident">model.appLike</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Groups elements that contain a critical apparatus entry.</td>
      </tr>
      <tr class="u" id="model.rdgPart">
         <td class="modelClass ident">model.rdgPart</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Groups elements that may appear as part of a textual or musical variant.</td>
      </tr>
      <tr class="u" id="model.rdgPart.music">
         <td class="modelClass ident">model.rdgPart.music</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Groups elements that may appear as part of a musical variant.</td>
      </tr>
      <tr class="u" id="model.rdgPart.text">
         <td class="modelClass ident">model.rdgPart.text</td>
         <td class="module unchanged">MEI.critapp</td>
         <td class="unchanged">Groups elements that may appear as part of a textual variant.</td>
      </tr>
      <tr class="u" id="model.stageDirLike">
         <td class="modelClass ident">model.stageDirLike</td>
         <td class="module unchanged">MEI.drama</td>
         <td class="unchanged">Groups elements containing stage directions in performance texts.</td>
      </tr>
      <tr class="u" id="model.choicePart">
         <td class="modelClass ident">model.choicePart</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements that may appear as part of the content of a choice element.</td>
      </tr>
      <tr class="u" id="model.editLike">
         <td class="modelClass ident">model.editLike</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements for editorial interventions that may be useful both in transcribing
            and in
            authoring processes.</td>
      </tr>
      <tr class="u" id="model.editTransPart">
         <td class="modelClass ident">model.editTransPart</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements that may appear as part of editorial and transcription elements.</td>
      </tr>
      <tr class="u" id="model.editTransPart.music">
         <td class="modelClass ident">model.editTransPart.music</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements that may appear as part of editorial and transcription elements in
            music
            notation.</td>
      </tr>
      <tr class="u" id="model.editTransPart.text">
         <td class="modelClass ident">model.editTransPart.text</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements that may appear as part of editorial and transcription elements in
            prose.</td>
      </tr>
      <tr class="u" id="model.transcriptionLike">
         <td class="modelClass ident">model.transcriptionLike</td>
         <td class="module unchanged">MEI.edittrans</td>
         <td class="unchanged">Groups elements used for editorial transcription of pre-existing source materials.</td>
      </tr>
      <tr class="u" id="model.figDescLike">
         <td class="modelClass ident">model.figDescLike</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Groups elements that provide a brief prose description of the appearance or content
            of a
            graphic figure.</td>
      </tr>
      <tr class="u" id="model.figureLike">
         <td class="modelClass ident">model.figureLike</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Groups elements representing or containing graphic information such as an illustration
            or
            figure.</td>
      </tr>
      <tr class="u" id="model.graphicLike">
         <td class="modelClass ident">model.graphicLike</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Groups elements that indicate the location of an inline graphic, illustration, or
            figure.</td>
      </tr>
      <tr class="u" id="model.tableLike">
         <td class="modelClass ident">model.tableLike</td>
         <td class="module unchanged">MEI.figtable</td>
         <td class="unchanged">Groups table-like elements.</td>
      </tr>
      <tr class="u" id="model.fingeringLike">
         <td class="modelClass ident">model.fingeringLike</td>
         <td class="module unchanged">MEI.fingering</td>
         <td class="unchanged">Groups elements that capture performance instructions regarding the use of the fingers
            of
            the hand (or a subset of them).</td>
      </tr>
      <tr class="u" id="model.expressionLike">
         <td class="modelClass ident">model.expressionLike</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Collects FRBR expression-like elements.</td>
      </tr>
      <tr class="u" id="model.itemLike">
         <td class="modelClass ident">model.itemLike</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Collects FRBR item-like elements.</td>
      </tr>
      <tr class="u" id="model.manifestationLike">
         <td class="modelClass ident">model.manifestationLike</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Collects FRBR manifestation-like elements.</td>
      </tr>
      <tr class="u" id="model.chordTableLike">
         <td class="modelClass ident">model.chordTableLike</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Groups elements that group playable chord definitions.</td>
      </tr>
      <tr class="u" id="model.controlEventLike.harmony">
         <td class="modelClass ident">model.controlEventLike.harmony</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Groups harmonic elements that function as control events; that is, those events that
            modify or otherwise depend on the existence of notated events.</td>
      </tr>
      <tr class="u" id="model.figbassLike">
         <td class="modelClass ident">model.figbassLike</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Groups elements that record figured bass.</td>
      </tr>
      <tr class="u" id="model.fLike">
         <td class="modelClass ident">model.fLike</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Groups elements that represent single figured bass elements.</td>
      </tr>
      <tr class="u" id="model.harmLike">
         <td class="modelClass ident">model.harmLike</td>
         <td class="module unchanged">MEI.harmony</td>
         <td class="unchanged">Groups elements that record indications of harmony.</td>
      </tr>
      <tr class="u" id="model.bifoliumLike">
         <td class="modelClass ident">model.bifoliumLike</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Collects bifoliumlike elements.</td>
      </tr>
      <tr class="u" id="model.editorialDeclPart">
         <td class="modelClass ident">model.editorialDeclPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of a description of the editorial process
            applied
            to the encoding of notation.</td>
      </tr>
      <tr class="u" id="model.encodingPart">
         <td class="modelClass ident">model.encodingPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of the description of the encoding process.</td>
      </tr>
      <tr class="u" id="model.eventPart">
         <td class="modelClass ident">model.eventPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may be used to provide a structured description of an event.</td>
      </tr>
      <tr class="u" id="model.foliumLike">
         <td class="modelClass ident">model.foliumLike</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Collects foliumlike elements.</td>
      </tr>
      <tr class="u" id="model.frontAndBackPart">
         <td class="modelClass ident">model.frontAndBackPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of auxiliary material preceding or following
            the
            text proper.</td>
      </tr>
      <tr class="u" id="model.headerPart">
         <td class="modelClass ident">model.headerPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of the MEI metadata header.</td>
      </tr>
      <tr class="u" id="model.paperModLike">
         <td class="modelClass ident">model.paperModLike</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements dealing with modifications of document pages.</td>
      </tr>
      <tr class="u" id="model.physDescPart">
         <td class="modelClass ident">model.physDescPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of the physical description of a bibliographic
            item.</td>
      </tr>
      <tr class="u" id="model.pubStmtPart">
         <td class="modelClass ident">model.pubStmtPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of the publication statement for a bibliographic
            item.</td>
      </tr>
      <tr class="u" id="model.startLike.header">
         <td class="modelClass ident">model.startLike.header</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may be document elements when the header module is invoked.</td>
      </tr>
      <tr class="u" id="model.workIdent">
         <td class="modelClass ident">model.workIdent</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that assist in the identification of a work.</td>
      </tr>
      <tr class="u" id="model.workLike">
         <td class="modelClass ident">model.workLike</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Collects work-like elements.</td>
      </tr>
      <tr class="u" id="model.verseLike">
         <td class="modelClass ident">model.verseLike</td>
         <td class="module unchanged">MEI.lyrics</td>
         <td class="unchanged">Groups elements that contain a lyric verse.</td>
      </tr>
      <tr class="u" id="model.eventLike.mensural">
         <td class="modelClass ident">model.eventLike.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Groups event elements that occur in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="model.layerPart.mensural">
         <td class="modelClass ident">model.layerPart.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Groups notated events that may appear at the layer level in the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="model.staffDefPart.mensural">
         <td class="modelClass ident">model.staffDefPart.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Groups elements that may appear in the declaration of staff features.</td>
      </tr>
      <tr class="u" id="model.staffPart.mensural">
         <td class="modelClass ident">model.staffPart.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Groups elements that are components of a staff in the mensural repertoire.</td>
      </tr>
      <tr class="u" id="model.midiLike">
         <td class="modelClass ident">model.midiLike</td>
         <td class="module unchanged">MEI.midi</td>
         <td class="unchanged">Groups elements which group MIDI-like elements.</td>
      </tr>
      <tr class="u" id="model.msInline">
         <td class="modelClass ident">model.msInline</td>
         <td class="module unchanged">MEI.msDesc</td>
         <td class="unchanged">Groups elements that may appear inline when the msdesc module is active.</td>
      </tr>
      <tr class="u" id="model.addressPart">
         <td class="modelClass ident">model.addressPart</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups elements used as part of a physical address.</td>
      </tr>
      <tr class="u" id="model.geogNamePart">
         <td class="modelClass ident">model.geogNamePart</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups elements which form part of a geographic name.</td>
      </tr>
      <tr class="u" id="model.nameLike.agent">
         <td class="modelClass ident">model.nameLike.agent</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups elements which contain names of individuals or corporate bodies.</td>
      </tr>
      <tr class="u" id="model.nameLike.geogName">
         <td class="modelClass ident">model.nameLike.geogName</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups geographic name elements.</td>
      </tr>
      <tr class="u" id="model.nameLike.label">
         <td class="modelClass ident">model.nameLike.label</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups elements that serve as stylistic labels.</td>
      </tr>
      <tr class="u" id="model.nameLike.place">
         <td class="modelClass ident">model.nameLike.place</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups place name elements.</td>
      </tr>
      <tr class="u" id="model.persNamePart">
         <td class="modelClass ident">model.persNamePart</td>
         <td class="module unchanged">MEI.namesdates</td>
         <td class="unchanged">Groups elements which form part of a personal name.</td>
      </tr>
      <tr class="u" id="model.eventLike.neumes">
         <td class="modelClass ident">model.eventLike.neumes</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups event elements that occur in the neume repertoire.</td>
      </tr>
      <tr class="u" id="model.layerPart.neumes">
         <td class="modelClass ident">model.layerPart.neumes</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups notated events that may appear at the layer level in the neume repertoire.</td>
      </tr>
      <tr class="u" id="model.neumeComponentModifierLike">
         <td class="modelClass ident">model.neumeComponentModifierLike</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups elements that modify neume components.</td>
      </tr>
      <tr class="u" id="model.neumeModifierLike">
         <td class="modelClass ident">model.neumeModifierLike</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups elements that modify neume-like features.</td>
      </tr>
      <tr class="u" id="model.neumePart">
         <td class="modelClass ident">model.neumePart</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups elements that may occur within a neume.</td>
      </tr>
      <tr class="u" id="model.syllableLike">
         <td class="modelClass ident">model.syllableLike</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups elements that accommodate neumed text.</td>
      </tr>
      <tr class="u" id="model.syllablePart">
         <td class="modelClass ident">model.syllablePart</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Groups elements that may appear as part of the content of a syllable.</td>
      </tr>
      <tr class="u" id="model.locrefLike">
         <td class="modelClass ident">model.locrefLike</td>
         <td class="module unchanged">MEI.ptrref</td>
         <td class="unchanged">Groups elements used for purposes of location and reference.</td>
      </tr>
      <tr class="u" id="model.addressLike">
         <td class="modelClass ident">model.addressLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to represent a postal address.</td>
      </tr>
      <tr class="u" id="model.annotLike">
         <td class="modelClass ident">model.annotLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups annotation-like elements.</td>
      </tr>
      <tr class="u" id="model.biblLike">
         <td class="modelClass ident">model.biblLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements containing a bibliographic description.</td>
      </tr>
      <tr class="u" id="model.biblPart">
         <td class="modelClass ident">model.biblPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a bibliographic description.</td>
      </tr>
      <tr class="u" id="model.captionLike">
         <td class="modelClass ident">model.captionLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that contain the text of a caption or other text displayed along with
            a
            figure.</td>
      </tr>
      <tr class="u" id="model.chordPart">
         <td class="modelClass ident">model.chordPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of the content of a chord element.</td>
      </tr>
      <tr class="u" id="model.controlEventLike">
         <td class="modelClass ident">model.controlEventLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements, such as dynamics, ties, phrase marks, pedal marks, etc., which depend
            upon other events, such as notes or rests, for their existence.</td>
      </tr>
      <tr class="u" id="model.dateLike">
         <td class="modelClass ident">model.dateLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements containing date expressions.</td>
      </tr>
      <tr class="u" id="model.descLike">
         <td class="modelClass ident">model.descLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements which provide a description of their parent entity.</td>
      </tr>
      <tr class="u" id="model.dimLike">
         <td class="modelClass ident">model.dimLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements which describe a measurement forming part of the physical dimensions
            of an
            object.</td>
      </tr>
      <tr class="u" id="model.editionLike">
         <td class="modelClass ident">model.editionLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements containing bibliographic edition information.</td>
      </tr>
      <tr class="u" id="model.editorialLike">
         <td class="modelClass ident">model.editorialLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups editorial intervention elements.</td>
      </tr>
      <tr class="u" id="model.endingLike">
         <td class="modelClass ident">model.endingLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent alternative endings.</td>
      </tr>
      <tr class="u" id="model.eventLike">
         <td class="modelClass ident">model.eventLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups event elements that occur in all notational repertoires.</td>
      </tr>
      <tr class="u" id="model.headLike">
         <td class="modelClass ident">model.headLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to provide a heading at the start of a text division or other
            markup
            component.</td>
      </tr>
      <tr class="u" id="model.identifierLike">
         <td class="modelClass ident">model.identifierLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups identifier-like elements.</td>
      </tr>
      <tr class="u" id="model.imprintPart">
         <td class="modelClass ident">model.imprintPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a bibliographic imprint.</td>
      </tr>
      <tr class="u" id="model.incipLike">
         <td class="modelClass ident">model.incipLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to represent a textual or musical incipit.</td>
      </tr>
      <tr class="u" id="model.instrDefLike">
         <td class="modelClass ident">model.instrDefLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to declare a MIDI instrument.</td>
      </tr>
      <tr class="u" id="model.keyAccidLike">
         <td class="modelClass ident">model.keyAccidLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent accidentals in a key signature.</td>
      </tr>
      <tr class="u" id="model.keySigLike">
         <td class="modelClass ident">model.keySigLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that have the same function as a key signature.</td>
      </tr>
      <tr class="u" id="model.labelLike">
         <td class="modelClass ident">model.labelLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to assign a label to other parts of a document.</td>
      </tr>
      <tr class="u" id="model.layerDefLike">
         <td class="modelClass ident">model.layerDefLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that permit declaration of layer properties.</td>
      </tr>
      <tr class="u" id="model.layerLike">
         <td class="modelClass ident">model.layerLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that function as notational layers within a staff.</td>
      </tr>
      <tr class="u" id="model.layerPart">
         <td class="modelClass ident">model.layerPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups notated events that may appear at the layer level in all repertoires.</td>
      </tr>
      <tr class="u" id="model.layerPart.mensuralAndNeumes">
         <td class="modelClass ident">model.layerPart.mensuralAndNeumes</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups notated events at the layer level that are shared by the mensural and neume
            repertoires.</td>
      </tr>
      <tr class="u" id="model.lbLike">
         <td class="modelClass ident">model.lbLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that function like line beginnings.</td>
      </tr>
      <tr class="u" id="model.mdivLike">
         <td class="modelClass ident">model.mdivLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements used to represent generic structural divisions of music notation.</td>
      </tr>
      <tr class="u" id="model.measurementLike">
         <td class="modelClass ident">model.measurementLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent a measurement.</td>
      </tr>
      <tr class="u" id="model.meterSigLike">
         <td class="modelClass ident">model.meterSigLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent a meter signature.</td>
      </tr>
      <tr class="u" id="model.milestoneLike.music">
         <td class="modelClass ident">model.milestoneLike.music</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups milestone-style elements found in music notation.</td>
      </tr>
      <tr class="u" id="model.milestoneLike.text">
         <td class="modelClass ident">model.milestoneLike.text</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups milestone-style elements found in text.</td>
      </tr>
      <tr class="u" id="model.nameLike">
         <td class="modelClass ident">model.nameLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that contain names.</td>
      </tr>
      <tr class="u" id="model.noteModifierLike">
         <td class="modelClass ident">model.noteModifierLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that modify note-like features.</td>
      </tr>
      <tr class="u" id="model.numLike">
         <td class="modelClass ident">model.numLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that denote a number or a quantity.</td>
      </tr>
      <tr class="u" id="model.paracontentPart">
         <td class="modelClass ident">model.paracontentPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements which may appear as part of the paragraph content model. A paragraph
            may
            contain inline elements and all other block-level elements except itself.</td>
      </tr>
      <tr class="u" id="model.partLike">
         <td class="modelClass ident">model.partLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent a separate performer part.</td>
      </tr>
      <tr class="u" id="model.partsLike">
         <td class="modelClass ident">model.partsLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that collect separate performer parts.</td>
      </tr>
      <tr class="u" id="model.pbLike">
         <td class="modelClass ident">model.pbLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups page beginning-like elements.</td>
      </tr>
      <tr class="u" id="model.pLike">
         <td class="modelClass ident">model.pLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups paragraph-like elements.</td>
      </tr>
      <tr class="u" id="model.relationLike">
         <td class="modelClass ident">model.relationLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Collects elements that express a relationship.</td>
      </tr>
      <tr class="u" id="model.rendLike">
         <td class="modelClass ident">model.rendLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that mark typographical features.</td>
      </tr>
      <tr class="u" id="model.repositoryLike">
         <td class="modelClass ident">model.repositoryLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that denote a corporate entity that holds a bibliographic item.</td>
      </tr>
      <tr class="u" id="model.resourceLike">
         <td class="modelClass ident">model.resourceLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups non-text components that represent the content of the musical text.</td>
      </tr>
      <tr class="u" id="model.respLike">
         <td class="modelClass ident">model.respLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that are used to indicate intellectual or other significant
            responsibility, for example within a bibliographic citation.</td>
      </tr>
      <tr class="u" id="model.respLikePart">
         <td class="modelClass ident">model.respLikePart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that delineate particular responsibilities as opposed to the respStmt
            element that provides for generic statements of responsibility.</td>
      </tr>
      <tr class="u" id="model.scoreDefLike">
         <td class="modelClass ident">model.scoreDefLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that provide score meta-information.</td>
      </tr>
      <tr class="u" id="model.scoreLike">
         <td class="modelClass ident">model.scoreLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent a score.</td>
      </tr>
      <tr class="u" id="model.scorePart">
         <td class="modelClass ident">model.scorePart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a score.</td>
      </tr>
      <tr class="u" id="model.sectionLike">
         <td class="modelClass ident">model.sectionLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that represent a segment of music notation.</td>
      </tr>
      <tr class="u" id="model.sectionPart">
         <td class="modelClass ident">model.sectionPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a section.</td>
      </tr>
      <tr class="u" id="model.sectionPart.mensuralAndNeumes">
         <td class="modelClass ident">model.sectionPart.mensuralAndNeumes</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a section in the mensural and neume
            repertoires.</td>
      </tr>
      <tr class="u" id="model.staffDefLike">
         <td class="modelClass ident">model.staffDefLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that permit declaration of staff properties.</td>
      </tr>
      <tr class="u" id="model.staffDefPart">
         <td class="modelClass ident">model.staffDefPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear in the declaration of staff features.</td>
      </tr>
      <tr class="u" id="model.staffGrpLike">
         <td class="modelClass ident">model.staffGrpLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that permit declaration of staff group properties.</td>
      </tr>
      <tr class="u" id="model.staffLike">
         <td class="modelClass ident">model.staffLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that function like staves.</td>
      </tr>
      <tr class="u" id="model.staffPart">
         <td class="modelClass ident">model.staffPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that are components of a staff.</td>
      </tr>
      <tr class="u" id="model.staffPart.mensuralAndNeumes">
         <td class="modelClass ident">model.staffPart.mensuralAndNeumes</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that are components of a staff in the mensural and neume
            repertoires.</td>
      </tr>
      <tr class="u" id="model.sylLike">
         <td class="modelClass ident">model.sylLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that contain a lyric syllable.</td>
      </tr>
      <tr class="u" id="model.textComponentLike">
         <td class="modelClass ident">model.textComponentLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups block-level text elements.</td>
      </tr>
      <tr class="u" id="model.textPhraseLike">
         <td class="modelClass ident">model.textPhraseLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups textual elements that occur at the level of individual words or phrases.</td>
      </tr>
      <tr class="u" id="model.textPhraseLike.limited">
         <td class="modelClass ident">model.textPhraseLike.limited</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups textual elements that occur at the level of individual words or phrases. This
            class
            is equivalent to the model.textPhraseLike class without the pb element.</td>
      </tr>
      <tr class="u" id="model.titleLike">
         <td class="modelClass ident">model.titleLike</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that denote the name of a bibliographic item.</td>
      </tr>
      <tr class="u" id="model.titlePagePart">
         <td class="modelClass ident">model.titlePagePart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a title page transcription.</td>
      </tr>
      <tr class="u" id="model.backLike">
         <td class="modelClass ident">model.backLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements that may contain back matter.</td>
      </tr>
      <tr class="u" id="model.divLike">
         <td class="modelClass ident">model.divLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements used to represent generic structural divisions of text.</td>
      </tr>
      <tr class="u" id="model.frontLike">
         <td class="modelClass ident">model.frontLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements that may contain front matter.</td>
      </tr>
      <tr class="u" id="model.lgLike">
         <td class="modelClass ident">model.lgLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements that have a line-grouping function.</td>
      </tr>
      <tr class="u" id="model.listLike">
         <td class="modelClass ident">model.listLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups list-like elements.</td>
      </tr>
      <tr class="u" id="model.lLike">
         <td class="modelClass ident">model.lLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements representing metrical components such as verse lines.</td>
      </tr>
      <tr class="u" id="model.qLike">
         <td class="modelClass ident">model.qLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements related to highlighting which can appear at the phrase-level.</td>
      </tr>
      <tr class="u" id="model.quoteLike">
         <td class="modelClass ident">model.quoteLike</td>
         <td class="module unchanged">MEI.text</td>
         <td class="unchanged">Groups elements used to directly contain quotations.</td>
      </tr>
      <tr class="u" id="model.graphicPrimitiveLike">
         <td class="modelClass ident">model.graphicPrimitiveLike</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Groups elements that function as drawing primitives.</td>
      </tr>
      <tr class="u" id="model.symbolTableLike">
         <td class="modelClass ident">model.symbolTableLike</td>
         <td class="module unchanged">MEI.usersymbols</td>
         <td class="unchanged">Groups elements that group symbol definitions.</td>
      </tr>
   </table>
   <h2>MacroSpec Comparison (Parameter Entities)</h2>
   <h3 id="macroAdded">0 new macroSpec classes:</h3>
   <table class="added"></table>
   <h3 id="macroRemoved">0 removed macroSpec classes:</h3>
   <table class="removed"></table>
   <h3 id="macroChanged">0 modified macroSpec classes:</h3>
   <table></table>
   <h3 id="macroUnchanged">7 unchanged macroSpec classes:</h3>
   <table>
      <tr class="u" id="macro.availabilityPart">
         <td class="macroClass ident">macro.availabilityPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups elements that may appear as part of a description of the availability of and
            access
            to a bibliographic item.</td>
      </tr>
      <tr class="u" id="macro.bibldescPart">
         <td class="macroClass ident">macro.bibldescPart</td>
         <td class="module unchanged">MEI.header</td>
         <td class="unchanged">Groups manifestation- and item-specific elements that may appear as part of a
            bibliographic description.</td>
      </tr>
      <tr class="u" id="macro.anyXML">
         <td class="macroClass ident">macro.anyXML</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Permits any XML elements except those from the MEI or SVG namespace.</td>
      </tr>
      <tr class="u" id="macro.metaLike.page">
         <td class="macroClass ident">macro.metaLike.page</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that contain meta-data about a single page.</td>
      </tr>
      <tr class="u" id="macro.musicPart">
         <td class="macroClass ident">macro.musicPart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of the music element.</td>
      </tr>
      <tr class="u" id="macro.struc-unstrucContent">
         <td class="macroClass ident">macro.struc-unstrucContent</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Provides a choice between structured and unstructured/mixed content.</td>
      </tr>
      <tr class="u" id="macro.titlePart">
         <td class="macroClass ident">macro.titlePart</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Groups elements that may appear as part of a bibliographic title.</td>
      </tr>
   </table>
   <h2>DataSpec Comparison (datatypes)</h2>
   <h3 id="dataSpecAdded">3 new dataSpecs:</h3>
   <table class="added">
      <tr class="a" id="data.HARPPEDALPOSITION">
         <td class="dataSpec datatype ident">data.HARPPEDALPOSITION</td>
         <td class="module">MEI.cmn</td>
         <td>Indicates the pedal setting for a harp strings.</td>
      </tr>
      <tr class="a" id="data.COURSENUMBER">
         <td class="dataSpec datatype ident">data.COURSENUMBER</td>
         <td class="module">MEI.stringtab</td>
         <td>In string tablature, the number of the course to be played.</td>
      </tr>
      <tr class="a" id="data.COURSETUNING">
         <td class="dataSpec datatype ident">data.COURSETUNING</td>
         <td class="module">MEI.stringtab</td>
         <td>Standard course tunings.</td>
      </tr>
   </table>
   <h3 id="dataSpecRemoved">0 removed dataSpecs:</h3>
   <table class="removed"></table>
   <h3 id="dataSpecChanged">2 modified dataSpecs:</h3>
   <table>
      <tr class="c" id="data.INTERVAL.HARMONIC">
         <td class="macroSpec datatype ident">data.INTERVAL.HARMONIC</td>
         <td class="module">MEI</td>
         <td class="desc"><span class="removed block">A token indicating diatonic interval quality and size.</span><span class="added block">A token indicating diatonic interval quality and size in shorthand notation.</span></td>
         <td class="classes">Referenced Macros:<br><ul></ul>
         </td>
         <td class="classes">Allowed values:<br><ul>
               <li class="added datatype value" title="added value">[AdMmP][1-9][0-9]*</li>
               <li class="removed datatype value" title="removed value">[AdMmP][0-9]+</li>
            </ul>
         </td>
      </tr>
      <tr class="c" id="data.NOTATIONTYPE">
         <td class="macroSpec datatype ident">data.NOTATIONTYPE</td>
         <td class="module">MEI</td>
         <td class="desc">Notation type and subtype</td>
         <td class="classes">Referenced Macros:<br><ul></ul>
         </td>
         <td class="classes">Allowed values:<br><ul>
               <li class="unchanged datatype value">cmn</li>
               <li class="unchanged datatype value">mensural</li>
               <li class="unchanged datatype value">mensural.black</li>
               <li class="unchanged datatype value">mensural.white</li>
               <li class="unchanged datatype value">neume</li>
               <li class="unchanged datatype value">tab</li>
               <li class="added datatype value" title="added value">tab.guitar</li>
               <li class="added datatype value" title="added value">tab.lute.french</li>
               <li class="added datatype value" title="added value">tab.lute.italian</li>
               <li class="added datatype value" title="added value">tab.lute.german</li>
            </ul>
         </td>
      </tr>
   </table>
   <h3 id="dataSpecUnchanged">161 unchanged dataSpecs:</h3>
   <table>
      <tr class="u" id="data.ACCIDENTAL.WRITTEN">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.WRITTEN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Written accidental values.</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.WRITTEN.basic">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.WRITTEN.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Written standard accidental values.</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.WRITTEN.extended">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.WRITTEN.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Written quarter-tone accidental values.</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.aeu">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.aeu</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Arel-Ezgi-Uzdilek (AEU) accidental values (written and gestural/performed).</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.persian">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.persian</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Persian accidental values (written and gestural/performed).</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.GESTURAL">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.GESTURAL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Gestural/performed standard accidental values.</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.GESTURAL.basic">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.GESTURAL.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Gestural/performed accidental values.</td>
      </tr>
      <tr class="u" id="data.ACCIDENTAL.GESTURAL.extended">
         <td class="dataSpec datatype ident">data.ACCIDENTAL.GESTURAL.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Gestural/performed quarter-tone accidental values.</td>
      </tr>
      <tr class="u" id="data.ARTICULATION">
         <td class="dataSpec datatype ident">data.ARTICULATION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">The following list of articulations mostly corresponds to symbols from the Western
            Musical
            Symbols portion of the Unicode Standard. The dot and stroke values may be used in
            cases where
            interpretation is difficult or undesirable.</td>
      </tr>
      <tr class="u" id="data.AUGMENTDOT">
         <td class="dataSpec datatype ident">data.AUGMENTDOT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Dots attribute values (number of augmentation dots) (Read, 113-119, ex. 8-21).</td>
      </tr>
      <tr class="u" id="data.BARMETHOD">
         <td class="dataSpec datatype ident">data.BARMETHOD</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Records where bar lines are drawn. The value 'staff' describes the traditional placement
            of bar lines.</td>
      </tr>
      <tr class="u" id="data.BARRENDITION">
         <td class="dataSpec datatype ident">data.BARRENDITION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Renderings of bar lines. Some values correspond to the Western Musical Symbols portion
            of
            the Unicode Standard.</td>
      </tr>
      <tr class="u" id="data.BEAM">
         <td class="dataSpec datatype ident">data.BEAM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Beam attribute values: initial, medial, terminal. Nested beaming is permitted.</td>
      </tr>
      <tr class="u" id="data.BEAMPLACE">
         <td class="dataSpec datatype ident">data.BEAMPLACE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of a beam relative to the events it affects.</td>
      </tr>
      <tr class="u" id="data.BEAT">
         <td class="dataSpec datatype ident">data.BEAT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A beat location,  i.e. , a decimal number.</td>
      </tr>
      <tr class="u" id="data.BEATRPT.REND">
         <td class="dataSpec datatype ident">data.BEATRPT.REND</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Visual and performance information for a repeated beat symbol.</td>
      </tr>
      <tr class="u" id="data.BEND.AMOUNT">
         <td class="dataSpec datatype ident">data.BEND.AMOUNT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Either an integer value, a decimal value, or a token. Fractional values are limited
            to
            .25, .5, .75, while the token value is restricted to 'full'.</td>
      </tr>
      <tr class="u" id="data.BOOLEAN">
         <td class="dataSpec datatype ident">data.BOOLEAN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Boolean attribute values.</td>
      </tr>
      <tr class="u" id="data.CANCELACCID">
         <td class="dataSpec datatype ident">data.CANCELACCID</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Indicates where cancellation accidentals are shown in a key signature.</td>
      </tr>
      <tr class="u" id="data.CERTAINTY">
         <td class="dataSpec datatype ident">data.CERTAINTY</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Values for certainty attribute. Certainty may be expressed by one of the predefined
            symbolic values  high , 
            medium , or  low . The value  unknown  should be used in cases where the encoder 
            does not wish to assert an opinion about the matter.</td>
      </tr>
      <tr class="u" id="data.CLEFLINE">
         <td class="dataSpec datatype ident">data.CLEFLINE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Clef line attribute values. The value must be in the range between 1 and the number
            of
            lines on the staff. The numbering of lines starts with the lowest line of the staff.</td>
      </tr>
      <tr class="u" id="data.CLEFSHAPE">
         <td class="dataSpec datatype ident">data.CLEFSHAPE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Clef shape attribute values (Read, p.53-56). Some values correspond to the Unicode
            Standard.</td>
      </tr>
      <tr class="u" id="data.CLUSTER">
         <td class="dataSpec datatype ident">data.CLUSTER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Tone-cluster rendition.</td>
      </tr>
      <tr class="u" id="data.CONFIDENCE">
         <td class="dataSpec datatype ident">data.CONFIDENCE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Confidence is expressed as a real number between 0 and 1; 0 representing certainly
            false
            and 1 representing certainly true.</td>
      </tr>
      <tr class="u" id="data.COLORNAMES">
         <td class="dataSpec datatype ident">data.COLORNAMES</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">List of named colors from CSS Color Module Level 4.</td>
      </tr>
      <tr class="u" id="data.COLORVALUES">
         <td class="dataSpec datatype ident">data.COLORVALUES</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Parameterized color values</td>
      </tr>
      <tr class="u" id="data.COLOR">
         <td class="dataSpec datatype ident">data.COLOR</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A value in one of the following forms is expected: 1) hexadecimal RRGGBB, 2) hexadecimal
            RRGGBBAA, 3) CSS RGB, 4) CSS RGBA, 5) HSL, 6) HSLA, or 7) CSS color name.</td>
      </tr>
      <tr class="u" id="data.COMPASSDIRECTION">
         <td class="dataSpec datatype ident">data.COMPASSDIRECTION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Description of direction with respect to an imaginary compass.</td>
      </tr>
      <tr class="u" id="data.COMPASSDIRECTION.basic">
         <td class="dataSpec datatype ident">data.COMPASSDIRECTION.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Basic compass directions.</td>
      </tr>
      <tr class="u" id="data.COMPASSDIRECTION.extended">
         <td class="dataSpec datatype ident">data.COMPASSDIRECTION.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Additional compass directions.</td>
      </tr>
      <tr class="u" id="data.DEGREES">
         <td class="dataSpec datatype ident">data.DEGREES</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">360th-unit measure of a circle’s circumference; optionally signed decimal number between
            -360 and 360.</td>
      </tr>
      <tr class="u" id="data.DIVISIO">
         <td class="dataSpec datatype ident">data.DIVISIO</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Divisio values.</td>
      </tr>
      <tr class="u" id="data.DURATION">
         <td class="dataSpec datatype ident">data.DURATION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Logical, that is, written, duration attribute values.</td>
      </tr>
      <tr class="u" id="data.DURATIONRESTS">
         <td class="dataSpec datatype ident">data.DURATIONRESTS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Logical, that is, written, duration attribute values for rests.</td>
      </tr>
      <tr class="u" id="data.DURATION.GESTURAL">
         <td class="dataSpec datatype ident">data.DURATION.GESTURAL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Performed duration attribute values.</td>
      </tr>
      <tr class="u" id="data.ENCLOSURE">
         <td class="dataSpec datatype ident">data.ENCLOSURE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Enclosures for editorial notes, accidentals, articulations, etc.</td>
      </tr>
      <tr class="u" id="data.EVENTREL">
         <td class="dataSpec datatype ident">data.EVENTREL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of musical material relative to a symbol on a staff instead of the staff.</td>
      </tr>
      <tr class="u" id="data.EVENTREL.basic">
         <td class="dataSpec datatype ident">data.EVENTREL.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of musical material relative to a symbol other than a staff.</td>
      </tr>
      <tr class="u" id="data.EVENTREL.extended">
         <td class="dataSpec datatype ident">data.EVENTREL.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of musical material relative to a symbol other than a staff.</td>
      </tr>
      <tr class="u" id="data.FILL">
         <td class="dataSpec datatype ident">data.FILL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Describes how a graphical object, such as a note head, should be filled. The relative
            values — top, bottom, left, and right — indicate these locations *after* rotation
            is
            applied.</td>
      </tr>
      <tr class="u" id="data.FINGER.FRET">
         <td class="dataSpec datatype ident">data.FINGER.FRET</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">In a guitar chord diagram, a label indicating which finger, if any, should be used
            to play
            an individual string. The index, middle, ring, and little fingers are represented
            by the
            values 1-4, while 't' is for the thumb. The values 'x' and 'o' indicate stopped and
            open
            strings, respectively.</td>
      </tr>
      <tr class="u" id="data.FONTFAMILY">
         <td class="dataSpec datatype ident">data.FONTFAMILY</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font family (for text) attribute values.</td>
      </tr>
      <tr class="u" id="data.FONTNAME">
         <td class="dataSpec datatype ident">data.FONTNAME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font name (for text) attribute values.</td>
      </tr>
      <tr class="u" id="data.FONTSIZE">
         <td class="dataSpec datatype ident">data.FONTSIZE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font size expressions.</td>
      </tr>
      <tr class="u" id="data.FONTSIZENUMERIC">
         <td class="dataSpec datatype ident">data.FONTSIZENUMERIC</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font size expressed as numbers;  i.e. , points or virtual units.</td>
      </tr>
      <tr class="u" id="data.FONTSIZESCALE">
         <td class="dataSpec datatype ident">data.FONTSIZESCALE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Relative size of symbol that may begin/end a line.</td>
      </tr>
      <tr class="u" id="data.FONTSIZETERM">
         <td class="dataSpec datatype ident">data.FONTSIZETERM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font size expressed as relative term.</td>
      </tr>
      <tr class="u" id="data.FONTSTYLE">
         <td class="dataSpec datatype ident">data.FONTSTYLE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font style (for text) attribute values.</td>
      </tr>
      <tr class="u" id="data.FONTWEIGHT">
         <td class="dataSpec datatype ident">data.FONTWEIGHT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Font weight (for text) attribute values.</td>
      </tr>
      <tr class="u" id="data.FRETNUMBER">
         <td class="dataSpec datatype ident">data.FRETNUMBER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">In string tablature, the fret number. The value  0  (zero) indicates the open
            string.</td>
      </tr>
      <tr class="u" id="data.GLISSANDO">
         <td class="dataSpec datatype ident">data.GLISSANDO</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Analytical glissando attribute values.</td>
      </tr>
      <tr class="u" id="data.GRACE">
         <td class="dataSpec datatype ident">data.GRACE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Do grace notes get time from the current (acc) or previous (unacc) one?</td>
      </tr>
      <tr class="u" id="data.HEADSHAPE">
         <td class="dataSpec datatype ident">data.HEADSHAPE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Note head shapes.</td>
      </tr>
      <tr class="u" id="data.HEADSHAPE.list">
         <td class="dataSpec datatype ident">data.HEADSHAPE.list</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Enumerated note head shapes.</td>
      </tr>
      <tr class="u" id="data.HEXNUM">
         <td class="dataSpec datatype ident">data.HEXNUM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Hexadecimal number.</td>
      </tr>
      <tr class="u" id="data.HORIZONTALALIGNMENT">
         <td class="dataSpec datatype ident">data.HORIZONTALALIGNMENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Data values for attributes that capture horizontal alignment.</td>
      </tr>
      <tr class="u" id="data.INTERVAL.MELODIC">
         <td class="dataSpec datatype ident">data.INTERVAL.MELODIC</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A token indicating direction of the interval but not its precise value, a diatonic
            interval (with optional direction and quality), or a decimal value in half steps.
            Decimal
            values are permitted to accommodate micro-tuning.</td>
      </tr>
      <tr class="u" id="data.ISODATE">
         <td class="dataSpec datatype ident">data.ISODATE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">ISO date formats.</td>
      </tr>
      <tr class="u" id="data.ISOTIME">
         <td class="dataSpec datatype ident">data.ISOTIME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">ISO 24-hour time format: HH:MM:SS.ss,  i.e. ,
            [0-9][0-9]:[0-9][0-9]:[0-9][0-9](\.?[0-9]*)?.</td>
      </tr>
      <tr class="u" id="data.KEYFIFTHS">
         <td class="dataSpec datatype ident">data.KEYFIFTHS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Indicates the location of the tonic in the circle of fifths.</td>
      </tr>
      <tr class="u" id="data.LAYERSCHEME">
         <td class="dataSpec datatype ident">data.LAYERSCHEME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Indicates how stems should be drawn when more than one layer is present and stem
            directions are not indicated on the notes/chords themselves. '1' indicates that there
            is only
            a single layer on a staff. '2o' means there are two layers with opposing stems. '2f'
            indicates
            two 'free' layers; that is, opposing stems will be drawn unless one of the layers
            has 'space'.
            In that case, stem direction in the remaining layer will be determined as if there
            were only
            one layer. '3o' and '3f' are analogous to '2o' and '2f' with three layers allowed.</td>
      </tr>
      <tr class="u" id="data.LIGATUREFORM">
         <td class="dataSpec datatype ident">data.LIGATUREFORM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Ligature forms.</td>
      </tr>
      <tr class="u" id="data.LINEFORM">
         <td class="dataSpec datatype ident">data.LINEFORM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Visual form of a line.</td>
      </tr>
      <tr class="u" id="data.LINESTARTENDSYMBOL">
         <td class="dataSpec datatype ident">data.LINESTARTENDSYMBOL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Symbol that may begin/end a line.</td>
      </tr>
      <tr class="u" id="data.LINEWIDTH">
         <td class="dataSpec datatype ident">data.LINEWIDTH</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Datatype of line width measurements.</td>
      </tr>
      <tr class="u" id="data.LINEWIDTHTERM">
         <td class="dataSpec datatype ident">data.LINEWIDTHTERM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Relative width of a line.</td>
      </tr>
      <tr class="u" id="data.MEASUREBEAT">
         <td class="dataSpec datatype ident">data.MEASUREBEAT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A count of measures plus a beat location,  i.e. , [0-9]+m *\+ *[0-9]+(\.?[0-9]*)?.
            The
            measure count is the number of bar lines crossed by the event, while the beat location
            is a
            timestamp expressed as a beat with an optional fractional part. For example, "1m+3.5"
            indicates a point in the next measure on the second half of beat 3. The measure number
            must be
            in the range of 0 to the number of remaining measures, while the beat number must
            be in the
            range from 0 to the numerator of the time signature plus 1. For example, in 6/8 the
            beat
            number must be within the range from 0 (the left bar line) to 7 (the right bar line).
            A value
            with a measure number of "0", such as "0m+2", indicates a point within the current
            measure.</td>
      </tr>
      <tr class="u" id="data.MEASUREBEATOFFSET">
         <td class="dataSpec datatype ident">data.MEASUREBEATOFFSET</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A count of measures plus a beat location,  i.e. , (\+|-)?[0-9]+m\+[0-9]+(\.?[0-9]*)?.
            The
            measure count is the number of bar lines crossed by the event, while the beat location
            is a
            timestamp expressed as a beat with an optional fractional part. The measure number
            must be in
            the range of preceding measures to the number of remaining measures. A value with
            a positive
            measure number, such as "1m+3", indicates a point in the following measure, while
            a value with
            a negative measure number, such as "-1m+3", marks a point in the preceding measure.
            The beat
            number must be in the range from 0 to the numerator of the time signature plus 1.
            For example,
            in 6/8 the beat number must be within the range from 0 (the left bar line) to 7 (the
            right
            bar line). A value with a measure number of "0", such as "0m+2", indicates a point
            within the
            current measure.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTUNSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTUNSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurement expressed in real-world ( e.g. , centimeters, millimeters, inches, points,
            picas, or pixels) or virtual units (vu). 'vu' is the default value. Unlike
            data.MEASUREMENTSIGNED, only positive values are allowed.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurement expressed in real-world ( e.g. , centimeters, millimeters, inches, points,
            picas, or pixels) or virtual units (vu). 'vu' is the default value. Unlike
            data.MEASUREMENTUNSIGNED, in which only positive values are allowed, both positive
            and negative
            values are permitted.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTFONTUNSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTFONTUNSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurement expressed relative to properties of the current font, in analogy to the
            respective CSS length units. Unlike data.MEASUREMENTFONTUNSIGNED, only positive values
            are
            allowed.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTFONTSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTFONTSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurement expressed relative to properties of the current font, in analogy to the
            respective CSS length units. Unlike data.MEASUREMENTFONTUNSIGNED, both positive and
            negative values
            are allowed.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTTYPOGRAPHYUNSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTTYPOGRAPHYUNSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurements used for typographical features. Unlike data.MEASUREMENTTYPOGRAPHYSIGNED,
            only
            positive values are allowed.</td>
      </tr>
      <tr class="u" id="data.MEASUREMENTTYPOGRAPHYSIGNED">
         <td class="dataSpec datatype ident">data.MEASUREMENTTYPOGRAPHYSIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Measurements used for typographical features. Unlike data.MEASUREMENTTYPOGRAPHYSIGNED,
            both
            positive and negative values are allowed.</td>
      </tr>
      <tr class="u" id="data.MELODICFUNCTION">
         <td class="dataSpec datatype ident">data.MELODICFUNCTION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Indication of melodic function,  i.e. , anticipation, lower neighbor, escape tone,
            etc.</td>
      </tr>
      <tr class="u" id="data.MENSURATIONSIGN">
         <td class="dataSpec datatype ident">data.MENSURATIONSIGN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Mensuration signs attribute values.</td>
      </tr>
      <tr class="u" id="data.METERFORM">
         <td class="dataSpec datatype ident">data.METERFORM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Contains an indication of how a meter signature should be rendered.</td>
      </tr>
      <tr class="u" id="data.METERSIGN">
         <td class="dataSpec datatype ident">data.METERSIGN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Meter.sym attribute values for CMN.</td>
      </tr>
      <tr class="u" id="data.MIDICHANNEL">
         <td class="dataSpec datatype ident">data.MIDICHANNEL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">MIDI channel number. One-based values must be followed by a lower-case letter "o".</td>
      </tr>
      <tr class="u" id="data.MIDIBPM">
         <td class="dataSpec datatype ident">data.MIDIBPM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Tempo expressed as "beats" per minute, where "beat" is always defined as a quarter
            note,
            *not the numerator of the time signature or the metronomic indication*.</td>
      </tr>
      <tr class="u" id="data.MIDIMSPB">
         <td class="dataSpec datatype ident">data.MIDIMSPB</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Tempo expressed as microseconds per "beat", where "beat" is always defined as a quarter
            note, *not the numerator of the time signature or the metronomic indication*.</td>
      </tr>
      <tr class="u" id="data.MIDINAMES">
         <td class="dataSpec datatype ident">data.MIDINAMES</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">General MIDI instrument names.</td>
      </tr>
      <tr class="u" id="data.MIDIVALUE">
         <td class="dataSpec datatype ident">data.MIDIVALUE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Generic MIDI value. One-based values must be followed by a lower-case letter "o".</td>
      </tr>
      <tr class="u" id="data.MIDIVALUE_NAME">
         <td class="dataSpec datatype ident">data.MIDIVALUE_NAME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">data.MIDIVALUE or data.NCName values.</td>
      </tr>
      <tr class="u" id="data.MIDIVALUE_PAN">
         <td class="dataSpec datatype ident">data.MIDIVALUE_PAN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">data.MIDIVALUE or data.PERCENT.LIMITED.SIGNED values.</td>
      </tr>
      <tr class="u" id="data.MIDIVALUE_PERCENT">
         <td class="dataSpec datatype ident">data.MIDIVALUE_PERCENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">data.MIDIVALUE or data.PERCENT.LIMITED values.</td>
      </tr>
      <tr class="u" id="data.MODE">
         <td class="dataSpec datatype ident">data.MODE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Modes.</td>
      </tr>
      <tr class="u" id="data.MODE.cmn">
         <td class="dataSpec datatype ident">data.MODE.cmn</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Common modes.</td>
      </tr>
      <tr class="u" id="data.MODE.gregorian">
         <td class="dataSpec datatype ident">data.MODE.gregorian</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Gregorian modes.</td>
      </tr>
      <tr class="u" id="data.MODE.extended">
         <td class="dataSpec datatype ident">data.MODE.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Modern modes.</td>
      </tr>
      <tr class="u" id="data.MODSRELATIONSHIP">
         <td class="dataSpec datatype ident">data.MODSRELATIONSHIP</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Bibliographic relationship values based on MODS version 3.4.</td>
      </tr>
      <tr class="u" id="data.MODUSMAIOR">
         <td class="dataSpec datatype ident">data.MODUSMAIOR</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Maxima-long relationship values.</td>
      </tr>
      <tr class="u" id="data.MODUSMINOR">
         <td class="dataSpec datatype ident">data.MODUSMINOR</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Long-breve relationship values.</td>
      </tr>
      <tr class="u" id="data.MUSICFONT">
         <td class="dataSpec datatype ident">data.MUSICFONT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Music font family.</td>
      </tr>
      <tr class="u" id="data.NCNAME">
         <td class="dataSpec datatype ident">data.NCNAME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">"Convenience" datatype that permits combining enumerated values with a user-supplied
            name.</td>
      </tr>
      <tr class="u" id="data.NMTOKEN">
         <td class="dataSpec datatype ident">data.NMTOKEN</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">"Convenience" datatype that permits combining enumerated values with user-supplied
            values.</td>
      </tr>
      <tr class="u" id="data.NONSTAFFPLACE">
         <td class="dataSpec datatype ident">data.NONSTAFFPLACE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Non-staff location.</td>
      </tr>
      <tr class="u" id="data.NOTEHEADMODIFIER">
         <td class="dataSpec datatype ident">data.NOTEHEADMODIFIER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Captures any notehead "modifiers"; that is, symbols added to the notehead, such as
            slashes, lines, text, and enclosures, etc.</td>
      </tr>
      <tr class="u" id="data.NOTEHEADMODIFIER.list">
         <td class="dataSpec datatype ident">data.NOTEHEADMODIFIER.list</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Enumerated note head modifier values.</td>
      </tr>
      <tr class="u" id="data.NOTEHEADMODIFIER.pat">
         <td class="dataSpec datatype ident">data.NOTEHEADMODIFIER.pat</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Captures text rendered in the center of the notehead.</td>
      </tr>
      <tr class="u" id="data.OCTAVE">
         <td class="dataSpec datatype ident">data.OCTAVE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Octave number. The default values conform to the Scientific Pitch Notation (SPN).</td>
      </tr>
      <tr class="u" id="data.OCTAVE.DIS">
         <td class="dataSpec datatype ident">data.OCTAVE.DIS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">The amount of octave displacement; that is, '8' (as in '8va' for 1 octave), '15' (for
            2
            octaves), or rarely '22' (for 3 octaves).</td>
      </tr>
      <tr class="u" id="data.ORIENTATION">
         <td class="dataSpec datatype ident">data.ORIENTATION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Rotation or reflection of base symbol values.</td>
      </tr>
      <tr class="u" id="data.NEIGHBORINGLAYER">
         <td class="dataSpec datatype ident">data.NEIGHBORINGLAYER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">For musical material designated to appear on an adjacent layer or staff, the location
            of the layer
            relative to the current one;  i.e. , the layer above or the layer below.</td>
      </tr>
      <tr class="u" id="data.PAGE.PANELS">
         <td class="dataSpec datatype ident">data.PAGE.PANELS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">The number of panels per page.</td>
      </tr>
      <tr class="u" id="data.PEDALSTYLE">
         <td class="dataSpec datatype ident">data.PEDALSTYLE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Styling of piano pedal marks.</td>
      </tr>
      <tr class="u" id="data.PERCENT">
         <td class="dataSpec datatype ident">data.PERCENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Positive decimal number plus '%',  i.e. , [0-9]+(\.[0-9]*)?%.</td>
      </tr>
      <tr class="u" id="data.PERCENT.LIMITED">
         <td class="dataSpec datatype ident">data.PERCENT.LIMITED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Decimal number between 0 and 100, followed by a percent sign "%".</td>
      </tr>
      <tr class="u" id="data.PERCENT.LIMITED.SIGNED">
         <td class="dataSpec datatype ident">data.PERCENT.LIMITED.SIGNED</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Decimal number between -100 and 100, followed by a percent sign "%".</td>
      </tr>
      <tr class="u" id="data.PGFUNC">
         <td class="dataSpec datatype ident">data.PGFUNC</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Page header and footer function; a value that defines the function (i.e., the placement)
            of the header or the footer.</td>
      </tr>
      <tr class="u" id="data.PGSCALE">
         <td class="dataSpec datatype ident">data.PGSCALE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Page scale factor; a percentage of the values in page.height and page.width.</td>
      </tr>
      <tr class="u" id="data.PITCHCLASS">
         <td class="dataSpec datatype ident">data.PITCHCLASS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Pclass (pitch class) attribute values.</td>
      </tr>
      <tr class="u" id="data.PITCHNAME">
         <td class="dataSpec datatype ident">data.PITCHNAME</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">The pitch names (gamut) used within a single octave. The default values conform to
            Acoustical Society of America representation.</td>
      </tr>
      <tr class="u" id="data.PITCHNAME.GESTURAL">
         <td class="dataSpec datatype ident">data.PITCHNAME.GESTURAL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Gestural pitch names need an additional value for when the notated pitch is not to
            be
            sounded.</td>
      </tr>
      <tr class="u" id="data.PITCHNUMBER">
         <td class="dataSpec datatype ident">data.PITCHNUMBER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Pnum (pitch number,  e.g. , MIDI) attribute values.</td>
      </tr>
      <tr class="u" id="data.PLACEMENT">
         <td class="dataSpec datatype ident">data.PLACEMENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location information.</td>
      </tr>
      <tr class="u" id="data.PROLATIO">
         <td class="dataSpec datatype ident">data.PROLATIO</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Semibreve-minim relationship values.</td>
      </tr>
      <tr class="u" id="data.RELATIONSHIP">
         <td class="dataSpec datatype ident">data.RELATIONSHIP</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">General-purpose relationships</td>
      </tr>
      <tr class="u" id="data.ROTATION">
         <td class="dataSpec datatype ident">data.ROTATION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Rotation.</td>
      </tr>
      <tr class="u" id="data.ROTATIONDIRECTION">
         <td class="dataSpec datatype ident">data.ROTATIONDIRECTION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Rotation term.</td>
      </tr>
      <tr class="u" id="data.SCALEDEGREE">
         <td class="dataSpec datatype ident">data.SCALEDEGREE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Scale degree values.</td>
      </tr>
      <tr class="u" id="data.SLASH">
         <td class="dataSpec datatype ident">data.SLASH</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">The number of slashes to be rendered for tremolandi.</td>
      </tr>
      <tr class="u" id="data.SLUR">
         <td class="dataSpec datatype ident">data.SLUR</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">i=initial, m=medial, t=terminal. Number is used to match endpoints of the slur when
            slurs
            are nested or overlap.</td>
      </tr>
      <tr class="u" id="data.STAFFITEM">
         <td class="dataSpec datatype ident">data.STAFFITEM</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Items that may be printed above, below, or between staves.</td>
      </tr>
      <tr class="u" id="data.STAFFITEM.basic">
         <td class="dataSpec datatype ident">data.STAFFITEM.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Items in all repertoires that may be printed near a staff.</td>
      </tr>
      <tr class="u" id="data.STAFFLOC">
         <td class="dataSpec datatype ident">data.STAFFLOC</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Staff location. The value  0  indicates the bottom line of the current staff; positive
            values are used for positions above the bottom line and negative values for the positions
            below. For example, in treble clef, 1 = F4, 2 = G4, 3 = A4, etc. and -1 = D4, -2 =
            C4, and so
            on.</td>
      </tr>
      <tr class="u" id="data.STAFFREL">
         <td class="dataSpec datatype ident">data.STAFFREL</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of musical material relative to a staff.</td>
      </tr>
      <tr class="u" id="data.STAFFREL.basic">
         <td class="dataSpec datatype ident">data.STAFFREL.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of symbol relative to a staff.</td>
      </tr>
      <tr class="u" id="data.STAFFREL.extended">
         <td class="dataSpec datatype ident">data.STAFFREL.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Location of symbol relative to a staff.</td>
      </tr>
      <tr class="u" id="data.STEMDIRECTION">
         <td class="dataSpec datatype ident">data.STEMDIRECTION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Stem direction.</td>
      </tr>
      <tr class="u" id="data.STEMDIRECTION.basic">
         <td class="dataSpec datatype ident">data.STEMDIRECTION.basic</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Common stem directions.</td>
      </tr>
      <tr class="u" id="data.STEMDIRECTION.extended">
         <td class="dataSpec datatype ident">data.STEMDIRECTION.extended</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Additional stem directions.</td>
      </tr>
      <tr class="u" id="data.STEMMODIFIER">
         <td class="dataSpec datatype ident">data.STEMMODIFIER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Stem modification.</td>
      </tr>
      <tr class="u" id="data.STEMPOSITION">
         <td class="dataSpec datatype ident">data.STEMPOSITION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Position of a note’s stem relative to the head of the note.</td>
      </tr>
      <tr class="u" id="data.STRINGNUMBER">
         <td class="dataSpec datatype ident">data.STRINGNUMBER</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">This datatype is deprecated in favor of data.COURSENUMBER and will be removed in a
            future version. In string tablature, the number of the string to be played.</td>
      </tr>
      <tr class="u" id="data.TEMPERAMENT">
         <td class="dataSpec datatype ident">data.TEMPERAMENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Temperament or tuning system.</td>
      </tr>
      <tr class="u" id="data.TEMPOVALUE">
         <td class="dataSpec datatype ident">data.TEMPOVALUE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Beats (meter signature denominator) per minute,  e.g. , 120.</td>
      </tr>
      <tr class="u" id="data.TEMPUS">
         <td class="dataSpec datatype ident">data.TEMPUS</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Breve-semibreve relationship values.</td>
      </tr>
      <tr class="u" id="data.TEXTRENDITIONLIST">
         <td class="dataSpec datatype ident">data.TEXTRENDITIONLIST</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Closed list of text rendition values.</td>
      </tr>
      <tr class="u" id="data.TEXTRENDITIONPAR">
         <td class="dataSpec datatype ident">data.TEXTRENDITIONPAR</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Parameterized text rendition values.</td>
      </tr>
      <tr class="u" id="data.TEXTRENDITION">
         <td class="dataSpec datatype ident">data.TEXTRENDITION</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Text rendition values.</td>
      </tr>
      <tr class="u" id="data.TIE">
         <td class="dataSpec datatype ident">data.TIE</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Tie attribute values: initial, medial, terminal.</td>
      </tr>
      <tr class="u" id="data.TSTAMPOFFSET">
         <td class="dataSpec datatype ident">data.TSTAMPOFFSET</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A positive or negative offset from the value given in the tstamp attribute in terms
            of
            musical time,  i.e. , beats[.fractional beat part].</td>
      </tr>
      <tr class="u" id="data.TUPLET">
         <td class="dataSpec datatype ident">data.TUPLET</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Tuplet attribute values: initial, medial, terminal.</td>
      </tr>
      <tr class="u" id="data.URI">
         <td class="dataSpec datatype ident">data.URI</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A Uniform Resource Identifier, see [RFC2396].</td>
      </tr>
      <tr class="u" id="data.VERTICALALIGNMENT">
         <td class="dataSpec datatype ident">data.VERTICALALIGNMENT</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">Data values for attributes that capture vertical alignment.</td>
      </tr>
      <tr class="u" id="data.WORD">
         <td class="dataSpec datatype ident">data.WORD</td>
         <td class="module unchanged">MEI</td>
         <td class="unchanged">A single "word" that contains only letters, digits, punctuation characters, or symbols.
            It
            cannot contain whitespace.</td>
      </tr>
      <tr class="u" id="data.DURATION.cmn">
         <td class="dataSpec datatype ident">data.DURATION.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Logical, that is, written, duration attribute values for the CMN repertoire.</td>
      </tr>
      <tr class="u" id="data.STAFFITEM.cmn">
         <td class="dataSpec datatype ident">data.STAFFITEM.cmn</td>
         <td class="module unchanged">MEI.cmn</td>
         <td class="unchanged">Items in the CMN repertoire that may be printed near a staff.</td>
      </tr>
      <tr class="u" id="data.ORNAM.cmn">
         <td class="dataSpec datatype ident">data.ORNAM.cmn</td>
         <td class="module unchanged">MEI.cmnOrnaments</td>
         <td class="unchanged">CMN ornam attribute values: A = appogiatura (upper neighbor); a = acciaccatura (lower
            neighbor); b = bebung; I = ascending slide; i = descending slide; k = delayed turn;
            K = 5-note
            turn; m = mordent (alternation with lower neighbor); M = inverted mordent (alternation
            with
            upper neighbor); N = Nachschlag (upper neighbor); n = Nachschlag (lower neighbor);
            S = turn; s
            = inverted turn; t = trill commencing on auxiliary note; T = trill commencing on principal
            note; O = generic / unspecified ornament.</td>
      </tr>
      <tr class="u" id="data.FRBRRELATIONSHIP">
         <td class="dataSpec datatype ident">data.FRBRRELATIONSHIP</td>
         <td class="module unchanged">MEI.frbr</td>
         <td class="unchanged">Relationships between FRBR entities.</td>
      </tr>
      <tr class="u" id="data.DURATION.mensural">
         <td class="dataSpec datatype ident">data.DURATION.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical, that is, written, note-shape (or note symbol) attribute values for the mensural
            repertoire.</td>
      </tr>
      <tr class="u" id="data.MULTIBREVERESTS.mensural">
         <td class="dataSpec datatype ident">data.MULTIBREVERESTS.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical, that is, written, duration attribute values for multi-breve rests in the
            mensural repertoire.</td>
      </tr>
      <tr class="u" id="data.DURATIONRESTS.mensural">
         <td class="dataSpec datatype ident">data.DURATIONRESTS.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Logical, that is, written, duration attribute values for mensural rests.</td>
      </tr>
      <tr class="u" id="data.DURQUALITY.mensural">
         <td class="dataSpec datatype ident">data.DURQUALITY.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Duration attribute values of a given note symbol for the mensural repertoire.</td>
      </tr>
      <tr class="u" id="data.FLAGFORM.mensural">
         <td class="dataSpec datatype ident">data.FLAGFORM.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Form of the flag.</td>
      </tr>
      <tr class="u" id="data.FLAGPOS.mensural">
         <td class="dataSpec datatype ident">data.FLAGPOS.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Position of the flag relative to the stem.</td>
      </tr>
      <tr class="u" id="data.STAFFITEM.mensural">
         <td class="dataSpec datatype ident">data.STAFFITEM.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Items in the Mensural repertoire that may be printed near a staff.</td>
      </tr>
      <tr class="u" id="data.STEMFORM.mensural">
         <td class="dataSpec datatype ident">data.STEMFORM.mensural</td>
         <td class="module unchanged">MEI.mensural</td>
         <td class="unchanged">Form of the stem attached to the note.</td>
      </tr>
      <tr class="u" id="data.STAFFITEM.neumes">
         <td class="dataSpec datatype ident">data.STAFFITEM.neumes</td>
         <td class="module unchanged">MEI.neumes</td>
         <td class="unchanged">Items in the Neume repertoire that may be printed near a staff.</td>
      </tr>
      <tr class="u" id="data.BETYPE">
         <td class="dataSpec datatype ident">data.BETYPE</td>
         <td class="module unchanged">MEI.shared</td>
         <td class="unchanged">Datatypes for values in begin, end, abstype and inttype attributes.</td>
      </tr>
   </table><script src="resources/js/d3.min.js"></script><script>
                    var elements = [
                        {type:'added', count: 5, ref:'#elementsAdded'},
                        {type:'changed', count: 42, ref:'#elementsChanged'},
                        {type:'removed', count: 0, ref:'#elementsRemoved'},
                        {type:'unchanged', count: 374, ref:'#elementsUnchanged'}
                    ];
                    var attClasses = [
                    {type:'added', count: 19, ref:'#attClassesAdded'},
                    {type:'changed', count: 27, ref:'#attClassesChanged'},
                    {type:'removed', count: 0, ref:'#attClassesRemoved'},
                    {type:'unchanged', count: 683, ref:'#attClassesUnchanged'}
                    ];
                    var modelClasses = [
                    {type:'added', count: 1, ref:'#modelClassesAdded'},
                    {type:'changed', count: 0, ref:'#modelClassesChanged'},
                    {type:'removed', count: 0, ref:'#modelClassesRemoved'},
                    {type:'unchanged', count: 143, ref:'#modelClassesUnchanged'}
                    ];
                    var macro = [
                    {type:'added', count: 0, ref:'#macroAdded'},
                    {type:'changed', count: 0, ref:'#macroChanged'},
                    {type:'removed', count: 0, ref:'#macroRemoved'},
                    {type:'unchanged', count: 7, ref:'#macroUnchanged'}
                    ];
                    var data = [
                    {type:'added', count: 3, ref:'#dataSpecAdded'},
                    {type:'changed', count: 2, ref:'#dataSpecChanged'},
                    {type:'removed', count: 0, ref:'#dataSpecRemoved'},
                    {type:'unchanged', count: 161, ref:'#dataSpecUnchanged'}
                    ];
                </script><script src="resources/js/main.js"></script></div>