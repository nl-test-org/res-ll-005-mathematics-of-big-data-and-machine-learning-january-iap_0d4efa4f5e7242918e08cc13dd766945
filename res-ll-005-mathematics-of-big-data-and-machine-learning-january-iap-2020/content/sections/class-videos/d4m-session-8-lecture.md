---
about_this_resource_text: <h2 class="subhead">Description</h2> <p>Theory of Kronecker
  graphs. Database ingest performance and database query performance. Array multiplication
  performance.</p> <p><strong>Instructor:</strong> Jeremy Kepner</p>
course_id: res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020
embedded_media:
- id: Video-YouTube-Stream
  media_location: MTakzGAhYvo
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Video-YouTube-Stream
  type: Video
  uid: f62f7845d6c800abdbbdf3f3749d1db4
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/MTakzGAhYvo/default.jpg
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1d97b999b81a3b3427582e246c5231b1
- id: 3Play-3PlayYouTubeid-MP4
  media_location: MTakzGAhYvo
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 302d71008001070b010374481ac85568
- id: MTakzGAhYvo.srt
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/d4m-session-8-lecture/MTakzGAhYvo.srt
  title: 3play caption file
  type: null
  uid: 1bb1ae7d93c45355e3dea82db44e6ff9
- id: MTakzGAhYvo.pdf
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/d4m-session-8-lecture/MTakzGAhYvo.pdf
  title: 3play pdf file
  type: null
  uid: 6e0bea3ebe68c1f470613d13599f101e
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 30f9aa3e91c7aaf42d9b180a9cefb5d7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 493a9f5681f28203a4509847e753de33
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1103408272
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Video-iTunes U-MP4
  type: Video
  uid: a0c54bde2e613218a3933c52514ff3d8
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITRESLL-005F12/MITRESLL-005F12_L07_Lec_300k.mp4
  parent_uid: 6e30eb0751acbd43196ff5b47508d2ff
  title: Video-Internet Archive-MP4
  type: Video
  uid: 52c189e103cfaf4f40134cbed293482d
inline_embed_id: 4293892d4msession8lecture26193836
layout: video
order_index: null
parent_uid: 22ed3115fb6b8a6bf2e9075e053e3953
related_resources_text: ''
short_url: d4m-session-8-lecture
technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/d4m-session-8-lecture
template_type: Tabbed
title: D4M Session 8 Lecture
transcript: '<p><span m="110">The</span> <span m="170">following</span> <span m="610">content</span>
  <span m="1120">is</span> <span m="1230">provided</span> <span m="1670">under</span>
  <span m="1940">a</span> <span m="1980">Creative</span> <span m="2430">Commons</span>
  <span m="2830">license.</span> <span m="3810">Your</span> <span m="3920">support</span>
  <span m="4410">will</span> <span m="4560">help</span> <span m="4840">MIT</span>
  <span m="5310">OpenCourseWare</span> <span m="6050">continue</span> <span m="6540">to</span>
  <span m="6690">offer</span> <span m="7000">high</span> <span m="7210">quality</span>
  <span m="7720">educational</span> <span m="8360">resources</span> <span m="8950">for</span>
  <span m="9080">free.</span> <span m="10160">To</span> <span m="10260">make</span>
  <span m="10350">a</span> <span m="10400">donation</span> <span m="11180">or</span>
  <span m="11330">to</span> <span m="11450">view</span> <span m="11660">additional</span>
  <span m="12070">materials</span> <span m="12700">from</span> <span m="12860">hundreds</span>
  <span m="13200">of</span> <span m="13300">MIT</span> <span m="13680">courses,</span>
  <span m="15000">visit</span> <span m="15160">MIT</span> <span m="16800">OpenCourseWare</span>
  <span m="18060">at</span> <span m="18520">ocw.mit.edu.</span></p><p><span m="21390">PROFESSOR:
  What</span> <span m="21580">we''re</span> <span m="21720">going</span> <span m="21820">to</span>
  <span m="21880">talk</span> <span m="22130">about</span> <span m="22360">today</span>
  <span m="22910">is</span> <span m="23470">in</span> <span m="23680">the</span> <span
  m="24180">previous</span> <span m="24590">class,</span> <span m="25440">we</span>
  <span m="25450">did</span> <span m="25570">a</span> <span m="25640">lot</span> <span
  m="26020">of</span> <span m="26600">examples</span> <span m="27500">on</span> <span
  m="27710">some</span> <span m="27880">data</span> <span m="28150">sets.</span> <span
  m="30800">And</span> <span m="32030">they</span> <span m="32170">were</span> <span
  m="32299">artificially</span> <span m="33880">generated</span> <span m="34390">data</span>
  <span m="34640">sets,</span> <span m="35810">which</span> <span m="36030">is</span>
  <span m="36570">a</span> <span m="36660">requirement</span> <span m="37390">in</span>
  <span m="37540">terms</span> <span m="37920">of</span> <span m="38180">if</span>
  <span m="38410">you</span> <span m="38530">want</span> <span m="38790">to</span>
  <span m="38870">do</span> <span m="39060">anything</span> <span m="39460">with</span>
  <span m="39630">big</span> <span m="39870">data</span> <span m="40170">and</span>
  <span m="40420">really</span> <span m="40610">show</span> <span m="41010">stuff,</span>
  <span m="41960">it</span> <span m="42210">can</span> <span m="42340">be</span> <span
  m="42470">really</span> <span m="42720">difficult</span> <span m="43220">to</span>
  <span m="43320">pass</span> <span m="43690">around</span> <span m="44960">terabytes</span>
  <span m="45290">and</span> <span m="45410">terabytes</span> <span m="45930">of</span>
  <span m="46030">data.</span> <span m="46790">So</span> <span m="46980">having</span>
  <span m="47300">data</span> <span m="47580">generators</span> <span m="48370">that</span>
  <span m="48890">generate</span> <span m="49480">the</span> <span m="49560">statistics</span>
  <span m="50270">that</span> <span m="50420">you</span> <span m="50580">want</span>
  <span m="51520">or</span> <span m="51640">approximate</span> <span m="51950">the</span>
  <span m="52260">statistics</span> <span m="52790">that</span> <span m="52890">you</span>
  <span m="53010">want</span> <span m="53340">are</span> <span m="53480">good</span>
  <span m="53630">to</span> <span m="53700">have.</span> <span m="54050">We</span>
  <span m="54550">had</span> <span m="54640">a</span> <span m="54730">previous</span>
  <span m="55190">lecture</span> <span m="55770">on</span> <span m="56040">power</span>
  <span m="56350">law</span> <span m="56570">graphs</span> <span m="57060">and</span>
  <span m="57170">talked</span> <span m="57410">about</span> <span m="57570">a</span>
  <span m="57620">perfect</span> <span m="57900">[AUDIO OUT]</span> <span m="58180">is</span>
  <span m="58400">very</span> <span m="58670">useful,</span> <span m="58940">and I</span>
  <span m="59210">encourage</span> <span m="59610">you</span> <span m="59710">to</span>
  <span m="59760">use</span> <span m="60050">that.</span> <span m="60350">It''s</span>
  <span m="60520">a</span> <span m="60590">useful</span> <span m="60970">analytic</span>
  <span m="61370">tool.</span></p><p><span m="62360">This</span> <span m="62570">one,</span>
  <span m="62710">we''re</span> <span m="62830">going</span> <span m="62940">to</span>
  <span m="62980">talk</span> <span m="63090">about</span> <span m="63300">Kronecker</span>
  <span m="63820">graphs</span> <span m="64500">and</span> <span m="65570">generation.</span>
  <span m="66360">Kronecker</span> <span m="66800">graphs</span> <span m="67230">are</span>
  <span m="67330">used</span> <span m="67840">in</span> <span m="67900">the</span>
  <span m="68000">largest</span> <span m="69150">benchmark</span> <span m="70020">in</span>
  <span m="70120">the</span> <span m="70250">world</span> <span m="71140">for</span>
  <span m="71250">benchmarking</span> <span m="72010">graph</span> <span m="72620">systems.</span>
  <span m="73610">And</span> <span m="73710">then</span> <span m="73840">finally,</span>
  <span m="74280">I''m</span> <span m="74350">going</span> <span m="74450">to</span>
  <span m="74510">talk</span> <span m="74780">a</span> <span m="74830">little</span>
  <span m="75030">bit</span> <span m="75170">about</span> <span m="75380">performance.</span>
  <span m="76890">What</span> <span m="77200">are</span> <span m="77260">the</span>
  <span m="77390">things</span> <span m="77610">you</span> <span m="77710">should</span>
  <span m="77880">be</span> <span m="78000">aware</span> <span m="78430">of</span>
  <span m="79460">when</span> <span m="80070">you''re</span> <span m="80210">doing</span>
  <span m="81210">systems</span> <span m="81870">and</span> <span m="81980">building</span>
  <span m="82320">systems</span> <span m="82780">from a</span> <span m="82970">performance</span>
  <span m="83510">perspective,</span> <span m="84160">the</span> <span m="84260">kinds</span>
  <span m="84470">of</span> <span m="84580">things</span> <span m="84890">that</span>
  <span m="84990">are</span> <span m="85290">essentially</span> <span m="85830">fundamental</span>
  <span m="86290">limits</span> <span m="86580">of</span> <span m="86650">the</span>
  <span m="86740">technology.</span></p><p><span m="89150">So</span> <span m="89310">moving</span>
  <span m="89880">forward,</span> <span m="90670">let''s</span> <span m="90930">talk</span>
  <span m="91240">about</span> <span m="92890">the</span> <span m="93490">Graph500</span>
  <span m="95970">benchmark.</span> <span m="97740">So</span> <span m="98650">the</span>
  <span m="98750">Graph500</span> <span m="99460">benchmark</span> <span m="100150">was</span>
  <span m="100500">created</span> <span m="101420">to</span> <span m="103690">provide</span>
  <span m="104130">a</span> <span m="104190">mechanism</span> <span m="105400">for</span>
  <span m="106100">timing</span> <span m="107240">the</span> <span m="107370">world''s</span>
  <span m="107720">most</span> <span m="107960">powerful</span> <span m="108370">computers</span>
  <span m="109090">and</span> <span m="109240">see</span> <span m="109380">how</span>
  <span m="109730">good</span> <span m="109990">they</span> <span m="110090">were</span>
  <span m="110470">on</span> <span m="112430">graph</span> <span m="112980">type</span>
  <span m="113270">operations.</span> <span m="114680">And</span> <span m="115290">so</span>
  <span m="115500">I</span> <span m="115660">was</span> <span m="115850">involved</span>
  <span m="116550">and</span> <span m="116630">actually</span> <span m="116940">wrote</span>
  <span m="117230">some</span> <span m="117420">of the</span> <span m="117540">initial</span>
  <span m="117850">code</span> <span m="118760">for</span> <span m="118930">this</span>
  <span m="119160">benchmark</span> <span m="119790">about</span> <span m="120930">5</span>
  <span m="121130">or</span> <span m="121200">10</span> <span m="121400">years</span>
  <span m="121640">ago.</span> <span m="122480">And</span> <span m="123530">it''s</span>
  <span m="123680">now</span> <span m="123780">become</span> <span m="124110">a</span>
  <span m="124180">community</span> <span m="125360">effort,</span> <span m="125850">and</span>
  <span m="125900">the</span> <span m="125990">code</span> <span m="126240">has</span>
  <span m="126370">changed,</span> <span m="127050">and</span> <span m="127240">other</span>
  <span m="127430">types</span> <span m="127710">of</span> <span m="127820">things.</span></p><p><span
  m="129810">And</span> <span m="131070">it''s</span> <span m="131250">mainly</span>
  <span m="131780">meant</span> <span m="132250">for</span> <span m="132400">dealing</span>
  <span m="132760">with</span> <span m="132990">parallel</span> <span m="133950">in-memory</span>
  <span m="134520">computations,</span> <span m="135850">but</span> <span m="136160">the</span>
  <span m="136250">benchmark</span> <span m="136750">is</span> <span m="136870">actually</span>
  <span m="137250">very</span> <span m="137530">useful</span> <span m="137950">for</span>
  <span m="138320">timing</span> <span m="138780">databases</span> <span m="139660">or</span>
  <span m="139840">any</span> <span m="140040">types</span> <span m="140370">of</span>
  <span m="140550">things.</span> <span m="140810">You</span> <span m="140920">can</span>
  <span m="141040">do</span> <span m="141140">the</span> <span m="141230">exact</span>
  <span m="141610">same</span> <span m="141860">operations.</span> <span m="143240">So</span>
  <span m="144030">it</span> <span m="144230">generates</span> <span m="144820">data,</span>
  <span m="145110">and</span> <span m="145365">then</span> <span m="145620">it</span>
  <span m="145700">has</span> <span m="145960">you</span> <span m="146150">construct</span>
  <span m="146485">it</span> <span m="146820">in</span> <span m="146950">a</span>
  <span m="147010">graph,</span> <span m="147420">and</span> <span m="147490">then</span>
  <span m="147600">it</span> <span m="147660">goes</span> <span m="147870">on</span>
  <span m="148030">to</span> <span m="148100">do</span> <span m="148230">some</span>
  <span m="148410">other</span> <span m="148610">operations.</span> <span m="149750">And</span>
  <span m="150110">so</span> <span m="150260">we''ve</span> <span m="150420">actually</span>
  <span m="150700">found</span> <span m="150920">it to</span> <span m="150990">be</span>
  <span m="151150">a</span> <span m="151190">very</span> <span m="151390">useful</span>
  <span m="151730">tool</span> <span m="152675">as</span> <span m="152930">a</span>
  <span m="153200">very</span> <span m="153730">fast,</span> <span m="154330">high-performance</span>
  <span m="155140">data</span> <span m="155390">generator.</span> <span m="155990">And</span>
  <span m="156360">if</span> <span m="156610">you</span> <span m="156730">want</span>
  <span m="156900">to</span> <span m="156970">time</span> <span m="157390">inserts</span>
  <span m="158160">of</span> <span m="158280">power</span> <span m="158640">law</span>
  <span m="158840">data,</span> <span m="159200">it''s</span> <span m="159420">very</span>
  <span m="159630">useful</span> <span m="159920">for</span> <span m="160050">that.</span></p><p><span
  m="160990">This</span> <span m="161170">is</span> <span m="161370">some</span> <span
  m="161540">older</span> <span m="161870">performance</span> <span m="162470">numbers.</span>
  <span m="162890">But</span> <span m="163040">this</span> <span m="163270">just</span>
  <span m="163460">shows</span> <span m="166360">essentially</span> <span m="167400">here</span>
  <span m="168550">on</span> <span m="168840">a</span> <span m="168890">single</span>
  <span m="170040">core</span> <span m="171310">of</span> <span m="171440">computing</span>
  <span m="172020">capability,</span> <span m="173340">the</span> <span m="173430">number</span>
  <span m="174340">of</span> <span m="174490">entries</span> <span m="175320">that</span>
  <span m="175420">we''re</span> <span m="175650">inserting</span> <span m="176160">into</span>
  <span m="176480">a</span> <span m="176570">table</span> <span m="177550">and</span>
  <span m="177990">the</span> <span m="178870">inserts</span> <span m="179460">per</span>
  <span m="179650">second</span> <span m="180270">that</span> <span m="180680">we''re</span>
  <span m="180890">getting.</span> <span m="181250">So</span> <span m="181420">the</span>
  <span m="181540">single</span> <span m="181910">core</span> <span m="182150">performance</span>
  <span m="182870">here</span> <span m="183750">for</span> <span m="183870">this</span>
  <span m="184150">data</span> <span m="185090">into</span> <span m="185560">Accumulo,</span>
  <span m="186750">it''s</span> <span m="186920">about</span> <span m="187260">20,000</span>
  <span m="188510">inserts</span> <span m="189020">per</span> <span m="189170">second.</span>
  <span m="189730">So</span> <span m="189980">there''s</span> <span m="190220">a</span>
  <span m="190290">one</span> <span m="190590">core</span> <span m="190930">database,</span>
  <span m="191480">very,</span> <span m="191800">very</span> <span m="191920">small.</span>
  <span m="193440">As</span> <span m="193630">you''ve</span> <span m="193770">seen--</span>
  <span m="194320">we''ve</span> <span m="194810">even</span> <span m="194900">showed</span>
  <span m="195330">last</span> <span m="195810">week</span> <span m="196880">on</span>
  <span m="197440">modern</span> <span m="197890">servers</span> <span m="198330">where
  we''re</span> <span m="198600">getting</span> <span m="198870">several</span> <span
  m="199170">thousand</span> <span m="200580">inserts</span> <span m="201120">per</span>
  <span m="201310">second</span> <span m="202120">on</span> <span m="203380">standard</span>
  <span m="204680">databases.</span></p><p><span m="208330">I''m</span> <span m="208600">comparing</span>
  <span m="209180">this</span> <span m="209390">also</span> <span m="209870">with</span>
  <span m="210100">just</span> <span m="210450">D4M</span> <span m="211270">without</span>
  <span m="211710">a</span> <span m="211760">database.</span> <span m="212230">If
  I</span> <span m="212350">just</span> <span m="212560">have</span> <span m="212730">triples</span>
  <span m="213850">and</span> <span m="214010">I</span> <span m="214070">construct</span>
  <span m="214670">an</span> <span m="214760">associative</span> <span m="215400">array,</span>
  <span m="216140">how</span> <span m="216360">fast</span> <span m="216820">does</span>
  <span m="217040">it</span> <span m="217200">do</span> <span m="217380">that?</span>
  <span m="217720">And</span> <span m="217890">so</span> <span m="218040">obviously,</span>
  <span m="219130">D4M</span> <span m="219630">is</span> <span m="220000">limited</span>
  <span m="220450">by</span> <span m="220580">how</span> <span m="220760">much</span>
  <span m="221000">memory</span> <span m="221640">you</span> <span m="221870">have</span>
  <span m="222280">on</span> <span m="222390">your</span> <span m="222560">system,</span>
  <span m="223330">but</span> <span m="223460">it</span> <span m="223590">just</span>
  <span m="224240">show</span> <span m="224610">you</span> <span m="224790">the</span>
  <span m="224940">constructing</span> <span m="225690">and</span> <span m="225780">associative</span>
  <span m="226380">array.</span> <span m="226800">And</span> <span m="226930">memory</span>
  <span m="227450">is</span> <span m="228490">faster</span> <span m="229120">than</span>
  <span m="229930">inserting</span> <span m="230570">data</span> <span m="230980">into</span>
  <span m="231430">a</span> <span m="231490">database</span> <span m="232860">by</span>
  <span m="233070">a</span> <span m="233130">good</span> <span m="233320">amount.</span>
  <span m="233740">And</span> <span m="233870">so</span> <span m="234290">again,</span>
  <span m="234610">if</span> <span m="234710">you</span> <span m="234850">could</span>
  <span m="235000">work</span> <span m="235280">with</span> <span m="235460">associative</span>
  <span m="235950">arrays and</span> <span m="236250">memory,</span> <span m="238350">that''s</span>
  <span m="238870">going</span> <span m="239000">to</span> <span m="239060">be</span>
  <span m="239630">better</span> <span m="240050">for</span> <span m="240390">you.</span>
  <span m="240930">Obviously,</span> <span m="241790">though, the</span> <span m="242050">database</span>
  <span m="242530">allows</span> <span m="242940">you</span> <span m="243090">to</span>
  <span m="243240">go</span> <span m="244060">to</span> <span m="244190">very</span>
  <span m="244510">large</span> <span m="244830">sizes.</span> <span m="245420">And</span>
  <span m="245570">one</span> <span m="245730">of</span> <span m="245770">the</span>
  <span m="245850">great</span> <span m="246150">things</span> <span m="246460">about</span>
  <span m="246680">Accumulo</span> <span m="247045">is</span> <span m="247360">this</span>
  <span m="247570">line</span> <span m="247950">stays</span> <span m="249260">pretty</span>
  <span m="249990">flat.</span> <span m="250640">You</span> <span m="250660">can</span>
  <span m="250820">go</span> <span m="250970">on,</span> <span m="251320">out,</span>
  <span m="251630">and</span> <span m="251720">out,</span> <span m="251940">and</span>
  <span m="251990">out,</span> <span m="252230">and</span> <span m="252320">out.</span>
  <span m="252520">That''s</span> <span m="252680">what</span> <span m="252800">it</span>
  <span m="252880">really</span> <span m="253070">prides</span> <span m="253510">itself</span>
  <span m="253920">on,</span> <span m="254200">is</span> <span m="254560">that--</span>
  <span m="255570">as</span> <span m="255790">you</span> <span m="255930">add</span>
  <span m="256260">data,</span> <span m="257019">it</span> <span m="257170">might</span>
  <span m="257920">degrade</span> <span m="258550">slightly,</span> <span m="261589">but</span>
  <span m="261779">if</span> <span m="262270">you''re</span> <span m="262420">inserting</span>
  <span m="262830">it</span> <span m="262930">right,</span> <span m="263390">that</span>
  <span m="263580">line</span> <span m="263930">stays</span> <span m="264120">pretty</span>
  <span m="264350">flat.</span></p><p><span m="267580">In</span> <span m="267660">the</span>
  <span m="267740">last</span> <span m="268020">class,</span> <span m="268290">we</span>
  <span m="268410">did</span> <span m="268580">show</span> <span m="268870">how to</span>
  <span m="269070">do</span> <span m="269190">parallel</span> <span m="269880">inserts</span>
  <span m="270550">in</span> <span m="270680">parallel</span> <span m="271200">D4M.</span>
  <span m="271260">And</span> <span m="271530">this</span> <span m="271860">shows</span>
  <span m="272320">parallel</span> <span m="273730">inserts</span> <span m="274820">here</span>
  <span m="275230">on</span> <span m="275350">a</span> <span m="275410">single</span>
  <span m="275840">node</span> <span m="276590">database,</span> <span m="277790">D4M</span>
  <span m="278420">itself</span> <span m="279250">basically</span> <span m="279850">taking</span>
  <span m="280220">this</span> <span m="280450">number</span> <span m="280830">and</span>
  <span m="281290">scaling</span> <span m="281770">it up</span> <span m="281950">and</span>
  <span m="282030">also</span> <span m="282370">into</span> <span m="282550">the</span>
  <span m="282660">database.</span> <span m="283220">And</span> <span m="283310">so</span>
  <span m="283450">here</span> <span m="283700">a</span> <span m="286840">single</span>
  <span m="287210">node,</span> <span m="287530">single</span> <span m="287950">core</span>
  <span m="288290">database</span> <span m="288910">who are</span> <span m="289140">getting</span>
  <span m="289570">100,000</span> <span m="290280">inserts</span> <span m="291240">a</span>
  <span m="291330">second</span> <span m="292200">with</span> <span m="293260">that.</span>
  <span m="293690">And</span> <span m="293870">so</span> <span m="296260">that</span>
  <span m="296440">just</span> <span m="296590">shows</span> <span m="296900">you</span>
  <span m="297290">some</span> <span m="297530">of the</span> <span m="298020">parallel</span>
  <span m="298460">expectations,</span> <span m="299140">and</span> <span m="299450">when</span>
  <span m="299660">you</span> <span m="299780">should</span> <span m="299990">use</span>
  <span m="302640">parallel</span> <span m="303060">versions</span> <span m="304500">databases.</span>
  <span m="305740">Again,</span> <span m="306005">if you</span> <span m="306270">can</span>
  <span m="306770">be</span> <span m="306940">in</span> <span m="307060">memory,</span>
  <span m="307590">you</span> <span m="307830">want</span> <span m="308050">to</span>
  <span m="308110">be</span> <span m="308290">in memory.</span> <span m="308625">It''s</span>
  <span m="308960">faster.</span> <span m="310080">If</span> <span m="310420">you</span>
  <span m="310530">can</span> <span m="310660">be</span> <span m="310820">in</span>
  <span m="310930">parallel</span> <span m="311440">memory,</span> <span m="312110">you</span>
  <span m="312280">probably</span> <span m="312550">want</span> <span m="312730">to</span>
  <span m="312770">be</span> <span m="312850">in</span> <span m="312970">parallel</span>
  <span m="313300">memory.</span> <span m="313600">That''s</span> <span m="313890">faster.</span>
  <span m="314630">But</span> <span m="314740">if</span> <span m="314810">you</span>
  <span m="314890">have</span> <span m="315030">really</span> <span m="315270">large</span>
  <span m="315620">problems,</span> <span m="316230">then</span> <span m="316270">obviously,</span>
  <span m="316680">you</span> <span m="316770">need</span> <span m="316920">to</span>
  <span m="316970">go</span> <span m="317090">to</span> <span m="317180">the</span>
  <span m="317250">database.</span> <span m="318070">And</span> <span m="318320">that''s</span>
  <span m="318530">what</span> <span m="318940">that''s</span> <span m="319200">for.</span></p><p><span
  m="321200">The</span> <span m="321550">data</span> <span m="323030">in</span> <span
  m="325750">the</span> <span m="327450">graph</span> <span m="327730">500</span>
  <span m="328180">benchmark</span> <span m="329160">is</span> <span m="329350">what</span>
  <span m="329500">we</span> <span m="329640">call</span> <span m="330110">a</span>
  <span m="330170">Kronecker</span> <span m="330630">graph.</span> <span m="331860">It</span>
  <span m="332100">basically</span> <span m="332790">takes</span> <span m="333300">a</span>
  <span m="333390">little,</span> <span m="333650">tiny</span> <span m="334000">matrix,</span>
  <span m="336480">a</span> <span m="336890">little</span> <span m="337150">seed</span>
  <span m="337500">matrix--</span> <span m="338030">in</span> <span m="338110">this</span>
  <span m="338290">case,</span> <span m="338650">g--</span> <span m="339970">and</span>
  <span m="340940">you</span> <span m="341090">can</span> <span m="341220">imagine</span>
  <span m="341940">what it</span> <span m="342140">looks</span> <span m="342390">like</span>
  <span m="342580">here.</span> <span m="343820">Imagine</span> <span m="344210">this</span>
  <span m="344380">is</span> <span m="344450">a</span> <span m="344540">two-by-two</span>
  <span m="345100">matrix</span> <span m="345600">here.</span> <span m="345790">You</span>
  <span m="345900">can</span> <span m="346050">sort</span> <span m="346260">of</span>
  <span m="346330">see,</span> <span m="347390">maybe,</span> <span m="347840">a</span>
  <span m="347890">little</span> <span m="348040">bit</span> <span m="348170">of</span>
  <span m="348220">the</span> <span m="348290">structure.</span> <span m="349310">And</span>
  <span m="349580">then</span> <span m="349790">it</span> <span m="350330">does</span>
  <span m="350520">a</span> <span m="350600">Kronecker</span> <span m="351140">product</span>
  <span m="351560">of</span> <span m="351640">that</span> <span m="351890">on</span>
  <span m="352170">out</span> <span m="352420">to</span> <span m="352540">create</span>
  <span m="353480">and</span> <span m="353590">adjacency</span> <span m="354220">matrix.</span>
  <span m="357930">By</span> <span m="358110">creating</span> <span m="358480">this</span>
  <span m="358650">adjacency</span> <span m="358950">matrix,</span> <span m="359210">that</span>
  <span m="359430">creates</span> <span m="359730">the</span> <span m="359810">graph.</span></p><p><span
  m="361100">And</span> <span m="362740">as</span> <span m="363060">a</span> <span
  m="363110">result,</span> <span m="363440">it</span> <span m="363540">naturally</span>
  <span m="364170">produces--</span> <span m="365410">this</span> <span m="365590">is</span>
  <span m="365750">the</span> <span m="365830">result.</span> <span m="366440">It</span>
  <span m="366550">produces</span> <span m="367000">something</span> <span m="367540">that</span>
  <span m="367670">naturally</span> <span m="367960">looks</span> <span m="368130">like</span>
  <span m="368270">a</span> <span m="368330">power</span> <span m="368680">law</span>
  <span m="369740">graph</span> <span m="370110">here.</span> <span m="370820">And</span>
  <span m="371020">this</span> <span m="371210">just</span> <span m="371400">shows</span>
  <span m="371790">you</span> <span m="371970">the</span> <span m="372130">dots,</span>
  <span m="372530">shows</span> <span m="372770">you</span> <span m="372920">the</span>
  <span m="373820">power</span> <span m="374200">law</span> <span m="374870">degree</span>
  <span m="375320">distribution</span> <span m="375980">of</span> <span m="376100">that.</span>
  <span m="377540">You</span> <span m="377750">can</span> <span m="377870">see</span>
  <span m="378350">the</span> <span m="378480">slope</span> <span m="378880">there</span>
  <span m="381220">generated</span> <span m="381770">from</span> <span m="381990">this.</span>
  <span m="382790">I</span> <span m="382990">should</span> <span m="383190">say</span>
  <span m="383310">one</span> <span m="383530">of</span> <span m="383870">the</span>
  <span m="384160">powerful</span> <span m="384730">things</span> <span m="385140">about</span>
  <span m="385480">this</span> <span m="385690">particular</span> <span m="386160">generator</span>
  <span m="386800">is</span> <span m="387860">you</span> <span m="388250">don''t</span>
  <span m="388540">have</span> <span m="388800">to</span> <span m="388950">form</span>
  <span m="389350">the</span> <span m="390370">adjacency</span> <span m="390990">matrix</span>
  <span m="391490">to</span> <span m="391640">construct</span> <span m="392090">the</span>
  <span m="392170">graph.</span> <span m="392930">So</span> <span m="393070">it</span>
  <span m="393110">doesn''t</span> <span m="393340">require</span> <span m="393850">you</span>
  <span m="393970">to</span> <span m="394050">build</span> <span m="394330">this</span>
  <span m="394460">gigantic</span> <span m="395000">matrix.</span> <span m="395700">It</span>
  <span m="396280">generates</span> <span m="396840">the</span> <span m="397440">edges</span>
  <span m="398110">atomically.</span></p><p><span m="399920">If</span> <span m="400050">you</span>
  <span m="400180">have</span> <span m="400330">many,</span> <span m="400780">many</span>
  <span m="400960">processes</span> <span m="401410">all</span> <span m="403270">doing</span>
  <span m="403560">this,</span> <span m="403740">as</span> <span m="403870">long</span>
  <span m="404180">as</span> <span m="404290">they</span> <span m="404420">set</span>
  <span m="404720">their</span> <span m="404860">random</span> <span m="405270">number</span>
  <span m="405600">seeds</span> <span m="406020">to</span> <span m="406150">different</span>
  <span m="406610">locations,</span> <span m="406920">they''ll</span> <span m="407230">all</span>
  <span m="407620">be</span> <span m="407750">generating</span> <span m="408750">perfectly</span>
  <span m="409810">consistent</span> <span m="411020">edges</span> <span m="411720">in</span>
  <span m="411910">a</span> <span m="411950">larger</span> <span m="412350">graph.</span>
  <span m="413220">So</span> <span m="415060">people</span> <span m="415340">have</span>
  <span m="415490">run</span> <span m="415720">this</span> <span m="415950">on</span>
  <span m="416180">computers</span> <span m="416650">with</span> <span m="417310">millions</span>
  <span m="417950">of</span> <span m="418060">cores</span> <span m="419660">to</span>
  <span m="419810">do</span> <span m="420000">that.</span> <span m="420210">Because</span>
  <span m="420590">the</span> <span m="421800">graph</span> <span m="422120">generator</span>
  <span m="422485">is</span> <span m="422850">completely--</span> <span m="423850">parallel</span>
  <span m="424370">allows</span> <span m="424640">you</span> <span m="424740">to</span>
  <span m="424780">essentially</span> <span m="425120">create</span> <span m="425360">a</span>
  <span m="425440">giant</span> <span m="426780">graph.</span></p><p><span m="429260">And</span>
  <span m="430450">also,</span> <span m="432710">the</span> <span m="432820">Kronecker</span>
  <span m="433510">graph</span> <span m="433670">does</span> <span m="434040">generate</span>
  <span m="434530">this</span> <span m="434750">structure</span> <span m="435470">here,</span>
  <span m="435840">which</span> <span m="435980">is</span> <span m="436170">these</span>
  <span m="437230">bumps</span> <span m="437670">and</span> <span m="437840">wiggles.</span>
  <span m="438790">And</span> <span m="439080">that</span> <span m="439410">actually</span>
  <span m="439870">corresponds</span> <span m="440990">to</span> <span m="442310">the</span>
  <span m="442500">power</span> <span m="443030">k.</span> <span m="444080">So</span>
  <span m="444340">you</span> <span m="444620">can</span> <span m="444800">count</span>
  <span m="445100">the</span> <span m="445190">number</span> <span m="445490">of</span>
  <span m="445550">bumps.</span> <span m="445810">We</span> <span m="445910">have</span>
  <span m="446040">1,</span> <span m="446507">2,</span> <span m="446974">3,</span>
  <span m="447441">4,</span> <span m="447908">5,</span> <span m="448375">6,</span>
  <span m="448842">7,</span> <span m="449309">8.</span> <span m="450250">So</span>
  <span m="450420">this</span> <span m="450660">would</span> <span m="450840">be</span>
  <span m="451900">a</span> <span m="452040">g</span> <span m="452400">to</span> <span
  m="452520">the</span> <span m="452700">8th</span> <span m="453880">graph.</span>
  <span m="454280">So</span> <span m="454460">that</span> <span m="454680">structure</span>
  <span m="455670">is</span> <span m="456340">visible</span> <span m="457480">there,</span>
  <span m="458900">which</span> <span m="459170">is</span> <span m="459430">an</span>
  <span m="459650">artificial</span> <span m="460500">feature</span> <span m="462080">of</span>
  <span m="462300">the</span> <span m="462380">data.</span></p><p><span m="463000">And</span>
  <span m="463310">so</span> <span m="465400">one</span> <span m="465700">of</span>
  <span m="465970">the</span> <span m="466110">things</span> <span m="466330">that''s</span>
  <span m="466450">actually</span> <span m="466740">occurred</span> <span m="467200">now--</span>
  <span m="467460">because</span> <span m="467750">people</span> <span m="468040">have</span>
  <span m="468110">been</span> <span m="468250">actually</span> <span m="468550">trying</span>
  <span m="468780">to</span> <span m="468830">use</span> <span m="469250">this</span>
  <span m="469470">generator</span> <span m="470030">because</span> <span m="470290">it''s</span>
  <span m="470460">so</span> <span m="471100">fast</span> <span m="471470">and</span>
  <span m="471560">efficient</span> <span m="472340">to</span> <span m="472950">simulate</span>
  <span m="473520">graphs.</span> <span m="474140">And</span> <span m="474550">we''ve</span>
  <span m="474660">basically</span> <span m="475270">said</span> <span m="475610">to</span>
  <span m="475740">people,</span> <span m="476890">not</span> <span m="477460">really</span>
  <span m="477730">designed</span> <span m="478340">to</span> <span m="478490">simulate</span>
  <span m="479140">large</span> <span m="479460">graphs,</span> <span m="479790">because</span>
  <span m="480030">it</span> <span m="480170">does</span> <span m="480840">create</span>
  <span m="481070">these</span> <span m="481250">artificial</span> <span m="482410">structures</span>
  <span m="483750">in</span> <span m="484020">there.</span> <span m="484470">And</span>
  <span m="484620">that''s</span> <span m="484980">the</span> <span m="485070">reason</span>
  <span m="485830">we</span> <span m="486020">develop</span> <span m="486370">the</span>
  <span m="486460">perfect</span> <span m="486780">power</span> <span m="487080">law</span>
  <span m="487290">method.</span> <span m="488010">Because</span> <span m="488300">that''s</span>
  <span m="488510">a</span> <span m="488560">much</span> <span m="488860">better</span>
  <span m="489090">method</span> <span m="489470">if</span> <span m="489550">you''re</span>
  <span m="489660">actually</span> <span m="489870">trying</span> <span m="490080">to</span>
  <span m="490140">simulate</span> <span m="491510">graphs</span> <span m="492260">for</span>
  <span m="492370">doing</span> <span m="492660">that.</span> <span m="493730">Again,</span>
  <span m="494020">this</span> <span m="494180">method</span> <span m="494630">has</span>
  <span m="494950">these</span> <span m="495160">advantages</span> <span m="495760">in</span>
  <span m="495860">terms</span> <span m="496150">of</span> <span m="496230">being</span>
  <span m="496450">able</span> <span m="496560">to</span> <span m="496670">generate</span>
  <span m="497140">them.</span></p><p><span m="501340">Another</span> <span m="501980">advantage</span>
  <span m="502610">of</span> <span m="503280">these</span> <span m="503470">Kronecker</span>
  <span m="503890">graphs--</span> <span m="504820">and</span> <span m="505000">so</span>
  <span m="505220">in</span> <span m="505300">this</span> <span m="505490">case,</span>
  <span m="505740">B</span> <span m="506120">is</span> <span m="506230">my</span>
  <span m="506400">little</span> <span m="507520">matrix</span> <span m="508210">here</span>
  <span m="509190">that</span> <span m="509380">I''m</span> <span m="509530">going</span>
  <span m="509670">to</span> <span m="509940">do</span> <span m="510340">Kronecker</span>
  <span m="510830">products</span> <span m="511330">of.</span> <span m="511840">In</span>
  <span m="511930">fact,</span> <span m="512130">let</span> <span m="512230">me</span>
  <span m="512789">remind</span> <span m="513440">you</span> <span m="513690">about</span>
  <span m="513980">what</span> <span m="514120">a</span> <span m="514190">Kronecker</span>
  <span m="514700">product</span> <span m="515110">is.</span> <span m="515940">So</span>
  <span m="516130">if</span> <span m="516230">I</span> <span m="516390">have</span>
  <span m="516669">here</span> <span m="517370">a</span> <span m="517450">matrix</span>
  <span m="518030">B,</span> <span m="518669">that''s</span> <span m="519049">nb by</span>
  <span m="519220">nb,</span> <span m="519689">although</span> <span m="520159">these</span>
  <span m="520390">don''t</span> <span m="520580">have</span> <span m="520809">to</span>
  <span m="520929">be</span> <span m="521080">square,</span> <span m="521919">and</span>
  <span m="522140">another</span> <span m="522450">matrix</span> <span m="522909">C</span>
  <span m="523330">that''s</span> <span m="523570">nc</span> <span m="523980">by</span>
  <span m="524140">mc</span> <span m="524480">doesn''t</span> <span m="524730">also</span>
  <span m="525080">have</span> <span m="525210">to</span> <span m="525280">be</span>
  <span m="525390">square.</span> <span m="526170">And</span> <span m="526310">when
  you do the</span> <span m="526590">Kronecker</span> <span m="527110">product,</span>
  <span m="527500">basically</span> <span m="527980">what</span> <span m="528130">you''re</span>
  <span m="528270">doing</span> <span m="529040">is</span> <span m="529190">essentially</span>
  <span m="529610">taking</span> <span m="530010">c</span> <span m="530810">and</span>
  <span m="530970">multiplying</span> <span m="531540">by</span> <span m="531680">the</span>
  <span m="531790">first</span> <span m="532110">element,</span> <span m="532490">and</span>
  <span m="532590">having</span> <span m="532910">essentially</span> <span m="533320">a</span>
  <span m="533390">block</span> <span m="533770">here.</span></p><p><span m="534140">And</span>
  <span m="534490">so</span> <span m="534860">it''s a</span> <span m="534920">way</span>
  <span m="535110">of</span> <span m="535480">essentially</span> <span m="535790">expanding</span>
  <span m="536580">the</span> <span m="536670">matrix</span> <span m="537560">in</span>
  <span m="537740">both</span> <span m="538850">dimensions.</span> <span m="539870">And</span>
  <span m="540670">Jure</span> <span m="540980">Leskovec,</span> <span m="541880">who''s</span>
  <span m="542060">now</span> <span m="542170">a</span> <span m="542210">professor</span>
  <span m="542660">at</span> <span m="542760">Stanford,</span> <span m="544010">essentially</span>
  <span m="544880">developed</span> <span m="545640">this</span> <span m="545840">method</span>
  <span m="546590">back</span> <span m="547160">in</span> <span m="547590">2005</span>
  <span m="549620">for</span> <span m="550360">creating</span> <span m="550780">these</span>
  <span m="550950">matrices</span> <span m="551920">which</span> <span m="552100">allow</span>
  <span m="552460">you</span> <span m="552640">to</span> <span m="552740">very</span>
  <span m="552950">naturally</span> <span m="553490">create</span> <span m="553890">power</span>
  <span m="554260">law</span> <span m="554440">matrices,</span> <span m="555260">and
  even</span> <span m="555470">had</span> <span m="555890">tools</span> <span m="556170">for</span>
  <span m="556380">fitting</span> <span m="556730">them</span> <span m="557510">to</span>
  <span m="557670">data,</span> <span m="558330">which</span> <span m="558550">is</span>
  <span m="558690">a</span> <span m="558960">useful</span> <span m="560090">thing.</span>
  <span m="561490">Again,</span> <span m="562090">its</span> <span m="562610">biggest</span>
  <span m="562980">impact</span> <span m="563400">has</span> <span m="563580">been</span>
  <span m="563800">on</span> <span m="565080">generating</span> <span m="565820">very</span>
  <span m="566130">large</span> <span m="566450">graphs,</span> <span m="567110">power</span>
  <span m="567310">law</span> <span m="567500">graphs</span> <span m="567770">very</span>
  <span m="568070">quickly.</span></p><p><span m="571170">The</span> <span m="571280">Kronecker</span>
  <span m="571840">graph</span> <span m="572190">itself</span> <span m="572770">has</span>
  <span m="573040">several</span> <span m="573770">different</span> <span m="574270">types</span>
  <span m="577370">that</span> <span m="577570">I</span> <span m="577630">call</span>
  <span m="577900">here,</span> <span m="578120">basically,</span> <span m="578530">explicit,</span>
  <span m="579480">stochastic,</span> <span m="580250">and an</span> <span m="580510">instance.</span>
  <span m="582110">So</span> <span m="582980">if</span> <span m="583180">I</span>
  <span m="583330">just</span> <span m="584010">set</span> <span m="584500">the</span>
  <span m="584780">coefficients</span> <span m="586610">of</span> <span m="586830">the</span>
  <span m="586940">Kronecker</span> <span m="587260">graph</span> <span m="587820">to</span>
  <span m="587940">be</span> <span m="588260">ones</span> <span m="588860">and</span>
  <span m="589030">zeroes</span> <span m="589720">and</span> <span m="589940">I</span>
  <span m="590000">Kronecker</span> <span m="590600">out,</span> <span m="590900">I</span>
  <span m="591000">will</span> <span m="591170">get</span> <span m="591350">structures</span>
  <span m="591890">that</span> <span m="592030">look</span> <span m="592250">like</span>
  <span m="592450">this.</span> <span m="593440">So</span> <span m="593470">this</span>
  <span m="593660">is</span> <span m="593810">a</span> <span m="593890">Kronecker</span>
  <span m="594400">graph</span> <span m="594730">that</span> <span m="594800">essentially</span>
  <span m="595230">is</span> <span m="595400">a</span> <span m="595950">bipartite,</span>
  <span m="597140">essentially</span> <span m="597560">starting</span> <span m="597930">with</span>
  <span m="598110">a--</span> <span m="598385">what</span> <span m="598660">you can</span>
  <span m="598850">call</span> <span m="599060">a</span> <span m="599120">star</span>
  <span m="600190">graph</span> <span m="600610">and</span> <span m="600760">then</span>
  <span m="601470">a</span> <span m="601570">diagonal.</span> <span m="602410">So</span>
  <span m="602430">that''s</span> <span m="602940">1.</span> <span m="604190">That''s</span>
  <span m="605460">g1.</span> <span m="606880">Then</span> <span m="607030">I</span>
  <span m="607100">Kronecker</span> <span m="607430">product</span> <span m="608200">again,</span>
  <span m="608600">g2</span> <span m="609730">and</span> <span m="609910">g3,</span>
  <span m="610385">and</span> <span m="610860">I</span> <span m="611030">get</span>
  <span m="611290">these</span> <span m="612010">different</span> <span m="612440">structure</span>
  <span m="613500">0</span> <span m="613950">1</span> <span m="614170">matrices.</span>
  <span m="615760">And</span> <span m="616030">so</span> <span m="616130">it''s</span>
  <span m="616230">only</span> <span m="616520">0''s</span> <span m="616910">and</span>
  <span m="617060">1''s,</span> <span m="617950">and</span> <span m="618380">so</span>
  <span m="618470">the</span> <span m="618580">structure</span> <span m="619250">and</span>
  <span m="619330">the</span> <span m="619400">connections</span> <span m="619880">are</span>
  <span m="619920">very</span> <span m="620140">obvious.</span></p><p><span m="621280">And</span>
  <span m="622360">this</span> <span m="622570">is</span> <span m="622720">actually</span>
  <span m="623090">useful</span> <span m="624450">for</span> <span m="624900">doing</span>
  <span m="625170">theory.</span> <span m="626630">So</span> <span m="627090">you</span>
  <span m="627230">can</span> <span m="627390">actually</span> <span m="627740">do</span>
  <span m="627890">a</span> <span m="627950">fair</span> <span m="628260">amount</span>
  <span m="628500">of</span> <span m="628620">theory</span> <span m="629210">on</span>
  <span m="629410">the</span> <span m="629490">structure</span> <span m="630100">of</span>
  <span m="630260">graphs</span> <span m="631160">using</span> <span m="631510">the</span>
  <span m="631590">0</span> <span m="631960">1</span> <span m="632150">matrices.</span>
  <span m="634600">And</span> <span m="634700">in</span> <span m="634770">fact,</span>
  <span m="635080">there''s</span> <span m="635240">a</span> <span m="635300">famous</span>
  <span m="635770">paper</span> <span m="636660">by</span> <span m="636880">Van</span>
  <span m="637130">Loan</span> <span m="637930">on</span> <span m="638430">Kronecker</span>
  <span m="638930">products.</span> <span m="639890">And</span> <span m="640280">basically,</span>
  <span m="640650">the</span> <span m="640750">paper</span> <span m="641210">is</span>
  <span m="641370">full</span> <span m="641710">of</span> <span m="641860">identities</span>
  <span m="642640">of</span> <span m="643120">Kronecker</span> <span m="643750">products</span>
  <span m="644210">that--</span> <span m="645660">the</span> <span m="646020">eigenvalues</span>
  <span m="648590">of</span> <span m="648800">the</span> <span m="648910">Kronecker</span>
  <span m="649350">product</span> <span m="649950">of</span> <span m="650100">two</span>
  <span m="650250">matrices</span> <span m="650970">is</span> <span m="651030">the</span>
  <span m="651160">same</span> <span m="651390">as</span> <span m="651450">the</span>
  <span m="651540">Kronecker</span> <span m="651950">product</span> <span m="652330">of</span>
  <span m="652440">their</span> <span m="652660">eigenvalues,</span> <span m="653630">and</span>
  <span m="654160">a</span> <span m="654210">whole</span> <span m="654480">series</span>
  <span m="655030">of</span> <span m="655160">those</span> <span m="655450">things.</span>
  <span m="655920">And</span> <span m="655970">so</span> <span m="656630">what''s</span>
  <span m="656880">nice</span> <span m="657260">is</span> <span m="657980">if</span>
  <span m="658130">you</span> <span m="658270">compute</span> <span m="658740">something</span>
  <span m="659180">on</span> <span m="659330">just</span> <span m="660270">the</span>
  <span m="660870">small</span> <span m="661220">matrix</span> <span m="661750">g,</span>
  <span m="662490">you</span> <span m="662620">can</span> <span m="662780">very</span>
  <span m="663310">quickly</span> <span m="664040">compute</span> <span m="664900">all</span>
  <span m="665250">the</span> <span m="665350">properties</span> <span m="666050">of</span>
  <span m="666400">the</span> <span m="666610">Kronecker</span> <span m="667070">product</span>
  <span m="667870">matrix,</span> <span m="668390">and</span> <span m="668480">that</span>
  <span m="668610">makes</span> <span m="668790">it</span> <span m="668890">very</span>
  <span m="669140">nice</span> <span m="669480">for</span> <span m="669600">doing</span>
  <span m="669940">theory.</span> <span m="670670">And</span> <span m="670830">so</span>
  <span m="671000">there''s</span> <span m="671210">times</span> <span m="671560">when</span>
  <span m="671650">you</span> <span m="671750">want</span> <span m="672420">to</span>
  <span m="673110">understand</span> <span m="673960">the</span> <span m="674040">structure</span>
  <span m="674700">of</span> <span m="674930">these</span> <span m="675200">things.</span>
  <span m="675730">Very</span> <span m="675960">useful</span> <span m="676440">theoretical</span>
  <span m="677100">tool</span> <span m="677320">for</span> <span m="677490">doing</span>
  <span m="677800">that.</span></p><p><span m="680630">If</span> <span m="680840">instead,</span>
  <span m="681290">we</span> <span m="681420">use</span> <span m="681930">our</span>
  <span m="683140">C</span> <span m="683630">graph,</span> <span m="684310">instead</span>
  <span m="684580">of</span> <span m="684660">it</span> <span m="684790">being</span>
  <span m="685070">1''s</span> <span m="685310">and</span> <span m="685450">0''s,</span>
  <span m="686270">it</span> <span m="686420">contains,</span> <span m="687350">say,</span>
  <span m="688740">numbers</span> <span m="689090">between</span> <span m="689420">0</span>
  <span m="689790">and</span> <span m="689910">1</span> <span m="690160">that</span>
  <span m="690300">are</span> <span m="690410">probabilities,</span> <span m="691330">the</span>
  <span m="691450">probability</span> <span m="692180">of</span> <span m="692710">creating</span>
  <span m="693070">an</span> <span m="693150">edge</span> <span m="693380">between</span>
  <span m="693730">those</span> <span m="693910">two</span> <span m="694060">vertices.</span>
  <span m="695090">And</span> <span m="695310">we</span> <span m="697130">multiply</span>
  <span m="697640">that</span> <span m="697990">on</span> <span m="698230">out.</span>
  <span m="698460">You</span> <span m="698610">get,</span> <span m="698900">essentially,</span>
  <span m="699760">a</span> <span m="699830">giant</span> <span m="700660">probability</span>
  <span m="701260">matrix</span> <span m="702600">showing</span> <span m="702960">the</span>
  <span m="703060">probability</span> <span m="703870">of</span> <span m="703970">edges.</span>
  <span m="705410">These</span> <span m="705570">are</span> <span m="705620">the</span>
  <span m="705740">same,</span> <span m="706170">but</span> <span m="706290">here</span>
  <span m="706530">we</span> <span m="706670">see</span> <span m="706930">we</span>
  <span m="707050">have</span> <span m="707290">differences.</span> <span m="707880">We</span>
  <span m="708020">don''t</span> <span m="708240">just have</span> <span m="708440">0''s</span>
  <span m="708730">and</span> <span m="708840">1''s.</span> <span m="709070">We</span>
  <span m="709200">have</span> <span m="709690">values</span> <span m="710050">between</span>
  <span m="710420">0''s</span> <span m="710770">and</span> <span m="710900">1''s.</span></p><p><span
  m="711670">And</span> <span m="711850">then</span> <span m="712450">using</span>
  <span m="712930">the</span> <span m="713010">Kronecker</span> <span m="713420">generation</span>
  <span m="714130">technique,</span> <span m="714610">we</span> <span m="714750">essentially</span>
  <span m="715100">draw</span> <span m="716300">instances</span> <span m="717590">from</span>
  <span m="717970">this</span> <span m="718170">probability</span> <span m="718750">matrix</span>
  <span m="719300">over</span> <span m="719550">here.</span> <span m="720110">So</span>
  <span m="720240">this</span> <span m="720400">allows</span> <span m="720860">us</span>
  <span m="720950">to</span> <span m="721420">randomly</span> <span m="721850">sample.</span>
  <span m="722250">So</span> <span m="722700">when</span> <span m="722810">you''re</span>
  <span m="722900">talking</span> <span m="723170">about</span> <span m="723410">Kronecker</span>
  <span m="723765">graphs,</span> <span m="724120">there''s</span> <span m="724500">three</span>
  <span m="724750">different</span> <span m="725070">types</span> <span m="725420">here.</span>
  <span m="726210">This</span> <span m="726510">is</span> <span m="727020">very</span>
  <span m="727310">easy</span> <span m="727520">to</span> <span m="727560">do</span>
  <span m="727720">theory</span> <span m="728140">on.</span> <span m="728630">You</span>
  <span m="728770">can</span> <span m="728900">do</span> <span m="729050">theory</span>
  <span m="729430">on</span> <span m="729580">this,</span> <span m="729800">too,</span>
  <span m="730140">but</span> <span m="730480">it</span> <span m="730700">tends</span>
  <span m="730980">to</span> <span m="731880">be</span> <span m="732010">a</span>
  <span m="732080">little</span> <span m="732250">bit</span> <span m="732400">more</span>
  <span m="732580">work-y.</span> <span m="733370">And</span> <span m="733590">then</span>
  <span m="734020">likewise,</span> <span m="734700">when</span> <span m="735110">you''re</span>
  <span m="735300">doing</span> <span m="735650">simulations,</span> <span m="736780">usually</span>
  <span m="737170">you</span> <span m="737320">end</span> <span m="737470">up</span>
  <span m="737610">with</span> <span m="738210">Kronecker</span> <span m="738690">graphs</span>
  <span m="739120">like</span> <span m="739320">this.</span></p><p><span m="743700">As</span>
  <span m="743860">an</span> <span m="743920">example</span> <span m="744450">of</span>
  <span m="744520">the</span> <span m="744590">kind</span> <span m="744810">of</span>
  <span m="744940">theory</span> <span m="745360">we</span> <span m="745570">can</span>
  <span m="745900">do,</span> <span m="749300">one</span> <span m="750130">of</span>
  <span m="750220">the</span> <span m="750310">nicest</span> <span m="751790">graphs</span>
  <span m="752120">to</span> <span m="752240">work</span> <span m="752520">with</span>
  <span m="752740">are</span> <span m="753150">bipartite</span> <span m="753870">graphs.</span>
  <span m="754950">So</span> <span m="755170">a</span> <span m="755530">bipartite</span>
  <span m="755620">graph</span> <span m="756130">is</span> <span m="756960">two</span>
  <span m="757980">sets</span> <span m="758240">of</span> <span m="758350">vertices,</span>
  <span m="759480">and</span> <span m="759900">each</span> <span m="760130">vertex</span>
  <span m="760590">has</span> <span m="760830">a</span> <span m="760890">connection</span>
  <span m="761390">to</span> <span m="762150">every</span> <span m="762390">vertex</span>
  <span m="762820">in</span> <span m="762900">the</span> <span m="763020">other</span>
  <span m="763280">set,</span> <span m="763550">but</span> <span m="763650">they</span>
  <span m="763760">don''t</span> <span m="764050">have</span> <span m="764180">any</span>
  <span m="764420">connections</span> <span m="765080">amongst</span> <span m="765470">themselves.</span>
  <span m="766800">And</span> <span m="767070">so</span> <span m="767870">here,</span>
  <span m="768210">I''m</span> <span m="768320">showing</span> <span m="768710">you</span>
  <span m="768950">a</span> <span m="769030">bipartite</span> <span m="769610">or</span>
  <span m="769970">star</span> <span m="770530">graph,</span> <span m="771430">so</span>
  <span m="771470">basically</span> <span m="771860">one</span> <span m="772140">set</span>
  <span m="772350">of</span> <span m="772410">vertices</span> <span m="772940">here</span>
  <span m="773540">and</span> <span m="773710">another</span> <span m="773970">set</span>
  <span m="774130">of</span> <span m="774190">vertices</span> <span m="774640">here.</span>
  <span m="775310">And</span> <span m="775370">all</span> <span m="775540">the</span>
  <span m="775600">vertices</span> <span m="776270">have</span> <span m="776420">connections</span>
  <span m="776890">to</span> <span m="777020">those</span> <span m="777330">vertex,</span>
  <span m="777830">but</span> <span m="777930">they</span> <span m="778030">have</span>
  <span m="778130">no</span> <span m="779110">connections</span> <span m="779620">themselves.</span>
  <span m="780330">And</span> <span m="780490">this</span> <span m="780670">is</span>
  <span m="780780">the</span> <span m="780920">adjacency</span> <span m="781490">matrix</span>
  <span m="781940">of</span> <span m="782040">that</span> <span m="782250">graph.</span></p><p><span
  m="784130">And</span> <span m="784290">here</span> <span m="784610">is</span> <span
  m="784710">another</span> <span m="785090">bipartite</span> <span m="785710">graph.</span>
  <span m="786190">It''s</span> <span m="786630">a</span> <span m="786810">3</span>
  <span m="787580">1</span> <span m="787890">set.</span> <span m="788890">And</span>
  <span m="789740">if</span> <span m="789990">I</span> <span m="790520">Kronecker</span>
  <span m="791000">product</span> <span m="791420">two</span> <span m="791570">bipartite</span>
  <span m="792000">graphs,</span> <span m="792600">the</span> <span m="792680">result</span>
  <span m="793130">is</span> <span m="793700">two</span> <span m="794540">more</span>
  <span m="794720">bipartite</span> <span m="795120">graphs.</span> <span m="796360">So</span>
  <span m="796630">as</span> <span m="796740">we</span> <span m="796880">see</span>
  <span m="797150">here, we''ve</span> <span m="797370">created</span> <span m="797720">this</span>
  <span m="798410">one</span> <span m="798610">here</span> <span m="799420">and</span>
  <span m="799670">this</span> <span m="799860">one</span> <span m="801000">here.</span>
  <span m="802000">And</span> <span m="802930">so</span> <span m="803170">in my</span>
  <span m="803280">notation,</span> <span m="804000">I''ll</span> <span m="804160">say</span>
  <span m="804400">B</span> <span m="804665">5,</span> <span m="805630">1</span> <span
  m="805870">is</span> <span m="806020">a</span> <span m="806190">bipartite.</span>
  <span m="807250">That''s</span> <span m="807530">basically--</span> <span m="807930">I''m</span>
  <span m="808020">saying</span> <span m="808260">I</span> <span m="808280">have</span>
  <span m="808390">a</span> <span m="808430">matrix</span> <span m="809290">that''s</span>
  <span m="809950">a</span> <span m="810922">5,</span> <span m="811408">1</span> <span
  m="812380">bipartite</span> <span m="812440">graph,</span> <span m="813570">3,</span>
  <span m="813830">1</span> <span m="814430">bipartite</span> <span m="814500">graph.</span>
  <span m="815330">And</span> <span m="815670">within</span> <span m="816470">some</span>
  <span m="816770">permutation,</span> <span m="817720">they</span> <span m="817830">produce</span>
  <span m="818620">a</span> <span m="818720">matrix</span> <span m="819140">that</span>
  <span m="819560">is</span> <span m="819790">the</span> <span m="819920">union</span>
  <span m="820690">of</span> <span m="820840">a</span> <span m="821190">15,</span>
  <span m="821540">a</span> <span m="821890">1,</span> <span m="822380">and</span>
  <span m="822560">a</span> <span m="822680">3,</span> <span m="823170">5.</span></p><p><span
  m="825340">And</span> <span m="825510">this</span> <span m="825700">result</span>
  <span m="826190">actually</span> <span m="827390">was</span> <span m="827580">first</span>
  <span m="827810">shown</span> <span m="828150">by</span> <span m="828690">a</span>
  <span m="828800">professor</span> <span m="829200">by the</span> <span m="829350">name</span>
  <span m="829550">of</span> <span m="829650">Weichsel</span> <span m="830470">in</span>
  <span m="830630">1962.</span> <span m="833040">And</span> <span m="833280">there
  was</span> <span m="833470">actually</span> <span m="833820">a</span> <span m="833900">little</span>
  <span m="834120">flurry</span> <span m="834770">of</span> <span m="835390">activity</span>
  <span m="835910">back</span> <span m="836230">in</span> <span m="836310">the</span>
  <span m="836390">1960s</span> <span m="839770">with</span> <span m="840040">this</span>
  <span m="840240">whole</span> <span m="840610">algebraic</span> <span m="841390">view
  of</span> <span m="841810">graph</span> <span m="842260">theory,</span> <span m="848960">which</span>
  <span m="849180">was</span> <span m="849330">very</span> <span m="849610">productive,</span>
  <span m="850140">but</span> <span m="850260">then</span> <span m="850400">it</span>
  <span m="850470">all</span> <span m="850660">died</span> <span m="850950">off.</span>
  <span m="851860">And</span> <span m="852060">after</span> <span m="852340">the</span>
  <span m="852510">lecture,</span> <span m="852840">I</span> <span m="852880">can</span>
  <span m="853070">tell</span> <span m="853240">you</span> <span m="853370">why</span>
  <span m="853540">that</span> <span m="853740">happened.</span> <span m="854540">But</span>
  <span m="854670">now</span> <span m="854890">it''s</span> <span m="855000">all</span>
  <span m="855160">coming</span> <span m="855450">back,</span> <span m="856200">which</span>
  <span m="856400">is</span> <span m="856540">nice.</span> <span m="856850">So</span>
  <span m="857020">it</span> <span m="857130">took</span> <span m="857310">us</span>
  <span m="858020">50</span> <span m="858290">years</span> <span m="858550">to</span>
  <span m="858680">rediscover</span> <span m="859280">this</span> <span m="859490">work.</span>
  <span m="860240">But</span> <span m="860510">there''s</span> <span m="860730">actually</span>
  <span m="861050">a</span> <span m="861630">whole</span> <span m="861800">book</span>
  <span m="862030">on</span> <span m="862180">it</span> <span m="862350">with lots</span>
  <span m="862670">of</span> <span m="862790">interesting</span> <span m="863200">results.</span></p><p><span
  m="865470">But</span> <span m="865610">then</span> <span m="865840">this</span>
  <span m="866030">just</span> <span m="866210">shows</span> <span m="866460">you</span>
  <span m="866580">the</span> <span m="866950">general</span> <span m="867370">result</span>
  <span m="867840">here.</span> <span m="868730">For</span> <span m="868950">any</span>
  <span m="869240">two</span> <span m="869500">bipartite</span> <span m="869920">graphs,</span>
  <span m="870360">if I</span> <span m="870680">Kronecker</span> <span m="871000">product</span>
  <span m="871265">them</span> <span m="871530">together,</span> <span m="872340">they</span>
  <span m="872520">are</span> <span m="872790">under</span> <span m="873030">some</span>
  <span m="873280">permutation</span> <span m="874560">equal</span> <span m="874940">to</span>
  <span m="876550">two</span> <span m="877530">other</span> <span m="877920">bipartite</span>
  <span m="878510">graphs.</span> <span m="879380">And</span> <span m="879540">this</span>
  <span m="880030">naturally</span> <span m="880590">shows</span> <span m="881270">you</span>
  <span m="881540">how</span> <span m="882830">the</span> <span m="882960">power</span>
  <span m="883490">law</span> <span m="883870">structure</span> <span m="885170">gets</span>
  <span m="885430">built</span> <span m="885930">up</span> <span m="886550">when</span>
  <span m="886690">you</span> <span m="886840">Kronecker</span> <span m="887360">product</span>
  <span m="887800">these</span> <span m="888040">graphs.</span> <span m="888370">So</span>
  <span m="888700">basically,</span> <span m="890720">you</span> <span m="891170">had</span>
  <span m="891390">this</span> <span m="892080">and</span> <span m="892300">this.</span>
  <span m="893080">And</span> <span m="893170">there,</span> <span m="893490">we</span>
  <span m="893650">basically--</span> <span m="894980">that''s</span> <span m="895410">the</span>
  <span m="895530">super</span> <span m="895870">node</span> <span m="896950">vertex</span>
  <span m="897460">here,</span> <span m="897650">this</span> <span m="897840">1,</span>
  <span m="898030">1</span> <span m="898240">vertex.</span> <span m="898680">And</span>
  <span m="898790">these</span> <span m="899010">are</span> <span m="899060">the</span>
  <span m="899620">lower</span> <span m="900740">degree</span> <span m="901830">pieces.</span>
  <span m="902940">And</span> <span m="903040">then</span> <span m="903150">these</span>
  <span m="903320">other</span> <span m="904140">vertices</span> <span m="905320">here</span>
  <span m="905980">are</span> <span m="906200">the</span> <span m="906640">singleton</span>
  <span m="907700">vertices.</span> <span m="908170">So</span> <span m="908330">you</span>
  <span m="908450">can</span> <span m="908560">see</span> <span m="908740">as</span>
  <span m="909030">you</span> <span m="909120">naturally</span> <span m="911050">product</span>
  <span m="911570">these</span> <span m="912140">bipartite</span> <span m="912600">graphs</span>
  <span m="912940">together,</span> <span m="913320">you</span> <span m="913450">naturally</span>
  <span m="914010">create</span> <span m="914300">these</span> <span m="914500">power</span>
  <span m="914850">law</span> <span m="916050">graphs.</span></p><p><span m="918700">An</span>
  <span m="919000">example--</span> <span m="919490">I</span> <span m="919600">won''t</span>
  <span m="919780">really</span> <span m="920020">belabor</span> <span m="920470">the</span>
  <span m="920800">details</span> <span m="921230">here--</span> <span m="921390">you</span>
  <span m="921580">can</span> <span m="922350">compute</span> <span m="922760">the</span>
  <span m="922860">degree</span> <span m="923300">distribution.</span> <span m="925960">And
  this</span> <span m="926080">is</span> <span m="926160">all--</span> <span m="926560">there''s</span>
  <span m="926960">a</span> <span m="927030">long</span> <span m="927510">chapter</span>
  <span m="927900">on</span> <span m="928060">this</span> <span m="928250">in</span>
  <span m="928310">the</span> <span m="928380">book.</span> <span m="929560">Basically,</span>
  <span m="930170">you</span> <span m="930280">can</span> <span m="930440">compute</span>
  <span m="931360">analytically</span> <span m="932310">the</span> <span m="932440">degree</span>
  <span m="932830">distributions</span> <span m="933850">of</span> <span m="934140">Kronecker</span>
  <span m="934550">producing</span> <span m="935550">bipartite</span> <span m="935620">graphs.</span>
  <span m="935980">This</span> <span m="936110">shows</span> <span m="936450">you</span>
  <span m="936880">the</span> <span m="936990">formula</span> <span m="937440">for</span>
  <span m="937600">doing</span> <span m="937850">that.</span> <span m="940180">And</span>
  <span m="940920">here</span> <span m="941200">is</span> <span m="941300">the</span>
  <span m="941460">actual</span> <span m="941970">degree</span> <span m="942400">distribution</span>
  <span m="943930">with</span> <span m="944170">the</span> <span m="944300">binomial</span>
  <span m="944820">coefficients</span> <span m="945880">for</span> <span m="946250">that.</span>
  <span m="948400">And</span> <span m="948630">so a</span> <span m="948990">very</span>
  <span m="949190">useful</span> <span m="949630">thing.</span> <span m="949830">You</span>
  <span m="949930">can</span> <span m="950290">a</span> <span m="950545">priori</span>
  <span m="951040">do</span> <span m="951420">that.</span></p><p><span m="952720">This</span>
  <span m="953000">shows</span> <span m="953260">you</span> <span m="953350">the</span>
  <span m="953440">results.</span> <span m="953950">So</span> <span m="954090">if</span>
  <span m="954200">I</span> <span m="954330">have</span> <span m="954570">a</span>
  <span m="954980">Kronecker</span> <span m="955480">product</span> <span m="955990">of</span>
  <span m="956160">a</span> <span m="956360">bipartite</span> <span m="957040">graph</span>
  <span m="957780">n</span> <span m="957980">equals</span> <span m="958470">5</span>
  <span m="958820">comma</span> <span m="959170">1,</span> <span m="959430">and</span>
  <span m="959720">I</span> <span m="959790">take</span> <span m="960010">it</span>
  <span m="960100">out</span> <span m="960280">to</span> <span m="960370">the</span>
  <span m="960470">10th</span> <span m="960760">power,</span> <span m="961470">this</span>
  <span m="961690">is</span> <span m="961870">the</span> <span m="962800">result</span>
  <span m="963270">is</span> <span m="963370">this</span> <span m="963540">blue</span>
  <span m="963810">line.</span> <span m="964730">And</span> <span m="964970">what</span>
  <span m="965150">you</span> <span m="965320">see</span> <span m="965910">is</span>
  <span m="966090">that</span> <span m="966200">you</span> <span m="966340">get--</span>
  <span m="967670">if</span> <span m="967820">you</span> <span m="967930">connect</span>
  <span m="968500">the</span> <span m="968600">last</span> <span m="969010">vertex</span>
  <span m="969580">and</span> <span m="969810">this</span> <span m="969930">vertex--</span>
  <span m="970480">essentially</span> <span m="970990">our</span> <span m="971160">poor</span>
  <span m="971470">man''s</span> <span m="971790">alpha--</span> <span m="972740">or</span>
  <span m="972920">connected</span> <span m="973360">any</span> <span m="973620">one</span>
  <span m="973850">of</span> <span m="973930">these</span> <span m="974120">other</span>
  <span m="974830">sets</span> <span m="975350">here,</span> <span m="975880">they</span>
  <span m="976010">have</span> <span m="976170">a</span> <span m="976230">constant</span>
  <span m="976710">slope</span> <span m="977070">of</span> <span m="977180">negative</span>
  <span m="977530">1.</span> <span m="978720">So</span> <span m="978870">that''s</span>
  <span m="979110">a</span> <span m="979210">theoretical</span> <span m="979920">result</span>
  <span m="980380">is</span> <span m="980500">that</span> <span m="980690">they</span>
  <span m="980810">have</span> <span m="981110">this</span> <span m="981610">constant</span>
  <span m="982090">slope.</span> <span m="983170">And</span> <span m="983250">that''s</span>
  <span m="983480">true</span> <span m="983750">down</span> <span m="984070">here,</span>
  <span m="984350">k to</span> <span m="984650">the</span> <span m="984950">5,</span>
  <span m="986220">other</span> <span m="986440">types</span> <span m="986710">of
  things.</span> <span m="986880">So</span> <span m="986960">we</span> <span m="987060">do</span>
  <span m="987180">get</span> <span m="987340">this</span> <span m="987460">bowing</span>
  <span m="987990">effect.</span> <span m="988420">So it''s</span> <span m="988580">not</span>
  <span m="988850">perfect</span> <span m="989650">with</span> <span m="989800">respect</span>
  <span m="990210">to</span> <span m="990290">that.</span> <span m="991890">But</span>
  <span m="992030">you</span> <span m="992140">can</span> <span m="992270">see</span>
  <span m="992650">how</span> <span m="992900">this</span> <span m="993440">power</span>
  <span m="993790">law</span> <span m="994420">is</span> <span m="994790">baked</span>
  <span m="995230">in</span> <span m="995450">to</span> <span m="995710">the</span>
  <span m="995880">Kronecker</span> <span m="996350">generator,</span> <span m="997160">which</span>
  <span m="997320">is</span> <span m="997430">a</span> <span m="997480">very</span>
  <span m="997690">nice</span> <span m="1000650">thing.</span></p><p><span m="1005070">This</span>
  <span m="1005500">shows</span> <span m="1005950">a</span> <span m="1006040">sample.</span>
  <span m="1006830">We</span> <span m="1007050">basically</span> <span m="1008050">created</span>
  <span m="1008850">a</span> <span m="1010480">4</span> <span m="1010710">by</span>
  <span m="1010860">1</span> <span m="1011110">bipartite</span> <span m="1011750">graph</span>
  <span m="1012150">and</span> <span m="1012270">then</span> <span m="1012410">sampled</span>
  <span m="1012930">it.</span> <span m="1013900">And</span> <span m="1014070">so</span>
  <span m="1014220">this</span> <span m="1014380">shows</span> <span m="1014850">the</span>
  <span m="1015660">stochastic</span> <span m="1016210">instance.</span> <span m="1017280">There''s</span>
  <span m="1017390">about</span> <span m="1017580">a</span> <span m="1017620">million</span>
  <span m="1018010">vertices</span> <span m="1018600">here.</span> <span m="1019300">Shows</span>
  <span m="1019580">you</span> <span m="1019710">that.</span> <span m="1020270">And</span>
  <span m="1020440">then</span> <span m="1020690">these</span> <span m="1021580">curves</span>
  <span m="1022220">here</span> <span m="1023050">show--</span> <span m="1023970">when</span>
  <span m="1024200">we</span> <span m="1024849">take</span> <span m="1025240">the</span>
  <span m="1025920">stochastic</span> <span m="1026619">graph</span> <span m="1027270">and</span>
  <span m="1027420">analytically</span> <span m="1028319">compute</span> <span m="1029390">what</span>
  <span m="1029579">the</span> <span m="1029730">expected</span> <span m="1030579">value</span>
  <span m="1031150">of</span> <span m="1031240">every</span> <span m="1031540">single</span>
  <span m="1031849">degree</span> <span m="1032270">is</span> <span m="1032540">assuming</span>
  <span m="1032970">a</span> <span m="1033040">Poisson</span> <span m="1033500">distribution,</span>
  <span m="1034510">and</span> <span m="1034550">you</span> <span m="1034650">can</span>
  <span m="1034780">see</span> <span m="1035060">that</span> <span m="1035200">we</span>
  <span m="1036210">get</span> <span m="1036420">pretty</span> <span m="1037099">much</span>
  <span m="1037270">a</span> <span m="1037339">perfect</span> <span m="1037740">fit</span>
  <span m="1037950">here</span> <span m="1040160">all</span> <span m="1040460">the</span>
  <span m="1040540">way</span> <span m="1040750">out,</span> <span m="1041800">except</span>
  <span m="1042300">to</span> <span m="1042490">the</span> <span m="1042609">very</span>
  <span m="1043030">end</span> <span m="1043339">here.</span></p><p><span m="1045480">And</span>
  <span m="1045630">this</span> <span m="1045869">is</span> <span m="1046089">where</span>
  <span m="1047130">you</span> <span m="1047220">get</span> <span m="1047359">some</span>
  <span m="1047550">pretty</span> <span m="1048069">interesting</span> <span m="1048610">statistics</span>
  <span m="1049210">going</span> <span m="1049520">on.</span> <span m="1051200">In</span>
  <span m="1051410">theory,</span> <span m="1054390">no</span> <span m="1054900">one</span>
  <span m="1055250">vertex--</span> <span m="1057690">this</span> <span m="1057850">is</span>
  <span m="1057940">your</span> <span m="1058080">distribution.</span> <span m="1059780">No</span>
  <span m="1060030">one</span> <span m="1060280">vertex</span> <span m="1060770">should</span>
  <span m="1060930">actually</span> <span m="1061340">be</span> <span m="1062310">attracting</span>
  <span m="1062710">this</span> <span m="1062870">many</span> <span m="1063100">nodes.</span>
  <span m="1063970">But</span> <span m="1064110">you</span> <span m="1064190">have</span>
  <span m="1064290">so</span> <span m="1064710">many</span> <span m="1064960">vertices</span>
  <span m="1065820">with</span> <span m="1065980">one</span> <span m="1066320">of</span>
  <span m="1066420">them</span> <span m="1066960">that</span> <span m="1067080">have</span>
  <span m="1067320">this</span> <span m="1067520">problem.</span> <span m="1067720">When</span>
  <span m="1067820">you</span> <span m="1067930">sum</span> <span m="1068200">them</span>
  <span m="1068340">all</span> <span m="1068480">together,</span> <span m="1069160">one
  of them</span> <span m="1069630">gets</span> <span m="1069820">to</span> <span m="1069910">be</span>
  <span m="1070050">chosen</span> <span m="1070440">to</span> <span m="1070500">be</span>
  <span m="1070660">the</span> <span m="1070750">winner.</span> <span m="1071520">And</span>
  <span m="1071920">it''s</span> <span m="1072200">what</span> <span m="1072430">pops</span>
  <span m="1072800">it</span> <span m="1072890">up</span> <span m="1073580">here.</span>
  <span m="1074140">So</span> <span m="1075010">all</span> <span m="1075360">the</span>
  <span m="1075460">way</span> <span m="1075670">out</span> <span m="1075980">to</span>
  <span m="1076090">the--</span> <span m="1076605">our fit</span> <span m="1077040">is</span>
  <span m="1077220">very</span> <span m="1077470">good</span> <span m="1077730">all</span>
  <span m="1077940">the way</span> <span m="1078210">out to the</span> <span m="1078360">super</span>
  <span m="1078660">node,</span> <span m="1078890">and</span> <span m="1079020">we</span>
  <span m="1079150">have</span> <span m="1079340">this</span> <span m="1079510">difference</span>
  <span m="1079880">here.</span> <span m="1080010">And this</span> <span m="1080200">is</span>
  <span m="1080240">where</span> <span m="1081230">the</span> <span m="1081330">Poisson</span>
  <span m="1081830">statistics</span> <span m="1082500">begin</span> <span m="1082780">to</span>
  <span m="1082860">fail.</span> <span m="1083740">So</span> <span m="1084260">again,</span>
  <span m="1084540">lots</span> <span m="1084840">of</span> <span m="1084930">opportunities</span>
  <span m="1085550">for</span> <span m="1085670">a</span> <span m="1085700">very</span>
  <span m="1087170">interesting</span> <span m="1087640">theory</span> <span m="1087880">there.</span></p><p><span
  m="1090820">So</span> <span m="1091030">that''s</span> <span m="1091320">just</span>
  <span m="1091610">pure</span> <span m="1092160">bipartite</span> <span m="1092900">graphs.</span>
  <span m="1094460">But</span> <span m="1094970">bipartite</span> <span m="1095500">graphs</span>
  <span m="1095780">have</span> <span m="1095970">no</span> <span m="1097110">inter-group</span>
  <span m="1097840">connections.</span> <span m="1098980">So</span> <span m="1099010">we</span>
  <span m="1099120">can</span> <span m="1099380">actually</span> <span m="1100020">create</span>
  <span m="1101460">something that</span> <span m="1101880">looks</span> <span m="1102070">like</span>
  <span m="1102210">a</span> <span m="1102270">power</span> <span m="1102560">law</span>
  <span m="1102700">graph</span> <span m="1103180">and</span> <span m="1103320">see</span>
  <span m="1104000">all</span> <span m="1104250">the</span> <span m="1104610">community</span>
  <span m="1105120">substructure</span> <span m="1106030">very</span> <span m="1106350">clearly.</span>
  <span m="1107210">But</span> <span m="1107380">those</span> <span m="1107690">communities</span>
  <span m="1108310">are</span> <span m="1108380">not</span> <span m="1108610">connected</span>
  <span m="1109100">in any</span> <span m="1109365">way.</span> <span m="1110130">And</span>
  <span m="1110340">so</span> <span m="1110580">to</span> <span m="1111030">create</span>
  <span m="1111330">connections</span> <span m="1112480">to</span> <span m="1112590">the</span>
  <span m="1112690">communities,</span> <span m="1113330">we</span> <span m="1113440">have</span>
  <span m="1113620">to</span> <span m="1113740">add</span> <span m="1113960">the</span>
  <span m="1114080">identity</span> <span m="1114480">matrix</span> <span m="1114910">down</span>
  <span m="1115160">the</span> <span m="1115465">diagonal.</span> <span m="1115770">And</span>
  <span m="1115940">that</span> <span m="1116170">well</span> <span m="1116340">then</span>
  <span m="1116580">now</span> <span m="1117210">connect</span> <span m="1117630">all</span>
  <span m="1118250">our</span> <span m="1118950">sub</span> <span m="1119510">bipartite</span>
  <span m="1120160">graphs</span> <span m="1120850">together.</span></p><p><span m="1124110">So</span>
  <span m="1124340">this</span> <span m="1124540">just</span> <span m="1124740">shows</span>
  <span m="1125160">here--</span> <span m="1125350">so</span> <span m="1125490">we</span>
  <span m="1125580">basically</span> <span m="1126020">take</span> <span m="1126250">our</span>
  <span m="1126480">bipartite</span> <span m="1127070">graph</span> <span m="1128030">plus
  the</span> <span m="1128320">identity,</span> <span m="1129370">and</span> <span
  m="1129420">that''s</span> <span m="1129650">essentially</span> <span m="1130310">this</span>
  <span m="1131890">combinatorial</span> <span m="1132560">sum</span> <span m="1132860">here</span>
  <span m="1133605">of</span> <span m="1133910">the</span> <span m="1134380">individual</span>
  <span m="1135020">bipartite</span> <span m="1135570">graphs</span> <span m="1136820">there.</span>
  <span m="1137510">Again,</span> <span m="1137870">where in</span> <span m="1138160">quotes,</span>
  <span m="1138510">it means</span> <span m="1138770">that</span> <span m="1138860">there''s</span>
  <span m="1139030">a</span> <span m="1139100">permutation</span> <span m="1139820">you</span>
  <span m="1139920">need</span> <span m="1140200">to</span> <span m="1140320">actually</span>
  <span m="1141090">make</span> <span m="1141300">this</span> <span m="1141490">all</span>
  <span m="1142120">work</span> <span m="1142470">out.</span></p><p><span m="1147190">We</span>
  <span m="1147390">actually</span> <span m="1147740">do</span> <span m="1147960">the</span>
  <span m="1148090">computation.</span> <span m="1151870">This</span> <span m="1152070">shows</span>
  <span m="1153200">the</span> <span m="1154020">4,</span> <span m="1154760">1</span>
  <span m="1154970">bipartite</span> <span m="1155520">plus</span> <span m="1155800">an</span>
  <span m="1155880">identity</span> <span m="1156250">bipartite</span> <span m="1156860">graph</span>
  <span m="1157130">out</span> <span m="1157340">to</span> <span m="1157430">the</span>
  <span m="1157520">fourth</span> <span m="1157830">power.</span> <span m="1158320">So</span>
  <span m="1158650">you</span> <span m="1158810">see</span> <span m="1159130">here</span>
  <span m="1159900">you''re</span> <span m="1160120">going to</span> <span m="1160405">get</span>
  <span m="1160690">1,</span> <span m="1161000">2.</span> <span m="1161270">You</span>
  <span m="1161540">can</span> <span m="1161700">compute</span> <span m="1162080">it</span>
  <span m="1162190">on</span> <span m="1162460">out</span> <span m="1162760">there.</span>
  <span m="1164380">And</span> <span m="1166640">what</span> <span m="1167360">you</span>
  <span m="1167490">see</span> <span m="1167740">is</span> <span m="1168040">this</span>
  <span m="1168390">recursive</span> <span m="1169020">structure,</span> <span m="1169580">almost</span>
  <span m="1169900">fractal</span> <span m="1170340">like</span> <span m="1170570">structure.</span>
  <span m="1171720">So</span> <span m="1171780">that''s</span> <span m="1172010">a</span>
  <span m="1172050">nice</span> <span m="1172300">way</span> <span m="1172430">to</span>
  <span m="1172520">view</span> <span m="1172740">it.</span> <span m="1173240">That''s</span>
  <span m="1173410">one</span> <span m="1173610">way</span> <span m="1173780">to</span>
  <span m="1174150">see</span> <span m="1174390">it.</span> <span m="1175020">But</span>
  <span m="1175290">you</span> <span m="1175410">don''t</span> <span m="1175660">really</span>
  <span m="1175930">see</span> <span m="1176440">the</span> <span m="1176560">bipartite</span>
  <span m="1177370">substructure</span> <span m="1178430">in</span> <span m="1178600">there.</span>
  <span m="1178860">It''s</span> <span m="1179040">hard</span> <span m="1179690">to</span>
  <span m="1179770">see</span> <span m="1180020">what''s</span> <span m="1180250">going</span>
  <span m="1180520">on</span> <span m="1180700">there.</span></p><p><span m="1181870">Well,</span>
  <span m="1182020">since</span> <span m="1182210">this is</span> <span m="1182490">analytic,</span>
  <span m="1183190">we</span> <span m="1183330">can</span> <span m="1183500">actually</span>
  <span m="1183850">compute</span> <span m="1184730">a</span> <span m="1184830">permutation</span>
  <span m="1185540">that</span> <span m="1185650">says</span> <span m="1185870">please</span>
  <span m="1186180">recover</span> <span m="1186810">all</span> <span m="1187050">those</span>
  <span m="1187240">bipartite</span> <span m="1187820">substructures.</span> <span
  m="1189030">And</span> <span m="1189280">so</span> <span m="1189880">in</span> <span
  m="1190050">the</span> <span m="1190240">software,</span> <span m="1190850">actually,</span>
  <span m="1191130">[INAUDIBLE],</span> <span m="1191590">we have a</span> <span m="1191910">way</span>
  <span m="1192230">of</span> <span m="1192660">basically</span> <span m="1193140">computing</span>
  <span m="1193630">a</span> <span m="1193700">permutation</span> <span m="1194410">of</span>
  <span m="1194520">this</span> <span m="1195010">that</span> <span m="1195110">basically</span>
  <span m="1195415">regroups</span> <span m="1196930">all</span> <span m="1197270">our</span>
  <span m="1198620">bipartite</span> <span m="1199280">groups</span> <span m="1199600">here.</span>
  <span m="1200060">And</span> <span m="1200160">then</span> <span m="1200270">you</span>
  <span m="1200370">can</span> <span m="1200510">see</span> <span m="1201270">all</span>
  <span m="1201650">the</span> <span m="1201890">bipartite</span> <span m="1203670">cores</span>
  <span m="1204140">or</span> <span m="1204240">bipartite</span> <span m="1204870">pieces,</span>
  <span m="1205590">and</span> <span m="1205700">then</span> <span m="1205820">all</span>
  <span m="1206270">the</span> <span m="1206450">interconnections</span> <span m="1207220">between</span>
  <span m="1207560">those</span> <span m="1207780">core</span> <span m="1208050">bipartite</span>
  <span m="1208600">pieces.</span></p><p><span m="1210080">To</span> <span m="1210570">give</span>
  <span m="1210750">you</span> <span m="1210860">a</span> <span m="1210910">better</span>
  <span m="1211180">sense</span> <span m="1211440">of</span> <span m="1211530">what</span>
  <span m="1211710">that</span> <span m="1211960">really</span> <span m="1212240">means,</span>
  <span m="1212940">here,</span> <span m="1214480">basically</span> <span m="1215160">we</span>
  <span m="1217400">have</span> <span m="1217840">b</span> <span m="1218520">to</span>
  <span m="1218630">the</span> <span m="1219000">i</span> <span m="1219370">to the</span>
  <span m="1219740">third</span> <span m="1220070">power</span> <span m="1220440">here.</span>
  <span m="1223000">That''s</span> <span m="1223220">what</span> <span m="1223340">it</span>
  <span m="1223410">looks</span> <span m="1223700">like.</span> <span m="1224190">If</span>
  <span m="1224320">we</span> <span m="1224450">just</span> <span m="1224950">subtract</span>
  <span m="1225670">out</span> <span m="1225980">the</span> <span m="1226080">first</span>
  <span m="1226500">and</span> <span m="1226640">second</span> <span m="1227010">order</span>
  <span m="1227720">components,</span> <span m="1228850">then</span> <span m="1229010">we''re</span>
  <span m="1229150">left</span> <span m="1229500">with</span> <span m="1229670">these</span>
  <span m="1229910">are</span> <span m="1229970">the</span> <span m="1230200">interconnecting</span>
  <span m="1231390">pieces.</span> <span m="1232010">We</span> <span m="1232450">can</span>
  <span m="1232570">see</span> <span m="1232690">that</span> <span m="1232820">much</span>
  <span m="1233070">better</span> <span m="1233330">when</span> <span m="1233480">we</span>
  <span m="1234120">permute</span> <span m="1234530">it.</span> <span m="1234700">So</span>
  <span m="1234940">here</span> <span m="1235340">is</span> <span m="1235570">the</span>
  <span m="1236370">permutation</span> <span m="1237220">of</span> <span m="1237440">just</span>
  <span m="1237640">the</span> <span m="1237730">bipartite</span> <span m="1238510">piece,</span>
  <span m="1239120">and</span> <span m="1239600">that</span> <span m="1239840">shows</span>
  <span m="1240070">you</span> <span m="1240180">these</span> <span m="1240450">core</span>
  <span m="1241720">bipartite</span> <span m="1242580">chunks</span> <span m="1243290">that</span>
  <span m="1243650">are</span> <span m="1243820">in</span> <span m="1244100">the</span>
  <span m="1244210">graph.</span> <span m="1245430">We</span> <span m="1245590">then</span>
  <span m="1245880">do</span> <span m="1246080">the</span> <span m="1246210">second</span>
  <span m="1246700">term,</span> <span m="1247010">which</span> <span m="1247230">is</span>
  <span m="1247810">b</span> <span m="1248290">kron</span> <span m="1248680">b</span>
  <span m="1249010">kron</span> <span m="1249400">i.</span></p><p><span m="1250630">So</span>
  <span m="1251040">this</span> <span m="1251240">is the</span> <span m="1251410">second.</span>
  <span m="1251610">Now</span> <span m="1251740">you</span> <span m="1251870">can</span>
  <span m="1252000">see</span> <span m="1252220">that</span> <span m="1252360">this</span>
  <span m="1252570">creates</span> <span m="1252970">connections</span> <span m="1253610">between</span>
  <span m="1254020">these</span> <span m="1254310">groups.</span> <span m="1256540">And</span>
  <span m="1256740">then</span> <span m="1256920">likewise,</span> <span m="1257630">if</span>
  <span m="1257750">you</span> <span m="1257860">do</span> <span m="1258270">the</span>
  <span m="1258390">next</span> <span m="1258730">one--</span> <span m="1258960">so</span>
  <span m="1259140">b</span> <span m="1260290">kron</span> <span m="1260810">i</span>
  <span m="1261890">b,</span> <span m="1262850">that</span> <span m="1263030">shows</span>
  <span m="1263260">you</span> <span m="1263380">the</span> <span m="1263630">connections</span>
  <span m="1264050">between</span> <span m="1264410">these</span> <span m="1264640">groups,</span>
  <span m="1265200">and</span> <span m="1265360">then</span> <span m="1265530">ibb</span>
  <span m="1266160">shows</span> <span m="1266990">you</span> <span m="1267090">the</span>
  <span m="1267190">different</span> <span m="1267480">connections</span> <span m="1268230">in</span>
  <span m="1268480">these</span> <span m="1268690">groups.</span> <span m="1268930">So</span>
  <span m="1269080">each</span> <span m="1270010">set</span> <span m="1270320">of--</span>
  <span m="1271710">when</span> <span m="1271880">we</span> <span m="1272000">take</span>
  <span m="1273440">b</span> <span m="1273730">plus</span> <span m="1274060">i</span>
  <span m="1274610">and</span> <span m="1274860">multiply</span> <span m="1275440">it</span>
  <span m="1275630">out</span> <span m="1276610">and</span> <span m="1276810">look</span>
  <span m="1276990">at</span> <span m="1277060">all</span> <span m="1277310">those</span>
  <span m="1277530">different</span> <span m="1277850">combinations</span> <span m="1278760">of</span>
  <span m="1278900">the</span> <span m="1278990">different</span> <span m="1279550">multiplies</span>
  <span m="1280430">there,</span> <span m="1281202">there''s</span> <span m="1281590">the</span>
  <span m="1281740">core</span> <span m="1282210">piece,</span> <span m="1283060">which</span>
  <span m="1283350">is</span> <span m="1283470">just</span> <span m="1283690">b</span>
  <span m="1284640">kron</span> <span m="1285060">to</span> <span m="1285140">the</span>
  <span m="1285270">3,</span> <span m="1285890">and</span> <span m="1286620">that</span>
  <span m="1286800">creates</span> <span m="1287110">this</span> <span m="1287380">core</span>
  <span m="1287780">structure</span> <span m="1288790">here,</span> <span m="1290020">which</span>
  <span m="1290400">is</span> <span m="1290500">these</span> <span m="1290710">dense</span>
  <span m="1291110">pieces,</span> <span m="1291760">and</span> <span m="1291880">then</span>
  <span m="1292010">all</span> <span m="1292280">the</span> <span m="1292420">other</span>
  <span m="1292720">polynomials</span> <span m="1293720">are</span> <span m="1293820">essentially</span>
  <span m="1294100">creating</span> <span m="1294520">interconnections</span> <span
  m="1295260">between</span> <span m="1295610">that.</span> <span m="1295810">So</span>
  <span m="1295900">you</span> <span m="1295980">can</span> <span m="1296120">get
  a</span> <span m="1296280">really</span> <span m="1296980">deep</span> <span m="1297490">understanding</span>
  <span m="1298360">of</span> <span m="1298430">the</span> <span m="1298540">core</span>
  <span m="1298890">structure</span> <span m="1299680">and</span> <span m="1299800">how</span>
  <span m="1300080">those</span> <span m="1300380">things</span> <span m="1301450">connect</span>
  <span m="1301780">together,</span> <span m="1302270">which</span> <span m="1302360">can</span>
  <span m="1302480">be</span> <span m="1302600">very</span> <span m="1303110">interesting.</span></p><p><span
  m="1306360">But</span> <span m="1306790">we</span> <span m="1306920">can</span>
  <span m="1307080">compute</span> <span m="1307540">these</span> <span m="1307910">interconnected</span>
  <span m="1308640">structures</span> <span m="1309220">fairly</span> <span m="1309580">nicely.</span>
  <span m="1311480">Here''s</span> <span m="1311800">a</span> <span m="1311910">higher</span>
  <span m="1312340">order</span> <span m="1312670">example</span> <span m="1313130">going</span>
  <span m="1313380">out</span> <span m="1313500">to</span> <span m="1313580">the</span>
  <span m="1313690">fifth.</span> <span m="1316230">But</span> <span m="1316340">we</span>
  <span m="1316440">can</span> <span m="1316580">compute</span> <span m="1316870">the</span>
  <span m="1316960">structure,</span> <span m="1317570">this</span> <span m="1317840">chi</span>
  <span m="1319290">structure</span> <span m="1319565">here,</span> <span m="1319840">which</span>
  <span m="1320200">is</span> <span m="1320350">essentially</span> <span m="1320800">a</span>
  <span m="1320860">summary</span> <span m="1321390">of</span> <span m="1321470">these,</span>
  <span m="1322060">by</span> <span m="1322190">just</span> <span m="1322470">looking</span>
  <span m="1322840">at</span> <span m="1326100">a</span> <span m="1326400">two-by-two.</span>
  <span m="1327630">So</span> <span m="1327770">we</span> <span m="1327850">can</span>
  <span m="1327970">compute</span> <span m="1328320">all</span> <span m="1328700">the</span>
  <span m="1328780">structures</span> <span m="1329500">of</span> <span m="1329600">the</span>
  <span m="1329700">interconnections</span> <span m="1330370">by</span> <span m="1330490">just</span>
  <span m="1330690">looking.</span> <span m="1330940">Since</span> <span m="1331090">we</span>
  <span m="1331200">have</span> <span m="1331340">a</span> <span m="1331410">bipartite</span>
  <span m="1332470">thing,</span> <span m="1333010">we</span> <span m="1333130">can</span>
  <span m="1333280">collapse</span> <span m="1333740">all</span> <span m="1333900">those</span>
  <span m="1334080">pieces</span> <span m="1334490">down</span> <span m="1334940">and</span>
  <span m="1335180">just</span> <span m="1335360">have a</span> <span m="1335640">two-by-two.</span>
  <span m="1335920">So</span> <span m="1336300">we</span> <span m="1336460">have</span>
  <span m="1336650">here</span> <span m="1337120">a</span> <span m="1337230">little</span>
  <span m="1337480">tiny</span> <span m="1337810">version</span> <span m="1338690">of</span>
  <span m="1338840">this</span> <span m="1339030">structure</span> <span m="1339295">here.</span>
  <span m="1339560">It</span> <span m="1339650">shows</span> <span m="1339910">you</span>
  <span m="1340020">that.</span> <span m="1340830">Likewise,</span> <span m="1341240">this</span>
  <span m="1341370">structure</span> <span m="1341760">here is</span> <span m="1342030">summarized</span>
  <span m="1342580">by</span> <span m="1342760">that,</span> <span m="1343650">and</span>
  <span m="1343820">this</span> <span m="1343900">structure</span> <span m="1344360">here</span>
  <span m="1344600">is</span> <span m="1344830">summarized</span> <span m="1345090">by</span>
  <span m="1345250">that.</span></p><p><span m="1346030">So you</span> <span m="1346160">can
  get</span> <span m="1346500">complete</span> <span m="1347010">knowledge,</span>
  <span m="1347480">not</span> <span m="1347860">just</span> <span m="1348010">at</span>
  <span m="1348160">the</span> <span m="1348250">low</span> <span m="1348490">level</span>
  <span m="1348800">scale,</span> <span m="1349160">but</span> <span m="1349320">at</span>
  <span m="1349440">all</span> <span m="1349750">scales</span> <span m="1350340">if</span>
  <span m="1350590">you</span> <span m="1350730">wanted</span> <span m="1350870">to</span>
  <span m="1351000">say</span> <span m="1351270">I</span> <span m="1351320">want</span>
  <span m="1351510">to</span> <span m="1351560">look</span> <span m="1351720">at</span>
  <span m="1351780">the</span> <span m="1351870">blocks</span> <span m="1352380">and</span>
  <span m="1352440">how</span> <span m="1352620">the</span> <span m="1352730">edges</span>
  <span m="1353050">are</span> <span m="1353130">connected</span> <span m="1353820">in</span>
  <span m="1353960">detail,</span> <span m="1354640">or if</span> <span m="1354830">I</span>
  <span m="1354890">just</span> <span m="1355120">want</span> <span m="1355270">to</span>
  <span m="1355400">consider</span> <span m="1355820">things</span> <span m="1356110">in</span>
  <span m="1356210">big</span> <span m="1356380">blocks</span> <span m="1357160">and</span>
  <span m="1357240">connect</span> <span m="1357580">them,</span> <span m="1357810">I</span>
  <span m="1357900">can</span> <span m="1358070">do</span> <span m="1358180">that</span>
  <span m="1358370">very</span> <span m="1358560">nicely</span> <span m="1358940">as</span>
  <span m="1359050">well.</span> <span m="1361050">And</span> <span m="1361220">again,</span>
  <span m="1361480">we</span> <span m="1361570">can</span> <span m="1361720">compute</span>
  <span m="1362010">the</span> <span m="1362100">degree</span> <span m="1362400">distributions</span>
  <span m="1363050">as</span> <span m="1363180">well.</span> <span m="1364050">So</span>
  <span m="1364090">this</span> <span m="1364320">just</span> <span m="1364500">shows</span>
  <span m="1365300">b</span> <span m="1366260">kron</span> <span m="1366500">to</span>
  <span m="1366560">the</span> <span m="1366690">k,</span> <span m="1367560">and</span>
  <span m="1367750">then</span> <span m="1368060">b</span> <span m="1368480">plus</span>
  <span m="1368600">the</span> <span m="1368700">second</span> <span m="1369040">order</span>
  <span m="1369360">terms,</span> <span m="1370080">and</span> <span m="1370260">then</span>
  <span m="1370820">moving</span> <span m="1371210">on</span> <span m="1371450">out.</span>
  <span m="1371760">And</span> <span m="1371860">actually,</span> <span m="1372240">what</span>
  <span m="1372270">you</span> <span m="1372390">see</span> <span m="1372690">is</span>
  <span m="1372810">by</span> <span m="1372960">adding</span> <span m="1373310">this</span>
  <span m="1373500">identity</span> <span m="1373880">matrix,</span> <span m="1374290">all
  it</span> <span m="1374450">does</span> <span m="1374590">is</span> <span m="1374940">slide</span>
  <span m="1375860">the</span> <span m="1375980">degree</span> <span m="1376330">structure</span>
  <span m="1377590">over.</span> <span m="1379030">It</span> <span m="1379170">also</span>
  <span m="1379420">does</span> <span m="1379710">change</span> <span m="1380030">the</span>
  <span m="1380140">slope</span> <span m="1381160">a</span> <span m="1381270">little</span>
  <span m="1381460">bit</span> <span m="1381630">here</span> <span m="1382000">by</span>
  <span m="1382130">adding</span> <span m="1382500">this</span> <span m="1382690">identity</span>
  <span m="1383070">matrix</span> <span m="1383560">along.</span> <span m="1384160">So</span>
  <span m="1384360">it''s</span> <span m="1384670">steeper</span> <span m="1385240">than</span>
  <span m="1385380">the</span> <span m="1385510">original.</span></p><p><span m="1386940">And</span>
  <span m="1387250">you</span> <span m="1387360">can</span> <span m="1387490">do</span>
  <span m="1387640">other</span> <span m="1387900">types</span> <span m="1388160">of</span>
  <span m="1388280">things.</span> <span m="1388820">Here''s</span> <span m="1389040">something</span>
  <span m="1389380">we</span> <span m="1389490">did</span> <span m="1389670">in</span>
  <span m="1389790">iso-parametric</span> <span m="1390640">ratios.</span> <span m="1391550">I</span>
  <span m="1391650">won''t</span> <span m="1391870">belabor</span> <span m="1392300">that.</span>
  <span m="1392520">But</span> <span m="1392610">it</span> <span m="1392690">essentially</span>
  <span m="1393080">is a way</span> <span m="1393270">of</span> <span m="1393360">computing</span>
  <span m="1393790">the</span> <span m="1393870">surface</span> <span m="1394310">to</span>
  <span m="1394390">volume</span> <span m="1394850">of</span> <span m="1394910">subgraphs.</span>
  <span m="1395960">And</span> <span m="1396030">we</span> <span m="1396100">can</span>
  <span m="1396240">compute</span> <span m="1396510">this</span> <span m="1396660">analytically.</span>
  <span m="1398020">And</span> <span m="1398160">we</span> <span m="1398270">see</span>
  <span m="1398480">that the</span> <span m="1398610">iso-parametric</span> <span
  m="1399430">ratio</span> <span m="1401170">of</span> <span m="1401380">a</span>
  <span m="1401460">bipartite</span> <span m="1402100">subgraph</span> <span m="1402680">is</span>
  <span m="1403360">constant,</span> <span m="1405480">but</span> <span m="1405670">the</span>
  <span m="1405760">half</span> <span m="1406230">bipartite</span> <span m="1407260">graph</span>
  <span m="1407570">has</span> <span m="1407810">this</span> <span m="1408000">property</span>
  <span m="1408400">here.</span></p><p><span m="1409090">And</span> <span m="1409250">just</span>
  <span m="1409420">to</span> <span m="1409520">summarize</span> <span m="1410100">here--</span>
  <span m="1410270">and</span> <span m="1410470">this</span> <span m="1410640">is</span>
  <span m="1410920">done</span> <span m="1411090">a</span> <span m="1411130">great</span>
  <span m="1411340">deal</span> <span m="1411550">in the</span> <span m="1411620">chapter--</span>
  <span m="1412620">this</span> <span m="1412820">just</span> <span m="1413000">shows</span>
  <span m="1413630">different</span> <span m="1413920">examples</span> <span m="1414460">of</span>
  <span m="1414540">the</span> <span m="1414650">theoretical</span> <span m="1415230">results</span>
  <span m="1415890">you</span> <span m="1416000">can</span> <span m="1416150">compute</span>
  <span m="1417050">for</span> <span m="1417495">a</span> <span m="1417940">bipartite</span>
  <span m="1418430">graph</span> <span m="1418940">or</span> <span m="1419100">a</span>
  <span m="1419270">bipartite</span> <span m="1419680">plus</span> <span m="1419960">an</span>
  <span m="1420040">identity,</span> <span m="1421510">the</span> <span m="1421580">degree</span>
  <span m="1421880">distribution.</span> <span m="1423530">Betweenness</span> <span
  m="1423960">centrality</span> <span m="1424550">is</span> <span m="1424650">a</span>
  <span m="1424690">fairly</span> <span m="1424990">complicated</span> <span m="1425500">metric.</span>
  <span m="1425820">We</span> <span m="1425930">actually</span> <span m="1426180">haven''t</span>
  <span m="1426450">figured it</span> <span m="1426770">out</span> <span m="1426970">for</span>
  <span m="1427050">this</span> <span m="1427230">one,</span> <span m="1427360">or</span>
  <span m="1427760">I</span> <span m="1427840">didn''t</span> <span m="1428050">bother
  to</span> <span m="1428370">figure it</span> <span m="1428700">out for</span> <span
  m="1428880">this</span> <span m="1429100">one.</span> <span m="1429770">I can</span>
  <span m="1429960">compute</span> <span m="1430390">the</span> <span m="1430470">diameter</span>
  <span m="1432120">very</span> <span m="1432280">nicely.</span> <span m="1432640">You
  can</span> <span m="1433000">compute the</span> <span m="1433130">eigenvalues.</span>
  <span m="1434310">And</span> <span m="1434700">the</span> <span m="1434980">iso-parametric</span>
  <span m="1436100">are</span> <span m="1436170">just</span> <span m="1436420">all</span>
  <span m="1436650">examples</span> <span m="1437130">of</span> <span m="1437220">a</span>
  <span m="1437270">kind</span> <span m="1437530">of</span> <span m="1437610">theoretical</span>
  <span m="1438210">work</span> <span m="1438770">you</span> <span m="1438930">can</span>
  <span m="1439150">do.</span> <span m="1439790">And</span> <span m="1440150">again,</span>
  <span m="1440380">I</span> <span m="1440450">think</span> <span m="1440590">it''s</span>
  <span m="1440730">very</span> <span m="1440940">useful</span> <span m="1441200">if</span>
  <span m="1441320">you</span> <span m="1441400">want</span> <span m="1441540">to</span>
  <span m="1442060">understand</span> <span m="1443010">the</span> <span m="1443090">substructure</span>
  <span m="1444160">and</span> <span m="1444260">how</span> <span m="1444470">the</span>
  <span m="1444550">different</span> <span m="1444830">parts</span> <span m="1445100">of</span>
  <span m="1445140">a</span> <span m="1445230">power</span> <span m="1445700">law</span>
  <span m="1446070">graph</span> <span m="1446330">might</span> <span m="1446870">interact</span>
  <span m="1447380">with</span> <span m="1447520">each</span> <span m="1447670">other.</span></p><p><span
  m="1450390">So</span> <span m="1450460">that</span> <span m="1450630">just</span>
  <span m="1450790">talks</span> <span m="1451040">about</span> <span m="1452026">Kronecker</span>
  <span m="1452480">graphs</span> <span m="1453090">and</span> <span m="1454130">what</span>
  <span m="1454420">are</span> <span m="1454520">the</span> <span m="1454630">bases</span>
  <span m="1455240">of</span> <span m="1455360">these</span> <span m="1455570">benchmarks.</span>
  <span m="1456540">And</span> <span m="1456760">now</span> <span m="1457000">I''m</span>
  <span m="1457120">going</span> <span m="1457270">to</span> <span m="1457310">get</span>
  <span m="1457490">into</span> <span m="1458590">some</span> <span m="1458850">benchmarks</span>
  <span m="1459390">again</span> <span m="1460220">themselves.</span> <span m="1463460">So</span>
  <span m="1463680">this is</span> <span m="1463910">just</span> <span m="1464460">to</span>
  <span m="1464650">remind</span> <span m="1465110">folks.</span> <span m="1466130">This</span>
  <span m="1466420">just</span> <span m="1466610">shows</span> <span m="1466980">some</span>
  <span m="1467110">examples</span> <span m="1468245">of</span> <span m="1468500">when</span>
  <span m="1468760">you''re</span> <span m="1469330">doing</span> <span m="1470040">benchmarking</span>
  <span m="1471310">of</span> <span m="1471780">inserts</span> <span m="1472940">into</span>
  <span m="1473410">a</span> <span m="1473480">database.</span> <span m="1474860">Normally,</span>
  <span m="1475190">when you do</span> <span m="1475320">parallel</span> <span m="1475680">computing,</span>
  <span m="1476090">you</span> <span m="1476210">have</span> <span m="1476530">one</span>
  <span m="1477890">parameter,</span> <span m="1479390">which</span> <span m="1479760">is</span>
  <span m="1480430">how</span> <span m="1480580">many</span> <span m="1481070">parallel</span>
  <span m="1481410">processes</span> <span m="1482660">are</span> <span m="1482830">you</span>
  <span m="1483030">running</span> <span m="1483960">at</span> <span m="1484180">the</span>
  <span m="1484280">same</span> <span m="1484610">time.</span> <span m="1485510">And</span>
  <span m="1485680">so</span> <span m="1485830">most</span> <span m="1486120">of</span>
  <span m="1486290">your</span> <span m="1486440">scaling</span> <span m="1486920">curves</span>
  <span m="1487410">will</span> <span m="1487590">be</span> <span m="1488150">with</span>
  <span m="1488300">respect</span> <span m="1488750">to,</span> <span m="1489030">in</span>
  <span m="1489120">this</span> <span m="1489310">case,</span> <span m="1492430">the</span>
  <span m="1492560">number</span> <span m="1492890">of</span> <span m="1492960">concurrent</span>
  <span m="1493490">processes</span> <span m="1494210">that</span> <span m="1494310">you''re</span>
  <span m="1494520">running</span> <span m="1494830">at</span> <span m="1494930">one</span>
  <span m="1495170">time</span> <span m="1495480">here.</span> <span m="1496120">I</span>
  <span m="1496170">think</span> <span m="1496350">we''re</span> <span m="1497120">going</span>
  <span m="1497340">up</span> <span m="1497440">to</span> <span m="1497560">32</span>
  <span m="1498030">here.</span> <span m="1498770">That''s</span> <span m="1498950">the</span>
  <span m="1499080">standard</span> <span m="1500010">parameter</span> <span m="1500400">in</span>
  <span m="1500790">parallel</span> <span m="1500990">computing.</span></p><p><span
  m="1501370">When you</span> <span m="1501580">have parallel</span> <span m="1502030">databases</span>
  <span m="1502810">involved,</span> <span m="1504710">now</span> <span m="1504980">you</span>
  <span m="1505140">have</span> <span m="1505880">a</span> <span m="1506000">couple</span>
  <span m="1506330">of</span> <span m="1506420">additional</span> <span m="1506910">parameters,</span>
  <span m="1507790">which</span> <span m="1508030">just</span> <span m="1508230">make</span>
  <span m="1508440">it</span> <span m="1508770">that</span> <span m="1509040">much</span>
  <span m="1509360">more</span> <span m="1510400">stuff</span> <span m="1510820">you</span>
  <span m="1510940">have</span> <span m="1511030">to</span> <span m="1511140">keep</span>
  <span m="1511240">in</span> <span m="1511440">your</span> <span m="1511550">head.</span>
  <span m="1513330">Essentially,</span> <span m="1513910">in</span> <span m="1513990">this</span>
  <span m="1514200">case,</span> <span m="1514980">Accumulo</span> <span m="1515520">calls</span>
  <span m="1515890">its</span> <span m="1516060">individual</span> <span m="1516690">data</span>
  <span m="1516960">servers</span> <span m="1517410">tablet</span> <span m="1517850">servers,</span>
  <span m="1518590">so</span> <span m="1518600">you</span> <span m="1518660">have</span>
  <span m="1518780">to</span> <span m="1518850">be</span> <span m="1518960">aware</span>
  <span m="1519130">of</span> <span m="1519200">how</span> <span m="1519360">many</span>
  <span m="1519570">tablet</span> <span m="1520110">servers</span> <span m="1520500">you</span>
  <span m="1520680">have.</span> <span m="1521670">So</span> <span m="1522170">that''s</span>
  <span m="1522340">another</span> <span m="1522700">parameter.</span> <span m="1523170">So</span>
  <span m="1523330">you</span> <span m="1523470">have</span> <span m="1523620">to</span>
  <span m="1523710">create</span> <span m="1523930">separate</span> <span m="1524360">curves</span>
  <span m="1524740">here.</span></p><p><span m="1524880">This</span> <span m="1525110">is</span>
  <span m="1525270">our</span> <span m="1525830">scaling</span> <span m="1526360">curve</span>
  <span m="1526560">with</span> <span m="1526700">a</span> <span m="1526720">number</span>
  <span m="1527000">of</span> <span m="1527070">ingest</span> <span m="1527540">processes</span>
  <span m="1528260">into</span> <span m="1528450">one</span> <span m="1528750">tablet</span>
  <span m="1529170">server</span> <span m="1530200">versus</span> <span m="1530590">number
  of</span> <span m="1530880">ingest</span> <span m="1531250">processes</span> <span
  m="1531870">into</span> <span m="1532760">six</span> <span m="1533130">tablets</span>
  <span m="1533550">servers.</span> <span m="1533940">And</span> <span m="1534040">as</span>
  <span m="1534290">you</span> <span m="1534400">can</span> <span m="1534540">see,</span>
  <span m="1536160">not</span> <span m="1536360">a</span> <span m="1536420">huge</span>
  <span m="1536730">difference</span> <span m="1537100">here</span> <span m="1537270">at
  the</span> <span m="1537410">small</span> <span m="1537820">end.</span> <span m="1538030">But</span>
  <span m="1538170">eventually,</span> <span m="1539130">the</span> <span m="1539230">one</span>
  <span m="1539460">tablet</span> <span m="1539830">server</span> <span m="1542530">database</span>
  <span m="1543530">levels</span> <span m="1543800">off</span> <span m="1544480">while</span>
  <span m="1544620">the</span> <span m="1544750">other</span> <span m="1544880">one</span>
  <span m="1545120">keeps</span> <span m="1545430">on</span> <span m="1545590">scaling.</span>
  <span m="1546650">And</span> <span m="1546820">so</span> <span m="1546940">this</span>
  <span m="1547150">is</span> <span m="1547280">very</span> <span m="1547570">tricky.</span>
  <span m="1548360">If</span> <span m="1548470">you</span> <span m="1548590">want</span>
  <span m="1548950">to</span> <span m="1549080">do</span> <span m="1549330">these</span>
  <span m="1549630">kind</span> <span m="1549900">of</span> <span m="1549970">results,</span>
  <span m="1550280">you</span> <span m="1550720">have</span> <span m="1550890">to</span>
  <span m="1550980">be</span> <span m="1551110">aware</span> <span m="1551540">of</span>
  <span m="1551590">both</span> <span m="1551930">of</span> <span m="1552050">these</span>
  <span m="1552310">parameters</span> <span m="1553740">in</span> <span m="1553930">order</span>
  <span m="1554220">to</span> <span m="1554720">really</span> <span m="1554970">understand</span>
  <span m="1555480">what</span> <span m="1556050">you''re</span> <span m="1556210">doing.</span></p><p><span
  m="1560050">There''s</span> <span m="1560090">also</span> <span m="1560400">a</span>
  <span m="1560510">third</span> <span m="1560930">parameter</span> <span m="1561540">which</span>
  <span m="1561770">is</span> <span m="1561920">generally</span> <span m="1562360">true</span>
  <span m="1562800">of</span> <span m="1562910">most</span> <span m="1563580">databases,</span>
  <span m="1564420">and</span> <span m="1564500">Accumulo</span> <span m="1564760">is</span>
  <span m="1565020">no</span> <span m="1565120">exception,</span> <span m="1565650">which</span>
  <span m="1565870">is</span> <span m="1566010">that</span> <span m="1566530">you''re</span>
  <span m="1566740">inserting</span> <span m="1567960">a</span> <span m="1568240">table</span>
  <span m="1568560">into</span> <span m="1568880">a</span> <span m="1568950">parallel</span>
  <span m="1569260">database,</span> <span m="1570260">that</span> <span m="1570450">table</span>
  <span m="1570710">is</span> <span m="1570800">going</span> <span m="1570930">to</span>
  <span m="1570980">be</span> <span m="1571080">split</span> <span m="1571960">amongst</span>
  <span m="1573110">the</span> <span m="1573840">different</span> <span m="1575360">parallel</span>
  <span m="1575740">servers</span> <span m="1576440">in</span> <span m="1576580">the</span>
  <span m="1576650">database.</span> <span m="1577740">And</span> <span m="1580240">that</span>
  <span m="1580410">will</span> <span m="1580520">have</span> <span m="1580640">a</span>
  <span m="1580700">big</span> <span m="1581010">impact</span> <span m="1581490">on</span>
  <span m="1581620">performance.</span> <span m="1582150">How</span> <span m="1583530">many</span>
  <span m="1583890">splits</span> <span m="1584550">you</span> <span m="1584700">have--</span>
  <span m="1585420">because</span> <span m="1585560">you''re</span> <span m="1585660">not</span>
  <span m="1585870">going</span> <span m="1585970">to</span> <span m="1586070">be</span>
  <span m="1586170">able</span> <span m="1586270">to</span> <span m="1586370">take</span>
  <span m="1586440">advantage</span> <span m="1586695">of--</span> <span m="1586950">if</span>
  <span m="1587450">you</span> <span m="1587550">have</span> <span m="1587660">fewer</span>
  <span m="1588040">splits</span> <span m="1588440">than the</span> <span m="1588540">number</span>
  <span m="1589000">of</span> <span m="1589070">database</span> <span m="1589890">server</span>
  <span m="1590220">nodes,</span> <span m="1590550">then</span> <span m="1590740">you''re</span>
  <span m="1590840">not</span> <span m="1591040">taking</span> <span m="1591390">advantage</span>
  <span m="1591820">of</span> <span m="1591870">those.</span> <span m="1592390">And</span>
  <span m="1592510">then</span> <span m="1592980">how</span> <span m="1593220">balanced</span>
  <span m="1593910">those</span> <span m="1594140">splits</span> <span m="1594600">are.</span>
  <span m="1595250">Is</span> <span m="1595360">the</span> <span m="1595470">data</span>
  <span m="1595800">going</span> <span m="1596130">in</span> <span m="1596670">uniformly</span>
  <span m="1597700">into</span> <span m="1598630">those</span> <span m="1598870">things?</span></p><p><span
  m="1599490">And</span> <span m="1599650">so</span> <span m="1599770">this</span>
  <span m="1600000">just</span> <span m="1600170">shows</span> <span m="1600640">you</span>
  <span m="1601140">an</span> <span m="1601220">example</span> <span m="1601840">of</span>
  <span m="1602020">an</span> <span m="1602110">8</span> <span m="1602330">tablet</span>
  <span m="1602720">server</span> <span m="1603130">Accumulo</span> <span m="1604120">doing
  the</span> <span m="1604420">inserts</span> <span m="1605000">with</span> <span
  m="1605220">no</span> <span m="1605420">splits</span> <span m="1606280">versus</span>
  <span m="1606690">doing</span> <span m="1606980">it,</span> <span m="1607050">in</span>
  <span m="1607130">this</span> <span m="1607320">case,</span> <span m="1607680">with</span>
  <span m="1607965">35</span> <span m="1608250">splits.</span> <span m="1608550">And
  you see</span> <span m="1608890">there''s</span> <span m="1609050">a</span> <span
  m="1609140">rather</span> <span m="1609460">large</span> <span m="1610440">impact</span>
  <span m="1611010">on</span> <span m="1611120">the</span> <span m="1611220">performance</span>
  <span m="1611860">there.</span> <span m="1612390">So</span> <span m="1613050">D4M</span>
  <span m="1613590">actually</span> <span m="1613850">has</span> <span m="1614030">tools.</span>
  <span m="1614460">We</span> <span m="1614650">didn''t really</span> <span m="1614820">go</span>
  <span m="1615180">into</span> <span m="1615440">them.</span> <span m="1615670">But</span>
  <span m="1615820">if</span> <span m="1615910">you</span> <span m="1616310">look</span>
  <span m="1617260">at</span> <span m="1617340">the</span> <span m="1617410">documentation,</span>
  <span m="1618780">we''re</span> <span m="1618950">allowing</span> <span m="1619350">you</span>
  <span m="1619510">to</span> <span m="1619640">do</span> <span m="1619840">splits.</span>
  <span m="1620650">The</span> <span m="1620790">databases</span> <span m="1621330">we''ve</span>
  <span m="1621590">given</span> <span m="1621840">you</span> <span m="1621950">access</span>
  <span m="1622430">to</span> <span m="1622590">are all</span> <span m="1622840">single</span>
  <span m="1623150">node</span> <span m="1623300">databases,</span> <span m="1624190">so</span>
  <span m="1624370">we''ve</span> <span m="1624480">made</span> <span m="1624650">your</span>
  <span m="1624740">life,</span> <span m="1624950">in a</span> <span m="1625320">certain</span>
  <span m="1625450">sense, a</span> <span m="1625510">little</span> <span m="1625670">bit</span>
  <span m="1625830">easier</span> <span m="1626630">that you</span> <span m="1626690">don''t
  have</span> <span m="1626970">to</span> <span m="1627060">worry</span> <span m="1627340">about</span>
  <span m="1627610">splits.</span> <span m="1628370">But</span> <span m="1628710">it</span>
  <span m="1628840">is</span> <span m="1628960">something--</span> <span m="1629460">as</span>
  <span m="1629590">you</span> <span m="1629710">work</span> <span m="1629970">on</span>
  <span m="1630110">larger</span> <span m="1630470">systems,</span> <span m="1630860">you</span>
  <span m="1630960">have</span> <span m="1631090">to</span> <span m="1631160">be</span>
  <span m="1631270">very</span> <span m="1631470">aware</span> <span m="1633060">of</span>
  <span m="1633110">the</span> <span m="1633420">splits.</span></p><p><span m="1637700">Another</span>
  <span m="1638010">thing</span> <span m="1638190">that''s</span> <span m="1638360">often</span>
  <span m="1638740">very</span> <span m="1639180">important</span> <span m="1640940">when</span>
  <span m="1641060">you''re</span> <span m="1641200">inserting</span> <span m="1642290">into</span>
  <span m="1642640">a</span> <span m="1642720">database</span> <span m="1643430">is</span>
  <span m="1643660">the</span> <span m="1645020">size</span> <span m="1645480">of
  the</span> <span m="1645620">chunks</span> <span m="1645950">of</span> <span m="1646070">data</span>
  <span m="1646480">you''re</span> <span m="1646610">handing</span> <span m="1647240">to</span>
  <span m="1647750">the</span> <span m="1647890">database.</span> <span m="1648380">This
  is</span> <span m="1648590">sometimes</span> <span m="1648870">called</span> <span
  m="1649090">the</span> <span m="1649150">block</span> <span m="1649520">size.</span>
  <span m="1650250">This is</span> <span m="1650340">a</span> <span m="1650400">very</span>
  <span m="1650900">important</span> <span m="1651310">parameter.</span> <span m="1651790">Blocking</span>
  <span m="1652410">of</span> <span m="1654820">programs</span> <span m="1655390">is</span>
  <span m="1655570">very</span> <span m="1655830">important.</span> <span m="1656820">Probably</span>
  <span m="1657050">the</span> <span m="1657160">key</span> <span m="1657470">thing</span>
  <span m="1657720">we</span> <span m="1657880">do</span> <span m="1658560">in</span>
  <span m="1658720">optimizing</span> <span m="1659840">any</span> <span m="1660120">program</span>
  <span m="1661000">is</span> <span m="1661440">coming</span> <span m="1661830">up,</span>
  <span m="1661980">finding</span> <span m="1662320">what</span> <span m="1662440">the</span>
  <span m="1662570">right</span> <span m="1662840">block</span> <span m="1663190">size</span>
  <span m="1663470">is</span> <span m="1663750">for a</span> <span m="1663960">system.</span>
  <span m="1664260">Because</span> <span m="1664420">it</span> <span m="1664500">almost</span>
  <span m="1664920">always</span> <span m="1665210">has</span> <span m="1665380">a</span>
  <span m="1665440">peak</span> <span m="1666130">around</span> <span m="1666500">some</span>
  <span m="1666770">number</span> <span m="1667110">here.</span></p><p><span m="1668020">And</span>
  <span m="1668200">so</span> <span m="1670230">this</span> <span m="1670540">just</span>
  <span m="1670780">shows</span> <span m="1671890">the</span> <span m="1672120">impact</span>
  <span m="1673260">of</span> <span m="1673430">block</span> <span m="1673930">size</span>
  <span m="1675280">on</span> <span m="1675670">the</span> <span m="1676340">performance</span>
  <span m="1676670">rate</span> <span m="1677040">here</span> <span m="1677850">for</span>
  <span m="1678490">Accumulo.</span> <span m="1679420">And</span> <span m="1679880">the</span>
  <span m="1679970">nice</span> <span m="1680190">about</span> <span m="1680370">D4M,</span>
  <span m="1680930">there''s</span> <span m="1681050">actually</span> <span m="1681330">a</span>
  <span m="1681400">parameter</span> <span m="1682060">you</span> <span m="1682160">can</span>
  <span m="1682310">set</span> <span m="1682710">for the</span> <span m="1682800">table</span>
  <span m="1683190">which</span> <span m="1683370">will</span> <span m="1683500">say</span>
  <span m="1684100">how</span> <span m="1684230">many</span> <span m="1684420">bytes</span>
  <span m="1685220">I</span> <span m="1685340">want</span> <span m="1685600">to</span>
  <span m="1685670">set.</span> <span m="1686040">I</span> <span m="1686150">think</span>
  <span m="1686370">the</span> <span m="1686450">default</span> <span m="1686880">is</span>
  <span m="1687130">500</span> <span m="1687650">kilobytes,</span> <span m="1688580">which</span>
  <span m="1688640">is</span> <span m="1688720">a</span> <span m="1688790">lot</span>
  <span m="1689070">smaller</span> <span m="1689510">than</span> <span m="1689690">I</span>
  <span m="1689710">would''ve</span> <span m="1689940">thought,</span> <span m="1690210">but</span>
  <span m="1690320">it''s</span> <span m="1690450">a</span> <span m="1690490">number</span>
  <span m="1690750">that</span> <span m="1690840">we</span> <span m="1690980">found</span>
  <span m="1691300">tends</span> <span m="1691580">to</span> <span m="1691690">be</span>
  <span m="1691880">fairly</span> <span m="1692340">optimal</span> <span m="1692830">across</span>
  <span m="1693170">a</span> <span m="1693240">wide</span> <span m="1693530">range</span>
  <span m="1693780">of</span> <span m="1693870">things.</span> <span m="1694460">Typically,</span>
  <span m="1694920">when</span> <span m="1695070">you</span> <span m="1695180">do</span>
  <span m="1695410">inserts</span> <span m="1695675">into</span> <span m="1695940">a</span>
  <span m="1696120">database,</span> <span m="1696540">you''re</span> <span m="1696650">like,</span>
  <span m="1696800">well,</span> <span m="1696880">I</span> <span m="1696920">want</span>
  <span m="1697040">to</span> <span m="1697080">give</span> <span m="1697200">you</span>
  <span m="1697260">the</span> <span m="1697360">biggest</span> <span m="1697680">chunk</span>
  <span m="1697900">that</span> <span m="1698010">I</span> <span m="1698060">can</span>
  <span m="1698670">and</span> <span m="1698840">move</span> <span m="1699050">on.</span>
  <span m="1699750">And</span> <span m="1699880">Accumulo</span> <span m="1700630">and</span>
  <span m="1700790">probably</span> <span m="1701100">a</span> <span m="1701140">lot</span>
  <span m="1701320">of</span> <span m="1701370">databases</span> <span m="1701790">actually</span>
  <span m="1702140">like</span> <span m="1702330">to</span> <span m="1702430">get</span>
  <span m="1702630">data</span> <span m="1702870">in</span> <span m="1703040">smaller</span>
  <span m="1703460">chunks</span> <span m="1704620">than</span> <span m="1704940">you</span>
  <span m="1705040">might</span> <span m="1705310">think.</span> <span m="1705910">Basically,</span>
  <span m="1706610">what''s</span> <span m="1706760">happening</span> <span m="1707250">then</span>
  <span m="1707560">is</span> <span m="1708560">if</span> <span m="1708630">you''re</span>
  <span m="1708720">giving</span> <span m="1709000">it</span> <span m="1709080">the</span>
  <span m="1709170">right</span> <span m="1709400">size</span> <span m="1709690">chunks,</span>
  <span m="1710120">then</span> <span m="1710490">it</span> <span m="1710550">all</span>
  <span m="1710730">fits</span> <span m="1710990">in</span> <span m="1711120">cache,</span>
  <span m="1711990">and</span> <span m="1712200">any</span> <span m="1712390">sorting</span>
  <span m="1712910">and</span> <span m="1713000">other</span> <span m="1713170">types</span>
  <span m="1713430">of</span> <span m="1713540">operations</span> <span m="1713950">it
  has</span> <span m="1714360">to do on</span> <span m="1714580">that</span> <span
  m="1714790">data</span> <span m="1715340">can</span> <span m="1715510">be</span>
  <span m="1715610">done</span> <span m="1715800">much</span> <span m="1716010">more</span>
  <span m="1716190">efficiently.</span></p><p><span m="1717240">So</span> <span m="1717310">this</span>
  <span m="1717510">just</span> <span m="1717720">shows</span> <span m="1717980">another</span>
  <span m="1718500">parameter</span> <span m="1719070">you</span> <span m="1719170">have</span>
  <span m="1719330">to</span> <span m="1719400">be</span> <span m="1719520">worried</span>
  <span m="1719850">about.</span> <span m="1720500">If</span> <span m="1720760">you</span>
  <span m="1720890">do</span> <span m="1721080">everything</span> <span m="1721670">right--</span>
  <span m="1721960">and</span> <span m="1722060">I</span> <span m="1722120">showed</span>
  <span m="1723100">these</span> <span m="1723320">results</span> <span m="1723710">before--</span>
  <span m="1724650">these</span> <span m="1724900">are</span> <span m="1724980">the
  kind</span> <span m="1725240">of</span> <span m="1725310">results</span> <span m="1725760">you
  can</span> <span m="1725920">get.</span> <span m="1726940">This</span> <span m="1727120">shows</span>
  <span m="1728090">essentially</span> <span m="1728480">on</span> <span m="1728620">an</span>
  <span m="1728800">8</span> <span m="1729070">node</span> <span m="1729740">system--</span>
  <span m="1730380">fairly</span> <span m="1730760">powerful,</span> <span m="1731350">24</span>
  <span m="1731770">cores</span> <span m="1732110">per</span> <span m="1733500">node</span>
  <span m="1734270">getting</span> <span m="1734640">the</span> <span m="1734820">4</span>
  <span m="1735090">million</span> <span m="1735520">inserts</span> <span m="1736190">or</span>
  <span m="1736320">entries</span> <span m="1736710">per</span> <span m="1736870">second</span>
  <span m="1737590">that</span> <span m="1737740">we</span> <span m="1737900">saw,</span>
  <span m="1738970">which</span> <span m="1739170">is,</span> <span m="1739510">to</span>
  <span m="1739670">our</span> <span m="1739780">knowledge,</span> <span m="1740260">again,</span>
  <span m="1740500">the</span> <span m="1740580">world</span> <span m="1740830">record</span>
  <span m="1741160">holder</span> <span m="1741460">for</span> <span m="1741610">this.</span></p><p><span
  m="1744710">That</span> <span m="1744930">talks</span> <span m="1745200">about</span>
  <span m="1745480">inserts.</span> <span m="1746380">Another</span> <span m="1746710">thing</span>
  <span m="1746920">that</span> <span m="1747030">we</span> <span m="1747170">also</span>
  <span m="1747550">want</span> <span m="1747910">to</span> <span m="1748080">look</span>
  <span m="1748330">at</span> <span m="1748550">is</span> <span m="1749260">queries.</span>
  <span m="1751290">So</span> <span m="1752800">as</span> <span m="1752970">I</span>
  <span m="1753060">said</span> <span m="1753660">before,</span> <span m="1754080">Accumulo</span>
  <span m="1754425">is</span> <span m="1754770">a</span> <span m="1754870">row-based</span>
  <span m="1755870">store,</span> <span m="1756900">which</span> <span m="1757000">means</span>
  <span m="1757170">if you</span> <span m="1757390">give</span> <span m="1757600">it</span>
  <span m="1757700">a</span> <span m="1757790">row</span> <span m="1758080">key,</span>
  <span m="1758830">it</span> <span m="1758950">will</span> <span m="1759120">return</span>
  <span m="1760200">the</span> <span m="1760300">result</span> <span m="1760770">in</span>
  <span m="1760900">constant</span> <span m="1761440">time.</span> <span m="1762320">And</span>
  <span m="1762530">so</span> <span m="1763450">that''s</span> <span m="1763720">true.</span>
  <span m="1764220">So</span> <span m="1764850">we''ve</span> <span m="1765180">done</span>
  <span m="1765380">a</span> <span m="1765420">bunch</span> <span m="1765640">of</span>
  <span m="1765710">queries</span> <span m="1766210">here,</span> <span m="1768110">lots</span>
  <span m="1768390">of</span> <span m="1768510">different</span> <span m="1768970">concurrent</span>
  <span m="1769470">processes</span> <span m="1770140">all</span> <span m="1770610">querying</span>
  <span m="1770820">at</span> <span m="1770940">the</span> <span m="1771020">same</span>
  <span m="1771390">time.</span> <span m="1772160">And</span> <span m="1772470">you</span>
  <span m="1772650">can</span> <span m="1772840">see</span> <span m="1773600">the</span>
  <span m="1774400">response</span> <span m="1774940">time</span> <span m="1775310">is</span>
  <span m="1775910">generally,</span> <span m="1777060">they</span> <span m="1777220">say,</span>
  <span m="1777600">around</span> <span m="1777850">50</span> <span m="1778170">milliseconds,</span>
  <span m="1779220">which</span> <span m="1779410">is</span> <span m="1779560">great.</span>
  <span m="1780130">And</span> <span m="1780200">this</span> <span m="1780340">is</span>
  <span m="1780460">the</span> <span m="1780560">full</span> <span m="1781020">round</span>
  <span m="1781340">trip</span> <span m="1781590">time.</span> <span m="1782070">A
  lot of</span> <span m="1782320">this</span> <span m="1782470">could</span> <span
  m="1782590">have</span> <span m="1782650">been</span> <span m="1782790">network</span>
  <span m="1783190">latency,</span> <span m="1783750">for</span> <span m="1783890">all</span>
  <span m="1784110">we know.</span> <span m="1784940">So</span> <span m="1785030">that''s</span>
  <span m="1785260">what</span> <span m="1785380">you</span> <span m="1785520">expect.</span>
  <span m="1785910">That''s</span> <span m="1786120">what</span> <span m="1786260">Accumulo</span>
  <span m="1786330">does.</span> <span m="1786860">If</span> <span m="1786960">you</span>
  <span m="1787170">do</span> <span m="1787310">row</span> <span m="1787670">queries,</span>
  <span m="1788610">then</span> <span m="1788750">you</span> <span m="1788820">get</span>
  <span m="1788990">constant</span> <span m="1789470">time.</span></p><p><span m="1790270">Now,</span>
  <span m="1790410">as</span> <span m="1790650">we''ve</span> <span m="1790790">talked</span>
  <span m="1791080">about</span> <span m="1791320">before,</span> <span m="1791710">we</span>
  <span m="1791880">do</span> <span m="1792030">our</span> <span m="1792190">special</span>
  <span m="1793010">exploded</span> <span m="1793620">transpose</span> <span m="1794320">schema,</span>
  <span m="1794690">which</span> <span m="1794860">essentially</span> <span m="1795290">give</span>
  <span m="1795510">this</span> <span m="1795730">performance</span> <span m="1796940">for</span>
  <span m="1797070">both</span> <span m="1797330">row</span> <span m="1797660">and</span>
  <span m="1797920">column</span> <span m="1798300">queries.</span> <span m="1798680">But</span>
  <span m="1798790">if</span> <span m="1798860">you</span> <span m="1798950">have</span>
  <span m="1799210">a</span> <span m="1799250">table</span> <span m="1799600">where</span>
  <span m="1799720">you</span> <span m="1799800">haven''t</span> <span m="1800060">done</span>
  <span m="1800260">that</span> <span m="1800590">and you</span> <span m="1800790">are</span>
  <span m="1801070">going</span> <span m="1801210">to</span> <span m="1801290">query</span>
  <span m="1801640">a</span> <span m="1801720">column,</span> <span m="1804060">it''s</span>
  <span m="1804270">a</span> <span m="1804350">complete</span> <span m="1804820">scan</span>
  <span m="1805190">of</span> <span m="1805260">the</span> <span m="1805350">table.</span>
  <span m="1806400">And</span> <span m="1806680">so</span> <span m="1807120">you</span>
  <span m="1807270">see</span> <span m="1807620">here--</span> <span m="1809090">when</span>
  <span m="1810550">you</span> <span m="1810690">want</span> <span m="1810970">to</span>
  <span m="1811070">do</span> <span m="1811250">a</span> <span m="1811330">column</span>
  <span m="1811730">query,</span> <span m="1812780">the</span> <span m="1812860">performance</span>
  <span m="1813400">is</span> <span m="1813520">just</span> <span m="1813730">going</span>
  <span m="1813850">to</span> <span m="1813900">go</span> <span m="1814520">up</span>
  <span m="1814730">and</span> <span m="1814830">up</span> <span m="1814970">and</span>
  <span m="1815100">up,</span> <span m="1816310">because</span> <span m="1816490">they''re</span>
  <span m="1816640">all</span> <span m="1816820">just</span> <span m="1816960">doing</span>
  <span m="1817180">more</span> <span m="1817380">and</span> <span m="1817440">more</span>
  <span m="1817640">scans,</span> <span m="1818460">and</span> <span m="1819010">the</span>
  <span m="1819370">system</span> <span m="1819760">can</span> <span m="1819880">only</span>
  <span m="1820070">scan</span> <span m="1820365">at a</span> <span m="1820660">certain</span>
  <span m="1821040">rate.</span> <span m="1821760">So</span> <span m="1822180">that''s,</span>
  <span m="1822400">again,</span> <span m="1823310">the</span> <span m="1823460">main</span>
  <span m="1823790">reason</span> <span m="1824230">why</span> <span m="1824510">we</span>
  <span m="1824680">do</span> <span m="1824820">these</span> <span m="1825000">special</span>
  <span m="1825380">schemas</span> <span m="1826110">is</span> <span m="1826270">to</span>
  <span m="1826380">avoid</span> <span m="1826710">this</span> <span m="1826860">performance</span>
  <span m="1827380">penalty.</span></p><p><span m="1830890">So</span> <span m="1831550">finally,</span>
  <span m="1832380">in</span> <span m="1832430">talking</span> <span m="1832950">about</span>
  <span m="1833280">performance,</span> <span m="1835050">let''s</span> <span m="1835270">talk</span>
  <span m="1835520">a</span> <span m="1835620">little</span> <span m="1835840">bit</span>
  <span m="1835940">about</span> <span m="1836380">D4M</span> <span m="1837470">performance</span>
  <span m="1838290">itself.</span> <span m="1840810">If</span> <span m="1841030">you</span>
  <span m="1841210">write</span> <span m="1841540">your</span> <span m="1841740">D4M</span>
  <span m="1843050">programs</span> <span m="1846190">optimally--</span> <span m="1847610">and</span>
  <span m="1847690">this</span> <span m="1847970">sometimes</span> <span m="1848410">takes</span>
  <span m="1848640">a</span> <span m="1848710">while</span> <span m="1848970">to</span>
  <span m="1849030">get</span> <span m="1849330">to,</span> <span m="1849600">because</span>
  <span m="1849870">usually you</span> <span m="1850300">don''t</span> <span m="1850630">quite</span>
  <span m="1850930">have</span> <span m="1851060">the--</span> <span m="1851320">or</span>
  <span m="1851560">I</span> <span m="1851670">should</span> <span m="1851870">say,</span>
  <span m="1852240">in</span> <span m="1852390">the</span> <span m="1852470">most</span>
  <span m="1852800">elegant</span> <span m="1853330">way</span> <span m="1853670">possible,</span>
  <span m="1855040">again,</span> <span m="1855510">this</span> <span m="1855700">sometimes</span>
  <span m="1856120">requires</span> <span m="1857300">some</span> <span m="1857570">understanding.</span>
  <span m="1858430">Most</span> <span m="1858950">applications</span> <span m="1859680">end</span>
  <span m="1860020">up</span> <span m="1860230">becoming</span> <span m="1861090">a</span>
  <span m="1861210">combination</span> <span m="1862950">of</span> <span m="1863180">matrix</span>
  <span m="1863670">multiplies</span> <span m="1864830">on</span> <span m="1865070">these</span>
  <span m="1865200">associative</span> <span m="1865800">arrays.</span></p><p><span
  m="1867120">Now,</span> <span m="1867240">it''s</span> <span m="1867370">usually</span>
  <span m="1867610">not</span> <span m="1867770">the</span> <span m="1867890">first</span>
  <span m="1868220">program</span> <span m="1868580">I</span> <span m="1868680">write,</span>
  <span m="1868940">but</span> <span m="1869080">usually,</span> <span m="1869560">it''s</span>
  <span m="1869680">the</span> <span m="1869790">last</span> <span m="1870200">one</span>
  <span m="1870420">I</span> <span m="1870510">write.</span> <span m="1871230">It</span>
  <span m="1871310">finally</span> <span m="1871760">dawns</span> <span m="1872210">on</span>
  <span m="1872410">me</span> <span m="1872720">how</span> <span m="1872920">to</span>
  <span m="1873020">do</span> <span m="1873140">the</span> <span m="1873250">entire</span>
  <span m="1874180">complicated</span> <span m="1874890">analytic</span> <span m="1875460">and</span>
  <span m="1875590">all</span> <span m="1875800">its</span> <span m="1875950">queries</span>
  <span m="1876640">as</span> <span m="1876800">a</span> <span m="1876880">series</span>
  <span m="1877710">of</span> <span m="1877860">special</span> <span m="1878290">sparse</span>
  <span m="1878620">matrix</span> <span m="1878980">multiplies,</span> <span m="1879980">which</span>
  <span m="1880220">then</span> <span m="1880440">allows</span> <span m="1880880">us</span>
  <span m="1881030">to</span> <span m="1881140">maximally</span> <span m="1882030">leverage</span>
  <span m="1882570">the</span> <span m="1882800">underlying</span> <span m="1883930">libraries</span>
  <span m="1884650">which</span> <span m="1884840">have</span> <span m="1884900">been</span>
  <span m="1885060">very</span> <span m="1885450">optimized</span> <span m="1886330">to</span>
  <span m="1886560">do--</span> <span m="1888970">it''s</span> <span m="1889140">basically</span>
  <span m="1889520">not</span> <span m="1889720">calling</span> <span m="1890120">any</span>
  <span m="1890280">of</span> <span m="1890330">my</span> <span m="1890510">code.</span>
  <span m="1890870">It''s</span> <span m="1890980">just</span> <span m="1891210">calling</span>
  <span m="1891500">the</span> <span m="1891670">MATLAB</span> <span m="1892010">sparse</span>
  <span m="1892350">matrix</span> <span m="1893070">multiply</span> <span m="1893660">routine,</span>
  <span m="1894190">which</span> <span m="1894390">is</span> <span m="1894550">further</span>
  <span m="1894900">calling</span> <span m="1895290">the</span> <span m="1895370">sparse</span>
  <span m="1895780">BLAS,</span> <span m="1896640">which</span> <span m="1896880">are</span>
  <span m="1897010">heavily</span> <span m="1897350">optimized</span> <span m="1897950">by</span>
  <span m="1898120">the</span> <span m="1898990">computing</span> <span m="1899410">vendors,</span>
  <span m="1900150">and</span> <span m="1900240">likewise</span> <span m="1900700">are
  calling</span> <span m="1901200">sort</span> <span m="1901490">routines.</span></p><p><span
  m="1902650">So</span> <span m="1904820">the</span> <span m="1904950">thing</span>
  <span m="1905170">you</span> <span m="1905260">have</span> <span m="1905380">to</span>
  <span m="1905490">understand,</span> <span m="1906260">though,</span> <span m="1906490">is</span>
  <span m="1906520">that</span> <span m="1906630">sparse</span> <span m="1907080">matrix</span>
  <span m="1907500">multiply</span> <span m="1908130">has</span> <span m="1908410">fundamental</span>
  <span m="1909290">hardware</span> <span m="1909910">limits</span> <span m="1911330">depending</span>
  <span m="1911780">on</span> <span m="1911850">the</span> <span m="1911940">kinds</span>
  <span m="1912240">of</span> <span m="1912310">multiplies</span> <span m="1912890">you''re</span>
  <span m="1913040">doing</span> <span m="1913360">here.</span> <span m="1914995">And</span>
  <span m="1915410">we</span> <span m="1915540">have</span> <span m="1915750">a</span>
  <span m="1915790">whole</span> <span m="1916370">program</span> <span m="1917500">that</span>
  <span m="1917610">basically</span> <span m="1918150">times</span> <span m="1918560">all</span>
  <span m="1918740">these</span> <span m="1918970">and</span> <span m="1919080">generates</span>
  <span m="1919610">them.</span> <span m="1919770">So if you ever</span> <span m="1920120">want</span>
  <span m="1920310">to</span> <span m="1920350">get</span> <span m="1920620">what</span>
  <span m="1920770">your</span> <span m="1920920">fundamental</span> <span m="1921440">limits</span>
  <span m="1921760">are,</span> <span m="1922640">we</span> <span m="1922770">have</span>
  <span m="1922920">a</span> <span m="1922970">set</span> <span m="1923130">of</span>
  <span m="1923210">programs</span> <span m="1923650">that</span> <span m="1923770">will</span>
  <span m="1923950">run</span> <span m="1924020">all</span> <span m="1924250">these</span>
  <span m="1924420">benchmarks</span> <span m="1925000">for</span> <span m="1925230">you</span>
  <span m="1925710">and</span> <span m="1925880">show</span> <span m="1926140">you</span>
  <span m="1926760">what</span> <span m="1926960">you</span> <span m="1927130">can</span>
  <span m="1927260">expect.</span></p><p><span m="1929310">And</span> <span m="1929450">this</span>
  <span m="1929590">shows</span> <span m="1929950">you,</span> <span m="1930050">basically,</span>
  <span m="1930770">the</span> <span m="1930890">fraction</span> <span m="1931680">of</span>
  <span m="1931830">the</span> <span m="1931940">theoretical</span> <span m="1932710">peak</span>
  <span m="1932970">performance</span> <span m="1933600">of</span> <span m="1933650">the</span>
  <span m="1933750">processor</span> <span m="1934850">as</span> <span m="1935040">a</span>
  <span m="1935110">function</span> <span m="1935600">of</span> <span m="1935700">the</span>
  <span m="1935820">total</span> <span m="1936680">memory</span> <span m="1938190">on</span>
  <span m="1938360">that</span> <span m="1938550">processor.</span> <span m="1938940">So</span>
  <span m="1939320">this</span> <span m="1939570">is</span> <span m="1939720">all</span>
  <span m="1939950">single</span> <span m="1940960">core,</span> <span m="1941570">single</span>
  <span m="1941950">processor</span> <span m="1942480">benchmarks.</span> <span m="1943870">So</span>
  <span m="1943970">as</span> <span m="1944130">you</span> <span m="1944230">can</span>
  <span m="1944380">see</span> <span m="1944670">here,</span> <span m="1944830">this</span>
  <span m="1945040">is</span> <span m="1945220">dense</span> <span m="1945520">matrix</span>
  <span m="1945920">multiply.</span> <span m="1948330">And</span> <span m="1948630">it''s</span>
  <span m="1949170">95%</span> <span m="1950480">efficient.</span></p><p><span m="1952750">If</span>
  <span m="1952910">I</span> <span m="1953320">was</span> <span m="1953550">to</span>
  <span m="1953670">build</span> <span m="1954190">a</span> <span m="1954300">piece</span>
  <span m="1954560">of</span> <span m="1954670">special</span> <span m="1955240">purpose</span>
  <span m="1955760">hardware</span> <span m="1957160">and a</span> <span m="1957440">memory</span>
  <span m="1957800">subsystem</span> <span m="1958920">for</span> <span m="1959030">doing</span>
  <span m="1959380">dense</span> <span m="1960050">matrix</span> <span m="1960710">multiply,</span>
  <span m="1961730">it</span> <span m="1961960">would</span> <span m="1962210">be</span>
  <span m="1962570">identical</span> <span m="1963360">to</span> <span m="1963450">the</span>
  <span m="1963550">computers</span> <span m="1964130">that</span> <span m="1964220">you</span>
  <span m="1964390">all</span> <span m="1964870">have.</span> <span m="1966340">Your</span>
  <span m="1966510">computers</span> <span m="1967210">have</span> <span m="1967380">been</span>
  <span m="1967620">absolutely</span> <span m="1968770">designed</span> <span m="1969420">to</span>
  <span m="1969520">do</span> <span m="1969950">dense</span> <span m="1970270">matrix</span>
  <span m="1970720">multiply.</span> <span m="1971850">And</span> <span m="1972820">for</span>
  <span m="1972940">good</span> <span m="1973110">or</span> <span m="1973170">bad,</span>
  <span m="1973770">that''s</span> <span m="1974030">just</span> <span m="1974210">the</span>
  <span m="1974340">way</span> <span m="1975590">it</span> <span m="1975750">is.</span>
  <span m="1975970">The</span> <span m="1976090">caching</span> <span m="1976610">structure,</span>
  <span m="1978100">the</span> <span m="1978660">matrix</span> <span m="1979010">multiply</span>
  <span m="1979500">units,</span> <span m="1979860">the</span> <span m="1979960">vectorization</span>
  <span m="1980710">units,</span> <span m="1981360">they''re</span> <span m="1981530">all</span>
  <span m="1982100">designed</span> <span m="1982830">to--</span> <span m="1983380">they''re</span>
  <span m="1983580">identical</span> <span m="1984210">to</span> <span m="1984400">a</span>
  <span m="1985110">custom</span> <span m="1985580">built</span> <span m="1986200">matrix</span>
  <span m="1986610">multiply</span> <span m="1986915">unit.</span> <span m="1987800">And</span>
  <span m="1988010">so</span> <span m="1988180">we</span> <span m="1988330">get</span>
  <span m="1988580">enormously</span> <span m="1989680">high</span> <span m="1989980">performance</span>
  <span m="1991070">here,</span> <span m="1991800">95%</span> <span m="1992780">peak</span>
  <span m="1993170">on</span> <span m="1993320">dense</span> <span m="1993580">matrix</span>
  <span m="1993940">multiply.</span></p><p><span m="1995110">Unfortunately,</span>
  <span m="1996100">that</span> <span m="1996310">hardware</span> <span m="1996790">architecture</span>
  <span m="1998500">and</span> <span m="1998700">everything</span> <span m="1999080">we</span>
  <span m="1999190">do</span> <span m="1999330">it</span> <span m="1999430">for</span>
  <span m="1999530">dense</span> <span m="1999790">matrix</span> <span m="2000120">multiply</span>
  <span m="2000640">is</span> <span m="2000860">the</span> <span m="2001060">opposite</span>
  <span m="2001760">of</span> <span m="2001940">what</span> <span m="2002100">we</span>
  <span m="2002230">would</span> <span m="2002400">do</span> <span m="2003200">if</span>
  <span m="2003400">we</span> <span m="2003540">built</span> <span m="2004320">a</span>
  <span m="2004450">computer</span> <span m="2005000">for</span> <span m="2005180">doing</span>
  <span m="2005510">sparse</span> <span m="2006070">matrix</span> <span m="2006470">multiply.</span>
  <span m="2007560">And</span> <span m="2007720">that''s</span> <span m="2007990">why</span>
  <span m="2008260">we</span> <span m="2008450">have,</span> <span m="2008850">when</span>
  <span m="2008950">we</span> <span m="2009080">go</span> <span m="2009250">from</span>
  <span m="2009400">dense</span> <span m="2009670">matrix</span> <span m="2010030">multiply</span>
  <span m="2010450">to</span> <span m="2010550">sparse</span> <span m="2010950">matrix</span>
  <span m="2011320">multiply,</span> <span m="2012350">this</span> <span m="2012630">1,000x</span>
  <span m="2013880">drop</span> <span m="2014270">in</span> <span m="2014660">performance.</span>
  <span m="2016700">And</span> <span m="2016970">this</span> <span m="2017580">is</span>
  <span m="2017750">not</span> <span m="2017980">getting</span> <span m="2018230">better</span>
  <span m="2018480">with</span> <span m="2018640">time.</span> <span m="2019490">This</span>
  <span m="2019720">is</span> <span m="2019880">getting</span> <span m="2021070">worse</span>
  <span m="2021390">with</span> <span m="2021560">time.</span></p><p><span m="2023370">And</span>
  <span m="2023620">there''s</span> <span m="2023770">nothing</span> <span m="2024060">you</span>
  <span m="2024190">can</span> <span m="2024290">do</span> <span m="2024410">about</span>
  <span m="2024650">it.</span> <span m="2024710">That</span> <span m="2024980">is</span>
  <span m="2025120">just</span> <span m="2025380">what</span> <span m="2025550">the</span>
  <span m="2025630">hardware</span> <span m="2026190">does.</span> <span m="2027010">Now,</span>
  <span m="2027150">it''s</span> <span m="2027350">still</span> <span m="2027810">better</span>
  <span m="2028160">to</span> <span m="2028280">do</span> <span m="2028450">sparse</span>
  <span m="2028790">matrix</span> <span m="2029120">multiply</span> <span m="2029470">than</span>
  <span m="2029820">to</span> <span m="2030040">convert it to</span> <span m="2030530">dense,</span>
  <span m="2031010">because</span> <span m="2031740">you''re</span> <span m="2031910">still</span>
  <span m="2032610">a</span> <span m="2032730">net</span> <span m="2033050">win</span>
  <span m="2033990">by</span> <span m="2034180">not</span> <span m="2035170">computing</span>
  <span m="2035680">all</span> <span m="2035770">those</span> <span m="2036000">zeros</span>
  <span m="2036810">that</span> <span m="2036940">you</span> <span m="2037070">would</span>
  <span m="2037170">have</span> <span m="2037450">in</span> <span m="2037540">a</span>
  <span m="2037580">very</span> <span m="2037820">sparse</span> <span m="2038200">matrix.</span>
  <span m="2038670">So</span> <span m="2039130">it''s</span> <span m="2039300">still</span>
  <span m="2039740">a</span> <span m="2039810">significant</span> <span m="2040540">win</span>
  <span m="2041090">in</span> <span m="2042130">execution</span> <span m="2042770">time</span>
  <span m="2043130">to</span> <span m="2043420">do</span> <span m="2043500">your</span>
  <span m="2043710">calculation</span> <span m="2044860">on</span> <span m="2045030">sparse</span>
  <span m="2045380">matrices</span> <span m="2046020">if they</span> <span m="2046270">are</span>
  <span m="2046540">sparse,</span> <span m="2048199">but</span> <span m="2048480">not</span>
  <span m="2048699">otherwise.</span></p><p><span m="2050150">And</span> <span m="2050570">then--</span>
  <span m="2054159">so</span> <span m="2054300">that''s</span> <span m="2054600">that.</span>
  <span m="2055719">This</span> <span m="2055969">shows</span> <span m="2059040">the</span>
  <span m="2060750">associative</span> <span m="2061370">array.</span> <span m="2062210">So</span>
  <span m="2063449">the</span> <span m="2064170">top</span> <span m="2064530">one</span>
  <span m="2064719">is</span> <span m="2064860">MATLAB</span> <span m="2065460">dense,</span>
  <span m="2066139">MATLAB</span> <span m="2066870">sparse,</span> <span m="2067580">D4M</span>
  <span m="2068500">associative</span> <span m="2069139">array.</span> <span m="2069370">And</span>
  <span m="2069489">we</span> <span m="2069600">worked</span> <span m="2069969">very</span>
  <span m="2070330">hard</span> <span m="2071239">to</span> <span m="2071429">make</span>
  <span m="2073219">the</span> <span m="2073330">D4M</span> <span m="2073909">associative</span>
  <span m="2074560">array</span> <span m="2075170">be</span> <span m="2075280">a</span>
  <span m="2075350">constant</span> <span m="2077170">factor</span> <span m="2077659">below</span>
  <span m="2078110">the</span> <span m="2078230">core</span> <span m="2078540">sparse.</span>
  <span m="2078900">So</span> <span m="2079050">you''re</span> <span m="2079260">really</span>
  <span m="2079900">getting</span> <span m="2080230">performance</span> <span m="2080830">that''s</span>
  <span m="2081060">pretty</span> <span m="2081280">darn</span> <span m="2081560">close</span>
  <span m="2081870">to</span> <span m="2081969">that.</span> <span m="2082610">And</span>
  <span m="2083070">so</span> <span m="2085050">generally,</span> <span m="2085489">doing</span>
  <span m="2085739">sparse</span> <span m="2086050">matrix</span> <span m="2086370">multiplies</span>
  <span m="2086920">on</span> <span m="2087040">the</span> <span m="2087120">associative</span>
  <span m="2087600">arrays</span> <span m="2087889">works</span> <span m="2088150">out</span>
  <span m="2088300">pretty</span> <span m="2088469">well.</span> <span m="2090760">But</span>
  <span m="2090780">again,</span> <span m="2091130">there</span> <span m="2091260">is</span>
  <span m="2091389">still</span> <span m="2091780">about</span> <span m="2092050">21%</span>
  <span m="2092929">efficient</span> <span m="2093389">of</span> <span m="2093460">the</span>
  <span m="2093550">hardware.</span></p><p><span m="2093940">And</span> <span m="2094090">then</span>
  <span m="2094179">the</span> <span m="2094380">final</span> <span m="2094850">thing</span>
  <span m="2095870">is</span> <span m="2096350">we</span> <span m="2096469">have</span>
  <span m="2096550">these</span> <span m="2096889">special</span> <span m="2097600">sparse</span>
  <span m="2097990">matrix</span> <span m="2098350">multiplies</span> <span m="2098900">where</span>
  <span m="2099050">we</span> <span m="2099200">concatenate</span> <span m="2100020">the</span>
  <span m="2100140">keys</span> <span m="2100560">together.</span> <span m="2101290">If</span>
  <span m="2101330">you</span> <span m="2101440">remember</span> <span m="2101780">way</span>
  <span m="2102010">back</span> <span m="2102360">when</span> <span m="2102500">we</span>
  <span m="2102580">did</span> <span m="2102720">the</span> <span m="2102800">bioinformatics</span>
  <span m="2104170">example,</span> <span m="2105150">we</span> <span m="2105300">could</span>
  <span m="2105420">do</span> <span m="2105530">special</span> <span m="2106350">matrix</span>
  <span m="2106830">multiplies</span> <span m="2107900">that</span> <span m="2108650">essentially</span>
  <span m="2109390">preserved</span> <span m="2110290">where</span> <span m="2110690">the</span>
  <span m="2110820">data</span> <span m="2111440">came</span> <span m="2111700">from.</span>
  <span m="2112010">If we</span> <span m="2112120">correlated</span> <span m="2112650">two</span>
  <span m="2112810">DNA</span> <span m="2113210">sequences,</span> <span m="2115290">we</span>
  <span m="2115550">would</span> <span m="2115970">have</span> <span m="2116160">a</span>
  <span m="2117480">matrix</span> <span m="2118230">that</span> <span m="2118340">would</span>
  <span m="2118450">show</span> <span m="2119080">the</span> <span m="2119250">IDs</span>
  <span m="2119730">of</span> <span m="2119800">the</span> <span m="2119900">DNA</span>
  <span m="2120310">sequence.</span> <span m="2121330">And</span> <span m="2121350">if</span>
  <span m="2121430">we</span> <span m="2121530">did</span> <span m="2121770">these</span>
  <span m="2121930">special</span> <span m="2122280">matrix</span> <span m="2122620">multiplies,</span>
  <span m="2123460">the</span> <span m="2123560">values</span> <span m="2124320">would</span>
  <span m="2124660">then</span> <span m="2124700">hold</span> <span m="2125020">the</span>
  <span m="2125160">exact</span> <span m="2126370">DNA</span> <span m="2126730">sequences</span>
  <span m="2127330">themselves</span> <span m="2128320">that</span> <span m="2128700">were</span>
  <span m="2128870">the</span> <span m="2128990">matches.</span></p><p><span m="2130030">Well,</span>
  <span m="2130200">there''s</span> <span m="2130370">a</span> <span m="2130460">performance</span>
  <span m="2131040">hit</span> <span m="2131190">that</span> <span m="2131320">comes</span>
  <span m="2131640">with</span> <span m="2131915">holding</span> <span m="2132190">that</span>
  <span m="2132390">additional</span> <span m="2132790">information,</span> <span
  m="2133750">all</span> <span m="2133920">of</span> <span m="2134270">this</span>
  <span m="2134360">string</span> <span m="2134820">information.</span> <span m="2135370">It</span>
  <span m="2135450">may  be</span> <span m="2135680">one</span> <span m="2135980">day</span>
  <span m="2136690">we''ll</span> <span m="2136810">be</span> <span m="2136910">able</span>
  <span m="2137020">to</span> <span m="2137100">optimize</span> <span m="2137700">this</span>
  <span m="2137920">further,</span> <span m="2138330">although</span> <span m="2138540">we''ve</span>
  <span m="2138720">actually</span> <span m="2139090">optimized</span> <span m="2139580">it</span>
  <span m="2139680">a</span> <span m="2139730">fair</span> <span m="2139970">bit</span>
  <span m="2140120">already.</span> <span m="2140760">And</span> <span m="2140910">so</span>
  <span m="2140990">there''s</span> <span m="2141180">another</span> <span m="2141680">factor</span>
  <span m="2142200">of</span> <span m="2142250">100.</span> <span m="2143030">And</span>
  <span m="2143170">it</span> <span m="2143250">looks</span> <span m="2143520">like</span>
  <span m="2143710">this</span> <span m="2143900">is</span> <span m="2144060">just,</span>
  <span m="2144610">again,</span> <span m="2145600">fundamentally</span> <span m="2146280">limited</span>
  <span m="2146680">by</span> <span m="2147670">the</span> <span m="2148120">speed</span>
  <span m="2148630">at</span> <span m="2148730">which</span> <span m="2149480">the</span>
  <span m="2149590">hardware</span> <span m="2149980">will</span> <span m="2150100">do</span>
  <span m="2150200">sparse</span> <span m="2150510">matrix</span> <span m="2150840">multiply</span>
  <span m="2151790">and</span> <span m="2151960">the</span> <span m="2152030">speed</span>
  <span m="2152860">at</span> <span m="2153040">which</span> <span m="2153440">it</span>
  <span m="2153550">can</span> <span m="2153700">do</span> <span m="2153840">string</span>
  <span m="2154750">sorting.</span> <span m="2155940">That''s</span> <span m="2156260">essentially</span>
  <span m="2156780">the</span> <span m="2156920">two</span> <span m="2157180">routines</span>
  <span m="2158100">that</span> <span m="2158780">all</span> <span m="2159280">these</span>
  <span m="2159490">functions</span> <span m="2159870">boil</span> <span m="2160170">down</span>
  <span m="2160460">to,</span> <span m="2160630">is</span> <span m="2160720">sparse</span>
  <span m="2161070">matrix</span> <span m="2161410">multiply</span> <span m="2161670">and</span>
  <span m="2161930">string</span> <span m="2162550">storing.</span> <span m="2163220">And</span>
  <span m="2163430">those</span> <span m="2163640">are</span> <span m="2163810">essentially</span>
  <span m="2164260">hardware</span> <span m="2164680">limited.</span> <span m="2165280">Those</span>
  <span m="2165460">are</span> <span m="2165540">very</span> <span m="2165820">optimized</span>
  <span m="2166420">functions.</span></p><p><span m="2168070">So</span> <span m="2169380">this</span>
  <span m="2169610">just</span> <span m="2169750">gives</span> <span m="2169940">you</span>
  <span m="2170070">a</span> <span m="2170200">way.</span> <span m="2170860">I</span>
  <span m="2171000">think</span> <span m="2171140">it''s</span> <span m="2171280">always--</span>
  <span m="2172020">the</span> <span m="2172210">first</span> <span m="2172510">thing</span>
  <span m="2172720">we</span> <span m="2172940">do</span> <span m="2173240">when</span>
  <span m="2173430">we</span> <span m="2173740">run</span> <span m="2173930">a</span>
  <span m="2173980">program</span> <span m="2174790">is</span> <span m="2177244">if</span>
  <span m="2178130">we</span> <span m="2178200">want</span> <span m="2178420">to</span>
  <span m="2178470">optimize</span> <span m="2178823">it,</span> <span m="2180130">we''ll</span>
  <span m="2180780">write</span> <span m="2181120">the</span> <span m="2181210">program</span>
  <span m="2181660">and</span> <span m="2181760">run it,</span> <span m="2182010">get</span>
  <span m="2182180">a</span> <span m="2182250">time,</span> <span m="2183230">and</span>
  <span m="2183390">then</span> <span m="2183490">we''ll</span> <span m="2183640">try</span>
  <span m="2183910">and</span> <span m="2184080">figure</span> <span m="2184470">out</span>
  <span m="2185520">based</span> <span m="2185840">on</span> <span m="2185980">this</span>
  <span m="2186160">type</span> <span m="2186390">of</span> <span m="2186510">data,</span>
  <span m="2187070">well,</span> <span m="2187410">what''s the</span> <span m="2187510">theoretical</span>
  <span m="2188080">best</span> <span m="2188380">we</span> <span m="2188500">could</span>
  <span m="2188690">do?</span> <span m="2190500">Given</span> <span m="2191330">what</span>
  <span m="2191530">this</span> <span m="2191930">calculation</span> <span m="2192520">is</span>
  <span m="2192680">dominated</span> <span m="2193130">by,</span> <span m="2193740">what</span>
  <span m="2193980">is</span> <span m="2194210">the</span> <span m="2194300">best</span>
  <span m="2194600">we</span> <span m="2194730">can</span> <span m="2194880">do?</span></p><p><span
  m="2196080">Because</span> <span m="2197110">if</span> <span m="2197260">the</span>
  <span m="2197360">best</span> <span m="2197660">we</span> <span m="2197790">could</span>
  <span m="2197960">do--</span> <span m="2198890">the</span> <span m="2199010">theoretical</span>
  <span m="2200170">peak</span> <span m="2202070">for</span> <span m="2202220">what</span>
  <span m="2202410">we</span> <span m="2202540">were</span> <span m="2202660">doing</span>
  <span m="2203130">was</span> <span m="2204620">1,000</span> <span m="2205320">times</span>
  <span m="2205700">better</span> <span m="2206050">than</span> <span m="2206210">what</span>
  <span m="2206390">we''re</span> <span m="2206510">doing,</span> <span m="2207080">that</span>
  <span m="2207330">tells</span> <span m="2207690">us, you</span> <span m="2207830">know</span>
  <span m="2207950">what?</span> <span m="2209400">If</span> <span m="2209560">we</span>
  <span m="2209680">have</span> <span m="2209790">to</span> <span m="2209860">invest</span>
  <span m="2210280">time</span> <span m="2210530">in</span> <span m="2210770">optimization,</span>
  <span m="2211530">it</span> <span m="2211710">probably</span> <span m="2212090">is</span>
  <span m="2212250">time</span> <span m="2212550">well</span> <span m="2212730">spent.</span>
  <span m="2214040">Going</span> <span m="2214420">from</span> <span m="2214830">being</span>
  <span m="2215120">1,000x</span> <span m="2215990">below</span> <span m="2216960">whatever</span>
  <span m="2217270">the</span> <span m="2217380">best</span> <span m="2217670">you</span>
  <span m="2217820">can</span> <span m="2217960">do</span> <span m="2218580">getting</span>
  <span m="2218820">to</span> <span m="2218940">100x</span> <span m="2220180">usually</span>
  <span m="2220580">doesn''t</span> <span m="2220890">take</span> <span m="2221110">too</span>
  <span m="2221220">much</span> <span m="2221460">trouble.</span> <span m="2221540">Usually,</span>
  <span m="2221630">you</span> <span m="2221980">can</span> <span m="2222150">find</span>
  <span m="2222630">what</span> <span m="2222760">that</span> <span m="2222970">issue</span>
  <span m="2223340">is</span> <span m="2223500">and you</span> <span m="2223690">can</span>
  <span m="2223790">correct</span> <span m="2224290">it.</span></p><p><span m="2226030">Likewise,</span>
  <span m="2227730">going</span> <span m="2228060">from</span> <span m="2228540">100x</span>
  <span m="2229450">to</span> <span m="2229890">10x</span> <span m="2231200">is</span>
  <span m="2231500">still</span> <span m="2232740">usually</span> <span m="2233240">a</span>
  <span m="2233330">worthwhile</span> <span m="2233970">thing</span> <span m="2234170">to</span>
  <span m="2234230">do.</span> <span m="2236075">If</span> <span m="2236470">you''re</span>
  <span m="2236790">at</span> <span m="2237610">10%</span> <span m="2238540">of</span>
  <span m="2238650">the</span> <span m="2238740">best</span> <span m="2239020">that</span>
  <span m="2239150">you</span> <span m="2239320">can</span> <span m="2239500">do,</span>
  <span m="2240540">then</span> <span m="2240830">you</span> <span m="2240930">begin</span>
  <span m="2241260">to</span> <span m="2241590">think</span> <span m="2241850">hard</span>
  <span m="2242210">about,</span> <span m="2242360">well,</span> <span m="2242510">do</span>
  <span m="2242620">I</span> <span m="2242710">really</span> <span m="2243280">want</span>
  <span m="2243530">to</span> <span m="2243620">chase?</span> <span m="2244940">I''m</span>
  <span m="2245060">never</span> <span m="2245300">going</span> <span m="2245400">to</span>
  <span m="2245480">probably</span> <span m="2245750">do</span> <span m="2245950">better</span>
  <span m="2246200">than</span> <span m="2246360">50%</span> <span m="2247430">of</span>
  <span m="2247560">what</span> <span m="2247740">the</span> <span m="2247830">best</span>
  <span m="2248130">is,</span> <span m="2248650">or</span> <span m="2248870">maybe</span>
  <span m="2249150">even</span> <span m="2249380">30%</span> <span m="2249710">or</span>
  <span m="2249770">40%.</span> <span m="2250280">Usually,</span> <span m="2250800">there''s</span>
  <span m="2250990">a</span> <span m="2251070">lot</span> <span m="2251930">of</span>
  <span m="2252050">effort</span> <span m="2253000">that</span> <span m="2253180">goes</span>
  <span m="2253650">into</span> <span m="2254140">going</span> <span m="2254550">from</span>
  <span m="2255390">10%</span> <span m="2256150">of</span> <span m="2256630">peak</span>
  <span m="2256920">performance</span> <span m="2257590">to</span> <span m="2258000">50%</span>
  <span m="2258610">of</span> <span m="2258850">performance.</span> <span m="2259470">But</span>
  <span m="2259820">going</span> <span m="2260040">from</span> <span m="2260220">0.1%</span>
  <span m="2261050">of</span> <span m="2261140">peak</span> <span m="2261320">performance</span>
  <span m="2261890">to</span> <span m="2262070">1%</span> <span m="2262740">of</span>
  <span m="2262820">peak</span> <span m="2263000">performance</span> <span m="2263530">is</span>
  <span m="2263660">usually</span> <span m="2264980">profile</span> <span m="2265290">the</span>
  <span m="2265380">code,</span> <span m="2265900">aha,</span> <span m="2266550">I''m</span>
  <span m="2266640">doing</span> <span m="2266840">something</span> <span m="2267160">wrong</span>
  <span m="2267500">here,</span> <span m="2267740">fix</span> <span m="2268090">it,</span>
  <span m="2269520">done.</span></p><p><span m="2270010">And</span> <span m="2270200">so</span>
  <span m="2270860">this</span> <span m="2271050">is</span> <span m="2271170">something</span>
  <span m="2271500">that''s</span> <span m="2271670">a</span> <span m="2271750">part</span>
  <span m="2272000">of</span> <span m="2272090">our</span> <span m="2272270">philosophy</span>
  <span m="2273000">in</span> <span m="2273120">doing</span> <span m="2273410">optimization,</span>
  <span m="2274410">and</span> <span m="2274550">why</span> <span m="2274870">we</span>
  <span m="2275040">spend</span> <span m="2275390">so</span> <span m="2275510">much</span>
  <span m="2275700">time</span> <span m="2275970">running</span> <span m="2276260">benchmarks</span>
  <span m="2276625">and</span> <span m="2277300">understanding</span> <span m="2277940">where--</span>
  <span m="2278910">because</span> <span m="2279050">it</span> <span m="2279270">tells</span>
  <span m="2279600">us</span> <span m="2279780">when</span> <span m="2280110">to</span>
  <span m="2280260">stop.</span> <span m="2281125">If</span> <span m="2281510">someone</span>
  <span m="2281780">says,</span> <span m="2282260">well,</span> <span m="2282460">will</span>
  <span m="2282650">this</span> <span m="2282800">be</span> <span m="2282960">faster,</span>
  <span m="2283390">and you</span> <span m="2283490">can</span> <span m="2283600">say</span>
  <span m="2283700">no,</span> <span m="2283960">it</span> <span m="2284010">won''t</span>
  <span m="2284210">be</span> <span m="2284360">faster,</span> <span m="2284890">you''re</span>
  <span m="2285150">done.</span> <span m="2285800">Or,</span> <span m="2286640">ah,</span>
  <span m="2286850">no,</span> <span m="2287160">we</span> <span m="2287600">think</span>
  <span m="2287860">in</span> <span m="2287970">a</span> <span m="2288020">few</span>
  <span m="2288230">weeks''</span> <span m="2288530">time,</span> <span m="2289730">we</span>
  <span m="2290110">can</span> <span m="2290250">really</span> <span m="2290480">make</span>
  <span m="2290720">it</span> <span m="2290840">a</span> <span m="2290910">lot</span>
  <span m="2291160">better.</span> <span m="2291760">So</span> <span m="2291910">very</span>
  <span m="2292250">useful</span> <span m="2292600">thing,</span> <span m="2292810">and</span>
  <span m="2292870">that''s</span> <span m="2293090">why</span> <span m="2293290">benchmarking</span>
  <span m="2293970">is</span> <span m="2294060">a</span> <span m="2294110">big</span>
  <span m="2294320">part</span> <span m="2294620">of</span> <span m="2294710">what</span>
  <span m="2294870">we</span> <span m="2295000">do.</span></p><p><span m="2296910">So</span>
  <span m="2297300">finally,</span> <span m="2297790">I</span> <span m="2297860">want</span>
  <span m="2298010">to</span> <span m="2298090">wrap</span> <span m="2298400">up</span>
  <span m="2298610">here.</span> <span m="2300060">This</span> <span m="2300300">was</span>
  <span m="2300440">one</span> <span m="2300600">of</span> <span m="2300660">the</span>
  <span m="2300750">first</span> <span m="2301220">charts</span> <span m="2301740">I</span>
  <span m="2301920">showed</span> <span m="2302380">you,</span> <span m="2302530">and</span>
  <span m="2302600">hopefully</span> <span m="2303000">now</span> <span m="2303190">it</span>
  <span m="2303270">makes</span> <span m="2303510">a</span> <span m="2303620">lot</span>
  <span m="2304080">more</span> <span m="2304380">sense.</span> <span m="2305780">This</span>
  <span m="2305980">shows</span> <span m="2306570">you</span> <span m="2306840">the</span>
  <span m="2307130">easy</span> <span m="2307790">path</span> <span m="2308260">toward</span>
  <span m="2308900">solving</span> <span m="2309460">your</span> <span m="2309610">problems</span>
  <span m="2310660">in</span> <span m="2310870">signal</span> <span m="2311250">processing</span>
  <span m="2311680">on</span> <span m="2312110">databases.</span> <span m="2313800">And</span>
  <span m="2313900">if</span> <span m="2313960">you</span> <span m="2314090">look</span>
  <span m="2314270">at</span> <span m="2314360">your</span> <span m="2314570">problem</span>
  <span m="2315090">as</span> <span m="2315280">one</span> <span m="2315550">of</span>
  <span m="2316570">how</span> <span m="2316710">much</span> <span m="2317000">data</span>
  <span m="2317290">I</span> <span m="2317430">want</span> <span m="2317680">to</span>
  <span m="2317770">process</span> <span m="2319070">and</span> <span m="2319400">how</span>
  <span m="2319680">much--</span> <span m="2320540">what</span> <span m="2320690">the</span>
  <span m="2320780">granularity</span> <span m="2321620">of</span> <span m="2321710">access</span>
  <span m="2322420">is,</span> <span m="2323390">well,</span> <span m="2323940">if</span>
  <span m="2324350">I</span> <span m="2324440">don''t</span> <span m="2324650">have</span>
  <span m="2324790">a</span> <span m="2324830">lot</span> <span m="2325110">of</span>
  <span m="2325180">data</span> <span m="2326080">and</span> <span m="2326280">I''m</span>
  <span m="2326380">accessing</span> <span m="2326740">it at</span> <span m="2327100">a</span>
  <span m="2327310">very</span> <span m="2327930">small</span> <span m="2328490">granularity,</span>
  <span m="2329880">well,</span> <span m="2329990">then</span> <span m="2330110">I</span>
  <span m="2330190">should</span> <span m="2330410">just</span> <span m="2331330">do</span>
  <span m="2331610">it</span> <span m="2332540">in</span> <span m="2332730">the</span>
  <span m="2332820">memory</span> <span m="2333660">of</span> <span m="2334240">my</span>
  <span m="2334370">computer.</span> <span m="2335470">Don''t</span> <span m="2335760">mess</span>
  <span m="2336010">around</span> <span m="2336320">with</span> <span m="2336480">files.</span>
  <span m="2336980">Don''t</span> <span m="2337200">mess</span> <span m="2337410">around</span>
  <span m="2337700">with</span> <span m="2337830">databases.</span> <span m="2338870">Keep</span>
  <span m="2339150">your</span> <span m="2339270">life</span> <span m="2339500">simple.</span>
  <span m="2340570">Work</span> <span m="2340830">it</span> <span m="2340980">there.</span></p><p><span
  m="2343720">If</span> <span m="2343860">the data</span> <span m="2344160">request</span>
  <span m="2344660">gets</span> <span m="2345050">high,</span> <span m="2345750">memory</span>
  <span m="2346200">is still</span> <span m="2346455">the</span> <span m="2346710">best.</span>
  <span m="2347540">Whether</span> <span m="2347700">you''re</span> <span m="2347870">doing</span>
  <span m="2348140">little</span> <span m="2348380">bits</span> <span m="2348620">or</span>
  <span m="2348930">big</span> <span m="2349130">bits,</span> <span m="2349370">working</span>
  <span m="2349800">out</span> <span m="2349920">of</span> <span m="2350010">main</span>
  <span m="2350290">memory</span> <span m="2350640">on</span> <span m="2350740">a</span>
  <span m="2350800">single</span> <span m="2351120">processor,</span> <span m="2351730">generally,</span>
  <span m="2352100">for</span> <span m="2352180">the</span> <span m="2352250">most</span>
  <span m="2352620">part,</span> <span m="2353230">is</span> <span m="2353390">where</span>
  <span m="2353610">you</span> <span m="2353720">want</span> <span m="2353960">to</span>
  <span m="2354010">be.</span> <span m="2356110">If</span> <span m="2356380">you''re</span>
  <span m="2356630">going</span> <span m="2356800">to</span> <span m="2356870">be</span>
  <span m="2358760">getting</span> <span m="2359180">to</span> <span m="2359200">larger</span>
  <span m="2360240">amounts</span> <span m="2360470">of</span> <span m="2360590">data</span>
  <span m="2361030">but</span> <span m="2361320">having</span> <span m="2361670">a</span>
  <span m="2361950">fairly</span> <span m="2362260">large</span> <span m="2362800">request</span>
  <span m="2363300">size,</span> <span m="2364190">then</span> <span m="2364370">using</span>
  <span m="2364750">files,</span> <span m="2366200">reading</span> <span m="2366490">those</span>
  <span m="2366740">files</span> <span m="2367210">in and</span> <span m="2367490">out--</span>
  <span m="2368310">so</span> <span m="2368470">basically,</span> <span m="2369220">if</span>
  <span m="2369510">I</span> <span m="2369640">have</span> <span m="2369820">a</span>
  <span m="2369930">lot</span> <span m="2370170">of</span> <span m="2370220">data</span>
  <span m="2370500">I want</span> <span m="2370610">to</span> <span m="2370700">process,</span>
  <span m="2371180">it</span> <span m="2371290">won''t</span> <span m="2371560">fit</span>
  <span m="2371690">into</span> <span m="2371900">serial</span> <span m="2372290">memory,</span>
  <span m="2373000">we''ll</span> <span m="2373190">write</span> <span m="2373470">it
  out</span> <span m="2373700">into a</span> <span m="2373760">bunch</span> <span
  m="2374010">of</span> <span m="2374110">files,</span> <span m="2374800">just</span>
  <span m="2374990">read</span> <span m="2375270">them</span> <span m="2375410">in,</span>
  <span m="2375710">process</span> <span m="2376210">them,</span> <span m="2376400">move</span>
  <span m="2376650">onto</span> <span m="2376940">the</span> <span m="2377040">next</span>
  <span m="2377360">file</span> <span m="2378140">is</span> <span m="2378440">the</span>
  <span m="2378550">right</span> <span m="2378810">thing</span> <span m="2379030">to</span>
  <span m="2379100">do.</span> <span m="2380100">Or</span> <span m="2381080">spread</span>
  <span m="2381390">it</span> <span m="2381470">out</span> <span m="2381700">in</span>
  <span m="2381800">parallel.</span> <span m="2382710">Run</span> <span m="2382940">a</span>
  <span m="2382980">bunch</span> <span m="2383270">of</span> <span m="2383320">nodes</span>
  <span m="2383730">and</span> <span m="2383830">use</span> <span m="2384040">the</span>
  <span m="2384170">RAM</span> <span m="2384540">in</span> <span m="2384610">each</span>
  <span m="2384770">one</span> <span m="2384950">of</span> <span m="2384990">those.</span>
  <span m="2385200">That''s</span> <span m="2385450">still</span> <span m="2385690">the</span>
  <span m="2385750">best</span> <span m="2386000">way</span> <span m="2386120">to</span>
  <span m="2386220">do</span> <span m="2386380">it.</span></p><p><span m="2390310">You</span>
  <span m="2390440">could</span> <span m="2390560">also</span> <span m="2390840">do</span>
  <span m="2391020">that</span> <span m="2391260">in</span> <span m="2391370">parallel.</span>
  <span m="2391880">You can have</span> <span m="2392310">parallel</span> <span m="2392780">programs</span>
  <span m="2393340">reading</span> <span m="2394630">parallel</span> <span m="2395060">files,</span>
  <span m="2395550">too.</span> <span m="2395800">So</span> <span m="2395980">if you
  have</span> <span m="2396180">really</span> <span m="2396590">enormous</span> <span
  m="2396940">amounts</span> <span m="2397250">of</span> <span m="2397320">data</span>
  <span m="2398020">and</span> <span m="2398200">you''re</span> <span m="2398330">going</span>
  <span m="2398460">to</span> <span m="2398520">be</span> <span m="2398690">reading</span>
  <span m="2399050">the</span> <span m="2399160">data</span> <span m="2399790">in</span>
  <span m="2399950">large</span> <span m="2400910">chunks,</span> <span m="2402500">then</span>
  <span m="2402670">you</span> <span m="2402810">want</span> <span m="2403050">to</span>
  <span m="2403090">use</span> <span m="2403760">parallel</span> <span m="2404150">files,</span>
  <span m="2405210">parallel</span> <span m="2405580">computing.</span> <span m="2406520">That''s</span>
  <span m="2406800">going</span> <span m="2406910">to</span> <span m="2406970">give</span>
  <span m="2407140">you</span> <span m="2407270">better</span> <span m="2407550">performance.</span>
  <span m="2408520">And</span> <span m="2408720">it''s</span> <span m="2408880">just</span>
  <span m="2409050">going</span> <span m="2409150">to</span> <span m="2409190">be</span>
  <span m="2409330">easy.</span> <span m="2410550">Have</span> <span m="2410970">a
  lot</span> <span m="2411080">of</span> <span m="2411370">files.</span> <span m="2411920">Each</span>
  <span m="2412480">program</span> <span m="2413060">reads</span> <span m="2413430">into</span>
  <span m="2413560">sets</span> <span m="2413680">of</span> <span m="2413780">files,</span>
  <span m="2414220">processes</span> <span m="2414720">its</span> <span m="2414920">set.</span>
  <span m="2415610">Very</span> <span m="2416070">easy</span> <span m="2416360">to</span>
  <span m="2416400">do.</span> <span m="2416720">And we</span> <span m="2416840">have</span>
  <span m="2416970">lots</span> <span m="2417330">of</span> <span m="2417420">support</span>
  <span m="2417880">in</span> <span m="2418000">our</span> <span m="2418120">[INAUDIBLE]</span>
  <span m="2418590">system</span> <span m="2418930">for</span> <span m="2419050">doing</span>
  <span m="2419280">those</span> <span m="2419420">types</span> <span m="2419650">of</span>
  <span m="2419690">problems.</span> <span m="2420270">It''s</span> <span m="2420570">the</span>
  <span m="2420610">thing that</span> <span m="2420850">most</span> <span m="2421050">people</span>
  <span m="2421280">do.</span></p><p><span m="2422020">However,</span> <span m="2423100">if</span>
  <span m="2423320">you</span> <span m="2423470">have</span> <span m="2423670">a</span>
  <span m="2423790">large</span> <span m="2424490">amount</span> <span m="2424810">of</span>
  <span m="2424910">data</span> <span m="2425980">and</span> <span m="2426140">you</span>
  <span m="2426240">want</span> <span m="2426390">to</span> <span m="2426430">be</span>
  <span m="2426570">accessing</span> <span m="2427170">small</span> <span m="2428140">fractions</span>
  <span m="2428780">of</span> <span m="2428910">it</span> <span m="2430150">randomly,</span>
  <span m="2431920">that''s</span> <span m="2432360">when</span> <span m="2432500">you</span>
  <span m="2432610">want</span> <span m="2432830">to</span> <span m="2432870">use</span>
  <span m="2433070">the</span> <span m="2433160">database.</span> <span m="2433630">That</span>
  <span m="2434150">is</span> <span m="2434360">the</span> <span m="2434460">use</span>
  <span m="2434850">case</span> <span m="2435970">for</span> <span m="2436240">the</span>
  <span m="2436340">database.</span> <span m="2437560">And</span> <span m="2437960">there
  are</span> <span m="2438100">definitely</span> <span m="2438430">times</span> <span
  m="2438810">when we</span> <span m="2439120">have</span> <span m="2439380">that</span>
  <span m="2439600">case</span> <span m="2440490">where</span> <span m="2440610">we</span>
  <span m="2440720">want</span> <span m="2441140">to</span> <span m="2441260">do</span>
  <span m="2441450">that.</span> <span m="2442390">But</span> <span m="2443280">you</span>
  <span m="2443490">want</span> <span m="2443790">to</span> <span m="2444180">build</span>
  <span m="2444610">towards</span> <span m="2444865">it.</span> <span m="2445120">A</span>
  <span m="2445190">lot</span> <span m="2445400">of</span> <span m="2445480">times</span>
  <span m="2445840">when</span> <span m="2445970">you''re</span> <span m="2446090">doing</span>
  <span m="2446490">analytics</span> <span m="2446760">or</span> <span m="2447030">algorithm</span>
  <span m="2447400">development,</span> <span m="2448050">you</span> <span m="2448180">tend
  to</span> <span m="2448270">be</span> <span m="2449180">in</span> <span m="2449360">these</span>
  <span m="2449710">cases</span> <span m="2450240">first.</span> <span m="2451320">And</span>
  <span m="2452150">so</span> <span m="2452340">rather</span> <span m="2452730">than</span>
  <span m="2454050">bite</span> <span m="2454490">off</span> <span m="2454780">the</span>
  <span m="2454890">complexity</span> <span m="2455760">associated</span> <span m="2456840">with</span>
  <span m="2457070">dealing</span> <span m="2457420">with</span> <span m="2457570">a</span>
  <span m="2457620">database,</span> <span m="2458700">use</span> <span m="2459030">these</span>
  <span m="2459280">tools</span> <span m="2459610">first.</span> <span m="2460270">But</span>
  <span m="2460400">then</span> <span m="2460560">eventually,</span> <span m="2461720">there</span>
  <span m="2461920">may</span> <span m="2462070">be a</span> <span m="2462220">time</span>
  <span m="2462470">where you</span> <span m="2462610">actually</span> <span m="2462870">have</span>
  <span m="2463050">to</span> <span m="2463140">use</span> <span m="2463290">the</span>
  <span m="2463390">database.</span> <span m="2463880">And</span> <span m="2464080">hopefully,</span>
  <span m="2465270">one</span> <span m="2465510">thing</span> <span m="2465640">you</span>
  <span m="2466070">get</span> <span m="2466230">out</span> <span m="2466410">of this</span>
  <span m="2466540">course is</span> <span m="2466980">understanding</span> <span
  m="2467920">this</span> <span m="2468150">nuance</span> <span m="2468310">type</span>
  <span m="2468700">of</span> <span m="2468940">thing.</span></p><p><span m="2469310">Because</span>
  <span m="2469530">a</span> <span m="2469560">lot</span> <span m="2469890">of</span>
  <span m="2469970">people</span> <span m="2470300">say,</span> <span m="2470870">we</span>
  <span m="2471120">need a</span> <span m="2471210">parallel</span> <span m="2471540">database.</span>
  <span m="2472670">Why?</span> <span m="2473480">We</span> <span m="2473640">have</span>
  <span m="2473700">a</span> <span m="2473730">lot</span> <span m="2473950">of</span>
  <span m="2474000">data.</span> <span m="2474630">All</span> <span m="2474760">right.</span>
  <span m="2474970">That''s</span> <span m="2475180">great.</span> <span m="2475810">Well,</span>
  <span m="2475950">what</span> <span m="2476070">do you</span> <span m="2476160">want
  to</span> <span m="2476340">do?</span> <span m="2476470">We want</span> <span m="2476920">to</span>
  <span m="2477140">scan over</span> <span m="2477300">the</span> <span m="2477390">whole</span>
  <span m="2477580">thing.</span> <span m="2479160">Well,</span> <span m="2479320">that''s</span>
  <span m="2479490">just</span> <span m="2479640">going</span> <span m="2479750">to</span>
  <span m="2479810">be</span> <span m="2480690">a</span> <span m="2480780">lot</span>
  <span m="2481000">of</span> <span m="2481040">data</span> <span m="2481320">really</span>
  <span m="2481560">slow.</span> <span m="2483180">So</span> <span m="2483250">people</span>
  <span m="2483590">will</span> <span m="2483900">do</span> <span m="2484020">that.</span>
  <span m="2484210">They''ll</span> <span m="2484310">load</span> <span m="2484530">a</span>
  <span m="2484570">bunch</span> <span m="2484780">of</span> <span m="2484860">data</span>
  <span m="2485165">in</span> <span m="2485470">the</span> <span m="2485660">system.</span>
  <span m="2485820">They''re</span> <span m="2486060">like,</span> <span m="2486210">well,</span>
  <span m="2486650">but</span> <span m="2486780">nothing is</span> <span m="2487190">faster.</span>
  <span m="2488940">It''s</span> <span m="2489050">like,</span> <span m="2489230">well,</span>
  <span m="2489630">yeah,</span> <span m="2489740">if you''re</span> <span m="2490070">going</span>
  <span m="2490190">to</span> <span m="2490230">scan</span> <span m="2490580">over
  a</span> <span m="2490860">significant</span> <span m="2491410">fraction</span>
  <span m="2491840">the</span> <span m="2491940">database,</span> <span m="2492410">it</span>
  <span m="2492540">will</span> <span m="2492810">be</span> <span m="2492940">slower--</span>
  <span m="2493850">certainly</span> <span m="2494150">slower</span> <span m="2494460">than</span>
  <span m="2494630">loading</span> <span m="2494970">it</span> <span m="2495050">into</span>
  <span m="2495260">the</span> <span m="2495340">memories</span> <span m="2495870">of</span>
  <span m="2495990">a</span> <span m="2496060">bunch</span> <span m="2496290">of</span>
  <span m="2496360">computers,</span> <span m="2496970">and</span> <span m="2497520">even</span>
  <span m="2497710">slower</span> <span m="2498060">than</span> <span m="2498510">just</span>
  <span m="2498690">having</span> <span m="2498940">a</span> <span m="2498990">bunch</span>
  <span m="2499200">of</span> <span m="2499300">files</span> <span m="2499740">and</span>
  <span m="2499940">reading</span> <span m="2500230">them</span> <span m="2500360">into</span>
  <span m="2500540">memory.</span></p><p><span m="2501770">And</span> <span m="2501930">increasingly</span>
  <span m="2502620">nowadays,</span> <span m="2506500">you''re</span> <span m="2506660">talking</span>
  <span m="2507120">about</span> <span m="2508170">this</span> <span m="2508590">is</span>
  <span m="2508960">millions</span> <span m="2509460">of</span> <span m="2509540">entries.</span>
  <span m="2512530">There''s</span> <span m="2512670">a</span> <span m="2512720">lot</span>
  <span m="2513120">of</span> <span m="2513320">things</span> <span m="2513690">that</span>
  <span m="2513830">were</span> <span m="2514030">databases</span> <span m="2514800">that</span>
  <span m="2514900">we</span> <span m="2515010">have,</span> <span m="2515320">like</span>
  <span m="2515550">the</span> <span m="2515790">lab''s</span> <span m="2516240">LDAP</span>
  <span m="2516710">server.</span> <span m="2518880">It''s</span> <span m="2519170">like</span>
  <span m="2519310">30,000</span> <span m="2519900">entries.</span> <span m="2520980">We</span>
  <span m="2521100">have</span> <span m="2521270">a</span> <span m="2521330">database</span>
  <span m="2521860">for</span> <span m="2522100">it.</span> <span m="2522520">You</span>
  <span m="2522640">could</span> <span m="2522780">send</span> <span m="2523140">it</span>
  <span m="2523220">around</span> <span m="2523490">an</span> <span m="2523600">Excel</span>
  <span m="2523950">spreadsheet</span> <span m="2524880">and</span> <span m="2525480">pretty</span>
  <span m="2525760">much</span> <span m="2525970">do</span> <span m="2526090">everything</span>
  <span m="2526430">with</span> <span m="2526580">that.</span> <span m="2527395">Or</span>
  <span m="2527720">the</span> <span m="2527830">entire</span> <span m="2528540">release</span>
  <span m="2528860">review</span> <span m="2529160">query,</span> <span m="2529620">or</span>
  <span m="2529810">the</span> <span m="2529920">phone</span> <span m="2530260">book,</span>
  <span m="2530530">or</span> <span m="2530580">whatever--</span> <span m="2530790">these</span>
  <span m="2530970">are</span> <span m="2531030">all</span> <span m="2531410">now,</span>
  <span m="2532050">by</span> <span m="2532200">today''s</span> <span m="2532570">standards,</span>
  <span m="2533230">microscopic</span> <span m="2534660">data</span> <span m="2534930">sets</span>
  <span m="2535230">that</span> <span m="2535330">can</span> <span m="2535590">trivially</span>
  <span m="2536030">be</span> <span m="2536380">stored</span> <span m="2536730">in</span>
  <span m="2536840">a</span> <span m="2536910">single</span> <span m="2537420">associative</span>
  <span m="2538030">array</span> <span m="2538570">in</span> <span m="2538700">something</span>
  <span m="2539050">like</span> <span m="2539240">this</span> <span m="2539500">and</span>
  <span m="2539590">manipulated</span> <span m="2539905">to</span> <span m="2540220">your</span>
  <span m="2540390">heart''s</span> <span m="2540620">content.</span> <span m="2541280">So</span>
  <span m="2541700">there''s</span> <span m="2541840">a</span> <span m="2541890">lot</span>
  <span m="2542180">of</span> <span m="2542230">data</span> <span m="2542480">sets</span>
  <span m="2542700">that</span> <span m="2542930">are</span> <span m="2542980">big</span>
  <span m="2543270">to</span> <span m="2543380">the</span> <span m="2543530">human</span>
  <span m="2544220">but</span> <span m="2544400">are</span> <span m="2544730">microscopic</span>
  <span m="2546020">to</span> <span m="2546170">the</span> <span m="2546300">technology</span>
  <span m="2546960">nowadays.</span></p><p><span m="2548480">So</span> <span m="2548620">this</span>
  <span m="2548810">is</span> <span m="2548960">usually</span> <span m="2549280">millions</span>
  <span m="2549920">of</span> <span m="2550010">entries.</span> <span m="2552430">This</span>
  <span m="2552650">might</span> <span m="2552880">be</span> <span m="2553050">hundreds</span>
  <span m="2553460">of</span> <span m="2553540">millions</span> <span m="2554680">of</span>
  <span m="2554800">entries.</span> <span m="2555370">Definitely,</span> <span m="2555820">when</span>
  <span m="2555960">you</span> <span m="2556110">really</span> <span m="2556400">need--</span>
  <span m="2556980">often,</span> <span m="2557340">you''re</span> <span m="2557480">talking</span>
  <span m="2557800">about</span> <span m="2558010">billions</span> <span m="2558440">of</span>
  <span m="2558540">entries</span> <span m="2559380">when you''re</span> <span m="2559600">getting</span>
  <span m="2559820">here</span> <span m="2560020">to</span> <span m="2560100">the</span>
  <span m="2560180">point</span> <span m="2560420">where</span> <span m="2560580">you</span>
  <span m="2560650">really</span> <span m="2560890">need a</span> <span m="2561300">database.</span>
  <span m="2562480">The</span> <span m="2562610">exception</span> <span m="2563330">to</span>
  <span m="2563450">this</span> <span m="2563790">being</span> <span m="2564420">if</span>
  <span m="2564590">you''re</span> <span m="2564770">in</span> <span m="2564930">a</span>
  <span m="2565000">program</span> <span m="2566270">that</span> <span m="2566440">requires--</span>
  <span m="2567500">many of</span> <span m="2567770">our</span> <span m="2567910">customers</span>
  <span m="2568330">will say</span> <span m="2568790">the</span> <span m="2568980">database</span>
  <span m="2569570">is</span> <span m="2569720">being</span> <span m="2570050">used.</span>
  <span m="2570470">This</span> <span m="2570650">is</span> <span m="2570770">where</span>
  <span m="2570950">the</span> <span m="2571080">data</span> <span m="2571320">is.</span>
  <span m="2571710">It''s</span> <span m="2571960">in</span> <span m="2572100">no</span>
  <span m="2572300">other</span> <span m="2572550">place.</span> <span m="2574010">So</span>
  <span m="2574220">for</span> <span m="2574350">integration</span> <span m="2575040">purposes,</span>
  <span m="2575580">then you</span> <span m="2575820">throw all</span> <span m="2576300">this</span>
  <span m="2576420">out the</span> <span m="2576500">window.</span></p><p><span m="2577700">If</span>
  <span m="2577870">they</span> <span m="2578070">say,</span> <span m="2578260">look,</span>
  <span m="2578510">this</span> <span m="2578840">is</span> <span m="2579010">where</span>
  <span m="2579180">the</span> <span m="2579290">data</span> <span m="2579500">is</span>
  <span m="2579840">and</span> <span m="2580410">that''s</span> <span m="2580610">the</span>
  <span m="2580710">only</span> <span m="2580960">way</span> <span m="2581130">you</span>
  <span m="2581210">can</span> <span m="2581380">get</span> <span m="2581530">it,</span>
  <span m="2582090">then</span> <span m="2582630">of</span> <span m="2582760">course.</span>
  <span m="2583990">But</span> <span m="2584110">that</span> <span m="2584300">still</span>
  <span m="2584530">doesn''t</span> <span m="2584840">mean</span> <span m="2585140">you</span>
  <span m="2585260">might</span> <span m="2585510">be</span> <span m="2585600">like,</span>
  <span m="2585840">yeah,</span> <span m="2585900">well,</span> <span m="2586050">you''re</span>
  <span m="2586210">going</span> <span m="2586300">to</span> <span m="2586350">store</span>
  <span m="2586600">it in the</span> <span m="2586720">database,</span> <span m="2587070">but</span>
  <span m="2587300">I''m</span> <span m="2587490">going to</span> <span m="2587780">store
  it</span> <span m="2588070">in</span> <span m="2588390">/temp,</span> <span m="2589560">and</span>
  <span m="2589820">work</span> <span m="2590060">on</span> <span m="2590250">it,</span>
  <span m="2590580">and</span> <span m="2590730">then</span> <span m="2590950">put</span>
  <span m="2591110">my</span> <span m="2591220">results</span> <span m="2591620">back</span>
  <span m="2591830">in</span> <span m="2591880">the</span> <span m="2591940">database,</span>
  <span m="2592410">because</span> <span m="2592700">I</span> <span m="2592800">know</span>
  <span m="2593000">that</span> <span m="2593420">what</span> <span m="2593600">I''m</span>
  <span m="2593760">doing</span> <span m="2594110">is</span> <span m="2594600">going</span>
  <span m="2594720">to</span> <span m="2594760">be</span> <span m="2594860">better.</span>
  <span m="2595660">There''s</span> <span m="2595870">no--</span> <span m="2597290">as
  they</span> <span m="2597440">say,</span> <span m="2598550">we</span> <span m="2598720">don''t</span>
  <span m="2598840">want</span> <span m="2598940">to</span> <span m="2598980">be</span>
  <span m="2599070">too</span> <span m="2599260">proud</span> <span m="2599610">to</span>
  <span m="2599720">win.</span></p><p><span m="2600560">Just</span> <span m="2600730">because</span>
  <span m="2601370">some</span> <span m="2601590">people,</span> <span m="2601690">it''s</span>
  <span m="2601810">like,</span> <span m="2601990">we</span> <span m="2602110">have</span>
  <span m="2602280">a</span> <span m="2602300">database,</span> <span m="2602800">and</span>
  <span m="2602910">everything</span> <span m="2603250">must</span> <span m="2603460">be</span>
  <span m="2603590">purely</span> <span m="2604010">done</span> <span m="2604220">in</span>
  <span m="2604340">the</span> <span m="2604440">database.</span> <span m="2605200">Or</span>
  <span m="2605270">some people are</span> <span m="2605510">like,</span> <span m="2605690">we</span>
  <span m="2605810">have</span> <span m="2606410">a</span> <span m="2606520">file</span>
  <span m="2606860">system, and</span> <span m="2607250">everything</span> <span m="2607540">must</span>
  <span m="2607730">be</span> <span m="2607960">purely</span> <span m="2608140">done</span>
  <span m="2608350">in the</span> <span m="2608430">file</span> <span m="2608740">system.</span>
  <span m="2609420">Or</span> <span m="2609910">we</span> <span m="2610590">have</span>
  <span m="2610940">this</span> <span m="2611170">language</span> <span m="2611640">and</span>
  <span m="2611760">everything--</span> <span m="2613030">the</span> <span m="2613220">right</span>
  <span m="2613470">tool</span> <span m="2613730">for</span> <span m="2613830">the</span>
  <span m="2613940">job,</span> <span m="2616350">pulling</span> <span m="2616620">them</span>
  <span m="2616750">together,</span> <span m="2617560">totally</span> <span m="2617920">fine.</span>
  <span m="2618620">It''s</span> <span m="2618710">a</span> <span m="2618770">quick</span>
  <span m="2619040">way</span> <span m="2619360">to</span> <span m="2619540">get</span>
  <span m="2620010">this</span> <span m="2620190">work</span> <span m="2620410">done</span>
  <span m="2620580">without</span> <span m="2620880">driving</span> <span m="2621120">yourself</span>
  <span m="2621450">crazy.</span></p><p><span m="2622580">So</span> <span m="2622930">with</span>
  <span m="2623080">that,</span> <span m="2623290">I''ll come</span> <span m="2623580">to</span>
  <span m="2623640">the</span> <span m="2623780">end.</span> <span m="2624080">I</span>
  <span m="2624180">have</span> <span m="2624470">one</span> <span m="2625250">code</span>
  <span m="2625520">example</span> <span m="2626090">which</span> <span m="2626270">is</span>
  <span m="2626360">relatively</span> <span m="2626800">short</span> <span m="2627160">to</span>
  <span m="2627240">show</span> <span m="2627500">you.</span> <span m="2628240">But</span>
  <span m="2628780">again,</span> <span m="2629250">parallel</span> <span m="2629660">graphs</span>
  <span m="2629980">are</span> <span m="2630100">the</span> <span m="2630220">dominant</span>
  <span m="2630780">type</span> <span m="2630990">of</span> <span m="2631070">data</span>
  <span m="2631360">we</span> <span m="2631450">see.</span> <span m="2632390">Graph500</span>
  <span m="2632830">relies</span> <span m="2633180">on</span> <span m="2633530">this</span>
  <span m="2633740">Kronecker</span> <span m="2634830">graphs.</span> <span m="2635380">Kronecker</span>
  <span m="2635590">graph</span> <span m="2635960">theory</span> <span m="2636215">is</span>
  <span m="2636470">a</span> <span m="2636540">great</span> <span m="2637310">theoretical</span>
  <span m="2637800">framework</span> <span m="2638340">for</span> <span m="2638500">looking</span>
  <span m="2638860">at</span> <span m="2639010">stuff.</span> <span m="2639560">You</span>
  <span m="2639650">get</span> <span m="2639790">all</span> <span m="2640340">the</span>
  <span m="2640940">identity</span> <span m="2641480">benefits</span> <span m="2642060">that</span>
  <span m="2642220">come</span> <span m="2642600">with</span> <span m="2643150">Kronecker</span>
  <span m="2644080">product</span> <span m="2644480">eigenvalues.</span> <span m="2645265">If</span>
  <span m="2645660">you''re</span> <span m="2645810">into</span> <span m="2645970">that,</span>
  <span m="2646230">I</span> <span m="2646310">certainly</span> <span m="2646860">suggest</span>
  <span m="2647210">you</span> <span m="2647360">read</span> <span m="2647570">the</span>
  <span m="2647630">Van</span> <span m="2647985">Loan</span> <span m="2648500">paper,</span>
  <span m="2649190">which</span> <span m="2649380">is</span> <span m="2649540">also</span>
  <span m="2650400">the</span> <span m="2650510">seminal</span> <span m="2650930">work</span>
  <span m="2651230">on</span> <span m="2651490">Kronecker</span> <span m="2652070">products.</span>
  <span m="2652770">And</span> <span m="2653230">I</span> <span m="2653350">don''t</span>
  <span m="2653460">think</span> <span m="2653580">anyone has</span> <span m="2653890">written</span>
  <span m="2654150">a</span> <span m="2654210">followup</span> <span m="2654660">to
  him, because</span> <span m="2655040">everyone is</span> <span m="2655360">like,</span>
  <span m="2655480">yep,</span> <span m="2656020">covered</span> <span m="2656280">it</span>
  <span m="2656370">there.</span> <span m="2656620">It''s</span> <span m="2656720">about</span>
  <span m="2656920">12,</span> <span m="2657280">15</span> <span m="2657640">pages.</span>
  <span m="2658450">Covered</span> <span m="2658740">all</span> <span m="2659060">the</span>
  <span m="2659150">properties</span> <span m="2659570">of</span> <span m="2659660">Kronecker</span>
  <span m="2660030">products.</span></p><p><span m="2662220">We</span> <span m="2662380">can</span>
  <span m="2662520">do</span> <span m="2662730">parallel</span> <span m="2663080">computing</span>
  <span m="2663510">in</span> <span m="2663570">D4M</span> <span m="2664050">via</span>
  <span m="2664340">pMATLAB.</span> <span m="2665400">And</span> <span m="2665710">again,</span>
  <span m="2666640">fundamentally,</span> <span m="2667430">if</span> <span m="2667540">you''ve</span>
  <span m="2667690">implemented</span> <span m="2668130">your</span> <span m="2668300">algorithms</span>
  <span m="2668710">correctly,</span> <span m="2669090">they''re</span> <span m="2669220">limited</span>
  <span m="2669620">by</span> <span m="2669760">hardware,</span> <span m="2671430">by</span>
  <span m="2671560">fundamental</span> <span m="2672090">aspects</span> <span m="2672590">of
  the</span> <span m="2672690">hardware.</span> <span m="2672990">There</span> <span
  m="2673130">are</span> <span m="2673270">limitations.</span> <span m="2673570">It''s</span>
  <span m="2673870">important</span> <span m="2674200">to</span> <span m="2674290">know</span>
  <span m="2674480">what</span> <span m="2674590">those</span> <span m="2674820">are</span>
  <span m="2675500">and</span> <span m="2675810">to</span> <span m="2675950">be</span>
  <span m="2676110">aware</span> <span m="2676360">of</span> <span m="2676600">them.</span></p>'
type: course
uid: 6e30eb0751acbd43196ff5b47508d2ff

---
None