<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<title>x9-lrn-resources</title>
<!-- 2018-03-23 Fri 17:49 -->
<meta  http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta  name="generator" content="Org-mode" />
<meta  name="author" content="wintermute" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center; }
  .todo   { font-family: monospace; color: red; }
  .done   { color: green; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  pre.src-sh:before    { content: 'sh'; }
  pre.src-bash:before  { content: 'sh'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-R:before     { content: 'R'; }
  pre.src-perl:before  { content: 'Perl'; }
  pre.src-java:before  { content: 'Java'; }
  pre.src-sql:before   { content: 'SQL'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.right  { text-align: center;  }
  th.left   { text-align: center;   }
  th.center { text-align: center; }
  td.right  { text-align: right;  }
  td.left   { text-align: left;   }
  td.center { text-align: center; }
  dt { font-weight: bold; }
  .footpara:nth-child(2) { display: inline; }
  .footpara { display: block; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2013 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
<script type="text/javascript" src="http://orgmode.org/mathjax/MathJax.js"></script>
<script type="text/javascript">
<!--/*--><![CDATA[/*><!--*/
    MathJax.Hub.Config({
        // Only one of the two following lines, depending on user settings
        // First allows browser-native MathML display, second forces HTML/CSS
        //  config: ["MMLorHTML.js"], jax: ["input/TeX"],
            jax: ["input/TeX", "output/HTML-CSS"],
        extensions: ["tex2jax.js","TeX/AMSmath.js","TeX/AMSsymbols.js",
                     "TeX/noUndefined.js"],
        tex2jax: {
            inlineMath: [ ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"], ["\\begin{displaymath}","\\end{displaymath}"] ],
            skipTags: ["script","noscript","style","textarea","pre","code"],
            ignoreClass: "tex2jax_ignore",
            processEscapes: false,
            processEnvironments: true,
            preview: "TeX"
        },
        showProcessingMessages: true,
        displayAlign: "center",
        displayIndent: "2em",

        "HTML-CSS": {
             scale: 100,
             availableFonts: ["STIX","TeX"],
             preferredFont: "TeX",
             webFont: "TeX",
             imageFont: "TeX",
             showMathMenu: true,
        },
        MMLorHTML: {
             prefer: {
                 MSIE:    "MML",
                 Firefox: "MML",
                 Opera:   "HTML",
                 other:   "HTML"
             }
        }
    });
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<h1 class="title">x9-lrn-resources</h1>
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. lrn&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn">lrn</span></span></a>
<ul>
<li><a href="#sec-1-1">1.1. lrn-bioinformatics</a>
<ul>
<li><a href="#sec-1-1-1">1.1.1. </a></li>
<li><a href="#sec-1-1-2">1.1.2. learn by doing </a></li>
</ul>
</li>
<li><a href="#sec-1-2">1.2. lrn-business</a>
<ul>
<li><a href="#sec-1-2-1">1.2.1. IP intellectual property</a></li>
<li><a href="#sec-1-2-2">1.2.2. from Icon mag: in europe, of 10k food products launched every year, 50% fail within 3 months, 95% fail within 2 years</a></li>
<li><a href="#sec-1-2-3">1.2.3. lrn-accounting</a></li>
</ul>
</li>
<li><a href="#sec-1-3">1.3. lrn-clothing&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_clothing">lrn_clothing</span></span></a>
<ul>
<li><a href="#sec-1-3-1">1.3.1. shoes</a></li>
</ul>
</li>
<li><a href="#sec-1-4">1.4. lrn-compsci</a>
<ul>
<li><a href="#sec-1-4-1">1.4.1. </a></li>
<li><a href="#sec-1-4-2">1.4.2. </a></li>
<li><a href="#sec-1-4-3">1.4.3. </a></li>
<li><a href="#sec-1-4-4">1.4.4. </a></li>
<li><a href="#sec-1-4-5">1.4.5. apparently loading data from a binary instead of a plaintext is 5-20x faster?</a></li>
<li><a href="#sec-1-4-6">1.4.6. The Big List of Naughty Strings (strings likely to cause issues as input) | Hacker News </a></li>
<li><a href="#sec-1-4-7">1.4.7. diagramming software: lucid charts chrome app</a></li>
<li><a href="#sec-1-4-8">1.4.8. lrn-apis</a></li>
<li><a href="#sec-1-4-9">1.4.9. lrn-algorithms-lrn-data-structures</a></li>
<li><a href="#sec-1-4-10">1.4.10. lrn-coding-style</a></li>
<li><a href="#sec-1-4-11">1.4.11. lrn-compilers</a></li>
<li><a href="#sec-1-4-12">1.4.12. lrn-cloud</a></li>
<li><a href="#sec-1-4-13">1.4.13. lrn-crypto lrn-encryption</a></li>
<li><a href="#sec-1-4-14">1.4.14. lrn-css-lrn-html-lrn-websites-lrn-web-programming</a></li>
<li><a href="#sec-1-4-15">1.4.15. lrn-debugging</a></li>
<li><a href="#sec-1-4-16">1.4.16. lrn-emacs-lrn-vim</a></li>
<li><a href="#sec-1-4-17">1.4.17. lrn-excel</a></li>
<li><a href="#sec-1-4-18">1.4.18. lrn-flowcharts</a></li>
<li><a href="#sec-1-4-19">1.4.19. lrn-functional-programming</a></li>
<li><a href="#sec-1-4-20">1.4.20. lrn-games (including finished ones I already own)</a></li>
<li><a href="#sec-1-4-21">1.4.21. lrn-git</a></li>
<li><a href="#sec-1-4-22">1.4.22. lrn-gpu</a></li>
<li><a href="#sec-1-4-23">1.4.23. lrn-hardware</a></li>
<li><a href="#sec-1-4-24">1.4.24. lrn-hdf5</a></li>
<li><a href="#sec-1-4-25">1.4.25. lrn-image-formats</a></li>
<li><a href="#sec-1-4-26">1.4.26. lrn-irc (lrn-irssi)</a></li>
<li><a href="#sec-1-4-27">1.4.27. lrn-langs</a></li>
<li><a href="#sec-1-4-28">1.4.28. lrn-linux</a></li>
<li><a href="#sec-1-4-29">1.4.29. lrn-low-level-programming</a></li>
<li><a href="#sec-1-4-30">1.4.30. lrn-nginx</a></li>
<li><a href="#sec-1-4-31">1.4.31. lrn-organizational software</a></li>
<li><a href="#sec-1-4-32">1.4.32. lrn-pandoc-lrn-markdown-lrn-plaintext-writing</a></li>
<li><a href="#sec-1-4-33">1.4.33. lrn-privacy-lrn-security</a></li>
<li><a href="#sec-1-4-34">1.4.34. lrn-prog-practices</a></li>
<li><a href="#sec-1-4-35">1.4.35. lrn-regex (regular expressions)</a></li>
<li><a href="#sec-1-4-36">1.4.36. lrn-scientific-programming</a></li>
<li><a href="#sec-1-4-37">1.4.37. lrn-testing-lrn-unit-testing</a></li>
<li><a href="#sec-1-4-38">1.4.38. lrn-tex-lrn-latex</a></li>
<li><a href="#sec-1-4-39">1.4.39. lrn-wasm-lrn-webassembly</a></li>
<li><a href="#sec-1-4-40">1.4.40. lrn-xml</a></li>
</ul>
</li>
<li><a href="#sec-1-5">1.5. lrn-cycling&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_cycling">lrn_cycling</span></span></a>
<ul>
<li><a href="#sec-1-5-1">1.5.1. road bikes to check out</a></li>
</ul>
</li>
<li><a href="#sec-1-6">1.6. lrn-design</a>
<ul>
<li><a href="#sec-1-6-1">1.6.1. core principles for design could just be sufficiently complicated that it's difficult to think of good counterexamples</a></li>
<li><a href="#sec-1-6-2">1.6.2. see kim's list of good websites</a></li>
<li><a href="#sec-1-6-3">1.6.3. go through hack design website</a></li>
<li><a href="#sec-1-6-4">1.6.4. crap way to improve usability </a></li>
<li><a href="#sec-1-6-5">1.6.5. proposal for an interactive introduction to graphics programming</a></li>
<li><a href="#sec-1-6-6">1.6.6. minimalist websites </a></li>
<li><a href="#sec-1-6-7">1.6.7. </a></li>
<li><a href="#sec-1-6-8">1.6.8. lrn-data-visualization</a></li>
<li><a href="#sec-1-6-9">1.6.9. lrn-fonts</a></li>
</ul>
</li>
<li><a href="#sec-1-7">1.7. lrn-diy</a>
<ul>
<li><a href="#sec-1-7-1">1.7.1. lrn-book-binding</a></li>
</ul>
</li>
<li><a href="#sec-1-8">1.8. lrn-economics-lrn-finance&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_economics">lrn_economics</span>&#xa0;<span class="lrn_finance">lrn_finance</span></span></a>
<ul>
<li><a href="#sec-1-8-1">1.8.1. lrn-computational-finance</a></li>
<li><a href="#sec-1-8-2">1.8.2. lrn-credit</a></li>
<li><a href="#sec-1-8-3">1.8.3. lrn-investing</a></li>
<li><a href="#sec-1-8-4">1.8.4. lrn-personal-finance</a></li>
<li><a href="#sec-1-8-5">1.8.5. lrn-ledger</a></li>
<li><a href="#sec-1-8-6">1.8.6. ask salim about that as an intro book, or maybe ap econ?</a></li>
<li><a href="#sec-1-8-7">1.8.7. revenue maybe prop to "buying power", which inv prop to rate (a la actuary guy), for which of course premium is calc from</a></li>
<li><a href="#sec-1-8-8">1.8.8. tightwads and purchasing pain as prop to income and expenses. how to get data on what these are for most people? could match with good accuracy to address alone?</a></li>
<li><a href="#sec-1-8-9">1.8.9. read law stuff on the shell-eni nigerian. malabu deal, in the british high court and another in arbitration?</a></li>
<li><a href="#sec-1-8-10">1.8.10. global witness ngo, tom wayne, maybe discusses docs</a></li>
<li><a href="#sec-1-8-11">1.8.11. </a></li>
<li><a href="#sec-1-8-12">1.8.12. </a></li>
<li><a href="#sec-1-8-13">1.8.13. keep read mankiw (while questioning assumptions, or at least tracking them)</a></li>
<li><a href="#sec-1-8-14">1.8.14. </a></li>
<li><a href="#sec-1-8-15">1.8.15. </a></li>
<li><a href="#sec-1-8-16">1.8.16. best books to learn econ </a></li>
<li><a href="#sec-1-8-17">1.8.17. side money</a></li>
</ul>
</li>
<li><a href="#sec-1-9">1.9. lrn-electrical-computer-engineering</a>
<ul>
<li><a href="#sec-1-9-1">1.9.1. (1 hr) read signals and systems section 8.7 for fm and instant freq for fun</a></li>
<li><a href="#sec-1-9-2">1.9.2. arduino/raspberry pi</a></li>
<li><a href="#sec-1-9-3">1.9.3. lrn-signal-processing (lrn-sig-proc)</a></li>
</ul>
</li>
<li><a href="#sec-1-10">1.10. lrn-Food-drink</a>
<ul>
<li><a href="#sec-1-10-1">1.10.1. lrn-healthy-eating (eating comes before exercise in importance!)</a></li>
<li><a href="#sec-1-10-2">1.10.2. class notes</a></li>
<li><a href="#sec-1-10-3">1.10.3. Get good at drinking!</a></li>
<li><a href="#sec-1-10-4">1.10.4. get good at cooking!</a></li>
<li><a href="#sec-1-10-5">1.10.5. coffee and tea</a></li>
<li><a href="#sec-1-10-6">1.10.6. already made cooking recipes that are good</a></li>
</ul>
</li>
<li><a href="#sec-1-11">1.11. lrn-grooming&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_grooming">lrn_grooming</span></span></a>
<ul>
<li><a href="#sec-1-11-1">1.11.1. lrn-hair&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_hair">lrn_hair</span></span></a></li>
</ul>
</li>
<li><a href="#sec-1-12">1.12. lrn-ergonomics</a>
<ul>
<li><a href="#sec-1-12-1">1.12.1. ergonomic chair stuff </a></li>
</ul>
</li>
<li><a href="#sec-1-13">1.13. lrn-hardware</a>
<ul>
<li><a href="#sec-1-13-1">1.13.1. sony WH-1000xM2 noise-canceling headphones</a></li>
<li><a href="#sec-1-13-2">1.13.2. lrn-knots</a></li>
</ul>
</li>
<li><a href="#sec-1-14">1.14. lrn-history</a>
<ul>
<li><a href="#sec-1-14-1">1.14.1. lrn-chinese-history</a></li>
</ul>
</li>
<li><a href="#sec-1-15">1.15. lrn-home-accoutrements</a>
<ul>
<li><a href="#sec-1-15-1">1.15.1. digitizing paper records from home </a></li>
</ul>
</li>
<li><a href="#sec-1-16">1.16. lrn-languages</a>
<ul>
<li><a href="#sec-1-16-1">1.16.1. dod's learning resources </a></li>
<li><a href="#sec-1-16-2">1.16.2. Katrina says  Pimsleur language learning courses are great</a></li>
<li><a href="#sec-1-16-3">1.16.3. lrn-french</a></li>
<li><a href="#sec-1-16-4">1.16.4. lrn-mandarin-chinese</a></li>
</ul>
</li>
<li><a href="#sec-1-17">1.17. lrn-math</a>
<ul>
<li><a href="#sec-1-17-1">1.17.1. </a></li>
<li><a href="#sec-1-17-2">1.17.2. </a></li>
<li><a href="#sec-1-17-3">1.17.3. </a></li>
<li><a href="#sec-1-17-4">1.17.4. </a></li>
<li><a href="#sec-1-17-5">1.17.5. visualization of math for pedagogy</a></li>
<li><a href="#sec-1-17-6">1.17.6. Ten lessons I wish I had learned before teaching differential equations" [pdf] </a></li>
<li><a href="#sec-1-17-7">1.17.7. peak finding </a></li>
<li><a href="#sec-1-17-8">1.17.8. lrn-calculus</a></li>
<li><a href="#sec-1-17-9">1.17.9. lrn-bond-graphs</a></li>
<li><a href="#sec-1-17-10">1.17.10. lrn-category-theory</a></li>
<li><a href="#sec-1-17-11">1.17.11. lrn-gradient-descent</a></li>
<li><a href="#sec-1-17-12">1.17.12. lrn-information-theory</a></li>
<li><a href="#sec-1-17-13">1.17.13. lrn-lin-alg</a></li>
<li><a href="#sec-1-17-14">1.17.14. lrn-network-graphs</a></li>
<li><a href="#sec-1-17-15">1.17.15. lrn-statistics-lrn-stats</a></li>
</ul>
</li>
<li><a href="#sec-1-18">1.18. lrn-nanoscience-lrn-nanotech</a>
<ul>
<li><a href="#sec-1-18-1">1.18.1. Nanodoc software</a></li>
</ul>
</li>
<li><a href="#sec-1-19">1.19. lrn-neural-networks</a>
<ul>
<li><a href="#sec-1-19-1">1.19.1. </a></li>
<li><a href="#sec-1-19-2">1.19.2. </a></li>
</ul>
</li>
<li><a href="#sec-1-20">1.20. lrn-NS lrn-neuroscience</a>
<ul>
<li><a href="#sec-1-20-1">1.20.1. what is known about coding in neurons? prob have to get into specific region</a></li>
<li><a href="#sec-1-20-2">1.20.2. maybe classify different ways of transfering information between them?</a></li>
<li><a href="#sec-1-20-3">1.20.3. sawtooth beta?????? wtf is up with these waveforms</a></li>
<li><a href="#sec-1-20-4">1.20.4. if learn stuff about thal, can maybe help with parkinson's?</a></li>
<li><a href="#sec-1-20-5">1.20.5. rlnshp b/w D1 DA rec b/w epi &amp; park's</a></li>
<li><a href="#sec-1-20-6">1.20.6. inactivation variables</a></li>
<li><a href="#sec-1-20-7">1.20.7. lrn-fmri</a></li>
<li><a href="#sec-1-20-8">1.20.8. lrn-iit</a></li>
<li><a href="#sec-1-20-9">1.20.9. lrn-holonomic-brain-theory</a></li>
<li><a href="#sec-1-20-10">1.20.10. lrn-neuro-anatomy (lrn-anatomy) lrn-neuroanatomy</a></li>
<li><a href="#sec-1-20-11">1.20.11. lrn-neuro-methods</a></li>
<li><a href="#sec-1-20-12">1.20.12. lrn-neuro-rhythms</a></li>
<li><a href="#sec-1-20-13">1.20.13. lrn-nootropics</a></li>
<li><a href="#sec-1-20-14">1.20.14. lrn-compu-ns</a></li>
</ul>
</li>
<li><a href="#sec-1-21">1.21. lrn-philosophy</a>
<ul>
<li><a href="#sec-1-21-1">1.21.1. lrn-logic</a></li>
</ul>
</li>
<li><a href="#sec-1-22">1.22. lrn-physics</a>
<ul>
<li><a href="#sec-1-22-1">1.22.1. accumulate ?</a></li>
<li><a href="#sec-1-22-2">1.22.2. go back over krane's intro (nick james has krane)</a></li>
<li><a href="#sec-1-22-3">1.22.3. study general relativity, like einstein's book?</a></li>
<li><a href="#sec-1-22-4">1.22.4. Could warp across space-time by generating points of huge gravity, from either huge masses or masses from energy?</a></li>
<li><a href="#sec-1-22-5">1.22.5. books (look at this e-library) </a></li>
<li><a href="#sec-1-22-6">1.22.6. why momentum works </a></li>
<li><a href="#sec-1-22-7">1.22.7. </a></li>
<li><a href="#sec-1-22-8">1.22.8. </a></li>
</ul>
</li>
<li><a href="#sec-1-23">1.23. lrn-politics</a>
<ul>
<li><a href="#sec-1-23-1">1.23.1. find news source for local political news, pay attn to local politics</a></li>
<li><a href="#sec-1-23-2">1.23.2. go over thinktanks </a></li>
<li><a href="#sec-1-23-3">1.23.3. use findthedata.org</a></li>
<li><a href="#sec-1-23-4">1.23.4. also check out google's publicdata thing?</a></li>
<li><a href="#sec-1-23-5">1.23.5. read less wrong, maybe take notes on essays? do the starter sequence</a></li>
<li><a href="#sec-1-23-6">1.23.6. look anti nuclear stuff to see what they say point by point</a></li>
<li><a href="#sec-1-23-7">1.23.7. add to um to listen? podcasts </a></li>
<li><a href="#sec-1-23-8">1.23.8. open-politics, a la open political data </a></li>
</ul>
</li>
<li><a href="#sec-1-24">1.24. lrn-productivity</a>
<ul>
<li><a href="#sec-1-24-1">1.24.1. wtf mdwiki allows wikis on github pages sites???</a></li>
<li><a href="#sec-1-24-2">1.24.2. lrn-procrastination</a></li>
</ul>
</li>
<li><a href="#sec-1-25">1.25. lrn-prof-dev-lrn-professional-development</a>
<ul>
<li><a href="#sec-1-25-1">1.25.1. 20130326 professional devlpmt talk</a></li>
<li><a href="#sec-1-25-2">1.25.2. lrn-leadership</a></li>
<li><a href="#sec-1-25-3">1.25.3. lrn-networking lrn-professional-networking / long-term-networking</a></li>
<li><a href="#sec-1-25-4">1.25.4. lrn-presn, lrn-presentations</a></li>
<li><a href="#sec-1-25-5">1.25.5. lrn-industry</a></li>
</ul>
</li>
<li><a href="#sec-1-26">1.26. lrn-ripping</a>
<ul>
<li><a href="#sec-1-26-1">1.26.1. DVDs</a></li>
<li><a href="#sec-1-26-2">1.26.2. CDs</a></li>
</ul>
</li>
<li><a href="#sec-1-27">1.27. lrn-sailing&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_sailing">lrn_sailing</span></span></a>
<ul>
<li><a href="#sec-1-27-1">1.27.1. sailing notes, day 1 2014-09-20</a></li>
<li><a href="#sec-1-27-2">1.27.2. sailing notes, day 2 2014-09-21</a></li>
<li><a href="#sec-1-27-3">1.27.3. sailing notes, day 3 2014-09-27</a></li>
<li><a href="#sec-1-27-4">1.27.4. sailing notes, day 4 2014-09-28</a></li>
</ul>
</li>
<li><a href="#sec-1-28">1.28. lrn-science-curation</a>
<ul>
<li><a href="#sec-1-28-1">1.28.1. researchgate and </a></li>
</ul>
</li>
<li><a href="#sec-1-29">1.29. lrn-science-policy</a>
<ul>
<li><a href="#sec-1-29-1">1.29.1. criticism of peer review</a></li>
<li><a href="#sec-1-29-2">1.29.2. reproducibility crisis</a></li>
</ul>
</li>
<li><a href="#sec-1-30">1.30. lrn-sociology</a></li>
<li><a href="#sec-1-31">1.31. lrn-social-movements</a>
<ul>
<li><a href="#sec-1-31-1">1.31.1. lrn-activism</a></li>
<li><a href="#sec-1-31-2">1.31.2. lrn-effective-altruism EA</a></li>
<li><a href="#sec-1-31-3">1.31.3. lrn-feminism</a></li>
<li><a href="#sec-1-31-4">1.31.4. lrn-labor-rights</a></li>
<li><a href="#sec-1-31-5">1.31.5. lrn-lrning</a></li>
<li><a href="#sec-1-31-6">1.31.6. lrn-quantified-self</a></li>
<li><a href="#sec-1-31-7">1.31.7. lrn-transhumanism</a></li>
</ul>
</li>
<li><a href="#sec-1-32">1.32. lrn-studying lrn-reading</a>
<ul>
<li><a href="#sec-1-32-1">1.32.1. PQRST system - Preview, Question, Read, Summary, Test</a></li>
<li><a href="#sec-1-32-2">1.32.2. Studying for Science, in calibre</a></li>
<li><a href="#sec-1-32-3">1.32.3. </a></li>
<li><a href="#sec-1-32-4">1.32.4. how to read a book</a></li>
<li><a href="#sec-1-32-5">1.32.5. lrn-trackers</a></li>
</ul>
</li>
<li><a href="#sec-1-33">1.33. lrn-symbolic-logic</a>
<ul>
<li><a href="#sec-1-33-1">1.33.1. learn symbolic regression</a></li>
<li><a href="#sec-1-33-2">1.33.2. jason's idea to optimize models based on fundamental laws of physical systems derived from symbolic logic,</a></li>
</ul>
</li>
<li><a href="#sec-1-34">1.34. lrn-teaching</a>
<ul>
<li><a href="#sec-1-34-1">1.34.1. avery's first-year grad school teacher starts class with an open ended question, and connects people's answers in a web through discussion, and then saves and posts to the web</a></li>
</ul>
</li>
<li><a href="#sec-1-35">1.35. lrn-traveling</a>
<ul>
<li><a href="#sec-1-35-1">1.35.1. eventually should learn air deals via </a></li>
<li><a href="#sec-1-35-2">1.35.2. can track trends via </a></li>
</ul>
</li>
<li><a href="#sec-1-36">1.36. lrn-writing</a>
<ul>
<li><a href="#sec-1-36-1">1.36.1. </a></li>
<li><a href="#sec-1-36-2">1.36.2. brian nosek says In writing, lead with the evidence, follow with the explanation.</a></li>
<li><a href="#sec-1-36-3">1.36.3. writing essay to eric denovellis after briefly reading chapters of his thesis:</a></li>
<li><a href="#sec-1-36-4">1.36.4. A manual for writers Kate l turabian</a></li>
<li><a href="#sec-1-36-5">1.36.5. lrn-writing-systems/software! currently using pandoc</a></li>
<li><a href="#sec-1-36-6">1.36.6. lrn-sci-writing</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>
<div id="outline-container-sec-1" class="outline-2">
<h2 id="sec-1"><span class="section-number-2">1</span> lrn&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn">lrn</span></span></h2>
<div class="outline-text-2" id="text-1">
</div><div id="outline-container-sec-1-1" class="outline-3">
<h3 id="sec-1-1"><span class="section-number-3">1.1</span> lrn-bioinformatics</h3>
<div class="outline-text-3" id="text-1-1">
</div><div id="outline-container-sec-1-1-1" class="outline-4">
<h4 id="sec-1-1-1"><span class="section-number-4">1.1.1</span> <a href="http://caporasolab.us/An-Introduction-To-Applied-Bioinformatics/">http://caporasolab.us/An-Introduction-To-Applied-Bioinformatics/</a></h4>
</div>
<div id="outline-container-sec-1-1-2" class="outline-4">
<h4 id="sec-1-1-2"><span class="section-number-4">1.1.2</span> learn by doing <a href="http://rosalind.info/problems/list-view/">http://rosalind.info/problems/list-view/</a></h4>
</div>
</div>
<div id="outline-container-sec-1-2" class="outline-3">
<h3 id="sec-1-2"><span class="section-number-3">1.2</span> lrn-business</h3>
<div class="outline-text-3" id="text-1-2">
</div><div id="outline-container-sec-1-2-1" class="outline-4">
<h4 id="sec-1-2-1"><span class="section-number-4">1.2.1</span> IP intellectual property</h4>
<div class="outline-text-4" id="text-1-2-1">
</div><ol class="org-ol"><li><a id="sec-1-2-1-1" name="sec-1-2-1-1"></a><a href="http://adlervermillion.com/how-to-read-a-patent/">http://adlervermillion.com/how-to-read-a-patent/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-2-2" class="outline-4">
<h4 id="sec-1-2-2"><span class="section-number-4">1.2.2</span> from Icon mag: in europe, of 10k food products launched every year, 50% fail within 3 months, 95% fail within 2 years</h4>
</div>
<div id="outline-container-sec-1-2-3" class="outline-4">
<h4 id="sec-1-2-3"><span class="section-number-4">1.2.3</span> lrn-accounting</h4>
<div class="outline-text-4" id="text-1-2-3">
</div><ol class="org-ol"><li><a id="sec-1-2-3-1" name="sec-1-2-3-1"></a>book Accounting for Programmers<br  /></li>
<li><a id="sec-1-2-3-2" name="sec-1-2-3-2"></a><a href="http://www.learnaccountingforfree.com/">http://www.learnaccountingforfree.com/</a><br  /></li>
<li><a id="sec-1-2-3-3" name="sec-1-2-3-3"></a><a href="http://www.dwmbeancounter.com/tutorial/Tutorial.html">http://www.dwmbeancounter.com/tutorial/Tutorial.html</a> <a href="http://hn.premii.com/#/comments/11239437">http://hn.premii.com/#/comments/11239437</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-3" class="outline-3">
<h3 id="sec-1-3"><span class="section-number-3">1.3</span> lrn-clothing&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_clothing">lrn_clothing</span></span></h3>
<div class="outline-text-3" id="text-1-3">
</div><div id="outline-container-sec-1-3-1" class="outline-4">
<h4 id="sec-1-3-1"><span class="section-number-4">1.3.1</span> shoes</h4>
<div class="outline-text-4" id="text-1-3-1">
</div><ol class="org-ol"><li><a id="sec-1-3-1-1" name="sec-1-3-1-1"></a>Hubero's shoe oil / grease<br  /></li>
<li><a id="sec-1-3-1-2" name="sec-1-3-1-2"></a>waterproofing canvas converse, apparently use fluoropolymer only, not silicon <a href="http://www.ehow.com/how_8383551_waterproof-converse.html">http://www.ehow.com/how_8383551_waterproof-converse.html</a><br  /></li>
<li><a id="sec-1-3-1-3" name="sec-1-3-1-3"></a>ethical shoes<br  /><ol class="org-ol"><li><a id="sec-1-3-1-3-1" name="sec-1-3-1-3-1"></a><a href="https://www.zshoesorganic.com/collections/mens/products/mens-blackout-edition-1?variant=42581730120">https://www.zshoesorganic.com/collections/mens/products/mens-blackout-edition-1?variant=42581730120</a><br  /></li>
<li><a id="sec-1-3-1-3-2" name="sec-1-3-1-3-2"></a><a href="https://www.etnies.com/us/mens/shoes/jameson-ht-4101000468.html?dwvar_4101000468_color=979#start=6">https://www.etnies.com/us/mens/shoes/jameson-ht-4101000468.html?dwvar_4101000468_color=979#start=6</a><br  /></li>
<li><a id="sec-1-3-1-3-3" name="sec-1-3-1-3-3"></a>vegan ? unclear <a href="https://keepcompany.com/products/the-homer-black-non-slip">https://keepcompany.com/products/the-homer-black-non-slip</a><br  /><ol class="org-ol"><li><a id="sec-1-3-1-3-3-1" name="sec-1-3-1-3-3-1"></a>even if not everything they sell is vegan, they do a LOT of things with musicians to donate to social causes like PP, ACLU, etc.<br  /></li></ol>
</li>
<li><a id="sec-1-3-1-3-4" name="sec-1-3-1-3-4"></a><a href="https://shop.ethletic.com/en/trainer/">https://shop.ethletic.com/en/trainer/</a><br  /></li>
<li><a id="sec-1-3-1-3-5" name="sec-1-3-1-3-5"></a>the people's movement<br  /></li>
<li><a id="sec-1-3-1-3-6" name="sec-1-3-1-3-6"></a>veja<br  /></li>
<li><a id="sec-1-3-1-3-7" name="sec-1-3-1-3-7"></a>indosole<br  /></li>
<li><a id="sec-1-3-1-3-8" name="sec-1-3-1-3-8"></a>fancy dress "vegan leather" shoes <a href="https://www.noah-shop.com/en/vegan-mens-shoes/">https://www.noah-shop.com/en/vegan-mens-shoes/</a><br  /></li>
<li><a id="sec-1-3-1-3-9" name="sec-1-3-1-3-9"></a>exercise <a href="https://www.etnies.com/us/mens/shoes/scout-4101000419.html?dwvar_4101000419_color=008#start=37">https://www.etnies.com/us/mens/shoes/scout-4101000419.html?dwvar_4101000419_color=008#start=37</a><br  /></li>
<li><a id="sec-1-3-1-3-10" name="sec-1-3-1-3-10"></a>brooks shoe company makes most shoes vegan? spec in running shoes <a href="http://www.brooksrunning.com/en_us">http://www.brooksrunning.com/en_us</a><br  /></li></ol>
</li></ol>
</div>
</div>
<div id="outline-container-sec-1-4" class="outline-3">
<h3 id="sec-1-4"><span class="section-number-3">1.4</span> lrn-compsci</h3>
<div class="outline-text-3" id="text-1-4">
</div><div id="outline-container-sec-1-4-1" class="outline-4">
<h4 id="sec-1-4-1"><span class="section-number-4">1.4.1</span> <a href="https://www.reddit.com/r/programming/comments/6dd7lg/every_5_minutes_you_spend_writing_code_in_a_new/">https://www.reddit.com/r/programming/comments/6dd7lg/every_5_minutes_you_spend_writing_code_in_a_new/</a></h4>
</div>
<div id="outline-container-sec-1-4-2" class="outline-4">
<h4 id="sec-1-4-2"><span class="section-number-4">1.4.2</span> <a href="https://github.com/Leo-G/DevopsWiki">https://github.com/Leo-G/DevopsWiki</a></h4>
</div>
<div id="outline-container-sec-1-4-3" class="outline-4">
<h4 id="sec-1-4-3"><span class="section-number-4">1.4.3</span> <a href="https://teachyourselfcs.com/">https://teachyourselfcs.com/</a></h4>
</div>
<div id="outline-container-sec-1-4-4" class="outline-4">
<h4 id="sec-1-4-4"><span class="section-number-4">1.4.4</span> <a href="http://composingprograms.com/">http://composingprograms.com/</a></h4>
</div>
<div id="outline-container-sec-1-4-5" class="outline-4">
<h4 id="sec-1-4-5"><span class="section-number-4">1.4.5</span> apparently loading data from a binary instead of a plaintext is 5-20x faster?</h4>
</div>
<div id="outline-container-sec-1-4-6" class="outline-4">
<h4 id="sec-1-4-6"><span class="section-number-4">1.4.6</span> The Big List of Naughty Strings (strings likely to cause issues as input) | Hacker News <a href="https://news.ycombinator.com/item?id=13406119">https://news.ycombinator.com/item?id=13406119</a></h4>
</div>
<div id="outline-container-sec-1-4-7" class="outline-4">
<h4 id="sec-1-4-7"><span class="section-number-4">1.4.7</span> diagramming software: lucid charts chrome app</h4>
</div>
<div id="outline-container-sec-1-4-8" class="outline-4">
<h4 id="sec-1-4-8"><span class="section-number-4">1.4.8</span> lrn-apis</h4>
<div class="outline-text-4" id="text-1-4-8">
</div><ol class="org-ol"><li><a id="sec-1-4-8-1" name="sec-1-4-8-1"></a><a href="https://news.ycombinator.com/item?id=8636758">https://news.ycombinator.com/item?id=8636758</a><br  /></li>
<li><a id="sec-1-4-8-2" name="sec-1-4-8-2"></a>cheatsheets for everything <a href="http://overapi.com/">http://overapi.com/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-9" class="outline-4">
<h4 id="sec-1-4-9"><span class="section-number-4">1.4.9</span> lrn-algorithms-lrn-data-structures</h4>
<div class="outline-text-4" id="text-1-4-9">
</div><ol class="org-ol"><li><a id="sec-1-4-9-1" name="sec-1-4-9-1"></a>visualizing algos: <a href="https://news.ycombinator.com/item?id=7949995">https://news.ycombinator.com/item?id=7949995</a><br  /></li>
<li><a id="sec-1-4-9-2" name="sec-1-4-9-2"></a>data compression explained <a href="http://mattmahoney.net/dc/dce.html">http://mattmahoney.net/dc/dce.html</a><br  /></li>
<li><a id="sec-1-4-9-3" name="sec-1-4-9-3"></a>big data<br  /><ol class="org-ol"><li><a id="sec-1-4-9-3-1" name="sec-1-4-9-3-1"></a><a href="https://ldtopology.wordpress.com/category/data-topology/">https://ldtopology.wordpress.com/category/data-topology/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-9-4" name="sec-1-4-9-4"></a>dictionary of algos and data structures <a href="http://xlinux.nist.gov/dads/">http://xlinux.nist.gov/dads/</a><br  /></li>
<li><a id="sec-1-4-9-5" name="sec-1-4-9-5"></a>algos used in the linux kernel <a href="http://cstheory.stackexchange.com/a/19773">http://cstheory.stackexchange.com/a/19773</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-10" class="outline-4">
<h4 id="sec-1-4-10"><span class="section-number-4">1.4.10</span> lrn-coding-style</h4>
<div class="outline-text-4" id="text-1-4-10">
</div><ol class="org-ol"><li><a id="sec-1-4-10-1" name="sec-1-4-10-1"></a>uni west FL style guide <a href="http://www.cs.uwf.edu/~wilde/gump/codestan.htm">http://www.cs.uwf.edu/~wilde/gump/codestan.htm</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-11" class="outline-4">
<h4 id="sec-1-4-11"><span class="section-number-4">1.4.11</span> lrn-compilers</h4>
<div class="outline-text-4" id="text-1-4-11">
</div><ol class="org-ol"><li><a id="sec-1-4-11-1" name="sec-1-4-11-1"></a>Compiler takes the source files and outputs object files, Linker takes the object files and creates an executable<br  /></li>
<li><a id="sec-1-4-11-2" name="sec-1-4-11-2"></a>installing GCC from scratch <a href="http://stackoverflow.com/a/9450422">http://stackoverflow.com/a/9450422</a>, though the next answer <a href="http://stackoverflow.com/a/10662297">http://stackoverflow.com/a/10662297</a> claims a much easier solution that IIRC worked on my centos office machine<br  /><div class="outline-text-5" id="text-1-4-11-2">
<p>
```
tar xzf gcc-4.6.2.tar.gz
cd gcc-4.6.2
./contrib/download<sub>prerequisites</sub>
cd ..
mkdir objdir
cd objdir
$PWD/../gcc-4.6.2/configure &#x2013;prefix=/opt/gcc-4.6.2
make
make install
```
</p>
</div>
</li>

<li><a id="sec-1-4-11-3" name="sec-1-4-11-3"></a>optimization <a href="http://www.agner.org/optimize/blog/">http://www.agner.org/optimize/blog/</a><br  /></li>
<li><a id="sec-1-4-11-4" name="sec-1-4-11-4"></a>read the dragon book?<br  /></li>
<li><a id="sec-1-4-11-5" name="sec-1-4-11-5"></a><a href="http://c9x.me/compile/bib/">http://c9x.me/compile/bib/</a><br  /></li>
<li><a id="sec-1-4-11-6" name="sec-1-4-11-6"></a><a href="http://steve-yegge.blogspot.com/2007/06/rich-programmer-food.html">http://steve-yegge.blogspot.com/2007/06/rich-programmer-food.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-12" class="outline-4">
<h4 id="sec-1-4-12"><span class="section-number-4">1.4.12</span> lrn-cloud</h4>
<div class="outline-text-4" id="text-1-4-12">
</div><ol class="org-ol"><li><a id="sec-1-4-12-1" name="sec-1-4-12-1"></a><a href="https://www.expeditedssl.com/aws-in-plain-english">https://www.expeditedssl.com/aws-in-plain-english</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-13" class="outline-4">
<h4 id="sec-1-4-13"><span class="section-number-4">1.4.13</span> lrn-crypto lrn-encryption</h4>
<div class="outline-text-4" id="text-1-4-13">
</div><ol class="org-ol"><li><a id="sec-1-4-13-1" name="sec-1-4-13-1"></a><a href="http://blog.sanctum.geek.nz/linux-crypto-introduction/">http://blog.sanctum.geek.nz/linux-crypto-introduction/</a><br  /></li>
<li><a id="sec-1-4-13-2" name="sec-1-4-13-2"></a>learn gpg and pgp finally<br  /><ol class="org-ol"><li><a id="sec-1-4-13-2-1" name="sec-1-4-13-2-1"></a><a href="http://support.gpgtools.org/kb/how-to/first-steps-where-do-i-start-where-do-i-begin">http://support.gpgtools.org/kb/how-to/first-steps-where-do-i-start-where-do-i-begin</a><br  /></li>
<li><a id="sec-1-4-13-2-2" name="sec-1-4-13-2-2"></a><a href="https://futureboy.us/pgp.html">https://futureboy.us/pgp.html</a><br  /></li>
<li><a id="sec-1-4-13-2-3" name="sec-1-4-13-2-3"></a><a href="http://blog.sanctum.geek.nz/linux-crypto-introduction/">http://blog.sanctum.geek.nz/linux-crypto-introduction/</a><br  /></li>
<li><a id="sec-1-4-13-2-4" name="sec-1-4-13-2-4"></a><a href="https://www.phildev.net/pgp/pgp_clear_vs_mime.html">https://www.phildev.net/pgp/pgp_clear_vs_mime.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-13-3" name="sec-1-4-13-3"></a>learn to use linux system keyring<br  /></li>
<li><a id="sec-1-4-13-4" name="sec-1-4-13-4"></a>Should you encrypt or compress first? | Hacker News <a href="https://news.ycombinator.com/item?id=11994286">https://news.ycombinator.com/item?id=11994286</a><br  /></li>
<li><a id="sec-1-4-13-5" name="sec-1-4-13-5"></a>lrn-tor<br  /><ol class="org-ol"><li><a id="sec-1-4-13-5-1" name="sec-1-4-13-5-1"></a>what NOT to do on tor: <a href="https://www.whonix.org/wiki/DoNot">https://www.whonix.org/wiki/DoNot</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-14" class="outline-4">
<h4 id="sec-1-4-14"><span class="section-number-4">1.4.14</span> lrn-css-lrn-html-lrn-websites-lrn-web-programming</h4>
<div class="outline-text-4" id="text-1-4-14">
</div><ol class="org-ol"><li><a id="sec-1-4-14-1" name="sec-1-4-14-1"></a><a href="http://jgthms.com/web-design-in-4-minutes/">http://jgthms.com/web-design-in-4-minutes/</a><br  /></li>
<li><a id="sec-1-4-14-2" name="sec-1-4-14-2"></a><a href="https://github.com/kamranahmedse/developer-roadmap/blob/master/README.md">https://github.com/kamranahmedse/developer-roadmap/blob/master/README.md</a><br  /></li>
<li><a id="sec-1-4-14-3" name="sec-1-4-14-3"></a><a href="http://www.csszengarden.com/">http://www.csszengarden.com/</a><br  /></li>
<li><a id="sec-1-4-14-4" name="sec-1-4-14-4"></a>complete reading list for css <a href="http://demosthenes.info/blog/919/A-Complete-Reading-List-For-CSS">http://demosthenes.info/blog/919/A-Complete-Reading-List-For-CSS</a><br  /></li>
<li><a id="sec-1-4-14-5" name="sec-1-4-14-5"></a><a href="https://www.reddit.com/r/web_design/comments/2x815r/feel_stuck_after_learning_htmlcss_heres_how_to/">https://www.reddit.com/r/web_design/comments/2x815r/feel_stuck_after_learning_htmlcss_heres_how_to/</a><br  /></li>
<li><a id="sec-1-4-14-6" name="sec-1-4-14-6"></a><a href="https://www.reddit.com/r/learnprogramming/comments/3ywzzg/a_small_list_of_publicly_available_css_best/">https://www.reddit.com/r/learnprogramming/comments/3ywzzg/a_small_list_of_publicly_available_css_best/</a><br  /></li>
<li><a id="sec-1-4-14-7" name="sec-1-4-14-7"></a><a href="http://hn.premii.com/#/comments/11093594Awesome%20Web%20Development%20Tools%20and%20Resources">http://hn.premii.com/#/comments/11093594Awesome%20Web%20Development%20Tools%20and%20Resources</a><br  /></li>
<li><a id="sec-1-4-14-8" name="sec-1-4-14-8"></a><a href="https://developer.mozilla.org/en-US/docs/Web/Guide/Introduction_to_Web_development">https://developer.mozilla.org/en-US/docs/Web/Guide/Introduction_to_Web_development</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-15" class="outline-4">
<h4 id="sec-1-4-15"><span class="section-number-4">1.4.15</span> lrn-debugging</h4>
<div class="outline-text-4" id="text-1-4-15">
</div><ol class="org-ol"><li><a id="sec-1-4-15-1" name="sec-1-4-15-1"></a>lrn-gdb<br  /><ol class="org-ol"><li><a id="sec-1-4-15-1-1" name="sec-1-4-15-1-1"></a>gdb tutorial <a href="http://dept-info.labri.fr/~thibault/gdb.html.en">http://dept-info.labri.fr/~thibault/gdb.html.en</a><br  /></li>
<li><a id="sec-1-4-15-1-2" name="sec-1-4-15-1-2"></a><a href="http://www.reddit.com/r/programming/comments/f8qgz/8_gdb_tricks_every_hacker_should_know/][8">http://www.reddit.com/r/programming/comments/f8qgz/8_gdb_tricks_every_hacker_should_know/][8</a> GDB tricks every hacker should know]]<br  /></li></ol>
</li>
<li><a id="sec-1-4-15-2" name="sec-1-4-15-2"></a>lrn-valgrind<br  /><ol class="org-ol"><li><a id="sec-1-4-15-2-1" name="sec-1-4-15-2-1"></a><a href="http://billiob.net/blog/20140330_vgdb.html">http://billiob.net/blog/20140330_vgdb.html</a><br  /></li>
<li><a id="sec-1-4-15-2-2" name="sec-1-4-15-2-2"></a><a href="https://news.ycombinator.com/item?id=8713346][Valgrind">https://news.ycombinator.com/item?id=8713346][Valgrind</a> is much more than a leak checking tool | Hacker News]]<br  /></li></ol>
</li>
<li><a id="sec-1-4-15-3" name="sec-1-4-15-3"></a>build your own debugger in cli <a href="https://github.com/snare/voltron">https://github.com/snare/voltron</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-16" class="outline-4">
<h4 id="sec-1-4-16"><span class="section-number-4">1.4.16</span> lrn-emacs-lrn-vim</h4>
<div class="outline-text-4" id="text-1-4-16">
</div><ol class="org-ol"><li><a id="sec-1-4-16-1" name="sec-1-4-16-1"></a>(Note to anyone reading: I will breathe vim until my dying breath, but after thinking long and hard about it, for a language like Python that has such a powerful, FOSS IDE like PyCharm, the time, complexity, <b>stability</b>, and cross-platform cost to get a similar environment working is just too high.<br  /><ol class="org-ol"><li><a id="sec-1-4-16-1-1" name="sec-1-4-16-1-1"></a>also, "org-mode" alone justifies at least some usage of Emacs/Spacemacs ;)<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-2" name="sec-1-4-16-2"></a>:( in thinking about vim autocomplete working with libraries etc., didn't even think about if they have anaconda/environment support&#x2026;which this <a href="https://www.reddit.com/r/Python/comments/414vx1/vim_best_way_to_setup_autocomplete_for_python_3/cz0j415/">https://www.reddit.com/r/Python/comments/414vx1/vim_best_way_to_setup_autocomplete_for_python_3/cz0j415/</a> says it's more trouble than it's worth<br  /></li>
<li><a id="sec-1-4-16-3" name="sec-1-4-16-3"></a>more likewise vim failure comments <a href="https://www.reddit.com/r/Python/comments/copik/can_you_autocomplete_function_returns_in_vim/c0u3nyq/">https://www.reddit.com/r/Python/comments/copik/can_you_autocomplete_function_returns_in_vim/c0u3nyq/</a><br  /></li>
<li><a id="sec-1-4-16-4" name="sec-1-4-16-4"></a>These and similar posts on r python make it VERY clear that the plugins powering python in vim are not as feature complete, integrated, or powerful as those in a real ide like pycharm<br  /><ol class="org-ol"><li><a id="sec-1-4-16-4-1" name="sec-1-4-16-4-1"></a><a href="https://www.reddit.com/r/Python/comments/6ac5pk/worth_the_switch_to_pycharm/">https://www.reddit.com/r/Python/comments/6ac5pk/worth_the_switch_to_pycharm/</a><br  /></li>
<li><a id="sec-1-4-16-4-2" name="sec-1-4-16-4-2"></a><a href="https://www.reddit.com/r/Python/comments/6ac5pk/comment/dhdlx4a">https://www.reddit.com/r/Python/comments/6ac5pk/comment/dhdlx4a</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-5" name="sec-1-4-16-5"></a>steven yegge (<a href="https://sites.google.com/site/steveyegge2/effective-emacs">https://sites.google.com/site/steveyegge2/effective-emacs</a>) says, in your editor, if where you need to go is &gt; 5 lines away, you should be using incremental search, not moving there. just as well applies to vim<br  /></li>
<li><a id="sec-1-4-16-6" name="sec-1-4-16-6"></a><a href="https://www.reddit.com/r/Python/comments/6ac5pk/worth_the_switch_to_pycharm/dhdq88h/">https://www.reddit.com/r/Python/comments/6ac5pk/worth_the_switch_to_pycharm/dhdq88h/</a><br  /></li>
<li><a id="sec-1-4-16-7" name="sec-1-4-16-7"></a>vim notes<br  /><ol class="org-ol"><li><a id="sec-1-4-16-7-1" name="sec-1-4-16-7-1"></a>just discovered that in vim, can search for newlines with '\n' a la `s/\n/???/g`, but only way to insert a newline is with '\r', a la `s/\n  \n/\r/g`<br  /></li>
<li><a id="sec-1-4-16-7-2" name="sec-1-4-16-7-2"></a>you can get the values of the current underlying character via `:as`<br  /></li>
<li><a id="sec-1-4-16-7-3" name="sec-1-4-16-7-3"></a>how to delete all but X&#x2026;Y in vim: `g!/.*cosampl0pt7.*15001.*/d`<br  /></li>
<li><a id="sec-1-4-16-7-4" name="sec-1-4-16-7-4"></a>sliming in vim via tmux <a href="https://github.com/epeli/slimux">https://github.com/epeli/slimux</a><br  /></li>
<li><a id="sec-1-4-16-7-5" name="sec-1-4-16-7-5"></a>libs (plugins, really)<br  /><ol class="org-ol"><li><a id="sec-1-4-16-7-5-1" name="sec-1-4-16-7-5-1"></a>autocompletion<br  /><ol class="org-ol"><li><a id="sec-1-4-16-7-5-1-1" name="sec-1-4-16-7-5-1-1"></a>YouCompleteMe<br  /></li>
<li><a id="sec-1-4-16-7-5-1-2" name="sec-1-4-16-7-5-1-2"></a>Neocomplete (formerly NeoComplCache)<br  /></li>
<li><a id="sec-1-4-16-7-5-1-3" name="sec-1-4-16-7-5-1-3"></a>SuperTab (uses built-in, is more for turning &lt;C-x&gt;&lt;C-o&gt; etc. into just &lt;TAB&gt;)<br  /></li>
<li><a id="sec-1-4-16-7-5-1-4" name="sec-1-4-16-7-5-1-4"></a>built-in Omnicomplete (often used in the above?)<br  /></li>
<li><a id="sec-1-4-16-7-5-1-5" name="sec-1-4-16-7-5-1-5"></a>Clang<sub>Complete</sub> (C and C++) <a href="https://github.com/Rip-Rip/clang_complete">https://github.com/Rip-Rip/clang_complete</a><br  /></li>
<li><a id="sec-1-4-16-7-5-1-6" name="sec-1-4-16-7-5-1-6"></a>auxiliary: AutoComplPop: constantly shows the autocomplete choices (probably built-in with good plugins above) <a href="http://www.vim.org/scripts/script.php?script_id=1879">http://www.vim.org/scripts/script.php?script_id=1879</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-7-5-2" name="sec-1-4-16-7-5-2"></a>file finder<br  /><ol class="org-ol"><li><a id="sec-1-4-16-7-5-2-1" name="sec-1-4-16-7-5-2-1"></a>Unite.vim (probably best)<br  /></li>
<li><a id="sec-1-4-16-7-5-2-2" name="sec-1-4-16-7-5-2-2"></a>CommandT (fast, but need to painfully compile Ruby, build with vim ruby support, etc.)<br  /></li>
<li><a id="sec-1-4-16-7-5-2-3" name="sec-1-4-16-7-5-2-3"></a>CtrlP (oldest? slowest? in VimScript)<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-7-5-3" name="sec-1-4-16-7-5-3"></a>snippets<br  /><ol class="org-ol"><li><a id="sec-1-4-16-7-5-3-1" name="sec-1-4-16-7-5-3-1"></a>firstly, see the popular, cross-compatible snippet store at <a href="https://github.com/honza/vim-snippets">https://github.com/honza/vim-snippets</a><br  /></li>
<li><a id="sec-1-4-16-7-5-3-2" name="sec-1-4-16-7-5-3-2"></a>UltiSnips (by default incompatible with YouCompleteMe, but can work well via SuperTab? or .vimrc changes?)<br  /></li>
<li><a id="sec-1-4-16-7-5-3-3" name="sec-1-4-16-7-5-3-3"></a>Neosnippet (same author as Neocomplete, probably works well with Neocomplete?)<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-16-7-6" name="sec-1-4-16-7-6"></a><a href="https://github.com/mhinz/vim-galore">https://github.com/mhinz/vim-galore</a><br  /></li>
<li><a id="sec-1-4-16-7-7" name="sec-1-4-16-7-7"></a>incremental search / replace: `:let i=1 | 38,46g/foo/s//\="bar_".i/ | let i=i+1`<br  /></li>
<li><a id="sec-1-4-16-7-8" name="sec-1-4-16-7-8"></a>insert date: `:r !date`<br  /></li>
<li><a id="sec-1-4-16-7-9" name="sec-1-4-16-7-9"></a>quick paragraph prettify `gqap`<br  /></li>
<li><a id="sec-1-4-16-7-10" name="sec-1-4-16-7-10"></a>folding, 'zfap' folds the paragraph, 'zo' opens, 'zc' closes<br  /></li>
<li><a id="sec-1-4-16-7-11" name="sec-1-4-16-7-11"></a>`:abbr pn penguin`<br  /></li>
<li><a id="sec-1-4-16-7-12" name="sec-1-4-16-7-12"></a>in insert, ctrl-t adds an indent to the line?<br  /></li>
<li><a id="sec-1-4-16-7-13" name="sec-1-4-16-7-13"></a>read json: `:r! curl -s "some<sub>url</sub><sub>to</sub><sub>json</sub>"` then `:%! python -m json.tool`<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-8" name="sec-1-4-16-8"></a>emacs notes<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-1" name="sec-1-4-16-8-1"></a>general emacs notes<br  /><div class="outline-text-6" id="text-1-4-16-8-1">
<ul class="org-ul">
<li>"redo" is weird, some kind of circular buffer
</li>
<li>to switch the "direction" of un/redoing, hit C-r it seems
</li>
<li>how to browse websites?
</li>
<li>mark (for region select) is set by C-space (since I had to rebind tmux :()
</li>
<li>due to super different emacs indention, in Insert mode, can only force a "new" indent via M-i
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-16-8-2" name="sec-1-4-16-8-2"></a>tutorial notes (a la emacs mode)<br  /><div class="outline-text-6" id="text-1-4-16-8-2">
<ul class="org-ul">
<li>C-v and M-v move forward and back a screenful (save for 2 lines so you can read continuously)
</li>
<li>h and l in vim correspond to C-b and C-f
</li>
<li>j and k in vim correspond to C-n and C-p
</li>
<li>b and e (words) in vim " to M-b and M-f
</li>
<li>"meta is usu acting on objects of the language, like sentences, whereas ctrl is usually for raw text"
</li>
<li>0 and $(9, for me) in vim " C-a and C-e
</li>
<li>( and ) (sentences) in vim " M-a and M-e (Emacs' sentence detection is far superior)
</li>
<li>the cursor location is the "point"
</li>
<li>M-&lt; and M-&gt; move to the beginning/end of buffer
</li>
<li>instead of just prefixing command with a number (since it would type the number), either "M-&lt;number&gt; &lt;command&gt;" or prefixing with "C-u &lt;number&gt; &lt;command&gt;" works; the latter is recommended
<ul class="org-ul">
<li>the number in this case is called a "prefix argument"
<ul class="org-ul">
<li>for some commands, the mere presence of a number changes the fundamental behavior of the commands, meaning it acts as a "flag" instead - this is not true of anything so far
</li>
</ul>
</li>
<li>thus, C-u 8 C-f moves forward 8 chars.
</li>
<li>this can also be used for individual characters, like C-u 8 a
</li>
<li>there are some exceptions, like how "C-u &lt;number&gt; C-v" SCROLLS by &lt;number&gt; lines
</li>
</ul>
</li>
<li>C-g is sort of the universal "interrupt and exit command entering"
</li>
<li>some commands are disabled for new users, where typing them opens a window explaining  them
</li>
<li>Emacs, according to its descriptions, appears to have vim-like newlines, where they're simply treated as their own character
</li>
<li>windows
<ul class="org-ul">
<li>C-x 1 closes all windows except one
</li>
</ul>
</li>
<li>killing/yanking = cutting/pasting
</li>
<li>deletion
<ul class="org-ul">
<li>Emacs calls backspace &lt;DEL&gt;, NOT the same as the usual delete key
<ul class="org-ul">
<li>despite this nomenclature, it is not considered a control character
</li>
</ul>
</li>
<li>Emacs can use C-d as the "delete next character" key, or colloquial delete
</li>
<li>M-&lt;DEL&gt; deletes the previous WORD, and M-d deletes thee next word
</li>
<li>when any of these are given an argument, they kill instead of deleting
</li>
</ul>
</li>
<li>killing
<ul class="org-ul">
<li>"killing" means you can reinsert the text, while you can only undo deletion
</li>
<li>C-k kills from cursor to end of line, and M-k kills to the end of the sentence
<ul class="org-ul">
<li>this means, to kill a line AND the newline at the end, you need to hit C-k twice; however, C-u 2 C-k will instead kill 2 whole lines AND their newlines
</li>
</ul>
</li>
<li>C-w kills a region, selected by making a mark via hitting C-space, and then moving the cursor
</li>
</ul>
</li>
<li>yanking
<ul class="org-ul">
<li>"yanking" is the REINSERTION of killed text
</li>
<li>C-y is the basic yank command
</li>
<li>once text is yanked in, can hit M-y repeatedly to exchange the text with earlier kills
</li>
</ul>
</li>
<li>undo
<ul class="org-ul">
<li>C-/ is the basic one
<ul class="org-ul">
<li>C-_ and C-x u are both identical to this
</li>
<li>all equivalences accept a numeric prefix argument as the number of undos
</li>
</ul>
</li>
<li>just like vim, undoing has no effect on the kill ring
</li>
<li>just like vim, commands that don't change the text aren't undone
</li>
</ul>
</li>
<li>files
<ul class="org-ul">
<li>opening files are called "finding" or "visiting" them
</li>
<li>C-x C-f opens a "minibuffer" for looking for a file
<ul class="org-ul">
<li>has rudimentary text completion, including "ls" of the dir in a new window upon TABBING
</li>
<li>this is also how you create new files
</li>
</ul>
</li>
<li>C-x C-s saves changes to a buffer to a file
</li>
</ul>
</li>
<li>buffers
<ul class="org-ul">
<li>C-x C-b lists all the buffers
</li>
<li>ALL things with text in Emacs exist in buffers
</li>
<li>you can reopen a buffer you have been editing with C-x C-f, same as finding the file, or C-x b
</li>
<li>not all buffers are files, like <b>Buffer List</b>, and <b>Messages</b>, and <b>scratch</b>
</li>
<li>you are free to navigate to other buffers without saving your changes in some
</li>
<li>C-x s conveniently asks you if you want to save all changes made to all modiifed buffers
</li>
</ul>
</li>
<li>Extended commands
<ul class="org-ul">
<li>C-x is "Character extend", and is followed by a character
</li>
<li>M-x is "Named command extend", and followed by a long name
</li>
</ul>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-16-8-3" name="sec-1-4-16-8-3"></a>whoa, apparently a vertical split with the large `projects.org` file causes interaction to slow down significantly? but not when it's in a single window in emacs, or even horiz split&#x2026;<br  /></li>
<li><a id="sec-1-4-16-8-4" name="sec-1-4-16-8-4"></a>basically don't use vertical split when working with `projects.org`<br  /></li>
<li><a id="sec-1-4-16-8-5" name="sec-1-4-16-8-5"></a>libraries<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-5-1" name="sec-1-4-16-8-5-1"></a>easy to make "web sequence diagrams" <a href="https://github.com/josteink/wsd-mode">https://github.com/josteink/wsd-mode</a><br  /></li>
<li><a id="sec-1-4-16-8-5-2" name="sec-1-4-16-8-5-2"></a>ess<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-5-2-1" name="sec-1-4-16-8-5-2-1"></a><a href="http://stats.stackexchange.com/questions/13605/what-are-some-good-references-advice-for-learning-emacs-speaks-statistics-with/13613#13613">http://stats.stackexchange.com/questions/13605/what-are-some-good-references-advice-for-learning-emacs-speaks-statistics-with/13613#13613</a><br  /></li>
<li><a id="sec-1-4-16-8-5-2-2" name="sec-1-4-16-8-5-2-2"></a><a href="http://blog.revolutionanalytics.com/2014/03/emacs-ess-and-r-for-zombies.html">http://blog.revolutionanalytics.com/2014/03/emacs-ess-and-r-for-zombies.html</a><br  /></li>
<li><a id="sec-1-4-16-8-5-2-3" name="sec-1-4-16-8-5-2-3"></a>`C-c C-c` ess-eval-region-or-function-or-paragraph-and-step<br  /></li>
<li><a id="sec-1-4-16-8-5-2-4" name="sec-1-4-16-8-5-2-4"></a>`C-c C-j` send line<br  /></li>
<li><a id="sec-1-4-16-8-5-2-5" name="sec-1-4-16-8-5-2-5"></a>`C-c C-r` send region<br  /></li>
<li><a id="sec-1-4-16-8-5-2-6" name="sec-1-4-16-8-5-2-6"></a>`C-c C-b` send buffer<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-8-5-3" name="sec-1-4-16-8-5-3"></a>evil<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-5-3-1" name="sec-1-4-16-8-5-3-1"></a><a href="http://juanjoalvarez.net/es/detail/2014/sep/19/vim-emacsevil-chaotic-migration-guide/">http://juanjoalvarez.net/es/detail/2014/sep/19/vim-emacsevil-chaotic-migration-guide/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-8-5-4" name="sec-1-4-16-8-5-4"></a>paredit<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-5-4-1" name="sec-1-4-16-8-5-4-1"></a><a href="http://danmidwood.com/content/2014/11/21/animated-paredit.html">http://danmidwood.com/content/2014/11/21/animated-paredit.html</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-16-8-6" name="sec-1-4-16-8-6"></a>python (not sure if properly workign? haven't tested in a while as of 2015-03-10)<br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-6-1" name="sec-1-4-16-8-6-1"></a><a href="http://www.jesshamrick.com/2012/09/18/emacs-as-a-python-ide/">http://www.jesshamrick.com/2012/09/18/emacs-as-a-python-ide/</a><br  /><ol class="org-ol"><li><a id="sec-1-4-16-8-6-1-1" name="sec-1-4-16-8-6-1-1"></a>go to the section marked "python environment", where it talks about ipython integration in Emacs, essentially a REPL<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-8-6-2" name="sec-1-4-16-8-6-2"></a>the "python-mode" (and maybe necessary "ipython") packages from Marmalade enable a REPL apparently<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-16-9" name="sec-1-4-16-9"></a>emacs on ipad<br  /><ol class="org-ol"><li><a id="sec-1-4-16-9-1" name="sec-1-4-16-9-1"></a><a href="https://robertwoodward.com/blog/2016/10/19/ssh-client-for-an-emacs-user-on-ios/">https://robertwoodward.com/blog/2016/10/19/ssh-client-for-an-emacs-user-on-ios/</a><br  /></li>
<li><a id="sec-1-4-16-9-2" name="sec-1-4-16-9-2"></a><a href="https://support.jumpdesktop.com/hc/en-us/articles/216423543-iOS-Physical-Keyboard-Support-and-Macros">https://support.jumpdesktop.com/hc/en-us/articles/216423543-iOS-Physical-Keyboard-Support-and-Macros</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-10" name="sec-1-4-16-10"></a>emacs ESS doesn't work with the wickhamverse/tidyverse? then it's not usable by modern standards (use Rstudio instead apparently)<br  /></li>
<li><a id="sec-1-4-16-11" name="sec-1-4-16-11"></a>resources<br  /><ol class="org-ol"><li><a id="sec-1-4-16-11-1" name="sec-1-4-16-11-1"></a>python scripting of vim <a href="http://vimdoc.sourceforge.net/htmldoc/if_pyth.html">http://vimdoc.sourceforge.net/htmldoc/if_pyth.html</a><br  /></li>
<li><a id="sec-1-4-16-11-2" name="sec-1-4-16-11-2"></a>C3F for literate prog of config <a href="http://www.wisdomandwonder.com/wordpress/wp-content/uploads/2014/03/C3F.html">http://www.wisdomandwonder.com/wordpress/wp-content/uploads/2014/03/C3F.html</a><br  /></li>
<li><a id="sec-1-4-16-11-3" name="sec-1-4-16-11-3"></a>emacs for devs <a href="https://github.com/pierre-lecocq/emacs4developers">https://github.com/pierre-lecocq/emacs4developers</a><br  /></li>
<li><a id="sec-1-4-16-11-4" name="sec-1-4-16-11-4"></a>emacs git packages <a href="http://www.reddit.com/r/emacs/comments/2ccqt1/evilfriendly_git_package/cje7k96">http://www.reddit.com/r/emacs/comments/2ccqt1/evilfriendly_git_package/cje7k96</a><br  /></li>
<li><a id="sec-1-4-16-11-5" name="sec-1-4-16-11-5"></a>visualization for learning emacs things <a href="http://sachachua.com/blog/book-thinking-with-emacs/">http://sachachua.com/blog/book-thinking-with-emacs/</a><br  /></li>
<li><a id="sec-1-4-16-11-6" name="sec-1-4-16-11-6"></a><a href="https://github.com/SirVer/ultisnips">https://github.com/SirVer/ultisnips</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12" name="sec-1-4-16-12"></a>org-mode notes<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-1" name="sec-1-4-16-12-1"></a>simple commands<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-1-1" name="sec-1-4-16-12-1-1"></a>`tab` cycles<br  /></li>
<li><a id="sec-1-4-16-12-1-2" name="sec-1-4-16-12-1-2"></a>`C-c t` cycles through TODO-DONE-blank for a correctly formatted star/headline item<br  /></li>
<li><a id="sec-1-4-16-12-1-3" name="sec-1-4-16-12-1-3"></a>`C-c , &lt;either case priority letter&gt;` gives an priority to that item, though it needs to be a TODO to show up on agenda<br  /></li>
<li><a id="sec-1-4-16-12-1-4" name="sec-1-4-16-12-1-4"></a>whoa, apparently the below two work not just on org headers, but also markdown-style unordered lists! however, they convert any ordered lists into unordered lists in this case<br  /></li>
<li><a id="sec-1-4-16-12-1-5" name="sec-1-4-16-12-1-5"></a>`M-return` basically gives you new headings at the 'current' level. It either<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-1-5-1" name="sec-1-4-16-12-1-5-1"></a>if it's not a header already, adds beginning stars to current line, turning it into heading of the 'most recent' order (top-to-bottom), or<br  /></li>
<li><a id="sec-1-4-16-12-1-5-2" name="sec-1-4-16-12-1-5-2"></a>if the line is already at that level heading AND the cursor is NOT in the first column, starts a new heading on the line below it that's ready for text input, moving all text to the right of the cursor (including under it) down to that new header. (This means a clean heading is created below if you're in Insert mode at the end of the above heading.)<br  /></li>
<li><a id="sec-1-4-16-12-1-5-3" name="sec-1-4-16-12-1-5-3"></a>if the line is already at that level heading AND the cursor IS in the first column, starts a new heading on the line ABOVE it that's ready for text input (so can then M-down to move it)<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12-1-6" name="sec-1-4-16-12-1-6"></a>`M-left/right` left = moves header to a higher level (less stars), right = lowers heading level. (This works too en masse for Visual general selection, even taking care of non-header material correctly, but not Visual Block / vertical selection.)<br  /></li>
<li><a id="sec-1-4-16-12-1-7" name="sec-1-4-16-12-1-7"></a>`M-down/up` down = moves current header down the buffer amongst headers of the same level, keeping the cursor on it, and likewise for up; stops when reaching a header of a higher level.<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12-2" name="sec-1-4-16-12-2"></a>install<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-2-1" name="sec-1-4-16-12-2-1"></a>there is a bug using ELPA packages etc. where you must not call ANY org functions before installing the FULL org package correctly - this means you need to comment out org settings set in ~/.emacs. It's dumb.<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12-3" name="sec-1-4-16-12-3"></a>you have to install capture mode - see the manual - where you use `C-c c`<br  /></li>
<li><a id="sec-1-4-16-12-4" name="sec-1-4-16-12-4"></a>MobileOrg<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-4-1" name="sec-1-4-16-12-4-1"></a>Note that org/relevant-files.org is the "index file" for MobileOrg, so it knows the notes I care about, I guess I have to individually link to them?<br  /></li>
<li><a id="sec-1-4-16-12-4-2" name="sec-1-4-16-12-4-2"></a>You add JUST the paths to all the files you want on MobileOrg, not direct files links. Note that this is documented nowhere.<br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12-5" name="sec-1-4-16-12-5"></a><a href="http://doc.norang.ca/org-mode.html">http://doc.norang.ca/org-mode.html</a><br  /></li>
<li><a id="sec-1-4-16-12-6" name="sec-1-4-16-12-6"></a>org-babel / literate-programming<br  /><ol class="org-ol"><li><a id="sec-1-4-16-12-6-1" name="sec-1-4-16-12-6-1"></a><a href="https://github.com/fniessen/refcard-org-babel/blob/master/Org-Babel-refcard.org">https://github.com/fniessen/refcard-org-babel/blob/master/Org-Babel-refcard.org</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-12-7" name="sec-1-4-16-12-7"></a>html export images can have attributes modofied, but must be members of unordered lists <a href="http://stackoverflow.com/a/17176870">http://stackoverflow.com/a/17176870</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-16-13" name="sec-1-4-16-13"></a>lrn-idea-vim-lrn-pycharm<br  /><ol class="org-ol"><li><a id="sec-1-4-16-13-1" name="sec-1-4-16-13-1"></a><a href="https://stackoverflow.com/questions/5585687/is-there-a-way-to-get-ideavim-to-honor-the-mappings-from-my-vimrc-file/23371030#23371030">https://stackoverflow.com/questions/5585687/is-there-a-way-to-get-ideavim-to-honor-the-mappings-from-my-vimrc-file/23371030#23371030</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-17" class="outline-4">
<h4 id="sec-1-4-17"><span class="section-number-4">1.4.17</span> lrn-excel</h4>
<div class="outline-text-4" id="text-1-4-17">
</div><ol class="org-ol"><li><a id="sec-1-4-17-1" name="sec-1-4-17-1"></a>why not to use Excel in science<br  /><ol class="org-ol"><li><a id="sec-1-4-17-1-1" name="sec-1-4-17-1-1"></a><a href="https://www.reddit.com/r/programming/comments/4zbw6h/excel_conversion_errors_are_all_over_the_place_in/">https://www.reddit.com/r/programming/comments/4zbw6h/excel_conversion_errors_are_all_over_the_place_in/</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-18" class="outline-4">
<h4 id="sec-1-4-18"><span class="section-number-4">1.4.18</span> lrn-flowcharts</h4>
<div class="outline-text-4" id="text-1-4-18">
</div><ol class="org-ol"><li><a id="sec-1-4-18-1" name="sec-1-4-18-1"></a><a href="http://users.evtek.fi/~jaanah/IntroC/DBeech/3gl_flow.htm">http://users.evtek.fi/~jaanah/IntroC/DBeech/3gl_flow.htm</a><br  /></li>
<li><a id="sec-1-4-18-2" name="sec-1-4-18-2"></a><a href="https://en.wikipedia.org/wiki/Flowchart">https://en.wikipedia.org/wiki/Flowchart</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-19" class="outline-4">
<h4 id="sec-1-4-19"><span class="section-number-4">1.4.19</span> lrn-functional-programming</h4>
<div class="outline-text-4" id="text-1-4-19">
</div><ol class="org-ol"><li><a id="sec-1-4-19-1" name="sec-1-4-19-1"></a>monads<br  /><ol class="org-ol"><li><a id="sec-1-4-19-1-1" name="sec-1-4-19-1-1"></a><a href="https://www.youtube.com/watch?v=ZhuHCtR3xq8">https://www.youtube.com/watch?v=ZhuHCtR3xq8</a><br  /><ol class="org-ol"><li><a id="sec-1-4-19-1-1-1" name="sec-1-4-19-1-1-1"></a>monoid is a way of thinking about, the 'type' of a func as the parameter type "to" the return type, and composing funcs to make a new func with the same "type"?<br  /></li>
<li><a id="sec-1-4-19-1-1-2" name="sec-1-4-19-1-1-2"></a>essence of a monoid is how you combine multiple things of the same type (like funcs) in order to create a new thing of the same type<br  /></li>
<li><a id="sec-1-4-19-1-1-3" name="sec-1-4-19-1-1-3"></a>"types are almost the same thing as [mathematical] sets"<br  /></li>
<li><a id="sec-1-4-19-1-1-4" name="sec-1-4-19-1-1-4"></a>"function application" (in func programming) = “calling a function"<br  /></li>
<li><a id="sec-1-4-19-1-1-5" name="sec-1-4-19-1-1-5"></a>the syntax is just “f a" since the func is linear? [based on types?]<br  /></li>
<li><a id="sec-1-4-19-1-1-6" name="sec-1-4-19-1-1-6"></a>his thought is that constructing complexity by making monoids etc. and combining functions is easier to understand and more controllable<br  /></li>
<li><a id="sec-1-4-19-1-1-7" name="sec-1-4-19-1-1-7"></a>can more easily mix and match parts of the system<br  /></li></ol>
</li>
<li><a id="sec-1-4-19-1-2" name="sec-1-4-19-1-2"></a>monads in python, supposed to be v helpful <a href="https://pypi.python.org/pypi/PyMonad/">https://pypi.python.org/pypi/PyMonad/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-19-2" name="sec-1-4-19-2"></a>some links about func prog <a href="http://alexott.net/en/fp/">http://alexott.net/en/fp/</a><br  /></li>
<li><a id="sec-1-4-19-3" name="sec-1-4-19-3"></a><a href="https://news.ycombinator.com/item?id=8676373">https://news.ycombinator.com/item?id=8676373</a><br  /></li>
<li><a id="sec-1-4-19-4" name="sec-1-4-19-4"></a><a href="http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html">http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-20" class="outline-4">
<h4 id="sec-1-4-20"><span class="section-number-4">1.4.20</span> lrn-games (including finished ones I already own)</h4>
<div class="outline-text-4" id="text-1-4-20">
</div><ol class="org-ol"><li><a id="sec-1-4-20-1" name="sec-1-4-20-1"></a>dwarf fortress<br  /><ol class="org-ol"><li><a id="sec-1-4-20-1-1" name="sec-1-4-20-1-1"></a><a href="https://www.reddit.com/r/dwarffortress/comments/log6l/to_bay_12_games_and_the_makers_of_df_utilities/">https://www.reddit.com/r/dwarffortress/comments/log6l/to_bay_12_games_and_the_makers_of_df_utilities/</a><br  /></li>
<li><a id="sec-1-4-20-1-2" name="sec-1-4-20-1-2"></a><a href="https://www.reddit.com/r/dwarffortress/comments/lf8ec/a_new_how_to_series_for_dwarf_fortress/">https://www.reddit.com/r/dwarffortress/comments/lf8ec/a_new_how_to_series_for_dwarf_fortress/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-20-2" name="sec-1-4-20-2"></a>fallout 4 modding<br  /><ol class="org-ol"><li><a id="sec-1-4-20-2-1" name="sec-1-4-20-2-1"></a>to get NMM working on fallout 4, had to make a "Fallout4Custom.ini" like in <a href="http://wiki.nexusmods.com/index.php/Fallout_4_Mod_Installation">http://wiki.nexusmods.com/index.php/Fallout_4_Mod_Installation</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-20-3" name="sec-1-4-20-3"></a>gothic 1 on win10 <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=484664831">https://steamcommunity.com/sharedfiles/filedetails/?id=484664831</a><br  /></li>
<li><a id="sec-1-4-20-4" name="sec-1-4-20-4"></a>gothic 2 with dx11 <a href="https://www.reddit.com/r/gaming/comments/4larhv/gothic_2_dx11mod_yes_thats_a_13_year_old_game/">https://www.reddit.com/r/gaming/comments/4larhv/gothic_2_dx11mod_yes_thats_a_13_year_old_game/</a><br  /></li>
<li><a id="sec-1-4-20-5" name="sec-1-4-20-5"></a>planescape torment on win10 <a href="https://www.gog.com/news/mod_spotlight_planescape_torment_mods_guide">https://www.gog.com/news/mod_spotlight_planescape_torment_mods_guide</a><br  /></li>
<li><a id="sec-1-4-20-6" name="sec-1-4-20-6"></a>stalker modding<br  /><ol class="org-ol"><li><a id="sec-1-4-20-6-1" name="sec-1-4-20-6-1"></a><a href="https://www.reddit.com/r/gaming/comments/1e6yaq/stalker_can_bring_out_the_worst_in_people/c9xqkhd">https://www.reddit.com/r/gaming/comments/1e6yaq/stalker_can_bring_out_the_worst_in_people/c9xqkhd</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-20-7" name="sec-1-4-20-7"></a>skyrim modding<br  /><ol class="org-ol"><li><a id="sec-1-4-20-7-1" name="sec-1-4-20-7-1"></a><a href="http://steamcommunity.com/app/72850/discussions/0/846955554753327781q">http://steamcommunity.com/app/72850/discussions/0/846955554753327781q</a><br  /></li>
<li><a id="sec-1-4-20-7-2" name="sec-1-4-20-7-2"></a><a href="https://www.reddit.com/r/gaming/comments/4m856l/a_skyrim_modpack_with_over_800_mods/">https://www.reddit.com/r/gaming/comments/4m856l/a_skyrim_modpack_with_over_800_mods/</a><br  /></li>
<li><a id="sec-1-4-20-7-3" name="sec-1-4-20-7-3"></a>skyrim the journey <a href="https://www.reddit.com/r/gaming/comments/3ddrjg/this_450_mods_skyrim_is_incredible/">https://www.reddit.com/r/gaming/comments/3ddrjg/this_450_mods_skyrim_is_incredible/</a> and <a href="https://www.reddit.com/r/skyrimjourney/comments/3en2mv/skyrim_journey_faq_what_is_this_thing_all_about/">https://www.reddit.com/r/skyrimjourney/comments/3en2mv/skyrim_journey_faq_what_is_this_thing_all_about/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-20-8" name="sec-1-4-20-8"></a>sleeping dogs on pc<br  /><ol class="org-ol"><li><a id="sec-1-4-20-8-1" name="sec-1-4-20-8-1"></a><a href="https://steamcommunity.com/app/202170/discussions/0/846959520864508574/">https://steamcommunity.com/app/202170/discussions/0/846959520864508574/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-20-9" name="sec-1-4-20-9"></a>shadowrun returns campaigns <a href="http://www.nexusmods.com/shadowrunreturns/mods/topalltime/?adult=2">http://www.nexusmods.com/shadowrunreturns/mods/topalltime/?adult=2</a><br  /></li>
<li><a id="sec-1-4-20-10" name="sec-1-4-20-10"></a>lrn-game-dev<br  /><ol class="org-ol"><li><a id="sec-1-4-20-10-1" name="sec-1-4-20-10-1"></a><a href="https://np.reddit.com/r/videos/comments/3u9k65/guy_makes_a_3d_printed_revolver_fires_it_at_the/cxd3p13">https://np.reddit.com/r/videos/comments/3u9k65/guy_makes_a_3d_printed_revolver_fires_it_at_the/cxd3p13</a><br  /></li>
<li><a id="sec-1-4-20-10-2" name="sec-1-4-20-10-2"></a>lrn-opengl (or don't, because will make me pull my hair out?)<br  /><ol class="org-ol"><li><a id="sec-1-4-20-10-2-1" name="sec-1-4-20-10-2-1"></a><a href="http://hn.premii.com/#/comments/11615788">http://hn.premii.com/#/comments/11615788</a><br  /></li></ol>
</li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-21" class="outline-4">
<h4 id="sec-1-4-21"><span class="section-number-4">1.4.21</span> lrn-git</h4>
<div class="outline-text-4" id="text-1-4-21">
</div><ol class="org-ol"><li><a id="sec-1-4-21-1" name="sec-1-4-21-1"></a><a href="https://github.com/k88hudson/git-flight-rules/blob/master/README.md">https://github.com/k88hudson/git-flight-rules/blob/master/README.md</a><br  /></li>
<li><a id="sec-1-4-21-2" name="sec-1-4-21-2"></a><a href="https://news.ycombinator.com/item?id=15951825">https://news.ycombinator.com/item?id=15951825</a><br  /></li>
<li><a id="sec-1-4-21-3" name="sec-1-4-21-3"></a>abstracted workflow models<br  /><ol class="org-ol"><li><a id="sec-1-4-21-3-1" name="sec-1-4-21-3-1"></a>pull request/feature branch workflow model<br  /><ol class="org-ol"><li><a id="sec-1-4-21-3-1-1" name="sec-1-4-21-3-1-1"></a>good expl of post PR cleanup <a href="http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/">http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/</a><br  /></li>
<li><a id="sec-1-4-21-3-1-2" name="sec-1-4-21-3-1-2"></a><a href="https://gist.github.com/Chaser324/ce0505fbed06b947d962">https://gist.github.com/Chaser324/ce0505fbed06b947d962</a><br  /></li>
<li><a id="sec-1-4-21-3-1-3" name="sec-1-4-21-3-1-3"></a><a href="http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/">http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-21-3-2" name="sec-1-4-21-3-2"></a>"gitflow" is a popular, shared-repo, for-serious git workflow model <a href="http://datasift.github.io/gitflow/IntroducingGitFlow.html">http://datasift.github.io/gitflow/IntroducingGitFlow.html</a><br  /></li>
<li><a id="sec-1-4-21-3-3" name="sec-1-4-21-3-3"></a><a href="http://nvie.com/posts/a-successful-git-branching-model/">http://nvie.com/posts/a-successful-git-branching-model/</a><br  /></li>
<li><a id="sec-1-4-21-3-4" name="sec-1-4-21-3-4"></a><a href="https://gist.github.com/Chaser324/ce0505fbed06b947d962">https://gist.github.com/Chaser324/ce0505fbed06b947d962</a><br  /></li>
<li><a id="sec-1-4-21-3-5" name="sec-1-4-21-3-5"></a><a href="http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/">http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-21-4" name="sec-1-4-21-4"></a>learning git<br  /><ol class="org-ol"><li><a id="sec-1-4-21-4-1" name="sec-1-4-21-4-1"></a>to create remote tracking branch,<br  /><ol class="org-ol"><li><a id="sec-1-4-21-4-1-1" name="sec-1-4-21-4-1-1"></a>1. create branch with `git checkout -b derp`<br  /></li>
<li><a id="sec-1-4-21-4-1-2" name="sec-1-4-21-4-1-2"></a>2. set up origin/derp to track it with `git branch &#x2013;set-upstream origin/derp`<br  /></li></ol>
</li>
<li><a id="sec-1-4-21-4-2" name="sec-1-4-21-4-2"></a><a href="http://www.wei-wang.com/ExplainGitWithD3/">http://www.wei-wang.com/ExplainGitWithD3/</a><br  /></li>
<li><a id="sec-1-4-21-4-3" name="sec-1-4-21-4-3"></a><a href="http://git-scm.com/book/en/Getting-Started-Git-Basics">http://git-scm.com/book/en/Getting-Started-Git-Basics</a><br  /></li>
<li><a id="sec-1-4-21-4-4" name="sec-1-4-21-4-4"></a>removing file from git but not filesystem <a href="http://stackoverflow.com/questions/1273108/how-do-i-git-rm-a-file-without-deleting-it-from-disk">http://stackoverflow.com/questions/1273108/how-do-i-git-rm-a-file-without-deleting-it-from-disk</a><br  /></li>
<li><a id="sec-1-4-21-4-5" name="sec-1-4-21-4-5"></a>pull a non master branch into a new clone of existing repo <a href="http://stackoverflow.com/a/72156">http://stackoverflow.com/a/72156</a><br  /></li>
<li><a id="sec-1-4-21-4-6" name="sec-1-4-21-4-6"></a><a href="http://hn.premii.com/#/comments/11142625">Understanding Git for real by exploring the .git directory</a><br  /></li>
<li><a id="sec-1-4-21-4-7" name="sec-1-4-21-4-7"></a><a href="http://rypress.com/tutorials/git/index">http://rypress.com/tutorials/git/index</a><br  /></li>
<li><a id="sec-1-4-21-4-8" name="sec-1-4-21-4-8"></a><a href="https://robots.thoughtbot.com/autosquashing-git-commits">https://robots.thoughtbot.com/autosquashing-git-commits</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-21-5" name="sec-1-4-21-5"></a>libraries/software to help<br  /><ol class="org-ol"><li><a id="sec-1-4-21-5-1" name="sec-1-4-21-5-1"></a>"hub" library for doing GitHub stuff on CLI <a href="https://github.com/github/hub">https://github.com/github/hub</a><br  /></li>
<li><a id="sec-1-4-21-5-2" name="sec-1-4-21-5-2"></a>magit<br  /><ol class="org-ol"><li><a id="sec-1-4-21-5-2-1" name="sec-1-4-21-5-2-1"></a><a href="http://www.masteringemacs.org/article/introduction-magit-emacs-mode-git">http://www.masteringemacs.org/article/introduction-magit-emacs-mode-git</a><br  /></li>
<li><a id="sec-1-4-21-5-2-2" name="sec-1-4-21-5-2-2"></a><a href="http://vickychijwani.me/magit-part-ii/">http://vickychijwani.me/magit-part-ii/</a><br  /></li>
<li><a id="sec-1-4-21-5-2-3" name="sec-1-4-21-5-2-3"></a><a href="http://magit.github.io/master/magit.html#Reflogs">http://magit.github.io/master/magit.html#Reflogs</a><br  /></li>
<li><a id="sec-1-4-21-5-2-4" name="sec-1-4-21-5-2-4"></a><a href="https://www.masteringemacs.org/article/introduction-magit-emacs-mode-git">https://www.masteringemacs.org/article/introduction-magit-emacs-mode-git</a><br  /></li>
<li><a id="sec-1-4-21-5-2-5" name="sec-1-4-21-5-2-5"></a><a href="http://magit.vc/">http://magit.vc/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-21-5-3" name="sec-1-4-21-5-3"></a>visxn: gitk <a href="http://lostechies.com/joshuaflanagan/2010/09/03/use-gitk-to-understand-git/">http://lostechies.com/joshuaflanagan/2010/09/03/use-gitk-to-understand-git/</a><br  /></li>
<li><a id="sec-1-4-21-5-4" name="sec-1-4-21-5-4"></a>visxn: tig <a href="http://jonas.nitro.dk/tig/manual.html">http://jonas.nitro.dk/tig/manual.html</a><br  /></li>
<li><a id="sec-1-4-21-5-5" name="sec-1-4-21-5-5"></a>better configs <a href="https://blog.scottnonnenberg.com/better-git-configuration/">https://blog.scottnonnenberg.com/better-git-configuration/</a> <a href="https://news.ycombinator.com/item?id=14045787">https://news.ycombinator.com/item?id=14045787</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-21-6" name="sec-1-4-21-6"></a>style guides<br  /><ol class="org-ol"><li><a id="sec-1-4-21-6-1" name="sec-1-4-21-6-1"></a><a href="https://github.com/agis-/git-style-guide">https://github.com/agis-/git-style-guide</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-22" class="outline-4">
<h4 id="sec-1-4-22"><span class="section-number-4">1.4.22</span> lrn-gpu</h4>
<div class="outline-text-4" id="text-1-4-22">
</div><ol class="org-ol"><li><a id="sec-1-4-22-1" name="sec-1-4-22-1"></a>nVidia's GPU gems <a href="http://http.developer.nvidia.com/GPUGems/gpugems_part01.html">http://http.developer.nvidia.com/GPUGems/gpugems_part01.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-23" class="outline-4">
<h4 id="sec-1-4-23"><span class="section-number-4">1.4.23</span> lrn-hardware</h4>
<div class="outline-text-4" id="text-1-4-23">
</div><ol class="org-ol"><li><a id="sec-1-4-23-1" name="sec-1-4-23-1"></a>kinesis keyboard<br  /><ol class="org-ol"><li><a id="sec-1-4-23-1-1" name="sec-1-4-23-1-1"></a><a href="http://abarry.org/how-to-fix-a-sticky-kinesis-advantage-keyboard/">http://abarry.org/how-to-fix-a-sticky-kinesis-advantage-keyboard/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-2" name="sec-1-4-23-2"></a>router<br  /><ol class="org-ol"><li><a id="sec-1-4-23-2-1" name="sec-1-4-23-2-1"></a>switching to ddwrt, read the following sites<br  /><ol class="org-ol"><li><a id="sec-1-4-23-2-1-1" name="sec-1-4-23-2-1-1"></a><a href="http://www.dd-wrt.com/phpBB2/viewtopic.php?t=51486">http://www.dd-wrt.com/phpBB2/viewtopic.php?t=51486</a><br  /></li>
<li><a id="sec-1-4-23-2-1-2" name="sec-1-4-23-2-1-2"></a><a href="http://www.dd-wrt.com/wiki/index.php/Installation#.22Flashing.22_Your_Router_with_DD-WRT_Firmware">http://www.dd-wrt.com/wiki/index.php/Installation#.22Flashing.22_Your_Router_with_DD-WRT_Firmware</a><br  /></li>
<li><a id="sec-1-4-23-2-1-3" name="sec-1-4-23-2-1-3"></a>the wiki <a href="http://www.dd-wrt.com/wiki/index.php/Netgear_WNDR3400recommends">http://www.dd-wrt.com/wiki/index.php/Netgear_WNDR3400recommends</a> an older version, and so use the router databse one instead <a href="https://secure.dd-wrt.com/site/support/router-database">https://secure.dd-wrt.com/site/support/router-database</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-2-2" name="sec-1-4-23-2-2"></a>routers suggested by reddit and newegg reviews (2015-01-16)<br  /><ol class="org-ol"><li><a id="sec-1-4-23-2-2-1" name="sec-1-4-23-2-2-1"></a>1. D-link DIR-655 <a href="http://www.amazon.com/D-Link-Wireless-Extreme-N-Gigabit-DIR-655/dp/B000LIFB7S/ref=sr_1_1?ie=UTF8&qid=1421448073&sr=8-1&keywords=dir655">http://www.amazon.com/D-Link-Wireless-Extreme-N-Gigabit-DIR-655/dp/B000LIFB7S/ref=sr_1_1?ie=UTF8&qid=1421448073&sr=8-1&keywords=dir655</a><br  /></li>
<li><a id="sec-1-4-23-2-2-2" name="sec-1-4-23-2-2-2"></a>2. netgear wndr3700 <a href="http://www.newegg.com/Product/Product.aspx?Item=N82E16833122326">http://www.newegg.com/Product/Product.aspx?Item=N82E16833122326</a> (basically the next thing up from the crappy 3400 i have)<br  /></li></ol>
</li>
<li><a id="sec-1-4-23-2-3" name="sec-1-4-23-2-3"></a>open router with openwrt! <a href="https://www.indiegogo.com/projects/turris-omnia-hi-performance-open-source-router#/">https://www.indiegogo.com/projects/turris-omnia-hi-performance-open-source-router#/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-3" name="sec-1-4-23-3"></a>laptops for linux<br  /><ol class="org-ol"><li><a id="sec-1-4-23-3-1" name="sec-1-4-23-3-1"></a><a href="https://news.ycombinator.com/item?id=8260733">https://news.ycombinator.com/item?id=8260733</a><br  /></li>
<li><a id="sec-1-4-23-3-2" name="sec-1-4-23-3-2"></a>site for dell refurbished comps! <a href="http://www.dell.com/learn/us/en/22/campaigns/outlet?c=us&l=en&s=dfh">http://www.dell.com/learn/us/en/22/campaigns/outlet?c=us&l=en&s=dfh</a><br  /></li>
<li><a id="sec-1-4-23-3-3" name="sec-1-4-23-3-3"></a>as of 2018, the dell XPS 13 developer edition appears to be the highest-quality linux-native laptop (and is super sexy!) &#x2013; it's a 13 inch laptop in an 11 inch frame!!<br  /></li></ol>
</li>
<li><a id="sec-1-4-23-4" name="sec-1-4-23-4"></a>lrn-desktop-specs<br  /><ol class="org-ol"><li><a id="sec-1-4-23-4-1" name="sec-1-4-23-4-1"></a>check out pangoly for computer build hardware prices<br  /></li>
<li><a id="sec-1-4-23-4-2" name="sec-1-4-23-4-2"></a><a href="http://www.tomshardware.com/reviews/build-your-own-pc,2601.html">http://www.tomshardware.com/reviews/build-your-own-pc,2601.html</a><br  /></li>
<li><a id="sec-1-4-23-4-3" name="sec-1-4-23-4-3"></a><a href="http://www.reddit.com/r/InternetIsBeautiful/comments/2kc228/a_website_to_generate_any_gaming_computer/">http://www.reddit.com/r/InternetIsBeautiful/comments/2kc228/a_website_to_generate_any_gaming_computer/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-5" name="sec-1-4-23-5"></a>lrn-memory<br  /><ol class="org-ol"><li><a id="sec-1-4-23-5-1" name="sec-1-4-23-5-1"></a>stack and heap <a href="http://stackoverflow.com/questions/79923/what-and-where-are-the-stack-and-heap">http://stackoverflow.com/questions/79923/what-and-where-are-the-stack-and-heap</a><br  /></li>
<li><a id="sec-1-4-23-5-2" name="sec-1-4-23-5-2"></a><a href="http://www.memorymanagement.org/index.html">http://www.memorymanagement.org/index.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-6" name="sec-1-4-23-6"></a>lrn-server<br  /><ol class="org-ol"><li><a id="sec-1-4-23-6-1" name="sec-1-4-23-6-1"></a>install: ars technica's old series <a href="http://arstechnica.com/gadgets/2012/11/how-to-set-up-a-safe-and-secure-web-server/">http://arstechnica.com/gadgets/2012/11/how-to-set-up-a-safe-and-secure-web-server/</a><br  /></li>
<li><a id="sec-1-4-23-6-2" name="sec-1-4-23-6-2"></a><a href="http://lifehacker.com/331865/host-your-domain-with-free-apps">http://lifehacker.com/331865/host-your-domain-with-free-apps</a><br  /></li>
<li><a id="sec-1-4-23-6-3" name="sec-1-4-23-6-3"></a>set up Tor node to help fight the Man <a href="https://supporters.eff.org/civicrm/mailing/view?reset=1&id=665">https://supporters.eff.org/civicrm/mailing/view?reset=1&id=665</a><br  /></li>
<li><a id="sec-1-4-23-6-4" name="sec-1-4-23-6-4"></a><i>Arq 5: Massively faster backup and restore for Mac and Windows</i><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-7" name="sec-1-4-23-7"></a>lrn-media-server (lrn-kodi)<br  /><ol class="org-ol"><li><a id="sec-1-4-23-7-1" name="sec-1-4-23-7-1"></a>windows 10<br  /><ol class="org-ol"><li><a id="sec-1-4-23-7-1-1" name="sec-1-4-23-7-1-1"></a><a href="http://mymediaexperience.com/windows-8-xbmc-appliance/">http://mymediaexperience.com/windows-8-xbmc-appliance/</a><br  /></li>
<li><a id="sec-1-4-23-7-1-2" name="sec-1-4-23-7-1-2"></a><a href="https://www.youtube.com/watch?v=QCIvb-lENWg">https://www.youtube.com/watch?v=QCIvb-lENWg</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-7-2" name="sec-1-4-23-7-2"></a>emulators <a href="http://lifehacker.com/5523672/turn-your-xbmc-media-center-into-a-video-game-console">http://lifehacker.com/5523672/turn-your-xbmc-media-center-into-a-video-game-console</a><br  /></li>
<li><a id="sec-1-4-23-7-3" name="sec-1-4-23-7-3"></a>ripping dvds<br  /><ol class="org-ol"><li><a id="sec-1-4-23-7-3-1" name="sec-1-4-23-7-3-1"></a><a href="https://www.reddit.com/r/htpc/comments/2y2her/best_ways_to_rip_dvdsbluray_for_kodi/">https://www.reddit.com/r/htpc/comments/2y2her/best_ways_to_rip_dvdsbluray_for_kodi/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-7-4" name="sec-1-4-23-7-4"></a>lrn-emby<br  /><ol class="org-ol"><li><a id="sec-1-4-23-7-4-1" name="sec-1-4-23-7-4-1"></a><a href="https://github.com/MediaBrowser/plugin.video.emby/wiki">https://github.com/MediaBrowser/plugin.video.emby/wiki</a><br  /></li>
<li><a id="sec-1-4-23-7-4-2" name="sec-1-4-23-7-4-2"></a><a href="https://emby.media/">https://emby.media/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-7-5" name="sec-1-4-23-7-5"></a><a href="http://lifehacker.com/5536963/the-ultimate-start-to-finish-guide-to-your-xbmc-media-center">http://lifehacker.com/5536963/the-ultimate-start-to-finish-guide-to-your-xbmc-media-center</a><br  /></li>
<li><a id="sec-1-4-23-7-6" name="sec-1-4-23-7-6"></a><a href="http://lifehacker.com/5900626/create-a-kickass-seamless-play-everything-media-center-the-complete-guide">http://lifehacker.com/5900626/create-a-kickass-seamless-play-everything-media-center-the-complete-guide</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-23-8" name="sec-1-4-23-8"></a>lrn-virtual-machines<br  /><ol class="org-ol"><li><a id="sec-1-4-23-8-1" name="sec-1-4-23-8-1"></a>lrn-virtualbox<br  /><ol class="org-ol"><li><a id="sec-1-4-23-8-1-1" name="sec-1-4-23-8-1-1"></a>"official" help on shared folders on windows-host/linux-client <a href="https://forums.virtualbox.org/viewtopic.php?f=3&t=15868">https://forums.virtualbox.org/viewtopic.php?f=3&t=15868</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-23-9" name="sec-1-4-23-9"></a>ugh, using little netbook, libreoffice didn't work on DEBIAN STABLE. if it doesn't work on that, it's not worth even using<br  /></li>
<li><a id="sec-1-4-23-10" name="sec-1-4-23-10"></a>asus chromebook flip<br  /><ol class="org-ol"><li><a id="sec-1-4-23-10-1" name="sec-1-4-23-10-1"></a>galliumOS doesn't work on prev version? <a href="https://wiki.galliumos.org/Hardware_Compatibility">https://wiki.galliumos.org/Hardware_Compatibility</a><br  /></li>
<li><a id="sec-1-4-23-10-2" name="sec-1-4-23-10-2"></a><a href="https://medium.com/adventures-in-codeland/coding-on-a-chromebook-a-how-to-guide-part-1-ec87152c00b1">https://medium.com/adventures-in-codeland/coding-on-a-chromebook-a-how-to-guide-part-1-ec87152c00b1</a><br  /></li>
<li><a id="sec-1-4-23-10-3" name="sec-1-4-23-10-3"></a><a href="https://solarianprogrammer.com/2017/09/11/two-weeks-programming-chromebook-challenge/">https://solarianprogrammer.com/2017/09/11/two-weeks-programming-chromebook-challenge/</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-24" class="outline-4">
<h4 id="sec-1-4-24"><span class="section-number-4">1.4.24</span> lrn-hdf5</h4>
<div class="outline-text-4" id="text-1-4-24">
</div><ol class="org-ol"><li><a id="sec-1-4-24-1" name="sec-1-4-24-1"></a>Moving away from HDF5 <a href="http://hn.premii.com/#/comments/10858189">http://hn.premii.com/#/comments/10858189</a><br  /></li>
<li><a id="sec-1-4-24-2" name="sec-1-4-24-2"></a>hdf5 woes on debian<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-1" name="sec-1-4-24-2-1"></a>trying to install<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-1-1" name="sec-1-4-24-2-1-1"></a>have tried hdfview from package - shows empty file, critical bug known since Jan 2017<br  /></li>
<li><a id="sec-1-4-24-2-1-2" name="sec-1-4-24-2-1-2"></a>have tried compiling hdfview, after MUCH effort compiling and HDF4 HDF5 libs, unclear compile error when it came to compiling HDFview specifically, possible java error<br  /></li>
<li><a id="sec-1-4-24-2-1-3" name="sec-1-4-24-2-1-3"></a>have tried running hdfview from Wine, but not working, maybe since key executable is a batch file 'hdfview.bat'<br  /></li>
<li><a id="sec-1-4-24-2-1-4" name="sec-1-4-24-2-1-4"></a>have tried hdf-compass package, gives error when loading example hdf<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-1-4-1" name="sec-1-4-24-2-1-4-1"></a>executable: HDFCompass<br  /></li>
<li><a id="sec-1-4-24-2-1-4-2" name="sec-1-4-24-2-1-4-2"></a>gives similar h5py library error?<br  /></li></ol>
</li>
<li><a id="sec-1-4-24-2-1-5" name="sec-1-4-24-2-1-5"></a>hdf-compass DOES work on non-pypet test HDF data, issue was pypet data<br  /></li>
<li><a id="sec-1-4-24-2-1-6" name="sec-1-4-24-2-1-6"></a>tried "compiling" most recent version of hdf-compass from pypi (0.7b3, vs. the package version of 0.6) via wheel file installation, but failed repeatedly in compiling wxPython/wxWidget dep<br  /></li>
<li><a id="sec-1-4-24-2-1-7" name="sec-1-4-24-2-1-7"></a>have tried, from stretch-backports, "silx view" which gives python h5py library error<br  /></li>
<li><a id="sec-1-4-24-2-1-8" name="sec-1-4-24-2-1-8"></a>have tried vitables which gives same? h5py library error as silx<br  /></li></ol>
</li>
<li><a id="sec-1-4-24-2-2" name="sec-1-4-24-2-2"></a>only success: using hdf-compass package on non-pypet data, e.g. "data.hdf5<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-2-1" name="sec-1-4-24-2-2-1"></a>note: in the readthedocs, the "install" page of HDF-Compass has just a "TBD"&#x2026;and the repo hasn't really been updated in 2 years&#x2026;and HDFView 3.0.0 may be newer than it.<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-2-1-1" name="sec-1-4-24-2-2-1-1"></a>in other words, hdf-compass may be dead<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-24-2-3" name="sec-1-4-24-2-3"></a>can use hdfview on cluster (module) to successfully load pypet hdf files!<br  /></li>
<li><a id="sec-1-4-24-2-4" name="sec-1-4-24-2-4"></a>why can only hdfview load pypet hdf files (and others), but HDFCompass can only load non-pypet?<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-4-1" name="sec-1-4-24-2-4-1"></a>possible answer: pypet hdf uses UTF8 (CSET H5T<sub>CSET</sub><sub>UTF8</sub>) instead of ASCII (CSET H5T<sub>CSET</sub><sub>ASCII</sub>) like data.hdf5 and NWB<br  /></li>
<li><a id="sec-1-4-24-2-4-2" name="sec-1-4-24-2-4-2"></a>possible answer: HDFCompass complains that there's no function in v0.6.0 to read CLASS when it's not IMAGE? or something? could be CLASS attribute<br  /><ol class="org-ol"><li><a id="sec-1-4-24-2-4-2-1" name="sec-1-4-24-2-4-2-1"></a>trying to remove this attribute: LOL that is DEF not the only problem<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-24-2-5" name="sec-1-4-24-2-5"></a>installed h5check to validate, but pypet hdf files pass validation! wtf?<br  /></li></ol>
</li>
<li><a id="sec-1-4-24-3" name="sec-1-4-24-3"></a>it seems like, despite hdf5 being made by a standards org, the software leaves a LOT to be desired!<br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-25" class="outline-4">
<h4 id="sec-1-4-25"><span class="section-number-4">1.4.25</span> lrn-image-formats</h4>
<div class="outline-text-4" id="text-1-4-25">
</div><ol class="org-ol"><li><a id="sec-1-4-25-1" name="sec-1-4-25-1"></a><a href="http://www.cs.virginia.edu/~webteam/readme/imgfmt.html">http://www.cs.virginia.edu/~webteam/readme/imgfmt.html</a><br  /></li>
<li><a id="sec-1-4-25-2" name="sec-1-4-25-2"></a><a href="https://stackoverflow.com/questions/2336522/png-vs-gif-vs-jpeg-vs-svg-when-best-to-use">https://stackoverflow.com/questions/2336522/png-vs-gif-vs-jpeg-vs-svg-when-best-to-use</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-26" class="outline-4">
<h4 id="sec-1-4-26"><span class="section-number-4">1.4.26</span> lrn-irc (lrn-irssi)</h4>
<div class="outline-text-4" id="text-1-4-26">
</div><ol class="org-ol"><li><a id="sec-1-4-26-1" name="sec-1-4-26-1"></a>commands<br  /><ol class="org-ol"><li><a id="sec-1-4-26-1-1" name="sec-1-4-26-1-1"></a>`/quit`<br  /></li>
<li><a id="sec-1-4-26-1-2" name="sec-1-4-26-1-2"></a>on startup, from <a href="https://wiki.archlinux.org/index.php/Irssi">https://wiki.archlinux.org/index.php/Irssi</a><br  /><ol class="org-ol"><li><a id="sec-1-4-26-1-2-1" name="sec-1-4-26-1-2-1"></a>join the server network via `/server add -auto -network fn chat.freenode.net`<br  /></li>
<li><a id="sec-1-4-26-1-2-2" name="sec-1-4-26-1-2-2"></a>auto add nickname via `/network add -nick &lt;user&gt; -autosendcmd "/msg NickServ identify &lt;password&gt;" fn`<br  /></li>
<li><a id="sec-1-4-26-1-2-3" name="sec-1-4-26-1-2-3"></a>auto join channel on freenode via `/channel add -auto #archlinux fn`<br  /></li></ol>
</li>
<li><a id="sec-1-4-26-1-3" name="sec-1-4-26-1-3"></a>live from <a href="https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat">https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat</a><br  /><ol class="org-ol"><li><a id="sec-1-4-26-1-3-1" name="sec-1-4-26-1-3-1"></a>`/connect irc.DERP.net`<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-26-2" name="sec-1-4-26-2"></a>useful resources<br  /><ol class="org-ol"><li><a id="sec-1-4-26-2-1" name="sec-1-4-26-2-1"></a><a href="https://freenode.net/faq.shtml#userregistration">https://freenode.net/faq.shtml#userregistration</a><br  /></li>
<li><a id="sec-1-4-26-2-2" name="sec-1-4-26-2-2"></a><a href="https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat">https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat</a><br  /></li>
<li><a id="sec-1-4-26-2-3" name="sec-1-4-26-2-3"></a><a href="https://wiki.archlinux.org/index.php/Irssi">https://wiki.archlinux.org/index.php/Irssi</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-27" class="outline-4">
<h4 id="sec-1-4-27"><span class="section-number-4">1.4.27</span> lrn-langs</h4>
<div class="outline-text-4" id="text-1-4-27">
</div><ol class="org-ol"><li><a id="sec-1-4-27-1" name="sec-1-4-27-1"></a><a href="https://github.com/melling/ComputerLanguages">https://github.com/melling/ComputerLanguages</a><br  /></li>
<li><a id="sec-1-4-27-2" name="sec-1-4-27-2"></a>lrn-assembly<br  /><ol class="org-ol"><li><a id="sec-1-4-27-2-1" name="sec-1-4-27-2-1"></a><a href="http://allthatiswrong.wordpress.com/2013/03/04/a-comparison-of-books-sfor-learning-assembly-language/">http://allthatiswrong.wordpress.com/2013/03/04/a-comparison-of-books-sfor-learning-assembly-language/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-3" name="sec-1-4-27-3"></a>lrn-bash<br  /><ol class="org-ol"><li><a id="sec-1-4-27-3-1" name="sec-1-4-27-3-1"></a>How "Exit Traps" Can Make Your Bash Scripts Way More Robust And Reliable <a href="http://redsymbol.net/articles/bash-exit-traps/">http://redsymbol.net/articles/bash-exit-traps/</a><br  /></li>
<li><a id="sec-1-4-27-3-2" name="sec-1-4-27-3-2"></a>Mastering Bash and Terminal | Hacker News <a href="https://news.ycombinator.com/item?id=13400350">https://news.ycombinator.com/item?id=13400350</a><br  /></li>
<li><a id="sec-1-4-27-3-3" name="sec-1-4-27-3-3"></a>'printenv' prints all environmental varbls<br  /></li>
<li><a id="sec-1-4-27-3-4" name="sec-1-4-27-3-4"></a>'set' prints SHELL environmental varbls (many are lowercase)<br  /></li>
<li><a id="sec-1-4-27-3-5" name="sec-1-4-27-3-5"></a>'$ (sleep 5; echo Tea is ready) &amp;'<br  /></li>
<li><a id="sec-1-4-27-3-6" name="sec-1-4-27-3-6"></a><a href="http://mmb.pcb.ub.es/~carlesfe/unix/tricks.txt">http://mmb.pcb.ub.es/~carlesfe/unix/tricks.txt</a><br  /><div class="outline-text-6" id="text-1-4-27-3-6">
<ul class="org-ul">
<li>I have marked with a * those which I think are absolutely essential
</li>
<li>Items for each section are sorted by oldest to newest. Come back soon for more!
</li>
<li>BASH
<ul class="org-ul">
<li>In bash, 'ctrl-r' searches your command history as you type
</li>
<li>Input from the commandline as if it were a file by replacing
'command &lt; file.in' with 'command &lt;&lt;&lt; "some input text"'
</li>
<li>'<sup>'</sup> is a sed-like operator to replace chars from last command
'ls docs; ^docs<sup>web</sup><sup>'</sup> is equal to 'ls web'. The second argument can be empty.
</li>
<li>'!!:n' selects the nth argument of the last command, and '!$' the last arg
'ls file1 file2 file3; cat !!:1-2' shows all files and cats only 1 and 2
</li>
<li>More in-line substitutions: <a href="http://tiny.cc/ecv0cw">http://tiny.cc/ecv0cw</a> <a href="http://tiny.cc/8zbltw">http://tiny.cc/8zbltw</a>
</li>
<li>'nohup ./long<sub>script</sub> &amp;' to leave stuff in background even if you logout
</li>
<li>'cd -' change to the previous directory you were working on
</li>
<li>'ctrl-x ctrl-e' opens an editor to work with long or complex command lines
</li>
<li>Use traps for cleaning up bash scripts on exit <a href="http://tiny.cc/traps">http://tiny.cc/traps</a>
</li>
<li>'shopt -s cdspell' automatically fixes your 'cd folder' spelling mistakes
</li>
<li>Add 'set editing-mode vi' in your ~/.inputrc to use the vi keybindings for bash and all readline-enabled applications (python, mysql, etc)
</li>
</ul>
</li>
<li>PSEUDO ALIASES FOR COMMONLY USED LONG COMMANDS
<ul class="org-ul">
<li>function lt() { ls -ltrsa "$@" | tail; }
</li>
<li>function psgrep() { ps axuf | grep -v grep | grep "$@" -i &#x2013;color=auto; }
</li>
<li>function fname() { find . -iname "<b>$@</b>"; }
</li>
</ul>
</li>
<li>VIM
<ul class="org-ul">
<li>':set spell' activates vim spellchecker. Use ']s' and '[s' to move between mistakes, 'zg' adds to the dictionary, 'z=' suggests correctly spelled words
</li>
<li>check my .vimrc <a href="http://tiny.cc/qxzktw">http://tiny.cc/qxzktw</a> and here <a href="http://tiny.cc/kzzktw">http://tiny.cc/kzzktw</a> for more
</li>
</ul>
</li>
<li>TOOLS
<ul class="org-ul">
<li>'htop' instead of 'top'
</li>
<li>'ranger' is a nice console file manager for vi fans
</li>
<li>Use 'apt-file' to see which package provides that file you're missing
</li>
<li>'dict' is a commandline dictionary
</li>
<li>Learn to use 'find' and 'locate' to look for files
</li>
<li>Compile your own version of 'screen' from the git sources. Most versions have a slow scrolling on a vertical split or even no vertical split at all
</li>
<li>'trash-cli' sends files to the trash instead of deleting them forever. Be very careful with 'rm' or maybe make a wrapper to avoid deleting '*' by accident (e.g. you want to type 'rm tmp*' but type 'rm tmp *')
</li>
<li>'file' gives information about a file, as image dimensions or text encoding
</li>
<li>'sort | uniq' to check for duplicate lines
</li>
<li>'echo start<sub>backup</sub>.sh | at midnight' starts a command at the specified time
</li>
<li>Pipe any command over 'column -t' to nicely align the columns
</li>
<li>Google 'magic sysrq' and learn how to bring you machine back from the dead
</li>
<li>'diff &#x2013;side-by-side fileA.txt fileB.txt | pager' to see a nice diff
</li>
<li>'j.py' <a href="http://tiny.cc/62qjow">http://tiny.cc/62qjow</a> remembers your most used folders and is an incredible substitute to browse directories by name instead of 'cd'
</li>
<li>'dropbox<sub>uploader</sub>.sh' <a href="http://tiny.cc/o2qjow">http://tiny.cc/o2qjow</a> is a fantastic solution to upload by commandline via Dropbox's API if you can't use the official client
</li>
<li>learn to use 'pushd' to save time navigating folders (j.py is better though)
</li>
<li>if you liked the 'psgrep' alias, check 'pgrep' as it is far more powerful
</li>
<li>never run 'chmod o+x * -R', capitalize the X to avoid executable files. If you want <span class="underline">only</span> executable folders: 'find . -type d -exec chmod g+x {} ;'
</li>
<li>'xargs' gets its input from a pipe and runs some command for each argument
</li>
<li>run jobs in parallel easily: 'ls *.png | parallel -j4 convert {} {.}.jpg'
</li>
</ul>
</li>
<li>NETWORKING
<ul class="org-ul">
<li>Don't know where to start? SMB is usually better than NFS for most cases.
</li>
<li>'sshfs<sub>mount'</sub> is not really stable, any network failure will be troublesome
</li>
<li>'python -m SimpleHTTPServer 8080' shares all the files in the current folder over HTTP, port 8080
</li>
<li>'ssh -R 12345:localhost:22 server.com "sleep 1000; exit"' forwards server.com's port 12345 to your local ssh port, even if you machine is not externally visible on the net.
</li>
<li>Now you can 'ssh localhost -p 12345' from server.com and you will log into your machine.
</li>
<li>'sleep' avoids getting kicked out from server.com for inactivity
</li>
<li>Read on 'ssh-keygen' to avoid typing passwords every time you ssh
</li>
<li>'socat TCP4-LISTEN:1234,fork TCP4:192.168.1.1:22' forwards your port 1234 to another machine's port 22. Very useful for quick NAT redirection.
</li>
<li>Some tools to monitor network connections and bandwith:
</li>
<li>'lsof -i' monitors network connections in real time
</li>
<li>'iftop' shows bandwith usage per <b>connection</b>
</li>
<li>'nethogs' shows the bandwith usage per <b>process</b>
</li>
<li>Use this trick on .ssh/config to directly access 'host2' which is on a private network, and must be accessed by ssh-ing into 'host1' first
</li>
<li>Host host2
</li>
<li>ProxyCommand ssh -T host1 'nc %h %p'
</li>
<li>HostName host2
</li>
<li>Pipe a compressed file over ssh to avoid creating large temporary .tgz files
</li>
<li>'tar cz folder/ | ssh server "tar xz"' or even better, use 'rsync'
</li>
<li>ssmtp can use a Gmail account as SMTP and send emails from the command line.
</li>
<li>'echo "Hello, User!" | mail user@domain.com' ## Thanks to Adam Ziaja.
</li>
<li>Configure your /etc/ssmtp/ssmtp.conf:
root=***E-MAIL***
mailhub=smtp.gmail.com:587
rewriteDomain=
hostname=smtp.gmail.com:587
UseSTARTTLS=YES
UseTLS=YES
AuthUser=***E-MAIL***
AuthPass=***PASSWORD***
AuthMethod=LOGIN
FromLineOverride=YES
</li>
</ul>
</li>

<li>command line one-liners
<ul class="org-ul">
<li>Run the last command
</li>
<li>$ !!
</li>
<li>Run the last command as root
</li>
<li>$ sudo !!
</li>
<li>Create a script of the last executed command
</li>
<li>$ echo "!!" &gt; script.sh
</li>
<li>Reuse all parameter of the previous command line
</li>
<li>$ echo cd .$ !*
</li>
<li>Run the last command with some argument
</li>
<li>$ echo a b c d e$ echo !!:2$ echo !!:3-$
</li>
<li>Insert the last argument of the previous command
</li>
<li>$ cp script.sh /usr/bin/$ cd &lt;ESC&gt; .
</li>
<li>Runs previous command but replacing
</li>
<li>$ echo no typos$ ^typos<sup>errors</sup>
</li>
<li>Escape any command aliases
</li>
<li>$ alias ls="ls -a"$ ls
</li>
<li>Quickly rename a file
</li>
<li>$ mv filename.{old,new}$ mv filename.{png,jpg}
</li>
<li>Create a quick back-up copy of a file
</li>
<li>$ cp file.txt{,.bak}
</li>
<li>Run a command from the history
</li>
<li>$ history &#x2026; 1225  ls -l 1226  git status 1227  history$ !-3$ !1225
</li>
<li>Search the history for the most recent command beginning with 'text'
</li>
<li>$ !text
</li>
<li>List of commands you use most often
</li>
<li>$ history | awk '{print $2}' | sort | uniq -c | sort -rn | head
</li>
<li>Execute a command without saving it in the history
</li>
<li>$ &lt;space&gt;command
</li>
<li>Make directory including intermediate directories
</li>
<li>$ mkdir -p a/long/directory/path
</li>
<li>Create a directory and change into it
</li>
<li>$ mkdir dir &amp;&amp; cd $_
</li>
<li>Change to the previous working directory
</li>
<li>$ cd -
</li>
<li>Jump to a directory. Execute a command. Jump back to current directory
</li>
<li>$ (cd /tmp &amp;&amp; ls)
</li>
<li>Create simple text file from command line
</li>
<li>$ cat &gt; file.txt{your text here}{your text here}&lt;ctrl-d&gt;
</li>
<li>Empty a file
</li>
<li>$ &gt; file.txt
</li>
<li>Show PATH in a human-readable way
</li>
<li>$ echo \(PATH | tr ':' 'n'\) tr ':' 'n' &lt;&lt;&lt; $PATH
</li>
<li>Make 'less' behave like 'tail -f'
</li>
<li>$ less +F somelogfile
</li>
<li>Redirect standard input to a file. Print it to standard output
</li>
<li>$ command | tee file.txt | less │ command │─▸│   tee   │─▸│ stdout │file
</li>
<li>Search for a  string inside all files in the current directory
</li>
<li>$ grep -RnsI &#x2013;color=auto &lt;pattern&gt; *
</li>
<li>Beyond grep
</li>
<li>_   /|'o.O'<code>(___)</code>  U    ack!$ ack &lt;pattern&gt;
</li>
<li>Recursively remove all empty directories
</li>
<li>$ find . -type d -empty -delete
</li>
<li>Count your commits
</li>
<li>$ git shortlog -sn
</li>
<li>Serve current directory tree at <a href="http://$HOSTNAME:8000/">http://$HOSTNAME:8000/</a>
</li>
<li>$ python -m SimpleHTTPServer
</li>
<li>Share a file between two computers
</li>
<li>$ nc -l 5566 &gt; data-dump.sql$ nc &lt;his-ip-address&gt; 5566 &lt; data-dump.sql
</li>
<li>Download an entire website
</li>
<li>$ wget -m <a href="http://website.com">http://website.com</a>
</li>
<li>Clear the terminal screen
</li>
<li>&lt;ctrl-l&gt;
</li>
<li>Salvage a borked terminal
</li>
<li>$ reset
</li>
<li>Close shell keeping all subprocess running
</li>
<li>$ disown -a &amp;&amp; exit
</li>
<li>Run a command immune to hangups
</li>
<li>$ nohup command &amp;
</li>
<li>Attach screen over ssh
</li>
<li>$ ssh user@host -t screen -r
</li>
<li>Compare a remote file with a local file
</li>
<li>$ ssh user@host cat /path/to/remotefile | diff /path/to/localfile -
</li>
<li>Get your public IP address
</li>
<li>$ curl ifconfig.me
</li>
<li>Set audible alarm when an IP address comes online
</li>
<li>$ ping -a IP<sub>address</sub>
</li>
<li>List programs with open ports and connections
</li>
<li>$ lsof -i
</li>
<li>Currently mounted filesystems in nice layout
</li>
<li>$ mount | column -t
</li>
<li>Display free disk space
</li>
<li>$ df -h
</li>
<li>Display disk usage statistics for the current directory
</li>
<li>$ du -sh *
</li>
<li>Display 10 biggest files/folders for the current directory
</li>
<li>$ du -s * | sort -nr | head
</li>
<li>Execute a command at a given time
</li>
<li>$ echo "ls -l" | at midnight
</li>
<li>Simple stopwatch
</li>
<li>$ time read&lt;ctrl-d&gt;
</li>
<li>Put a console clock in top right corner
</li>
<li>$ while sleep 1;do tput sc;tput cup 0 $(($(tput cols)-29));date;tput rc;done &amp;
</li>
<li>Display the top ten running processes. (Sorted by memory usage)
</li>
<li>$ ps aux | sort -nk +4 | tail
</li>
<li>Kill all Ruby processes
</li>
<li>$ ps aux | grep ruby | awk '{ print \(2 }' | xargs kill -9\) ps aux | awk '<i>ruby</i> &amp;&amp; ! <i>awk</i> { system("kill -9 "$2) }'
</li>
<li>32 bits or 64 bits?
</li>
<li>$ getconf LONG<sub>BIT</sub>
</li>
<li>Displays a calendar
</li>
<li>$ cal 12 1984
</li>
<li>What day is today?
</li>
<li>$ cal | sed "s/.*/ &amp; <i>;s</i> \((date +%d) / [] /"\) cal | sed "s/.*/ &amp; <i>;s</i> $(date +%d) / $(printf 'e[0;31m[]e[0m') /"
</li>
<li>Show File System Hierarchy
</li>
<li>$ man hier
</li>
<li>Quick access to the ascii table
</li>
<li>$ man ascii
</li>
<li>Russian Roulette in Bash
</li>
<li>$ [ $[ $RANDOM % 6 ] == 0 ] &amp;&amp; rm -rf / || echo "You live"
</li>
<li>Watch Star Wars via telnet
</li>
<li>$ telnet towel.blinkenlights.nl
</li>
</ul>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-27-3-7" name="sec-1-4-27-3-7"></a><a href="http://mywiki.wooledge.org/BashGuide/">http://mywiki.wooledge.org/BashGuide/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-4" name="sec-1-4-27-4"></a>lrn-c-lang<br  /><ol class="org-ol"><li><a id="sec-1-4-27-4-1" name="sec-1-4-27-4-1"></a>use c to work through algos and data s? and cpython, use gdb when lrning c<br  /></li>
<li><a id="sec-1-4-27-4-2" name="sec-1-4-27-4-2"></a>learn basic c (take notes, it's long) <a href="http://computer.howstuffworks.com/c23.htm/printable">http://computer.howstuffworks.com/c23.htm/printable</a><br  /></li>
<li><a id="sec-1-4-27-4-3" name="sec-1-4-27-4-3"></a><a href="http://c.learncodethehardway.org/">http://c.learncodethehardway.org/</a><br  /></li>
<li><a id="sec-1-4-27-4-4" name="sec-1-4-27-4-4"></a>really good comment <a href="https://news.ycombinator.com/item?id=580332">https://news.ycombinator.com/item?id=580332</a><br  /></li>
<li><a id="sec-1-4-27-4-5" name="sec-1-4-27-4-5"></a>the descent into c <a href="http://www.chiark.greenend.org.uk/~sgtatham/cdescent/">http://www.chiark.greenend.org.uk/~sgtatham/cdescent/</a><br  /></li>
<li><a id="sec-1-4-27-4-6" name="sec-1-4-27-4-6"></a>building c projects <a href="http://nethack4.org/blog/building-c.html">http://nethack4.org/blog/building-c.html</a><br  /></li>
<li><a id="sec-1-4-27-4-7" name="sec-1-4-27-4-7"></a><a href="http://hn.premii.com/#/comments/10864176">How to C in 2016</a><br  /></li>
<li><a id="sec-1-4-27-4-8" name="sec-1-4-27-4-8"></a>reference:<br  /><ol class="org-ol"><li><a id="sec-1-4-27-4-8-1" name="sec-1-4-27-4-8-1"></a>escape sequences:<br  /><div class="outline-text-7" id="text-1-4-27-4-8-1">
<p>
a - alert or bell character
b - backspace
f - formfeed
n - newline
r - carriage return
t - horizontal tab
v - vertical tab
</p>
<ul class="org-ul">
<li>backslash
</li>
</ul>
<p>
? - question mark
' - single quote
" - double quote
ooo - octal number
xhh - hex number
</p>
</div>
</li>

<li><a id="sec-1-4-27-4-8-2" name="sec-1-4-27-4-8-2"></a>strings (via libraries)<br  /><ol class="org-ol"><li><a id="sec-1-4-27-4-8-2-1" name="sec-1-4-27-4-8-2-1"></a><a href="http://www.and.org/vstr/comparison">http://www.and.org/vstr/comparison</a><br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-5" name="sec-1-4-27-5"></a>lrn-clojure<br  /></li>
<li><a id="sec-1-4-27-6" name="sec-1-4-27-6"></a>lrn-cpp<br  /><ol class="org-ol"><li><a id="sec-1-4-27-6-1" name="sec-1-4-27-6-1"></a>write a direct c to assembly thing via clang a la <a href="http://assembly.ynh.io/">http://assembly.ynh.io/</a><br  /></li>
<li><a id="sec-1-4-27-6-2" name="sec-1-4-27-6-2"></a><a href="http://yosefk.com/c++fqa/">http://yosefk.com/c++fqa/</a><br  /></li>
<li><a id="sec-1-4-27-6-3" name="sec-1-4-27-6-3"></a><a href="http://google-styleguide.googlecode.com/svn/trunk/cppguide.xml">http://google-styleguide.googlecode.com/svn/trunk/cppguide.xml</a><br  /></li>
<li><a id="sec-1-4-27-6-4" name="sec-1-4-27-6-4"></a><a href="http://en.wikipedia.org/wiki/Substitution_failure_is_not_an_error">http://en.wikipedia.org/wiki/Substitution_failure_is_not_an_error</a><br  /></li>
<li><a id="sec-1-4-27-6-5" name="sec-1-4-27-6-5"></a>multidim arrays<br  /><ol class="org-ol"><li><a id="sec-1-4-27-6-5-1" name="sec-1-4-27-6-5-1"></a><a href="http://www.eskimo.com/~scs/cclass/int/sx9b.html">http://www.eskimo.com/~scs/cclass/int/sx9b.html</a><br  /></li>
<li><a id="sec-1-4-27-6-5-2" name="sec-1-4-27-6-5-2"></a><a href="http://www.parashift.com/c++-faq/multidim-arrays.html">http://www.parashift.com/c++-faq/multidim-arrays.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-6-6" name="sec-1-4-27-6-6"></a>streams <a href="http://www.cprogramming.com/tutorial/c++-iostreams.html">http://www.cprogramming.com/tutorial/c++-iostreams.html</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-6-6-1" name="sec-1-4-27-6-6-1"></a>other things on streams?<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-6-7" name="sec-1-4-27-6-7"></a><a href="http://david.tribble.com/text/cdiffs.htm">http://david.tribble.com/text/cdiffs.htm</a><br  /></li>
<li><a id="sec-1-4-27-6-8" name="sec-1-4-27-6-8"></a><a href="http://www.codeproject.com/Articles/7042/How-to-interpret-complex-C-C-declarations">http://www.codeproject.com/Articles/7042/How-to-interpret-complex-C-C-declarations</a><br  /></li>
<li><a id="sec-1-4-27-6-9" name="sec-1-4-27-6-9"></a><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-s096-introduction-to-c-and-c-january-iap-2013/">http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-s096-introduction-to-c-and-c-january-iap-2013/</a><br  /></li>
<li><a id="sec-1-4-27-6-10" name="sec-1-4-27-6-10"></a><a href="http://newdata.box.sk/bx/c/htm/ch04.htm">http://newdata.box.sk/bx/c/htm/ch04.htm</a><br  /></li>
<li><a id="sec-1-4-27-6-11" name="sec-1-4-27-6-11"></a><a href="https://fffaraz.github.io/awesome-cpp/">https://fffaraz.github.io/awesome-cpp/</a><br  /></li>
<li><a id="sec-1-4-27-6-12" name="sec-1-4-27-6-12"></a>c++11<br  /><ol class="org-ol"><li><a id="sec-1-4-27-6-12-1" name="sec-1-4-27-6-12-1"></a><a href="http://www.codeproject.com/Articles/570638/Ten-Cplusplus-Features-Every-Cplusplus-Developer">http://www.codeproject.com/Articles/570638/Ten-Cplusplus-Features-Every-Cplusplus-Developer</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-6-13" name="sec-1-4-27-6-13"></a>c++ seed<sub>seq</sub> <a href="http://www.pcg-random.org/posts/cpp-seeding-surprises.html">http://www.pcg-random.org/posts/cpp-seeding-surprises.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-7" name="sec-1-4-27-7"></a>lrn-haskell<br  /><ol class="org-ol"><li><a id="sec-1-4-27-7-1" name="sec-1-4-27-7-1"></a><a href="http://learnyouahaskell.com">http://learnyouahaskell.com</a><br  /></li>
<li><a id="sec-1-4-27-7-2" name="sec-1-4-27-7-2"></a><a href="https://news.ycombinator.com/item?id=8118696">https://news.ycombinator.com/item?id=8118696</a><br  /></li>
<li><a id="sec-1-4-27-7-3" name="sec-1-4-27-7-3"></a><a href="https://github.com/caiorss/Functional-Programming">https://github.com/caiorss/Functional-Programming</a><br  /></li>
<li><a id="sec-1-4-27-7-4" name="sec-1-4-27-7-4"></a><a href="http://www.haskellbook.com/">http://www.haskellbook.com/</a><br  /></li>
<li><a id="sec-1-4-27-7-5" name="sec-1-4-27-7-5"></a><a href="http://hn.premii.com/#/article/11138818">The Joy and Agony of Haskell in Production</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-8" name="sec-1-4-27-8"></a>lrn-javascript-lrn-js<br  /><ol class="org-ol"><li><a id="sec-1-4-27-8-1" name="sec-1-4-27-8-1"></a><a href="https://sivers.org/learn-js">https://sivers.org/learn-js</a><br  /></li>
<li><a id="sec-1-4-27-8-2" name="sec-1-4-27-8-2"></a><a href="http://fourlightyears.blogspot.com.au/2015/05/an-incredibly-brief-introduction-to.html">http://fourlightyears.blogspot.com.au/2015/05/an-incredibly-brief-introduction-to.html</a><br  /></li>
<li><a id="sec-1-4-27-8-3" name="sec-1-4-27-8-3"></a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">https://developer.mozilla.org/en-US/docs/Web/JavaScript</a><br  /></li>
<li><a id="sec-1-4-27-8-4" name="sec-1-4-27-8-4"></a><a href="https://news.ycombinator.com/item?id=12954540">https://news.ycombinator.com/item?id=12954540</a><br  /></li>
<li><a id="sec-1-4-27-8-5" name="sec-1-4-27-8-5"></a>lrn-d3.js<br  /><ol class="org-ol"><li><a id="sec-1-4-27-8-5-1" name="sec-1-4-27-8-5-1"></a><a href="https://github.com/jakevdp/mpld3">https://github.com/jakevdp/mpld3</a><br  /></li>
<li><a id="sec-1-4-27-8-5-2" name="sec-1-4-27-8-5-2"></a><a href="http://worrydream.com/DrawingDynamicVisualizationsTalkAddendum/">http://worrydream.com/DrawingDynamicVisualizationsTalkAddendum/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-9" name="sec-1-4-27-9"></a>lrn-lisp<br  /><ol class="org-ol"><li><a id="sec-1-4-27-9-1" name="sec-1-4-27-9-1"></a>lrn-clojure<br  /><ol class="org-ol"><li><a id="sec-1-4-27-9-1-1" name="sec-1-4-27-9-1-1"></a><a href="https://news.ycombinator.com/item?id=1033503">https://news.ycombinator.com/item?id=1033503</a><br  /></li>
<li><a id="sec-1-4-27-9-1-2" name="sec-1-4-27-9-1-2"></a><a href="http://www.cis.upenn.edu/~matuszek/Concise%20Guides/Concise%20Clojure.html">http://www.cis.upenn.edu/~matuszek/Concise%20Guides/Concise%20Clojure.html</a><br  /></li>
<li><a id="sec-1-4-27-9-1-3" name="sec-1-4-27-9-1-3"></a><a href="http://java.ociweb.com/mark/clojure/article.html">http://java.ociweb.com/mark/clojure/article.html</a><br  /></li>
<li><a id="sec-1-4-27-9-1-4" name="sec-1-4-27-9-1-4"></a><a href="http://aphyr.com/posts/305-clojure-from-the-ground-up-macros">http://aphyr.com/posts/305-clojure-from-the-ground-up-macros</a><br  /></li>
<li><a id="sec-1-4-27-9-1-5" name="sec-1-4-27-9-1-5"></a><a href="http://learn-clojure.com/">http://learn-clojure.com/</a><br  /></li>
<li><a id="sec-1-4-27-9-1-6" name="sec-1-4-27-9-1-6"></a><a href="https://en.wikibooks.org/wiki/Learning_Clojure">https://en.wikibooks.org/wiki/Learning_Clojure</a><br  /></li>
<li><a id="sec-1-4-27-9-1-7" name="sec-1-4-27-9-1-7"></a>(not far along other than text?) <a href="http://sicpinclojure.com/?q=print/content/introduction">http://sicpinclojure.com/?q=print/content/introduction</a><br  /></li>
<li><a id="sec-1-4-27-9-1-8" name="sec-1-4-27-9-1-8"></a><a href="http://blip.tv/clojure/clojure-concurrency-819147">http://blip.tv/clojure/clojure-concurrency-819147</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-9-2" name="sec-1-4-27-9-2"></a>lrn-scheme<br  /><ol class="org-ol"><li><a id="sec-1-4-27-9-2-1" name="sec-1-4-27-9-2-1"></a><a href="http://stackoverflow.com/questions/11908746/mit-scheme-repl-with-command-line-history-and-tab-completion/11916365">http://stackoverflow.com/questions/11908746/mit-scheme-repl-with-command-line-history-and-tab-completion/11916365</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-9-3" name="sec-1-4-27-9-3"></a>syntax converting b/w diff lisps <a href="http://hyperpolyglot.org/lisp">http://hyperpolyglot.org/lisp</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-10" name="sec-1-4-27-10"></a>lrn-markdown<br  /><ol class="org-ol"><li><a id="sec-1-4-27-10-1" name="sec-1-4-27-10-1"></a>use orgmode for note-taking system, NOT markdown, stop researching this<br  /><ol class="org-ol"><li><a id="sec-1-4-27-10-1-1" name="sec-1-4-27-10-1-1"></a>pros for markdown<br  /><div class="outline-text-7" id="text-1-4-27-10-1-1">
<ul class="org-ul">
<li>plaintext: counter: orgmode already does that
</li>
<li>readability: counter: markdown looks human readable (so does org)
</li>
<li>export: counter: org already has vast export, and Pandoc import, and ANY more md-&gt;pandoc functionality can be had by org-&gt;md-&gt;edits-&gt;pandoc
</li>
<li>coolness: markdown is/looks cooler (markdown wins here, but only here, and only slightly)
</li>
<li>keep in mind this is INDEPENDENT of HOW I want to organize either md/org
</li>
</ul>
</div>
</li>
<li><a id="sec-1-4-27-10-1-2" name="sec-1-4-27-10-1-2"></a>cons for markdown<br  /><div class="outline-text-7" id="text-1-4-27-10-1-2">
<ul class="org-ul">
<li>would have to recreate huge amount of orgmode, literally everything (agenda building, agenda search, user interface for interacting with agenda)
</li>
<li>would just be adding meta layer (filetags, header tags, etc) on top of markdown just like org
</li>
</ul>
</div>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-11" name="sec-1-4-27-11"></a>lrn-matlab<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-1" name="sec-1-4-27-11-1"></a>code analysis tools<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-1-1" name="sec-1-4-27-11-1-1"></a><a href="http://www.artefact.tk/software/matlab/m2html/">http://www.artefact.tk/software/matlab/m2html/</a><br  /></li>
<li><a id="sec-1-4-27-11-1-2" name="sec-1-4-27-11-1-2"></a><a href="http://www.mathworks.com/matlabcentral/newsreader/view_thread/276144">http://www.mathworks.com/matlabcentral/newsreader/view_thread/276144</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-2" name="sec-1-4-27-11-2"></a>commands<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-2-1" name="sec-1-4-27-11-2-1"></a>`repmat` to replicate matrices<br  /></li>
<li><a id="sec-1-4-27-11-2-2" name="sec-1-4-27-11-2-2"></a>`bsxfun` does some binary operation between two matrices, but if one of them is a less dimensional than the other but still has values in other dimensions, it replicates those vales of the smaller matrix to match the size of the larger one, thus allowing a linear-algebraically correct binary operation on every element of hte larger matrix<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-3" name="sec-1-4-27-11-3"></a>documentation generation<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-3-1" name="sec-1-4-27-11-3-1"></a>so conclusion: either native documenting or doxygen style?<br  /></li>
<li><a id="sec-1-4-27-11-3-2" name="sec-1-4-27-11-3-2"></a>overview soverflow <a href="http://stackoverflow.com/questions/26242145/what-is-the-mathworks-way-to-generate-matlab-html-documentation">http://stackoverflow.com/questions/26242145/what-is-the-mathworks-way-to-generate-matlab-html-documentation</a><br  /></li>
<li><a id="sec-1-4-27-11-3-3" name="sec-1-4-27-11-3-3"></a>another soverflow summary <a href="http://stackoverflow.com/a/20014162/2723794">http://stackoverflow.com/a/20014162/2723794</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-3-3-1" name="sec-1-4-27-11-3-3-1"></a>from soverflow <a href="http://doxyf.sourceforge.net/doc0/html/mtoc0/">http://doxyf.sourceforge.net/doc0/html/mtoc0/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-3-4" name="sec-1-4-27-11-3-4"></a>official <a href="http://www.mathworks.com/help/matlab/matlab_prog/marking-up-matlab-comments-for-publishing.html">http://www.mathworks.com/help/matlab/matlab_prog/marking-up-matlab-comments-for-publishing.html</a><br  /></li>
<li><a id="sec-1-4-27-11-3-5" name="sec-1-4-27-11-3-5"></a>another official <a href="http://www.mathworks.com/help/matlab/matlab_prog/display-custom-documentation.html">http://www.mathworks.com/help/matlab/matlab_prog/display-custom-documentation.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-4" name="sec-1-4-27-11-4"></a>dev tools<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-4-1" name="sec-1-4-27-11-4-1"></a>matlab-emacs <a href="http://blog.angjookanazawa.com/post/8815280589/productivity-matlab-emacs-integration-more">http://blog.angjookanazawa.com/post/8815280589/productivity-matlab-emacs-integration-more</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-5" name="sec-1-4-27-11-5"></a>gotchas<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-5-1" name="sec-1-4-27-11-5-1"></a>for csv output, use `dlmwrite()` function (see below)<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-5-1-1" name="sec-1-4-27-11-5-1-1"></a>1. cannot just pass args to `save()` function<br  /></li>
<li><a id="sec-1-4-27-11-5-1-2" name="sec-1-4-27-11-5-1-2"></a>2. `csvwrite()` function ONLY saves to 5 significant digits (srsly?)<br  /></li>
<li><a id="sec-1-4-27-11-5-1-3" name="sec-1-4-27-11-5-1-3"></a>3. must use `dlmwrite()` e.g. `dlmwrite('test.csv', your<sub>data</sub>, 'precision','%10.5f')` for non-5 sig digits, see <a href="http://stackoverflow.com/a/18428990/2723794">http://stackoverflow.com/a/18428990/2723794</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-5-1-3-1" name="sec-1-4-27-11-5-1-3-1"></a>thankfully, `dlmwrite()` defaults to comma-delimiting, so don't need to specify that<br  /></li>
<li><a id="sec-1-4-27-11-5-1-3-2" name="sec-1-4-27-11-5-1-3-2"></a>thankfully, `dlmwrite()`'s precision argument accepts C-style formatting strings<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-11-5-2" name="sec-1-4-27-11-5-2"></a>are strings called chars in matlab? blasphemy<br  /></li>
<li><a id="sec-1-4-27-11-5-3" name="sec-1-4-27-11-5-3"></a>matlab either previously, or still, doesn't support transparent objects in plots with log <a href="http://www.mathworks.com/matlabcentral/answers/13441-bizare-problem-with-facealpha-and-rendering#answer_18342">http://www.mathworks.com/matlabcentral/answers/13441-bizare-problem-with-facealpha-and-rendering#answer_18342</a><br  /></li>
<li><a id="sec-1-4-27-11-5-4" name="sec-1-4-27-11-5-4"></a>matlab doesn't let you control transparency/alpha of individual markers e.g. for scatter3 <a href="http://www.mathworks.com/matlabcentral/answers/10855-how-can-i-apply-variable-transparency-to-a-plot-using-scatter3">http://www.mathworks.com/matlabcentral/answers/10855-how-can-i-apply-variable-transparency-to-a-plot-using-scatter3</a><br  /></li>
<li><a id="sec-1-4-27-11-5-5" name="sec-1-4-27-11-5-5"></a>run all plot generation/saving scripts TWICE in a LIVE session: if using a script to save a matlab plot to file, matlab will size/draw ticks on axes and resize the plot DIFFERENTLY depending on IF that plot is already loaded into memory (present in a figure on the screen) or not. So run all plot-saving scripts TWICE<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-6" name="sec-1-4-27-11-6"></a>libraries<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-6-1" name="sec-1-4-27-11-6-1"></a>matlab EEGlab plugin, analyzes .avg files?<br  /></li>
<li><a id="sec-1-4-27-11-6-2" name="sec-1-4-27-11-6-2"></a>batch/cluster jobs <a href="https://github.com/simonster/matorque">https://github.com/simonster/matorque</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-7" name="sec-1-4-27-11-7"></a>plotting<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-7-1" name="sec-1-4-27-11-7-1"></a><a href="https://www.io.ac.nz/blog/matlab-to-latex/">https://www.io.ac.nz/blog/matlab-to-latex/</a><br  /></li>
<li><a id="sec-1-4-27-11-7-2" name="sec-1-4-27-11-7-2"></a>for scatter plot fill-in of regions with matplotlib, <a href="http://stackoverflow.com/a/8794532/2723794">http://stackoverflow.com/a/8794532/2723794</a><br  /></li>
<li><a id="sec-1-4-27-11-7-3" name="sec-1-4-27-11-7-3"></a><a href="http://www.mathworks.com/help/matlab/learn_matlab/understanding-handle-graphics-objects.html">http://www.mathworks.com/help/matlab/learn_matlab/understanding-handle-graphics-objects.html</a><br  /></li>
<li><a id="sec-1-4-27-11-7-4" name="sec-1-4-27-11-7-4"></a>test X problems with parallel matplotlib plotting<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-7-4-1" name="sec-1-4-27-11-7-4-1"></a><a href="https://stackoverflow.com/questions/4931376/generating-matplotlib-graphs-without-a-running-x-server">https://stackoverflow.com/questions/4931376/generating-matplotlib-graphs-without-a-running-x-server</a><br  /></li>
<li><a id="sec-1-4-27-11-7-4-2" name="sec-1-4-27-11-7-4-2"></a><a href="https://stackoverflow.com/questions/2801882/generating-a-png-with-matplotlib-when-display-is-undefined">https://stackoverflow.com/questions/2801882/generating-a-png-with-matplotlib-when-display-is-undefined</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-11-8" name="sec-1-4-27-11-8"></a>spectrogramming<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-8-1" name="sec-1-4-27-11-8-1"></a><a href="http://www.mathworks.com/help/signal/ug/psd-estimate-using-fft.html">http://www.mathworks.com/help/signal/ug/psd-estimate-using-fft.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-9" name="sec-1-4-27-11-9"></a>testing<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-1" name="sec-1-4-27-11-9-1"></a><a href="http://blogs.mathworks.com/steve/2013/03/12/matlab-software-testing-tools-old-and-new-r2013a/">http://blogs.mathworks.com/steve/2013/03/12/matlab-software-testing-tools-old-and-new-r2013a/</a><br  /></li>
<li><a id="sec-1-4-27-11-9-2" name="sec-1-4-27-11-9-2"></a><a href="http://www.mathworks.com/help/matlab/matlab-unit-test-framework.html">http://www.mathworks.com/help/matlab/matlab-unit-test-framework.html</a><br  /></li>
<li><a id="sec-1-4-27-11-9-3" name="sec-1-4-27-11-9-3"></a>doctest <a href="http://www.mathworks.com/matlabcentral/fileexchange/28862-doctest-embed-testable-examples-in-your-function-s-help-comments">http://www.mathworks.com/matlabcentral/fileexchange/28862-doctest-embed-testable-examples-in-your-function-s-help-comments</a><br  /></li>
<li><a id="sec-1-4-27-11-9-4" name="sec-1-4-27-11-9-4"></a>doctest <a href="https://bitbucket.org/tgs/doctest-for-matlab/src">https://bitbucket.org/tgs/doctest-for-matlab/src</a><br  /></li>
<li><a id="sec-1-4-27-11-9-5" name="sec-1-4-27-11-9-5"></a>matlab testing<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1" name="sec-1-4-27-11-9-5-1"></a>defns<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1-1" name="sec-1-4-27-11-9-5-1-1"></a>test defns<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1-1-1" name="sec-1-4-27-11-9-5-1-1-1"></a>"unit tests are the smallest testable part of an application", defined as "short code fragments"<br  /></li>
<li><a id="sec-1-4-27-11-9-5-1-1-2" name="sec-1-4-27-11-9-5-1-1-2"></a>test cases (aka test scripts) &#x2013; are these collections of unit tests?<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1-1-2-1" name="sec-1-4-27-11-9-5-1-1-2-1"></a>matlab.unittest.TestCase "is the means by which a test is written in the matlab.unitteste framework"<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-9-5-1-1-3" name="sec-1-4-27-11-9-5-1-1-3"></a>test suites are collections of test cases<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-9-5-1-2" name="sec-1-4-27-11-9-5-1-2"></a>test-related defns<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1-2-1" name="sec-1-4-27-11-9-5-1-2-1"></a>test fixture &#x2013; "fixed state of set of objects used as a baseline for running tests"<br  /></li>
<li><a id="sec-1-4-27-11-9-5-1-2-2" name="sec-1-4-27-11-9-5-1-2-2"></a>test harness &#x2013; automated test framework, including both collection of test data and test script repo<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-11-9-5-1-3" name="sec-1-4-27-11-9-5-1-3"></a>qualifications defns<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-1-3-1" name="sec-1-4-27-11-9-5-1-3-1"></a>verification (e.g. verifyEqual) &#x2013; "informs the testing framework of the [nonfatal] failure (incl diag info), but continues to execute w/o throwing an exception"<br  /></li>
<li><a id="sec-1-4-27-11-9-5-1-3-2" name="sec-1-4-27-11-9-5-1-3-2"></a>assumption (e.g. assumeFalse) &#x2013; "if failure, throws throws 'AssumptionFailedException', marks test content as filtered, and continues test"<br  /></li>
<li><a id="sec-1-4-27-11-9-5-1-3-3" name="sec-1-4-27-11-9-5-1-3-3"></a>assertion (e.g. assertTrue) &#x2013; "tests for preconditions", "if an assertion occurs, remainder of method is invalid and test marked 'Incomplete'"<br  /></li>
<li><a id="sec-1-4-27-11-9-5-1-3-4" name="sec-1-4-27-11-9-5-1-3-4"></a>fatal assertion (e.g. fatalAssertTrue) &#x2013; "renders remainder of test method Invalid because state is unrecoverable"<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-11-9-5-2" name="sec-1-4-27-11-9-5-2"></a>meeting agenda<br  /><ol class="org-ol"><li><a id="sec-1-4-27-11-9-5-2-1" name="sec-1-4-27-11-9-5-2-1"></a>remove mechanism/input functions currently in func<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-11-10" name="sec-1-4-27-11-10"></a>X11 <a href="http://cplusadd.blogspot.com/2012/01/speeding-up-matlab-over-x11-forwarding.html">http://cplusadd.blogspot.com/2012/01/speeding-up-matlab-over-x11-forwarding.html</a><br  /></li>
<li><a id="sec-1-4-27-11-11" name="sec-1-4-27-11-11"></a>tags a la exuberant ctags<br  /><div class="outline-text-6" id="text-1-4-27-11-11">
<p>
from <a href="https://www.mathworks.com/matlabcentral/newsreader/view_thread/93917">https://www.mathworks.com/matlabcentral/newsreader/view_thread/93917</a>, add below to .ctags file in said directory:
```
&#x2013;langdef=matlab
&#x2013;langmap=matlab:.m
&#x2013;regex-matlab=/<sup>function[</sup> \t]*([a-zA-Z0-9<sub>]</sub>+)[ \t]*=[
\t]*([a-zA-Z0-9<sub>]</sub>+)/\2/f,functions/
&#x2013;regex-matlab=/<sup>function[</sup> \t]*([a-zA-Z0-9<sub>]</sub>+)[^=]*$/\1/f,functions/
```
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-27-12" name="sec-1-4-27-12"></a>lrn-python<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-1" name="sec-1-4-27-12-1"></a><a href="http://awesome-python.com/">http://awesome-python.com/</a><br  /></li>
<li><a id="sec-1-4-27-12-2" name="sec-1-4-27-12-2"></a><a href="https://tomaugspurger.github.io/modern-1.html">https://tomaugspurger.github.io/modern-1.html</a><br  /></li>
<li><a id="sec-1-4-27-12-3" name="sec-1-4-27-12-3"></a><a href="http://unlogic.co.uk/2013/02/08/vim-as-a-python-ide/">http://unlogic.co.uk/2013/02/08/vim-as-a-python-ide/</a><br  /></li>
<li><a id="sec-1-4-27-12-4" name="sec-1-4-27-12-4"></a><a href="https://www.reddit.com/r/Python/comments/4edpl0/how_do_you_use_python_to_automate_tasks_in_life/">How do you use python to automate tasks in life or at work?</a><br  /></li>
<li><a id="sec-1-4-27-12-5" name="sec-1-4-27-12-5"></a><a href="https://vladcalin.github.io/what-every-python-project-should-have.html#what-every-python-project-should-have">https://vladcalin.github.io/what-every-python-project-should-have.html#what-every-python-project-should-have</a><br  /></li>
<li><a id="sec-1-4-27-12-6" name="sec-1-4-27-12-6"></a>From Python to Numpy | Hacker News <a href="https://news.ycombinator.com/item?id=13355034">https://news.ycombinator.com/item?id=13355034</a><br  /></li>
<li><a id="sec-1-4-27-12-7" name="sec-1-4-27-12-7"></a>anaconda cons <a href="https://www.reddit.com/r/Python/comments/4uj41m/disadvantages_of_continuum_analytics_anacondaconda/">https://www.reddit.com/r/Python/comments/4uj41m/disadvantages_of_continuum_analytics_anacondaconda/</a><br  /></li>
<li><a id="sec-1-4-27-12-8" name="sec-1-4-27-12-8"></a>advanced<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-8-1" name="sec-1-4-27-12-8-1"></a>generators<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-8-1-1" name="sec-1-4-27-12-8-1-1"></a><a href="http://intermediatepythonista.com/python-generators">http://intermediatepythonista.com/python-generators</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-8-1-1-1" name="sec-1-4-27-12-8-1-1-1"></a><a href="http://www.dabeaz.com/finalgenerator/">http://www.dabeaz.com/finalgenerator/</a><br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-12-9" name="sec-1-4-27-12-9"></a>best practices<br  /><div class="outline-text-6" id="text-1-4-27-12-9">
<ul class="org-ul">
<li>Control Flow
<ul class="org-ul">
<li>`if&#x2026;elif&#x2026;` is the preferred replacement for any `case` or `switch` logic
<ul class="org-ul">
<li>source: <a href="http://docs.python.org/2/tutorial/controlflow.html#if-statements">http://docs.python.org/2/tutorial/controlflow.html#if-statements</a>
</li>
</ul>
</li>
</ul>
</li>
<li>Dicts
<ul class="org-ul">
<li>"Looping over dict keys and vals"
</li>
<li><a href="https://www.youtube.com/watch?v=OSGv2VnC0go#t=1292">https://www.youtube.com/watch?v=OSGv2VnC0go#t=1292</a>
</li>
<li>at 21m30s, "Looping over dict keys and vals"
</li>
<li>`k, v in dict.items()` makes a huge list, but is better than `for k in d`
</li>
<li>`for k, v in dict.iteritems()` is better than .items and returns an iterator
</li>
<li>aka, for iterating over keys AND values in dict, use .iteritems
</li>
<li>"Looping over dict keys"
</li>
<li><a href="https://www.youtube.com/watch?v=OSGv2VnC0go#t=1292">https://www.youtube.com/watch?v=OSGv2VnC0go#t=1292</a>
</li>
<li>`for k in dict.keys():` is better than `for k in dict` since makes list
</li>
</ul>
</li>
<li>File I/O
<ul class="org-ul">
<li>if you did not open a file with `with`, then you need to close the file
</li>
<li><a href="https://en.wikibooks.org/wiki/Non-Programmer's_Tutorial_for_Python_3/File_IO">https://en.wikibooks.org/wiki/Non-Programmer's_Tutorial_for_Python_3/File_IO</a>
</li>
</ul>
</li>
<li>Logic
<ul class="org-ul">
<li>if comparing floats, don't use logical equals `==`, instead use `&lt; epsilon` where epsilon is some small value.
</li>
<li>this is due to error accumulation in floats, etc.
</li>
</ul>
</li>
<li>2.7
<ul class="org-ul">
<li>Use `xrange` most? of the time instead of `range`
</li>
<li>not a problem in python3
</li>
<li>generally, use `izip` instead of `zip` for doing stuff over two lists, since `zip` makes a copy of both lists in memory and returns a list, whereas `izip` returns an iterator only over a certain portion
</li>
</ul>
</li>
</ul>
</div>

<ol class="org-ol"><li><a id="sec-1-4-27-12-9-1" name="sec-1-4-27-12-9-1"></a><a href="http://blog.dispatched.ch/2011/06/12/how-to-become-a-proficient-python-programmer/">http://blog.dispatched.ch/2011/06/12/how-to-become-a-proficient-python-programmer/</a><br  /></li>
<li><a id="sec-1-4-27-12-9-2" name="sec-1-4-27-12-9-2"></a><a href="http://hn.premii.com/#/comments/10831045">The Elements of Python Style</a><br  /></li>
<li><a id="sec-1-4-27-12-9-3" name="sec-1-4-27-12-9-3"></a>style<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-9-3-1" name="sec-1-4-27-12-9-3-1"></a><a href="http://hn.premii.com/#/comments/10831045">The Elements of Python Style</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-9-4" name="sec-1-4-27-12-9-4"></a><a href="https://news.ycombinator.com/item?id=9896369">Ask HN: Good Python codebases to read? | Hacker News</a><br  /></li>
<li><a id="sec-1-4-27-12-9-5" name="sec-1-4-27-12-9-5"></a><a href="https://news.ycombinator.com/item?id=5998750">Ask HN: Intermediate Python learning resources? | Hacker News</a><br  /></li>
<li><a id="sec-1-4-27-12-9-6" name="sec-1-4-27-12-9-6"></a><a href="http://hn.premii.com/#/comments/10891778">Complexity of Python Operations (2013)</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-10" name="sec-1-4-27-12-10"></a>debugging<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-10-1" name="sec-1-4-27-12-10-1"></a><a href="http://blog.ionelmc.ro/2013/06/05/python-debugging-tools/">http://blog.ionelmc.ro/2013/06/05/python-debugging-tools/</a><br  /></li>
<li><a id="sec-1-4-27-12-10-2" name="sec-1-4-27-12-10-2"></a><a href="https://pypi.python.org/pypi/ipdb">https://pypi.python.org/pypi/ipdb</a><br  /></li>
<li><a id="sec-1-4-27-12-10-3" name="sec-1-4-27-12-10-3"></a><a href="https://pythonconquerstheuniverse.wordpress.com/2009/09/10/debugging-in-python/">https://pythonconquerstheuniverse.wordpress.com/2009/09/10/debugging-in-python/</a><br  /></li>
<li><a id="sec-1-4-27-12-10-4" name="sec-1-4-27-12-10-4"></a><a href="https://docs.python.org/3.4/library/pdb.html">https://docs.python.org/3.4/library/pdb.html</a><br  /></li>
<li><a id="sec-1-4-27-12-10-5" name="sec-1-4-27-12-10-5"></a><a href="https://stackoverflow.com/questions/4228637/getting-started-with-the-python-debugger-pdb">https://stackoverflow.com/questions/4228637/getting-started-with-the-python-debugger-pdb</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-11" name="sec-1-4-27-12-11"></a>guis<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-11-1" name="sec-1-4-27-12-11-1"></a><a href="https://www.reddit.com/r/Python/comments/46jyvn/python_3_and_gui_is_qt_the_last_remaining_option/">Python 3 and GUI. Is Qt the last remaining option?</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-12" name="sec-1-4-27-12-12"></a>learning<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-12-1" name="sec-1-4-27-12-12-1"></a>memorize that numpy is row-major <a href="http://stackoverflow.com/a/20341959/2723794">http://stackoverflow.com/a/20341959/2723794</a> (meanwhile matlab data is column-major)<br  /></li>
<li><a id="sec-1-4-27-12-12-2" name="sec-1-4-27-12-12-2"></a>top 10 modules to learn <a href="http://www.reddit.com/r/Python/comments/28yo37/what_are_the_top_10_builtin_python_modules_that_a/">http://www.reddit.com/r/Python/comments/28yo37/what_are_the_top_10_builtin_python_modules_that_a/</a><br  /></li>
<li><a id="sec-1-4-27-12-12-3" name="sec-1-4-27-12-12-3"></a>go through Dive Into Python 3<br  /></li>
<li><a id="sec-1-4-27-12-12-4" name="sec-1-4-27-12-12-4"></a><a href="http://stackoverflow.com/questions/3873654/combinations-from-dictionary-with-list-values-using-python/3873734">http://stackoverflow.com/questions/3873654/combinations-from-dictionary-with-list-values-using-python/3873734</a><br  /></li>
<li><a id="sec-1-4-27-12-12-5" name="sec-1-4-27-12-12-5"></a><a href="http://lurnq.com/lesson/Getting-started-with-Python-Tips-Tools-and-Resources/">http://lurnq.com/lesson/Getting-started-with-Python-Tips-Tools-and-Resources/</a><br  /></li>
<li><a id="sec-1-4-27-12-12-6" name="sec-1-4-27-12-12-6"></a>importing<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-12-6-1" name="sec-1-4-27-12-12-6-1"></a><a href="http://blog.amir.rachum.com/post/63666832095/python-importing">http://blog.amir.rachum.com/post/63666832095/python-importing</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-12-7" name="sec-1-4-27-12-12-7"></a>string formatting <a href="https://docs.python.org/release/3.0.1/whatsnew/2.6.html#pep-3101">https://docs.python.org/release/3.0.1/whatsnew/2.6.html#pep-3101</a><br  /></li>
<li><a id="sec-1-4-27-12-12-8" name="sec-1-4-27-12-12-8"></a><a href="https://www.reddit.com/r/programming/comments/3384ql/super_helpful_resources_for_learning_to_program/">https://www.reddit.com/r/programming/comments/3384ql/super_helpful_resources_for_learning_to_program/</a><br  /></li>
<li><a id="sec-1-4-27-12-12-9" name="sec-1-4-27-12-12-9"></a><a href="http://composingprograms.com/">http://composingprograms.com/</a><br  /></li>
<li><a id="sec-1-4-27-12-12-10" name="sec-1-4-27-12-12-10"></a><a href="https://www.reddit.com/r/programming/comments/4e57ws/sicp_in_python_3_from_berkeley/">SICP in Python 3 from Berkeley</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13" name="sec-1-4-27-12-13"></a>libraries<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-1" name="sec-1-4-27-12-13-1"></a>alternatives to matplotlib <a href="http://www.reddit.com/r/Python/comments/2cxdml/python_for_business_analytics_reporting/cjk1el9">http://www.reddit.com/r/Python/comments/2cxdml/python_for_business_analytics_reporting/cjk1el9</a><br  /></li>
<li><a id="sec-1-4-27-12-13-2" name="sec-1-4-27-12-13-2"></a><a href="http://blog.hartleybrody.com/python-serialize/">http://blog.hartleybrody.com/python-serialize/</a><br  /></li>
<li><a id="sec-1-4-27-12-13-3" name="sec-1-4-27-12-13-3"></a>lrn-cython<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-3-1" name="sec-1-4-27-12-13-3-1"></a><a href="http://stackoverflow.com/questions/5710441/call-cython-function-from-c?lq=1">http://stackoverflow.com/questions/5710441/call-cython-function-from-c?lq=1</a><br  /></li>
<li><a id="sec-1-4-27-12-13-3-2" name="sec-1-4-27-12-13-3-2"></a><a href="http://www.reddit.com/r/programming/comments/2n5dx7/runcython_makes_it_dead_simple_to_use_the_cython/">http://www.reddit.com/r/programming/comments/2n5dx7/runcython_makes_it_dead_simple_to_use_the_cython/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-4" name="sec-1-4-27-12-13-4"></a>lrn-matplotlib<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-4-1" name="sec-1-4-27-12-13-4-1"></a><a href="https://github.com/WeatherGod/AnatomyOfMatplotlib">https://github.com/WeatherGod/AnatomyOfMatplotlib</a><br  /></li>
<li><a id="sec-1-4-27-12-13-4-2" name="sec-1-4-27-12-13-4-2"></a><a href="http://nbviewer.jupyter.org/github/WeatherGod/AnatomyOfMatplotlib/blob/master/AnatomyOfMatplotlib-Part2-Plotting_Methods_Overview.ipynb">http://nbviewer.jupyter.org/github/WeatherGod/AnatomyOfMatplotlib/blob/master/AnatomyOfMatplotlib-Part2-Plotting_Methods_Overview.ipynb</a><br  /></li>
<li><a id="sec-1-4-27-12-13-4-3" name="sec-1-4-27-12-13-4-3"></a><a href="https://news.ycombinator.com/item?id=14668706">https://news.ycombinator.com/item?id=14668706</a><br  /></li>
<li><a id="sec-1-4-27-12-13-4-4" name="sec-1-4-27-12-13-4-4"></a><a href="http://datacommunitydc.org/blog/2013/07/python-for-data-analysis-the-landscape-of-tutorials/">http://datacommunitydc.org/blog/2013/07/python-for-data-analysis-the-landscape-of-tutorials/</a><br  /></li>
<li><a id="sec-1-4-27-12-13-4-5" name="sec-1-4-27-12-13-4-5"></a><a href="http://matplotlib.org/examples/api/barchart_demo.html">http://matplotlib.org/examples/api/barchart_demo.html</a> seems like a decent example, IF it is canon<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-4-5-1" name="sec-1-4-27-12-13-4-5-1"></a>the fig in `fig, ax = plt.subplots()` is important, meaning the order of the returned thing from that func matter<br  /></li>
<li><a id="sec-1-4-27-12-13-4-5-2" name="sec-1-4-27-12-13-4-5-2"></a>one sets the ylabels etc. on what appears to be a LIVE `ax` object, independent of the name of the `rects2 = ax.bar()`<br  /></li>
<li><a id="sec-1-4-27-12-13-4-5-3" name="sec-1-4-27-12-13-4-5-3"></a>one saves the figure with what appears to be a LIVE `plt` usage, using `plt.savefig("file")`<br  /></li>
<li><a id="sec-1-4-27-12-13-4-5-4" name="sec-1-4-27-12-13-4-5-4"></a>this might explain why parallelizing it is difficult<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-4-6" name="sec-1-4-27-12-13-4-6"></a>matplotlib for python developers book?<br  /></li>
<li><a id="sec-1-4-27-12-13-4-7" name="sec-1-4-27-12-13-4-7"></a><a href="http://www.reddit.com/r/Python/comments/2cfulw/indepth_matplotlib_tutorials_beginner_to_advanced/">http://www.reddit.com/r/Python/comments/2cfulw/indepth_matplotlib_tutorials_beginner_to_advanced/</a><br  /></li>
<li><a id="sec-1-4-27-12-13-4-8" name="sec-1-4-27-12-13-4-8"></a>turning off 'mpl.use('Agg')' configs in runsim and plot<sub>austin</sub>, and putting `backend : Agg` in each computer's '~/.matplotlib/matplotlibrc' seems to help fix weird nonX11 parallel script plotting in matplotlib<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-5" name="sec-1-4-27-12-13-5"></a>json libs<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-5-1" name="sec-1-4-27-12-13-5-1"></a><a href="http://stackoverflow.com/questions/12451431/loading-parsing-json-file-in-python">http://stackoverflow.com/questions/12451431/loading-parsing-json-file-in-python</a><br  /></li>
<li><a id="sec-1-4-27-12-13-5-2" name="sec-1-4-27-12-13-5-2"></a><a href="http://stackoverflow.com/questions/2835559/python-parsing-file-json/2835672">http://stackoverflow.com/questions/2835559/python-parsing-file-json/2835672</a><br  /></li>
<li><a id="sec-1-4-27-12-13-5-3" name="sec-1-4-27-12-13-5-3"></a>apparently python lib 'ujson' is super fast<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-6" name="sec-1-4-27-12-13-6"></a>statsmodels<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-6-1" name="sec-1-4-27-12-13-6-1"></a>GLM class docs <a href="http://statsmodels.sourceforge.net/devel/generated/statsmodels.genmod.generalized_linear_model.GLM.html#statsmodels.genmod.generalized_linear_model.GLM">http://statsmodels.sourceforge.net/devel/generated/statsmodels.genmod.generalized_linear_model.GLM.html#statsmodels.genmod.generalized_linear_model.GLM</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-7" name="sec-1-4-27-12-13-7"></a>numpy<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-7-1" name="sec-1-4-27-12-13-7-1"></a>detecting if BLAS/LAPACK compiled into numpy <a href="http://stackoverflow.com/questions/9000164/how-to-check-blas-lapack-linkage-in-numpy-scipy">http://stackoverflow.com/questions/9000164/how-to-check-blas-lapack-linkage-in-numpy-scipy</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-8" name="sec-1-4-27-12-13-8"></a>pandas<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-8-1" name="sec-1-4-27-12-13-8-1"></a>howtos <a href="https://www.reddit.com/r/Python/comments/2k8h7j/pandas_more_advanced_analysis_munging_and/">https://www.reddit.com/r/Python/comments/2k8h7j/pandas_more_advanced_analysis_munging_and/</a><br  /></li>
<li><a id="sec-1-4-27-12-13-8-2" name="sec-1-4-27-12-13-8-2"></a><a href="http://pandas.pydata.org/pandas-docs/stable/comparison_with_r.html#comparison-with-r-r-libraries">http://pandas.pydata.org/pandas-docs/stable/comparison_with_r.html#comparison-with-r-r-libraries</a><br  /></li>
<li><a id="sec-1-4-27-12-13-8-3" name="sec-1-4-27-12-13-8-3"></a>hdf5 <a href="http://glowingpython.blogspot.com/2014/08/quick-hdf5-with-pandas.html">http://glowingpython.blogspot.com/2014/08/quick-hdf5-with-pandas.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-13-9" name="sec-1-4-27-12-13-9"></a>vbench (for benchmarking)<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-13-9-1" name="sec-1-4-27-12-13-9-1"></a><a href="https://github.com/pydata/vbench">https://github.com/pydata/vbench</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-12-14" name="sec-1-4-27-12-14"></a>package management and py versioning<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-1" name="sec-1-4-27-12-14-1"></a>Python project template with a convenient Makefile-facility and helpers | Hacker News <a href="https://news.ycombinator.com/item?id=13513685">https://news.ycombinator.com/item?id=13513685</a><br  /></li>
<li><a id="sec-1-4-27-12-14-2" name="sec-1-4-27-12-14-2"></a><a href="https://www.reddit.com/r/programming/comments/3rnj0u/pigar_a_tool_to_generate_requirements_for_your/">Pigar - A tool to generate requirements for your Python project : programming</a><br  /></li>
<li><a id="sec-1-4-27-12-14-3" name="sec-1-4-27-12-14-3"></a>anaconda<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-3-1" name="sec-1-4-27-12-14-3-1"></a>conda create: <a href="http://conda.pydata.org/docs/intro.html#creating-python-3-4-or-python-2-6-environments">http://conda.pydata.org/docs/intro.html#creating-python-3-4-or-python-2-6-environments</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-14-4" name="sec-1-4-27-12-14-4"></a>custom installations<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-4-1" name="sec-1-4-27-12-14-4-1"></a><a href="http://toomuchdata.com/2014/02/16/how-to-install-python-on-centos/">http://toomuchdata.com/2014/02/16/how-to-install-python-on-centos/</a><br  /></li>
<li><a id="sec-1-4-27-12-14-4-2" name="sec-1-4-27-12-14-4-2"></a><a href="http://iainhunter.wordpress.com/2012/11/08/howto-install-python3-pip3-tornado-on-mac/">http://iainhunter.wordpress.com/2012/11/08/howto-install-python3-pip3-tornado-on-mac/</a><br  /></li>
<li><a id="sec-1-4-27-12-14-4-3" name="sec-1-4-27-12-14-4-3"></a><a href="http://www.thisisthegreenroom.com/2011/installing-python-numpy-scipy-matplotlib-and-ipython-on-lion/">http://www.thisisthegreenroom.com/2011/installing-python-numpy-scipy-matplotlib-and-ipython-on-lion/</a><br  /></li>
<li><a id="sec-1-4-27-12-14-4-4" name="sec-1-4-27-12-14-4-4"></a><a href="http://www.lowindata.com/2013/installing-scientific-python-on-mac-os-x/">http://www.lowindata.com/2013/installing-scientific-python-on-mac-os-x/</a><br  /></li>
<li><a id="sec-1-4-27-12-14-4-5" name="sec-1-4-27-12-14-4-5"></a><a href="http://neuroscience.telenczuk.pl/?p=400">http://neuroscience.telenczuk.pl/?p=400</a><br  /></li>
<li><a id="sec-1-4-27-12-14-4-6" name="sec-1-4-27-12-14-4-6"></a><a href="http://superuser.com/questions/276840/uninstalling-python-3-on-a-mac">http://superuser.com/questions/276840/uninstalling-python-3-on-a-mac</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-14-5" name="sec-1-4-27-12-14-5"></a>virtualenv<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-5-1" name="sec-1-4-27-12-14-5-1"></a>I'm putting 2 in ~/python<sub>virtualenvs</sub>/2.7.8/<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-5-1-1" name="sec-1-4-27-12-14-5-1-1"></a>symlinking the binary to the system's python2<br  /></li>
<li><a id="sec-1-4-27-12-14-5-1-2" name="sec-1-4-27-12-14-5-1-2"></a>using `pip` to install pretty much everything<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-14-5-2" name="sec-1-4-27-12-14-5-2"></a>note! you need a gcc-fortran compiler like `multilib/gcc-fortran-multilib` in your system to properly install scipy inside a venv<br  /></li>
<li><a id="sec-1-4-27-12-14-5-3" name="sec-1-4-27-12-14-5-3"></a>install instructions<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-5-3-1" name="sec-1-4-27-12-14-5-3-1"></a>get virtualenv easily via <a href="http://virtualenv.readthedocs.org/en/latest/virtualenv.html">http://virtualenv.readthedocs.org/en/latest/virtualenv.html</a> , it don't matter babe, preferably just get it from your package manager<br  /></li>
<li><a id="sec-1-4-27-12-14-5-3-2" name="sec-1-4-27-12-14-5-3-2"></a>note  that the VERSION OF PYTHON the virtualenv you download is in is the version of python it installs<br  /></li>
<li><a id="sec-1-4-27-12-14-5-3-3" name="sec-1-4-27-12-14-5-3-3"></a>run `virtualenv &lt;-p BIN&gt; ENV` where BIN is the actual python binary you want to install and ENV is the directory it'll install everything to, and so I typically use '~/python<sub>virtualenvs</sub>/&lt;version&gt;'<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-12-14-6" name="sec-1-4-27-12-14-6"></a>distributing<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-14-6-1" name="sec-1-4-27-12-14-6-1"></a><a href="https://glyph.twistedmatrix.com/2015/09/software-you-can-use.html">https://glyph.twistedmatrix.com/2015/09/software-you-can-use.html</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-12-15" name="sec-1-4-27-12-15"></a>packaging<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-15-1" name="sec-1-4-27-12-15-1"></a><a href="https://packaging.python.org/tutorials/distributing-packages/">https://packaging.python.org/tutorials/distributing-packages/</a><br  /></li>
<li><a id="sec-1-4-27-12-15-2" name="sec-1-4-27-12-15-2"></a>namespacing "submodules" in your package: <a href="https://docs.python.org/3/reference/import.html#submodules">https://docs.python.org/3/reference/import.html#submodules</a><br  /></li>
<li><a id="sec-1-4-27-12-15-3" name="sec-1-4-27-12-15-3"></a><a href="http://infinitemonkeycorps.net/docs/pph/">http://infinitemonkeycorps.net/docs/pph/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-16" name="sec-1-4-27-12-16"></a>scientific (incl visxn)<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-16-1" name="sec-1-4-27-12-16-1"></a>python scientific lecture notes in Study<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-16-1-1" name="sec-1-4-27-12-16-1-1"></a>via youtube/entries in lib/python/matplotlib<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-16-2" name="sec-1-4-27-12-16-2"></a>ODE solvers vs matlab<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-16-2-1" name="sec-1-4-27-12-16-2-1"></a><a href="https://gist.github.com/moble/3aa44230256b66956587">https://gist.github.com/moble/3aa44230256b66956587</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-2" name="sec-1-4-27-12-16-2-2"></a><a href="http://mail.scipy.org/pipermail/scipy-user/2010-February/024143.html">http://mail.scipy.org/pipermail/scipy-user/2010-February/024143.html</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-3" name="sec-1-4-27-12-16-2-3"></a><a href="http://stackoverflow.com/questions/26770112/rewriting-python-scipy-integrate-odeint-to-mimic-matlab-ode15s">http://stackoverflow.com/questions/26770112/rewriting-python-scipy-integrate-odeint-to-mimic-matlab-ode15s</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-4" name="sec-1-4-27-12-16-2-4"></a><a href="http://stackoverflow.com/questions/22608223/how-does-scipy-integrate-odeint-accelerate-function-evaluation/22608568#22608568">http://stackoverflow.com/questions/22608223/how-does-scipy-integrate-odeint-accelerate-function-evaluation/22608568#22608568</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-5" name="sec-1-4-27-12-16-2-5"></a><a href="https://itp.tugraz.at/~ert//blog/2014/06/02/equivalent-ode-integrators-in-matlab-and-scipy/">https://itp.tugraz.at/~ert//blog/2014/06/02/equivalent-ode-integrators-in-matlab-and-scipy/</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-6" name="sec-1-4-27-12-16-2-6"></a><a href="http://numerics.kaust.edu.sa/nodepy/">http://numerics.kaust.edu.sa/nodepy/</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-7" name="sec-1-4-27-12-16-2-7"></a>[pdf] <a href="http://hplgit.github.io/odespy/doc/pub/tutorial/odespy.pdf">http://hplgit.github.io/odespy/doc/pub/tutorial/odespy.pdf</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-8" name="sec-1-4-27-12-16-2-8"></a>[pdf] <a href="http://homes.esat.kuleuven.be/~mpederso/papers/numpy.pdf">http://homes.esat.kuleuven.be/~mpederso/papers/numpy.pdf</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-9" name="sec-1-4-27-12-16-2-9"></a>[pdf] <a href="http://mil-oss.org/resources/mil-oss-wg3_replacing-matlab-with-paython_andy-henshaw.pdf">http://mil-oss.org/resources/mil-oss-wg3_replacing-matlab-with-paython_andy-henshaw.pdf</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-10" name="sec-1-4-27-12-16-2-10"></a><a href="http://stackoverflow.com/questions/2133031/is-matlab-faster-than-python">http://stackoverflow.com/questions/2133031/is-matlab-faster-than-python</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-11" name="sec-1-4-27-12-16-2-11"></a>[pdf] <a href="https://www.cs.virginia.edu/~skadron/Papers/BiC09.pdf">https://www.cs.virginia.edu/~skadron/Papers/BiC09.pdf</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-12" name="sec-1-4-27-12-16-2-12"></a>[pdf] <a href="http://bmi.bmt.tue.nl/sysbio/software/Speeding%20up%20simulations%20of%20ODE%20models%20in%20Matlab%20using%20CVode%20and%20MEX%20files.pdf">http://bmi.bmt.tue.nl/sysbio/software/Speeding%20up%20simulations%20of%20ODE%20models%20in%20Matlab%20using%20CVode%20and%20MEX%20files.pdf</a><br  /></li>
<li><a id="sec-1-4-27-12-16-2-13" name="sec-1-4-27-12-16-2-13"></a>this seems to be exactly the same as what's used in dnsim <a href="http://blogs.mathworks.com/loren/2011/11/14/generating-c-code-from-your-matlab-algorithms/#12">http://blogs.mathworks.com/loren/2011/11/14/generating-c-code-from-your-matlab-algorithms/#12</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-16-3" name="sec-1-4-27-12-16-3"></a><a href="http://stackoverflow.com/questions/9000164/how-to-check-blas-lapack-linkage-in-numpy-scipy">http://stackoverflow.com/questions/9000164/how-to-check-blas-lapack-linkage-in-numpy-scipy</a><br  /></li>
<li><a id="sec-1-4-27-12-16-4" name="sec-1-4-27-12-16-4"></a>albersszafir (Danielle Szafir)<br  /><div class="outline-text-7" id="text-1-4-27-12-16-4">
<p>
.@stefanvdwalt 's Python Data Science Survival Pack: <a href="https://t.co/0kJyKhxhji">https://t.co/0kJyKhxhji</a> #ieeevis (via @EricCAlexander)
</p>

<p>
4:06 PM Oct 25th via Twitter Web Client
<a href="https://twitter.com/dalbersszafir/status/658374028680372224][Twitter">https://twitter.com/dalbersszafir/status/658374028680372224][Twitter</a> / Danielle Szafir: .@stefanvdwalt 's Python D&#x2026;]]
</p>
</div>
</li>

<li><a id="sec-1-4-27-12-16-5" name="sec-1-4-27-12-16-5"></a><a href="http://hn.premii.com/#/comments/12722465">http://hn.premii.com/#/comments/12722465</a><br  /></li>
<li><a id="sec-1-4-27-12-16-6" name="sec-1-4-27-12-16-6"></a>visxn<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-16-6-1" name="sec-1-4-27-12-16-6-1"></a><a href="https://speakerdeck.com/jakevdp/pythons-visualization-landscape-pycon-2017">https://speakerdeck.com/jakevdp/pythons-visualization-landscape-pycon-2017</a><br  /></li>
<li><a id="sec-1-4-27-12-16-6-2" name="sec-1-4-27-12-16-6-2"></a><a href="https://www.reddit.com/r/Python/comments/55k4ru/a_dramatic_tour_through_pythons_data/">https://www.reddit.com/r/Python/comments/55k4ru/a_dramatic_tour_through_pythons_data/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-12-17" name="sec-1-4-27-12-17"></a>testing<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-17-1" name="sec-1-4-27-12-17-1"></a><a href="http://pytest.org/latest/">http://pytest.org/latest/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-12-18" name="sec-1-4-27-12-18"></a>vim<br  /><ol class="org-ol"><li><a id="sec-1-4-27-12-18-1" name="sec-1-4-27-12-18-1"></a><a href="https://www.reddit.com/r/Python/comments/3qf1qi/vim_and_python_a_match_made_in_heaven/cwenvm1">good<sub>names</sub><sub>all</sub><sub>taken</sub> comments on VIM and Python - a match made in heaven</a><br  /></li>
<li><a id="sec-1-4-27-12-18-2" name="sec-1-4-27-12-18-2"></a><a href="https://github.com/klen/python-mode">https://github.com/klen/python-mode</a><br  /></li>
<li><a id="sec-1-4-27-12-18-3" name="sec-1-4-27-12-18-3"></a><a href="https://www.reddit.com/r/Python/comments/1x9rhb/the_best_life_jacket_for_programming_with_vim/">https://www.reddit.com/r/Python/comments/1x9rhb/the_best_life_jacket_for_programming_with_vim/</a><br  /></li>
<li><a id="sec-1-4-27-12-18-4" name="sec-1-4-27-12-18-4"></a><a href="https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/">https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/</a><br  /></li>
<li><a id="sec-1-4-27-12-18-5" name="sec-1-4-27-12-18-5"></a><a href="https://www.fullstackpython.com/vim.html">https://www.fullstackpython.com/vim.html</a><br  /></li>
<li><a id="sec-1-4-27-12-18-6" name="sec-1-4-27-12-18-6"></a><a href="https://justin.abrah.ms/vim/vim_and_python.html">https://justin.abrah.ms/vim/vim_and_python.html</a><br  /></li>
<li><a id="sec-1-4-27-12-18-7" name="sec-1-4-27-12-18-7"></a><a href="http://docs.python-guide.org/en/latest/dev/env/">http://docs.python-guide.org/en/latest/dev/env/</a><br  /></li>
<li><a id="sec-1-4-27-12-18-8" name="sec-1-4-27-12-18-8"></a><a href="https://news.ycombinator.com/item?id=4234768">https://news.ycombinator.com/item?id=4234768</a><br  /></li>
<li><a id="sec-1-4-27-12-18-9" name="sec-1-4-27-12-18-9"></a><a href="http://jedi.jedidjah.ch/en/latest/">http://jedi.jedidjah.ch/en/latest/</a><br  /></li>
<li><a id="sec-1-4-27-12-18-10" name="sec-1-4-27-12-18-10"></a><a href="https://www.reddit.com/r/vim/comments/2j0fxc/python_3_completion_vim_plugins/">https://www.reddit.com/r/vim/comments/2j0fxc/python_3_completion_vim_plugins/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-13" name="sec-1-4-27-13"></a>lrn-r-language<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-1" name="sec-1-4-27-13-1"></a>quick notes<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-1-1" name="sec-1-4-27-13-1-1"></a>can check class of an object [does this mean any DATA object in R?] with `class()` or check type with `typeof()`<br  /></li>
<li><a id="sec-1-4-27-13-1-2" name="sec-1-4-27-13-1-2"></a>similarly, can look at structure of any data with `str()`<br  /></li>
<li><a id="sec-1-4-27-13-1-3" name="sec-1-4-27-13-1-3"></a><a href="https://github.com/mikelove/r-gotchas">https://github.com/mikelove/r-gotchas</a><br  /></li>
<li><a id="sec-1-4-27-13-1-4" name="sec-1-4-27-13-1-4"></a>cannot (easily?) add columns of greater length to a data.frame, INCLUDING an empty one. which is annoying, but also means you're not constantly spewing NA values into larger and large data.frames.<br  /></li>
<li><a id="sec-1-4-27-13-1-5" name="sec-1-4-27-13-1-5"></a>NA = not available but still a logical type, NULL = more of an "undefined value" type that does NOT work with logic, numerics, etc.<br  /></li>
<li><a id="sec-1-4-27-13-1-6" name="sec-1-4-27-13-1-6"></a>ggplot2<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-1-6-1" name="sec-1-4-27-13-1-6-1"></a>`ggplot() + derp` doesn't like lists of `geom<sub>line</sub>()`'s etc., since not functions but rather environments?<br  /></li>
<li><a id="sec-1-4-27-13-1-6-2" name="sec-1-4-27-13-1-6-2"></a>stackoverflow says to use "faceting" builtin to ggplot2 instead of loop/apply for subplots etc.<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-1-7" name="sec-1-4-27-13-1-7"></a>`%&gt;%` is a pipe operator, see <a href="https://github.com/smbache/magrittr">https://github.com/smbache/magrittr</a> , needs magrittr loaded<br  /></li>
<li><a id="sec-1-4-27-13-1-8" name="sec-1-4-27-13-1-8"></a>subsetting data frames: bracket indexing vs use of `subset()<br  /><div class="outline-text-7" id="text-1-4-27-13-1-8">
<ul class="org-ul">
<li>the below is how you would grab all columns' information, for the rows that match our search.
</li>
</ul>
<p>
```
derp &lt;- melt(df, id='voltages', variable.name='q<sub>value'</sub>, value.name = 'time<sub>constants'</sub>)
subset(derp, q<sub>value</sub> %in% 'tau<sub>h</sub><sub>3'</sub>)
derp[derp$q<sub>value</sub> %in% "tau<sub>h</sub><sub>3</sub>",]
derp[derp$q<sub>value</sub> == "tau<sub>h</sub><sub>3</sub>",]
```
</p>
<ul class="org-ul">
<li>bracket indexing ONLY if it ends with a comma, WTF? has to do with how you can use `derp[1,3]` or `derp[,3]` to access portions of the data frame. First number is row (which is how we're trying to find it), second is column, so using a comma then nothing means "return all columns for the found rows", as opposed to `,1` which would return the entries of only the first column, that match the row match we did
</li>
<li>a la `derp[&lt;rows&gt;, &lt;columns&gt;]`
</li>
<li>This only appears to make sense for searching down individual columns, since the `$` operator implies that you're only talking about columns
</li>
<li>This is still pretty confusing, and there is poor equivalency here between rows and columns &#x2013; much of the behavior is assuming you care about columns
</li>
<li>wickham talks about implementing `subset()`, but even though it's easier and saves on keystrokes since it makes assumptions about what your variables are based on the data that you initially supply it with, in longer, more complicated scripts, it can screw up things since it uses dynamic scoping. See <a href="http://adv-r.had.co.nz/Computing-on-the-language.html#nse">http://adv-r.had.co.nz/Computing-on-the-language.html#nse</a>
</li>
<li><b><b>so it seems for longer scripts, i.e. what i always want to do, it's better to do bracket indexing rather than `subset()`.</b></b>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-27-13-1-9" name="sec-1-4-27-13-1-9"></a>note on r-lang: to install packages inside R, on linux must install "tk" and "tcl" libraries/programs yourself<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-2" name="sec-1-4-27-13-2"></a>comparisons to other analysis langs<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-2-1" name="sec-1-4-27-13-2-1"></a><a href="http://r4stats.com/articles/popularity/">http://r4stats.com/articles/popularity/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-3" name="sec-1-4-27-13-3"></a>debugging<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-3-1" name="sec-1-4-27-13-3-1"></a>overview <a href="http://stackoverflow.com/questions/4442518/general-suggestions-for-debugging-r">http://stackoverflow.com/questions/4442518/general-suggestions-for-debugging-r</a><br  /></li>
<li><a id="sec-1-4-27-13-3-2" name="sec-1-4-27-13-3-2"></a><a href="http://www.biostat.jhsph.edu/~rpeng/docs/R-debug-tools.pdf">http://www.biostat.jhsph.edu/~rpeng/docs/R-debug-tools.pdf</a><br  /></li>
<li><a id="sec-1-4-27-13-3-3" name="sec-1-4-27-13-3-3"></a>cwatson says he uses `browser()` e.g. <a href="http://www.stats.uwo.ca/faculty/murdoch/software/debuggingR/debug.shtml">http://www.stats.uwo.ca/faculty/murdoch/software/debuggingR/debug.shtml</a><br  /></li>
<li><a id="sec-1-4-27-13-3-4" name="sec-1-4-27-13-3-4"></a>apparently can use gdb? <a href="http://www.stats.uwo.ca/faculty/murdoch/software/debuggingR/gdb.shtml">http://www.stats.uwo.ca/faculty/murdoch/software/debuggingR/gdb.shtml</a><br  /></li>
<li><a id="sec-1-4-27-13-3-5" name="sec-1-4-27-13-3-5"></a>ess has ess-tracebug<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-4" name="sec-1-4-27-13-4"></a>documentation<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-4-1" name="sec-1-4-27-13-4-1"></a>wickham recommends roxygen2 &#x2013; R packaging and documentation generation, a la his holiness wickham <a href="http://r-pkgs.had.co.nz/intro.html">http://r-pkgs.had.co.nz/intro.html</a><br  /></li>
<li><a id="sec-1-4-27-13-4-2" name="sec-1-4-27-13-4-2"></a>R roxygen2 more docs <a href="http://stackoverflow.com/a/25638970/2723794">http://stackoverflow.com/a/25638970/2723794</a> (since apparently base docs not super good)<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-5" name="sec-1-4-27-13-5"></a>r gotchas<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-5-1" name="sec-1-4-27-13-5-1"></a><a href="https://ironholds.org/projects/rbitrary/">https://ironholds.org/projects/rbitrary/</a><br  /></li>
<li><a id="sec-1-4-27-13-5-2" name="sec-1-4-27-13-5-2"></a>mike's <a href="https://github.com/mikelove/r-gotchas">https://github.com/mikelove/r-gotchas</a><br  /></li>
<li><a id="sec-1-4-27-13-5-3" name="sec-1-4-27-13-5-3"></a>R inferno <a href="http://www.burns-stat.com/documents/books/the-r-inferno/">http://www.burns-stat.com/documents/books/the-r-inferno/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-6" name="sec-1-4-27-13-6"></a>learning R<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-6-1" name="sec-1-4-27-13-6-1"></a><a href="http://r4ds.had.co.nz/">http://r4ds.had.co.nz/</a><br  /></li>
<li><a id="sec-1-4-27-13-6-2" name="sec-1-4-27-13-6-2"></a>use <a href="http://swirlstats.com/">http://swirlstats.com/</a> to learn R?<br  /></li>
<li><a id="sec-1-4-27-13-6-3" name="sec-1-4-27-13-6-3"></a>advanced R book <a href="http://adv-r.had.co.nz/">http://adv-r.had.co.nz/</a> and <a href="http://www.johndcook.com/blog/r_language_for_programmers/">http://www.johndcook.com/blog/r_language_for_programmers/</a><br  /></li>
<li><a id="sec-1-4-27-13-6-4" name="sec-1-4-27-13-6-4"></a>func prog in r<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-6-4-1" name="sec-1-4-27-13-6-4-1"></a>apply funcs <a href="http://nsaunders.wordpress.com/2010/08/20/a-brief-introduction-to-apply-in-r/">http://nsaunders.wordpress.com/2010/08/20/a-brief-introduction-to-apply-in-r/</a><br  /></li>
<li><a id="sec-1-4-27-13-6-4-2" name="sec-1-4-27-13-6-4-2"></a><a href="http://adv-r.had.co.nz/Functional-programming.html">http://adv-r.had.co.nz/Functional-programming.html</a><br  /></li>
<li><a id="sec-1-4-27-13-6-4-3" name="sec-1-4-27-13-6-4-3"></a><a href="http://stat.ethz.ch/R-manual/R-devel/library/base/html/funprog.html">http://stat.ethz.ch/R-manual/R-devel/library/base/html/funprog.html</a><br  /></li>
<li><a id="sec-1-4-27-13-6-4-4" name="sec-1-4-27-13-6-4-4"></a><a href="http://redsymbol.net/articles/crash-course-applied-functional-programming/">http://redsymbol.net/articles/crash-course-applied-functional-programming/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-6-5" name="sec-1-4-27-13-6-5"></a>patterns / idioms / helpful<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-6-5-1" name="sec-1-4-27-13-6-5-1"></a>load/clean/func/do <a href="http://stackoverflow.com/a/1434424">http://stackoverflow.com/a/1434424</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-13-7" name="sec-1-4-27-13-7"></a>libraries<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-1" name="sec-1-4-27-13-7-1"></a>data.table &#x2013; for larger data sets<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-1-1" name="sec-1-4-27-13-7-1-1"></a><a href="http://hn.premii.com/#/comments/8794276">http://hn.premii.com/#/comments/8794276</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-2" name="sec-1-4-27-13-7-1-2"></a><a href="http://blog.yhathq.com/posts/fast-summary-statistics-with-data-dot-table.html">http://blog.yhathq.com/posts/fast-summary-statistics-with-data-dot-table.html</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-3" name="sec-1-4-27-13-7-1-3"></a><a href="http://datatable.r-forge.r-project.org/datatable-faq.pdf">http://datatable.r-forge.r-project.org/datatable-faq.pdf</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-4" name="sec-1-4-27-13-7-1-4"></a>comparison with data frame etc.<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-1-4-1" name="sec-1-4-27-13-7-1-4-1"></a><a href="http://stackoverflow.com/questions/13618488/what-you-can-do-with-data-frame-that-you-cant-in-data-table">http://stackoverflow.com/questions/13618488/what-you-can-do-with-data-frame-that-you-cant-in-data-table</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-4-2" name="sec-1-4-27-13-7-1-4-2"></a><a href="http://www.r-bloggers.com/data-table-or-data-frame/">http://www.r-bloggers.com/data-table-or-data-frame/</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-4-3" name="sec-1-4-27-13-7-1-4-3"></a><a href="https://github.com/Rdatatable/data.table/wiki/Benchmarks-:-Grouping">https://github.com/Rdatatable/data.table/wiki/Benchmarks-:-Grouping</a><br  /></li>
<li><a id="sec-1-4-27-13-7-1-4-4" name="sec-1-4-27-13-7-1-4-4"></a><a href="http://stackoverflow.com/questions/21435339/data-table-vs-dplyr-can-one-do-something-well-the-other-cant-or-does-poorly?rq=1">http://stackoverflow.com/questions/21435339/data-table-vs-dplyr-can-one-do-something-well-the-other-cant-or-does-poorly?rq=1</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-13-7-2" name="sec-1-4-27-13-7-2"></a>ESS<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-2-1" name="sec-1-4-27-13-7-2-1"></a>ESS with Rmarkdown files <a href="http://johnstantongeddes.org/open%20science/2014/03/26/Rmd-polymode.html">http://johnstantongeddes.org/open%20science/2014/03/26/Rmd-polymode.html</a><br  /></li>
<li><a id="sec-1-4-27-13-7-2-2" name="sec-1-4-27-13-7-2-2"></a>how to debug with ESS<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-7-3" name="sec-1-4-27-13-7-3"></a>ggvis<br  /></li>
<li><a id="sec-1-4-27-13-7-4" name="sec-1-4-27-13-7-4"></a>ggplot2<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-4-1" name="sec-1-4-27-13-7-4-1"></a>read ggplot2 book in R<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-7-5" name="sec-1-4-27-13-7-5"></a>json libs: rjson vs RJSONIO vs jsonlite, apparently jsonlite is newest/best, and pretty compatible interface with the native rjson<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-7-5-1" name="sec-1-4-27-13-7-5-1"></a>comparison of the three <a href="http://rstudio-pubs-static.s3.amazonaws.com/31702_9c22e3d1a0c44968a4a1f9656f1800ab.html">http://rstudio-pubs-static.s3.amazonaws.com/31702_9c22e3d1a0c44968a4a1f9656f1800ab.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-7-6" name="sec-1-4-27-13-7-6"></a>magrittr &#x2013; as a better, faster pipeR <a href="http://cran.r-project.org/web/packages/magrittr/vignettes/magrittr.html">http://cran.r-project.org/web/packages/magrittr/vignettes/magrittr.html</a> (for comparison with pipeR <a href="http://renkun.me/blog/2014/08/08/difference-between-magrittr-and-pipeR.html">http://renkun.me/blog/2014/08/08/difference-between-magrittr-and-pipeR.html</a>)<br  /></li>
<li><a id="sec-1-4-27-13-7-7" name="sec-1-4-27-13-7-7"></a>melt (part of package `reshape`)<br  /><div class="outline-text-7" id="text-1-4-27-13-7-7">
<p>
```
derp &lt;- melt(df, id.vars='voltages', variable.name='q<sub>value'</sub>, value.name = 'time<sub>constants'</sub>)
```
</p>
<ul class="org-ul">
<li>id = sort of our "index variable"
</li>
<li>variable = names of each of the columns; will be turned into R "Factors" a la categorical variable
</li>
<li>values = what they sound like, the actual data
</li>
<li>note that normally, each of the above are turned into fields of the data frame with the exact same name as above! slightly confusing, since they are all so generic
</li>
<li>this worked for getting the values according to a specific "factor", as they are organized in the "variable" field(?)
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-27-13-7-8" name="sec-1-4-27-13-7-8"></a>plyr funcs &#x2013;  for modern usage of data frames, by Hadley Wickham <a href="http://blog.rstudio.org/2014/01/17/introducing-dplyr/">http://blog.rstudio.org/2014/01/17/introducing-dplyr/</a><br  /></li>
<li><a id="sec-1-4-27-13-7-9" name="sec-1-4-27-13-7-9"></a>shiny &#x2013; <a href="http://shiny.rstudio.com/">http://shiny.rstudio.com/</a><br  /></li>
<li><a id="sec-1-4-27-13-7-10" name="sec-1-4-27-13-7-10"></a>slidify for presentations with rmarkdown <a href="http://ramnathv.github.io/slidify/">http://ramnathv.github.io/slidify/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-8" name="sec-1-4-27-13-8"></a>packaging<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-8-1" name="sec-1-4-27-13-8-1"></a>building R package process, from wickham's <a href="http://r-pkgs.had.co.nz/intro.html">http://r-pkgs.had.co.nz/intro.html</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-8-1-1" name="sec-1-4-27-13-8-1-1"></a>0. install all necessary packages, especially "devtools"<br  /></li>
<li><a id="sec-1-4-27-13-8-1-2" name="sec-1-4-27-13-8-1-2"></a>1. create base/bare package via `devtools::create("~/Dropbox/progz/lib/R/dnsimr")` (Rstudio will install automatically?)<br  /></li>
<li><a id="sec-1-4-27-13-8-1-3" name="sec-1-4-27-13-8-1-3"></a>2. install if not Rstudio via `devtools::install("~/Dropbox/progz/lib/R/dnsimr")` or `install.packages("~/Dropbox/progz/lib/R/dnsimr", repos=NULL, type="source")` a la <a href="http://stackoverflow.com/a/1474125/2723794">http://stackoverflow.com/a/1474125/2723794</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-8-1-3-1" name="sec-1-4-27-13-8-1-3-1"></a>as developing, can reload package with `devtools::load<sub>all</sub>("~/Dropbox/progz/lib/R/dnsimr")`<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-13-9" name="sec-1-4-27-13-9"></a>scripting<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-9-1" name="sec-1-4-27-13-9-1"></a>Rscript vs R CMD BATCH (also vs littler) <a href="http://biostat.jhsph.edu/~hjaffee/R_tasks.html">http://biostat.jhsph.edu/~hjaffee/R_tasks.html</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-9-1-1" name="sec-1-4-27-13-9-1-1"></a>only Rscripts allows "stdout redirection", so whatever use Rscript<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-13-10" name="sec-1-4-27-13-10"></a>speed improvements<br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-10-1" name="sec-1-4-27-13-10-1"></a>faster R <a href="http://www.noamross.net/blog/2013/4/25/faster-talk.html">http://www.noamross.net/blog/2013/4/25/faster-talk.html</a><br  /></li>
<li><a id="sec-1-4-27-13-10-2" name="sec-1-4-27-13-10-2"></a>ask mike about usage of "RLLVM" library for just-in-time R compilation<br  /></li>
<li><a id="sec-1-4-27-13-10-3" name="sec-1-4-27-13-10-3"></a>mike says Rcpp is easy to use and fast <a href="http://adv-r.had.co.nz/Rcpp.html">http://adv-r.had.co.nz/Rcpp.html</a><br  /></li>
<li><a id="sec-1-4-27-13-10-4" name="sec-1-4-27-13-10-4"></a><a href="http://stat.ethz.ch/R-manual/R-devel/library/parallel/html/mclapply.html">http://stat.ethz.ch/R-manual/R-devel/library/parallel/html/mclapply.html</a><br  /></li>
<li><a id="sec-1-4-27-13-10-5" name="sec-1-4-27-13-10-5"></a><a href="http://rpubs.com/wbnicholson/32755">http://rpubs.com/wbnicholson/32755</a><br  /><ol class="org-ol"><li><a id="sec-1-4-27-13-10-5-1" name="sec-1-4-27-13-10-5-1"></a>mentions parallel Rcpp! apparently RcppParallel is in dev<br  /></li></ol>
</li>
<li><a id="sec-1-4-27-13-10-6" name="sec-1-4-27-13-10-6"></a>"Rprof()" for time profiling?<br  /></li>
<li><a id="sec-1-4-27-13-10-7" name="sec-1-4-27-13-10-7"></a><a href="http://blog.yhathq.com/posts/reducing-your-r-memory-footprint-by-7000x.html">http://blog.yhathq.com/posts/reducing-your-r-memory-footprint-by-7000x.html</a><br  /></li>
<li><a id="sec-1-4-27-13-10-8" name="sec-1-4-27-13-10-8"></a>need to dl BLAS for R separately?<br  /></li>
<li><a id="sec-1-4-27-13-10-9" name="sec-1-4-27-13-10-9"></a>R parallel <a href="http://cran.r-project.org/web/views/HighPerformanceComputing.html">http://cran.r-project.org/web/views/HighPerformanceComputing.html</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-27-14" name="sec-1-4-27-14"></a>lrn-ruby<br  /><ol class="org-ol"><li><a id="sec-1-4-27-14-1" name="sec-1-4-27-14-1"></a>for Jekyll/GitHub Pages<br  /></li>
<li><a id="sec-1-4-27-14-2" name="sec-1-4-27-14-2"></a>on Ubuntu, can't just use default ruby install (of course), use <a href="https://gorails.com/setup/ubuntu/16.04">https://gorails.com/setup/ubuntu/16.04</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-15" name="sec-1-4-27-15"></a>lrn-rust<br  /><ol class="org-ol"><li><a id="sec-1-4-27-15-1" name="sec-1-4-27-15-1"></a><a href="http://hn.premii.com/#/comments/10863114">Why I love Rust</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-16" name="sec-1-4-27-16"></a>lrn-sql<br  /><ol class="org-ol"><li><a id="sec-1-4-27-16-1" name="sec-1-4-27-16-1"></a><a href="http://sql-joins.leopard.in.ua/">http://sql-joins.leopard.in.ua/</a><br  /></li>
<li><a id="sec-1-4-27-16-2" name="sec-1-4-27-16-2"></a>why not to use mysql <a href="http://grimoire.ca/mysql/choose-something-else">http://grimoire.ca/mysql/choose-something-else</a><br  /></li>
<li><a id="sec-1-4-27-16-3" name="sec-1-4-27-16-3"></a><a href="http://hn.premii.com/#/comments/9464505">PostgreSQL vs. MS SQL Server</a><br  /></li>
<li><a id="sec-1-4-27-16-4" name="sec-1-4-27-16-4"></a><a href="http://mikesmithers.wordpress.com/2011/11/26/installing-oracle-11gxe-on-mint-and-ubuntu/">http://mikesmithers.wordpress.com/2011/11/26/installing-oracle-11gxe-on-mint-and-ubuntu/</a><br  /></li>
<li><a id="sec-1-4-27-16-5" name="sec-1-4-27-16-5"></a><a href="http://jim-zimmerman.com/?p=392">http://jim-zimmerman.com/?p=392</a><br  /></li>
<li><a id="sec-1-4-27-16-6" name="sec-1-4-27-16-6"></a><a href="http://docs.oracle.com/cd/E17781_01/install.112/e18802/toc.htm#BABJFAIA">http://docs.oracle.com/cd/E17781_01/install.112/e18802/toc.htm#BABJFAIA</a><br  /></li>
<li><a id="sec-1-4-27-16-7" name="sec-1-4-27-16-7"></a><a href="https://forums.oracle.com/forums/thread.jspa?messageID=10280550&tstart=0#10280550">https://forums.oracle.com/forums/thread.jspa?messageID=10280550&tstart=0#10280550</a><br  /></li>
<li><a id="sec-1-4-27-16-8" name="sec-1-4-27-16-8"></a><a href="https://cn.forums.oracle.com/forums/thread.jspa?threadID=2300010">https://cn.forums.oracle.com/forums/thread.jspa?threadID=2300010</a><br  /></li>
<li><a id="sec-1-4-27-16-9" name="sec-1-4-27-16-9"></a><a href="https://cn.forums.oracle.com/forums/thread.jspa?threadID=2301639&tstart=0">https://cn.forums.oracle.com/forums/thread.jspa?threadID=2301639&tstart=0</a><br  /></li>
<li><a id="sec-1-4-27-16-10" name="sec-1-4-27-16-10"></a>sqlite<br  /><ol class="org-ol"><li><a id="sec-1-4-27-16-10-1" name="sec-1-4-27-16-10-1"></a><a href="http://charlesleifer.com/blog/five-reasons-you-should-use-sqlite-in-2016/">http://charlesleifer.com/blog/five-reasons-you-should-use-sqlite-in-2016/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-27-16-11" name="sec-1-4-27-16-11"></a>why postgresql <a href="https://www.compose.io/articles/what-postgresql-has-over-other-open-source-sql-databases/">https://www.compose.io/articles/what-postgresql-has-over-other-open-source-sql-databases/</a><br  /></li>
<li><a id="sec-1-4-27-16-12" name="sec-1-4-27-16-12"></a><a href="https://news.ycombinator.com/item?id=12978139">https://news.ycombinator.com/item?id=12978139</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-28" class="outline-4">
<h4 id="sec-1-4-28"><span class="section-number-4">1.4.28</span> lrn-linux</h4>
<div class="outline-text-4" id="text-1-4-28">
</div><ol class="org-ol"><li><a id="sec-1-4-28-1" name="sec-1-4-28-1"></a><a href="http://linoxide.com/guide/linux-command-shelf.html">http://linoxide.com/guide/linux-command-shelf.html</a><br  /></li>
<li><a id="sec-1-4-28-2" name="sec-1-4-28-2"></a><a href="https://sanctum.geek.nz/arabesque/linux-crypto-backups/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed:+arabesqueblog+(Arabesque)">https://sanctum.geek.nz/arabesque/linux-crypto-backups/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed:+arabesqueblog+(Arabesque)</a><br  /></li>
<li><a id="sec-1-4-28-3" name="sec-1-4-28-3"></a>commands/programs for the terminal<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1" name="sec-1-4-28-3-1"></a>lrn-mutt (other entries for al/pine show 1. dev has stopped, 2. doesn't have all the fixins, 3. only mutt lets you change ALL? keybindings)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-1" name="sec-1-4-28-3-1-1"></a>patterns for search<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-1-1" name="sec-1-4-28-3-1-1-1"></a><a href="http://www.therandymon.com/woodnotes/mutt/node70.html">http://www.therandymon.com/woodnotes/mutt/node70.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-1-2" name="sec-1-4-28-3-1-2"></a>mutt flags<br  /><div class="outline-text-7" id="text-1-4-28-3-1-2">
<ul class="org-ul">
<li>+   message is to you and you only
</li>
<li>T   message is to you, but also to or cc'ed to others
</li>
<li>C   message is cc'ed to you
</li>
<li>F   message is from you
</li>
<li>L   message is sent to a subscribed mailing list
</li>
<li>D   message is deleted (is marked for deletion)
</li>
<li>d   message have attachments marked for deletion
</li>
<li>K   contains a PGP public key
</li>
<li>N   message is new
</li>
<li>O   message is old
</li>
<li>P   message is PGP encrypted
</li>
<li>r   message has been replied to
</li>
<li>S   message is PGP signed, and the signature is succesfully verified
</li>
<li>s   message is PGP signed
</li>
<li>!   message is flagged
</li>
<li>*   message is tagged
</li>
</ul>
</div>
</li>
<li><a id="sec-1-4-28-3-1-3" name="sec-1-4-28-3-1-3"></a>comparison<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-3-1" name="sec-1-4-28-3-1-3-1"></a>alpine vs reapline vs mutt<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-3-1-1" name="sec-1-4-28-3-1-3-1-1"></a><a href="http://www.nerdenmeister.org/2011/09/04/alpine-vs-mutt/">http://www.nerdenmeister.org/2011/09/04/alpine-vs-mutt/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4" name="sec-1-4-28-3-1-4"></a>guides<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-1" name="sec-1-4-28-3-1-4-1"></a><a href="http://fsk141.com/linux/my-fear-of-mutt-and-why-it-was-all-for-null.html">http://fsk141.com/linux/my-fear-of-mutt-and-why-it-was-all-for-null.html</a><br  /></li>
<li><a id="sec-1-4-28-3-1-4-2" name="sec-1-4-28-3-1-4-2"></a><a href="http://stevelosh.com/blog/2012/10/the-homely-mutt/">http://stevelosh.com/blog/2012/10/the-homely-mutt/</a> is excellent, and makes lots of references to other blog intros itself<br  /></li>
<li><a id="sec-1-4-28-3-1-4-3" name="sec-1-4-28-3-1-4-3"></a><a href="https://wiki.archlinux.org/index.php/OfflineIMAP#Automatic_mutt_mailbox_generation">https://wiki.archlinux.org/index.php/OfflineIMAP#Automatic_mutt_mailbox_generation</a><br  /></li>
<li><a id="sec-1-4-28-3-1-4-4" name="sec-1-4-28-3-1-4-4"></a><a href="http://www.reddit.com/r/commandline/comments/1dafbe/mutt_i_dont_get_it/c9ohm50">http://www.reddit.com/r/commandline/comments/1dafbe/mutt_i_dont_get_it/c9ohm50</a><br  /></li>
<li><a id="sec-1-4-28-3-1-4-5" name="sec-1-4-28-3-1-4-5"></a><a href="https://www.debian-administration.org/article/75/Reading_HTML_email_with_Mutt">https://www.debian-administration.org/article/75/Reading_HTML_email_with_Mutt</a><br  /></li>
<li><a id="sec-1-4-28-3-1-4-6" name="sec-1-4-28-3-1-4-6"></a>notes on <a href="https://www.proteansec.com/linux/the-ultimate-guide-to-mutt/">https://www.proteansec.com/linux/the-ultimate-guide-to-mutt/</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-1" name="sec-1-4-28-3-1-4-6-1"></a>"The <b>folder</b> configuration option defined the mailbox location [like ~/Mail], while"<br  /></li>
<li><a id="sec-1-4-28-3-1-4-6-2" name="sec-1-4-28-3-1-4-6-2"></a>"the <b>spoolfile</b> defines our default inbox location. [like ~/Mail/name.surname/Inbox]"<br  /></li>
<li><a id="sec-1-4-28-3-1-4-6-3" name="sec-1-4-28-3-1-4-6-3"></a>Mutt also contains different configuration options regarding different folders:<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-3-1" name="sec-1-4-28-3-1-4-6-3-1"></a>"spoolfile / Inbox":<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-3-1-1" name="sec-1-4-28-3-1-4-6-3-1-1"></a>the startup folder where all the new email is kept: this can be thought as an Inbox folder.<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4-6-3-2" name="sec-1-4-28-3-1-4-6-3-2"></a>"mbox / Archive":<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-3-2-1" name="sec-1-4-28-3-1-4-6-3-2-1"></a>a folder where we can move the read emails, so they don’t show up in spoolfile anymore (but we also don’t want to delete those emails). This can be thought as an Archive folder.<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4-6-3-3" name="sec-1-4-28-3-1-4-6-3-3"></a>"record / Sent Mail":<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-3-3-1" name="sec-1-4-28-3-1-4-6-3-3-1"></a>a folder where sent messages are moved, so we have them archived somewhere in case we need it sometime in the future. This can be thought as a Sent Mail folder.<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4-6-3-4" name="sec-1-4-28-3-1-4-6-3-4"></a>"postponed / Drafts":<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-6-3-4-0-1" name="sec-1-4-28-3-1-4-6-3-4-0-1"></a>a folder where emails that we’ve started to write, but haven’t finished yet are stored. This can be thought as a Drafts folder.<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4-7" name="sec-1-4-28-3-1-4-7"></a>extensions<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-1" name="sec-1-4-28-3-1-4-7-1"></a>goobook for google contacts<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-1-1" name="sec-1-4-28-3-1-4-7-1-1"></a>if gives weird authentication error, then run in bash `goobook authenticate`<br  /></li>
<li><a id="sec-1-4-28-3-1-4-7-1-2" name="sec-1-4-28-3-1-4-7-1-2"></a><a href="http://fsk141.com/linux/gooey-google-contact-goodness-with-mutt.html">http://fsk141.com/linux/gooey-google-contact-goodness-with-mutt.html</a><br  /></li>
<li><a id="sec-1-4-28-3-1-4-7-1-3" name="sec-1-4-28-3-1-4-7-1-3"></a>to install mutt on OS X with Macports, need to throw in "+imap" flag to install<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-1-3-1" name="sec-1-4-28-3-1-4-7-1-3-1"></a>more complicated than that:<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-1-3-1-1" name="sec-1-4-28-3-1-4-7-1-3-1-1"></a>THIS has the answer <a href="http://ajitabhpandey.info/2012/08/installing-mutt-on-mac-os-x/">http://ajitabhpandey.info/2012/08/installing-mutt-on-mac-os-x/</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-1-3-1-1-1" name="sec-1-4-28-3-1-4-7-1-3-1-1-1"></a>you have to use `sudo port install mutt-devel +compress+gdbm+gnuregex+gpgme+headercache+imap+pop+sasl+smtp+ssl+trash`<br  /></li>
<li><a id="sec-1-4-28-3-1-4-7-1-3-1-1-2" name="sec-1-4-28-3-1-4-7-1-3-1-1-2"></a>this is because the SSL addition doesn't build for some reason without some of the other packages, and not all the things in the other-referenced muttrc's work without these packages<br  /></li></ol>
</li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-3-1-4-7-2" name="sec-1-4-28-3-1-4-7-2"></a>offlineimap<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-4-7-2-1" name="sec-1-4-28-3-1-4-7-2-1"></a>if cert doesn't work, try putting the first SHA-1 from running `gnutls-cli -p 993 imap.gmail.com` into ~/.offlineimaprc<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-3-1-5" name="sec-1-4-28-3-1-5"></a>tips<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-1-5-1" name="sec-1-4-28-3-1-5-1"></a>delete duplicates <a href="http://41j.com/blog/2011/09/delete-duplicate-emails-in-mutt/">http://41j.com/blog/2011/09/delete-duplicate-emails-in-mutt/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-3-2" name="sec-1-4-28-3-2"></a>cron<br  /><div class="outline-text-6" id="text-1-4-28-3-2">
<ol class="org-ol">
<li>must change editor to something other than Vim apparently, like by entering to the terminal "$ $EDITOR=nano"
</li>
<li>enter into the terminal "$ crontab -e" and you'll be able to change the cron thing, where each entry is
Argument 1: Minute (0 - 59)
Argument 2: Hour (0 - 23)
Argument 3: Day of Month (1 - 31)
Argument 4: Month (1-12)
Argument 5: Day of Week (0 - 6) Sunday = 0
Argument 6: Command
</li>
</ol>
</div>
</li>

<li><a id="sec-1-4-28-3-3" name="sec-1-4-28-3-3"></a>mmv <a href="http://linux.die.net/Linux-CLI/mass-rename.html">http://linux.die.net/Linux-CLI/mass-rename.html</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-3-1" name="sec-1-4-28-3-3-1"></a>use it via `mmv \*.JPG \#1.jpeg`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-4" name="sec-1-4-28-3-4"></a>lrn-ranger<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-4-1" name="sec-1-4-28-3-4-1"></a><a href="https://www.digitalocean.com/community/tutorials/installing-and-using-ranger-a-terminal-file-manager-on-a-ubuntu-vps">https://www.digitalocean.com/community/tutorials/installing-and-using-ranger-a-terminal-file-manager-on-a-ubuntu-vps</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-5" name="sec-1-4-28-3-5"></a>rsync<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-5-1" name="sec-1-4-28-3-5-1"></a><a href="http://moo.nac.uci.edu/~hjm/HOWTO_move_data.html">http://moo.nac.uci.edu/~hjm/HOWTO_move_data.html</a><br  /></li>
<li><a id="sec-1-4-28-3-5-2" name="sec-1-4-28-3-5-2"></a><a href="https://library.linode.com/linux-tools/utilities/rsync">https://library.linode.com/linux-tools/utilities/rsync</a><br  /></li>
<li><a id="sec-1-4-28-3-5-3" name="sec-1-4-28-3-5-3"></a><a href="http://everythinglinux.org/rsync/rsync_content.html">http://everythinglinux.org/rsync/rsync_content.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-6" name="sec-1-4-28-3-6"></a>sed<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-6-1" name="sec-1-4-28-3-6-1"></a><a href="http://hn.premii.com/#/comments/8851124">http://hn.premii.com/#/comments/8851124</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-7" name="sec-1-4-28-3-7"></a>tmux<br  /><ol class="org-ol"><li><a id="sec-1-4-28-3-7-1" name="sec-1-4-28-3-7-1"></a><a href="http://robots.thoughtbot.com/how-to-copy-and-paste-with-tmux-on-mac-os-x">http://robots.thoughtbot.com/how-to-copy-and-paste-with-tmux-on-mac-os-x</a><br  /></li>
<li><a id="sec-1-4-28-3-7-2" name="sec-1-4-28-3-7-2"></a><a href="http://danielallendeutsch.com/blog/16-using-tmux-properly.html">http://danielallendeutsch.com/blog/16-using-tmux-properly.html</a><br  /></li>
<li><a id="sec-1-4-28-3-7-3" name="sec-1-4-28-3-7-3"></a><a href="http://robots.thoughtbot.com/post/55885045171/tmux-copy-paste-on-os-x-a-better-future">http://robots.thoughtbot.com/post/55885045171/tmux-copy-paste-on-os-x-a-better-future</a><br  /></li>
<li><a id="sec-1-4-28-3-7-4" name="sec-1-4-28-3-7-4"></a><a href="http://www.davidxia.com/2013/03/remote-pair-programming-with-tmux-in-the-cloud/">http://www.davidxia.com/2013/03/remote-pair-programming-with-tmux-in-the-cloud/</a><br  /></li>
<li><a id="sec-1-4-28-3-7-5" name="sec-1-4-28-3-7-5"></a><a href="http://rhnh.net/2011/08/20/vim-and-tmux-on-osx">http://rhnh.net/2011/08/20/vim-and-tmux-on-osx</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-3-8" name="sec-1-4-28-3-8"></a>fzf <a href="https://github.com/junegunn/fzf">https://github.com/junegunn/fzf</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-4" name="sec-1-4-28-4"></a>conky system monitor<br  /></li>
<li><a id="sec-1-4-28-5" name="sec-1-4-28-5"></a>lrn-android<br  /><ol class="org-ol"><li><a id="sec-1-4-28-5-1" name="sec-1-4-28-5-1"></a>guide to making android stuff <a href="https://github.com/nstevens/androidguide/wiki">https://github.com/nstevens/androidguide/wiki</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6" name="sec-1-4-28-6"></a>lrn-arch documentation (for macbook air at least) (much of this is out of date&#x2026;and unnecessary if using a distro with a full DE)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-1" name="sec-1-4-28-6-1"></a>backlight<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-1-1" name="sec-1-4-28-6-1-1"></a>`echo 9 | sudo tee /sys/class/backlight/acpi<sub>video0</sub>/brightness` changes screen brightness!<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-1-1-1" name="sec-1-4-28-6-1-1-1"></a>max screen brightness for acpi<sub>video0</sub> is 15 - use this one as main<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-1-2" name="sec-1-4-28-6-1-2"></a>`echo 5 | sudo tee /sys/class/backlight/intel<sub>backlight</sub>/brightness` is another screen brightness one, don't use<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-1-2-1" name="sec-1-4-28-6-1-2-1"></a>max screen brightness for intel<sub>backlight</sub> is 1808, REALLY - don't bother using this one<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-2" name="sec-1-4-28-6-2"></a>copypasta / system clipboard<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-2-1" name="sec-1-4-28-6-2-1"></a>main thing: CLIPBOARD buffer is the one I use<br  /></li>
<li><a id="sec-1-4-28-6-2-2" name="sec-1-4-28-6-2-2"></a>emacs: omg, the headaches man&#x2026;so on arch, a surefire way / this worked once:<br  /><div class="outline-text-7" id="text-1-4-28-6-2-2">
<ol class="org-ol">
<li>do NOT install emacs-nox (i.e. the one without X11 workings), instead install the normal emacs
</li>
<li>not only that, but do NOT run emacs strictly inside the terminal, i.e. starting it with "emacs &#x2013;no-window-system", as this prevents seemingly any X Primary/Clipboard clipboard buffer interaction
</li>
<li>Install program `xclip`, as you do NOT need programs `xorg-xclipboard` or `xsel` for copypasta to work
<ul class="org-ul">
<li>you can test the Primary/Clipboard clipboard buffers via `xclip -out -selection primary` etc.
</li>
</ul>
</li>
<li>Enjoy - AFAIK, by Emacs &gt;23, you don't even need to `(setq x-select-enable-clipboard t)` to make it copy to X11's Clipboard clipboard buffer. It should work at this point, but I haven't done it from scratch.
</li>
</ol>
</div>
</li>

<li><a id="sec-1-4-28-6-2-3" name="sec-1-4-28-6-2-3"></a><a id="ID-00c9c268-5700-4d70-b882-50aa62a15027" name="ID-00c9c268-5700-4d70-b882-50aa62a15027"></a>get arch copypasta working in vim and terminal emacs<br  /><div class="outline-text-7" id="text-1-4-28-6-2-3">

<ul class="org-ul">
<li>notes 2014-08-21
<ul class="org-ul">
<li>so, with a new and improved `omgclipboard`, including now knowing the existence of the `secondary` and `buffer-cut` buffers
</li>
<li>note that this is after I got the emacs clipboard working, which involved JUST running it in standalone-X-window style outside of the terminal
</li>
<li>copying into buffers
<ul class="org-ul">
<li>`emacs` (nonterminal, that pops out) copies into the CLIPBOARD buffer
</li>
<li>`emacs` terminal does not copy into any buffers! (it does use a program-private buffer though)
</li>
<li>`vim` copies into the PRIMARY buffer
<ul class="org-ul">
<li>this includes, that if the vim session is exited, the PRIMARY buffer is emptied
</li>
<li>this is with either the `set clipboard=unnamed` setting on, or NO explicit clipboard setting on in its .vimrc
</li>
<li>hooray! with `set clipboard=unnamedplus` (see the plus), it ONLY uses the CLIPBOARD, not the PRIMARY as before from <a href="http://stackoverflow.com/a/11489440">http://stackoverflow.com/a/11489440</a>
</li>
</ul>
</li>
<li>`firefox` is complicated
<ul class="org-ul">
<li>`firefox` JUST selection of texts actually copies into the PRIMARY (though this usually happens when copying text)
</li>
<li>ctrl+c or a "real copy" copies its contents into the CLIPBOARD
</li>
<li>so, what ends up happening most of the time is it copies into both PRIMARY and CLIPBOARD
</li>
</ul>
</li>
<li>`skype` and `vinagre` right-click copies its contents into BOTH PRIMARY and CLIPBOARD
</li>
</ul>
</li>
<li>pasting from buffers
<ul class="org-ul">
<li>`vim` pastes from the PRIMARY buffer (e.g. from firefox' copying)
</li>
<li>`firefox` pastes from the CLIPBOARD buffer
</li>
<li>`emacs`, (nonterminal) under evil, pastes weirdness and apparently has an internal buffer, vim-style. Natively, though, it pastes from the CLIPBOARD buffer, as you would expect, since it only writes to the CLIPBOARD one.
</li>
<li>`emacs` terminal also doesn't paste from any of the other buffers
</li>
<li>middle mouse in tmux in urxvt pastes something??? just a hyphen? it doesn't appear to be any of the 4 buffers from xclip
<ul class="org-ul">
<li>more testing reveals it pastes a PORTION of the text in the PRIMARY buffer&#x2026;wtf???
</li>
</ul>
</li>
<li>as a test of general desktop stuff, `skype` and `vinagre` pastes from the CLIPBOARD
</li>
</ul>
</li>
<li>after looking online, apparently many people complain about this with firefox, and it seems difficult to change
</li>
</ul>
</li>
<li>therefore, based on firefox's (and other desktop apps) pasting preference for CLIPBOARD, and the customizability of vim and emacs, the best thing to do is apparently center everything around the CLIPBOARD buffer, e.g.
<ol class="org-ol">
<li>make vim copy/paste from it, and
<ul class="org-ul">
<li>vim: to make it use CLIPBOARD, add `set clipboard=unnamedplus` in .vimrc, yes!!! a la <a href="http://stackoverflow.com/a/11489440">http://stackoverflow.com/a/11489440</a>
</li>
</ul>
</li>
<li>make terminal-emacs copy/paste from it
<ul class="org-ul">
<li>so, nonterminal emacs is fine, it doesn't even need `(xclip-mode 1)` in emacs settings to copy/paste to CLIPBOARD, it works out of the box
</li>
<li>terminal emacs (i.e. with '-nw' passed) is more complicated, has two requirements:
<ol class="org-ol">
<li>emacs needs the TERM environment variable to be set to 'xterm' or 'xterm-256color'
<ul class="org-ul">
<li>this can NOT be done automatically in emacs settings, apparently, even with the `setenv` function, since it still doesn't seem to work. Solution now is to add a 'TERM=xterm-256color' definition prior to all alias'd emacs bash aliases, so it's pretty much fixed
</li>
<li>variants of screen and urxvt will not work! AFAIK this includes 'screen-256color', 'screen', 'rxvt-unicode-256color', 'rxvt-unicode'
</li>
<li>note that this turns the emacs colors awful, the 'color-theme' package can rectify this
</li>
</ul>
</li>
<li>emacs also needs the 'xclip' emacs package (you also need it installed on the system), and you have to turn it on with just `(xclip-mode 1)`
</li>
</ol>
</li>
</ul>
</li>
</ol>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-4-28-6-2-4" name="sec-1-4-28-6-2-4"></a>got copypasta working in urxvt tmux terminal!<br  /><div class="outline-text-7" id="text-1-4-28-6-2-4">
<ul class="org-ul">
<li>apparently, can do `ctrl+meta+v` to paste from X11 CLIPBOARD buffer, judging from the docs at <a href="http://pod.tst.eu/http://cvs.schmorp.de/rxvt-unicode/doc/rxvt.1.pod">http://pod.tst.eu/http://cvs.schmorp.de/rxvt-unicode/doc/rxvt.1.pod</a>
<p>
:ID:       c6260a97-e525-4a61-857c-9f8a99c3213c
</p>
<p>
:END:
</p>
</li>
</ul>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-28-6-3" name="sec-1-4-28-6-3"></a>file manager<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-3-1" name="sec-1-4-28-6-3-1"></a>can change nautilus settings via running `dconf-editor` and going to 'org-&gt;nautilus-&gt;' to hardcode the objects, or the thing in the upper left duh, or can use `gnome-tweak-tool`<br  /></li>
<li><a id="sec-1-4-28-6-3-2" name="sec-1-4-28-6-3-2"></a>can use `locate` via the 'mlocate' package, must first update with `sudo updatedb` - it's pretty fast<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-4" name="sec-1-4-28-6-4"></a>file system<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-4-1" name="sec-1-4-28-6-4-1"></a>filelight for visualizing hdd space<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-5" name="sec-1-4-28-6-5"></a>firefox kde? theme color change bug <a href="https://bbs.archlinux.org/viewtopic.php?id=211139">https://bbs.archlinux.org/viewtopic.php?id=211139</a> and <a href="https://bbs.archlinux.org/viewtopic.php?id=137382">https://bbs.archlinux.org/viewtopic.php?id=137382</a><br  /></li>
<li><a id="sec-1-4-28-6-6" name="sec-1-4-28-6-6"></a>kernel modules<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-6-1" name="sec-1-4-28-6-6-1"></a>there are some details in the wireless note<br  /></li>
<li><a id="sec-1-4-28-6-6-2" name="sec-1-4-28-6-6-2"></a>the proper place to blacklist things, as per <a href="https://wiki.archlinux.org/index.php/Kernel_modules#Blacklisting">https://wiki.archlinux.org/index.php/Kernel_modules#Blacklisting</a> , is in a `/etc/modprobe.d/&lt;modprobe|blacklist&gt;.conf` file where you just put an entry for `blacklist &lt;module name&gt;`<br  /></li>
<li><a id="sec-1-4-28-6-6-3" name="sec-1-4-28-6-6-3"></a>`lspci -vnn | grep -7 14e4` tells us what actual modules are being used by the hardware, in this case the wireless card in a macbook<br  /></li>
<li><a id="sec-1-4-28-6-6-4" name="sec-1-4-28-6-6-4"></a>you can see the status of some? modules via `lsmod`, and you can see where all the modules are loaded from via `mkinitcpio -v | less`<br  /></li>
<li><a id="sec-1-4-28-6-6-5" name="sec-1-4-28-6-6-5"></a>you can potentially individually load modules by making files in `/etc/modules-load.d/&lt;module&gt;.conf` where the contents is just the module name<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-7" name="sec-1-4-28-6-7"></a>keepass / passwords<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-7-1" name="sec-1-4-28-6-7-1"></a>had to install custom keepass portable to home dir for FF extension "KeeFox" &#x2013; for deets, see its main wurbsite<br  /></li>
<li><a id="sec-1-4-28-6-7-2" name="sec-1-4-28-6-7-2"></a>update: i have no freaking clue where the above wurbsite actually is, it might actual be INSIDE the plugin (via html file)<br  /></li>
<li><a id="sec-1-4-28-6-7-3" name="sec-1-4-28-6-7-3"></a>Note: must install `xsel` package to get copying directly from KeePass, though still don't have paste TO KeePass<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-8" name="sec-1-4-28-6-8"></a>keyboard / keymap<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-8-1" name="sec-1-4-28-6-8-1"></a>ctrl-caps swapping? only diff is, as of 2014-12-10, I now use '/usr/share/kbd/keymaps/i386/qwerty/us-nocapslock.map.gz' where the Caps<sub>Lock</sub> keycode is turned into Control vis-a-vis <a href="http://unix.stackexchange.com/a/7676">http://unix.stackexchange.com/a/7676</a><br  /></li>
<li><a id="sec-1-4-28-6-8-2" name="sec-1-4-28-6-8-2"></a>note that this is an update that affects the terminal but NOT X11, which is still dominated by 10-evdev.conf, which now has "ctrl:nocaps" instead of constantly switching "ctrl:swapcaps"<br  /></li>
<li><a id="sec-1-4-28-6-8-3" name="sec-1-4-28-6-8-3"></a>now, if NEED capslock, just `loadkeys &#x2026;/us-capsctrlswap.map.gz` (or maybe can just do `loadkeys us-capsctrlswap`)<br  /></li>
<li><a id="sec-1-4-28-6-8-4" name="sec-1-4-28-6-8-4"></a>can set default keymap persistently via `localectl set-keymap &#x2013;no-convert us-nocapslock`<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-8-4-1" name="sec-1-4-28-6-8-4-1"></a>might be able to do this as well with this, but untested<br  /><div class="outline-text-8" id="text-1-4-28-6-8-4-1">
<p>
```{bash}
</p>
<p>
export KEYMAP=us-nocapslock
```
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-28-6-8-5" name="sec-1-4-28-6-8-5"></a>passing `alt+L/R arrow` through virtual console: further edits to '&#x2026;/us-nocapslock.map.gz' from here fix it <a href="http://unix.stackexchange.com/a/146241/94558">http://unix.stackexchange.com/a/146241/94558</a> (though NOTE that there is a typo in the answer, the second string is F106 not F105, simple and obvious typo)<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-9" name="sec-1-4-28-6-9"></a>installing arch<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-9-1" name="sec-1-4-28-6-9-1"></a>I think the blog I used to great success was <a href="http://blog.panks.me/posts/2013/06/arch-linux-installation-with-os-x-on-macbook-air-dual-boot/">http://blog.panks.me/posts/2013/06/arch-linux-installation-with-os-x-on-macbook-air-dual-boot/</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-9-1-1" name="sec-1-4-28-6-9-1-1"></a>other ones<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-9-1-1-1" name="sec-1-4-28-6-9-1-1-1"></a><a href="https://github.com/pandeiro/arch-on-air">https://github.com/pandeiro/arch-on-air</a><br  /></li>
<li><a id="sec-1-4-28-6-9-1-1-2" name="sec-1-4-28-6-9-1-1-2"></a><a href="http://codylittlewood.com/arch-linux-on-macbook-pro-installation/">http://codylittlewood.com/arch-linux-on-macbook-pro-installation/</a><br  /></li>
<li><a id="sec-1-4-28-6-9-1-1-3" name="sec-1-4-28-6-9-1-1-3"></a><a href="https://vec.io/posts/use-arch-linux-and-xmonad-on-macbook-pro-with-retina-display">https://vec.io/posts/use-arch-linux-and-xmonad-on-macbook-pro-with-retina-display</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-9-1-2" name="sec-1-4-28-6-9-1-2"></a>the only mistake, IIRC, is that `-C` isn't a proper argument to `grub-mkstandalone`, as instead you should use whattever I can't recall it's referring to in the man page<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-9-2" name="sec-1-4-28-6-9-2"></a>checkout <a href="https://github.com/jantman/puppet-archlinux-macbookretina">https://github.com/jantman/puppet-archlinux-macbookretina</a> and <a href="http://hn.premii.com/#/comments/8904213">http://hn.premii.com/#/comments/8904213</a><br  /></li>
<li><a id="sec-1-4-28-6-9-3" name="sec-1-4-28-6-9-3"></a>reinstalling arch <a href="https://wiki.archlinux.org/index.php/Install_from_existing_Linux">https://wiki.archlinux.org/index.php/Install_from_existing_Linux</a> and <a href="http://www.reddit.com/r/archlinux/comments/2wi1k1/id_like_to_point_out_the_arch_wiki_has_many_ways/">http://www.reddit.com/r/archlinux/comments/2wi1k1/id_like_to_point_out_the_arch_wiki_has_many_ways/</a><br  /></li>
<li><a id="sec-1-4-28-6-9-4" name="sec-1-4-28-6-9-4"></a>this was helpful <a href="https://vec.io/posts/use-arch-linux-and-xmonad-on-macbook-pro-with-retina-display">https://vec.io/posts/use-arch-linux-and-xmonad-on-macbook-pro-with-retina-display</a><br  /></li>
<li><a id="sec-1-4-28-6-9-5" name="sec-1-4-28-6-9-5"></a>THIS was what made me get through reinstalling <a href="http://zanshin.net/2015/02/05/arch-linux-on-a-macbook-pro-part-3-base-installation/">http://zanshin.net/2015/02/05/arch-linux-on-a-macbook-pro-part-3-base-installation/</a><br  /></li>
<li><a id="sec-1-4-28-6-9-6" name="sec-1-4-28-6-9-6"></a>XXX make a note that can Terminal from Apple's perspective in HFS+ partition when rebooting with Cmd+r to do a net install!!!<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-10" name="sec-1-4-28-6-10"></a>laptop power<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-10-1" name="sec-1-4-28-6-10-1"></a><a href="https://wiki.archlinux.org/index.php/MacBook#Power_management">https://wiki.archlinux.org/index.php/MacBook#Power_management</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-11" name="sec-1-4-28-6-11"></a>lrn-dotfiles<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-11-1" name="sec-1-4-28-6-11-1"></a>gnu stow <a href="http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html">http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-12" name="sec-1-4-28-6-12"></a>maintenance<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-12-1" name="sec-1-4-28-6-12-1"></a>obviously, pay attention to your programs when `pacman -Suy`<br  /></li>
<li><a id="sec-1-4-28-6-12-2" name="sec-1-4-28-6-12-2"></a>`pipelight` is a special case, as it needs to be activated (see its entry under netflix) every time a new version is installed<br  /></li>
<li><a id="sec-1-4-28-6-12-3" name="sec-1-4-28-6-12-3"></a>haskell: run `cabal update` and `cabal install world` to update installed libs for haskell use<br  /></li>
<li><a id="sec-1-4-28-6-12-4" name="sec-1-4-28-6-12-4"></a>what is what is file "000033.log" in dropbox? how to search for that, find? is it emacs?<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-13" name="sec-1-4-28-6-13"></a>microphone<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-13-1" name="sec-1-4-28-6-13-1"></a>starting pulseaudio server and switching input in pavucontrol to analog seems to make mic work<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-14" name="sec-1-4-28-6-14"></a>mime / xdg-open types<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-14-1" name="sec-1-4-28-6-14-1"></a>installed 'mimeopen' package to be able to 'mimeopen -d file.pdf', then can set /usr/bin/okular to be the program, it works! with calibre and xdg-open and everything<br  /></li>
<li><a id="sec-1-4-28-6-14-2" name="sec-1-4-28-6-14-2"></a>use `mimeopen -d &lt;file&gt;.&lt;filetype&gt; to CLI-set which specific program you want to use for that filetype<br  /></li>
<li><a id="sec-1-4-28-6-14-3" name="sec-1-4-28-6-14-3"></a>`xdg-mime query default application/pdf` to query program<br  /></li>
<li><a id="sec-1-4-28-6-14-4" name="sec-1-4-28-6-14-4"></a>`xdg-mime query filetype file.pdf` to query filetype<br  /></li>
<li><a id="sec-1-4-28-6-14-5" name="sec-1-4-28-6-14-5"></a>some applications appear to force their Mimetypes in a way that conflicts with even when you set it<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-14-5-1" name="sec-1-4-28-6-14-5-1"></a>check out `grep 'application/pdf' /usr/share/applications/*' to see which ones reset<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-15" name="sec-1-4-28-6-15"></a>neovim<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-15-1" name="sec-1-4-28-6-15-1"></a>got everything working (minus powerline, which appears to be a fundamental issue with vim's `bindeval`) by installing from yaourt `neovim-git` and `python2-neovim-git`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-16" name="sec-1-4-28-6-16"></a>netflix and az prime<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-1" name="sec-1-4-28-6-16-1"></a>how I got netflix working on FIREFOX:<br  /></li>
<li><a id="sec-1-4-28-6-16-2" name="sec-1-4-28-6-16-2"></a>just to be careful, make sure you close all browsers before updating: <a href="https://answers.launchpad.net/pipelight/+faq/2357">https://answers.launchpad.net/pipelight/+faq/2357</a><br  /></li>
<li><a id="sec-1-4-28-6-16-3" name="sec-1-4-28-6-16-3"></a>write down that needed to activate multilib section of /etc/pacman.conf in order to install pipelight for netflix ANY way, since it was necessary for ANYTHING for wine, including most/all of it's lib32-x dependencies<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-3-1" name="sec-1-4-28-6-16-3-1"></a>this is done by uncommenting the `[multilib]` lines in `/etc/pacman.conf`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-16-4" name="sec-1-4-28-6-16-4"></a>to make it easier, add pipelight to `/etc/pacman.conf`<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-4-1" name="sec-1-4-28-6-16-4-1"></a>do all of step 1 in <a href="http://pipelight.net/cms/install/installation-arch-linux.html">http://pipelight.net/cms/install/installation-arch-linux.html</a> to add the pipelight binary repos to your native pacman behavior<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-16-5" name="sec-1-4-28-6-16-5"></a>just to be safe do "sudo pipelight-plugin &#x2013;disable-all"<br  /></li>
<li><a id="sec-1-4-28-6-16-6" name="sec-1-4-28-6-16-6"></a>"sudo pipelight-plugin &#x2013;enable silverlight"", then accept the licenses (SUDO is important here)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-6-1" name="sec-1-4-28-6-16-6-1"></a>note that enabling the plugin and accepting the licenses are currently needed every update<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-16-7" name="sec-1-4-28-6-16-7"></a>also did "sudo pipelight-plugin &#x2013;create-mozilla-plugins" but this may not be necessary<br  /></li>
<li><a id="sec-1-4-28-6-16-8" name="sec-1-4-28-6-16-8"></a>then get a user agent extension to firefox like the "UAControl 0.1.3.1" extension, giving it the user agent for netflix.com "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:15.0) Gecko/20120427 Firefox/15.0a1"<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-8-1" name="sec-1-4-28-6-16-8-1"></a>"chromium &#x2013;user-agent="derp" " doesn't seem to work anymore?<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-16-9" name="sec-1-4-28-6-16-9"></a>AZ prime<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-16-9-1" name="sec-1-4-28-6-16-9-1"></a>is different, uses flash but needs old proprietary stuff from the HAL package, so install `hal` from yaourt and run the script from <a href="https://wiki.archlinux.org/index.php/Flash_DRM_content#Using_the_HAL_package">https://wiki.archlinux.org/index.php/Flash_DRM_content#Using_the_HAL_package</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-17" name="sec-1-4-28-6-17"></a>photo editing<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-17-1" name="sec-1-4-28-6-17-1"></a>the GIMP, obviously, but `mogrify()` (and `convert()`) as part of imagemagick are awesome for commandline photo editing, like rotation of a bunch of files<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-18" name="sec-1-4-28-6-18"></a>peripherals<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-18-1" name="sec-1-4-28-6-18-1"></a>arch ipod<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-18-1-1" name="sec-1-4-28-6-18-1-1"></a><a href="https://wiki.archlinux.org/index.php/IPod#iPod_Classic.2FNano3g">https://wiki.archlinux.org/index.php/IPod#iPod_Classic.2FNano3g</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-18-1-1-1" name="sec-1-4-28-6-18-1-1-1"></a>this worked! you can start by mounting like normal!<br  /></li>
<li><a id="sec-1-4-28-6-18-1-1-2" name="sec-1-4-28-6-18-1-1-2"></a>the only thing is that you need something that can read the database like `gtkpod`<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-18-2" name="sec-1-4-28-6-18-2"></a>compnet printer/printing<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-18-2-1" name="sec-1-4-28-6-18-2-1"></a>install `cups` and `libcups`<br  /></li>
<li><a id="sec-1-4-28-6-18-2-2" name="sec-1-4-28-6-18-2-2"></a>then, enable on boot via systemctl `systemctl enable org.cups.cupsd.service` and start `systemctl start org.cups.cupsd.service` a la <a href="https://bbs.archlinux.org/viewtopic.php?pid=1478928#p1478928">https://bbs.archlinux.org/viewtopic.php?pid=1478928#p1478928</a> (previously, was just "systemctl start cups")<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-18-2-2-1" name="sec-1-4-28-6-18-2-2-1"></a>this is necessary for hp-setup to find the ppd file!<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-18-2-3" name="sec-1-4-28-6-18-2-3"></a>go to `localhost:631` in browser<br  /></li>
<li><a id="sec-1-4-28-6-18-2-4" name="sec-1-4-28-6-18-2-4"></a>install `hplip` that's lip not lib<br  /></li>
<li><a id="sec-1-4-28-6-18-2-5" name="sec-1-4-28-6-18-2-5"></a>run `sudo hp-setup`, probably have to run with -i interactive flag<br  /></li>
<li><a id="sec-1-4-28-6-18-2-6" name="sec-1-4-28-6-18-2-6"></a>try running `hp-doctor` if problems<br  /></li>
<li><a id="sec-1-4-28-6-18-2-7" name="sec-1-4-28-6-18-2-7"></a>this helped! <a href="http://www.muktware.com/2013/04/how-to-install-and-configure-hp-printer-in-arch-linux/4192">http://www.muktware.com/2013/04/how-to-install-and-configure-hp-printer-in-arch-linux/4192</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-19" name="sec-1-4-28-6-19"></a>pictures program<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-19-1" name="sec-1-4-28-6-19-1"></a>use 'geeqie', dev'd fork of dead gqview?<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-20" name="sec-1-4-28-6-20"></a>python<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-20-1" name="sec-1-4-28-6-20-1"></a>even though there are some native python thingies, consider them OS USE ONLY, via deploying ALL python development use using virtualenv! see the philosophy here: <a href="https://hynek.me/articles/virtualenv-lives/">https://hynek.me/articles/virtualenv-lives/</a><br  /></li>
<li><a id="sec-1-4-28-6-20-2" name="sec-1-4-28-6-20-2"></a>anaconda<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-20-2-1" name="sec-1-4-28-6-20-2-1"></a>to make "up arrow" and ctrl-p move up (and down, down) in the history, on Arch at least (bc Arch is using a newer libncurses?), must "conda install ncurses" as well into each environment <a href="https://github.com/ContinuumIO/anaconda-issues/issues/455">https://github.com/ContinuumIO/anaconda-issues/issues/455</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-21" name="sec-1-4-28-6-21"></a>screenshot<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-21-1" name="sec-1-4-28-6-21-1"></a>using imagemagick, which is probably already installed<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-21-1-1" name="sec-1-4-28-6-21-1-1"></a>run `import -window root screenshot.jpg` to save a screenshot to /home/USER<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-21-2" name="sec-1-4-28-6-21-2"></a>sometimes, opening the screenshots in certain image viewers, or the actual screenshot itself, will be screwed up, probably something to do with its headers &#x2013; in that case, basically just run `mogrify -density 90 screenshot.jpg` from <a href="http://tex.stackexchange.com/a/134911">http://tex.stackexchange.com/a/134911</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-22" name="sec-1-4-28-6-22"></a>skype<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-22-1" name="sec-1-4-28-6-22-1"></a>okay, so you're going to need to switch your audio to PulseAudio (which, AFAIK, is headphones/speaker-sensitive and just as good/capable as native sound stuff.)<br  /></li>
<li><a id="sec-1-4-28-6-22-2" name="sec-1-4-28-6-22-2"></a>packages needed to be installed (from pacman):<br  /><div class="outline-text-7" id="text-1-4-28-6-22-2">
<ol class="org-ol">
<li>multilib/skype
</li>
<li>extra/libcanberra-pulse (needed for pavucontrol)
</li>
<li>extra/libpulse (necessary, this'll probably already be installed due to chromium etc.)
</li>
<li>multilib/lib32-libpulse (specifically needed for skype?)
</li>
<li>extra/pavucontrol (maybe unnecessary, but acts as a good `alsamixer` for PulseAudio INCLUDING the fact that it shows the amplitude of the ACTUAL SIGNAL either being output or input, so you can see if you're getting any mic signal)
</li>
<li>extra/pulseaudio (needed for input processing and pavucontrol working correctly, aka it acts as a PulseAudio server?)
</li>
<li>extra/pulseaudio-alsa (optional, equalizes `alsamixer` behavior with the PulseAudio channels)
</li>
</ol>
</div>
</li>

<li><a id="sec-1-4-28-6-22-3" name="sec-1-4-28-6-22-3"></a>another thing: as per Solution 1 at <a href="https://wiki.archlinux.org/index.php/skype#Crackling.2Fnoisy_sound_.28mainly_using_64-bit_OS.29">https://wiki.archlinux.org/index.php/skype#Crackling.2Fnoisy_sound_.28mainly_using_64-bit_OS.29</a> , add `PULSE<sub>LATENCY</sub><sub>MSEC</sub>=60` to the beginning of the `exec&#x2026;` line in `/usr/bin/skype`. This is needed for the horrible crackling quality on both input and output.<br  /></li>
<li><a id="sec-1-4-28-6-22-4" name="sec-1-4-28-6-22-4"></a>lastly, you MAY need to go into either pavucontrol? or at least alsamixer and increase the input capture and Digital channels to nonzero<br  /></li>
<li><a id="sec-1-4-28-6-22-5" name="sec-1-4-28-6-22-5"></a>after this, you may not need to restart X or the computer, but do it anyways just to be sure. It should work at this point.<br  /></li>
<li><a id="sec-1-4-28-6-22-6" name="sec-1-4-28-6-22-6"></a>note: after restarting the computer, you will need to reenable PulseAudio using the simple `pulseaudio &#x2013;start`, after which you can use pavucontrol to control it<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-23" name="sec-1-4-28-6-23"></a>spotify<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-23-1" name="sec-1-4-28-6-23-1"></a>turn off notifications after v1: edit the config file seems to be the only way to work, even if just adding a line <a href="https://bbs.archlinux.org/viewtopic.php?id=206204">https://bbs.archlinux.org/viewtopic.php?id=206204</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-24" name="sec-1-4-28-6-24"></a>sound<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-24-1" name="sec-1-4-28-6-24-1"></a>make sure to switch to PulseAudio using `pulseaudio &#x2013;start` on startup (see the skype section for install)<br  /></li>
<li><a id="sec-1-4-28-6-24-2" name="sec-1-4-28-6-24-2"></a>see skype section for how to setup pulseaudio<br  /></li>
<li><a id="sec-1-4-28-6-24-3" name="sec-1-4-28-6-24-3"></a>audacity doesn't like pulseaudio, use `pulseaudio &#x2013;kill`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-25" name="sec-1-4-28-6-25"></a>steam<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-25-1" name="sec-1-4-28-6-25-1"></a>upon install:<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-25-1-1" name="sec-1-4-28-6-25-1-1"></a>1. install and run like usual, will download crap<br  /></li>
<li><a id="sec-1-4-28-6-25-1-2" name="sec-1-4-28-6-25-1-2"></a>2. alias steam to "STEAM<sub>RUNTIME</sub>=0 steam" <a href="https://wiki.archlinux.org/index.php/steam#Using_native_runtime">https://wiki.archlinux.org/index.php/steam#Using_native_runtime</a><br  /></li>
<li><a id="sec-1-4-28-6-25-1-3" name="sec-1-4-28-6-25-1-3"></a>3. will yell about missing dependencies, which, from link above, you can find by `cd ~/.local/share/Steam/ubuntu12<sub>32</sub> ; LD<sub>LIBRARY</sub><sub>PATH</sub>=".:${LD<sub>LIBRARY</sub><sub>PATH</sub>}" ldd $(file *|sed '<i>ELF</i>!d;s/:.*//g')|grep 'not found'|sort|uniq`<br  /></li>
<li><a id="sec-1-4-28-6-25-1-4" name="sec-1-4-28-6-25-1-4"></a>4. use `pkgfile` to find which packages those specific .so files are from<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-25-2" name="sec-1-4-28-6-25-2"></a>archaic<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-25-2-1" name="sec-1-4-28-6-25-2-1"></a>VERSION<sub>ID</sub>="2015.11.01" in /etc/os-release from <a href="https://wiki.archlinux.org/index.php/Steam/Troubleshooting#VERSION_ID:_unbound_variable">https://wiki.archlinux.org/index.php/Steam/Troubleshooting#VERSION_ID:_unbound_variable</a><br  /></li>
<li><a id="sec-1-4-28-6-25-2-2" name="sec-1-4-28-6-25-2-2"></a>temporarily downgrading to libgcrypt-1.6.5-1 from <a href="https://bugs.archlinux.org/task/48994">https://bugs.archlinux.org/task/48994</a><br  /></li>
<li><a id="sec-1-4-28-6-25-2-3" name="sec-1-4-28-6-25-2-3"></a>steam complains about no opengl direct rendering unless `multilib/lib32-intel-dri` is installed (a la <a href="https://bbs.archlinux.org/viewtopic.php?pid=1432335">https://bbs.archlinux.org/viewtopic.php?pid=1432335</a>) (and also probably `multilib/lib32-mesa-libgl`)<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-26" name="sec-1-4-28-6-26"></a>system, incl X11 settings, package configs (including journal for manual changes to system)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-1" name="sec-1-4-28-6-26-1"></a>getting started<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-1-1" name="sec-1-4-28-6-26-1-1"></a>(unnecessary to actually have an `xorg.conf` in arch, but it's way better to have one)<br  /></li>
<li><a id="sec-1-4-28-6-26-1-2" name="sec-1-4-28-6-26-1-2"></a>make sure you install the `xf86-video-intel` or whatever it is, that's not explicitly mentioned in the arch Beg Guide<br  /></li>
<li><a id="sec-1-4-28-6-26-1-3" name="sec-1-4-28-6-26-1-3"></a>generate a skeleton via running `Xorg :0 -configure`<br  /></li>
<li><a id="sec-1-4-28-6-26-1-4" name="sec-1-4-28-6-26-1-4"></a>then sudo copy the new file `/root/xorg.conf.new` to `/etc/X11/xorg.conf`<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-1-4-1" name="sec-1-4-28-6-26-1-4-1"></a>not necessarily necessary, but do it<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-1-5" name="sec-1-4-28-6-26-1-5"></a>start it with `startx`, which uses `~/.xinitrc`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-2" name="sec-1-4-28-6-26-2"></a>fonts<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-2-1" name="sec-1-4-28-6-26-2-1"></a>(as in, in xterm in X11)<br  /></li>
<li><a id="sec-1-4-28-6-26-2-2" name="sec-1-4-28-6-26-2-2"></a>add the fonts to `/usr/share/fonts/&lt;folder for whichever filetype they are, like TTF&gt;`<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-2-2-1" name="sec-1-4-28-6-26-2-2-1"></a>after this, they should be see/grep-able using `fc-list`, just to make sure<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-2-3" name="sec-1-4-28-6-26-2-3"></a>in `.Xdefaults` or whichever your WM is using, add<br  /><div class="outline-text-8" id="text-1-4-28-6-26-2-3">
<p>
```
XTerm*faceName: PragmataPro:style=Regular
XTerm*faceSize: 10
```
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-28-6-26-3" name="sec-1-4-28-6-26-3"></a>important files for X:<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-3-1" name="sec-1-4-28-6-26-3-1"></a>~/.xinitrc (where you choose your wm)<br  /></li>
<li><a id="sec-1-4-28-6-26-3-2" name="sec-1-4-28-6-26-3-2"></a>~/.Xdefaults<br  /></li>
<li><a id="sec-1-4-28-6-26-3-3" name="sec-1-4-28-6-26-3-3"></a>/etc/X11/xorg.conf<br  /></li>
<li><a id="sec-1-4-28-6-26-3-4" name="sec-1-4-28-6-26-3-4"></a>also see files listed in $lib/bash/rsync<sub>utils</sub>/maint/sync<sub>arch</sub><sub>system</sub><sub>files</sub>.sh<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-4" name="sec-1-4-28-6-26-4"></a>whoa `xdg-open` can be used on terminal or even dmenu with arguments to open in native app<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-4-1" name="sec-1-4-28-6-26-4-1"></a>you use `xdg-mime` to edit default applications<br  /></li>
<li><a id="sec-1-4-28-6-26-4-2" name="sec-1-4-28-6-26-4-2"></a>to open pdfs in firefox, for example, (see `xdg-mime &#x2013;manual`), use `xdg-mime default firefox.desktop application/pdf`<br  /></li>
<li><a id="sec-1-4-28-6-26-4-3" name="sec-1-4-28-6-26-4-3"></a>can maybe edit ~/.local/share/applications/mimeapps.list ? not sure<br  /></li>
<li><a id="sec-1-4-28-6-26-4-4" name="sec-1-4-28-6-26-4-4"></a>can use `mimeopen -d &lt;file&gt;` via xdg-open for interative mime default app selection on CLI! see <a href="https://wiki.archlinux.org/index.php/Xdg-open#perl-file-mimeinfo">https://wiki.archlinux.org/index.php/Xdg-open#perl-file-mimeinfo</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-5" name="sec-1-4-28-6-26-5"></a>`dmesg` gets like the kernel cycle buffer or something? what even is that?<br  /></li>
<li><a id="sec-1-4-28-6-26-6" name="sec-1-4-28-6-26-6"></a>changing keyboard settings using xkboptions a la X11 (archaic)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-6-1" name="sec-1-4-28-6-26-6-1"></a>can change any of these to default via `setxkbmap -option` by itself<br  /></li>
<li><a id="sec-1-4-28-6-26-6-2" name="sec-1-4-28-6-26-6-2"></a>swap capslock and control, like for laptop keyboard, with just `setxkbmap -option "ctrl:swapcaps"`<br  /></li>
<li><a id="sec-1-4-28-6-26-6-3" name="sec-1-4-28-6-26-6-3"></a>swap alt and windows keys, like for home keyboard with just `setxkbmap -option "altwin:swap<sub>alt</sub><sub>win</sub>"`<br  /></li>
<li><a id="sec-1-4-28-6-26-6-4" name="sec-1-4-28-6-26-6-4"></a>so, you may have to start by additionally installing the `evdev` general input (incl. keyboard and mouse) driver, idk<br  /></li>
<li><a id="sec-1-4-28-6-26-6-5" name="sec-1-4-28-6-26-6-5"></a>once done, enabling caps/ctrl swapping on startup is as easy as expressing an XkbOption in `/etc/X11/xorg.conf.d/10-evdev.conf` like<br  /><div class="outline-text-8" id="text-1-4-28-6-26-6-5">
<p>
```
Section "InputClass"
        Identifier "evdev keyboard catchall"
        MatchIsKeyboard "on"
</p>

<p>
        Option "XkbOptions" "ctrl:swapcaps"
        Driver "evdev"
EndSection
```
</p>
</div>
</li>

<li><a id="sec-1-4-28-6-26-6-6" name="sec-1-4-28-6-26-6-6"></a>as of 2014-12-10, have just started using "ctrl:nocaps" instead of messing with swapcaps for X11, and made new keymaps to fix both caps/ctrl switch and alt+arrow (alt+L/R arrows) console switching in non-X11 console via:<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-7" name="sec-1-4-28-6-26-7"></a>swapfile see <a href="https://wiki.archlinux.org/index.php/swap#Swap_file_creation">https://wiki.archlinux.org/index.php/swap#Swap_file_creation</a><br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-7-0-1" name="sec-1-4-28-6-26-7-0-1"></a>this is from <a href="http://www.linux.com/learn/tutorials/769644-hacking-your-linux-keyboard-with-xkb/">http://www.linux.com/learn/tutorials/769644-hacking-your-linux-keyboard-with-xkb/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-8" name="sec-1-4-28-6-26-8"></a>2014-12-03: so apparently running "systemctl mask systemd-udev-settle" will disable that thing which was slowing down boot<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-8-1" name="sec-1-4-28-6-26-8-1"></a>this worked! briefly reading forums say that this settling thing isn't really used or at least is obsolete<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-9" name="sec-1-4-28-6-26-9"></a>visual framework settings (gtk, etc.)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-26-9-1" name="sec-1-4-28-6-26-9-1"></a>qt, affecting konquerer, dolphin, vlc: run `qtconfig-qt4`<br  /></li>
<li><a id="sec-1-4-28-6-26-9-2" name="sec-1-4-28-6-26-9-2"></a>some others? `gtk-chtheme`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-26-10" name="sec-1-4-28-6-26-10"></a>apparently config files for lots of installed pacman packages are in "/usr/share/&lt;program&gt;/stuff.conf"<br  /></li>
<li><a id="sec-1-4-28-6-26-11" name="sec-1-4-28-6-26-11"></a>CLI X11 display scripting `DISPLAY=:0.0 .screenlayout/laptop.sh`<br  /></li>
<li><a id="sec-1-4-28-6-26-12" name="sec-1-4-28-6-26-12"></a>`xprop` run through terminal allows you to click on a program running in X11 and see its properties?<br  /></li>
<li><a id="sec-1-4-28-6-26-13" name="sec-1-4-28-6-26-13"></a>use `xev` to find keycodes<br  /></li>
<li><a id="sec-1-4-28-6-26-14" name="sec-1-4-28-6-26-14"></a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-27" name="sec-1-4-28-6-27"></a>lrn-thinkpad-specific<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-27-1" name="sec-1-4-28-6-27-1"></a><a href="https://wiki.archlinux.org/index.php/Thinkpad_T450s">https://wiki.archlinux.org/index.php/Thinkpad_T450s</a><br  /></li>
<li><a id="sec-1-4-28-6-27-2" name="sec-1-4-28-6-27-2"></a>thinkpad wireless notes<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-27-2-1" name="sec-1-4-28-6-27-2-1"></a>after uninstalling all netctl, networkmanager, wpa stuff, etc. etc.<br  /></li>
<li><a id="sec-1-4-28-6-27-2-2" name="sec-1-4-28-6-27-2-2"></a>just doing `ip link set wlp3s0 up` gives `ipv6: addrconf(netdev<sub>up</sub>): wlp3s0: link is not ready`, though doing `ip link` seems to suggest it is up after all<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-27-3" name="sec-1-4-28-6-27-3"></a>apparently `tp<sub>smapi`</sub> doesn't work for newer processors like mine <a href="http://www.thinkwiki.org/wiki/Tp_smapi">http://www.thinkwiki.org/wiki/Tp_smapi</a> suggests to use thinkpad<sub>acpi</sub> instead<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-28" name="sec-1-4-28-6-28"></a>time<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-28-1" name="sec-1-4-28-6-28-1"></a>change timezone by `timedatectl set-timezone america/new<sub>york`</sub> or america/chicago etc.<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-29" name="sec-1-4-28-6-29"></a>trackpad<br  /><div class="outline-text-6" id="text-1-4-28-6-29">
<ol class="org-ol">
<li>dl "mtrack" driver
</li>
<li>add either the section or just the preferences here to /etc/x11/xorg.conf:
```
### aes: some of these settings are new/nondefault, and this entire section might be as well
section "inputclass"
        matchistouchpad "on"
        identifier      "touchpads"
        option "thumbsize" "50"
        option "scrolldistance" "80"
        option "sensitivity" "0.5"
        option "fingerhigh" "9"
        driver          "mtrack"
endsection
```
</li>
</ol>
</div>

<ol class="org-ol"><li><a id="sec-1-4-28-6-29-1" name="sec-1-4-28-6-29-1"></a>as of 2014<sub>07</sub><sub>30</sub>, new update to xorg-server 1.16, having that stuff in the `xorg.conf` was sufficient to completely disable the trackpad!<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-29-1-1" name="sec-1-4-28-6-29-1-1"></a>however, deleting then reinstalling the mtrack driver through yaourt and adding in 10-mtrack.conf to xorg.conf.d didn't have any effects<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-29-2" name="sec-1-4-28-6-29-2"></a>so adding these settings into 10-mtrack.conf makes it seem like they're working!<br  /></li>
<li><a id="sec-1-4-28-6-29-3" name="sec-1-4-28-6-29-3"></a>ugh so on 2014-08-21, seemingly upgraded xorg, andt disabled touchpad, though it was an easy fix since `/etc/x11/xorg.conf.d/50-synaptics.conf` suddenly was demoted to just a backup with `.pacsave`. by copying the pacsave to the file's name before, it now works! ugh, i don't want to have to do this every time!<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-30" name="sec-1-4-28-6-30"></a>urxvt<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-30-1" name="sec-1-4-28-6-30-1"></a>transparency in xmonad through compositing<br  /><div class="outline-text-7" id="text-1-4-28-6-30-1">
<ol class="org-ol">
<li>enable composite in /etc/x11/xorg.conf through
```
section "extensions"
        option "composite" "enable"
endsection
```
</li>
<li>dl prog `xcompmgr`, and in your `~/.xinitrc`, put (maybe needs to be before exec monad) `xcompmgr -c &amp;`
</li>
<li>if want background picture, program `feh` seems to work better than program `xloadimage`
</li>
</ol>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-28-6-31" name="sec-1-4-28-6-31"></a>vnc<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-31-1" name="sec-1-4-28-6-31-1"></a>apparently i'm using `vncviewer` which is really `aur/tigervnc-viewer` but may come with default vnc package?<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-32" name="sec-1-4-28-6-32"></a>webcam<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-32-1" name="sec-1-4-28-6-32-1"></a>package 'isight-firmware-tools' or something like it from aur, and then reboot of computer, seems to fix nonfunctioning webcam on air<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-33" name="sec-1-4-28-6-33"></a>window managers<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-33-1" name="sec-1-4-28-6-33-1"></a>i3 when using in kde<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-33-1-1" name="sec-1-4-28-6-33-1-1"></a><a href="https://faq.i3wm.org/question/2939/i3wm-and-kde-together/">https://faq.i3wm.org/question/2939/i3wm-and-kde-together/</a> (kde sys settings) and <a href="http://stackoverflow.com/a/21617087">http://stackoverflow.com/a/21617087</a> (environment vbl) for 2 diffferent methods<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-33-2" name="sec-1-4-28-6-33-2"></a>xmobar and xmonad<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-33-2-1" name="sec-1-4-28-6-33-2-1"></a>maybe better than pacman to just do clean cabal-install of xmonad and xmonad-contrib?<br  /></li>
<li><a id="sec-1-4-28-6-33-2-2" name="sec-1-4-28-6-33-2-2"></a>so, necessary and sufficient to use these by installing via pacman `xmonad`, `xmobar`, and `xmonad-contrib` (the latter are important for customization of xmonad.hs)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-33-2-2-1" name="sec-1-4-28-6-33-2-2-1"></a>you may also need to use the cabal builder to build the `xmonad` and `xmobar` programs<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-33-2-3" name="sec-1-4-28-6-33-2-3"></a>the xmonad mod4 key bug was solved upon exiting spotify for some reason<br  /></li>
<li><a id="sec-1-4-28-6-33-2-4" name="sec-1-4-28-6-33-2-4"></a><a href="http://thinkingeek.com/2011/11/21/simple-guide-configure-xmonad-dzen2-conky/">http://thinkingeek.com/2011/11/21/simple-guide-configure-xmonad-dzen2-conky/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-6-34" name="sec-1-4-28-6-34"></a>wireless (broadcom 43224)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-1" name="sec-1-4-28-6-34-1"></a>NetworkManager<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-1-1" name="sec-1-4-28-6-34-1-1"></a>to save wifi passwords, go to 'nm-connection-editor', right click on people next to password and "store password for all users"<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-34-2" name="sec-1-4-28-6-34-2"></a>bu / general wpa wireless support<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-2-1" name="sec-1-4-28-6-34-2-1"></a>use `wpa<sub>supplicant</sub>.conf` example in `z wpa<sub>supplicant`</sub> entry in the db<br  /><div class="outline-text-8" id="text-1-4-28-6-34-2-1">
<p>
```
fast<sub>reauth</sub>=0
network={
ssid="bu (802.1x)"
priority=15
key<sub>mgmt</sub>=wpa-eap
eap=peap mschapv2
identity="user"
password="derp"
phase2="auth=mschapv2"
}
```
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-4-28-6-34-3" name="sec-1-4-28-6-34-3"></a>autoswitch<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-3-1" name="sec-1-4-28-6-34-3-1"></a>need `wpa<sub>actiond`</sub> for wireless switching and `ifplugd` for wired switching, as per <a href="https://wiki.archlinux.org/index.php/netctl#automatic_operation">https://wiki.archlinux.org/index.php/netctl#automatic_operation</a><br  /></li>
<li><a id="sec-1-4-28-6-34-3-2" name="sec-1-4-28-6-34-3-2"></a>you then add auto daemons via `netctl-ifplugd@&lt;interface&gt;.service` for wired and `netctl-auto@&lt;interface&gt;.service` for wireless<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-34-4" name="sec-1-4-28-6-34-4"></a>troubleshooting wireless network<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-4-1" name="sec-1-4-28-6-34-4-1"></a>first set up the interface with `sudo ip link set wlp2s0 up`<br  /></li>
<li><a id="sec-1-4-28-6-34-4-2" name="sec-1-4-28-6-34-4-2"></a>then do the handshake via `sudo wpa<sub>supplicant</sub> -b -dwext -iwlp2s0 -c/etc/wpa<sub>supplicant</sub>/wpa<sub>supplicant</sub>.conf`<br  /></li>
<li><a id="sec-1-4-28-6-34-4-3" name="sec-1-4-28-6-34-4-3"></a>then get a dhcp lease via `sudo dhcpcd wlp2s0`<br  /></li>
<li><a id="sec-1-4-28-6-34-4-4" name="sec-1-4-28-6-34-4-4"></a>finally, ping to test `ping -c 2 www.google.com`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-34-5" name="sec-1-4-28-6-34-5"></a>oh my god, don't even get me started. <a href="http://andym3.wordpress.com/projects/the-broadcom-wireless-card-guide/">http://andym3.wordpress.com/projects/the-broadcom-wireless-card-guide/</a><br  /></li>
<li><a id="sec-1-4-28-6-34-6" name="sec-1-4-28-6-34-6"></a>as of 2014<sub>06</sub><sub>01</sub>, now i need to load module `brcmsmac` with `modprobe brcmsmac` after booting in order to load the wireless interface, after which everything is peachy<br  /></li>
<li><a id="sec-1-4-28-6-34-7" name="sec-1-4-28-6-34-7"></a>as of 2014<sub>06</sub><sub>19</sub>, everything is back in order, the normal interface wlp2s0 loads on boot, and it works.<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-7-1" name="sec-1-4-28-6-34-7-1"></a>the issue was, while something did go wrong a while back, i def made things worse by blacklisting pretty much all available broadcom wireless drivers in `/usr/lib/modprobe/broadcom-wl.conf`<br  /></li>
<li><a id="sec-1-4-28-6-34-7-2" name="sec-1-4-28-6-34-7-2"></a>the proper place to blacklist things, as per <a href="https://wiki.archlinux.org/index.php/kernel_modules#blacklisting">https://wiki.archlinux.org/index.php/kernel_modules#blacklisting</a> , is in a `/etc/modprobe.d/&lt;modprobe|blacklist&gt;.conf` file where you just put an entry for `blacklist &lt;module name&gt;`<br  /></li>
<li><a id="sec-1-4-28-6-34-7-3" name="sec-1-4-28-6-34-7-3"></a>as per looking at the actual module being used by the hardware, `lspci -vnn | grep -7 14e4` tells us that now, the `bcma` module is the one being used<br  /><ol class="org-ol"><li><a id="sec-1-4-28-6-34-7-3-1" name="sec-1-4-28-6-34-7-3-1"></a>this is good, since this appears to be the default one, as it's one of the few that are already loaded in the kernel.<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-34-7-4" name="sec-1-4-28-6-34-7-4"></a>so in other words, if it breaks again, do another `lspci&#x2026;` to see if bcma is not being used, etc. note that `brcmsmac` relies on `bcma`, which apparently can still be loaded if blacklisted if you do `sudo modprobe brcmsmac`<br  /></li>
<li><a id="sec-1-4-28-6-34-7-5" name="sec-1-4-28-6-34-7-5"></a>you can see the status of some? modules via `lsmod`, and you can see where all the modules are loaded from via `mkinitcpio -v | less`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-6-34-8" name="sec-1-4-28-6-34-8"></a>as of 2014<sub>07</sub><sub>29</sub>, there was a kernel upgrade and now broadcom-wl module doesn't appear to work, so had to modprobe brcmsmac to get working again. since wl automatically blacklists brcmsmac, i uninstalled wl from yaourt, and upon reboot brcmsmac starts automatically and works. so will delay getting broadcom-wl for a while. wow i actually knew what to do at this point.<br  /></li>
<li><a id="sec-1-4-28-6-34-9" name="sec-1-4-28-6-34-9"></a>seems you need to manually reenable/etc netctl profiles via `sudo netctl enable/start/reenable wlp2s0-derp` before you can enable them in netctl-auto<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-7" name="sec-1-4-28-7"></a>lrn-debian documentation<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-1" name="sec-1-4-28-7-1"></a>mime / xdg-open types<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-1-1" name="sec-1-4-28-7-1-1"></a>use `mimeopen -d &lt;file&gt;.&lt;filetype&gt; to cli-set which specific program you want to use for that filetype<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-7-2" name="sec-1-4-28-7-2"></a>networkmanager wifi<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-2-1" name="sec-1-4-28-7-2-1"></a>nmcli - one cli client built in<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-2-1-1" name="sec-1-4-28-7-2-1-1"></a>commands<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-2-1-1-1" name="sec-1-4-28-7-2-1-1-1"></a>to show list of wifi networks do `nmcli dev wifi list`<br  /></li>
<li><a id="sec-1-4-28-7-2-1-1-2" name="sec-1-4-28-7-2-1-1-2"></a>to add a network, do `nmcli dev wifi connect &lt;ssid&gt;`<br  /></li>
<li><a id="sec-1-4-28-7-2-1-1-3" name="sec-1-4-28-7-2-1-1-3"></a>to connect if already have a connection, can do `nmcli con up id &lt;connection id`<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-7-2-1-2" name="sec-1-4-28-7-2-1-2"></a>notes<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-2-1-2-1" name="sec-1-4-28-7-2-1-2-1"></a>i guess it treats wifi as a generic device?<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-7-3" name="sec-1-4-28-7-3"></a>r<br  /><ol class="org-ol"><li><a id="sec-1-4-28-7-3-1" name="sec-1-4-28-7-3-1"></a><a href="http://cran.us.r-project.org/bin/linux/debian/">http://cran.us.r-project.org/bin/linux/debian/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-7-4" name="sec-1-4-28-7-4"></a>troubleshooting X11 screen flickering (in both gnome and kde):<br  /><div class="outline-text-6" id="text-1-4-28-7-4">
<p>
according to the combination of the options from <a href="https://askubuntu.com/a/963059">https://askubuntu.com/a/963059</a> but in the file placement from <a href="https://wiki.archlinux.org/index.php/intel_graphics#Xorg_configuration">https://wiki.archlinux.org/index.php/intel_graphics#Xorg_configuration</a> , need to put the below in either the file '/usr/share/X11/xorg.conf.d/20-intel.conf' or '/etc/X11/xorg.conf.d/20-intel.conf'
</p>

<p>
Section "Device"
   Identifier  "Intel Graphics"
   Driver      "intel"
   Option     "AccelMethod"  "uxa"
EndSection  
</p>
</div>
</li></ol>
</li>
<li><a id="sec-1-4-28-8" name="sec-1-4-28-8"></a>lrn-kernel<br  /><ol class="org-ol"><li><a id="sec-1-4-28-8-1" name="sec-1-4-28-8-1"></a><a href="http://kernelnewbies.org/kernel">http://kernelnewbies.org/kernel</a><br  /></li>
<li><a id="sec-1-4-28-8-2" name="sec-1-4-28-8-2"></a><a href="http://www.reddit.com/r/linux/comments/2corc0/just_in_case_hes_a_reddit_troll/cjhmc7k">http://www.reddit.com/r/linux/comments/2corc0/just_in_case_hes_a_reddit_troll/cjhmc7k</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-9" name="sec-1-4-28-9"></a>lrn-wayland<br  /><ol class="org-ol"><li><a id="sec-1-4-28-9-1" name="sec-1-4-28-9-1"></a><a href="http://hdante.wordpress.com/2014/07/08/the-hello-wayland-tutorial/">http://hdante.wordpress.com/2014/07/08/the-hello-wayland-tutorial/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-10" name="sec-1-4-28-10"></a>lrn-windows (ugh)<br  /><ol class="org-ol"><li><a id="sec-1-4-28-10-1" name="sec-1-4-28-10-1"></a>xbox 360 controller receiver<br  /><ol class="org-ol"><li><a id="sec-1-4-28-10-1-1" name="sec-1-4-28-10-1-1"></a><a href="http://www.nikingstore.com/blog/tutorial-on-how-to-install-the-driver-for-a-generic-xbox-360-wireless-receiver-on-windows7/">http://www.nikingstore.com/blog/tutorial-on-how-to-install-the-driver-for-a-generic-xbox-360-wireless-receiver-on-windows7/</a><br  /></li>
<li><a id="sec-1-4-28-10-1-2" name="sec-1-4-28-10-1-2"></a>if xbro controller on pc not working, disable driver for "Human Interface Devices &gt; HID-compliant game controller" driver that pops up when controller is connected<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-10-2" name="sec-1-4-28-10-2"></a>tronscript <a href="https://www.reddit.com/r/talesfromtechsupport/comments/40ch6u/reccomended_by_millions_of_people/cyt3eqy">https://www.reddit.com/r/talesfromtechsupport/comments/40ch6u/reccomended_by_millions_of_people/cyt3eqy</a><br  /></li>
<li><a id="sec-1-4-28-10-3" name="sec-1-4-28-10-3"></a>windows activation<br  /><ol class="org-ol"><li><a id="sec-1-4-28-10-3-1" name="sec-1-4-28-10-3-1"></a>under system: Product ID: 00326-10000-00000-AA730<br  /></li>
<li><a id="sec-1-4-28-10-3-2" name="sec-1-4-28-10-3-2"></a>under activation: "Windows 10 on this device is activated with a digital entitlement"<br  /></li></ol>
</li>
<li><a id="sec-1-4-28-10-4" name="sec-1-4-28-10-4"></a>free windows OS downloads <a href="https://www.reddit.com/r/windows/comments/4jwlel/how_to_download_all_windows_isos_from_microsoft/">https://www.reddit.com/r/windows/comments/4jwlel/how_to_download_all_windows_isos_from_microsoft/</a> <a href="https://www.microsoft.com/en-us/software-download/techbench">https://www.microsoft.com/en-us/software-download/techbench</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-11" name="sec-1-4-28-11"></a>magic sysrq key <a href="https://en.wikipedia.org/wiki/magic_sysrq_key">https://en.wikipedia.org/wiki/magic_sysrq_key</a><br  /></li>
<li><a id="sec-1-4-28-12" name="sec-1-4-28-12"></a>awk sed <a href="http://www.theunixschool.com/p/awk-sed.html">http://www.theunixschool.com/p/awk-sed.html</a><br  /></li>
<li><a id="sec-1-4-28-13" name="sec-1-4-28-13"></a>lrn-make and other tools like autotools<br  /><ol class="org-ol"><li><a id="sec-1-4-28-13-1" name="sec-1-4-28-13-1"></a>what does make -j 4 do really?<br  /></li>
<li><a id="sec-1-4-28-13-2" name="sec-1-4-28-13-2"></a><a href="http://hn.premii.com/#/comments/11006006">Introduction to the Autotools (autoconf, automake, and libtool)</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-14" name="sec-1-4-28-14"></a>filesystem<br  /><ol class="org-ol"><li><a id="sec-1-4-28-14-1" name="sec-1-4-28-14-1"></a>file managers <a href="http://www.softpanorama.org/ofm/index.shtml">http://www.softpanorama.org/ofm/index.shtml</a><br  /></li>
<li><a id="sec-1-4-28-14-2" name="sec-1-4-28-14-2"></a>linux filesystem hierarchy standard <a href="http://refspecs.linuxfoundation.org/fhs_2.3/fhs-2.3.html">http://refspecs.linuxfoundation.org/fhs_2.3/fhs-2.3.html</a><br  /></li>
<li><a id="sec-1-4-28-14-3" name="sec-1-4-28-14-3"></a>sshfs <a href="https://library.linode.com/networking/ssh-filesystems#sph_using-sshfs-with-linux">https://library.linode.com/networking/ssh-filesystems#sph_using-sshfs-with-linux</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-15" name="sec-1-4-28-15"></a>security<br  /><ol class="org-ol"><li><a id="sec-1-4-28-15-1" name="sec-1-4-28-15-1"></a><a href="http://spenserj.com/blog/2013/07/15/securing-a-linux-server/">http://spenserj.com/blog/2013/07/15/securing-a-linux-server/</a><br  /></li>
<li><a id="sec-1-4-28-15-2" name="sec-1-4-28-15-2"></a><a href="https://wiki.archlinux.org/index.php/security">https://wiki.archlinux.org/index.php/security</a><br  /></li>
<li><a id="sec-1-4-28-15-3" name="sec-1-4-28-15-3"></a><a href="http://daeken.com/2013-03-17_so_you_want_to_be_a_breaker__pt__1__web_security.html">http://daeken.com/2013-03-17_so_you_want_to_be_a_breaker__pt__1__web_security.html</a><br  /></li>
<li><a id="sec-1-4-28-15-4" name="sec-1-4-28-15-4"></a><a href="http://blog.sanctum.geek.nz/linux-crypto-introduction/">http://blog.sanctum.geek.nz/linux-crypto-introduction/</a><br  /></li>
<li><a id="sec-1-4-28-15-5" name="sec-1-4-28-15-5"></a>ssh best practices <a href="http://hn.premii.com/#/comments/11052745">http://hn.premii.com/#/comments/11052745</a> <a href="https://blog.0xbadc0de.be/archives/300">https://blog.0xbadc0de.be/archives/300</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-16" name="sec-1-4-28-16"></a>tutorials<br  /><ol class="org-ol"><li><a id="sec-1-4-28-16-1" name="sec-1-4-28-16-1"></a><a href="http://www.tummy.com/articles/index.html">http://www.tummy.com/articles/index.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-28-17" name="sec-1-4-28-17"></a>terminal<br  /><ol class="org-ol"><li><a id="sec-1-4-28-17-1" name="sec-1-4-28-17-1"></a>urxvt<br  /><ol class="org-ol"><li><a id="sec-1-4-28-17-1-1" name="sec-1-4-28-17-1-1"></a><a href="https://sergeemond.com/en/article/rxvt-unicode-on-os-x/">https://sergeemond.com/en/article/rxvt-unicode-on-os-x/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-28-18" name="sec-1-4-28-18"></a>chroot <a href="http://www.unixwiz.net/techtips/chroot-practices.html">http://www.unixwiz.net/techtips/chroot-practices.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-29" class="outline-4">
<h4 id="sec-1-4-29"><span class="section-number-4">1.4.29</span> lrn-low-level-programming</h4>
<div class="outline-text-4" id="text-1-4-29">
</div><ol class="org-ol"><li><a id="sec-1-4-29-1" name="sec-1-4-29-1"></a><a href="https://github.com/gurugio/lowlevelprogramming-university">https://github.com/gurugio/lowlevelprogramming-university</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-30" class="outline-4">
<h4 id="sec-1-4-30"><span class="section-number-4">1.4.30</span> lrn-nginx</h4>
<div class="outline-text-4" id="text-1-4-30">
</div><ol class="org-ol"><li><a id="sec-1-4-30-1" name="sec-1-4-30-1"></a><a href="http://blog.zachorr.com/nginx-setup/">http://blog.zachorr.com/nginx-setup/</a><br  /></li>
<li><a id="sec-1-4-30-2" name="sec-1-4-30-2"></a><a href="http://carrot.is/coding/nginx_introduction">http://carrot.is/coding/nginx_introduction</a><br  /></li>
<li><a id="sec-1-4-30-3" name="sec-1-4-30-3"></a>archaic nginx notes<br  /><div class="outline-text-5" id="text-1-4-30-3">
<ul class="org-ul">
<li>old Kewl filez on it:
/var/log/nginx/error.log
/var/log/nginx/access.log
/etc/nginx/sites-enabled/www
/etc/init.d/nginx
</li>
<li>HTML locations:
<ul class="org-ul">
<li>On Mac:
<ul class="org-ul">
<li>` /opt/local/share/nginx/html `
</li>
</ul>
</li>
<li>On Linux: (probably)
<ul class="org-ul">
<li>` /usr/share/nginx/html `
</li>
</ul>
</li>
</ul>
</li>

<li>config locations:
<ul class="org-ul">
<li>for nginx.conf, mime.types:
<ul class="org-ul">
<li>On Mac:
<ul class="org-ul">
<li>` /opt/local/etc/nginx `
</li>
</ul>
</li>
<li>On Linux: (probably)
<ul class="org-ul">
<li>` <i>etc/nginx</i> `
</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li>Instructions from <a href="http://mwholt.blogspot.com/2012/09/installing-nginx-php-mysql-on-mac-os-x.html">http://mwholt.blogspot.com/2012/09/installing-nginx-php-mysql-on-mac-os-x.html</a>
</li>
</ul>
<p>
```
Run sudo port install nginx to install nginx. Twiddle thumbs&#x2026; and at the end of the install, you'll be shown a command that causes it to run at system start: sudo port load nginx.
</p>

<p>
Configure nginx. Start by setting the default config files:
</p>

<p>
    cd /opt/local/etc/nginx
    sudo cp nginx.conf.default nginx.conf
    sudo cp mime.types.default mime.types
    sudo nginx -s reload
    Load <a href="http://localhost">http://localhost</a> in your browser to see that it's working. You're now done installing nginx.
```
</p>
</div>
</li></ol>
</div>

<div id="outline-container-sec-1-4-31" class="outline-4">
<h4 id="sec-1-4-31"><span class="section-number-4">1.4.31</span> lrn-organizational software</h4>
<div class="outline-text-4" id="text-1-4-31">
</div><ol class="org-ol"><li><a id="sec-1-4-31-1" name="sec-1-4-31-1"></a>org-mode beats everything. I'm not sure there's any feature that org-mode doesn't already have or has as a plugin<br  /></li>
<li><a id="sec-1-4-31-2" name="sec-1-4-31-2"></a>good overall thread <a href="https://www.reddit.com/r/vim/comments/1fxd60/vim_as_notetakingorganization_software_anyone/">https://www.reddit.com/r/vim/comments/1fxd60/vim_as_notetakingorganization_software_anyone/</a><br  /></li>
<li><a id="sec-1-4-31-3" name="sec-1-4-31-3"></a>(good) todo.txt via <a href="https://github.com/freitass/todo.txt-vim">https://github.com/freitass/todo.txt-vim</a> and <a href="http://todotxt.com/">http://todotxt.com/</a><br  /><ol class="org-ol"><li><a id="sec-1-4-31-3-1" name="sec-1-4-31-3-1"></a>emacs<br  /><ol class="org-ol"><li><a id="sec-1-4-31-3-1-1" name="sec-1-4-31-3-1-1"></a><a href="https://github.com/rpdillon/todotxt.el">https://github.com/rpdillon/todotxt.el</a><br  /></li>
<li><a id="sec-1-4-31-3-1-2" name="sec-1-4-31-3-1-2"></a><a href="https://github.com/avillafiorita/todotxt-mode">https://github.com/avillafiorita/todotxt-mode</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-31-4" name="sec-1-4-31-4"></a>(good) taskwarrior CLI <a href="https://www.reddit.com/r/vim/comments/3na8sr/vim_todo_list_equivalent_or_should_i_use/">https://www.reddit.com/r/vim/comments/3na8sr/vim_todo_list_equivalent_or_should_i_use/</a><br  /></li>
<li><a id="sec-1-4-31-5" name="sec-1-4-31-5"></a>(good) vimwiki <a href="https://github.com/vimwiki/vimwiki">https://github.com/vimwiki/vimwiki</a><br  /></li>
<li><a id="sec-1-4-31-6" name="sec-1-4-31-6"></a>(meh/okay) vim-pad  <a href="https://github.com/fmoralesc/vim-pad">https://github.com/fmoralesc/vim-pad</a> see <a href="https://www.reddit.com/r/vim/comments/2r24nm/note_taking_using_vim_and_pandocs/cnby5no">https://www.reddit.com/r/vim/comments/2r24nm/note_taking_using_vim_and_pandocs/cnby5no</a><br  /></li>
<li><a id="sec-1-4-31-7" name="sec-1-4-31-7"></a>(meh) vim-notes <a href="https://github.com/xolox/vim-notes">https://github.com/xolox/vim-notes</a><br  /></li>
<li><a id="sec-1-4-31-8" name="sec-1-4-31-8"></a>(meh) vimoutliner (no longer maintained?) <a href="https://github.com/vimoutliner/vimoutliner">https://github.com/vimoutliner/vimoutliner</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-32" class="outline-4">
<h4 id="sec-1-4-32"><span class="section-number-4">1.4.32</span> lrn-pandoc-lrn-markdown-lrn-plaintext-writing</h4>
<div class="outline-text-4" id="text-1-4-32">
</div><ol class="org-ol"><li><a id="sec-1-4-32-1" name="sec-1-4-32-1"></a><a href="http://kieranhealy.org/blog/archives/2014/01/23/plain-text/">http://kieranhealy.org/blog/archives/2014/01/23/plain-text/</a><br  /></li>
<li><a id="sec-1-4-32-2" name="sec-1-4-32-2"></a><a href="http://jeromyanglim.blogspot.com/2012/07/beamer-pandoc-markdown.html">http://jeromyanglim.blogspot.com/2012/07/beamer-pandoc-markdown.html</a><br  /></li>
<li><a id="sec-1-4-32-3" name="sec-1-4-32-3"></a><a href="https://news.ycombinator.com/item?id=10271028">https://news.ycombinator.com/item?id=10271028</a><br  /></li>
<li><a id="sec-1-4-32-4" name="sec-1-4-32-4"></a><a href="http://wcm1.web.rice.edu/plain-text-citations.html">http://wcm1.web.rice.edu/plain-text-citations.html</a><br  /></li>
<li><a id="sec-1-4-32-5" name="sec-1-4-32-5"></a><a href="http://third-bit.com/2013/06/13/problems-with-pandoc.html">http://third-bit.com/2013/06/13/problems-with-pandoc.html</a><br  /></li>
<li><a id="sec-1-4-32-6" name="sec-1-4-32-6"></a>good guide from start to finish <a href="http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown">http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown</a><br  /></li>
<li><a id="sec-1-4-32-7" name="sec-1-4-32-7"></a>getting reveal.js or other weird formats to work<br  /><ol class="org-ol"><li><a id="sec-1-4-32-7-1" name="sec-1-4-32-7-1"></a>download source code into "Default user data directory", e.g. '~/.pandoc'<br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-33" class="outline-4">
<h4 id="sec-1-4-33"><span class="section-number-4">1.4.33</span> lrn-privacy-lrn-security</h4>
<div class="outline-text-4" id="text-1-4-33">
</div><ol class="org-ol"><li><a id="sec-1-4-33-1" name="sec-1-4-33-1"></a>lrn-vpn's<br  /><ol class="org-ol"><li><a id="sec-1-4-33-1-1" name="sec-1-4-33-1-1"></a><a href="https://thatoneprivacysite.net/">https://thatoneprivacysite.net/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-33-2" name="sec-1-4-33-2"></a><a href="https://medium.com/@kappklot/things-to-know-about-web-security-before-trumps-inauguration-a-harm-reductionist-guide-c365a5ddbcb8#.s6nqky8lv">https://medium.com/@kappklot/things-to-know-about-web-security-before-trumps-inauguration-a-harm-reductionist-guide-c365a5ddbcb8#.s6nqky8lv</a><br  /></li>
<li><a id="sec-1-4-33-3" name="sec-1-4-33-3"></a><a href="https://securityinabox.org/en/guide/mobile-phones">https://securityinabox.org/en/guide/mobile-phones</a><br  /></li>
<li><a id="sec-1-4-33-4" name="sec-1-4-33-4"></a><a href="https://crashoverridenetwork.tumblr.com/post/114270394687/so-youve-been-doxed-a-guide-to-best-practices">https://crashoverridenetwork.tumblr.com/post/114270394687/so-youve-been-doxed-a-guide-to-best-practices</a><br  /></li>
<li><a id="sec-1-4-33-5" name="sec-1-4-33-5"></a>&gt; All uploaded images and the extracted text are deleted immediately<br  /><div class="outline-text-5" id="text-1-4-33-5">
<p>
Until they are served with a subpoena for a particular client, or a sweeping subpoena to store everything forever, or the company is sold and the new parent has different values, or the company decides to mine customer data for advertising uses, or there's a bug in the software, or there's a long-lived cache of the data, or it gets into their backups accidentally or deliberately, or they don't keep the data but keep "just" the meta-data, or they do statistics or analytics before deleting the data, or they are hacked, or they simply change their minds.
</p>

<p>
In terms of privacy, even a non-free non-open-source local app with DRM or license management is better than a server app with a "strict privacy policy". With a good firewall setup, you can be pretty sure that the local app won't betray you.
</p>
</div>
</li>

<li><a id="sec-1-4-33-6" name="sec-1-4-33-6"></a>From reading hn comments on gnu ring, p2p messaging, hard part with p2p is speed and retaining identity and history across multiple devices, which is only solved by 1. Manually transferring keys or 2. Id server (but in that case it's not p2p!)<br  /><ol class="org-ol"><li><a id="sec-1-4-33-6-1" name="sec-1-4-33-6-1"></a>Thus, decentralized/distributed like matrix might be best compromise of usability and redundancy<br  /></li>
<li><a id="sec-1-4-33-6-2" name="sec-1-4-33-6-2"></a><img src="https://a.doko.moe/ubvuak.png" alt="ubvuak.png" /><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-34" class="outline-4">
<h4 id="sec-1-4-34"><span class="section-number-4">1.4.34</span> lrn-prog-practices</h4>
<div class="outline-text-4" id="text-1-4-34">
</div><ol class="org-ol"><li><a id="sec-1-4-34-1" name="sec-1-4-34-1"></a>data ETL<br  /></li>
<li><a id="sec-1-4-34-2" name="sec-1-4-34-2"></a><a href="http://samizdat.mines.edu/howto/howtobeaprogrammer.html">http://samizdat.mines.edu/howto/howtobeaprogrammer.html</a><br  /></li>
<li><a id="sec-1-4-34-3" name="sec-1-4-34-3"></a><a href="https://github.com/webpro/programming-principles">https://github.com/webpro/programming-principles</a><br  /></li>
<li><a id="sec-1-4-34-4" name="sec-1-4-34-4"></a><a href="http://mixmastamyk.bitbucket.org/pro_soft_dev/">http://mixmastamyk.bitbucket.org/pro_soft_dev/</a><br  /></li>
<li><a id="sec-1-4-34-5" name="sec-1-4-34-5"></a>"draw, discuss, explain. then iterate/repeat"<br  /></li>
<li><a id="sec-1-4-34-6" name="sec-1-4-34-6"></a>notes from greg wilson talk on what we know about sw dev <a href="https://vimeo.com/9270320">https://vimeo.com/9270320</a><br  /><ol class="org-ol"><li><a id="sec-1-4-34-6-1" name="sec-1-4-34-6-1"></a>(woodfield 1979) 25% incr in reqr complexity =&gt; 100% incr in soln complexity<br  /><ol class="org-ol"><li><a id="sec-1-4-34-6-1-1" name="sec-1-4-34-6-1-1"></a>this also means you should cut down on reqr<br  /></li></ol>
</li>
<li><a id="sec-1-4-34-6-2" name="sec-1-4-34-6-2"></a>(van genuchten 1991) two biggest causes of project failure are<br  /><ol class="org-ol"><li><a id="sec-1-4-34-6-2-1" name="sec-1-4-34-6-2-1"></a>1. poor estimation<br  /></li>
<li><a id="sec-1-4-34-6-2-2" name="sec-1-4-34-6-2-2"></a>2. unstable requirements<br  /></li></ol>
</li>
<li><a id="sec-1-4-34-6-3" name="sec-1-4-34-6-3"></a>(thomas 1997) if more than 20-25% of a component needs revision, it's better to rewrite it from scratch<br  /></li></ol>
</li>
<li><a id="sec-1-4-34-7" name="sec-1-4-34-7"></a>lrn-licensing<br  /><ol class="org-ol"><li><a id="sec-1-4-34-7-1" name="sec-1-4-34-7-1"></a>gpl 2 v 3 <a href="http://www.groklaw.net/article.php?story=20060118155841115">http://www.groklaw.net/article.php?story=20060118155841115</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-4-35" class="outline-4">
<h4 id="sec-1-4-35"><span class="section-number-4">1.4.35</span> lrn-regex (regular expressions)</h4>
<div class="outline-text-4" id="text-1-4-35">
</div><ol class="org-ol"><li><a id="sec-1-4-35-1" name="sec-1-4-35-1"></a><a href="http://www.regexr.com/">http://www.regexr.com/</a><br  /></li>
<li><a id="sec-1-4-35-2" name="sec-1-4-35-2"></a>read book!<br  /></li>
<li><a id="sec-1-4-35-3" name="sec-1-4-35-3"></a>take notes on <a href="http://nikic.github.io/2012/06/15/the-true-power-of-regular-expressions.html">http://nikic.github.io/2012/06/15/the-true-power-of-regular-expressions.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-36" class="outline-4">
<h4 id="sec-1-4-36"><span class="section-number-4">1.4.36</span> lrn-scientific-programming</h4>
<div class="outline-text-4" id="text-1-4-36">
</div><ol class="org-ol"><li><a id="sec-1-4-36-1" name="sec-1-4-36-1"></a>add simulation filesystem org to coding practices (use as an exercise to revisit it)<br  /><ol class="org-ol"><li><a id="sec-1-4-36-1-1" name="sec-1-4-36-1-1"></a>see what solutions are already published, poll people, etc.<br  /></li></ol>
</li>
<li><a id="sec-1-4-36-2" name="sec-1-4-36-2"></a>read misha's good practices wiki for tips<br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-37" class="outline-4">
<h4 id="sec-1-4-37"><span class="section-number-4">1.4.37</span> lrn-testing-lrn-unit-testing</h4>
<div class="outline-text-4" id="text-1-4-37">
</div><ol class="org-ol"><li><a id="sec-1-4-37-1" name="sec-1-4-37-1"></a>learn unit testing <a href="http://www.developingthefuture.net/writing-high-quality-unit-tests-tutorial/">http://www.developingthefuture.net/writing-high-quality-unit-tests-tutorial/</a><br  /></li>
<li><a id="sec-1-4-37-2" name="sec-1-4-37-2"></a>xunit <a href="http://en.wikipedia.org/wiki/xunit">http://en.wikipedia.org/wiki/xunit</a><br  /></li>
<li><a id="sec-1-4-37-3" name="sec-1-4-37-3"></a>GitHub's Scientist <a href="http://githubengineering.com/scientist/">http://githubengineering.com/scientist/</a><br  /></li>
<li><a id="sec-1-4-37-4" name="sec-1-4-37-4"></a><a href="https://www.reddit.com/r/programming/comments/50uxvs/testing_for_people_who_hate_testing/">https://www.reddit.com/r/programming/comments/50uxvs/testing_for_people_who_hate_testing/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-38" class="outline-4">
<h4 id="sec-1-4-38"><span class="section-number-4">1.4.38</span> lrn-tex-lrn-latex</h4>
<div class="outline-text-4" id="text-1-4-38">
</div><ol class="org-ol"><li><a id="sec-1-4-38-1" name="sec-1-4-38-1"></a>emacs as the ultimate latex editor <a href="http://hn.premii.com/#/comments/8777565][emacs">http://hn.premii.com/#/comments/8777565][emacs</a> as the ultimate latex editor]]<br  /></li>
<li><a id="sec-1-4-38-2" name="sec-1-4-38-2"></a><a href="http://www.tug.dk/FontCatalogue/">http://www.tug.dk/FontCatalogue/</a><br  /></li>
<li><a id="sec-1-4-38-3" name="sec-1-4-38-3"></a>latex for professional journal things<br  /><ol class="org-ol"><li><a id="sec-1-4-38-3-1" name="sec-1-4-38-3-1"></a><a href="http://www.latex-community.org/know-how/latex/51-latex-math-science/280-formatting-latex-articles-for-biology-journals">http://www.latex-community.org/know-how/latex/51-latex-math-science/280-formatting-latex-articles-for-biology-journals</a><br  /></li>
<li><a id="sec-1-4-38-3-2" name="sec-1-4-38-3-2"></a>bibtex<br  /><ol class="org-ol"><li><a id="sec-1-4-38-3-2-1" name="sec-1-4-38-3-2-1"></a><a href="http://phdtools.blogspot.com/2011/07/making-bibtex-file-from-folder-of-pdf.html?m=1">http://phdtools.blogspot.com/2011/07/making-bibtex-file-from-folder-of-pdf.html?m=1</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-4-38-4" name="sec-1-4-38-4"></a>shane latex for making new commands<br  /><div class="outline-text-5" id="text-1-4-38-4">
<p>
\newcommand{\creds}[1]{
  \(^{\mathrm{#1}}\)
}
</p>

<p>
\creds{a, b}
</p>
</div>
</li>

<li><a id="sec-1-4-38-5" name="sec-1-4-38-5"></a>chris latex for programming logic into latex<br  /><div class="outline-text-5" id="text-1-4-38-5">
<p>
% color in table entries where p-value &lt; 0.05
\usepackage{xstring}
\usepackage{collcell,array,xcolor}
\newcommand{\formatcolentry}[1]{%
\ifdecimal{#1}%
{\ifdimless{#1pt}{.05pt}%
{\textcolor{red}{\textbf{#1}}}%
{\textcolor{black}{#1}}}%
{#1}%
}
</p>

<p>
\newcolumntype{h}{&gt;{\collectcell\formatcolentry}r&lt;{\endcollectcell}}
</p>
</div>
</li>

<li><a id="sec-1-4-38-6" name="sec-1-4-38-6"></a>how to install new latex classes, under texlive on *nix:<br  /><div class="outline-text-5" id="text-1-4-38-6">
<ol class="org-ol">
<li>if have class file e.g. 'pnastwo.cls', put it in '$home/texmf/tex/latex/pnastwo' like in the above link
</li>
<li>then run 'texhash ~/texmf' to index/whatever it (like mentioned in <a href="http://tex.stackexchange.com/a/130082">http://tex.stackexchange.com/a/130082</a>), then you should be done! and can call the the class in tex across your filesystem
</li>
</ol>
</div>

<ol class="org-ol"><li><a id="sec-1-4-38-6-1" name="sec-1-4-38-6-1"></a>deploying new stylesheet: just put `#+latex<sub>class</sub>: pnastwo` at the top of the doc, and will automatically make it look much prettier (including smaller font)<br  /></li>
<li><a id="sec-1-4-38-6-2" name="sec-1-4-38-6-2"></a><a href="https://www.math.hmc.edu/computing/support/tex/installing/">https://www.math.hmc.edu/computing/support/tex/installing/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-38-7" name="sec-1-4-38-7"></a>latex for resumes / cvs<br  /><ol class="org-ol"><li><a id="sec-1-4-38-7-1" name="sec-1-4-38-7-1"></a><a href="https://www.toofishes.net/blog/why-i-do-my-resume-latex/">https://www.toofishes.net/blog/why-i-do-my-resume-latex/</a><br  /></li>
<li><a id="sec-1-4-38-7-2" name="sec-1-4-38-7-2"></a><a href="http://hn.premii.com/#/article/10787608">Hack your Resume</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-38-8" name="sec-1-4-38-8"></a>lrn-beamer<br  /><ol class="org-ol"><li><a id="sec-1-4-38-8-1" name="sec-1-4-38-8-1"></a>dark theme <a href="http://paralleltransport.blogspot.com/2012/04/dark-theme-for-beamer.html">http://paralleltransport.blogspot.com/2012/04/dark-theme-for-beamer.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-38-9" name="sec-1-4-38-9"></a>lrn-bibtex<br  /><ol class="org-ol"><li><a id="sec-1-4-38-9-1" name="sec-1-4-38-9-1"></a>and natbib <a href="http://en.wikibooks.org/wiki/latex/bibliography_management#natbib">http://en.wikibooks.org/wiki/latex/bibliography_management#natbib</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-38-10" name="sec-1-4-38-10"></a>resources<br  /><ol class="org-ol"><li><a id="sec-1-4-38-10-1" name="sec-1-4-38-10-1"></a><a href="http://mrzool.cc/tex-boilerplates/">http://mrzool.cc/tex-boilerplates/</a><br  /></li></ol>
</li>
<li><a id="sec-1-4-38-11" name="sec-1-4-38-11"></a>"modern tex" and xelatex and luatex <a href="https://news.ycombinator.com/item?id=13990798">https://news.ycombinator.com/item?id=13990798</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-39" class="outline-4">
<h4 id="sec-1-4-39"><span class="section-number-4">1.4.39</span> lrn-wasm-lrn-webassembly</h4>
<div class="outline-text-4" id="text-1-4-39">
</div><ol class="org-ol"><li><a id="sec-1-4-39-1" name="sec-1-4-39-1"></a><a href="https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/">https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/</a><br  /></li>
<li><a id="sec-1-4-39-2" name="sec-1-4-39-2"></a>if WASM is just a new form of binaries and blobs and things revert to the 90s, then openness will come to rely on reverse engineering binaries etc prob, right? esp since you're not going to get more efficient than binaries<br  /></li></ol>
</div>
<div id="outline-container-sec-1-4-40" class="outline-4">
<h4 id="sec-1-4-40"><span class="section-number-4">1.4.40</span> lrn-xml</h4>
<div class="outline-text-4" id="text-1-4-40">
</div><ol class="org-ol"><li><a id="sec-1-4-40-1" name="sec-1-4-40-1"></a>learn xpath, apparently a good way to go through xml<br  /></li>
<li><a id="sec-1-4-40-2" name="sec-1-4-40-2"></a>emacs also has nxml-mode, which is supposed to be good<br  /></li>
<li><a id="sec-1-4-40-3" name="sec-1-4-40-3"></a><a href="https://en.wikipedia.org/wiki/Comparison_of_XML_editors">https://en.wikipedia.org/wiki/Comparison_of_XML_editors</a><br  /></li>
<li><a id="sec-1-4-40-4" name="sec-1-4-40-4"></a>stackoverflow says, if you really need industrial usage of XML like in a corporate environment, open tools just don't cut it<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-5" class="outline-3">
<h3 id="sec-1-5"><span class="section-number-3">1.5</span> lrn-cycling&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_cycling">lrn_cycling</span></span></h3>
<div class="outline-text-3" id="text-1-5">
</div><div id="outline-container-sec-1-5-1" class="outline-4">
<h4 id="sec-1-5-1"><span class="section-number-4">1.5.1</span> road bikes to check out</h4>
<div class="outline-text-4" id="text-1-5-1">
</div><ol class="org-ol"><li><a id="sec-1-5-1-1" name="sec-1-5-1-1"></a>peugeout, fuji, panasonic (sp) old?, raleigh is okay but not for speed bikes, bianci, trek, vilano shimano?<br  /></li>
<li><a id="sec-1-5-1-2" name="sec-1-5-1-2"></a>vilano shimano looks good<br  /></li>
<li><a id="sec-1-5-1-3" name="sec-1-5-1-3"></a><a href="http://www.hyperionauctions.co.uk/catalogue.html">http://www.hyperionauctions.co.uk/catalogue.html</a><br  /></li>
<li><a id="sec-1-5-1-4" name="sec-1-5-1-4"></a>Hub Bicycle shop woman named emily says $6-700 is a good price for a good road bike<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-6" class="outline-3">
<h3 id="sec-1-6"><span class="section-number-3">1.6</span> lrn-design</h3>
<div class="outline-text-3" id="text-1-6">
</div><div id="outline-container-sec-1-6-1" class="outline-4">
<h4 id="sec-1-6-1"><span class="section-number-4">1.6.1</span> core principles for design could just be sufficiently complicated that it's difficult to think of good counterexamples</h4>
</div>
<div id="outline-container-sec-1-6-2" class="outline-4">
<h4 id="sec-1-6-2"><span class="section-number-4">1.6.2</span> see kim's list of good websites</h4>
<div class="outline-text-4" id="text-1-6-2">
</div><ol class="org-ol"><li><a id="sec-1-6-2-1" name="sec-1-6-2-1"></a>precedents<br  /><ol class="org-ol"><li><a id="sec-1-6-2-1-1" name="sec-1-6-2-1-1"></a><a href="http://softlabnyc.com/">http://softlabnyc.com/</a><br  /></li>
<li><a id="sec-1-6-2-1-2" name="sec-1-6-2-1-2"></a><a href="http://www.herzogdemeuron.com/index.html">http://www.herzogdemeuron.com/index.html</a><br  /></li>
<li><a id="sec-1-6-2-1-3" name="sec-1-6-2-1-3"></a><a href="http://lesailes.hermes.com/us/en/">http://lesailes.hermes.com/us/en/</a> (very similar idea, i think)<br  /></li>
<li><a id="sec-1-6-2-1-4" name="sec-1-6-2-1-4"></a><a href="http://www.janeriksvendsen.no/">http://www.janeriksvendsen.no/</a><br  /></li>
<li><a id="sec-1-6-2-1-5" name="sec-1-6-2-1-5"></a><a href="http://spacecollective.org/recent">http://spacecollective.org/recent</a><br  /></li>
<li><a id="sec-1-6-2-1-6" name="sec-1-6-2-1-6"></a><a href="http://www.spacedepartment.de/">http://www.spacedepartment.de/</a><br  /></li>
<li><a id="sec-1-6-2-1-7" name="sec-1-6-2-1-7"></a><a href="http://blog.bleed.com/">http://blog.bleed.com/</a><br  /></li>
<li><a id="sec-1-6-2-1-8" name="sec-1-6-2-1-8"></a><a href="http://www.ala.uk.com/portfolio/">http://www.ala.uk.com/portfolio/</a> (nothing special, but an example of a horizontal website)<br  /></li>
<li><a id="sec-1-6-2-1-9" name="sec-1-6-2-1-9"></a><a href="http://www.big.dk/#projects">http://www.big.dk/#projects</a><br  /></li>
<li><a id="sec-1-6-2-1-10" name="sec-1-6-2-1-10"></a><a href="http://shop.acnestudios.com/">http://shop.acnestudios.com/</a> (split screen)<br  /></li>
<li><a id="sec-1-6-2-1-11" name="sec-1-6-2-1-11"></a><a href="http://www.makearchitects.com/#/projects/">http://www.makearchitects.com/#/projects/</a> (smaller format of gridded display of work)<br  /></li>
<li><a id="sec-1-6-2-1-12" name="sec-1-6-2-1-12"></a><a href="http://koko3.fi/">http://koko3.fi/</a> (nice in conveying materiality, tangibility of the works)<br  /></li>
<li><a id="sec-1-6-2-1-13" name="sec-1-6-2-1-13"></a><a href="http://www.maisonmartinmargiela.com/">http://www.maisonmartinmargiela.com/</a> (windows format)<br  /></li>
<li><a id="sec-1-6-2-1-14" name="sec-1-6-2-1-14"></a><a href="http://lineto.com/">http://lineto.com/</a> (?)<br  /></li>
<li><a id="sec-1-6-2-1-15" name="sec-1-6-2-1-15"></a><a href="http://www.inventorymagazine.com/">http://www.inventorymagazine.com/</a> (simplicity with nice images)<br  /></li>
<li><a id="sec-1-6-2-1-16" name="sec-1-6-2-1-16"></a><a href="http://www.formuswithlove.se/">http://www.formuswithlove.se/</a> (nice obvious transition between split screens)<br  /></li>
<li><a id="sec-1-6-2-1-17" name="sec-1-6-2-1-17"></a><a href="http://sagmeister.com/welcome">http://sagmeister.com/welcome</a> (interesting)<br  /></li></ol>
</li>
<li><a id="sec-1-6-2-2" name="sec-1-6-2-2"></a>fonts | elements<br  /><ol class="org-ol"><li><a id="sec-1-6-2-2-1" name="sec-1-6-2-2-1"></a><a href="http://www.tomsachs.org/">http://www.tomsachs.org/</a> (text)<br  /></li>
<li><a id="sec-1-6-2-2-2" name="sec-1-6-2-2-2"></a><a href="http://www.comme-des-garcons.com/reneburri1207.html">http://www.comme-des-garcons.com/reneburri1207.html</a> (image transition)<br  /></li>
<li><a id="sec-1-6-2-2-3" name="sec-1-6-2-2-3"></a><a href="http://lineto.com/">http://lineto.com/</a> (index bar is real nice)<br  /></li>
<li><a id="sec-1-6-2-2-4" name="sec-1-6-2-2-4"></a><a href="http://musevery.com/site/">http://musevery.com/site/</a> (nice contour drawings and text together)<br  /></li>
<li><a id="sec-1-6-2-2-5" name="sec-1-6-2-2-5"></a><a href="http://www.asuivre-creations.fr/index.html">http://www.asuivre-creations.fr/index.html</a> (nice highlighting element)<br  /></li>
<li><a id="sec-1-6-2-2-6" name="sec-1-6-2-2-6"></a><a href="http://www.bleed.no/">http://www.bleed.no/</a> (nice noise background on index)<br  /></li>
<li><a id="sec-1-6-2-2-7" name="sec-1-6-2-2-7"></a><a href="http://www.marni-anticamera.com/03">http://www.marni-anticamera.com/03</a> (continuous, long image to convey space)<br  /></li>
<li><a id="sec-1-6-2-2-8" name="sec-1-6-2-2-8"></a><a href="http://www.pho-ku.com/">http://www.pho-ku.com/</a> (typing of content)<br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-6-3" class="outline-4">
<h4 id="sec-1-6-3"><span class="section-number-4">1.6.3</span> go through hack design website</h4>
</div>
<div id="outline-container-sec-1-6-4" class="outline-4">
<h4 id="sec-1-6-4"><span class="section-number-4">1.6.4</span> crap way to improve usability <a href="http://www.userfocus.co.uk/articles/a_crap_way_to_improve_usability.html#content">http://www.userfocus.co.uk/articles/a_crap_way_to_improve_usability.html#content</a></h4>
</div>
<div id="outline-container-sec-1-6-5" class="outline-4">
<h4 id="sec-1-6-5"><span class="section-number-4">1.6.5</span> <a href="https://news.ycombinator.com/item?id=8085385">proposal for an interactive introduction to graphics programming</a></h4>
</div>
<div id="outline-container-sec-1-6-6" class="outline-4">
<h4 id="sec-1-6-6"><span class="section-number-4">1.6.6</span> minimalist websites <a href="https://news.ycombinator.com/item?id=11517491">https://news.ycombinator.com/item?id=11517491</a></h4>
</div>
<div id="outline-container-sec-1-6-7" class="outline-4">
<h4 id="sec-1-6-7"><span class="section-number-4">1.6.7</span> <a href="http://otakugangsta.com/">http://otakugangsta.com/</a></h4>
</div>
<div id="outline-container-sec-1-6-8" class="outline-4">
<h4 id="sec-1-6-8"><span class="section-number-4">1.6.8</span> lrn-data-visualization</h4>
<div class="outline-text-4" id="text-1-6-8">
</div><ol class="org-ol"><li><a id="sec-1-6-8-1" name="sec-1-6-8-1"></a><a href="https://research.googleblog.com/2016/12/open-sourcing-embedding-projector-tool.html">https://research.googleblog.com/2016/12/open-sourcing-embedding-projector-tool.html</a><br  /></li>
<li><a id="sec-1-6-8-2" name="sec-1-6-8-2"></a>colorization<br  /><ol class="org-ol"><li><a id="sec-1-6-8-2-1" name="sec-1-6-8-2-1"></a>gamma error in picture scaling <a href="http://www.4p8.com/eric.brasseur/gamma.html">http://www.4p8.com/eric.brasseur/gamma.html</a><br  /></li>
<li><a id="sec-1-6-8-2-2" name="sec-1-6-8-2-2"></a><a href="http://newcoder.io/dataviz/intro/">http://newcoder.io/dataviz/intro/</a><br  /></li>
<li><a id="sec-1-6-8-2-3" name="sec-1-6-8-2-3"></a>visxn - take notes on : why should engineers and scientists be worried about color? <a href="http://researchweb.watson.ibm.com/people/l/lloydt/color/color.HTM">http://researchweb.watson.ibm.com/people/l/lloydt/color/color.HTM</a><br  /></li>
<li><a id="sec-1-6-8-2-4" name="sec-1-6-8-2-4"></a><a href="http://tools.medialab.sciences-po.fr/iwanthue/">http://tools.medialab.sciences-po.fr/iwanthue/</a><br  /></li>
<li><a id="sec-1-6-8-2-5" name="sec-1-6-8-2-5"></a><a href="http://jfly.iam.u-tokyo.ac.jp/color/index.html">Color Universal Design (CUD) / Colorblind Barrier Free</a><br  /></li>
<li><a id="sec-1-6-8-2-6" name="sec-1-6-8-2-6"></a>colorization of classification images <a href="http://hn.premii.com/#/comments/11605586">http://hn.premii.com/#/comments/11605586</a><br  /></li></ol>
</li>
<li><a id="sec-1-6-8-3" name="sec-1-6-8-3"></a><a href="http://hn.premii.com/#/comments/11432644">A Simple Web Developer's Guide to Color</a><br  /></li>
<li><a id="sec-1-6-8-4" name="sec-1-6-8-4"></a>Spatial information design lab at Columbia<br  /></li>
<li><a id="sec-1-6-8-5" name="sec-1-6-8-5"></a>coloring figures and colorblindness <a href="http://jfly.iam.u-tokyo.ac.jp/color/index.html">http://jfly.iam.u-tokyo.ac.jp/color/index.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-6-9" class="outline-4">
<h4 id="sec-1-6-9"><span class="section-number-4">1.6.9</span> lrn-fonts</h4>
<div class="outline-text-4" id="text-1-6-9">
</div><ol class="org-ol"><li><a id="sec-1-6-9-1" name="sec-1-6-9-1"></a><a href="http://input.fontbureau.com/">http://input.fontbureau.com/</a><br  /></li>
<li><a id="sec-1-6-9-2" name="sec-1-6-9-2"></a>general system for fonts for programming <a href="http://input.fontbureau.com/info/">http://input.fontbureau.com/info/</a><br  /></li>
<li><a id="sec-1-6-9-3" name="sec-1-6-9-3"></a><a href="http://hn.premii.com/#/comments/11465799">Why you hate Comic Sans</a><br  /></li>
<li><a id="sec-1-6-9-4" name="sec-1-6-9-4"></a><a href="https://github.com/be5invis/Iosevka/releases/tag/v1.12.5">https://github.com/be5invis/Iosevka/releases/tag/v1.12.5</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-7" class="outline-3">
<h3 id="sec-1-7"><span class="section-number-3">1.7</span> lrn-diy</h3>
<div class="outline-text-3" id="text-1-7">
</div><div id="outline-container-sec-1-7-1" class="outline-4">
<h4 id="sec-1-7-1"><span class="section-number-4">1.7.1</span> lrn-book-binding</h4>
<div class="outline-text-4" id="text-1-7-1">
</div><ol class="org-ol"><li><a id="sec-1-7-1-1" name="sec-1-7-1-1"></a><a href="https://www.reddit.com/r/bookbinding">https://www.reddit.com/r/bookbinding</a><br  /></li>
<li><a id="sec-1-7-1-2" name="sec-1-7-1-2"></a><a href="https://news.ycombinator.com/item?id=15876260">https://news.ycombinator.com/item?id=15876260</a><br  /></li>
<li><a id="sec-1-7-1-3" name="sec-1-7-1-3"></a><a href="http://homepage.divms.uiowa.edu/~jones/book/">http://homepage.divms.uiowa.edu/~jones/book/</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-8" class="outline-3">
<h3 id="sec-1-8"><span class="section-number-3">1.8</span> lrn-economics-lrn-finance&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_economics">lrn_economics</span>&#xa0;<span class="lrn_finance">lrn_finance</span></span></h3>
<div class="outline-text-3" id="text-1-8">
</div><div id="outline-container-sec-1-8-1" class="outline-4">
<h4 id="sec-1-8-1"><span class="section-number-4">1.8.1</span> lrn-computational-finance</h4>
<div class="outline-text-4" id="text-1-8-1">
</div><ol class="org-ol"><li><a id="sec-1-8-1-1" name="sec-1-8-1-1"></a>downloading history data <a href="https://www.reddit.com/r/algotrading/comments/46vzhv/you_can_download_historical_data_from_ib_using/">https://www.reddit.com/r/algotrading/comments/46vzhv/you_can_download_historical_data_from_ib_using/</a><br  /></li>
<li><a id="sec-1-8-1-2" name="sec-1-8-1-2"></a>blotter interface <a href="https://www.interactivebrokers.com/en/software/tws/usersguidebook/specializedorderentry/understand_the_blotter_interface.htm">https://www.interactivebrokers.com/en/software/tws/usersguidebook/specializedorderentry/understand_the_blotter_interface.htm</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-8-2" class="outline-4">
<h4 id="sec-1-8-2"><span class="section-number-4">1.8.2</span> lrn-credit</h4>
<div class="outline-text-4" id="text-1-8-2">
</div><ol class="org-ol"><li><a id="sec-1-8-2-1" name="sec-1-8-2-1"></a><a href="http://www.reddit.com/r/personalfinance/comments/2jnvbf/remember_that_annualcreditreportcom_is_the_only/][remember">http://www.reddit.com/r/personalfinance/comments/2jnvbf/remember_that_annualcreditreportcom_is_the_only/][remember</a> that annualcreditreport.com is the only authorized site for your free u.s. credit report as mandated by the ftc]]<br  /></li></ol>
</div>
<div id="outline-container-sec-1-8-3" class="outline-4">
<h4 id="sec-1-8-3"><span class="section-number-4">1.8.3</span> lrn-investing</h4>
<div class="outline-text-4" id="text-1-8-3">
</div><ol class="org-ol"><li><a id="sec-1-8-3-1" name="sec-1-8-3-1"></a><a href="https://investor.vanguard.com/mutual-funds/lifestrategy/#/">https://investor.vanguard.com/mutual-funds/lifestrategy/#/</a><br  /></li>
<li><a id="sec-1-8-3-2" name="sec-1-8-3-2"></a>lrn-bb-brian's recommendations<br  /><ol class="org-ol"><li><a id="sec-1-8-3-2-1" name="sec-1-8-3-2-1"></a>basically, vanguard roth IRA into the VFIFX fund &#x2013; actually maybe VFFVX to target 2055 retirement<br  /></li>
<li><a id="sec-1-8-3-2-2" name="sec-1-8-3-2-2"></a>brian-recommended financial metrics <a href="http://www.macroaxis.com/invest/market/visvx--compareprofile--uscax">http://www.macroaxis.com/invest/market/visvx--compareprofile--uscax</a><br  /></li>
<li><a id="sec-1-8-3-2-3" name="sec-1-8-3-2-3"></a>bstout brian recommends 'futureadvisor'<br  /></li>
<li><a id="sec-1-8-3-2-4" name="sec-1-8-3-2-4"></a>bb finance says $10,000 into roth ira through vanguard<br  /><ol class="org-ol"><li><a id="sec-1-8-3-2-4-1" name="sec-1-8-3-2-4-1"></a>says start in vfifx (3k min)<br  /></li>
<li><a id="sec-1-8-3-2-4-2" name="sec-1-8-3-2-4-2"></a>once 12k, split into indiv mutual funds<br  /></li>
<li><a id="sec-1-8-3-2-4-3" name="sec-1-8-3-2-4-3"></a>now is good time to buy 20150911 esp intl<br  /></li>
<li><a id="sec-1-8-3-2-4-4" name="sec-1-8-3-2-4-4"></a>definitely don't put in more than max, or withdraw (obvi)<br  /></li>
<li><a id="sec-1-8-3-2-4-5" name="sec-1-8-3-2-4-5"></a>if more, "invest in a vanguard taxable accoutn", "something like vsivx, since doesn't pay much in dividends, and is therefore tax efficient" - "just builds equity which you don't get taxed on until later, and laxed at lt cap gains, which is much more favourable"<br  /></li></ol>
</li>
<li><a id="sec-1-8-3-2-5" name="sec-1-8-3-2-5"></a>more<br  /><ol class="org-ol"><li><a id="sec-1-8-3-2-5-1" name="sec-1-8-3-2-5-1"></a>firstly, find low fee mutual fund company in planning on 2040/50 retirement via roth ira and roth 401k<br  /></li>
<li><a id="sec-1-8-3-2-5-2" name="sec-1-8-3-2-5-2"></a>max out roth ira (or roth 401k if so chosen) ($5500/yr) <b><b>first</b></b>, super important in 20s<br  /></li>
<li><a id="sec-1-8-3-2-5-3" name="sec-1-8-3-2-5-3"></a>then do vanguard "small cap value fund" and "total stock market index fund" ticket visvx, vtsax<br  /></li>
<li><a id="sec-1-8-3-2-5-4" name="sec-1-8-3-2-5-4"></a>then open tax deferred life insurance policy<br  /></li>
<li><a id="sec-1-8-3-2-5-5" name="sec-1-8-3-2-5-5"></a>then don't take out until not in high income bracket<br  /></li>
<li><a id="sec-1-8-3-2-5-6" name="sec-1-8-3-2-5-6"></a>after that, it's up to you, including "vanguard/peer-to-peer lending/equity"<br  /></li></ol>
</li>
<li><a id="sec-1-8-3-2-6" name="sec-1-8-3-2-6"></a>20160125 convo<br  /><div class="outline-text-6" id="text-1-8-3-2-6">
<p>
Re advisors:  vanguard and fidelity is fine, but only if you have a balance large enough to get free advice, no commission (salaried), and recommend only vanguard funds which are cheap
Hmm, PDF&#x2026;no, but I use roboinvesting software to optimize portfolio weights
Future Adviser
Analysizes finances in all current online accounts, balances based on goals, and provides top 3 inexpensive and close beta index funds that meet target
Pretty easy, and totally free (if you act on advice yourself rather than them buying/selling)
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-8-3-3" name="sec-1-8-3-3"></a><a href="https://www.reddit.com/r/personalfinance/comments/3y6zix/no_401k_at_work_do_i_have_investment_options/">No 401(k) at work, do I have investment options besides Roth IRA?</a><br  /></li>
<li><a id="sec-1-8-3-4" name="sec-1-8-3-4"></a>software<br  /><ol class="org-ol"><li><a id="sec-1-8-3-4-1" name="sec-1-8-3-4-1"></a><a href="https://www.reddit.com/r/personalfinance/comments/3z851u/mint_vs_personal_capital_vs_etc_2016_edition/">Mint vs personal Capital vs Etc: 2016 edition</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-8-4" class="outline-4">
<h4 id="sec-1-8-4"><span class="section-number-4">1.8.4</span> lrn-personal-finance</h4>
<div class="outline-text-4" id="text-1-8-4">
</div><ol class="org-ol"><li><a id="sec-1-8-4-1" name="sec-1-8-4-1"></a>id breach <a href="http://www.secnav.navy.mil/opmbreachdon/pages/default.aspx">http://www.secnav.navy.mil/opmbreachdon/pages/default.aspx</a><br  /><ol class="org-ol"><li><a id="sec-1-8-4-1-1" name="sec-1-8-4-1-1"></a>This is the authoritative source for all OPM breach info and should provide FAQs and all resources one might need to determine if you're affected and are eligible for the identity/credit protection<br  /></li></ol>
</li>
<li><a id="sec-1-8-4-2" name="sec-1-8-4-2"></a><a href="https://www.reddit.com/r/personalfinance/comments/4rcqbu/ive_simulated_and_plotted_the_entire_sp_since/">https://www.reddit.com/r/personalfinance/comments/4rcqbu/ive_simulated_and_plotted_the_entire_sp_since/</a><br  /></li>
<li><a id="sec-1-8-4-3" name="sec-1-8-4-3"></a><a href="https://www.reddit.com/r/personalfinance/comments/4sf15k/this_guy_has_made_an_amazing_to_me_anyway/">https://www.reddit.com/r/personalfinance/comments/4sf15k/this_guy_has_made_an_amazing_to_me_anyway/</a><br  /></li>
<li><a id="sec-1-8-4-4" name="sec-1-8-4-4"></a>buy an annuity when retiring? what even is that?<br  /></li></ol>
</div>
<div id="outline-container-sec-1-8-5" class="outline-4">
<h4 id="sec-1-8-5"><span class="section-number-4">1.8.5</span> lrn-ledger</h4>
<div class="outline-text-4" id="text-1-8-5">
</div><ol class="org-ol"><li><a id="sec-1-8-5-1" name="sec-1-8-5-1"></a><a href="https://www.petekeen.net/a-robust-reporting-system-for-ledger">https://www.petekeen.net/a-robust-reporting-system-for-ledger</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-8-6" class="outline-4">
<h4 id="sec-1-8-6"><span class="section-number-4">1.8.6</span> ask salim about that as an intro book, or maybe ap econ?</h4>
</div>
<div id="outline-container-sec-1-8-7" class="outline-4">
<h4 id="sec-1-8-7"><span class="section-number-4">1.8.7</span> revenue maybe prop to "buying power", which inv prop to rate (a la actuary guy), for which of course premium is calc from</h4>
</div>
<div id="outline-container-sec-1-8-8" class="outline-4">
<h4 id="sec-1-8-8"><span class="section-number-4">1.8.8</span> tightwads and purchasing pain as prop to income and expenses. how to get data on what these are for most people? could match with good accuracy to address alone?</h4>
</div>
<div id="outline-container-sec-1-8-9" class="outline-4">
<h4 id="sec-1-8-9"><span class="section-number-4">1.8.9</span> read law stuff on the shell-eni nigerian. malabu deal, in the british high court and another in arbitration?</h4>
</div>
<div id="outline-container-sec-1-8-10" class="outline-4">
<h4 id="sec-1-8-10"><span class="section-number-4">1.8.10</span> global witness ngo, tom wayne, maybe discusses docs</h4>
</div>
<div id="outline-container-sec-1-8-11" class="outline-4">
<h4 id="sec-1-8-11"><span class="section-number-4">1.8.11</span> <a href="http://blog.alexmaccaw.com/an-engineers-guide-to-stock-options">http://blog.alexmaccaw.com/an-engineers-guide-to-stock-options</a></h4>
</div>
<div id="outline-container-sec-1-8-12" class="outline-4">
<h4 id="sec-1-8-12"><span class="section-number-4">1.8.12</span> <a href="http://core-econ.org/">http://core-econ.org/</a></h4>
</div>
<div id="outline-container-sec-1-8-13" class="outline-4">
<h4 id="sec-1-8-13"><span class="section-number-4">1.8.13</span> keep read mankiw (while questioning assumptions, or at least tracking them)</h4>
</div>
<div id="outline-container-sec-1-8-14" class="outline-4">
<h4 id="sec-1-8-14"><span class="section-number-4">1.8.14</span> <a href="https://en.wikipedia.org/wiki/porter_five_forces_analysis">https://en.wikipedia.org/wiki/porter_five_forces_analysis</a></h4>
</div>
<div id="outline-container-sec-1-8-15" class="outline-4">
<h4 id="sec-1-8-15"><span class="section-number-4">1.8.15</span> <a href="http://ericsink.com/bos/Finance_for_Geeks.html">http://ericsink.com/bos/Finance_for_Geeks.html</a></h4>
</div>
<div id="outline-container-sec-1-8-16" class="outline-4">
<h4 id="sec-1-8-16"><span class="section-number-4">1.8.16</span> best books to learn econ <a href="https://www.reddit.com/r/AskSocialScience/comments/p0ali/can_anybody_recommend_a_good_unbiased_book_on_the/">https://www.reddit.com/r/AskSocialScience/comments/p0ali/can_anybody_recommend_a_good_unbiased_book_on_the/</a></h4>
</div>
<div id="outline-container-sec-1-8-17" class="outline-4">
<h4 id="sec-1-8-17"><span class="section-number-4">1.8.17</span> side money</h4>
<div class="outline-text-4" id="text-1-8-17">
</div><ol class="org-ol"><li><a id="sec-1-8-17-1" name="sec-1-8-17-1"></a><a href="http://www.reddit.com/r/personalfinance/comments/2mn6ap/full_time_student_what_are_some_ways_to_work_from/">http://www.reddit.com/r/personalfinance/comments/2mn6ap/full_time_student_what_are_some_ways_to_work_from/</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-9" class="outline-3">
<h3 id="sec-1-9"><span class="section-number-3">1.9</span> lrn-electrical-computer-engineering</h3>
<div class="outline-text-3" id="text-1-9">
</div><div id="outline-container-sec-1-9-1" class="outline-4">
<h4 id="sec-1-9-1"><span class="section-number-4">1.9.1</span> (1 hr) read signals and systems section 8.7 for fm and instant freq for fun</h4>
</div>
<div id="outline-container-sec-1-9-2" class="outline-4">
<h4 id="sec-1-9-2"><span class="section-number-4">1.9.2</span> arduino/raspberry pi</h4>
<div class="outline-text-4" id="text-1-9-2">
</div><ol class="org-ol"><li><a id="sec-1-9-2-1" name="sec-1-9-2-1"></a>buy which model? an uno?<br  /></li>
<li><a id="sec-1-9-2-2" name="sec-1-9-2-2"></a>learn it, have fun with it, do some starter projects<br  /></li>
<li><a id="sec-1-9-2-3" name="sec-1-9-2-3"></a><a href="http://www.ladyada.net/learn/arduino/">http://www.ladyada.net/learn/arduino/</a><br  /></li>
<li><a id="sec-1-9-2-4" name="sec-1-9-2-4"></a><a href="http://lifehacker.com/5976912/a-beginners-guide-to-diying-with-the-raspberry-pi?popular=true">http://lifehacker.com/5976912/a-beginners-guide-to-diying-with-the-raspberry-pi?popular=true</a><br  /></li>
<li><a id="sec-1-9-2-5" name="sec-1-9-2-5"></a><a href="http://www.icrobotics.co.uk/wiki/index.php/Turning_the_Raspberry_Pi_Into_an_FM_Transmitter">http://www.icrobotics.co.uk/wiki/index.php/Turning_the_Raspberry_Pi_Into_an_FM_Transmitter</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-9-3" class="outline-4">
<h4 id="sec-1-9-3"><span class="section-number-4">1.9.3</span> lrn-signal-processing (lrn-sig-proc)</h4>
<div class="outline-text-4" id="text-1-9-3">
</div><ol class="org-ol"><li><a id="sec-1-9-3-1" name="sec-1-9-3-1"></a>online: study emily's autocovorr = variance, and since PSD = Fourier(autocovar), power spectrum is freq "decomposition" of var in time<br  /><ol class="org-ol"><li><a id="sec-1-9-3-1-1" name="sec-1-9-3-1-1"></a>work through the math of it on wikipedia!!<br  /></li>
<li><a id="sec-1-9-3-1-2" name="sec-1-9-3-1-2"></a>email contents:<br  /><div class="outline-text-6" id="text-1-9-3-1-2">
<p>
Recall that the power spectral density is the Fourier transform of the autocorrelation function.
<a href="https://en.wikipedia.org/wiki/Spectral_density#Power_spectral_density">https://en.wikipedia.org/wiki/Spectral_density#Power_spectral_density</a>
<a href="https://en.wikipedia.org/wiki/Wiener%E2%80%93Khinchin_theorem">https://en.wikipedia.org/wiki/Wiener%E2%80%93Khinchin_theorem</a>
</p>

<p>
The autocorrelation function describes the second moment (variance) of a wide-sense stationary stochastic process:
<a href="https://en.wikipedia.org/wiki/Stationary_process#Weak_or_wide-sense_stationarity">https://en.wikipedia.org/wiki/Stationary_process#Weak_or_wide-sense_stationarity</a>
</p>

<p>
Hence the power spectrum is a frequency-domain decomposition of the time-domain variance of the process. Note that this only makes sense if you're treating the signal as a stochastic process, rather than a deterministic signal. Pretty much all spectral analysis of neural data (at least implicitly) models the signal (possibly windowed) as a wide-sense stationary process.
</p>

<p>
This is also why you need to remove the DC component (mean across time) before calculating the power spectrum: the mean across time is the first moment, which is assumed to be constant.
</p>
</div>
</li></ol>
</li>

<li><a id="sec-1-9-3-2" name="sec-1-9-3-2"></a>"coh is freq dom equi of corr, involving both ampl and phase" from nan's defense<br  /></li>
<li><a id="sec-1-9-3-3" name="sec-1-9-3-3"></a>Get/read another textbook on sig proc<br  /></li>
<li><a id="sec-1-9-3-4" name="sec-1-9-3-4"></a>Learn hilbert finally<br  /><ol class="org-ol"><li><a id="sec-1-9-3-4-1" name="sec-1-9-3-4-1"></a>hilbert gives inst ampl?<br  /></li></ol>
</li>
<li><a id="sec-1-9-3-5" name="sec-1-9-3-5"></a>tutorials<br  /><ol class="org-ol"><li><a id="sec-1-9-3-5-1" name="sec-1-9-3-5-1"></a>Fourier stuff from jeremy kun<br  /><ol class="org-ol"><li><a id="sec-1-9-3-5-1-1" name="sec-1-9-3-5-1-1"></a><a href="http://jeremykun.com/2012/04/25/the-fourier-series/">http://jeremykun.com/2012/04/25/the-fourier-series/</a><br  /></li>
<li><a id="sec-1-9-3-5-1-2" name="sec-1-9-3-5-1-2"></a><a href="http://jeremykun.com/2012/05/27/the-fourier-transform-a-primer/">http://jeremykun.com/2012/05/27/the-fourier-transform-a-primer/</a><br  /></li>
<li><a id="sec-1-9-3-5-1-3" name="sec-1-9-3-5-1-3"></a><a href="http://jeremykun.com/2012/06/06/generalized-functions/">http://jeremykun.com/2012/06/06/generalized-functions/</a><br  /></li>
<li><a id="sec-1-9-3-5-1-4" name="sec-1-9-3-5-1-4"></a><a href="http://jeremykun.com/2012/06/23/the-discrete-fourier-transform/">http://jeremykun.com/2012/06/23/the-discrete-fourier-transform/</a><br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-9-3-6" name="sec-1-9-3-6"></a><a href="https://ccrma.stanford.edu/~jos/filters/what_filter.html">https://ccrma.stanford.edu/~jos/filters/what_filter.html</a><br  /></li>
<li><a id="sec-1-9-3-7" name="sec-1-9-3-7"></a>"perseval and walder" book (on sig proc)<br  /></li>
<li><a id="sec-1-9-3-8" name="sec-1-9-3-8"></a>meditate on how, for digital filters, "nyq is defined as pi radians / second"<br  /></li>
<li><a id="sec-1-9-3-9" name="sec-1-9-3-9"></a>What is this phase shift business for low pass filters??<br  /></li>
<li><a id="sec-1-9-3-10" name="sec-1-9-3-10"></a><a href="http://www.ece.rutgers.edu/~orfanidi/intro2sp/">http://www.ece.rutgers.edu/~orfanidi/intro2sp/</a><br  /></li>
<li><a id="sec-1-9-3-11" name="sec-1-9-3-11"></a><a href="http://www.dspguide.com/pdfbook.htm">http://www.dspguide.com/pdfbook.htm</a><br  /></li>
<li><a id="sec-1-9-3-12" name="sec-1-9-3-12"></a>Code up fourier (cpp? or c that is called by python?)<br  /></li>
<li><a id="sec-1-9-3-13" name="sec-1-9-3-13"></a>Code up wavelets (cpp? or c that is called by python?)<br  /></li>
<li><a id="sec-1-9-3-14" name="sec-1-9-3-14"></a>what is coherence a la EEG, and global coh<br  /></li>
<li><a id="sec-1-9-3-15" name="sec-1-9-3-15"></a>lrn-music-signals<br  /><ol class="org-ol"><li><a id="sec-1-9-3-15-1" name="sec-1-9-3-15-1"></a>quality levels <a href="http://www.stereophile.com/content/mp3-vs-aac-vs-flac-vs-cd-page-2#V1hUIlCZ5GW4pveb.97">http://www.stereophile.com/content/mp3-vs-aac-vs-flac-vs-cd-page-2#V1hUIlCZ5GW4pveb.97</a><br  /></li>
<li><a id="sec-1-9-3-15-2" name="sec-1-9-3-15-2"></a>converting FLAC to AAC <a href="http://keithmilleruae.blogspot.com/2014/03/converting-flac-to-aac-for-apple-iphone.html?m=1">http://keithmilleruae.blogspot.com/2014/03/converting-flac-to-aac-for-apple-iphone.html?m=1</a> and <a href="https://unix.stackexchange.com/questions/77687/how-do-i-convert-flac-files-to-aac-preferrably-vbr-320k">https://unix.stackexchange.com/questions/77687/how-do-i-convert-flac-files-to-aac-preferrably-vbr-320k</a><br  /></li>
<li><a id="sec-1-9-3-15-3" name="sec-1-9-3-15-3"></a>why 24 bit and 192 kHz sampling for listening is bad <a href="https://xiph.org/~xiphmont/demo/neil-young.html">https://xiph.org/~xiphmont/demo/neil-young.html</a> and <a href="http://www.trustmeimascientist.com/2013/02/04/the-science-of-sample-rates-when-higher-is-better-and-when-it-isnt/">http://www.trustmeimascientist.com/2013/02/04/the-science-of-sample-rates-when-higher-is-better-and-when-it-isnt/</a><br  /></li>
<li><a id="sec-1-9-3-15-4" name="sec-1-9-3-15-4"></a>EAC<br  /><ol class="org-ol"><li><a id="sec-1-9-3-15-4-1" name="sec-1-9-3-15-4-1"></a><a href="https://hydrogenaud.io/index.php/topic,30959.0.html">https://hydrogenaud.io/index.php/topic,30959.0.html</a><br  /></li>
<li><a id="sec-1-9-3-15-4-2" name="sec-1-9-3-15-4-2"></a><a href="http://wiki.hydrogenaud.io/index.php?title=EAC_and_FLAC">http://wiki.hydrogenaud.io/index.php?title=EAC_and_FLAC</a><br  /></li></ol>
</li>
<li><a id="sec-1-9-3-15-5" name="sec-1-9-3-15-5"></a>what.cd torrent group, extensive interview process <a href="https://www.whatinterviewprep.com/">https://www.whatinterviewprep.com/</a><br  /></li></ol>
</li></ol>
</div>
</div>
<div id="outline-container-sec-1-10" class="outline-3">
<h3 id="sec-1-10"><span class="section-number-3">1.10</span> lrn-Food-drink</h3>
<div class="outline-text-3" id="text-1-10">
</div><div id="outline-container-sec-1-10-1" class="outline-4">
<h4 id="sec-1-10-1"><span class="section-number-4">1.10.1</span> lrn-healthy-eating (eating comes before exercise in importance!)</h4>
<div class="outline-text-4" id="text-1-10-1">
</div><ol class="org-ol"><li><a id="sec-1-10-1-1" name="sec-1-10-1-1"></a>omg make frozen burritos for lunches? aka other frozen food on sunday&#xa0;&#xa0;&#xa0;<span class="tag"><span class="_home">@home</span></span><br  /></li>
<li><a id="sec-1-10-1-2" name="sec-1-10-1-2"></a>whole 30<br  /></li>
<li><a id="sec-1-10-1-3" name="sec-1-10-1-3"></a>notes from gohar, having done both paleo for years and Whole 30<br  /><ol class="org-ol"><li><a id="sec-1-10-1-3-1" name="sec-1-10-1-3-1"></a>Gohar says whole 30 , plan all meals, must go to market or whatever on Sunday - non negotiable. Also she had 2 cheat meals per week<br  /></li>
<li><a id="sec-1-10-1-3-2" name="sec-1-10-1-3-2"></a>Nom nom Paleo site <a href="http://nomnompaleo.com/">http://nomnompaleo.com/</a><br  /></li>
<li><a id="sec-1-10-1-3-3" name="sec-1-10-1-3-3"></a>Put stuff like meat in individual packages in freezer<br  /></li>
<li><a id="sec-1-10-1-3-4" name="sec-1-10-1-3-4"></a>Roast big sheets of vegetables<br  /></li>
<li><a id="sec-1-10-1-3-5" name="sec-1-10-1-3-5"></a>Gohar says work lunch, do frozen containers of chili and soup etc ready to go in freezer<br  /></li>
<li><a id="sec-1-10-1-3-6" name="sec-1-10-1-3-6"></a>Pre prep on Sunday even if not cooking on that day<br  /></li></ol>
</li>
<li><a id="sec-1-10-1-4" name="sec-1-10-1-4"></a><a href="http://www.nytimes.com/2015/04/21/upshot/simple-rules-for-healthy-eating.html">http://www.nytimes.com/2015/04/21/upshot/simple-rules-for-healthy-eating.html</a><br  /></li>
<li><a id="sec-1-10-1-5" name="sec-1-10-1-5"></a>gohar cabbage salad<br  /><ol class="org-ol"><li><a id="sec-1-10-1-5-1" name="sec-1-10-1-5-1"></a>dressing option 1. honey, apple cider vinegar, olive oil.<br  /></li>
<li><a id="sec-1-10-1-5-2" name="sec-1-10-1-5-2"></a>dressing option 2. rice vinegar, mirin, and tiny bits of olive oil and sesame oil<br  /></li>
<li><a id="sec-1-10-1-5-3" name="sec-1-10-1-5-3"></a>main thing: "mandolin" a head of cabbage, roast and toss in some seeds, add big handful of chopped mint, add a wee bit of mandolined shallots or red onions<br  /></li>
<li><a id="sec-1-10-1-5-4" name="sec-1-10-1-5-4"></a>can add roasted chicken<br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-10-2" class="outline-4">
<h4 id="sec-1-10-2"><span class="section-number-4">1.10.2</span> class notes</h4>
<div class="outline-text-4" id="text-1-10-2">
</div><ol class="org-ol"><li><a id="sec-1-10-2-1" name="sec-1-10-2-1"></a>20140224-adult education cajun cooking class<br  /><div class="outline-text-5" id="text-1-10-2-1">
<ul class="org-ul">
<li>cajun roux
<ul class="org-ul">
<li>darker so more flavor and color, less when formal
</li>
<li>used as a french thickening agent
</li>
<li>low heat!
</li>
</ul>
</li>
<li>jambalaya - rice dish with stuff, while gumbo is a stew w/ rice in it
<ul class="org-ul">
<li>"red" jambalaya - tomato
</li>
<li>uncooked rice (he did 3 cups to 5c stock and large tomato sauce)
</li>
<li>you can bake jambalaya
</li>
</ul>
</li>
<li>shrimp remoulade - "remolaude" means condiment
</li>
<li>cajun "trinity" - celery, green chilis, pepper
<ul class="org-ul">
<li>"holy trinity" - trinity + garlic
</li>
</ul>
</li>
<li>okra - word originally "okigumbo" but now gumbo
<ul class="org-ul">
<li>use it in gumbo!
</li>
</ul>
</li>
<li>his greatgrandma used tomatoes in gumbo
</li>
<li>if you "move around" the chx, it'll break apart, so make the call
</li>
<li>Andouille sausage
<ul class="org-ul">
<li>can you get good stuff even at supermarket now, since it's a thing
</li>
</ul>
</li>
<li>diagonal cuts of jalapeno are quicker
</li>
<li>poaching liquid - lots of lemon, celery, white wine
</li>
<li>15 mins on softening his vegs - until the color starts to dull
</li>
<li>add lemon to remoulade stuff (and many other things)
</li>
<li>"crystal" hot sauce, less vinegary
</li>
<li>poach just a few shrimp at a time, since some will chamge temp too much to be effectual
<ul class="org-ul">
<li>don't want rubber overcooked, get "just at or undercooked"
</li>
<li>look at the head of the spine to check if center underdone
</li>
<li>shock the shrimp
</li>
</ul>
</li>
<li>cajuns use animal fat in roux, Creole used butter and were richer, it's more traditionally French, simpler (less ingredients), more finely differentiated
</li>
<li>hoppier beer: drink it sooner
</li>
<li>incr alc = it ages better / you can wait on it
</li>
<li>Ommegang, Allagash, and Cambr Brew Comp have "wild yeast" beers
</li>
<li>CBC is isolating Cambridge "urban" natural yeast
</li>
<li>"GumboTales" book
</li>
</ul>
</div>
</li></ol>
</div>

<div id="outline-container-sec-1-10-3" class="outline-4">
<h4 id="sec-1-10-3"><span class="section-number-4">1.10.3</span> Get good at drinking!</h4>
<div class="outline-text-4" id="text-1-10-3">
</div><ol class="org-ol"><li><a id="sec-1-10-3-1" name="sec-1-10-3-1"></a>try montenegro digestif<br  /></li>
<li><a id="sec-1-10-3-2" name="sec-1-10-3-2"></a>william recommends Amaro Dell'erborista, said it was amazing<br  /></li>
<li><a id="sec-1-10-3-3" name="sec-1-10-3-3"></a>buy ricardo, amaro montenegro @liquor store&#xa0;&#xa0;&#xa0;<span class="tag"><span class="food">food</span>&#xa0;<span class="buy">buy</span></span><br  /></li>
<li><a id="sec-1-10-3-4" name="sec-1-10-3-4"></a>beer: kevin wang wants Trillium and Tree House beers (made in boston), says they're the best on beeradvocate.com<br  /></li>
<li><a id="sec-1-10-3-5" name="sec-1-10-3-5"></a>rsh more on very old fashioneds<br  /></li>
<li><a id="sec-1-10-3-6" name="sec-1-10-3-6"></a>Zephyr cocktail at Hawthorne, made by Jason, very good<br  /></li>
<li><a id="sec-1-10-3-7" name="sec-1-10-3-7"></a>mojitos<br  /></li>
<li><a id="sec-1-10-3-8" name="sec-1-10-3-8"></a>1919 <a href="http://cocktailvirgin.blogspot.com/2008/11/1919-cocktail.html?m=1">http://cocktailvirgin.blogspot.com/2008/11/1919-cocktail.html?m=1</a><br  /></li>
<li><a id="sec-1-10-3-9" name="sec-1-10-3-9"></a>Bourbon &amp; ginger<br  /><ol class="org-ol"><li><a id="sec-1-10-3-9-1" name="sec-1-10-3-9-1"></a>either Talisker 18 and ginger ale, or<br  /><ol class="org-ol"><li><a id="sec-1-10-3-9-1-1" name="sec-1-10-3-9-1-1"></a>ginger syrup via<br  /><div class="outline-text-7" id="text-1-10-3-9-1-1">
<ul class="org-ul">
<li>1/2 cup sugar (fine turbinado)
</li>
<li>1/2 cup water
</li>
<li>1/4 lb. fresh ginger root (peeled and finely grated)
</li>
<li>In a small saucepot bring the sugar, water, and ginger to a boil. Turn off the heat, and allow to steep and cool for one hour. Strain off the ginger pieces, and reserve the syrup.
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-9-1-2" name="sec-1-10-3-9-1-2"></a>mixed via<br  /><div class="outline-text-7" id="text-1-10-3-9-1-2">
<ul class="org-ul">
<li>Large ice cubes
</li>
<li>3 oz. Maker's Mark (or your favorite bourbon)
</li>
<li>1 tbsp. ginger syrup
</li>
<li>2 slices fresh ripe peach (Try pear if peaches are out of season.)
</li>
<li>2 oz. soda water
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-9-1-3" name="sec-1-10-3-9-1-3"></a>Fill a 10 oz. highball glass with ice. Add bourbon and ginger syrup, and stir. Add peach slices (or pear), and pour soda water to the top of the glass. Stir gently.<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-10-3-10" name="sec-1-10-3-10"></a>Prof moriarty fernet drink at Peter kern lib<br  /></li>
<li><a id="sec-1-10-3-11" name="sec-1-10-3-11"></a>beers to try<br  /><ol class="org-ol"><li><a id="sec-1-10-3-11-1" name="sec-1-10-3-11-1"></a>headytopper<br  /></li>
<li><a id="sec-1-10-3-11-2" name="sec-1-10-3-11-2"></a>Great lakes brewing co, commodore perry IPA<br  /></li></ol>
</li>
<li><a id="sec-1-10-3-12" name="sec-1-10-3-12"></a>wines to try<br  /><ol class="org-ol"><li><a id="sec-1-10-3-12-1" name="sec-1-10-3-12-1"></a>Sokol Blosser - Evolution<br  /></li></ol>
</li>
<li><a id="sec-1-10-3-13" name="sec-1-10-3-13"></a>ward eight recipes<br  /><ol class="org-ol"><li><a id="sec-1-10-3-13-1" name="sec-1-10-3-13-1"></a>old recipe:<br  /><div class="outline-text-6" id="text-1-10-3-13-1">
<ul class="org-ul">
<li>0.5 oz lemon juice
</li>
<li>0.5 oz orange juice
</li>
<li>2 oz rye whiskey
</li>
<li>4 dashes grenadine
</li>
<li>shake, serve with cracked ice
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-13-2" name="sec-1-10-3-13-2"></a>from a latin quarter ? nightclub in 1950s:<br  /><div class="outline-text-6" id="text-1-10-3-13-2">
<ul class="org-ul">
<li>1.5 oz rye
</li>
<li>juice from half a lemon
</li>
<li>1 oz orange juice
</li>
<li>1 tsp grenadine
</li>
<li>shake and strain, garnish with maraschino
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-13-3" name="sec-1-10-3-13-3"></a>1934 G Selmer Fougner for the New York Sun<br  /><div class="outline-text-6" id="text-1-10-3-13-3">
<ul class="org-ul">
<li>juice from one lemon
</li>
<li>1 "barspoon" of powdered sugar
</li>
<li>put above in large whiskey glass 3/4 full of bourbon
</li>
<li>add ice
</li>
<li>3/4 dashes orange bitters
</li>
<li>one-half "jigger" of grenadine
</li>
<li>either bruised mint or creme de menthe
</li>
<li>top off with water or seltzer
</li>
<li>add two half slices of orange, a piece of pineapple and a cherry
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-13-4" name="sec-1-10-3-13-4"></a>1936 Mr Boston advertisement<br  /><div class="outline-text-6" id="text-1-10-3-13-4">
<ul class="org-ul">
<li>1.5 oz Old Mr Boston Rye ""Liqueur"
</li>
<li>1 oz lemon juice
</li>
<li>0.5 oz orange juice
</li>
<li>0.5 oz grenadine
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-13-5" name="sec-1-10-3-13-5"></a>modern Ward Eight from Drink<br  /><div class="outline-text-6" id="text-1-10-3-13-5">
<ul class="org-ul">
<li>3 oz Old Overholt Rye
</li>
<li>1 oz lemon juice
</li>
<li>0.5 oz simple syrup
</li>
<li>4 dash Ango orange bitters
</li>
<li>0.5 oz grenadine
</li>
<li>top with soda water
</li>
<li>muddle mint into a glass and then remove the mint
</li>
</ul>
</div>
</li></ol>
</li>

<li><a id="sec-1-10-3-14" name="sec-1-10-3-14"></a>south boston cocktail, from Mr Boston official bartender's guide<br  /><div class="outline-text-5" id="text-1-10-3-14">
<ul class="org-ul">
<li>1 part Wire Works American Gin
</li>
<li>1 part apple brandy
</li>
<li>0.5 part lemon juice
</li>
<li>0.25 grenadine or pomegranate syrup
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-15" name="sec-1-10-3-15"></a>the lone tree from Hotel Touraine, Boston<br  /><div class="outline-text-5" id="text-1-10-3-15">
<ul class="org-ul">
<li>1 part american gin
</li>
<li>1 part sweet vermouth
</li>
<li>1 dash orange bitters
</li>
<li>strip of orange peel
</li>
</ul>
</div>
</li>

<li><a id="sec-1-10-3-16" name="sec-1-10-3-16"></a>Fanciulli is a Manhattan but Fernet Branca instead of Angostura<br  /></li>
<li><a id="sec-1-10-3-17" name="sec-1-10-3-17"></a>Dillionaire <a href="http://www.seriouseats.com/recipes/2014/03/dillionaire-dill-hendricks-gin-cucumber-cocktail-recipe.html">http://www.seriouseats.com/recipes/2014/03/dillionaire-dill-hendricks-gin-cucumber-cocktail-recipe.html</a><br  /></li>
<li><a id="sec-1-10-3-18" name="sec-1-10-3-18"></a>Fernet vallet Mexican fernet?<br  /></li></ol>
</div>
<div id="outline-container-sec-1-10-4" class="outline-4">
<h4 id="sec-1-10-4"><span class="section-number-4">1.10.4</span> get good at cooking!</h4>
<div class="outline-text-4" id="text-1-10-4">
</div><ol class="org-ol"><li><a id="sec-1-10-4-1" name="sec-1-10-4-1"></a><span class="todo TODO">TODO</span> specific recipes "Le Cuisine Austine"<br  /><ol class="org-ol"><li><a id="sec-1-10-4-1-1" name="sec-1-10-4-1-1"></a>better stuff for sick babe<br  /><ol class="org-ol"><li><a id="sec-1-10-4-1-1-1" name="sec-1-10-4-1-1-1"></a>quinoa with beef<br  /></li>
<li><a id="sec-1-10-4-1-1-2" name="sec-1-10-4-1-1-2"></a>protein shakes<br  /></li>
<li><a id="sec-1-10-4-1-1-3" name="sec-1-10-4-1-1-3"></a>keep whole wheat pita bread in freezer to toast and add hummus and tomatoes<br  /></li>
<li><a id="sec-1-10-4-1-1-4" name="sec-1-10-4-1-1-4"></a>Feta, watermelon, and mint salad<br  /></li>
<li><a id="sec-1-10-4-1-1-5" name="sec-1-10-4-1-1-5"></a>parfaits<br  /></li></ol>
</li>
<li><a id="sec-1-10-4-1-2" name="sec-1-10-4-1-2"></a>vietnamese caramel pork <a href="https://www.reddit.com/r/GifRecipes/comments/79owiu/vietnamese_caramel_pork/">https://www.reddit.com/r/GifRecipes/comments/79owiu/vietnamese_caramel_pork/</a><br  /></li>
<li><a id="sec-1-10-4-1-3" name="sec-1-10-4-1-3"></a><a href="http://www.supercook.com/#/recipes">http://www.supercook.com/#/recipes</a><br  /></li>
<li><a id="sec-1-10-4-1-4" name="sec-1-10-4-1-4"></a><a href="http://myfridgefood.com/">http://myfridgefood.com/</a><br  /></li>
<li><a id="sec-1-10-4-1-5" name="sec-1-10-4-1-5"></a>ribs: Remove silver skin, wash with water and pat super dry. Apply dry rub (your choice, but ground mustard, chili powder, onion/garlic powder, salt/pepper, crushed red pepper flakes, little cinnamon and cumin is Kat's go-to). Massage the shit out of your ribs with rub. Flip upside down so ribs cook in their own juices. Cook at 300F for 3 hrs. Remove from oven, flip and baste in BBQ sauce (again, your choice or make your own &#x2013; Kat does apple cider vinegar, reduced sugar ketchup, whole grain mustard, small amount of honey, worchestire, spices as needed). Crank up to 375. Baste every 10 min for about 30 min. Takes 3.5-4 hrs depending on size of rack. These always fall off the bone.<br  /></li>
<li><a id="sec-1-10-4-1-6" name="sec-1-10-4-1-6"></a>baked potato and kimchi (idea from Sam Marcus, whose mom is amazing cook)<br  /></li>
<li><a id="sec-1-10-4-1-7" name="sec-1-10-4-1-7"></a>the "Kreuben" - pastrami Reuben with kimchi in place of cole slaw (based off The Freak #55 from Rhea's in San Fran)<br  /></li>
<li><a id="sec-1-10-4-1-8" name="sec-1-10-4-1-8"></a>salad from Refill Cafe in SD: kale, roasted corn, edamame [/lima beans], sweet potato [I thought was caramelized carrots], tomato, sunflower seeds [nuts/protein], champagne vinagrette<br  /></li>
<li><a id="sec-1-10-4-1-9" name="sec-1-10-4-1-9"></a>make goulash from food lab <a href="http://www.seriouseats.com/2016/02/hungarian-goulash-beef-paprika-stew-recipe-food-lab.html">http://www.seriouseats.com/2016/02/hungarian-goulash-beef-paprika-stew-recipe-food-lab.html</a><br  /></li>
<li><a id="sec-1-10-4-1-10" name="sec-1-10-4-1-10"></a>supposedly good chili <a href="https://www.reddit.com/r/recipes/comments/14o99i/its_that_time_of_year_for_chili_share_your_recipe/c7f2dro">https://www.reddit.com/r/recipes/comments/14o99i/its_that_time_of_year_for_chili_share_your_recipe/c7f2dro</a><br  /><div class="outline-text-6" id="text-1-10-4-1-10">
<p>
WARNING THIS IS THE BEST CHILI YOU WILL EVER TASTE, DON'T DIE AFTER EATING
Grocery List
1 - 2 lb of a Boneless Beef Chuck cubed. (no g/b or cubed steak)
1 Large Container Beef Stock
1 large red onion
1 Yellow Onion
1 Stalk of Celery
1 Beer I like to use Blue Moon
1 pack of Thick Cut Bacon
1 Large Bag of Pinto Beans DRY (This is secret #1)
1 Small Bag Black Beans DRY ( Dry Beans all together are secret #1)
1 Large Garlic Clove
1 Red Bell pepper
2 Cans Stewed Tomatoes with Green Chili's
Extra Virgin Olive Oil &amp; Butter
Small Can of Tomato Paste
Cheddar Cheese and Oyster Crackers (Optional)
Spices
Assorted Spices, Cumin, Chili Powder, Garlic Powder, Onion Powder, Paprika, Oregano, Salt, Pepper.
Fridge Staples
Worcestershire Sauce
Ketchup (Secret #2)
Vinegar
Hot Sauce/Tabasco
Liquid Smoke
Preperation.
Soak Dry Beans Overnight, If you don't soak overnight, Soak at least one hour prior to cooking.
Cover Beans with Water, Chop Yellow onion in half, and chop celery 2 celery stalks in half. Add the Halved onion's and celery to the water/dry bean mixture, Boil beans Until Almost soft and when the water level is low Add 1/2 of your beef stock/broth.
Continue boiling until fully cooked, You will have a soupy bean/beef/veg broth just covering the top of the beans. Remove the 2 onion halves and the celery stalks.
Dice your entire red Onion, and red bell Pepper, and Mince your garlic.
Start a hot pan with EVOO and 1tbs Butter. Add the Bacon, Once partially cooked, Add Diced Chuck, Cook until the outsides are seared, add The entire onion and red bell pepper, saute until translucent and sweet, add minced garlic and cook for 20-30 seconds more. This whole process shouldn't take more than 5 minutes.
Add the rest of the Beef Broth to the beans and your Beer, Add the Beef/Bacon/Onion/RBP/Garlic Mixture to the Pot as well. Also add Both cans of Stewed tomatoes.
Add about 1tbs of each seasoning, except oregano, add 1tsp oregano. Be very liberal with the worcestershire, add lots. Add 2 tsp vinegar, 2 tsp hot sauce and 1tbs liquid smoke. And Add Several TBS of Ketchup, this is my secret. It brings tons of flavor profile to the table. Also Add A tbs or so of tomato paste if you like thicker chili. Simmer this for at least an hour stirring occasionally.
Serve with Diced onions, Cheddar Cheese and Oyster crackers if you please.
NEVER MAKE CHILIS WITH CANNED BEANS YOU DISGUST ME!!!
Options: Add a tbs of mustard, Add large Carrots or other larger portion vegetable in the bean boiling process for additional veg broth flavor. Add more spices for your particular flavor profile. Add red pepper flake for heat, Add Fresh diced jalapeno's in the sauteing process.
</p>
</div>
</li>

<li><a id="sec-1-10-4-1-11" name="sec-1-10-4-1-11"></a><a href="http://www.seriouseats.com/2015/03/how-to-make-light-tender-potato-gnocchi.html">http://www.seriouseats.com/2015/03/how-to-make-light-tender-potato-gnocchi.html</a><br  /></li>
<li><a id="sec-1-10-4-1-12" name="sec-1-10-4-1-12"></a><a href="http://www.reddit.com/r/food/comments/26grwy/my_chicago_style_stuffed_pizza_best_ones_ive_made/">http://www.reddit.com/r/food/comments/26grwy/my_chicago_style_stuffed_pizza_best_ones_ive_made/</a><br  /></li>
<li><a id="sec-1-10-4-1-13" name="sec-1-10-4-1-13"></a><a href="https://www.reddit.com/r/food/comments/3xcu1v/34_oz_bone_in_ribeye_with_red_wine_shallot_sauce/">34 oz bone in Ribeye with Red Wine shallot sauce. Best steak I have ever made.</a><br  /></li>
<li><a id="sec-1-10-4-1-14" name="sec-1-10-4-1-14"></a>cassoulet <a href="http://cooking.nytimes.com/recipes/1017177-slow-cooker-cassoulet?smid=fb-nytimes&smtyp=cur">http://cooking.nytimes.com/recipes/1017177-slow-cooker-cassoulet?smid=fb-nytimes&smtyp=cur</a><br  /></li>
<li><a id="sec-1-10-4-1-15" name="sec-1-10-4-1-15"></a>gumbo <a href="http://www.foodnetwork.com/recipes/emeril-lagasse/chicken-and-smoked-sausage-gumbo-with-white-rice-recipe.html">http://www.foodnetwork.com/recipes/emeril-lagasse/chicken-and-smoked-sausage-gumbo-with-white-rice-recipe.html</a> OR <a href="http://www.foodnetwork.com/recipes/emeril-lagasse/chicken-and-smoked-sausage-gumbo-recipe.html">http://www.foodnetwork.com/recipes/emeril-lagasse/chicken-and-smoked-sausage-gumbo-recipe.html</a> ? or another one? not sure which<br  /></li>
<li><a id="sec-1-10-4-1-16" name="sec-1-10-4-1-16"></a>chx tikka masala <a href="http://www.seriouseats.com/recipes/2012/06/chicken-tikka-masala-for-the-grill-recipe.html">http://www.seriouseats.com/recipes/2012/06/chicken-tikka-masala-for-the-grill-recipe.html</a><br  /></li>
<li><a id="sec-1-10-4-1-17" name="sec-1-10-4-1-17"></a>bean soup recipe, good for xmas <a href="http://food52.com/recipes/26953-brothy-garlicky-beans">http://food52.com/recipes/26953-brothy-garlicky-beans</a><br  /></li>
<li><a id="sec-1-10-4-1-18" name="sec-1-10-4-1-18"></a>recreate booya's tacos, lime zest or oil in the fry<br  /></li>
<li><a id="sec-1-10-4-1-19" name="sec-1-10-4-1-19"></a>slow cooker bbq chx <a href="http://slowcookerhealthy.com/recipes/sweet-and-tangy-pulled-chicken/">http://slowcookerhealthy.com/recipes/sweet-and-tangy-pulled-chicken/</a><br  /></li>
<li><a id="sec-1-10-4-1-20" name="sec-1-10-4-1-20"></a>this is good if up the paste to make spicy, maybe add peanuts <a href="http://www.seriouseats.com/recipes/2014/03/kimchi-chicken-cabbage-stir-fry.html">http://www.seriouseats.com/recipes/2014/03/kimchi-chicken-cabbage-stir-fry.html</a><br  /></li>
<li><a id="sec-1-10-4-1-21" name="sec-1-10-4-1-21"></a>"Marinating the chicken strips in a mixture of cornstarch, egg white, wine, and seasonings—a process known as velveting—guarantees silky, tender meat." from <a href="http://www.seriouseats.com/recipes/2014/07/stir-fried-chicken-mushrooms-oyster-sauce-recipe.html">http://www.seriouseats.com/recipes/2014/07/stir-fried-chicken-mushrooms-oyster-sauce-recipe.html</a><br  /></li>
<li><a id="sec-1-10-4-1-22" name="sec-1-10-4-1-22"></a>learn to make morocan mouciaz dish with caramelized onions and dates? And sesame seeds over beef?<br  /></li>
<li><a id="sec-1-10-4-1-23" name="sec-1-10-4-1-23"></a><a href="https://www.reddit.com/r/Fitness/comments/2rbbcj/what_is_your_favorite_bringtowork_lunch_meal/">https://www.reddit.com/r/Fitness/comments/2rbbcj/what_is_your_favorite_bringtowork_lunch_meal/</a><br  /></li>
<li><a id="sec-1-10-4-1-24" name="sec-1-10-4-1-24"></a><a href="http://jessicainthekitchen.com/vegan-crockpot-quinoa-black-bean-chili/">http://jessicainthekitchen.com/vegan-crockpot-quinoa-black-bean-chili/</a><br  /></li>
<li><a id="sec-1-10-4-1-25" name="sec-1-10-4-1-25"></a><a href="http://www.bbcgoodfood.com/recipes/1104644/ribeye-steaks-with-chilli-butter-and-homemade-chip">http://www.bbcgoodfood.com/recipes/1104644/ribeye-steaks-with-chilli-butter-and-homemade-chip</a><br  /></li>
<li><a id="sec-1-10-4-1-26" name="sec-1-10-4-1-26"></a><a href="http://www.seriouseats.com/2012/12/the-food-lab-complete-guide-to-pan-seared-steaks.html">http://www.seriouseats.com/2012/12/the-food-lab-complete-guide-to-pan-seared-steaks.html</a><br  /></li>
<li><a id="sec-1-10-4-1-27" name="sec-1-10-4-1-27"></a>creme brulee <a href="https://www.reddit.com/r/food/comments/38bt20/wife_got_me_a_brulee_torch_for_my_birthday_and/">https://www.reddit.com/r/food/comments/38bt20/wife_got_me_a_brulee_torch_for_my_birthday_and/</a><br  /></li>
<li><a id="sec-1-10-4-1-28" name="sec-1-10-4-1-28"></a>pineapple bacon tacos <a href="http://www.seriouseats.com/2016/02/pineapple-bacon-tacos-al-pastor-reverse.html#1203084">http://www.seriouseats.com/2016/02/pineapple-bacon-tacos-al-pastor-reverse.html#1203084</a><br  /></li>
<li><a id="sec-1-10-4-1-29" name="sec-1-10-4-1-29"></a><a href="https://www.reddit.com/r/food/comments/4vmw8e/one_of_the_best_slow_cooker_recipes_i_have_tried/">https://www.reddit.com/r/food/comments/4vmw8e/one_of_the_best_slow_cooker_recipes_i_have_tried/</a>&#xa0;&#xa0;&#xa0;<span class="tag"><span class="food">food</span></span><br  /></li>
<li><a id="sec-1-10-4-1-30" name="sec-1-10-4-1-30"></a><a href="http://oldschoolpastry.blogspot.com/2011/07/foodie-friday-dipney-or-barbeque.html?m=1">http://oldschoolpastry.blogspot.com/2011/07/foodie-friday-dipney-or-barbeque.html?m=1</a><br  /></li>
<li><a id="sec-1-10-4-1-31" name="sec-1-10-4-1-31"></a>Different mushrooms in miso butter and black pepper sauce with lemon<br  /></li>
<li><a id="sec-1-10-4-1-32" name="sec-1-10-4-1-32"></a>Make bouillabaisse, especially Richard Olney's recipe in Lulu's Provencal Table<br  /></li>
<li><a id="sec-1-10-4-1-33" name="sec-1-10-4-1-33"></a>butternut squash risotto<br  /></li>
<li><a id="sec-1-10-4-1-34" name="sec-1-10-4-1-34"></a>vegan meal prep<br  /><ol class="org-ol"><li><a id="sec-1-10-4-1-34-1" name="sec-1-10-4-1-34-1"></a><a href="https://spoonuniversity.com/recipe/10-cheap-vegan-meal-prep-ideas">https://spoonuniversity.com/recipe/10-cheap-vegan-meal-prep-ideas</a><br  /></li>
<li><a id="sec-1-10-4-1-34-2" name="sec-1-10-4-1-34-2"></a><a href="https://thestingyvegan.com/vegan-meal-prep-ideas/">https://thestingyvegan.com/vegan-meal-prep-ideas/</a><br  /></li>
<li><a id="sec-1-10-4-1-34-3" name="sec-1-10-4-1-34-3"></a><a href="https://www.reddit.com/r/mealprep/comments/6j95y9/7_days_of_food_for_20_by_cheap_lazy_vegan/">https://www.reddit.com/r/mealprep/comments/6j95y9/7_days_of_food_for_20_by_cheap_lazy_vegan/</a><br  /></li></ol>
</li>
<li><a id="sec-1-10-4-1-35" name="sec-1-10-4-1-35"></a>make more bean salads<br  /></li></ol>
</li>
<li><a id="sec-1-10-4-2" name="sec-1-10-4-2"></a>ask packer about burger recipe<br  /><ol class="org-ol"><li><a id="sec-1-10-4-2-1" name="sec-1-10-4-2-1"></a>add caramelized onions embedded into burger<br  /></li>
<li><a id="sec-1-10-4-2-2" name="sec-1-10-4-2-2"></a>use worcestershire, or fish sauce, or marmite for umami<br  /></li>
<li><a id="sec-1-10-4-2-3" name="sec-1-10-4-2-3"></a>let beef patties marinate with above<br  /></li></ol>
</li>
<li><a id="sec-1-10-4-3" name="sec-1-10-4-3"></a>buy steak tips and sausage marinade sauce Dom's butcher shop in boston&#xa0;&#xa0;&#xa0;<span class="tag"><span class="food">food</span>&#xa0;<span class="buy">buy</span></span><br  /></li>
<li><a id="sec-1-10-4-4" name="sec-1-10-4-4"></a>last remaining organic producers as of <a href="http://www.nytimes.com/2012/07/08/business/organic-food-purists-worry-about-big-companies-influence.html?_r=2">http://www.nytimes.com/2012/07/08/business/organic-food-purists-worry-about-big-companies-influence.html?_r=2</a><br  /><ol class="org-ol"><li><a id="sec-1-10-4-4-1" name="sec-1-10-4-4-1"></a>Eden foods<br  /></li>
<li><a id="sec-1-10-4-4-2" name="sec-1-10-4-4-2"></a>Clif Bar &amp; Company<br  /></li>
<li><a id="sec-1-10-4-4-3" name="sec-1-10-4-4-3"></a>Amy’s Kitchen<br  /></li>
<li><a id="sec-1-10-4-4-4" name="sec-1-10-4-4-4"></a>Lundberg Family Farms<br  /></li></ol>
</li>
<li><a id="sec-1-10-4-5" name="sec-1-10-4-5"></a>scrambled eggs<br  /><ol class="org-ol"><li><a id="sec-1-10-4-5-1" name="sec-1-10-4-5-1"></a><a href="http://food52.com/blog/8583-how-to-make-perfect-scrambled-eggs">http://food52.com/blog/8583-how-to-make-perfect-scrambled-eggs</a><br  /></li></ol>
</li>
<li><a id="sec-1-10-4-6" name="sec-1-10-4-6"></a>Chefmaca.com<br  /></li>
<li><a id="sec-1-10-4-7" name="sec-1-10-4-7"></a>bacon<br  /><ol class="org-ol"><li><a id="sec-1-10-4-7-1" name="sec-1-10-4-7-1"></a>cooks illustrated recommends FARMLAND thick sliced bacon and PLUMROSE Premium thick sliced bacon<br  /><ol class="org-ol"><li><a id="sec-1-10-4-7-1-1" name="sec-1-10-4-7-1-1"></a>says more meat (higher protein to fat ratio), and thicker, means better<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-10-4-8" name="sec-1-10-4-8"></a>smoker and grill cooking<br  /><ol class="org-ol"><li><a id="sec-1-10-4-8-1" name="sec-1-10-4-8-1"></a>smoking cheese <a href="http://melissaknorris.com/2014/06/how-to-smoke-cheeseathome/">http://melissaknorris.com/2014/06/how-to-smoke-cheeseathome/</a><br  /></li>
<li><a id="sec-1-10-4-8-2" name="sec-1-10-4-8-2"></a>brisket smoker rub <a href="http://www.thesmokerking.com/page6d.html">http://www.thesmokerking.com/page6d.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-10-4-9" name="sec-1-10-4-9"></a>also gohar says marinate chicken in basil, mint, garlic, and lemon<br  /></li>
<li><a id="sec-1-10-4-10" name="sec-1-10-4-10"></a>try Red boat fish sauce<br  /></li>
<li><a id="sec-1-10-4-11" name="sec-1-10-4-11"></a>Haloumi food<br  /></li>
<li><a id="sec-1-10-4-12" name="sec-1-10-4-12"></a>Montreal dry rub steak rub<br  /></li>
<li><a id="sec-1-10-4-13" name="sec-1-10-4-13"></a>From instant pot cookbook, do porcini mushroom pate, Moroccan lamb tagine, coconut fish curry<br  /></li>
<li><a id="sec-1-10-4-14" name="sec-1-10-4-14"></a>Make porchetta for holidays<br  /></li>
<li><a id="sec-1-10-4-15" name="sec-1-10-4-15"></a>make and freeze own veggie burgers<br  /></li></ol>
</div>
<div id="outline-container-sec-1-10-5" class="outline-4">
<h4 id="sec-1-10-5"><span class="section-number-4">1.10.5</span> coffee and tea</h4>
<div class="outline-text-4" id="text-1-10-5">
</div><ol class="org-ol"><li><a id="sec-1-10-5-1" name="sec-1-10-5-1"></a>chris johnson says peruvian from Harvest near babe's is good<br  /></li></ol>
</div>
<div id="outline-container-sec-1-10-6" class="outline-4">
<h4 id="sec-1-10-6"><span class="section-number-4">1.10.6</span> already made cooking recipes that are good</h4>
<div class="outline-text-4" id="text-1-10-6">
</div><ol class="org-ol"><li><a id="sec-1-10-6-1" name="sec-1-10-6-1"></a>lobster thermidor recipe, successfully tripled (maybe only need 2 tblspn tarragon? or 3) &#x2013; emeril's lobster thermidor <a href="http://www.foodnetwork.com/recipes/emeril-lagasse/lobster-thermidor-recipe.html?oc=linkback">http://www.foodnetwork.com/recipes/emeril-lagasse/lobster-thermidor-recipe.html?oc=linkback</a><br  /></li>
<li><a id="sec-1-10-6-2" name="sec-1-10-6-2"></a>did this but used Alton Brown indoors steak cooking method, make sure you "baste" the butter/juices back on the steak when outside of the oven! makes a big diff <a href="http://www.bbcgoodfood.com/recipes/1104644/ribeye-steaks-with-chilli-butter-and-homemade-chip">http://www.bbcgoodfood.com/recipes/1104644/ribeye-steaks-with-chilli-butter-and-homemade-chip</a><br  /></li>
<li><a id="sec-1-10-6-3" name="sec-1-10-6-3"></a><a href="http://www.eatingwell.com/recipe/249458/tilapia-corn-chowder/">http://www.eatingwell.com/recipe/249458/tilapia-corn-chowder/</a><br  /></li>
<li><a id="sec-1-10-6-4" name="sec-1-10-6-4"></a><a href="http://eatwithinyourmeans.com/pressure-cooker-lentil-soup/">http://eatwithinyourmeans.com/pressure-cooker-lentil-soup/</a><br  /></li>
<li><a id="sec-1-10-6-5" name="sec-1-10-6-5"></a><a href="http://www.seriouseats.com/recipes/2015/01/ultimate-beef-stroganof-recipe.html">http://www.seriouseats.com/recipes/2015/01/ultimate-beef-stroganof-recipe.html</a><br  /></li>
<li><a id="sec-1-10-6-6" name="sec-1-10-6-6"></a><a href="https://food52.com/recipes/15831-nekisia-davis-olive-oil-and-maple-granola">https://food52.com/recipes/15831-nekisia-davis-olive-oil-and-maple-granola</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-11" class="outline-3">
<h3 id="sec-1-11"><span class="section-number-3">1.11</span> lrn-grooming&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_grooming">lrn_grooming</span></span></h3>
<div class="outline-text-3" id="text-1-11">
</div><div id="outline-container-sec-1-11-1" class="outline-4">
<h4 id="sec-1-11-1"><span class="section-number-4">1.11.1</span> lrn-hair&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_hair">lrn_hair</span></span></h4>
<div class="outline-text-4" id="text-1-11-1">
</div><ol class="org-ol"><li><a id="sec-1-11-1-1" name="sec-1-11-1-1"></a>if need pomade, Murray's (sp) or Imperial (water-based) are supposedly good<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-12" class="outline-3">
<h3 id="sec-1-12"><span class="section-number-3">1.12</span> lrn-ergonomics</h3>
<div class="outline-text-3" id="text-1-12">
</div><div id="outline-container-sec-1-12-1" class="outline-4">
<h4 id="sec-1-12-1"><span class="section-number-4">1.12.1</span> ergonomic chair stuff <a href="https://www.reddit.com/r/productivity/comments/60e5ya/if_youre_looking_to_purchase_an_ergonomic_chair/">https://www.reddit.com/r/productivity/comments/60e5ya/if_youre_looking_to_purchase_an_ergonomic_chair/</a></h4>
</div>
</div>
<div id="outline-container-sec-1-13" class="outline-3">
<h3 id="sec-1-13"><span class="section-number-3">1.13</span> lrn-hardware</h3>
<div class="outline-text-3" id="text-1-13">
</div><div id="outline-container-sec-1-13-1" class="outline-4">
<h4 id="sec-1-13-1"><span class="section-number-4">1.13.1</span> sony WH-1000xM2 noise-canceling headphones</h4>
<div class="outline-text-4" id="text-1-13-1">
</div><ol class="org-ol"><li><a id="sec-1-13-1-1" name="sec-1-13-1-1"></a>update: just get bose QC 35's since time-tested. M2's may still have the first series manu defect and longterm changes unknown<br  /></li>
<li><a id="sec-1-13-1-2" name="sec-1-13-1-2"></a>second gen mdr1000x's<br  /></li>
<li><a id="sec-1-13-1-3" name="sec-1-13-1-3"></a>apparently beat the "classic" bose quiet comfor 35's<br  /></li>
<li><a id="sec-1-13-1-4" name="sec-1-13-1-4"></a><a href="https://www.reddit.com/r/headphones/comments/53mshx/sony_mdr1000x_first_reviews/">https://www.reddit.com/r/headphones/comments/53mshx/sony_mdr1000x_first_reviews/</a><br  /></li>
<li><a id="sec-1-13-1-5" name="sec-1-13-1-5"></a><a href="http://www.trustedreviews.com/reviews/sony-wh-1000xm2">http://www.trustedreviews.com/reviews/sony-wh-1000xm2</a><br  /></li>
<li><a id="sec-1-13-1-6" name="sec-1-13-1-6"></a><a href="https://www.amazon.com/Sony-WH1000XM2-Cancelling-Wireless-Headphones/dp/B074KDJVS2">https://www.amazon.com/Sony-WH1000XM2-Cancelling-Wireless-Headphones/dp/B074KDJVS2</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-13-2" class="outline-4">
<h4 id="sec-1-13-2"><span class="section-number-4">1.13.2</span> lrn-knots</h4>
<div class="outline-text-4" id="text-1-13-2">
</div><ol class="org-ol"><li><a id="sec-1-13-2-1" name="sec-1-13-2-1"></a><a href="https://gearpatrol.com/2017/12/30/how-to-tie-knots/">https://gearpatrol.com/2017/12/30/how-to-tie-knots/</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-14" class="outline-3">
<h3 id="sec-1-14"><span class="section-number-3">1.14</span> lrn-history</h3>
<div class="outline-text-3" id="text-1-14">
</div><div id="outline-container-sec-1-14-1" class="outline-4">
<h4 id="sec-1-14-1"><span class="section-number-4">1.14.1</span> lrn-chinese-history</h4>
<div class="outline-text-4" id="text-1-14-1">
</div><ol class="org-ol"><li><a id="sec-1-14-1-1" name="sec-1-14-1-1"></a>Riley Bogema's list of books for chinese history<br  /><ol class="org-ol"><li><a id="sec-1-14-1-1-1" name="sec-1-14-1-1-1"></a>The open empire – Valerie hanson<br  /></li>
<li><a id="sec-1-14-1-1-2" name="sec-1-14-1-1-2"></a>The Chinese frontier – 221bc – 1857?<br  /></li>
<li><a id="sec-1-14-1-1-3" name="sec-1-14-1-1-3"></a>The perilous frontier – Thomas barfield<br  /></li>
<li><a id="sec-1-14-1-1-4" name="sec-1-14-1-1-4"></a>Ancient china and its enemies – Nicola icosmo<br  /></li>
<li><a id="sec-1-14-1-1-5" name="sec-1-14-1-1-5"></a>The rise of the east empire<br  /></li>
<li><a id="sec-1-14-1-1-6" name="sec-1-14-1-1-6"></a>Mao’s biography<br  /></li>
<li><a id="sec-1-14-1-1-7" name="sec-1-14-1-1-7"></a>1845-1864 – the largest uprising in human history<br  /></li>
<li><a id="sec-1-14-1-1-8" name="sec-1-14-1-1-8"></a>God’s Chinese son – jonathan Spence<br  /></li>
<li><a id="sec-1-14-1-1-9" name="sec-1-14-1-1-9"></a>The unknown story of mao – jung chang, john halliday<br  /></li>
<li><a id="sec-1-14-1-1-10" name="sec-1-14-1-1-10"></a>Chinese civilization – a source book &#x2014; patricia ebrey<br  /></li>
<li><a id="sec-1-14-1-1-11" name="sec-1-14-1-1-11"></a>Cheng-du – “the best city in china” – travel hub<br  /></li></ol>
</li></ol>
</div>
</div>
<div id="outline-container-sec-1-15" class="outline-3">
<h3 id="sec-1-15"><span class="section-number-3">1.15</span> lrn-home-accoutrements</h3>
<div class="outline-text-3" id="text-1-15">
</div><div id="outline-container-sec-1-15-1" class="outline-4">
<h4 id="sec-1-15-1"><span class="section-number-4">1.15.1</span> digitizing paper records from home <a href="https://github.com/danielquinn/paperless">https://github.com/danielquinn/paperless</a></h4>
</div>
</div>
<div id="outline-container-sec-1-16" class="outline-3">
<h3 id="sec-1-16"><span class="section-number-3">1.16</span> lrn-languages</h3>
<div class="outline-text-3" id="text-1-16">
</div><div id="outline-container-sec-1-16-1" class="outline-4">
<h4 id="sec-1-16-1"><span class="section-number-4">1.16.1</span> dod's learning resources <a href="http://www.dliflc.edu/products.html">http://www.dliflc.edu/products.html</a></h4>
</div>
<div id="outline-container-sec-1-16-2" class="outline-4">
<h4 id="sec-1-16-2"><span class="section-number-4">1.16.2</span> Katrina says  Pimsleur language learning courses are great</h4>
</div>
<div id="outline-container-sec-1-16-3" class="outline-4">
<h4 id="sec-1-16-3"><span class="section-number-4">1.16.3</span> lrn-french</h4>
<div class="outline-text-4" id="text-1-16-3">
</div><ol class="org-ol"><li><a id="sec-1-16-3-1" name="sec-1-16-3-1"></a>french duolingo<br  /></li>
<li><a id="sec-1-16-3-2" name="sec-1-16-3-2"></a>rosetta stone<br  /></li></ol>
</div>
<div id="outline-container-sec-1-16-4" class="outline-4">
<h4 id="sec-1-16-4"><span class="section-number-4">1.16.4</span> lrn-mandarin-chinese</h4>
</div>
</div>
<div id="outline-container-sec-1-17" class="outline-3">
<h3 id="sec-1-17"><span class="section-number-3">1.17</span> lrn-math</h3>
<div class="outline-text-3" id="text-1-17">
</div><div id="outline-container-sec-1-17-1" class="outline-4">
<h4 id="sec-1-17-1"><span class="section-number-4">1.17.1</span> <a href="http://jeremykun.com/primers/">http://jeremykun.com/primers/</a></h4>
</div>
<div id="outline-container-sec-1-17-2" class="outline-4">
<h4 id="sec-1-17-2"><span class="section-number-4">1.17.2</span> <a href="http://jeffe.cs.illinois.edu/teaching/comptop/">http://jeffe.cs.illinois.edu/teaching/comptop/</a></h4>
</div>
<div id="outline-container-sec-1-17-3" class="outline-4">
<h4 id="sec-1-17-3"><span class="section-number-4">1.17.3</span> <a href="https://www.ocf.berkeley.edu/~abhishek/chicmath.htm">https://www.ocf.berkeley.edu/~abhishek/chicmath.htm</a></h4>
</div>
<div id="outline-container-sec-1-17-4" class="outline-4">
<h4 id="sec-1-17-4"><span class="section-number-4">1.17.4</span> <a href="http://www.johnmyleswhite.com/notebook/2013/03/22/modes-medians-and-means-an-unifying-perspective/">http://www.johnmyleswhite.com/notebook/2013/03/22/modes-medians-and-means-an-unifying-perspective/</a></h4>
</div>
<div id="outline-container-sec-1-17-5" class="outline-4">
<h4 id="sec-1-17-5"><span class="section-number-4">1.17.5</span> visualization of math for pedagogy</h4>
<div class="outline-text-4" id="text-1-17-5">
</div><ol class="org-ol"><li><a id="sec-1-17-5-1" name="sec-1-17-5-1"></a><a href="http://math.stackexchange.com/questions/733754/visually-stunning-math-concepts-which-are-easy-to-explain">http://math.stackexchange.com/questions/733754/visually-stunning-math-concepts-which-are-easy-to-explain</a><br  /></li>
<li><a id="sec-1-17-5-2" name="sec-1-17-5-2"></a><a href="https://en.wikipedia.org/wiki/user:lucasvb/gallery">https://en.wikipedia.org/wiki/user:lucasvb/gallery</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-6" class="outline-4">
<h4 id="sec-1-17-6"><span class="section-number-4">1.17.6</span> Ten lessons I wish I had learned before teaching differential equations" [pdf] <a href="http://hn.premii.com/#/comments/11207183">http://hn.premii.com/#/comments/11207183</a></h4>
</div>
<div id="outline-container-sec-1-17-7" class="outline-4">
<h4 id="sec-1-17-7"><span class="section-number-4">1.17.7</span> peak finding <a href="http://blog.ytotech.com/2015/11/01/findpeaks-in-python/">http://blog.ytotech.com/2015/11/01/findpeaks-in-python/</a></h4>
</div>
<div id="outline-container-sec-1-17-8" class="outline-4">
<h4 id="sec-1-17-8"><span class="section-number-4">1.17.8</span> lrn-calculus</h4>
<div class="outline-text-4" id="text-1-17-8">
</div><ol class="org-ol"><li><a id="sec-1-17-8-1" name="sec-1-17-8-1"></a><a href="https://ocw.mit.edu/resources/res-18-006-calculus-revisited-single-variable-calculus-fall-2010/index.htm">https://ocw.mit.edu/resources/res-18-006-calculus-revisited-single-variable-calculus-fall-2010/index.htm</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-9" class="outline-4">
<h4 id="sec-1-17-9"><span class="section-number-4">1.17.9</span> lrn-bond-graphs</h4>
<div class="outline-text-4" id="text-1-17-9">
</div><ol class="org-ol"><li><a id="sec-1-17-9-1" name="sec-1-17-9-1"></a>look for samantaray 2001 intro in the study/mathematics<br  /></li>
<li><a id="sec-1-17-9-2" name="sec-1-17-9-2"></a>also, intro<a href="http://www.youtube.com/watch?v=p9vz3onmqjs">http://www.youtube.com/watch?v=p9vz3onmqjs</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-10" class="outline-4">
<h4 id="sec-1-17-10"><span class="section-number-4">1.17.10</span> lrn-category-theory</h4>
<div class="outline-text-4" id="text-1-17-10">
</div><ol class="org-ol"><li><a id="sec-1-17-10-1" name="sec-1-17-10-1"></a><a href="http://category-theory.mitpress.mit.edu/">http://category-theory.mitpress.mit.edu/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-11" class="outline-4">
<h4 id="sec-1-17-11"><span class="section-number-4">1.17.11</span> lrn-gradient-descent</h4>
<div class="outline-text-4" id="text-1-17-11">
</div><ol class="org-ol"><li><a id="sec-1-17-11-1" name="sec-1-17-11-1"></a><a href="http://sebastianruder.com/optimizing-gradient-descent/">http://sebastianruder.com/optimizing-gradient-descent/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-12" class="outline-4">
<h4 id="sec-1-17-12"><span class="section-number-4">1.17.12</span> lrn-information-theory</h4>
<div class="outline-text-4" id="text-1-17-12">
</div><ol class="org-ol"><li><a id="sec-1-17-12-1" name="sec-1-17-12-1"></a>read ch4 of dayan and abbott for info theory<br  /></li>
<li><a id="sec-1-17-12-2" name="sec-1-17-12-2"></a>read the original shannon paper<br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-13" class="outline-4">
<h4 id="sec-1-17-13"><span class="section-number-4">1.17.13</span> lrn-lin-alg</h4>
<div class="outline-text-4" id="text-1-17-13">
</div><ol class="org-ol"><li><a id="sec-1-17-13-1" name="sec-1-17-13-1"></a>understand bases, egmodes, vector spaces <a href="http://setosa.io/ev/eigenvectors-and-eigenvalues/">http://setosa.io/ev/eigenvectors-and-eigenvalues/</a><br  /></li>
<li><a id="sec-1-17-13-2" name="sec-1-17-13-2"></a>and how fourier transform can be interpreted as them, write out derivations and definitions as specifically as possible<br  /></li>
<li><a id="sec-1-17-13-3" name="sec-1-17-13-3"></a>print and l2 <a href="http://jeremykun.com/2011/07/25/inner-product-spaces-a-primer/">http://jeremykun.com/2011/07/25/inner-product-spaces-a-primer/</a><br  /></li>
<li><a id="sec-1-17-13-4" name="sec-1-17-13-4"></a>go over colburn's linalg primers<br  /></li>
<li><a id="sec-1-17-13-5" name="sec-1-17-13-5"></a><a href="https://en.m.wikipedia.org/wiki/eigenvalues_and_eigenvectors">eigenvalues and eigenvectors - wikipedia, the free encyclopedia</a><br  /></li>
<li><a id="sec-1-17-13-6" name="sec-1-17-13-6"></a><a href="http://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues">making sense of principal component analysis, eigenvectors &amp; eigenvalues - cross validated</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-14" class="outline-4">
<h4 id="sec-1-17-14"><span class="section-number-4">1.17.14</span> lrn-network-graphs</h4>
<div class="outline-text-4" id="text-1-17-14">
</div><ol class="org-ol"><li><a id="sec-1-17-14-1" name="sec-1-17-14-1"></a><a href="https://gephi.org/">https://gephi.org/</a> viz software<br  /></li>
<li><a id="sec-1-17-14-2" name="sec-1-17-14-2"></a><a href="http://bingweb.binghamton.edu/~sayama/SSIE641/">http://bingweb.binghamton.edu/~sayama/SSIE641/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-17-15" class="outline-4">
<h4 id="sec-1-17-15"><span class="section-number-4">1.17.15</span> lrn-statistics-lrn-stats</h4>
<div class="outline-text-4" id="text-1-17-15">
</div><ol class="org-ol"><li><a id="sec-1-17-15-1" name="sec-1-17-15-1"></a>best way to learn data analysis/stats is&#x2026;to probably do it, including NOT just reading books, but REAL problems or active HOMEWORK "You'll learn faster by doing problems than reading material"<br  /></li>
<li><a id="sec-1-17-15-2" name="sec-1-17-15-2"></a>help<br  /><ol class="org-ol"><li><a id="sec-1-17-15-2-1" name="sec-1-17-15-2-1"></a><a href="https://www.reddit.com/r/statistics/comments/3vjqj2/cant_tell_if_statistics_is_hard_or_if_im_stupid/">https://www.reddit.com/r/statistics/comments/3vjqj2/cant_tell_if_statistics_is_hard_or_if_im_stupid/</a><br  /></li>
<li><a id="sec-1-17-15-2-2" name="sec-1-17-15-2-2"></a><a href="http://www.theanalysisfactor.com/the-statistics-myth-why-statistics-seems-so-hard-to-learn/">http://www.theanalysisfactor.com/the-statistics-myth-why-statistics-seems-so-hard-to-learn/</a><br  /></li>
<li><a id="sec-1-17-15-2-3" name="sec-1-17-15-2-3"></a><img src="http://www.socialresearchmethods.net/kb/Assets/images/stat_t3.gif" alt="stat_t3.gif" /><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-3" name="sec-1-17-15-3"></a><a href="http://emilkirkegaard.dk/understanding_statistics/?app=NHST_subgroup_fallacy">http://emilkirkegaard.dk/understanding_statistics/?app=NHST_subgroup_fallacy</a><br  /></li>
<li><a id="sec-1-17-15-4" name="sec-1-17-15-4"></a>Recommended Self-Study Path for Statistics | Hacker News <a href="https://news.ycombinator.com/item?id=12703032">https://news.ycombinator.com/item?id=12703032</a><br  /></li>
<li><a id="sec-1-17-15-5" name="sec-1-17-15-5"></a>Probability &amp; Statistics | <a href="http://oli.cmu.edu/courses/free-open/statistics-course-details/">http://oli.cmu.edu/courses/free-open/statistics-course-details/</a><br  /></li>
<li><a id="sec-1-17-15-6" name="sec-1-17-15-6"></a>print / write down p value yes/no definitions on wall&#xa0;&#xa0;&#xa0;<span class="tag"><span class="_office">@office</span></span><br  /></li>
<li><a id="sec-1-17-15-7" name="sec-1-17-15-7"></a><a href="https://stats.stackexchange.com/questions/176671/where-to-start-with-statistics-for-an-experienced-developer">https://stats.stackexchange.com/questions/176671/where-to-start-with-statistics-for-an-experienced-developer</a><br  /></li>
<li><a id="sec-1-17-15-8" name="sec-1-17-15-8"></a>go through <a href="http://www.refsmmat.com/statistics/#statistics-done-wrong">http://www.refsmmat.com/statistics/#statistics-done-wrong</a><br  /></li>
<li><a id="sec-1-17-15-9" name="sec-1-17-15-9"></a><a href="https://learnandteachstatistics.wordpress.com/2013/09/09/study-stats-1/">https://learnandteachstatistics.wordpress.com/2013/09/09/study-stats-1/</a><br  /></li>
<li><a id="sec-1-17-15-10" name="sec-1-17-15-10"></a><a href="https://www.coursera.org/specialization/jhudatascience/1/overview">https://www.coursera.org/specialization/jhudatascience/1/overview</a><br  /></li>
<li><a id="sec-1-17-15-11" name="sec-1-17-15-11"></a>dl book: "statistics for spatiotemporal data" - rec'd by lepage?<br  /></li>
<li><a id="sec-1-17-15-12" name="sec-1-17-15-12"></a>always? list assumptions for stat rsh analysis<br  /></li>
<li><a id="sec-1-17-15-13" name="sec-1-17-15-13"></a>program mutual information, be able to explain it<br  /></li>
<li><a id="sec-1-17-15-14" name="sec-1-17-15-14"></a>Stats book: ch5 initially, "random sample X1,&#x2026;,Xn is a SINGLE kind of RV and n observations" "a sample size is the number of observations"<br  /></li>
<li><a id="sec-1-17-15-15" name="sec-1-17-15-15"></a>how not to do it<br  /><ol class="org-ol"><li><a id="sec-1-17-15-15-1" name="sec-1-17-15-15-1"></a><a href="http://academia.stackexchange.com/questions/60393/how-to-argue-against-questionable-research-practices-such-as-p-hacking-and-harki">http://academia.stackexchange.com/questions/60393/how-to-argue-against-questionable-research-practices-such-as-p-hacking-and-harki</a><br  /></li>
<li><a id="sec-1-17-15-15-2" name="sec-1-17-15-15-2"></a><a href="http://www.refsmmat.com/statistics/#statistics-done-wrong">http://www.refsmmat.com/statistics/#statistics-done-wrong</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-16" name="sec-1-17-15-16"></a>books<br  /><ol class="org-ol"><li><a id="sec-1-17-15-16-1" name="sec-1-17-15-16-1"></a>probability: reddit and HN seem to agree that Feller's Introduction to Probability Theory is a very good classic<br  /></li>
<li><a id="sec-1-17-15-16-2" name="sec-1-17-15-16-2"></a><a href="https://news.ycombinator.com/item?id=201913">https://news.ycombinator.com/item?id=201913</a> Casella and Berger's Statistical Inference is then a possible next step?<br  /></li>
<li><a id="sec-1-17-15-16-3" name="sec-1-17-15-16-3"></a>HN's HilbertSpace comment <a href="https://news.ycombinator.com/item?id=955336">https://news.ycombinator.com/item?id=955336</a><br  /></li>
<li><a id="sec-1-17-15-16-4" name="sec-1-17-15-16-4"></a><a href="https://www.reddit.com/r/compsci/comments/299n0y/what_are_good_books_on_statistics/">https://www.reddit.com/r/compsci/comments/299n0y/what_are_good_books_on_statistics/</a><br  /><div class="outline-text-6" id="text-1-17-15-16-4">
<p>
Early in my career, I asked that question. Eventually I got some answers.
</p>

<p>
Broadly usually the 'big bucks' are in things that are new at least in some important sense. To find such things, one recommended approach is to stand "on the shoulders of giants". Then you may still do some original work, but you have one heck of a base. My view is that Moore's law, the Internet, etc. are not nearly fully exploited, that enormous value remains, and the best way to get some of this value is to find a big unsolved problem where a good solution will be very valuable, stand on the shoulders of some giants, do some original work to get some powerful 'secret sauce' for solving the problem (which appears not to be easy to solve otherwise), start a business, please customers, get revenue, grow the business and sell it.
</p>

<p>
Here, however, just what problem, giants, original work, secret sauce are NOT easy to see. Broadly we are trying to see, no, MAKE, the future, and usually that is not easy. While we can see what applications have been made of statistics in the past, what statistics will be applied where in the future is not easy to see.
</p>

<p>
Yes, broadly statistics is highly promising. Or, in 'information technology' we want valuable, new information, are awash in cycles, bytes, bandwidth, infrastructure software, and data, and want to use these to create the information. Here, on appropriate problems, statistics can commonly, easily, totally 'blow away' anything else. The marriage between (A) 'information technology' in business and (B) statistics has yet to be consummated, even to reach to 'going steady' stage, assuming the traditional order of events.
</p>

<p>
For 100 years or so, people have come to statistics from various areas of work. Usually they had some data and some questions. Some of the areas have been educational and psychological testing, experiments and testing in agriculture and medicine, industrial quality control, model building in economics, experimental work in physics and chemistry, investing, attempts to create mathematically based sciences in the social sciences, especially economics, psychology, sociology, and political science. In sociology, old examples would be James Coleman, Pete Rossi (professors of my wife when she got her Ph.D.), Leo Goodman.
</p>

<p>
Likely the best fast, practical path into statistics is via books, courses, etc. intended for students in the social sciences. These students commonly do not have good backgrounds in mathematics. For the mathematical prerequisites, generally can get by, as a start, with just high school first year algebra. With this path can learn about probability distributions, the central limit theorem, the law of large numbers, statistical estimation and confidence intervals, hypothesis testing, cross tabulation, analysis of variance, regression analysis, principle components analysis, and more.
</p>

<p>
For more, statistics is a rock solid part of mathematics, as solid as any part of pure mathematics, e.g., topology, geometry, analysis, algebra, etc. That is, statistics is based solidly on theorems and proofs, sometimes relatively deep ones.
</p>

<p>
Statistics as theorems and proofs is called 'mathematical statistics'. Long standard has been (with TeX markup):
</p>

<p>
Alexander M.\ Mood, Franklin A.\ Graybill, and Duane C.\ Boas, {\it Introduction to the Theory of Statistics, Third Edition,\/} McGraw-Hill, New York.\ \
</p>

<p>
The main prerequisite for this book is just a not very good course in calculus, and the book actually makes not much use of calculus. Mostly all a student will need from calculus is that it can find the area under a curve. Since the book has long been standard, can't really ignore it, but it's ugly. And often, with just calculus, the book doesn't really give solid proofs of the results. E.g., their treatment of sufficient statistics has some nice intuition, but their proof is junk. The subject cries out for a good book, but I'm not trying to write one or waiting for someone else to.
</p>

<p>
Can get some of the flavor of mathematical statistics done with high quality, as mathematics, in, say (with TeX markup):
</p>

<p>
Jean-Ren\'e Barra, {\it Mathematical Basis of Statistics,\/} ISBN 0-12-079240-0, Academic Press, New York.\ \
</p>

<p>
Robert J.\ Serfling, {\it Approximation Theorems of Mathematical Statistics,\/} ISBN 0-471-02403-1, John Wiley and Sons, New York.\ \
</p>

<p>
P.\ Billingsley, {\it Convergence of Probability Measures, 2\raise0.5ex\hbox{ed},\/} ISBN: 0-471-19745-9, John Wiley, New York.\ \
</p>

<p>
R.\ S.\ Lipster and A.\ N.\ Shiryayev, {\it Statistics of Random Processes I, II,} ISBN 0-387-90226-0, Springer-Verlag, New York.\ \
</p>

<p>
However, pursued mathematically, statistics has some relatively advanced prerequisites some of which curiously are not popular in US university mathematics departments.
</p>

<p>
For the prerequisites,
</p>

<p>
High School. Should have had high school first and second year algebra (reasonable facility with algebraic manipulations, the binomial theorem, complex numbers, both of which will see again in important ways), plane geometry (where nearly all the work was proofs &#x2013; first place to learn about proofs), trigonometry (usually assumed in calculus and important in, say, analysis of organ tone harmonics and, thus, the most important example of an infinite dimensional Hilbert space), analytic geometry (especially the conic sections, especially ellipses which definitely will see again), and, if can, solid geometry (for more intuition in three dimensions).
</p>

<p>
College. Need a standard calculus course, not necessarily a very comprehensive or difficult one because will do the subject all over again, maybe two or three times, and more later, WITH the proofs!
</p>

<p>
Then need linear algebra, that is, how to work with data of several dimensions, which is just crucial. The big result is the polar decomposition, and there get to think about ellipses and get to use complex numbers. Also the course is an introduction to functional analysis and Hilbert space. Use any popular book to get started but in the end cover the classic, Halmos, "Finite Dimensional Vector Spaces'. Halmos wrote this when he was an assistant to von Neumann and intended it to be a finite dimensional introduction to Hilbert space (which once von Neumann had to explain to Hilbert) which it is. It also has some multi-linear algebra, of interest to exterior algebra now popular in relativity, but likely for nearly any business applications of statistics for the next several decades can skip that chapter.
</p>

<p>
Then need some advanced calculus. That is a poorly organized, huge, catch-all subject beyond any one course. The usual start is 'baby' Rudin, 'Principles of Mathematical Analysis'. So, that's calculus with the proofs. Warning: The book is severe, succinct, with zero pictures. Have to draw your own pictures in your head. The book is packed solidly with powerful material just awash in important applications from statistics, economics, and engineering to physics, but there is hardly a hint of the applications in the book. I enjoyed the book, but few people will enjoy it or even get through it. Hint: Get a really good teacher! Then for more, popular is Spivak, 'Calculus on Manifolds', mostly because it is short. Actually, it's too short. I prefer Fleming, 'Functions of Several Variables' until get to the exterior algebra chapter at which time, if care, can now get the thin
</p>

<p>
Henri Cartan, {\it Differential Forms,\/} ISBN 0-486-45010-4, Dover, Mineola, NY, 2006.\ \
</p>

<p>
in English.
</p>

<p>
Between Halmos, baby Rudin, and Spivak, you will have covered Harvard's Math 55 with a colorful description at
</p>

<p>
<a href="http://www.american.com/archive/2008/march-april-magazine-co">http://www.american.com/archive/2008/march-april-magazine-co</a>&#x2026;
</p>

<p>
Harvard tries to cover these three for freshman, but in most math departments the material will take you through all or nearly all of a focused undergraduate pure math major.
</p>

<p>
If somewhere take a course in abstract algebra, e.g., with a little group theory, then that might help!
</p>

<p>
Graduate School. Might learn a little more about topology, say, from Simmons, 'Introduction to Topology and Modern Analysis'. So, get good with metric spaces and get started on duality.
</p>

<p>
The next big step is a course in measure theory and functional analysis. The Simmons work will help. Baby Rudin will be crucial; Halmos is recommended. So, with measure theory, do calculus over again and in a very different and much more powerful way and a way just crucial, even central, for mathematical approaches to statistics. The functional analysis will concentrate on representation theorems, the Radon-Nikodym theorem, and Hilbert and Banach spaces. Long popular, from Stanford and sometimes aimed at statistics students, is Royden, 'Real Analysis'. It's gorgeous. Should also read the real half of Rudin, 'Real and Complex Analysis'; it's a few steps up in difficulty from baby Rudin. Again, hint: Get a good course from a good teacher who can get you over the material without getting stuck. Then go back and study the material 2-3 more times, apply it, do some original research in it, and finally begin to understand it.
</p>

<p>
We're talking high, top, center crown jewels of civilization here; the stuff is of just awesome power; my view is that it is, for the rest of this century, one of the main pillars of increases in economic productivity via the exploitation of Moore's law; on 'what to program', computer science is stuck and this material is the most promising way forward; as a famous restaurant owner once said about some Morey St. Denis, "you won't find better".
</p>

<p>
Now are ready for probability. I recommend:
</p>

<p>
Leo Breiman, {\it Probability,\/} ISBN 0-89871-296-3, SIAM, Philadelphia.\ \
</p>

<p>
M.\ Lo\`eve, {\it Probability Theory, I and II, 4th Edition,\/} Springer-Verlag, New York.\ \
</p>

<p>
Kai Lai Chung, {\it A Course in Probability Theory, Second Edition,\/} ISBN 0-12-174650-X, Academic Press, New York.\ \
</p>

<p>
Jacques Neveu, {\it Mathematical Foundations of the Calculus of Probability,\/} Holden-Day, San Francisco.\ \
</p>

<p>
Neveu is succinct, gorgeous, but not easy. This material is NOT popular in US departments of mathematics. At Princeton, see Cinlar.
</p>

<p>
Then should make some progress with stochastic processes: The big book is Gihman and and Skorohod, right, in three volumes, but mostly people settle for shorter treatments. Whatever, should learn about Poisson processes, Markov processes (discrete time, finite state space is enough to get started), Brownian motion, and martingales. Might also learn about second order stationary processes. A good course in stochastic processes is NOT easy to find, especially in mathematics departments.
</p>

<p>
Now are ready to attack statistics mathematically! I don't know of a good, single 'mathematical statistics' book at this level. Instead, there are many books &#x2013; I gave some above &#x2013; and then the journals. Thankfully, the field is relatively close to applications; so can take a practical problem and concentrate on what is relevant to it. One of my papers was some new work, at this level, in mathematical statistics for a problem in practical computing and computer science. The computer science community struggled terribly with the mathematics. So, it was some progress in computer science that community will have to struggle to understand.
</p>

<p>
One approach to work in computing is just to try things, that is, just to throw things against the wall and see if they appear to stick. Or, maybe the truth of the situation really is a simple statistical model. Likely that model will fit the data well. So, try many simple statistical models. We use these models mostly ignoring the mathematical assumptions; mostly we are proceeding 'heuristically', that is, with guessing. If any of the models fit well, then they can be considered candidates for the truth. So, are throwing things against the wall to see if they fit. This approach also called 'data mining'.
</p>

<p>
Problems:
</p>

<p>
(1) Will be quite limited in what statistical models can use. That is, will be drawing from a cookbook instead of being a real chef who can create good, new dishes appropriate for the available ingredients and customers!
</p>

<p>
(2) Don't have much, e.g., have not proceeded mathematically where from the deductive logic of assumptions and proofs actually know in advance some good things about the results. Something like breaking into a pharmacy, mixing up a lot of pills, taking them, and seeing if feel better! Uh, I'll pass and let you do that without me!
</p>

<p>
(3) May have gone through a lot of computer time in an 'exponential, combinatorial explosion' of efforts throwing against the wall.
</p>

<p>
(4) Have ignored a LOT in statistics that can add to what know about the results.
</p>

<p>
(5) Will be tempted to conclude have have found 'causality' but will likely not have.
</p>

<p>
(6) Will be tempted to conclude that have a model that predicts, but that is on shaky ground and risky and needs more work.
</p>

<p>
Applied to important problems, this approach can be dangerous.
</p>

<p>
There are not many healthy statistics departments. Much of the career interest is in biostatistics, especially related to FDA rules.
</p>

<p>
It appears that among the top statistics departments are Berkeley and UNC. Since Breiman and Brillinger are at Berkeley and since Stanford, long good in statistics, is not far away, if I were looking for a Ph.D. in statistics then I'd pick Berkeley.
</p>

<p>
There is a general problem getting a 'job' in a technical field and likely also with statistics. The assumption in US business is still as in factories 150 years ago: The supervisor knows more than the subordinate; the subordinate is supposed just to add common labor to what the supervisor says. In particular job descriptions are written by the supervisors, not the subordinates!
</p>

<p>
Well, there are nearly no supervisors in US business who have even as much as a weak little hollow hint of a tiny clue about the material described here. So, won't need that material to qualify for the job descriptions. Moreover, if actually know such material and let that fact leak out, then will likely not make it past the first level HR English major phone screen person who will tremble and conclude that you are not like the employees they have! If you do get hired and someone in your management chain discovers that you have used some mathematics they don't understand, you might be on the way out the door, especially is your work was valuable for the company!
</p>

<p>
Of course, the solution is to find a valuable application and start your own business. While maybe biomedical venture capital can understand crucial, core technical content, in information technology venture capital, likely you will be trying to explain this stuff to, say, history majors who worked in fund raising, marketing, general management, or financial analysis or have a background in just relatively elementary parts of computing. Just will NOT find more than six people, maybe not more than zero people, in US venture capital who can work the exercises in Royden or explain the strong law of large numbers. Sorry 'bout that! So, if you explain that the value of your venture is the powerful material in your 'secret sauce', then you will be regarded as a kook, far outside the mainstream of venture funded entrepreneurs, discarded, maybe even laughed at. As it is, some of the venture people are making money now, and the rest just want to be more like the ones who are making money. Looking for anything really new, powerful, and valuable is just NOT in the picture.
</p>

<p>
So, once you have some results in users, customers, revenue, etc., then maybe you can get some venture funding; just why at that point, owning 100% of the business, you would take venture funding, a Board that can fire you, etc. is less clear! Or venture funding is not for everyone! Or venture firms prefer to give money to people who don't need it!
</p>

<p>
For the real power of the 'secret sauce', you have just to keep that a secret!
</p>

<p>
Once mathematicians have yachts, at the venture firms math will be to info tech like biochem is to biotech. In the meanwhile note that a valuable application of statistics can put you on the Forbes 400 where there are not many people! Generally if you are making a valuable application of advanced or new statistics, then you will not know many people who understand what you are doing. Or, if lots of people understood it, then it wouldn't be valuable!
</p>
</div>
</li>

<li><a id="sec-1-17-15-16-5" name="sec-1-17-15-16-5"></a>one of, if not the best recommended books on Bayesian? "jaynes' Prob theory: the logic of sci"<br  /></li>
<li><a id="sec-1-17-15-16-6" name="sec-1-17-15-16-6"></a><a href="https://www.reddit.com/r/statistics/comments/2le25z/what_books_or_papers_are_must_reads_for_every/">https://www.reddit.com/r/statistics/comments/2le25z/what_books_or_papers_are_must_reads_for_every/</a><br  /></li>
<li><a id="sec-1-17-15-16-7" name="sec-1-17-15-16-7"></a><a href="https://www.reddit.com/r/statistics/comments/1bun3v/ms_in_stats_with_an_applied_background/c9a8i8z">https://www.reddit.com/r/statistics/comments/1bun3v/ms_in_stats_with_an_applied_background/c9a8i8z</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-17" name="sec-1-17-15-17"></a>p-values<br  /><ol class="org-ol"><li><a id="sec-1-17-15-17-1" name="sec-1-17-15-17-1"></a>friends don't let friends calculate p-values <a href="http://www.scottbot.net/hial/?p=24697">http://www.scottbot.net/hial/?p=24697</a><br  /></li>
<li><a id="sec-1-17-15-17-2" name="sec-1-17-15-17-2"></a>table of alpha and beta errors in experiments, from table 6.2 of matlab for neuroscientists<br  /><div class="outline-text-6" id="text-1-17-15-17-2">
<ul class="org-ul">
<li><b>* effect exists (h0 false) effect doesn't exist (h0 true)*</b>
</li>
<li><b><b>we conclude it exists</b></b> discovery of effect alpha (false rejection of h0)
</li>
<li><b><b>we conclude it doesn't</b></b> beta (false retention of f0) failure to reject the null hypothesis
</li>
</ul>
</div>
</li>

<li><a id="sec-1-17-15-17-3" name="sec-1-17-15-17-3"></a>if think understand them, go through <a href="http://www.refsmmat.com/statistics/#statistics-done-wrong">http://www.refsmmat.com/statistics/#statistics-done-wrong</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-18" name="sec-1-17-15-18"></a>arima<br  /><ol class="org-ol"><li><a id="sec-1-17-15-18-1" name="sec-1-17-15-18-1"></a>identifying the numbers of ar or ma <a href="http://people.duke.edu/~rnau/411arim3.htm">http://people.duke.edu/~rnau/411arim3.htm</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-19" name="sec-1-17-15-19"></a>pca<br  /><ol class="org-ol"><li><a id="sec-1-17-15-19-1" name="sec-1-17-15-19-1"></a><a href="http://georgemdallas.wordpress.com/2013/10/30/principal-component-analysis-4-dummies-eigenvectors-eigenvalues-and-dimension-reduction/">http://georgemdallas.wordpress.com/2013/10/30/principal-component-analysis-4-dummies-eigenvectors-eigenvalues-and-dimension-reduction/</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-20" name="sec-1-17-15-20"></a>anova<br  /></li>
<li><a id="sec-1-17-15-21" name="sec-1-17-15-21"></a><a href="https://www.reddit.com/r/statistics/comments/2le25z/what_books_or_papers_are_must_reads_for_every/">https://www.reddit.com/r/statistics/comments/2le25z/what_books_or_papers_are_must_reads_for_every/</a><br  /></li>
<li><a id="sec-1-17-15-22" name="sec-1-17-15-22"></a>misleading statistics<br  /><ol class="org-ol"><li><a id="sec-1-17-15-22-1" name="sec-1-17-15-22-1"></a>Misleading modelling: overfitting, cross-validation, and the bias-variance trade-off <a href="https://blog.cambridgecoding.com/2016/03/24/misleading-modelling-overfitting-cross-validation-and-the-bias-variance-trade-off/">https://blog.cambridgecoding.com/2016/03/24/misleading-modelling-overfitting-cross-validation-and-the-bias-variance-trade-off/</a><br  /></li>
<li><a id="sec-1-17-15-22-2" name="sec-1-17-15-22-2"></a><a href="http://hn.premii.com/#/comments/11369790">Cambridge professor on how to stop being manipulated by misleading statistics</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-23" name="sec-1-17-15-23"></a>lrn-bayes<br  /><ol class="org-ol"><li><a id="sec-1-17-15-23-1" name="sec-1-17-15-23-1"></a><a href="http://hn.premii.com/#/comments/11613877">http://hn.premii.com/#/comments/11613877</a><br  /></li>
<li><a id="sec-1-17-15-23-2" name="sec-1-17-15-23-2"></a><a href="https://arbital.com/p/bayes_rule/?l=1zq">https://arbital.com/p/bayes_rule/?l=1zq</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-24" name="sec-1-17-15-24"></a>lrn-machine-learning-artificial-intelligence<br  /><ol class="org-ol"><li><a id="sec-1-17-15-24-1" name="sec-1-17-15-24-1"></a><a href="http://www.statsblogs.com/2014/12/30/machine-learning-books-suggested-by-michael-i-jordan-from-berkeley/">Machine Learning books Suggested by Michael I. Jordan from Berkeley | StatsBlogs.com | All About Statistics</a><br  /></li>
<li><a id="sec-1-17-15-24-2" name="sec-1-17-15-24-2"></a><a href="http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/">http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/</a><br  /></li>
<li><a id="sec-1-17-15-24-3" name="sec-1-17-15-24-3"></a>somehow go through elements of statistical learning<br  /></li>
<li><a id="sec-1-17-15-24-4" name="sec-1-17-15-24-4"></a><a href="http://hn.premii.com/#/comments/12713056">http://hn.premii.com/#/comments/12713056</a><br  /></li>
<li><a id="sec-1-17-15-24-5" name="sec-1-17-15-24-5"></a><a href="http://ghyslain.me/bookshelf">http://ghyslain.me/bookshelf</a><br  /></li>
<li><a id="sec-1-17-15-24-6" name="sec-1-17-15-24-6"></a><a href="https://news.ycombinator.com/item?id=14764700">https://news.ycombinator.com/item?id=14764700</a> <a href="https://unsupervisedmethods.com/my-curated-list-of-ai-and-machine-learning-resources-from-around-the-web-9a97823b8524">https://unsupervisedmethods.com/my-curated-list-of-ai-and-machine-learning-resources-from-around-the-web-9a97823b8524</a><br  /></li></ol>
</li>
<li><a id="sec-1-17-15-25" name="sec-1-17-15-25"></a>good books for data science etc <a href="http://multithreaded.stitchfix.com/blog/2016/06/09/ds-books/">http://multithreaded.stitchfix.com/blog/2016/06/09/ds-books/</a><br  /></li>
<li><a id="sec-1-17-15-26" name="sec-1-17-15-26"></a><a href="https://brownmath.com/swt/">https://brownmath.com/swt/</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-18" class="outline-3">
<h3 id="sec-1-18"><span class="section-number-3">1.18</span> lrn-nanoscience-lrn-nanotech</h3>
<div class="outline-text-3" id="text-1-18">
</div><div id="outline-container-sec-1-18-1" class="outline-4">
<h4 id="sec-1-18-1"><span class="section-number-4">1.18.1</span> Nanodoc software</h4>
</div>
</div>
<div id="outline-container-sec-1-19" class="outline-3">
<h3 id="sec-1-19"><span class="section-number-3">1.19</span> lrn-neural-networks</h3>
<div class="outline-text-3" id="text-1-19">
</div><div id="outline-container-sec-1-19-1" class="outline-4">
<h4 id="sec-1-19-1"><span class="section-number-4">1.19.1</span> <a href="http://colah.github.io/posts/2014-03-nn-manifolds-topology/">http://colah.github.io/posts/2014-03-nn-manifolds-topology/</a></h4>
</div>
<div id="outline-container-sec-1-19-2" class="outline-4">
<h4 id="sec-1-19-2"><span class="section-number-4">1.19.2</span> <a href="ftp://ftp.sas.com/pub/neural/FAQ.html">ftp://ftp.sas.com/pub/neural/FAQ.html</a></h4>
</div>
</div>
<div id="outline-container-sec-1-20" class="outline-3">
<h3 id="sec-1-20"><span class="section-number-3">1.20</span> lrn-NS lrn-neuroscience</h3>
<div class="outline-text-3" id="text-1-20">
</div><div id="outline-container-sec-1-20-1" class="outline-4">
<h4 id="sec-1-20-1"><span class="section-number-4">1.20.1</span> what is known about coding in neurons? prob have to get into specific region</h4>
</div>
<div id="outline-container-sec-1-20-2" class="outline-4">
<h4 id="sec-1-20-2"><span class="section-number-4">1.20.2</span> maybe classify different ways of transfering information between them?</h4>
</div>
<div id="outline-container-sec-1-20-3" class="outline-4">
<h4 id="sec-1-20-3"><span class="section-number-4">1.20.3</span> sawtooth beta?????? wtf is up with these waveforms</h4>
</div>
<div id="outline-container-sec-1-20-4" class="outline-4">
<h4 id="sec-1-20-4"><span class="section-number-4">1.20.4</span> if learn stuff about thal, can maybe help with parkinson's?</h4>
</div>
<div id="outline-container-sec-1-20-5" class="outline-4">
<h4 id="sec-1-20-5"><span class="section-number-4">1.20.5</span> rlnshp b/w D1 DA rec b/w epi &amp; park's</h4>
</div>
<div id="outline-container-sec-1-20-6" class="outline-4">
<h4 id="sec-1-20-6"><span class="section-number-4">1.20.6</span> inactivation variables</h4>
<div class="outline-text-4" id="text-1-20-6">
</div><ol class="org-ol"><li><a id="sec-1-20-6-1" name="sec-1-20-6-1"></a>h is not so much an inactivation variable (i.e. level of inactivation) as much as a DE-inactivation variable (where completely inactivated is 0 NOT 1!!!!!)<br  /><ol class="org-ol"><li><a id="sec-1-20-6-1-1" name="sec-1-20-6-1-1"></a>"Recall that h is the probability that a Na channel is NOT inactivated", p. 49, Ionic Channels of Excitable Membranes<br  /></li>
<li><a id="sec-1-20-6-1-2" name="sec-1-20-6-1-2"></a>another way of thinking: h is prob that the "inactivation gate" is OPEN, allowing current to flow &#x2013; so if it's 0, then the gate is closed<br  /></li>
<li><a id="sec-1-20-6-1-3" name="sec-1-20-6-1-3"></a>NOT inactivated = the inactivation gate is OPEN, omg<br  /></li>
<li><a id="sec-1-20-6-1-4" name="sec-1-20-6-1-4"></a>see <a href="http://palgrave.nature.com/neuro/journal/v3/n11s/full/nn1100_1165.html">http://palgrave.nature.com/neuro/journal/v3/n11s/full/nn1100_1165.html</a> and "Ionic Channels of Excitable Membranes" for why the original HH paper theory that it's an inactivating PARTICLE has been deprecated for theory of an inactivating GATE<br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-20-7" class="outline-4">
<h4 id="sec-1-20-7"><span class="section-number-4">1.20.7</span> lrn-fmri</h4>
<div class="outline-text-4" id="text-1-20-7">
</div><ol class="org-ol"><li><a id="sec-1-20-7-1" name="sec-1-20-7-1"></a>fmri methods wiki <a href="http://www.fmrimethods.org/index.php/Main_Page">http://www.fmrimethods.org/index.php/Main_Page</a><br  /></li>
<li><a id="sec-1-20-7-2" name="sec-1-20-7-2"></a>cwatson's notes on fMRI<br  /><div class="outline-text-5" id="text-1-20-7-2">
<ul class="org-ul">
<li>look at Friston &amp; Dolan, NeuroImage, 2010 (Volume 52, pp 752-765), and the references therein
</li>
<li>also look at Friston's Dynamic Causal Modeling
</li>
<li>first paper for that was Neuroimage, 2003
<ul class="org-ul">
<li>although that isn't quite like the modeling we did in, e.g. cn510
</li>
</ul>
</li>
<li>also I think there's a paper from 2003, with Friston and Breakspear as two of the authors, I can't remember the journal
</li>
<li>a very recent one (that I haven't read) is Hellyer et al., J Neuroscience, 2014 (Vol. 34, Issue 2)
</li>
<li>and you might want to check out Deco et al., J Neurosci, 2013 (Vol. 33, Issue 27)
</li>
</ul>
</div>
</li></ol>
</div>

<div id="outline-container-sec-1-20-8" class="outline-4">
<h4 id="sec-1-20-8"><span class="section-number-4">1.20.8</span> lrn-iit</h4>
<div class="outline-text-4" id="text-1-20-8">
</div><ol class="org-ol"><li><a id="sec-1-20-8-1" name="sec-1-20-8-1"></a><a href="http://integratedinformationtheory.org/">http://integratedinformationtheory.org/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-20-9" class="outline-4">
<h4 id="sec-1-20-9"><span class="section-number-4">1.20.9</span> lrn-holonomic-brain-theory</h4>
<div class="outline-text-4" id="text-1-20-9">
</div><ol class="org-ol"><li><a id="sec-1-20-9-0-1" name="sec-1-20-9-0-1"></a><a href="http://en.wikipedia.org/wiki/Holonomic_brain_theory">http://en.wikipedia.org/wiki/Holonomic_brain_theory</a><br  /></li>
<li><a id="sec-1-20-9-0-2" name="sec-1-20-9-0-2"></a><a href="http://www.scholarpedia.org/article/Holonomic_Brain_Theory">http://www.scholarpedia.org/article/Holonomic_Brain_Theory</a> (entry written by Karl Pribram, 2007)<br  /></li>
<li><a id="sec-1-20-9-0-3" name="sec-1-20-9-0-3"></a>Comparison between Karl Pribram's "Holographic Brain Theory" andmore conventional models of neuronal computation:<br  /></li>
<li><a id="sec-1-20-9-0-4" name="sec-1-20-9-0-4"></a><a href="http://www.acsa2000.net/bcngroup/jponkp/">http://www.acsa2000.net/bcngroup/jponkp/</a><br  /></li>
<li><a id="sec-1-20-9-0-5" name="sec-1-20-9-0-5"></a>Karl Pribram on radio show "New Dimensions" (2hr, good nontechnical intro w/ historical perspective)<br  /><ol class="org-ol"><li><a id="sec-1-20-9-0-5-1" name="sec-1-20-9-0-5-1"></a>Part 1: <a href="http://www.youtube.com/watch?v=2-ROSF7cE48">http://www.youtube.com/watch?v=2-ROSF7cE48</a><br  /></li>
<li><a id="sec-1-20-9-0-5-2" name="sec-1-20-9-0-5-2"></a>Part 2: <a href="http://www.youtube.com/watch?v=XqbG4IKS4vQ&feature=relmfu">http://www.youtube.com/watch?v=XqbG4IKS4vQ&feature=relmfu</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-20-10" class="outline-4">
<h4 id="sec-1-20-10"><span class="section-number-4">1.20.10</span> lrn-neuro-anatomy (lrn-anatomy) lrn-neuroanatomy</h4>
<div class="outline-text-4" id="text-1-20-10">
</div><ol class="org-ol"><li><a id="sec-1-20-10-1" name="sec-1-20-10-1"></a>lrn sagittal sections of the brain<br  /></li>
<li><a id="sec-1-20-10-2" name="sec-1-20-10-2"></a><a href="https://ocw.mit.edu/courses/brain-and-cognitive-sciences/9-913-a-intensive-neuroanatomy-january-iap-2002/index.htm">https://ocw.mit.edu/courses/brain-and-cognitive-sciences/9-913-a-intensive-neuroanatomy-january-iap-2002/index.htm</a><br  /></li>
<li><a id="sec-1-20-10-3" name="sec-1-20-10-3"></a>memorize Brodmann's Areas and their function<br  /></li>
<li><a id="sec-1-20-10-4" name="sec-1-20-10-4"></a>go through Purves' brain anatomy sections, including rear as if learning language<br  /></li>
<li><a id="sec-1-20-10-5" name="sec-1-20-10-5"></a>that functional anatomy book jason recommended<br  /></li>
<li><a id="sec-1-20-10-6" name="sec-1-20-10-6"></a>From Jason's "Topics to Research" Gdoc, maybe available at <a href="https://docs.google.com/document/d/1-voDgaDehnA8F810GJKhEDmnpLIRQcDodF1A_iniaUY/edit">https://docs.google.com/document/d/1-voDgaDehnA8F810GJKhEDmnpLIRQcDodF1A_iniaUY/edit</a> Structural Information Resources:<br  /><ol class="org-ol"><li><a id="sec-1-20-10-6-1" name="sec-1-20-10-6-1"></a>Allen Brain Atlas (Mouse, Human): <a href="http://www.brain-map.org/">http://www.brain-map.org/</a> (excellent tools)<br  /></li>
<li><a id="sec-1-20-10-6-2" name="sec-1-20-10-6-2"></a>Scalable Brain Atlas (is in INCF): <a href="http://scalablebrainatlas.incf.org/main/index.php">http://scalablebrainatlas.incf.org/main/index.php</a><br  /></li>
<li><a id="sec-1-20-10-6-3" name="sec-1-20-10-6-3"></a>INDI (International Neuroimaging Data-Sharing Initiative; is in INCF): <a href="http://fcon_1000.projects.nitrc.org/index.html">http://fcon_1000.projects.nitrc.org/index.html</a><br  /></li>
<li><a id="sec-1-20-10-6-4" name="sec-1-20-10-6-4"></a>BiND (Bipolar Disorder Neuroimaging Database): <a href="https://sites.google.com/site/bipolardatabase/">https://sites.google.com/site/bipolardatabase/</a><br  /></li>
<li><a id="sec-1-20-10-6-5" name="sec-1-20-10-6-5"></a>Referenced in Neurocognitive Networks @ Scholarpedia: <a href="http://www.scholarpedia.org/article/Neurocognitive_networks">http://www.scholarpedia.org/article/Neurocognitive_networks</a><br  /></li>
<li><a id="sec-1-20-10-6-6" name="sec-1-20-10-6-6"></a>The Brain Architecture Management System: <a href="http://brancusi.usc.edu/bkms/">http://brancusi.usc.edu/bkms/</a><br  /></li>
<li><a id="sec-1-20-10-6-7" name="sec-1-20-10-6-7"></a>Collations of Connectivity data on the Macaque brain: <a href="http://cocomac.org/home.asp">http://cocomac.org/home.asp</a><br  /></li>
<li><a id="sec-1-20-10-6-8" name="sec-1-20-10-6-8"></a>Connectome wiki: <a href="http://neurolex.org/wiki/Category:Resource:Connectome_Wiki">http://neurolex.org/wiki/Category:Resource:Connectome_Wiki</a><br  /></li></ol>
</li>
<li><a id="sec-1-20-10-7" name="sec-1-20-10-7"></a>neuroanatomy lessons online <a href="http://neuroscience.uth.tmc.edu/toc.htm">http://neuroscience.uth.tmc.edu/toc.htm</a><br  /></li>
<li><a id="sec-1-20-10-8" name="sec-1-20-10-8"></a><a href="http://headneckbrainspine.com/Neuroanatomy-modules.php">http://headneckbrainspine.com/Neuroanatomy-modules.php</a><br  /></li>
<li><a id="sec-1-20-10-9" name="sec-1-20-10-9"></a>lrn-thal-anatomy<br  /><ol class="org-ol"><li><a id="sec-1-20-10-9-1" name="sec-1-20-10-9-1"></a>read medical campus thal book to study its anatomy<br  /></li>
<li><a id="sec-1-20-10-9-2" name="sec-1-20-10-9-2"></a>p5d1m8<sub>20160111</sub>, brown: "parabrachial nucleus is like a highway into the thal"<br  /></li>
<li><a id="sec-1-20-10-9-3" name="sec-1-20-10-9-3"></a>The entire thalamus has diffuse brainstem reticulated input<br  /></li>
<li><a id="sec-1-20-10-9-4" name="sec-1-20-10-9-4"></a><a href="http://www.fountia.com/thalamus/">http://www.fountia.com/thalamus/</a><br  /></li>
<li><a id="sec-1-20-10-9-5" name="sec-1-20-10-9-5"></a>"thal to striatum def goes to cholin INs"<br  /></li>
<li><a id="sec-1-20-10-9-6" name="sec-1-20-10-9-6"></a>parafunicular thal is cholin input FROM thal into putamen?<br  /></li>
<li><a id="sec-1-20-10-9-7" name="sec-1-20-10-9-7"></a>thal and hcn and Kleak<br  /><ol class="org-ol"><li><a id="sec-1-20-10-9-7-1" name="sec-1-20-10-9-7-1"></a>(Meuth 2006, p. 1525) says "All known pacemaker channels (HCN1-4), TASK1-3 channels, and at least five other members of the K2P channel family (TREK1, TREK2, TRAAK, THIK1, THIK2) are expressed in rat dLGN. 2) the dominant isoforms, HCN2 and TASK3, are coexpressed in TC neurons."<br  /></li>
<li><a id="sec-1-20-10-9-7-2" name="sec-1-20-10-9-7-2"></a>(Ying 2006, abstract) says "The principal source of the IH current in [ventrobasal complex thalamocortical relay] neurons is the hyperpolarization-activated cyclic nucleotide-gated (HCN) type 2 channel."<br  /></li>
<li><a id="sec-1-20-10-9-7-3" name="sec-1-20-10-9-7-3"></a>(Chen 2006, p. 3874) says "In thalamocortical neurons, HCN1 is barely detectable and the slower HCN2 and HCN4 isoforms predominate (Notomi and Shigemoto 2004; Santoro et al. 2000) with the majority of the current (80 –90%) attributed to HCN2 (Ludwig et al. 2003)."<br  /></li></ol>
</li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-20-11" class="outline-4">
<h4 id="sec-1-20-11"><span class="section-number-4">1.20.11</span> lrn-neuro-methods</h4>
<div class="outline-text-4" id="text-1-20-11">
</div><ol class="org-ol"><li><a id="sec-1-20-11-1" name="sec-1-20-11-1"></a>compile list of NS methods, bycategory<br  /><ol class="org-ol"><li><a id="sec-1-20-11-1-1" name="sec-1-20-11-1-1"></a>a very old ephys review calls LFP, or "micro EEG", as most similar to electro-"histology"<br  /></li></ol>
</li>
<li><a id="sec-1-20-11-2" name="sec-1-20-11-2"></a>technologies<br  /><ol class="org-ol"><li><a id="sec-1-20-11-2-1" name="sec-1-20-11-2-1"></a>electrode types (tons)<br  /></li>
<li><a id="sec-1-20-11-2-2" name="sec-1-20-11-2-2"></a>cochlear implant types<br  /></li>
<li><a id="sec-1-20-11-2-3" name="sec-1-20-11-2-3"></a>neuroprosthetic types<br  /></li>
<li><a id="sec-1-20-11-2-4" name="sec-1-20-11-2-4"></a>are there any major catalogues of these?<br  /></li>
<li><a id="sec-1-20-11-2-5" name="sec-1-20-11-2-5"></a>emery says fronto has no anatomical connectivity to parietal, only goes through thal<br  /></li>
<li><a id="sec-1-20-11-2-6" name="sec-1-20-11-2-6"></a>emery agrees human thal has 1 IN for every ~5 TCs, inside nuclei (i.e. not including RE)<br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-20-12" class="outline-4">
<h4 id="sec-1-20-12"><span class="section-number-4">1.20.12</span> lrn-neuro-rhythms</h4>
<div class="outline-text-4" id="text-1-20-12">
</div><ol class="org-ol"><li><a id="sec-1-20-12-1" name="sec-1-20-12-1"></a>primer on brainwaves <a href="https://neuroscience.stanford.edu/news/getting-brain-waves-history-and-resources">https://neuroscience.stanford.edu/news/getting-brain-waves-history-and-resources</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-20-13" class="outline-4">
<h4 id="sec-1-20-13"><span class="section-number-4">1.20.13</span> lrn-nootropics</h4>
<div class="outline-text-4" id="text-1-20-13">
</div><ol class="org-ol"><li><a id="sec-1-20-13-1" name="sec-1-20-13-1"></a><a href="https://www.gwern.net/Nootropics">https://www.gwern.net/Nootropics</a><br  /></li>
<li><a id="sec-1-20-13-2" name="sec-1-20-13-2"></a><a href="https://www.reddit.com/r/nootropics/wiki/beginners">https://www.reddit.com/r/nootropics/wiki/beginners</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-20-14" class="outline-4">
<h4 id="sec-1-20-14"><span class="section-number-4">1.20.14</span> lrn-compu-ns</h4>
<div class="outline-text-4" id="text-1-20-14">
</div><ol class="org-ol"><li><a id="sec-1-20-14-1" name="sec-1-20-14-1"></a><a href="http://neuronaldynamics.epfl.ch/online/index.html">http://neuronaldynamics.epfl.ch/online/index.html</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-21" class="outline-3">
<h3 id="sec-1-21"><span class="section-number-3">1.21</span> lrn-philosophy</h3>
<div class="outline-text-3" id="text-1-21">
</div><div id="outline-container-sec-1-21-1" class="outline-4">
<h4 id="sec-1-21-1"><span class="section-number-4">1.21.1</span> lrn-logic</h4>
<div class="outline-text-4" id="text-1-21-1">
</div><ol class="org-ol"><li><a id="sec-1-21-1-1" name="sec-1-21-1-1"></a><a href="http://www.reddit.com/r/philosophy/comments/2jbezu/teach_yourself_logic_a_study_guide_version_120/][teach">http://www.reddit.com/r/philosophy/comments/2jbezu/teach_yourself_logic_a_study_guide_version_120/][teach</a> yourself logic: a study guide (version 12.0)]]<br  /></li>
<li><a id="sec-1-21-1-2" name="sec-1-21-1-2"></a>[[Teach Yourself Logic 2016: A Study Guide [pdf] <a href="http://hn.premii.com/#/comments/10819702][Teach">http://hn.premii.com/#/comments/10819702][Teach</a> Yourself Logic 2016: A Study Guide [pdf]]]<br  /></li>
<li><a id="sec-1-21-1-3" name="sec-1-21-1-3"></a><a href="https://www.reddit.com/r/philosophy/comments/4dj3yo/when_fallacy_sites_and_logic_textbooks_get_it/">When Fallacy Sites and Logic Textbooks Get It Wrong</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-22" class="outline-3">
<h3 id="sec-1-22"><span class="section-number-3">1.22</span> lrn-physics</h3>
<div class="outline-text-3" id="text-1-22">
</div><div id="outline-container-sec-1-22-1" class="outline-4">
<h4 id="sec-1-22-1"><span class="section-number-4">1.22.1</span> accumulate <a href="http://physics.stackexchange.com/questions/6157/list-of-freely-available-physics-books">http://physics.stackexchange.com/questions/6157/list-of-freely-available-physics-books</a>?</h4>
</div>
<div id="outline-container-sec-1-22-2" class="outline-4">
<h4 id="sec-1-22-2"><span class="section-number-4">1.22.2</span> go back over krane's intro (nick james has krane)</h4>
</div>
<div id="outline-container-sec-1-22-3" class="outline-4">
<h4 id="sec-1-22-3"><span class="section-number-4">1.22.3</span> study general relativity, like einstein's book?</h4>
</div>
<div id="outline-container-sec-1-22-4" class="outline-4">
<h4 id="sec-1-22-4"><span class="section-number-4">1.22.4</span> Could warp across space-time by generating points of huge gravity, from either huge masses or masses from energy?</h4>
</div>
<div id="outline-container-sec-1-22-5" class="outline-4">
<h4 id="sec-1-22-5"><span class="section-number-4">1.22.5</span> books (look at this e-library) <a href="http://publishing.cdlib.org/ucpressebooks/view?docId=ft4t1nb2gv;brand=ucpress">http://publishing.cdlib.org/ucpressebooks/view?docId=ft4t1nb2gv;brand=ucpress</a></h4>
</div>
<div id="outline-container-sec-1-22-6" class="outline-4">
<h4 id="sec-1-22-6"><span class="section-number-4">1.22.6</span> why momentum works <a href="http://distill.pub/2017/momentum/">http://distill.pub/2017/momentum/</a></h4>
</div>
<div id="outline-container-sec-1-22-7" class="outline-4">
<h4 id="sec-1-22-7"><span class="section-number-4">1.22.7</span> <a href="https://www.lucify.com/inside-einsteins-head/">https://www.lucify.com/inside-einsteins-head/</a></h4>
</div>
<div id="outline-container-sec-1-22-8" class="outline-4">
<h4 id="sec-1-22-8"><span class="section-number-4">1.22.8</span> <a href="https://news.ycombinator.com/item?id=16151853">https://news.ycombinator.com/item?id=16151853</a></h4>
</div>
</div>
<div id="outline-container-sec-1-23" class="outline-3">
<h3 id="sec-1-23"><span class="section-number-3">1.23</span> lrn-politics</h3>
<div class="outline-text-3" id="text-1-23">
</div><div id="outline-container-sec-1-23-1" class="outline-4">
<h4 id="sec-1-23-1"><span class="section-number-4">1.23.1</span> find news source for local political news, pay attn to local politics</h4>
</div>
<div id="outline-container-sec-1-23-2" class="outline-4">
<h4 id="sec-1-23-2"><span class="section-number-4">1.23.2</span> go over thinktanks <a href="http://en.wikipedia.org/wiki/list_of_think_tanks_in_the_%20united_states">http://en.wikipedia.org/wiki/list_of_think_tanks_in_the_%20united_states</a></h4>
</div>
<div id="outline-container-sec-1-23-3" class="outline-4">
<h4 id="sec-1-23-3"><span class="section-number-4">1.23.3</span> use findthedata.org</h4>
</div>
<div id="outline-container-sec-1-23-4" class="outline-4">
<h4 id="sec-1-23-4"><span class="section-number-4">1.23.4</span> also check out google's publicdata thing?</h4>
</div>
<div id="outline-container-sec-1-23-5" class="outline-4">
<h4 id="sec-1-23-5"><span class="section-number-4">1.23.5</span> read less wrong, maybe take notes on essays? do the starter sequence</h4>
<div class="outline-text-4" id="text-1-23-5">
</div><ol class="org-ol"><li><a id="sec-1-23-5-1" name="sec-1-23-5-1"></a>study biases!<br  /></li></ol>
</div>
<div id="outline-container-sec-1-23-6" class="outline-4">
<h4 id="sec-1-23-6"><span class="section-number-4">1.23.6</span> look anti nuclear stuff to see what they say point by point</h4>
</div>
<div id="outline-container-sec-1-23-7" class="outline-4">
<h4 id="sec-1-23-7"><span class="section-number-4">1.23.7</span> add to um to listen? podcasts <a href="http://www.reddit.com/r/outoftheloop/comments/26ptiv/eli70_what_is_a_podcast/chtc5o5">http://www.reddit.com/r/outoftheloop/comments/26ptiv/eli70_what_is_a_podcast/chtc5o5</a></h4>
</div>
<div id="outline-container-sec-1-23-8" class="outline-4">
<h4 id="sec-1-23-8"><span class="section-number-4">1.23.8</span> open-politics, a la open political data <a href="https://theunitedstates.io/">https://theunitedstates.io/</a></h4>
</div>
</div>
<div id="outline-container-sec-1-24" class="outline-3">
<h3 id="sec-1-24"><span class="section-number-3">1.24</span> lrn-productivity</h3>
<div class="outline-text-3" id="text-1-24">
</div><div id="outline-container-sec-1-24-1" class="outline-4">
<h4 id="sec-1-24-1"><span class="section-number-4">1.24.1</span> wtf <a href="http://dynalon.github.io/mdwiki/#!index.md">http://dynalon.github.io/mdwiki/#!index.md</a> mdwiki allows wikis on github pages sites???</h4>
</div>
<div id="outline-container-sec-1-24-2" class="outline-4">
<h4 id="sec-1-24-2"><span class="section-number-4">1.24.2</span> lrn-procrastination</h4>
<div class="outline-text-4" id="text-1-24-2">
</div><ol class="org-ol"><li><a id="sec-1-24-2-1" name="sec-1-24-2-1"></a>notes from procrastination talk <a href="https://www.youtube.com/watch?v=mhFQA998WiA">https://www.youtube.com/watch?v=mhFQA998WiA</a><br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-1" name="sec-1-24-2-1-1"></a>we put things off thinking that we will have fun in the meantime, but usually it's guilt instead, a paralyzing emotion<br  /></li>
<li><a id="sec-1-24-2-1-2" name="sec-1-24-2-1-2"></a>we put things off by cooking, cleaning, other work things, things that have a "moral" component of "well look i'm doing this thing"<br  /></li>
<li><a id="sec-1-24-2-1-3" name="sec-1-24-2-1-3"></a>what we THINK we understand about procrastination is not actually true, but we still think these things in everyday exp:<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-3-1" name="sec-1-24-2-1-3-1"></a>we think it's about having fun (it's not)<br  /></li>
<li><a id="sec-1-24-2-1-3-2" name="sec-1-24-2-1-3-2"></a>we think we're not affecting our future self (we are)<br  /></li>
<li><a id="sec-1-24-2-1-3-3" name="sec-1-24-2-1-3-3"></a>it's all about giving in to feel good (it's not)<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-4" name="sec-1-24-2-1-4"></a>"tomorrow is a mystical land where 98% of human productivity is stored"<br  /></li>
<li><a id="sec-1-24-2-1-5" name="sec-1-24-2-1-5"></a>one new defn of procr is "the gap b/w intention and action"<br  /></li>
<li><a id="sec-1-24-2-1-6" name="sec-1-24-2-1-6"></a>procr is a subset of delay, "all procr is delay, but not all delay is procr"<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-6-1" name="sec-1-24-2-1-6-1"></a>example: if you plan to do hw for friday on thurs, that's not procr. If you get to thur and decide you don't "feel" like doing it, that's procr<br  /></li>
<li><a id="sec-1-24-2-1-6-2" name="sec-1-24-2-1-6-2"></a>voluntary, irrational delay<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-7" name="sec-1-24-2-1-7"></a>xxx [therefore, an important part of deciding BETWEEN delay and procr is planning!]<br  /></li>
<li><a id="sec-1-24-2-1-8" name="sec-1-24-2-1-8"></a>grad students esp feel this badly because there is much they need to and SHOULD delay, but they equate that with procr in their heads!!!<br  /></li>
<li><a id="sec-1-24-2-1-9" name="sec-1-24-2-1-9"></a>procr doesn't just affect performance, but also well-being, health, relationships, etc.<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-9-1" name="sec-1-24-2-1-9-1"></a>procrastinating students are actually sick more<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-10" name="sec-1-24-2-1-10"></a>think about how procr directly affects spending time with others<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-10-1" name="sec-1-24-2-1-10-1"></a>and how the stress you get from it spreads to other people like a disease<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-11" name="sec-1-24-2-1-11"></a>regrets of people bereaving those close to them who'd died is basically procr<br  /></li>
<li><a id="sec-1-24-2-1-12" name="sec-1-24-2-1-12"></a>fixing it<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-12-1" name="sec-1-24-2-1-12-1"></a>thinking about your agency<br  /></li>
<li><a id="sec-1-24-2-1-12-2" name="sec-1-24-2-1-12-2"></a>the most precious thing you have is time<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-13" name="sec-1-24-2-1-13"></a>procr is "NOT a time-management issue", a planner does NOT help<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-13-1" name="sec-1-24-2-1-13-1"></a>procrs tell time just like normies (study done by one of his students)<br  /></li>
<li><a id="sec-1-24-2-1-13-2" name="sec-1-24-2-1-13-2"></a>another of his students studied if procrs suffer the "planning fallacy" where they plan they're going to do a TON and then don't live up to it<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-13-2-1" name="sec-1-24-2-1-13-2-1"></a>procrs did NOT suffer planning fallacy (difference between expected and real understanding of how much studying they'd done)<br  /></li>
<li><a id="sec-1-24-2-1-13-2-2" name="sec-1-24-2-1-13-2-2"></a>procrs did study less and study later, but completely understood that they had done this<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-14" name="sec-1-24-2-1-14"></a>it is NOT an issue with planning<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-14-1" name="sec-1-24-2-1-14-1"></a>lots of people do their planning, but don't plan what they're going to do right now<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-15" name="sec-1-24-2-1-15"></a>he gave an example of a meeting with a student after which he knew the student didn't keep working for the rest of the time that day<br  /></li>
<li><a id="sec-1-24-2-1-16" name="sec-1-24-2-1-16"></a>xxx need to keep working AFTER successful meeting, use those good feelings for productivity<br  /></li>
<li><a id="sec-1-24-2-1-17" name="sec-1-24-2-1-17"></a>he says he never procrs anymore since he UNDERSTANDS the self deception<br  /></li>
<li><a id="sec-1-24-2-1-18" name="sec-1-24-2-1-18"></a>part of his understanding is of how actually long (and not that long) it takes himself to do something<br  /></li>
<li><a id="sec-1-24-2-1-19" name="sec-1-24-2-1-19"></a>just writing out a plan relieves stress, but does NOT solve the issue!!<br  /></li>
<li><a id="sec-1-24-2-1-20" name="sec-1-24-2-1-20"></a>procr is "weakness of will" and exerting self-control<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-20-1" name="sec-1-24-2-1-20-1"></a>the more you say "well I'll just do this thing that only takes 2 minutes", you're still facing the same hard decision and willpower threshold 2 minutes later<br  /></li>
<li><a id="sec-1-24-2-1-20-2" name="sec-1-24-2-1-20-2"></a>in that moment, you're either going to work or not work<br  /></li>
<li><a id="sec-1-24-2-1-20-3" name="sec-1-24-2-1-20-3"></a>"at its heart, it's about weakness of will, and about self-regulation"<br  /></li>
<li><a id="sec-1-24-2-1-20-4" name="sec-1-24-2-1-20-4"></a>it's a self-regulation failure, like buying things you don't need or eating things you don't need to eat<br  /></li>
<li><a id="sec-1-24-2-1-20-5" name="sec-1-24-2-1-20-5"></a>xxx it's about willpower<br  /></li>
<li><a id="sec-1-24-2-1-20-6" name="sec-1-24-2-1-20-6"></a>"I want to feel good now"<br  /></li>
<li><a id="sec-1-24-2-1-20-7" name="sec-1-24-2-1-20-7"></a>esp with a thesis, when you get it back and it's not perfect/has lots of edits to do, you feel bad! [and that's okay] you get negative reinforcement (emotionally)<br  /></li>
<li><a id="sec-1-24-2-1-20-8" name="sec-1-24-2-1-20-8"></a>"negative reinforcement" is the removal of a negative stimulus, like using an umbrella<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-20-8-1" name="sec-1-24-2-1-20-8-1"></a>"procr is neg reinforcement", since the task makes you uncomfortable, therefore you're avoiding the task (to avoid the neg stim)<br  /></li>
<li><a id="sec-1-24-2-1-20-8-2" name="sec-1-24-2-1-20-8-2"></a>xxx therefore, by USING procr, you're REINFORCING that it's effective<br  /></li>
<li><a id="sec-1-24-2-1-20-8-3" name="sec-1-24-2-1-20-8-3"></a>it's a reinforced habit, and is difficult to change<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-20-9" name="sec-1-24-2-1-20-9"></a>[i originally was planning to talk to therapist about lack of "energy" of me doing things, but what if the real issue isn't energy but willpower? what if it's nto that i'm tired (although that does happen, but less frequently and a nap cures it), but it's self control and not enough willpower to work?]<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-20-9-1" name="sec-1-24-2-1-20-9-1"></a>the real issue may not be that i'm tired, but that I'm UNWILLING<br  /></li>
<li><a id="sec-1-24-2-1-20-9-2" name="sec-1-24-2-1-20-9-2"></a>listening to this discussion esp about personality and impulsivity, sounds like to work on solving this procr, i need to better understand the psych report and my personality<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-21" name="sec-1-24-2-1-21"></a>there are multiple parts of this "self-regulation failure" - how do you intervene in these?<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1" name="sec-1-24-2-1-21-1"></a>personality<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1" name="sec-1-24-2-1-21-1-1"></a>how to intervene<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-1" name="sec-1-24-2-1-21-1-1-1"></a>dutiful, self-disciplined people don't procr much<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-2" name="sec-1-24-2-1-21-1-1-2"></a>low "conscientiousness" (wishing to do a task correctly and thoroughly) means procr<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-3" name="sec-1-24-2-1-21-1-1-3"></a>high "impulsivity" means procr<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-3-1" name="sec-1-24-2-1-21-1-1-3-1"></a>"they can't shield one intention from another intention"<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-4" name="sec-1-24-2-1-21-1-1-4"></a>perfectionism<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-4-1" name="sec-1-24-2-1-21-1-1-4-1"></a>difference b/w self-perfectionists vs socially-prescribed perfectionism (driven by other people)<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-4-1-1" name="sec-1-24-2-1-21-1-1-4-1-1"></a>the socially-prescribed perfectionists live up to OTHER people's standards, have lots of negative internal talk, and score high with procr<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-4-2" name="sec-1-24-2-1-21-1-1-4-2"></a>"perfectionism isn't bad, it depends on the flavor"<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-5" name="sec-1-24-2-1-21-1-1-5"></a>emotional intelligence<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-5-1" name="sec-1-24-2-1-21-1-1-5-1"></a>higher emo intel, lower procr<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-5-2" name="sec-1-24-2-1-21-1-1-5-2"></a>it's a skill that you CAN learn<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-5-3" name="sec-1-24-2-1-21-1-1-5-3"></a>"I said i was gonna do this, it doesn't matter how i feel"<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-5-4" name="sec-1-24-2-1-21-1-1-5-4"></a>task: just track how you feel about doing different things and write it down<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-5-5" name="sec-1-24-2-1-21-1-1-5-5"></a>neuroticism is emotional instability<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-5-5-1" name="sec-1-24-2-1-21-1-1-5-5-1"></a>those who're neurotic have emo rxns to work that are WAY out of proportion, low lows and high highs, even when the work is NOT A BIG DEAL<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-5-6" name="sec-1-24-2-1-21-1-1-5-6"></a>procr will stay up all night, do task, turn it in, feel great, but then not use that good feeling to do more work<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-5-6-1" name="sec-1-24-2-1-21-1-1-5-6-1"></a>real learning should be constant (at lower magnitude), not stop and go with cramming and then unworking<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-5-7" name="sec-1-24-2-1-21-1-1-5-7"></a>you have to learn to USE your emotions but also not react to neg emotions<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-5-8" name="sec-1-24-2-1-21-1-1-5-8"></a>"You can have fear but you do not need to BE your fear" (fear is the mind killer&#x2026;incl how it applies to learning!)<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-1-6" name="sec-1-24-2-1-21-1-1-6"></a>procr is also a developmental thing<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-1-1-6-1" name="sec-1-24-2-1-21-1-1-6-1"></a>PFC is last brain part in dev<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-6-2" name="sec-1-24-2-1-21-1-1-6-2"></a>if you've "achieved" your identity, less likely to procr<br  /></li>
<li><a id="sec-1-24-2-1-21-1-1-6-3" name="sec-1-24-2-1-21-1-1-6-3"></a>"you can't expect an 18 yo to act like a 25yo"<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-21-1-2" name="sec-1-24-2-1-21-1-2"></a>lots of personality traits are inherited???<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-2" name="sec-1-24-2-1-21-2"></a>the nature of the goals<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-2-1" name="sec-1-24-2-1-21-2-1"></a>how to intervene<br  /></li>
<li><a id="sec-1-24-2-1-21-2-2" name="sec-1-24-2-1-21-2-2"></a>task aversiveness<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-2-2-1" name="sec-1-24-2-1-21-2-2-1"></a>what makes a task aversive?<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-2-2-1-1" name="sec-1-24-2-1-21-2-2-1-1"></a>splitting a task into inception, planning, and action phases,<br  /></li>
<li><a id="sec-1-24-2-1-21-2-2-1-2" name="sec-1-24-2-1-21-2-2-1-2"></a>boredom/frustration at every stage<br  /></li>
<li><a id="sec-1-24-2-1-21-2-2-1-3" name="sec-1-24-2-1-21-2-2-1-3"></a>frustration at inception and planning phases = due to lack of meaning/enjoyment/(importance?)<br  /></li>
<li><a id="sec-1-24-2-1-21-2-2-1-4" name="sec-1-24-2-1-21-2-2-1-4"></a>frustration at action phase = due to lack of structure/control/uncertainy<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-2-2-2" name="sec-1-24-2-1-21-2-2-2"></a>temporal construal theory = are you thinking abstractly or concretely, and how that affects our temporal interpretation<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-2-2-2-1" name="sec-1-24-2-1-21-2-2-2-1"></a>"when you think about things concretely, you think of them in terms of today, but abstractly, tomorrow" (recent psych result)<br  /></li>
<li><a id="sec-1-24-2-1-21-2-2-2-2" name="sec-1-24-2-1-21-2-2-2-2"></a>so it's not jsut breaking things down into baby steps, but the fact you're thinking about real world actions, which makes your brain give the things more urgency<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-21-2-3" name="sec-1-24-2-1-21-2-3"></a>how we think about the task<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-2-3-1" name="sec-1-24-2-1-21-2-3-1"></a>"I work better without pressure" fallacy aka the "arousal procr"<br  /></li>
<li><a id="sec-1-24-2-1-21-2-3-2" name="sec-1-24-2-1-21-2-3-2"></a>quote from thesis "The mental discipline necessary to work towards a deadline is something that you must develop. It can become a habit just as lettings things slide until the last minute can become a habit. That pattern leads to staying up all night and writing in a blind panic. Besides ruining your health, you never can write your best. If anyone tells you "I have to wait until the pressure is on before I can start to cook", don't believe it. Occasionally, you may be able to work under pressure of a deadline, but stop kidding yourself, it won't be your best."<br  /></li>
<li><a id="sec-1-24-2-1-21-2-3-3" name="sec-1-24-2-1-21-2-3-3"></a>uh make deadlines<br  /></li>
<li><a id="sec-1-24-2-1-21-2-3-4" name="sec-1-24-2-1-21-2-3-4"></a>several quotes from music industry people about how you THINK you'd work better under pressure, but that's not true and not how it works<br  /></li>
<li><a id="sec-1-24-2-1-21-2-3-5" name="sec-1-24-2-1-21-2-3-5"></a>procrs think "it could have been worse", but that's just making an excuse (and you're always going to be able to say that to yourself, but it's never helpful)<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-21-3" name="sec-1-24-2-1-21-3"></a>self-control and willpower<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-3-1" name="sec-1-24-2-1-21-3-1"></a>how to intervene<br  /></li>
<li><a id="sec-1-24-2-1-21-3-2" name="sec-1-24-2-1-21-3-2"></a>willpower is like a muscle<br  /></li>
<li><a id="sec-1-24-2-1-21-3-3" name="sec-1-24-2-1-21-3-3"></a>self-regulatory depletion<br  /></li>
<li><a id="sec-1-24-2-1-21-3-4" name="sec-1-24-2-1-21-3-4"></a>implications are that you can BUILD it up like a muscle<br  /></li>
<li><a id="sec-1-24-2-1-21-3-5" name="sec-1-24-2-1-21-3-5"></a>can build it using "value affirmation"<br  /></li>
<li><a id="sec-1-24-2-1-21-3-6" name="sec-1-24-2-1-21-3-6"></a>even when you think you have nothing less, there are ways to motivate yourself to increase your willpower reserve<br  /></li>
<li><a id="sec-1-24-2-1-21-3-7" name="sec-1-24-2-1-21-3-7"></a>meditation helps<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-3-7-1" name="sec-1-24-2-1-21-3-7-1"></a>[is that because it helps you recognize what you're doing from an external POV? what is that called?]<br  /></li>
<li><a id="sec-1-24-2-1-21-3-7-2" name="sec-1-24-2-1-21-3-7-2"></a>meditation helps attn, and attn helps willpower<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-3-8" name="sec-1-24-2-1-21-3-8"></a>"implementation intentions"<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-3-8-1" name="sec-1-24-2-1-21-3-8-1"></a>sort of like Ivy Lee method where you just say, "When X happens [e.g. done with task, end of talk], I'm going to do Y (read a paper), then Z"<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-3-8-1-1" name="sec-1-24-2-1-21-3-8-1-1"></a>prob esp helpful at beginning of day<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-21-3-8-2" name="sec-1-24-2-1-21-3-8-2"></a>"people who make implementation INTENTIONS tend to follow through"<br  /></li>
<li><a id="sec-1-24-2-1-21-3-8-3" name="sec-1-24-2-1-21-3-8-3"></a>(sort of like a super todo list, but tied together like triggers)<br  /></li>
<li><a id="sec-1-24-2-1-21-3-8-4" name="sec-1-24-2-1-21-3-8-4"></a>THIS is writing down the list of what to do today in nb<br  /></li>
<li><a id="sec-1-24-2-1-21-3-8-5" name="sec-1-24-2-1-21-3-8-5"></a>saying "i'm going to spend all day doing a task like writing" when you've NEVER spent the entire day doing that is not helpful &#x2013; what is helpful is finer granularity, like "11am-noon I'm going to write, then eat lunch, then 12.30-1.30 i'm going to write more"<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-3-8-5-1" name="sec-1-24-2-1-21-3-8-5-1"></a>that's also asking too much of a single interval<br  /></li>
<li><a id="sec-1-24-2-1-21-3-8-5-2" name="sec-1-24-2-1-21-3-8-5-2"></a>once you get into the habit of doing something like that more frequently, then you'll have more of it done and won't need to do it all at once<br  /></li></ol>
</li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-21-4" name="sec-1-24-2-1-21-4"></a>cognition and beliefs<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-21-4-1" name="sec-1-24-2-1-21-4-1"></a>how to intervene<br  /></li></ol>
</li></ol>
</li>
<li><a id="sec-1-24-2-1-22" name="sec-1-24-2-1-22"></a>procr will stay up all night, do task, turn it in, feel great, but then not use that good feeling to do more work<br  /><ol class="org-ol"><li><a id="sec-1-24-2-1-22-1" name="sec-1-24-2-1-22-1"></a>real learning should be constant (at lower magnitude), not stop and go with cramming and then unworking<br  /></li></ol>
</li>
<li><a id="sec-1-24-2-1-23" name="sec-1-24-2-1-23"></a>fear is the mind killer and the procrastinator<br  /></li></ol>
</li></ol>
</div>
</div>
<div id="outline-container-sec-1-25" class="outline-3">
<h3 id="sec-1-25"><span class="section-number-3">1.25</span> lrn-prof-dev-lrn-professional-development</h3>
<div class="outline-text-3" id="text-1-25">
</div><div id="outline-container-sec-1-25-1" class="outline-4">
<h4 id="sec-1-25-1"><span class="section-number-4">1.25.1</span> 20130326 professional devlpmt talk</h4>
<div class="outline-text-4" id="text-1-25-1">
<ul class="org-ul">
<li>lots of assumptions about attn during talks (esp w/ science)
</li>
<li>long pauses
</li>
<li>engagement w/ audience
</li>
<li>human contact and stories
</li>
<li>diff b/w msg, speaker, and audience
</li>
<li>aud doesn't on verbal or visual; integrates both all the tiem
</li>
<li>"provide a mental struct that uses prior knowledge"
</li>
<li>don't turn off lights for a post-lunch talk
</li>
<li>narrow down message to land only 1 thing
</li>
<li>"you have to want the audience to learn the thing"
</li>
<li>he discourages using notes
</li>
<li>now he says 3 points
</li>
<li>hard to distinguish b/w his real Q's and rhetorical Q's
</li>
<li>"hyperlinks" and linking to web during talk, omg
</li>
<li>wtf multitasking? "being intentional"
<ul class="org-ul">
<li>use consistent themes
</li>
</ul>
</li>
<li>go grab related pieces of news
</li>
<li>"stories are the most engaging things"
</li>
<li>could always put it more casually (like at the end of a slide)
</li>
<li>have a midway synopsis slide?
</li>
<li>he keeps pushing relevant engagement as if people don't know your stuff at all
</li>
<li>stupid handout
</li>
<li>what to do if eqns put people off?
<ul class="org-ul">
<li>he doesn't seem confident in his response, more about "what's most relevant to most people"
</li>
</ul>
</li>
<li>think of the ones in the audience who know the LEAST on your stuff
</li>
<li>give enough for the people who follow to graspp the details, then shift and bring in the poeple whoo don't need it
</li>
<li>this guy has a 90s-level understanding of powerpoint
</li>
<li>he uses hyperlinks as if "techniques"
</li>
<li>powerpoint is low-info-resolution; when need higher, go to print
</li>
<li>"the Google search engine"
</li>
<li>"be metaphoric in your designs"
</li>
<li>use metaphorical images
</li>
<li>carve out a specific niche and try to attack the likely questions people will have
</li>
<li>make a media library for yourself, esp if it's diff take, esp w/ human element
</li>
<li>how do you control your speech?
<ul class="org-ul">
<li>arrive at a place of ease, "who gives a s&#x2014;"
</li>
<li>"less is more" for speaking
</li>
<li>once again, simplify your speech
</li>
<li>not as important as content
</li>
<li>"be present" [he means mindfulness]
</li>
<li>look at people and smile at them
</li>
<li>make sure people come AND leave with questions, not answers
</li>
</ul>
</li>
<li>review articles for quotes
</li>
</ul>
</div>
</div>

<div id="outline-container-sec-1-25-2" class="outline-4">
<h4 id="sec-1-25-2"><span class="section-number-4">1.25.2</span> lrn-leadership</h4>
<div class="outline-text-4" id="text-1-25-2">
</div><ol class="org-ol"><li><a id="sec-1-25-2-1" name="sec-1-25-2-1"></a>Nancy at SZ collab meeting, 2014<sub>04</sub><sub>02</sub>: "let's try to write down questions for which this group are the right people to do it"<br  /></li></ol>
</div>
<div id="outline-container-sec-1-25-3" class="outline-4">
<h4 id="sec-1-25-3"><span class="section-number-4">1.25.3</span> lrn-networking lrn-professional-networking / long-term-networking</h4>
<div class="outline-text-4" id="text-1-25-3">
</div><ol class="org-ol"><li><a id="sec-1-25-3-1" name="sec-1-25-3-1"></a>frank: biotech/industry/startups, ESPECIALLY in boston expect YOU to reach out to them, there exist certain pipelines from certain institutions<br  /></li></ol>
</div>
<div id="outline-container-sec-1-25-4" class="outline-4">
<h4 id="sec-1-25-4"><span class="section-number-4">1.25.4</span> lrn-presn, lrn-presentations</h4>
<div class="outline-text-4" id="text-1-25-4">
</div><ol class="org-ol"><li><a id="sec-1-25-4-1" name="sec-1-25-4-1"></a>lrn-academic-presn<br  /><ol class="org-ol"><li><a id="sec-1-25-4-1-1" name="sec-1-25-4-1-1"></a><a href="http://matt.might.net/articles/academic-presentation-tips/">http://matt.might.net/articles/academic-presentation-tips/</a><br  /></li>
<li><a id="sec-1-25-4-1-2" name="sec-1-25-4-1-2"></a><a href="http://www.cs.berkeley.edu/~jrs/speaking.html">http://www.cs.berkeley.edu/~jrs/speaking.html</a><br  /></li>
<li><a id="sec-1-25-4-1-3" name="sec-1-25-4-1-3"></a><a href="http://www.inference.phy.cam.ac.uk/mackay/how2talk.wrd">http://www.inference.phy.cam.ac.uk/mackay/how2talk.wrd</a><br  /></li>
<li><a id="sec-1-25-4-1-4" name="sec-1-25-4-1-4"></a><a href="http://homepages.inf.ed.ac.uk/sgwater/presentation_advice.html">http://homepages.inf.ed.ac.uk/sgwater/presentation_advice.html</a><br  /></li>
<li><a id="sec-1-25-4-1-5" name="sec-1-25-4-1-5"></a><a href="http://people.eecs.berkeley.edu/~jrs/speaking.html">http://people.eecs.berkeley.edu/~jrs/speaking.html</a><br  /></li></ol>
</li>
<li><a id="sec-1-25-4-2" name="sec-1-25-4-2"></a>lrn-public-speaking<br  /><ol class="org-ol"><li><a id="sec-1-25-4-2-1" name="sec-1-25-4-2-1"></a><a href="http://homepages.inf.ed.ac.uk/imurray2/teaching/speaking/">http://homepages.inf.ed.ac.uk/imurray2/teaching/speaking/</a><br  /></li>
<li><a id="sec-1-25-4-2-2" name="sec-1-25-4-2-2"></a><a href="http://www.cs.berkeley.edu/~jrs/speaking.html">http://www.cs.berkeley.edu/~jrs/speaking.html</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-25-5" class="outline-4">
<h4 id="sec-1-25-5"><span class="section-number-4">1.25.5</span> lrn-industry</h4>
<div class="outline-text-4" id="text-1-25-5">
</div><ol class="org-ol"><li><a id="sec-1-25-5-1" name="sec-1-25-5-1"></a>Scott and Jon answering questions about working in industry at GPN retreat 20170608<br  /><ol class="org-ol"><li><a id="sec-1-25-5-1-1" name="sec-1-25-5-1-1"></a>most results in industry are negative, and expect a lot of them (unlike academia)<br  /></li>
<li><a id="sec-1-25-5-1-2" name="sec-1-25-5-1-2"></a>what they strongly frown upon is sloppy sci tech, which are more important than what you know<br  /></li></ol>
</li></ol>
</div>
</div>
<div id="outline-container-sec-1-26" class="outline-3">
<h3 id="sec-1-26"><span class="section-number-3">1.26</span> lrn-ripping</h3>
<div class="outline-text-3" id="text-1-26">
</div><div id="outline-container-sec-1-26-1" class="outline-4">
<h4 id="sec-1-26-1"><span class="section-number-4">1.26.1</span> DVDs</h4>
<div class="outline-text-4" id="text-1-26-1">
</div><ol class="org-ol"><li><a id="sec-1-26-1-1" name="sec-1-26-1-1"></a>Makemkv and handbrake for DVDs?<br  /></li>
<li><a id="sec-1-26-1-2" name="sec-1-26-1-2"></a>Best way to rip my DVD collection, keeping intact original subs? <a href="https://www.reddit.com/r/cordcutters/comments/26mbz9/best_way_to_rip_my_dvd_collection_keeping_intact/">https://www.reddit.com/r/cordcutters/comments/26mbz9/best_way_to_rip_my_dvd_collection_keeping_intact/</a><br  /></li>
<li><a id="sec-1-26-1-3" name="sec-1-26-1-3"></a><a href="https://forums.plex.tv/discussion/comment/1335697/#Comment_1335697">https://forums.plex.tv/discussion/comment/1335697/#Comment_1335697</a><br  /></li>
<li><a id="sec-1-26-1-4" name="sec-1-26-1-4"></a><a href="http://www.brorsoft.com/tutorial/best-handbrake-settings-for-plex.html">http://www.brorsoft.com/tutorial/best-handbrake-settings-for-plex.html</a><br  /></li>
<li><a id="sec-1-26-1-5" name="sec-1-26-1-5"></a>sounds like should use 264 (not 265) until av1 comes out<br  /></li>
<li><a id="sec-1-26-1-6" name="sec-1-26-1-6"></a><a href="https://forums.plex.tv/discussion/252545/handbrake-settings-to-preserve-dvd-quality">https://forums.plex.tv/discussion/252545/handbrake-settings-to-preserve-dvd-quality</a><br  /></li>
<li><a id="sec-1-26-1-7" name="sec-1-26-1-7"></a><a href="https://handbrake.fr/docs/en/latest/technical/official-presets.html">https://handbrake.fr/docs/en/latest/technical/official-presets.html</a><br  /></li>
<li><a id="sec-1-26-1-8" name="sec-1-26-1-8"></a><a href="https://support.plex.tv/articles/203824396-what-media-formats-are-supported/?mobile_site=true">https://support.plex.tv/articles/203824396-what-media-formats-are-supported/?mobile_site=true</a><br  /></li>
<li><a id="sec-1-26-1-9" name="sec-1-26-1-9"></a><a href="https://www.reddit.com/r/PleX/comments/5l8owa/question_best_practice_for_ripping_owned_dvds_to/?utm_source=amp&utm_medium=comment_list">https://www.reddit.com/r/PleX/comments/5l8owa/question_best_practice_for_ripping_owned_dvds_to/?utm_source=amp&utm_medium=comment_list</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-26-2" class="outline-4">
<h4 id="sec-1-26-2"><span class="section-number-4">1.26.2</span> CDs</h4>
<div class="outline-text-4" id="text-1-26-2">
</div><ol class="org-ol"><li><a id="sec-1-26-2-1" name="sec-1-26-2-1"></a>Exact Audio Copy and ffmpeg for transcoding<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-27" class="outline-3">
<h3 id="sec-1-27"><span class="section-number-3">1.27</span> lrn-sailing&#xa0;&#xa0;&#xa0;<span class="tag"><span class="lrn_sailing">lrn_sailing</span></span></h3>
<div class="outline-text-3" id="text-1-27">
</div><div id="outline-container-sec-1-27-1" class="outline-4">
<h4 id="sec-1-27-1"><span class="section-number-4">1.27.1</span> sailing notes, day 1 2014-09-20</h4>
<div class="outline-text-4" id="text-1-27-1">
<ul class="org-ul">
<li>agenda: the boat, wind, turning, knots
</li>
<li>can take (discounted) $39 multiple choice test after finishing class for most basic registration
</li>
<li>chris allen teaching
</li>
<li>"Courageous" an NPO, and "Community Sailing on the Charles" also recommended
</li>
<li>get 35 days of member sailing after class, that may roll over
</li>
<li>parts of boat
<ul class="org-ul">
<li>omega symbol on sails means it's a student, everyone on water will see and understand that
</li>
<li>hullspeed eqn determines literally the max speed of the boat, f(length on water line) = 7 knots for solings
<ul class="org-ul">
<li>need 12-15 knots windspeed for max boat speed, but &gt;15 knots doesn't make it any faster!
</li>
</ul>
</li>
<li>need "one hand" of wtr b/w ground
</li>
<li>can't use tiller to brake
<ul class="org-ul">
<li>xxx "can't brake, can only take foot off the gas"
</li>
</ul>
</li>
<li>heeling = when boat turns lat on its side
</li>
<li>"lines" = boat term for lines
<ul class="org-ul">
<li>can use "camp or cleat" to catch/sit lines near winches
</li>
<li>you "trim" vs "ease" the line
</li>
</ul>
</li>
<li>"blocks" = boat term for pulleys
</li>
<li>standing rigging = literally the rigging on it 24/7, even when at mooring
</li>
<li>running rigging = stuff like sails that you put on to go
</li>
<li>can BEND the sails like wings, which planes can't do
</li>
<li>can trim the aft stay to bend the mast (don't worry about plastic deformation)
</li>
<li>the boom is free in its range
</li>
<li>watch spongebob episode about parts of the boat/learning to drive
</li>
<li>luff = Leading edge of sail (see "luffing")
</li>
<li>clew = no clew what the name is, it's not the tack or head
</li>
<li>4 lines
<ol class="org-ol">
<li>main halyard, hoists main sail up
</li>
<li>jib halyard
</li>
<li>jib sheet
</li>
<li>main sheet
</li>
</ol>
</li>
<li>in rigging, you "tack on the tag" [connect the tack of both main and jib to their things]
</li>
<li>sails shaking = luffing [boat is telling you it wants directions]
</li>
<li>stays = permanent metal wire lines going up the mast connected to the boat. Frontmost stay is what the jib tack goes on
</li>
<li>jib sheet loosens/tightens jib clew
</li>
<li>"roaches and leeches" on main sail (leech is the perfect triangle, roach is the extra fabric on sail)
</li>
</ul>
</li>
<li>port/starboard are fixed, but there are also wind-relative side terms "winward aka weatherside" and "leeward" (pron loohr-word)
</li>
<li>right of way: if starb = win, you have RoW
</li>
<li>"the boat leans to lee[side]" [but it wants to turn into winward/wants to approach the wind]
</li>
<li>helm = person holding the tiller, and sometimes the main sheet
</li>
<li>the wind
<ul class="org-ul">
<li>spd and dir
</li>
<li>there exist nautical vs statue miles
</li>
<li>17 mph = 15 knots / good enough
</li>
<li>solings want 5-10 for learning, 10-15 is fun, &gt;12 is intense
</li>
<li>there are smaller storm sails for high wind
</li>
<li>gusts are often 20 knots
<ul class="org-ul">
<li>gust mgmt is adv
</li>
<li>can see them coming on the water sometimes
</li>
</ul>
</li>
<li>0 is the worst wind speed
</li>
<li>Boston harbor wind mostly S-SW (meaning coming from)
</li>
<li>winds on the sail
<ul class="org-ul">
<li>when going upwind, front of sail is a high-pressure sys, back of sail is a low-pressure sys, which makes a lift vector called "attached airflow" or pilots call "laminar flow"
</li>
<li>air on both sides reaches end of sail at same time
</li>
<li>the lift vector is usually very perpendicular to the wind dir, but when combined with vertical keel hydrodynamics, makes an upwind vector
</li>
<li>this all is called lift
</li>
</ul>
</li>
<li>jib has red and green "telltales", and you want them BOTH to be strong
<ul class="org-ul">
<li>if inner red weak, trim it, and vice versa
</li>
</ul>
</li>
<li>"when in doubt, let it out"
</li>
<li>leech has tails that come out in rear
</li>
<li>"points of sail" 360 degree wheel, from
<ul class="org-ul">
<li>into wind / "in irons",
</li>
<li>"close reach" maximizing lift,
</li>
<li>"beam reach" named for flat beam behind helm
</li>
<li>"? reach" more downward, starting to use "drag" instead of lift
</li>
</ul>
</li>
<li>wind coming on left side = "port tack", wind coming on starboard = "starboard tack"
</li>
<li>"head up" = turn nose to point up to source of wind
<ul class="org-ul">
<li>done by pulling tiller into wind
</li>
<li>as opposed to "fall off"
</li>
</ul>
</li>
<li>solings are good at not staying in irons
</li>
</ul>
</li>
<li>turning the boat, aka "tacking"
<ul class="org-ul">
<li>to turn, push tiller into sail
</li>
<li>pushes rear of boat around wrt the bow
</li>
<li>when tacking, don't need to adjust main, since is "self-tacking"
</li>
<li>NEVER let go of the tiller, also bad if not looking at front
</li>
<li>newbs tend to turn around when tacking - don't
</li>
<li>tacking the jib
<ul class="org-ul">
<li>when turning L, loosen the R jib line and pull the L line
</li>
</ul>
</li>
</ul>
</li>
<li>in irons is sometimes called the safety position
</li>
<li>xxx in "jibbing aka gybbing" (turning downwind), can get "uncontrolled jibe" where jib starts luffing and then turns around to be opposite the direction of the main; this is VERY bad, as the boom will then come snap around VERY quickly
</li>
<li>helmsman is "in the box"
</li>
<li>"listen to the jib"
</li>
<li>man overboard rescue is usually either a figure 8 or a "quick turn"
</li>
<li>knots: cleat hitch, bowlein, stopper knots (8, pigtail)
</li>
</ul>
</div>
</div>

<div id="outline-container-sec-1-27-2" class="outline-4">
<h4 id="sec-1-27-2"><span class="section-number-4">1.27.2</span> sailing notes, day 2 2014-09-21</h4>
<div class="outline-text-4" id="text-1-27-2">
<ul class="org-ul">
<li>if going downwind in a far reach (can't remember exact phrasing), can be "sailing by the lee" where boom is still on the winward side
</li>
<li id="downwind : drag">upwind : lift
</li>
<li>starb tack has RoW over port tack
</li>
<li>if get a "puff", can
<ol class="org-ol">
<li>let off main sail (best, simplest)
</li>
<li>head into wind
</li>
<li>sit differently
<ul class="org-ul">
<li>"the boat hates people"
</li>
<li>"everyone should sit on the winward side =&gt; the boat will point to leeward"
</li>
</ul>
</li>
</ol>
</li>
<li>most difficult thing is keeping a course
</li>
<li>jib vs jibe
</li>
<li>best time to do jib during tack
<ul class="org-ul">
<li>to release, just when jib? start luffing
</li>
<li>to tighten, wait until luff of jib crosses the mast
</li>
</ul>
</li>
<li>he trusts candied ginger for seasickness/nausea
</li>
<li>"crash jibe" = immediately going to start a jibe bc of emergency, watch your head
</li>
<li>mooring
<ul class="org-ul">
<li>exiting mooring
<ul class="org-ul">
<li>let the jib fully luff when unmooring
</li>
<li>can artificially (aka with hands) tighten jib to get a kickstart
<ul class="org-ul">
<li>aka "backing the jib"
</li>
<li>this is used to change dir, NOT to go fwd
</li>
</ul>
</li>
</ul>
</li>
<li>entering mooring
<ul class="org-ul">
<li>open the jib completely
<ul class="org-ul">
<li>this decr wind power
</li>
<li>this change the handling too, so be careful
</li>
</ul>
</li>
<li>once "on the moor," should luff and/or drop main
</li>
<li>can easily drop the sails by pulling on luff
</li>
<li>xxx "luffing a sail" = loosening
</li>
<li>can always "pass" on a particular mooring = good practice too
</li>
<li>"shopping window" of potential moors is usu b/w 270 degrees and 320 degrees, if on a reach/going upwind
</li>
<li>lots of mooring maneuvers exist
</li>
<li>"sneak in from behind, let sails out early"
</li>
</ul>
</li>
</ul>
</li>
<li>man overboard
<ul class="org-ul">
<li>important things
<ol class="org-ol">
<li>cry out (say it)
</li>
<li>throw flotation, even if they're wearing a lifevest (so you can see the flotation)
</li>
<li>get a spotter who constantly maintains eyes and arm pointing on the person
</li>
</ol>
<p>
(4.) do NOT jump out, since more people in water = less control of boat; only jump in for elderly, invalid, or infants
</p>
</li>
<li>"quick turn" easiest, best
<ul class="org-ul">
<li>immediately turn to beam reach, go 5/6 boat lengths,
</li>
<li>then jib,
</li>
<li>then turn or tack to return to where the person is, loosening sails to slow down when close
</li>
</ul>
</li>
</ul>
</li>
<li>Balance
<ul class="org-ul">
<li>CLR/"the pivot" = center of lat resistance, can rotate around this point/vertical line
</li>
<li>CE/"the push" = center of effort, midpoint of mass b/w the sails (and maybe people as well?), so it provides torque around the pivot, and change location depending on absolute and relative location of the sails
</li>
<li>knowing this really helps for better sailing
</li>
<li>"weatherhelm" is idea that boat tends to turn into the wind
<ul class="org-ul">
<li>this is by design, so it keeps you awake etc.
</li>
<li>dealing with weatherhelm is newb stuff, you should be able to compensate
</li>
<li>this includes that you need to "fight" the boat doing this to go in a straight line
</li>
</ul>
</li>
<li>if strong wind, then main will get more, which shifts the push more to main
</li>
<li>if main gets too much push, can get enough weatherhelm so that the push is so rear that tilling isn't effective
<ul class="org-ul">
<li>letting main out is best solution to get rid of this
</li>
<li>"the less balanced the boat, the less effective the rudder"
<ul class="org-ul">
<li>this includes heeling
</li>
<li>too much heeling is inefficient
</li>
</ul>
</li>
</ul>
</li>
<li>bending the mast also moves the push to the rear
</li>
</ul>
</li>
<li>leeway
<ul class="org-ul">
<li>if trying to reach a point, should aim a little towards the source of wind to actually get there (have to go sideways a little)
</li>
<li>this can happen especially for tidal reasons (think of the hydrodyns of the keel)
</li>
<li>xxx read more about this
</li>
</ul>
</li>
<li>rules of the road
<ul class="org-ul">
<li>if vessel collision, EVERYONE is at fault
</li>
<li>diff boat classes has more or less RoW
</li>
<li>stand-on (so) or give-way (gw)
</li>
<li>gw means the boat with more control (often facing the wind more) has an easier time getting out of the way
</li>
<li>so means you should maintain your course and speed
</li>
<li>starb tack: if port tack and starb tack both going upwind and headed on collision course, port tack is gw and should move
</li>
<li>leeward boat: if in irons/close reach, and intercept w/ a beam reach boat, beam reach is gw and should move
</li>
<li>overtaken: ??
</li>
</ul>
</li>
<li>big boats: 5 loud blasts = danger, idk what you're doing and I can't tell
</li>
<li>spinikerup = restricted maneurver (has RoW)
</li>
<li>Apparent Wind (AW)
<ul class="org-ul">
<li>relative wind feeling
</li>
<li>often when you feel wind loss, it's this
</li>
<li>changing dir of AW
<ul class="org-ul">
<li>as boat goes forward, gradually wind vector will approach course
</li>
<li>"your boat spd has bent the dir of the wind"
</li>
</ul>
</li>
<li>if want more wind, head up, since AW incr, instead of falling down (which would give you a better angle)
</li>
</ul>
</li>
</ul>
</div>
</div>

<div id="outline-container-sec-1-27-3" class="outline-4">
<h4 id="sec-1-27-3"><span class="section-number-4">1.27.3</span> sailing notes, day 3 2014-09-27</h4>
<div class="outline-text-4" id="text-1-27-3">
<ul class="org-ul">
<li>backing the jib = using your hands
<ul class="org-ul">
<li>like when leaving mooring and want to turn
</li>
<li>if main is tight, then can make this much harder
</li>
</ul>
</li>
<li>if someone falls off, can do
<ol class="org-ol">
<li>"quick stop" (where come by on downwind),
</li>
<li>"figure 8" which is commonly taught since involves a tack instead of a jibe, and
</li>
<li>"quick turn" which is what they taught me
</li>
</ol>
</li>
<li>pick people up on WINWARD side of boat, not leeward &#x2013; wind can knock boat into person, better visibility
</li>
<li>weather-helm: when rear of boat becomes boss
<ul class="org-ul">
<li>reduce it via
<ol class="org-ol">
<li>let main out
</li>
<li>head up into wind
</li>
<li>tighten jib
</li>
</ol>
</li>
</ul>
</li>
<li>"fall-off" - away from wind
</li>
<li>jibe has less turning power then tack
</li>
<li>right of way: if both starb, tiebreaker is who gets wind first
</li>
</ul>
</div>
</div>

<div id="outline-container-sec-1-27-4" class="outline-4">
<h4 id="sec-1-27-4"><span class="section-number-4">1.27.4</span> sailing notes, day 4 2014-09-28</h4>
<div class="outline-text-4" id="text-1-27-4">
<ul class="org-ul">
<li>bending mast = brings CE back and tightens
</li>
<li>outhaul = incr curvature of foot
<ul class="org-ul">
<li>thing with the weird tie at bottom of boom
</li>
</ul>
</li>
<li>cunningham helps upwind, most vertical portion of main
</li>
<li>fuller sails = "keep the wind"
</li>
<li>boom vang is how you take twist out
</li>
</ul>
</div>

<ol class="org-ol"><li><a id="sec-1-27-4-1" name="sec-1-27-4-1"></a>Navigation 2<br  /><div class="outline-text-5" id="text-1-27-4-1">
<ul class="org-ul">
<li>"obtaining a fix&#x2026;"
</li>
<li>D = RxT
<ul class="org-ul">
<li>Distance comes from chart
</li>
<li>Rate is difficult, use an app/GPS
<ul class="org-ul">
<li>recommends "iSailor" app
</li>
</ul>
</li>
</ul>
</li>
<li>inside ring is mag compass, outer time [? can't read word]
</li>
<li>dead reckoning - figuring outhere you are between two places you absolutely knoow where you are, like a buoy
</li>
<li>cross lines that you get
</li>
<li>range = where two tings line up
</li>
<li>bearing = looking at single thing
</li>
<li>all boats use mag north
</li>
<li>tide/current is like +- 4 degrees
</li>
<li>90 is the amount of leeway you must allow to the ???
</li>
</ul>
</div>
</li>

<li><a id="sec-1-27-4-2" name="sec-1-27-4-2"></a>tide/current<br  /><div class="outline-text-5" id="text-1-27-4-2">
<ul class="org-ul">
<li>add high and low knoots are added to soundings
</li>
<li>be careful of supertide (goes below)
</li>
<li>hours of tide (roman numerals usu used):
<ol class="org-ol">
<li>1/12 of tide comes in
</li>
<li>3/12
</li>
<li>6/12 (half the tide comes in the middle)
</li>
<li>9/12
</li>
<li>11/12 (slows)
</li>
<li>12/12
</li>
</ol>
</li>
<li>going out: ebbing
</li>
<li>if current against, go shallow
</li>
<li>if with you, go deep
<ul class="org-ul">
<li>deeper water = stronger current
</li>
</ul>
</li>
<li>wind and tide and current: don't have 2 of them against you
</li>
<li>"you plan tides and wind"
</li>
<li>we know about storms 4-5 days in advance
</li>
</ul>
</div>
</li>

<li><a id="sec-1-27-4-3" name="sec-1-27-4-3"></a>weather<br  /><div class="outline-text-5" id="text-1-27-4-3">
<ul class="org-ul">
<li>"anvil clouds" out of NW
<ul class="org-ul">
<li>if seem them, have 30 mins to get to shelter
</li>
<li>turns cold at 10 minutes
</li>
<li>squalls 15-30 min long, 25 knots
</li>
<li>if get caught, drop sails, maybe store them
</li>
</ul>
</li>
<li>everyone runs aground
<ul class="org-ul">
<li>think where you are in the tide cycle, wear lifejacker (if happens)
</li>
<li>keel is the thing usu caught
</li>
</ul>
</li>
<li>"topping lift" = same place a standing halyard, used to keep up the boom
</li>
<li>float plan = just tell somebody when/where going
</li>
<li>coast guard can stop you anytime, "courtesy inspection"
</li>
<li>!!! need as many lifejackets as people, plus throwable
</li>
<li>if motor, needs a fire extinguisher
</li>
<li>must have a lookout at all times (can be the skipper)
</li>
<li>CAN drink on boats, but just can't get hammered
<ul class="org-ul">
<li>no formal BAC amount, but can get in trouble with law if drunk
</li>
</ul>
</li>
<li>big boats
<ul class="org-ul">
<li>1 toot means "leaving you on port", 1 response means "yes", 5 means "no"
</li>
</ul>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-27-4-4" name="sec-1-27-4-4"></a>sail shapes<br  /><div class="outline-text-5" id="text-1-27-4-4">
<ul class="org-ul">
<li>wind at top of sail is much faster
</li>
<li>when wind faster, usu dir is diff
</li>
<li>so far, we've just been using the halyards just to raise sail, but can use it to change shape of jib or main
</li>
<li>loose sails can "hold" wind for longer
</li>
<li>jib down haul - pulls down jib tack to tighten
</li>
<li>pulling Cunningham allows more curvature in main
</li>
<li>can also loosen sail via loosening sail clews
</li>
<li>draft of sail = how curved it is?
</li>
<li>jubs and mains have backstays that can tighten
</li>
<li>jib fairlead (that's the things that you pull the jib lines through)
<ul class="org-ul">
<li>pulling back lets off gas
</li>
</ul>
</li>
<li>twist (in main)
<ul class="org-ul">
<li>raise boom = allows twist
</li>
<li>"boom vang" = triple pulley thing, cxn boom to mast
</li>
<li>!!! "golden rule of sailing" = want top batten and boom aligned
</li>
</ul>
</li>
</ul>
</div>
</li>

<li><a id="sec-1-27-4-5" name="sec-1-27-4-5"></a>buoyage<br  /><div class="outline-text-5" id="text-1-27-4-5">
<ul class="org-ul">
<li>magenta on maps = has a light
</li>
<li>box containing
<ul class="org-ul">
<li>orange/red circle = advisory
</li>
<li>orange/red square = warning
</li>
<li>orange/red diamond = don't go, really bad
</li>
</ul>
</li>
</ul>
</div>
</li></ol>
</div>
</div>

<div id="outline-container-sec-1-28" class="outline-3">
<h3 id="sec-1-28"><span class="section-number-3">1.28</span> lrn-science-curation</h3>
<div class="outline-text-3" id="text-1-28">
</div><div id="outline-container-sec-1-28-1" class="outline-4">
<h4 id="sec-1-28-1"><span class="section-number-4">1.28.1</span> researchgate <a href="https://achilleaskostoulas.com/2014/12/13/researchgate-i-dont-think-so/">https://achilleaskostoulas.com/2014/12/13/researchgate-i-dont-think-so/</a> and <a href="https://www.quora.com/Is-ResearchGate-the-social-network-for-scientists-a-useful-tool">https://www.quora.com/Is-ResearchGate-the-social-network-for-scientists-a-useful-tool</a></h4>
</div>
</div>
<div id="outline-container-sec-1-29" class="outline-3">
<h3 id="sec-1-29"><span class="section-number-3">1.29</span> lrn-science-policy</h3>
<div class="outline-text-3" id="text-1-29">
</div><div id="outline-container-sec-1-29-1" class="outline-4">
<h4 id="sec-1-29-1"><span class="section-number-4">1.29.1</span> criticism of peer review</h4>
<div class="outline-text-4" id="text-1-29-1">
</div><ol class="org-ol"><li><a id="sec-1-29-1-1" name="sec-1-29-1-1"></a><a href="http://blog.mrtz.org/2014/12/15/the-nips-experiment.html">http://blog.mrtz.org/2014/12/15/the-nips-experiment.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-29-2" class="outline-4">
<h4 id="sec-1-29-2"><span class="section-number-4">1.29.2</span> reproducibility crisis</h4>
<div class="outline-text-4" id="text-1-29-2">
</div><ol class="org-ol"><li><a id="sec-1-29-2-1" name="sec-1-29-2-1"></a><a href="https://www.firstthings.com/article/2016/05/scientific-regress">https://www.firstthings.com/article/2016/05/scientific-regress</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-30" class="outline-3">
<h3 id="sec-1-30"><span class="section-number-3">1.30</span> lrn-sociology</h3>
</div>
<div id="outline-container-sec-1-31" class="outline-3">
<h3 id="sec-1-31"><span class="section-number-3">1.31</span> lrn-social-movements</h3>
<div class="outline-text-3" id="text-1-31">
</div><div id="outline-container-sec-1-31-1" class="outline-4">
<h4 id="sec-1-31-1"><span class="section-number-4">1.31.1</span> lrn-activism</h4>
<div class="outline-text-4" id="text-1-31-1">
</div><ol class="org-ol"><li><a id="sec-1-31-1-1" name="sec-1-31-1-1"></a><a href="http://www.showingupforracialjustice.org/about">http://www.showingupforracialjustice.org/about</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-31-2" class="outline-4">
<h4 id="sec-1-31-2"><span class="section-number-4">1.31.2</span> lrn-effective-altruism EA</h4>
<div class="outline-text-4" id="text-1-31-2">
</div><ol class="org-ol"><li><a id="sec-1-31-2-1" name="sec-1-31-2-1"></a><a href="https://en.wikipedia.org/wiki/Open_Philanthropy">https://en.wikipedia.org/wiki/Open_Philanthropy</a> and <a href="http://www.openphilanthropy.org/">http://www.openphilanthropy.org/</a><br  /></li>
<li><a id="sec-1-31-2-2" name="sec-1-31-2-2"></a><a href="http://www.givewell.org/labs/causes">http://www.givewell.org/labs/causes</a><br  /></li>
<li><a id="sec-1-31-2-3" name="sec-1-31-2-3"></a><a href="http://www.goodventures.org/">http://www.goodventures.org/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-31-3" class="outline-4">
<h4 id="sec-1-31-3"><span class="section-number-4">1.31.3</span> lrn-feminism</h4>
<div class="outline-text-4" id="text-1-31-3">
</div><ol class="org-ol"><li><a id="sec-1-31-3-1" name="sec-1-31-3-1"></a><a href="http://geekfeminism.wikia.com/wiki/resources_for_allies">http://geekfeminism.wikia.com/wiki/resources_for_allies</a><br  /></li>
<li><a id="sec-1-31-3-2" name="sec-1-31-3-2"></a><a href="https://www.reddit.com/r/Feminism/comments/x9hkv/quintessential_feminist_literature/c5ke6l2">https://www.reddit.com/r/Feminism/comments/x9hkv/quintessential_feminist_literature/c5ke6l2</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-31-4" class="outline-4">
<h4 id="sec-1-31-4"><span class="section-number-4">1.31.4</span> lrn-labor-rights</h4>
<div class="outline-text-4" id="text-1-31-4">
</div><ol class="org-ol"><li><a id="sec-1-31-4-1" name="sec-1-31-4-1"></a>california programming overtime rules <a href="http://www.gotovertime.com/computer_pro.html">http://www.gotovertime.com/computer_pro.html</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-31-5" class="outline-4">
<h4 id="sec-1-31-5"><span class="section-number-4">1.31.5</span> lrn-lrning</h4>
<div class="outline-text-4" id="text-1-31-5">
</div><ol class="org-ol"><li><a id="sec-1-31-5-1" name="sec-1-31-5-1"></a><a href="https://opencourser.com/">https://opencourser.com/</a><br  /></li>
<li><a id="sec-1-31-5-2" name="sec-1-31-5-2"></a><a href="http://noexcuselist.com/">http://noexcuselist.com/</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-31-6" class="outline-4">
<h4 id="sec-1-31-6"><span class="section-number-4">1.31.6</span> lrn-quantified-self</h4>
<div class="outline-text-4" id="text-1-31-6">
</div><ol class="org-ol"><li><a id="sec-1-31-6-1" name="sec-1-31-6-1"></a><a href="http://technori.com/2013/04/4281-the-beginners-guide-to-quantified-self-plus-a-list-of-the-best-personal-data-tools-out-there/">http://technori.com/2013/04/4281-the-beginners-guide-to-quantified-self-plus-a-list-of-the-best-personal-data-tools-out-there/</a><br  /></li>
<li><a id="sec-1-31-6-2" name="sec-1-31-6-2"></a>zuzka's QS list<br  /><ol class="org-ol"><li><a id="sec-1-31-6-2-1" name="sec-1-31-6-2-1"></a><a href="http://www.producthunt.com/@bellebcooper/collections/quantified-self-software?utm_source=Product+Hunt&utm_campaign=b41e411581-Quantified_self_tools_8_30_2015&utm_medium=email&utm_term=0_2cd7d34185-b41e411581-121170245">http://www.producthunt.com/@bellebcooper/collections/quantified-self-software?utm_source=Product+Hunt&utm_campaign=b41e411581-Quantified_self_tools_8_30_2015&utm_medium=email&utm_term=0_2cd7d34185-b41e411581-121170245</a><br  /></li>
<li><a id="sec-1-31-6-2-2" name="sec-1-31-6-2-2"></a><a href="http://www.thewalkgame.com/">http://www.thewalkgame.com/</a><br  /></li>
<li><a id="sec-1-31-6-2-3" name="sec-1-31-6-2-3"></a><a href="https://exist.io/?ref=producthunt">https://exist.io/?ref=producthunt</a><br  /></li>
<li><a id="sec-1-31-6-2-4" name="sec-1-31-6-2-4"></a><a href="https://www.microsoft.com/en-us/store/apps/tep-tracker/9wzdncrcv7g7?ref=producthunt">https://www.microsoft.com/en-us/store/apps/tep-tracker/9wzdncrcv7g7?ref=producthunt</a><br  /></li>
<li><a id="sec-1-31-6-2-5" name="sec-1-31-6-2-5"></a><a href="http://habitlist.com/?ref=producthunt">http://habitlist.com/?ref=producthunt</a><br  /></li>
<li><a id="sec-1-31-6-2-6" name="sec-1-31-6-2-6"></a><a href="http://betterposture.co/">http://betterposture.co/</a><br  /></li></ol>
</li></ol>
</div>
<div id="outline-container-sec-1-31-7" class="outline-4">
<h4 id="sec-1-31-7"><span class="section-number-4">1.31.7</span> lrn-transhumanism</h4>
<div class="outline-text-4" id="text-1-31-7">
</div><ol class="org-ol"><li><a id="sec-1-31-7-1" name="sec-1-31-7-1"></a>(sync'd) <a href="http://www.aleph.se/Trans/Cultural/Philosophy/">http://www.aleph.se/Trans/Cultural/Philosophy/</a><br  /></li>
<li><a id="sec-1-31-7-2" name="sec-1-31-7-2"></a>(sync'd) <a href="http://www.aleph.se/Trans/Global/Uploading/">http://www.aleph.se/Trans/Global/Uploading/</a><br  /></li>
<li><a id="sec-1-31-7-3" name="sec-1-31-7-3"></a><a href="http://www.simulation-argument.com/">http://www.simulation-argument.com/</a><br  /></li>
<li><a id="sec-1-31-7-4" name="sec-1-31-7-4"></a>(sync'd 20160627) <a href="http://www.minduploading.org/articles/">http://www.minduploading.org/articles/</a><br  /></li>
<li><a id="sec-1-31-7-5" name="sec-1-31-7-5"></a><a href="http://www.theneuroethicsblog.com/2016/11/the-2016-kavli-futures-symposium_15.htm">http://www.theneuroethicsblog.com/2016/11/the-2016-kavli-futures-symposium_15.htm</a><br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-32" class="outline-3">
<h3 id="sec-1-32"><span class="section-number-3">1.32</span> lrn-studying lrn-reading</h3>
<div class="outline-text-3" id="text-1-32">
</div><div id="outline-container-sec-1-32-1" class="outline-4">
<h4 id="sec-1-32-1"><span class="section-number-4">1.32.1</span> PQRST system - Preview, Question, Read, Summary, Test</h4>
</div>
<div id="outline-container-sec-1-32-2" class="outline-4">
<h4 id="sec-1-32-2"><span class="section-number-4">1.32.2</span> Studying for Science, in calibre</h4>
</div>
<div id="outline-container-sec-1-32-3" class="outline-4">
<h4 id="sec-1-32-3"><span class="section-number-4">1.32.3</span> <a href="http://lemire.me/blog/archives/2014/12/30/how-to-learn-efficiently/">http://lemire.me/blog/archives/2014/12/30/how-to-learn-efficiently/</a></h4>
</div>
<div id="outline-container-sec-1-32-4" class="outline-4">
<h4 id="sec-1-32-4"><span class="section-number-4">1.32.4</span> how to read a book</h4>
<div class="outline-text-4" id="text-1-32-4">
</div><ol class="org-ol"><li><a id="sec-1-32-4-1" name="sec-1-32-4-1"></a>follow your own goals<br  /></li>
<li><a id="sec-1-32-4-2" name="sec-1-32-4-2"></a>first read overview/discovery, second for detail and understanding, third for notes which he means exec summary in your own words about all major points - discovery should be very small, just major things<br  /></li>
<li><a id="sec-1-32-4-3" name="sec-1-32-4-3"></a>use multiple "modes" for review, like talking, visualizing<br  /></li>
<li><a id="sec-1-32-4-4" name="sec-1-32-4-4"></a>author context<br  /></li>
<li><a id="sec-1-32-4-5" name="sec-1-32-4-5"></a>general arguments are far more important than details<br  /></li>
<li><a id="sec-1-32-4-6" name="sec-1-32-4-6"></a>know how long you're going to read<br  /></li>
<li><a id="sec-1-32-4-7" name="sec-1-32-4-7"></a>read as if you imagine you're going to have formal argu with author<br  /></li>
<li><a id="sec-1-32-4-8" name="sec-1-32-4-8"></a>one hour (and an initial fifteen for easing in) is a good time for concentration. 3 1hr sess are better than 1 3 hr sess<br  /></li>
<li><a id="sec-1-32-4-9" name="sec-1-32-4-9"></a>actually estimate times for reading!<br  /></li>
<li><a id="sec-1-32-4-10" name="sec-1-32-4-10"></a>prefer margin notes that summ over highlights. And if highlighting, only words not sentences-want to minimize reread<br  /></li>
<li><a id="sec-1-32-4-11" name="sec-1-32-4-11"></a>[standalone mental rehearsal?]<br  /></li>
<li><a id="sec-1-32-4-12" name="sec-1-32-4-12"></a>these techniques will get better over a few months!<br  /></li></ol>
</div>
<div id="outline-container-sec-1-32-5" class="outline-4">
<h4 id="sec-1-32-5"><span class="section-number-4">1.32.5</span> lrn-trackers</h4>
<div class="outline-text-4" id="text-1-32-5">
</div><ol class="org-ol"><li><a id="sec-1-32-5-1" name="sec-1-32-5-1"></a><a href="http://www.reddit.com/r/trackers/comments/hrgmv/tracker_with_pdfsebooks_of_college_textbooks/c1xrq44">http://www.reddit.com/r/trackers/comments/hrgmv/tracker_with_pdfsebooks_of_college_textbooks/c1xrq44</a><br  /></li>
<li><a id="sec-1-32-5-2" name="sec-1-32-5-2"></a><a href="http://www.calvinshub.com/2008/11/how-to-download-e-books-from-mirc">http://www.calvinshub.com/2008/11/how-to-download-e-books-from-mirc</a><br  /></li>
<li><a id="sec-1-32-5-3" name="sec-1-32-5-3"></a>libgen <a href="https://sites.google.com/site/themetalibrary/library-genesis">https://sites.google.com/site/themetalibrary/library-genesis</a> ?<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-33" class="outline-3">
<h3 id="sec-1-33"><span class="section-number-3">1.33</span> lrn-symbolic-logic</h3>
<div class="outline-text-3" id="text-1-33">
</div><div id="outline-container-sec-1-33-1" class="outline-4">
<h4 id="sec-1-33-1"><span class="section-number-4">1.33.1</span> learn symbolic regression</h4>
</div>
<div id="outline-container-sec-1-33-2" class="outline-4">
<h4 id="sec-1-33-2"><span class="section-number-4">1.33.2</span> jason's idea to optimize models based on fundamental laws of physical systems derived from symbolic logic,</h4>
<div class="outline-text-4" id="text-1-33-2">
</div><ol class="org-ol"><li><a id="sec-1-33-2-1" name="sec-1-33-2-1"></a>read schmidt, m., &amp; lipson, h. (2009). distilling free-form natural laws from experimental data. <span class="underline">science</span>, _324<sub>(5923)</sub>, 81–85. <a href="10.1126/science.1165893">10.1126/science.1165893</a><br  /></li>
<li><a id="sec-1-33-2-2" name="sec-1-33-2-2"></a>his email:by the way, when i've seen it used, the term "model optimization" usually refers to "parameter optimization".i'm using "model optimization" to refer to the optimization of the mathematical form of the model (i.e., the same way statisticians discuss finding the best statistical distribution to model data).<br  /></li>
<li><a id="sec-1-33-2-3" name="sec-1-33-2-3"></a>continuation:ok, one more addition - in practice, when statisticians talk about choosing the best distribution to model data, they are choosing a distribution from a discrete set where the choice is based on known properties of the different distributions.when i say "model optimization", i'm thinking more of an optimization by the <b>incremental variation</b> of a mathematical form (than property-based selection from a discrete set).however, if i were debating myself, i would point out that most distributions used in applied statistics are actually derivable from the gamma distribution (a well-known fact considered in the theoretical domain).thus, the continuous variation of gamma distribution parameters will sweep a range of mathematical forms (= that are commonly applied distributions) that could be optimized in the same sense i was describing.haha, ok, enough of that.<br  /></li></ol>
</div>
</div>
<div id="outline-container-sec-1-34" class="outline-3">
<h3 id="sec-1-34"><span class="section-number-3">1.34</span> lrn-teaching</h3>
<div class="outline-text-3" id="text-1-34">
</div><div id="outline-container-sec-1-34-1" class="outline-4">
<h4 id="sec-1-34-1"><span class="section-number-4">1.34.1</span> avery's first-year grad school teacher starts class with an open ended question, and connects people's answers in a web through discussion, and then saves and posts to the web</h4>
</div>
</div>
<div id="outline-container-sec-1-35" class="outline-3">
<h3 id="sec-1-35"><span class="section-number-3">1.35</span> lrn-traveling</h3>
<div class="outline-text-3" id="text-1-35">
</div><div id="outline-container-sec-1-35-1" class="outline-4">
<h4 id="sec-1-35-1"><span class="section-number-4">1.35.1</span> eventually should learn air deals via <a href="http://www.reddit.com/r/IAmA/comments/v82rz/iama_deltaklmai%20r_france_reservation_agent_that/">http://www.reddit.com/r/IAmA/comments/v82rz/iama_deltaklmai%20r_france_reservation_agent_that/</a></h4>
</div>
<div id="outline-container-sec-1-35-2" class="outline-4">
<h4 id="sec-1-35-2"><span class="section-number-4">1.35.2</span> can track trends via <a href="http://www.expedia.com/daily/trend_tracker">http://www.expedia.com/daily/trend_tracker</a></h4>
</div>
</div>
<div id="outline-container-sec-1-36" class="outline-3">
<h3 id="sec-1-36"><span class="section-number-3">1.36</span> lrn-writing</h3>
<div class="outline-text-3" id="text-1-36">
</div><div id="outline-container-sec-1-36-1" class="outline-4">
<h4 id="sec-1-36-1"><span class="section-number-4">1.36.1</span> <a href="http://splasho.com/upgoer5/">http://splasho.com/upgoer5/</a></h4>
</div>
<div id="outline-container-sec-1-36-2" class="outline-4">
<h4 id="sec-1-36-2"><span class="section-number-4">1.36.2</span> brian nosek says In writing, lead with the evidence, follow with the explanation.</h4>
</div>
<div id="outline-container-sec-1-36-3" class="outline-4">
<h4 id="sec-1-36-3"><span class="section-number-4">1.36.3</span> writing essay to eric denovellis after briefly reading chapters of his thesis:</h4>
<div class="outline-text-4" id="text-1-36-3">
<p>
(tl;dr: you often write sentences with many clauses, just like I do. For several reasons listed, it's probably a better idea to break most or ALL of those sentences with multiple clauses down into individual sentences.)
</p>

<p>
essay:
</p>

<p>
Also, do as I preach, not as I do. All this writing below is cursed by what exactly I'm saying that neither of us should do, but that we tend to do.
</p>

<p>
simplify, simplify, simplify &#x2013; you write a ton like how I natively write, specifically subjects with lots of adjectives/etc., like 'context-relevant sensorimotor information'. Recently, Nancy did more than tear apart my attempt at an SFN abstract, to the point where she effectively rewrote the whole thing - and I couldn't deny that what she wrote was way more understandable. The key difference was shorter sentences. Much of the time I would be trying to say very, very related things together within the same sentence, since the science itself flows between them, but every single clause you add to a sentence adds SO much overhead if the person only 90% truly grasps what you said in the first clause.
</p>

<p>
Honestly, multiple-clause stuff is probably fine in a thesis (where the main readers ARE going to be able to directly follow you easily since they have maybe even already read the papers you're discussing) . But if there's one thing that stuck out to me when I was doing a direct comparison between my writing (very similar to this) and Nancy's for the same piece of writing, was (being brutally honest here), how STUPID the latter was. I mean that the latter was better written, but honestly the grammar was so simple that a child could have read it, it was SO plain. There were many more short sentences, but just like a function, each one served one purpose and one purpose only. I tried thinking "how do i change my perspective to write like this" and honestly the first thought in my head was "write it like you would for someone super super dumb"&#x2026;and that's both horrifying that that was my thought, but also that was what made it great! As you read the simplistic version, your head responded like "Okay. Okay. Yeah. Well, yeah that follows. Yeah. uh-huh. Yep."
</p>

<p>
By looking at the multiple clause sentences like right here at the end of page 91, i see the same thing I do natively, which I have to edit it out. Splitting up all these super-related clauses will, yes, make it sound less "professional" or academic&#x2026;but I think that's because it exactly makes it SIMPLER, and I'm of the opinion now that that helps the reader understand the stuff better than ANYTHING else.
</p>

<p>
The very pseudoscientific way I think of it is, imagine your brain, the compartmentalization/compression of each of these major points is probably FAR better in your brain than in mine &#x2013; you've read these papers multiple times or at least have kicked around the key points and obvious things from the writing in your head for years, almost like you think of each of the ideas as if they are individual words. You encapsulate them in your mind very well, because you've spent years in grad school obsessing over these and related ideas. To someone else, even someone who is familiar (but not as much) with the work, each of these major points are going to be more like sentences. When I read "task demands' expected values increase" I have to process it, like "okay, the subject is task demands [which part is that in? let me look back a few sentences]&#x2026;okay&#x2026;now, what's it doing?". To you (just like propofol phase-amplitude coupling to me), that entire clause is a single "idea", fully encapsulated, but to someone else, it's an unknown connection between the subject, what's it's doing, and how that's different than a very similar effect on the same subject or vice versa, nevermind anatomical localizations. By the time I get to the next clause, I may (and was) still trying to process the first "connection" or result, as that's literally the first time I've been hit with it, and I need to learn it in order to move on. If two major points/results (from papers) are different clauses in the same sentence, then in all likelihood i'm still going to be trying to figure out what you exactly mean by the first as I'm moving onto the second, and then I'm trying to build two different connection/result ideas in my head, etc. Furthermore, I'm not going to have any idea if the second clause REQUIRES the first clause, or if they're completely independent (as they most of the time are).
</p>

<p>
I think that, to someone who has extensively embedded such ideas in their head, each of these results/clauses are going to seem like single entities to them. For the same reason, several of these are going to be related, and it's going to be obvious that "result 1 is important, and result 2 is tied to result 1 so result 2 is this". But for the lay person, it's nontrivial just to figure out what result 1 is and all it entails, and putting more results in the same sentence is going to force them to almost try to parallelize figuring out results 1-3. I'm not saying this is a run-on since it's not, it's just a long sentence, but I think my pseudoscientific bullshit explanation above is a big part of why academics (people who understand a particular idea really, really, obsessively well) write such long sentences. YOU understand that "Ax=B" is Thereom 1, and so you say "Thm1, and Thm2, and Thm3", but for lay person seeing "Ax=B" the first time, it's harder on them than it is on you for understanding that the first time they see it. The "academic" way of writing would be this really long sentence (except in mathematics&#x2026;but we'll get to that), but I think the "simpler" way of splitting it up into, say, individual theorems that the reader attacks one at a time, goes a LONGGG way towards simplicity. That may actually be part of why Nancy's version of my writing was so much clearer: the separation between what constituted individual "ideas" is so much cleaner, almost like how math manuscripts don't go "Thm 1 =&gt; Thm 2 =&gt; Thm 3", but instead treat each of them one at a time. Separating by sentences also tells the reader "you don't need Thm1 to understand Thm2, as they're independent, and you can take all the time you want just to focus on the full sentence that is Thm1" Then, later, when you actually DO need Thm1 AND Thm2 to imply Thm3, you can refer to them using MUCH simpler terminology.
</p>

<p>
I'm sending you both my and Nancy's abstracts so you can see the differences/superiority I'm talking about; honestly, it was a super good exercise for my understanding of writing differences to compare/contrast them. Doing so convinced me that 1. her way is better, and 2. it's just plain simpler. Just making the sentences shorter overall makes each of them THAT much easier to understand. It can almost make you sound like a simplistic robot, but the separation of ideas reduces cognitive load SO MUCH that I'm currently of the opinion that that is the MOST IMPORTANT thing to change in my own writing. And because you seem to write VERY similar to how I do, I think that same change seems relevant.
</p>
</div>
</div>

<div id="outline-container-sec-1-36-4" class="outline-4">
<h4 id="sec-1-36-4"><span class="section-number-4">1.36.4</span> A manual for writers Kate l turabian</h4>
</div>
<div id="outline-container-sec-1-36-5" class="outline-4">
<h4 id="sec-1-36-5"><span class="section-number-4">1.36.5</span> lrn-writing-systems/software! currently using pandoc</h4>
<div class="outline-text-4" id="text-1-36-5">
</div><ol class="org-ol"><li><a id="sec-1-36-5-1" name="sec-1-36-5-1"></a><a href="http://hn.premii.com/#/comments/11223520">The Plain Person’s Guide to Plain Text Social Science</a><br  /></li></ol>
</div>
<div id="outline-container-sec-1-36-6" class="outline-4">
<h4 id="sec-1-36-6"><span class="section-number-4">1.36.6</span> lrn-sci-writing</h4>
<div class="outline-text-4" id="text-1-36-6">
</div><ol class="org-ol"><li><a id="sec-1-36-6-1" name="sec-1-36-6-1"></a><a href="https://medium.com/advice-and-help-in-authoring-a-phd-or-non-fiction/how-to-write-paragraphs-80781e2f3054">https://medium.com/advice-and-help-in-authoring-a-phd-or-non-fiction/how-to-write-paragraphs-80781e2f3054</a><br  /></li>
<li><a id="sec-1-36-6-2" name="sec-1-36-6-2"></a><a href="https://corticalia.wordpress.com/2018/02/26/how-to-write/">https://corticalia.wordpress.com/2018/02/26/how-to-write/</a><br  /></li>
<li><a id="sec-1-36-6-3" name="sec-1-36-6-3"></a>notes on "The Science of Scientific Writing", American Scientist, 1990<br  /><ol class="org-ol"><li><a id="sec-1-36-6-3-1" name="sec-1-36-6-3-1"></a>1. expectation: minimize distance b/w subject and verb<br  /></li>
<li><a id="sec-1-36-6-3-2" name="sec-1-36-6-3-2"></a>2. make each sentence ("unit of discourse", e.g. everything before a semicolon) on one thing and one thing only, or serve a single function, or make a single point<br  /></li>
<li><a id="sec-1-36-6-3-3" name="sec-1-36-6-3-3"></a>3. stress position/emphasis: put most important stuff at end of sentence<br  /></li>
<li><a id="sec-1-36-6-3-4" name="sec-1-36-6-3-4"></a>use the beginning of sentences to serve as "topic position" either for linkage to previously established material or predicting future points<br  /><ol class="org-ol"><li><a id="sec-1-36-6-3-4-1" name="sec-1-36-6-3-4-1"></a>BUT don't start sentences constantly with brand-new ideas that haven't been introduced yet<br  /></li>
<li><a id="sec-1-36-6-3-4-2" name="sec-1-36-6-3-4-2"></a>don't use the begininng of sentences to give things their first appearance<br  /></li></ol>
</li>
<li><a id="sec-1-36-6-3-5" name="sec-1-36-6-3-5"></a>"a sentence is too long when it has more candidates for stress positions than there are stress positions available"<br  /></li>
<li><a id="sec-1-36-6-3-6" name="sec-1-36-6-3-6"></a>number 1 problem in professional writing: misplacement of old and new (to the reader) information<br  /></li>
<li><a id="sec-1-36-6-3-7" name="sec-1-36-6-3-7"></a>[like i suspected] put OLD information at beginning topic position, put NEW information at ending stress position<br  /></li>
<li><a id="sec-1-36-6-3-8" name="sec-1-36-6-3-8"></a>always make sure to include connections to older information (linkages)<br  /></li>
<li><a id="sec-1-36-6-3-9" name="sec-1-36-6-3-9"></a>they consistently list out the main verbs of each sentence to examine the structure of the abstract<br  /></li>
<li><a id="sec-1-36-6-3-10" name="sec-1-36-6-3-10"></a>"articulate the action of every sentence in its verb"<br  /></li>
<li><a id="sec-1-36-6-3-11" name="sec-1-36-6-3-11"></a>provide context before giving new information<br  /></li></ol>
</li>
<li><a id="sec-1-36-6-4" name="sec-1-36-6-4"></a>Purdon, Patrick on writing sci papers: "methods first, then results then&#x2026;whatever intro/disc"<br  /></li>
<li><a id="sec-1-36-6-5" name="sec-1-36-6-5"></a><a href="http://www.northwestern.edu/climb/resources/written-communication/">http://www.northwestern.edu/climb/resources/written-communication/</a><br  /></li>
<li><a id="sec-1-36-6-6" name="sec-1-36-6-6"></a><a href="https://cgi.duke.edu/web/sciwriting/">https://cgi.duke.edu/web/sciwriting/</a><br  /></li>
<li><a id="sec-1-36-6-7" name="sec-1-36-6-7"></a><a href="https://simplystatistics.org/2016/04/21/writing/">https://simplystatistics.org/2016/04/21/writing/</a><br  /></li></ol>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="author">Author: wintermute</p>
<p class="date">Created: 2018-03-23 Fri 17:49</p>
<p class="creator"><a href="http://www.gnu.org/software/emacs/">Emacs</a> 25.1.1 (<a href="http://orgmode.org">Org</a> mode 8.2.10)</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>