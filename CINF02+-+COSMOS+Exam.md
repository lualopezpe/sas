
<img src="files/sas.png">

## CINF02- COSMOS

_Actividad evaluativa transferencia de conocimiento CINF02-COSMOS_

**Responda las preguntas `1` y `2` con base en el `Snippet 1`.**

#### Snippet 1


```sas
libname lcata XLSX 
"/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx";

proc contents data=lcata._all_ nods;
run;
```

    SAS Connection established. Subprocess id is 2724
    





<!DOCTYPE html>
<html lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta charset="utf-8"/>
<meta content="SAS 9.4" name="generator"/>
<title>SAS Output</title>
<style>
/*<![CDATA[*/
.body.c > table, .body.c > pre, .body.c div > table,
.body.c div > pre, .body.c > table, .body.c > pre,
.body.j > table, .body.j > pre, .body.j div > table,
.body.j div > pre, .body.j > table, .body.j > pre,
.body.c p.note, .body.c p.warning, .body.c p.error, .body.c p.fatal,
.body.j p.note, .body.j p.warning, .body.j p.error, .body.j p.fatal,
.body.c > table.layoutcontainer, .body.j > table.layoutcontainer { margin-left: auto; margin-right: auto }
.layoutregion.l table, .layoutregion.l pre, .layoutregion.l p.note,
.layoutregion.l p.warning, .layoutregion.l p.error, .layoutregion.l p.fatal { margin-left: 0 }
.layoutregion.c table, .layoutregion.c pre, .layoutregion.c p.note,
.layoutregion.c p.warning, .layoutregion.c p.error, .layoutregion.c p.fatal { margin-left: auto; margin-right: auto }
.layoutregion.r table, .layoutregion.r pre, .layoutregion.r p.note,
.layoutregion.r table, .layoutregion.r pre, .layoutregion.r p.note,
.layoutregion.r p.warning, .layoutregion.r p.error, .layoutregion.r p.fatal { margin-right: 0 }
article, aside, details, figcaption, figure, footer, header, hgroup, nav, section { display: block }
html{ font-size: 100% }
.body { margin: 1em; font-size: 13px; line-height: 1.231 }
sup { position: relative; vertical-align: baseline; bottom: 0.25em; font-size: 0.8em }
sub { position: relative; vertical-align: baseline; top: 0.25em; font-size: 0.8em }
ul, ol { margin: 1em 0; padding: 0 0 0 40px }
dd { margin: 0 0 0 40px }
nav ul, nav ol { list-style: none; list-style-image: none; margin: 0; padding: 0 }
img { border: 0; vertical-align: middle }
svg:not(:root) { overflow: hidden }
figure { margin: 0 }
table { border-collapse: collapse; border-spacing: 0 }
.layoutcontainer { border-collapse: separate; border-spacing: 0 }
p { margin-top: 0; text-align: left }
h1.heading1 { text-align: left }
h2.heading2 { text-align: left }
h3.heading3 { text-align: left }
h4.heading4 { text-align: left }
h5.heading5 { text-align: left }
h6.heading6 { text-align: left }
span { text-align: left }
table { margin-bottom: 1em }
td, th { text-align: left; padding: 3px 6px; vertical-align: top }
td[class$="fixed"], th[class$="fixed"] { white-space: pre }
section, article { padding-top: 1px; padding-bottom: 8px }
hr.pagebreak { height: 0px; border: 0; border-bottom: 1px solid #c0c0c0; margin: 1em 0 }
.stacked-value { text-align: left; display: block }
.stacked-cell > .stacked-value, td.data > td.data, th.data > td.data, th.data > th.data, td.data > th.data, th.header > th.header { border: 0 }
.stacked-cell > div.data { border-width: 0 }
.systitleandfootercontainer { white-space: nowrap; margin-bottom: 1em }
.systitleandfootercontainer > p { margin: 0 }
.systitleandfootercontainer > p > span { display: inline-block; width: 100%; white-space: normal }
.batch { display: table }
.toc { display: none }
.proc_note_group, .proc_title_group { margin-bottom: 1em }
p.proctitle { margin: 0 }
p.note, p.warning, p.error, p.fatal { display: table }
.notebanner, .warnbanner, .errorbanner, .fatalbanner,
.notecontent, .warncontent, .errorcontent, .fatalcontent { display: table-cell; padding: 0.5em }
.notebanner, .warnbanner, .errorbanner, .fatalbanner { padding-right: 0 }
.body > div > ol li { text-align: left }
.c { text-align: center }
.r { text-align: right }
.l { text-align: left }
.j { text-align: justify }
.d { text-align: right }
.b { vertical-align: bottom }
.m { vertical-align: middle }
.t { vertical-align: top }
a:active { color: #800080 }
.aftercaption {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
    padding-top: 4pt;
}
.batch > colgroup {
    border-left: 1px solid #c1c1c1;
    border-right: 1px solid #c1c1c1;
}
.batch > tbody, .batch > thead, .batch > tfoot {
    border-top: 1px solid #c1c1c1;
    border-bottom: 1px solid #c1c1c1;
}
.batch { border: hidden; }
.batch {
    background-color: #fafbfe;
    border: 1px solid #c1c1c1;
    border-collapse: separate;
    border-spacing: 1px;
    color: #000000;
    font-family: 'SAS Monospace', 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    padding: 7px;
    }
.beforecaption {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.body {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    margin-left: 8px;
    margin-right: 8px;
}
.bodydate {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    text-align: right;
    vertical-align: top;
    width: 100%;
}
.bycontentfolder {
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: none;
    margin-left: 6pt;
}
.byline {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.bylinecontainer > col, .bylinecontainer > colgroup > col, .bylinecontainer > colgroup, .bylinecontainer > tr, .bylinecontainer > * > tr, .bylinecontainer > thead, .bylinecontainer > tbody, .bylinecontainer > tfoot { border: none; }
.bylinecontainer {
    background-color: #fafbfe;
    border: none;
    border-spacing: 1px;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.caption {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.cell, .container {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.contentfolder, .contentitem {
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: none;
    margin-left: 6pt;
}
.contentproclabel, .contentprocname {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.contents {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: decimal;
    margin-left: 8px;
    margin-right: 8px;
}
.contentsdate {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.contenttitle {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: bold;
}
.continued {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
    width: 100%;
}
.data, .dataemphasis {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.dataemphasisfixed {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.dataempty {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.datafixed {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.datastrong {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.datastrongfixed {
    background-color: #ffffff;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.date {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.document {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.errorbanner {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.errorcontent {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.errorcontentfixed {
    background-color: #fafbfe;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.extendedpage {
    background-color: #fafbfe;
    border-style: solid;
    border-width: 1pt;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
    text-align: center;
}
.fatalbanner {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.fatalcontent {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.fatalcontentfixed {
    background-color: #fafbfe;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.folderaction {
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: none;
    margin-left: 6pt;
}
.footer {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.footeremphasis {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.footeremphasisfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.footerempty {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.footerfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.footerstrong {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.footerstrongfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.frame {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.graph > colgroup {
    border-left: 1px solid #c1c1c1;
    border-right: 1px solid #c1c1c1;
}
.graph > tbody, .graph > thead, .graph > tfoot {
    border-top: 1px solid #c1c1c1;
    border-bottom: 1px solid #c1c1c1;
}
.graph { border: hidden; }
.graph {
    background-color: #fafbfe;
    border: 1px solid #c1c1c1;
    border-collapse: separate;
    border-spacing: 1px;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    }
.header {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.headeremphasis {
    background-color: #d8dbd3;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.headeremphasisfixed {
    background-color: #d8dbd3;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.headerempty {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.headerfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.headersandfooters {
    background-color: #edf2f9;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.headerstrong {
    background-color: #d8dbd3;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.headerstrongfixed {
    background-color: #d8dbd3;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #000000;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.heading1, .heading2, .heading3, .heading4, .heading5, .heading6 { font-family: Arial, Helvetica, sans-serif }
.index {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.indexaction, .indexitem {
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: none;
    margin-left: 6pt;
}
.indexprocname {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.indextitle {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: bold;
}
.layoutcontainer, .layoutregion {
    border-width: 0;
    border-spacing: 30px;
}
.linecontent {
    background-color: #fafbfe;
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
a:link { color: #0000ff }
.list {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: disc;
}
.list10 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: square;
}
.list2 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: circle;
}
.list3, .list4, .list5, .list6, .list7, .list8, .list9 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: square;
}
.listitem {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: disc;
}
.listitem10 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: square;
}
.listitem2 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: circle;
}
.listitem3, .listitem4, .listitem5, .listitem6, .listitem7, .listitem8, .listitem9 {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: square;
}
.note {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.notebanner {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.notecontent {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.notecontentfixed {
    background-color: #fafbfe;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.output > colgroup {
    border-left: 1px solid #c1c1c1;
    border-right: 1px solid #c1c1c1;
}
.output > tbody, .output > thead, .output > tfoot {
    border-top: 1px solid #c1c1c1;
    border-bottom: 1px solid #c1c1c1;
}
.output { border: hidden; }
.output {
    background-color: #fafbfe;
    border: 1px solid #c1c1c1;
    border-collapse: separate;
    border-spacing: 1px;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    }
.pageno {
    background-color: #fafbfe;
    border-spacing: 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
    text-align: right;
    vertical-align: top;
}
.pages {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: decimal;
    margin-left: 8px;
    margin-right: 8px;
}
.pagesdate {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.pagesitem {
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    list-style-type: none;
    margin-left: 6pt;
}
.pagesproclabel, .pagesprocname {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.pagestitle {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: bold;
}
.paragraph {
    background-color: #fafbfe;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.parskip > col, .parskip > colgroup > col, .parskip > colgroup, .parskip > tr, .parskip > * > tr, .parskip > thead, .parskip > tbody, .parskip > tfoot { border: none; }
.parskip {
    border: none;
    border-spacing: 0;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
    }
.prepage {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    text-align: left;
}
.proctitle {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.proctitlefixed {
    background-color: #fafbfe;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowfooter {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowfooteremphasis {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.rowfooteremphasisfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.rowfooterempty {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowfooterfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.rowfooterstrong {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowfooterstrongfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowheader {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowheaderemphasis {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.rowheaderemphasisfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: italic;
    font-weight: normal;
}
.rowheaderempty {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowheaderfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.rowheaderstrong {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.rowheaderstrongfixed {
    background-color: #edf2f9;
    border-color: #b0b7bb;
    border-style: solid;
    border-width: 0 1px 1px 0;
    color: #112277;
    font-family: 'Courier New', Courier, monospace;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.systemfooter, .systemfooter10, .systemfooter2, .systemfooter3, .systemfooter4, .systemfooter5, .systemfooter6, .systemfooter7, .systemfooter8, .systemfooter9 {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.systemtitle, .systemtitle10, .systemtitle2, .systemtitle3, .systemtitle4, .systemtitle5, .systemtitle6, .systemtitle7, .systemtitle8, .systemtitle9 {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size: small;
    font-style: normal;
    font-weight: bold;
}
.systitleandfootercontainer > col, .systitleandfootercontainer > colgroup > col, .systitleandfootercontainer > colgroup, .systitleandfootercontainer > tr, .systitleandfootercontainer > * > tr, .systitleandfootercontainer > thead, .systitleandfootercontainer > tbody, .systitleandfootercontainer > tfoot { border: none; }
.systitleandfootercontainer {
    background-color: #fafbfe;
    border: none;
    border-spacing: 1px;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.table > col, .table > colgroup > col {
    border-left: 1px solid #c1c1c1;
    border-right: 0 solid #c1c1c1;
}
.table > tr, .table > * > tr {
    border-top: 1px solid #c1c1c1;
    border-bottom: 0 solid #c1c1c1;
}
.table { border: hidden; }
.table {
    border-color: #c1c1c1;
    border-style: solid;
    border-width: 1px 0 0 1px;
    border-collapse: collapse;
    border-spacing: 0;
    }
.titleandnotecontainer > col, .titleandnotecontainer > colgroup > col, .titleandnotecontainer > colgroup, .titleandnotecontainer > tr, .titleandnotecontainer > * > tr, .titleandnotecontainer > thead, .titleandnotecontainer > tbody, .titleandnotecontainer > tfoot { border: none; }
.titleandnotecontainer {
    background-color: #fafbfe;
    border: none;
    border-spacing: 1px;
    color: #000000;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
    width: 100%;
}
.titlesandfooters {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.usertext {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
a:visited { color: #800080 }
.warnbanner {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: bold;
}
.warncontent {
    background-color: #fafbfe;
    color: #112277;
    font-family: Arial, 'Albany AMT', Helvetica, Helv;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
.warncontentfixed {
    background-color: #fafbfe;
    color: #112277;
    font-family: 'Courier New', Courier;
    font-size:  normal;
    font-style: normal;
    font-weight: normal;
}
/*]]>*/
</style>
</head>
<body class="l body">
<div style="padding-bottom: 8px; padding-top: 1px">
<div id="IDX" class="systitleandfootercontainer" style="border-spacing: 1px">
<p><span class="c systemtitle">The SAS System</span> </p>
</div>
<div class="proc_title_group">
<p class="c proctitle">The CONTENTS Procedure</p>
</div>
<div style="padding-bottom: 8px; padding-top: 1px">
<table class="table" style="border-spacing: 0" aria-label="Directory Information">
<caption aria-label="Directory Information"></caption>
<colgroup><col/><col/></colgroup>
<thead>
<tr>
<th class="c b header" colspan="2" scope="colgroup">Directory</th>
</tr>
</thead>
<tbody>
<tr>
<th class="rowheader" scope="row">Libref</th>
<td class="data">LCATA</td>
</tr>
<tr>
<th class="rowheader" scope="row">Engine</th>
<td class="data">XLSX</td>
</tr>
<tr>
<th class="rowheader" scope="row">Physical Name</th>
<td class="data">/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx</td>
</tr>
<tr>
<th class="rowheader" scope="row">Por</th>
<td class="data">.</td>
</tr>
</tbody>
</table>
</div>
<div id="IDX1" style="padding-bottom: 8px; padding-top: 1px">
<table class="table" style="border-spacing: 0" aria-label="Library Members">
<caption aria-label="Library Members"></caption>
<colgroup><col/></colgroup><colgroup><col/><col/><col/></colgroup>
<thead>
<tr>
<th class="r b header" scope="col">#</th>
<th class="b header" scope="col">Name</th>
<th class="b header" scope="col">Member Type</th>
<th class="b header" scope="col">DBMSTYPE</th>
</tr>
</thead>
<tbody>
<tr>
<th class="r rowheader" scope="row">1</th>
<td class="data">APLICACION_SAP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">2</th>
<td class="data">CALIFICACION_EXTERNA_COMERCIAL</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">3</th>
<td class="data">CALIFICACION_EXTERNA_CONSUMO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">4</th>
<td class="data">CALIFICACION_EXTERNA_MICRO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">5</th>
<td class="data">CALIFICACION_EXTERNA_VIVIENDA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">6</th>
<td class="data">CALIFICACION_INTERNA_COMERCIAL</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">7</th>
<td class="data">CALIFICACION_INTERNA_CONSUMO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">8</th>
<td class="data">CALIFICACION_INTERNA_MICRO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">9</th>
<td class="data">CALIFICACION_INTERNA_VIVIENDA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">10</th>
<td class="data">CARTERA_CON_REV_1000</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">11</th>
<td class="data">CLIENTE_FORANEO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">12</th>
<td class="data">COLGAAP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">13</th>
<td class="data">CONTROL_VERSION</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">14</th>
<td class="data">ENTIDAD_RELACIONADA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">15</th>
<td class="data">FORMATO110</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">16</th>
<td class="data">HOMOLOGACION_SAP_PRODUCTO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">17</th>
<td class="data">MODALIDAD</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">18</th>
<td class="data">MODALIDAD_EMP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">19</th>
<td class="data">PLANES EMPLEADOS</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">20</th>
<td class="data">PROVISION_CON_REV_1000</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
</tbody>
</table>
</div>
</div>
</body>
</html>




**Pregunta 1.** ¿Cuál es la ventaja de usar `libname XLSX` para la carga de los Catálogos Contables? <br><br>
a) Permite acceder los archivos _xlsx_ directamente y trabajar con ellos como si fueran tablas _SAS_. <br>
b) Es un motor que utiliza componente de Microsoft para la carga del _xlsx_. <br>
c) No ofrece ninguna ventaja sobre alternativas como `libname EXCEL` ó `libname PCFILES`. <br>
d) Para la carga de los Catálogos Contables no se emplea `libname XLSX`. 

**Pregunta 2.** En caso de que se requiera ejecutar nuevamente el código anterior ¿Qué sucede si uno de los nombres de las hojas de Excel contiene espacios? <br><br>
a) Falla. Puesto que el nombre de la hoja de _EXCEL_ contiene espacios y el nombre de la tabla SAS resultante no es válido. <br>
b) No falla. En la tabla de resultado resultado aparece la hoja _EXCEL_ aún con espacios. Pero, en caso de intentar acceder a la tabla SAS correspondiente se produce un `error` por no ser un nombre SAS válido. <br>

**Responda la pregunta `3` con base en el `Snippet 2`.**

#### Snippet 2


```sas
libname lcata XLSX ("/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx" 
                    "/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Cuentasconta.xlsx"
                    );
```

**Pregunta 3.** ¿Qué se puede afirmar con respecto del _Snippet 2_? <br><br>
a) Falla. Contiene un error de sintaxis. <br>
b) No falla pero solo asigna a `lcata` las hojas del primer archivo `EXCEL`. <br>
c) No falla y asigna a `lcata` las hojas de ambos archivos `EXCEL`. <br>
d) El `libname XLSX` no soporta múltiples archivos asignados a un mismo `libref`. <br>

**Pregunta 4.** ¿Cuál de los siguientes no hace parte del flujo de los procesos Contables? <br> <br>
a) Interfaz Contable <br> 
b) Controles Reportes <br>
c) Revelaciones <br>
d) Generación Resultado Final

**Pregunta 5.** ¿Cuál es el objetivo del Control Saldos _Base Final_? <br> <br>
a) Verificar que los saldos anteriores de la _base final_ actual sean consistentes con los saldos actuales de la _base final_ anterior <br>
b) Validar que obligaciones tienen saldos $>= 0$ y verifica que se hayan asignado cuentas.<br>
c) Agrupar saldos por cuenta contable.<br>
d) Verificar inconsistencia en cuentas, es decir, identificar cuentas asignadas como `INVALIDAS`.<br>

**Responda las pregunta `6` con base en el `Snippet 3`.**

#### Snippet 3


```sas
/*Concepto Interes */
if( Saldo_Int_Cte_Total NE . ) then 
    do;
        llave_CALIFICACION=catx('#',PUT((Codigo_Clase),$FClasificacion.), Modalidad, Calificacion_Externa,"INTERES",codigo_moneda_aux );
        cuenta=putC(upcase(llave_CALIFICACION),formato);
        CodContCUIFInteresCALIF=TRIM(cuenta);
    end;
```

 Obligacion | Saldo_Int_Cte_Total | CodContCUIFInteresCALIF
-----|---------------------|------------------------
 a   |        0            |      INVALIDA
 s   |        8            |      1410058216
 d   |        -1           |      1410058216
 f   |        0            |      1410058216
 z   |        .            |      INVALIDA

Supongase que se tiene un grupo de obligaciones para las que se requiere calcular el campo `CodContCUIFInteresCALIF` y cuyos saldos se muestran en la tabla anterior. Ahora bien, considere las siguientes afirmaciones: <br><br>
I.   Existe un error de inconsistencia en cuenta en la obligación `z`.<br>
II.  La asignación de cuentas de la tabla no corresponde a la aplicada en el `Snippet 3` puesto que la obligación `z` tiene saldo `missing`.<br>
III. La inconsistencia en `CodContCUIFInteresCALIF` para la obligación `z` **no** aparece en el informe de inconsistencia en cuenta.<br>
IV.  La asignación de cuenta de la obligación `a` es una inconsistencia en cuenta.<br>


**Pregunta 6.** De las afirmaciones anteriores se puede decir que <br> <br>
a) I y I son verdaderas. <br>
b) II, III, IV son verdaderas.<br>
c) Todas son ciertas.<br>
d) II y IV son verdaderas.<br>

**Responda las preguntas `7` con base en el `Snippet 4`.**

##### Snippet 4


```sas
DATA Modalidad_;
    SET LCATA.MODALIDAD (keep=Codigo_Producto Descripcion Rename=(Codigo_Producto=Codig ));
    Codigo = PUT(Codig, 2.);
    DROP Codig;
RUN;

DATA WORK._EG_CFMT;
    LENGTH label $ 50;
    SET Modalidad_ (KEEP=Codigo Descripcion RENAME=(Codigo= start Descripcion=label)) END=__last;
    RETAIN fmtname "FModalidad" type "C";
    end=start;
    OUTPUT;
    IF __last = 1 THEN
        DO;
            hlo = "O";
            label = "CARTERA DE CREDITOS";
            OUTPUT;
    END;
RUN;
```


```sas
proc format library=work ctrlin = _EG_CFMT;
run;
```

Codigo_Producto | Descripcion
----------------|---------------
6	            | VIVIENDA VIS
7	            | VIVIENDA NO VIS
18	            | LEASING HABITACIONAL
19	            | LEASING FINANCIERO
21	            | LEASING FINANCIERO
20	            | CÁNONES DE BIENES DADOS EN LEASING OPERACIONAL


**Pregunta 7.** En el `Snippet 4` se muestra la creación de un formato personalizado utilizando un `PROC FORMAT`. También se muestra la tabla `SAS` con la que se genera el formato. Teniendo en cuenta la información anterior y el seguiente `DATA STEP` es correcto afirmar:


```sas
data test1;
    test1 = put(3, $FModalidad.);
run;

proc print data=test1; run;
```

a) Imprime `INVALIDA`<br>
b) Imprime `CARTERA DE CREDITOS`<br>
c) Imprime `VIVIENDA VIS`<br>
d) Error, no encuentra `FMODALIDAD`.

**Responda la pregunta `8` con base en el `Snippet 5`.**

#### Snippet 5

`Saldos Acumulados` <br>
El reporte saldos acumulados, tiene como objetivo agrupar los saldos por cuentas contables y conceptos, para facilitar al usuario la conciliación.



```sas
/*Asignación de cuentas*/
if( saldo_n NE . ) then 
    do;
        /*
        Se forma llave y se calcula cuenta_n
        */
    end;
```

`Base Final`

| obligacion | cuenta1 | cuenta2  | cuenta3 | saldo1 | saldo2 | saldo3 |
|------------|-------- |----------|---------|--------|--------|--------|
|     1      | 161214  |          | 410051  |    0   |        |   100  |
|     2      | 143122  |  192121  |         |    0   |   -150 |        |
|     3      | 818189  |          |         |    250 |        |        |
|     4      | 161214  |          | 410051  |    250 |        |   -50  |
|     5      | 143122  |  192121  |         |    0   |   -150 |        |

**Pregunta 8.** Teniendo en cuenta la información del `Snippet 5`, el valor del saldo para la cuenta `161214` en el reporte de saldos acumulados es <br><br>
a) 0 <br>
b) 500 <br>
c) 250 <br>
d) 200 <br>


**Pregunta 9.** ¿Qué validación se hace para asignar cuenta? <br> <br>
a) Saldo actual $>= 0$ <br>
b) Saldo anterior $>= 0$ <br>
c) Saldo actual $\not = missing$ ó Saldo anterior $\not = missing$ <br>
d) Saldo actual $> 0$ ó Saldo anterior $> 0$ <br>

**Pregunta 10.** ¿Cuál es el directorio donde se alojan los reportes `XLSX` generados en Controles Reportes? <br> <br> 
a) SAS_Salidas <br>
b) SAS_DataMart <br>
c) SAS_Controles_Reportes <br>
d) SAS_Catalogos

**Pregunta 11.** ¿Dónde se encuentra parametrizado el cuerpo y asunto del correo de notificaciones para Controles Reportes? <br> <br>
a) Parámetros Notificaciones <br>
b) Catálogo Emails <br>
c) Notificaciones Controles Reportes <br>
d) Parámetros Controles Reportes <br>

**Pregunta 12.** ¿Qué tabla se debe revisar si se requiere ajustar el correo o lista distribución a la que se envian las notificaciones de Controles Reportes?<br> <br>
a) Parámetros Notificaciones<br>
b) Catálogo Emails<br>
c) Notificaciones Controles Reportes<br>
d) Parámetros Controles Reportes<br>

**Pregunta 13.** ¿Cuál es el objetivo del Reporte Balance Comparativo y Delta?<br><br>
a) Contiene las Cuentas de Ajuste para la _Interfaz Contable_.<br>
b) Facilitar la Conciliación de Saldos Acumulados. <br>
c) Informar los saldos de SAS por cuentas contables y el valor del Delta.<br>
d) Garantizar la consistenia de la _Interfaz Contable_. <br>

**Pregunta 14.** ¿Qué control tiene como objetivo verificar que todas las obligaciones que posean saldo en cada uno de los conceptos (Capital, Intereses, Cuentas por Cobrar y/o Otros Conceptos) tenga asociada una calificación? <br><br>
a) Inconsistencia en Cuentas <br>
b) Error Calificación <br>
c) Saldos Acumulados <br>
d) Intereses Bucket 3 <br>


**Pregunta 15.** Si se desea ampliar el plazo del día límite de espera del archivo ERP del balance SAP para que sea efectivo en la ejecución del proceso de `Cargar Balance`, ¿cuál es la tabla que contiene el parámetro a ser ajustado? <br> <br>
a) Parametros Generales<br>
b) Parametros Switch<br>
c) Parametros Notificaciones<br>
d) Parametros Contables<br>

**Pregunta 16.** En el proceso de generación de la _Base Final_ se hace válidación de registros duplicados?<br><br>
a) Si, en Generales Calificación hay una macro que verifica la existencia de registros duplicados en el insumo de Resultado Final.<br>
b) No, no es necesario hacer validación de registros duplicados puesto que desde Perdida Esperada garantizan la consistencia de ls datos. <br>

**Responda la pregunta `17` con base en el `Snippet 6`.**

#### Snippet 6
ERROR: El archivo LIB_BCO.BCO_SEGMENTO_GENERALES_31JAN2018.DATA no existe.
**Pregunta 17.** La causa más probable para que en la ejecución de la malla contable se presente un error como el que aprece en el Snippet 6 es <br><br>
a) No se ejecutó el orden adecuado la generación de la Base Final.<br>
b) No se generó el insumo `LIB_BCO.BSP_SEGMENTO_GENERALES_31JAN2018.DATA` desde PE.<br>
c) No se hizo una adecuada segmentación en los formatos de revelaciones. <br>
d) No es un error que se presente en el flujo de la malla contable. <br>

**Pregunta 18.** ¿Cuál es el orden correcto de ejcución de la _Base Final_? <br><br>
a) Resultado Final - Generales Calificación - Saldos Bucket 3 - Saldos Cuentas Temp Calif - Cuentas Provision - Provision Prorrateo - Base Final <br>
b) Base Cero - Saldos Bucket 3 - Saldos Cuentas  Temp Calif - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
c) Generales Calificación - Saldos Bucket 3 - Saldos Cuentas  Temp Calif - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
d) Generales Calificación - Saldos Cuentas  Temp Calif - Saldos Bucket 3 - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
