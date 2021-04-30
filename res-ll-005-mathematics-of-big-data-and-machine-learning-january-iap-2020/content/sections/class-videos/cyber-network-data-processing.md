---
about_this_resource_text: <h2 class="subhead">Description</h2> <p>In this video, which
  plays from the beginning to 00:23:28, Dr. Vijay Gadepally discusses anomaly detection
  and data conditioning in machine learning.</p> <p><strong>Instructor:</strong>&nbsp;Vijay
  Gadepally</p>
course_id: res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020
embedded_media:
- id: Video-YouTube-Stream
  media_location: RpPlj2HnuWg
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: Video-YouTube-Stream
  type: Video
  uid: cfd4b110b59c97aeb0ee07448798484d
- id: 3Play-3PlayYouTubeid-MP4
  media_location: RpPlj2HnuWg
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: bae2487a5f38a088f30b9cfeebe111d6
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITRESLL-005IAP20/MITRESLL-005IAP20_ses02_300k.mp4
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: Video-Internet Archive-MP4
  type: Video
  uid: ecfacc6be0e8dfabde56dd59f35a5020
- id: RpPlj2HnuWg.srt
  parent_uid: 220f355503e86e36bb1588e0277a066c
  technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/cyber-network-data-processing/RpPlj2HnuWg.srt
  title: 3play caption file
  type: null
  uid: 2d41940c80508d1a6c7ed65c9d2071f8
- id: RpPlj2HnuWg.pdf
  parent_uid: 220f355503e86e36bb1588e0277a066c
  technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/cyber-network-data-processing/RpPlj2HnuWg.pdf
  title: 3play pdf file
  type: null
  uid: 1d360cf2e7cba564583a9a5f182083cc
- id: Caption-3Play YouTube id-SRT_1
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1b7a44ce4dcc88d3d86c9f938252c2d2
- id: Transcript-3Play YouTube id-PDF_1
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 413a40658e57773f621eaa283b2be6f4
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/RpPlj2HnuWg/default.jpg
  parent_uid: 220f355503e86e36bb1588e0277a066c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b36862b26bff870d827fcce34612b29d
inline_embed_id: 54654736aidataarchitecture92477327
layout: video
order_index: null
parent_uid: 22ed3115fb6b8a6bf2e9075e053e3953
related_resources_text: ''
short_url: cyber-network-data-processing
technical_location: https://ocw.mit.edu/resources/res-ll-005-mathematics-of-big-data-and-machine-learning-january-iap-2020/class-videos/cyber-network-data-processing
template_type: Embed
title: Cyber Network Data Processing
transcript: <p><span m="496">[SQUEAKING]</span></p><p><span m="1984">[RUSTLING]</span></p><p><span
  m="3968">[CLICKING]</span></p><p>&nbsp;</p><p><span m="16370">VIJAY GADEPALLY:</span>
  <span m="16380">I</span> <span m="16670">hope</span> <span m="16890">you all</span>
  <span m="17010">are</span> <span m="17220">enjoying</span> <span m="17460">the</span>
  <span m="17520">class</span> <span m="17950">so</span> <span m="18000">far.</span>
  <span m="18920">It's</span> <span m="19620">always</span> <span m="19860">interesting--</span>
  <span m="20430">we</span> <span m="20550">have</span> <span m="20730">people</span>
  <span m="21030">with</span> <span m="21180">a</span> <span m="21240">variety</span>
  <span m="21720">of</span> <span m="21810">backgrounds</span> <span m="22440">here,</span>
  <span m="23560">so</span> <span m="23640">it's</span> <span m="23740">just</span>
  <span m="23940">great</span> <span m="24270">to</span> <span m="24810">kind</span>
  <span m="24960">of</span> <span m="25050">hear</span> <span m="25230">the</span>
  <span m="25320">questions</span> <span m="25860">as</span> <span m="26010">we're</span>
  <span m="26130">going</span> <span m="26370">along.</span></p><p><span m="27460">So</span>
  <span m="27960">I'm</span> <span m="28020">going</span> <span m="28140">to</span>
  <span m="28230">give</span> <span m="28380">a</span> <span m="28440">quick</span>
  <span m="28800">example</span> <span m="30870">to</span> <span m="30990">begin</span>
  <span m="31260">the</span> <span m="31350">class</span> <span m="31680">right</span>
  <span m="31890">now</span> <span m="32390">that</span> <span m="32490">kind</span>
  <span m="32729">of</span> <span m="32790">drive</span> <span m="33180">in</span>
  <span m="33390">some</span> <span m="33570">of</span> <span m="33630">the</span>
  <span m="33690">concepts</span> <span m="34290">that</span> <span m="34410">we</span>
  <span m="34530">talked</span> <span m="34890">about</span> <span m="35340">on</span>
  <span m="35490">the</span> <span m="35580">first</span> <span m="35850">class.</span>
  <span m="36130">But</span> <span m="36240">this</span> <span m="36390">is</span>
  <span m="36660">kind</span> <span m="36870">of</span> <span m="36930">real</span>
  <span m="37290">rather</span> <span m="37560">than</span> <span m="37770">sort</span>
  <span m="37980">of</span> <span m="38040">cartoon</span> <span m="38760">neural</span>
  <span m="39030">networks.</span> <span m="39860">But</span> <span m="40020">it's</span>
  <span m="40110">sort</span> <span m="40320">of</span> <span m="40380">a</span> <span
  m="40470">real</span> <span m="40740">research</span> <span m="41220">result</span>
  <span m="41590">that</span> <span m="42690">we</span> <span m="42840">have.</span></p><p><span
  m="43950">Before</span> <span m="44250">I</span> <span m="44310">begin,</span> <span
  m="44710">I'd</span> <span m="44810">like</span> <span m="44910">to</span> <span
  m="45030">thank</span> <span m="45630">Emily</span> <span m="45930">Do</span> <span
  m="46260">who</span> <span m="46380">was</span> <span m="46470">one</span> <span
  m="46590">of</span> <span m="46650">my</span> <span m="46770">graduate</span> <span
  m="47160">students</span> <span m="47460">who</span> <span m="47550">actually</span>
  <span m="47850">did</span> <span m="48000">all</span> <span m="48120">the</span>
  <span m="48210">work.</span> <span m="48770">I</span> <span m="48930">just</span>
  <span m="49080">put</span> <span m="49500">some</span> <span m="49740">of</span>
  <span m="49830">the</span> <span m="49920">slides</span> <span m="50250">together--</span>
  <span m="50640">not</span> <span m="50760">even</span> <span m="50940">all</span>
  <span m="51090">of</span> <span m="51180">them,</span> <span m="51480">just</span>
  <span m="51690">a</span> <span m="51720">few.</span> <span m="52500">So</span> <span
  m="52650">really,</span> <span m="52890">the</span> <span m="52980">credit</span>
  <span m="53310">for</span> <span m="53460">this</span> <span m="53640">work</span>
  <span m="54600">goes</span> <span m="54840">to</span> <span m="54930">Emily.</span>
  <span m="55920">Anything</span> <span m="56310">I</span> <span m="56610">misrepresent</span>
  <span m="57360">is</span> <span m="57690">my</span> <span m="57930">fault,</span>
  <span m="58540">not</span> <span m="58620">hers.</span> <span m="59580">She</span>
  <span m="59760">graduated,</span> <span m="60450">so</span> <span m="61080">I'll</span>
  <span m="61230">take</span> <span m="61440">the</span> <span m="61530">blame</span>
  <span m="61800">for</span> <span m="61980">anything</span> <span m="63330">that's</span>
  <span m="63520">not</span> <span m="63720">interesting.</span> <span m="64330">So</span>
  <span m="65730">with</span> <span m="65910">that,</span> <span m="66370">we'll</span>
  <span m="66420">begin.</span></p><p><span m="67680">All</span> <span m="67740">right,</span>
  <span m="67920">so</span> <span m="68040">the</span> <span m="68130">overall</span>
  <span m="68490">goal</span> <span m="68820">of</span> <span m="68940">this</span>
  <span m="69120">project</span> <span m="69780">was</span> <span m="70050">really</span>
  <span m="70350">to</span> <span m="70500">detect</span> <span m="70870">and</span>
  <span m="70990">classify</span> <span m="71460">network</span> <span m="71790">attacks</span>
  <span m="72180">from</span> <span m="72330">real</span> <span m="72600">internet</span>
  <span m="72960">traffic.</span> <span m="73990">And</span> <span m="74220">in</span>
  <span m="74370">order</span> <span m="74580">to</span> <span m="74700">do</span>
  <span m="74910">this,</span> <span m="75750">as</span> <span m="75930">many</span>
  <span m="76110">of</span> <span m="76200">you</span> <span m="76320">can</span>
  <span m="76470">imagine,</span> <span m="76950">we</span> <span m="77040">had</span>
  <span m="77160">to</span> <span m="77250">find</span> <span m="77580">a</span> <span
  m="77680">data</span> <span m="77900">set</span> <span m="78180">that</span> <span
  m="78330">was</span> <span m="78510">of</span> <span m="78630">interest.</span>
  <span m="79000">So</span> <span m="79100">this</span> <span m="79140">is</span>
  <span m="79260">probably</span> <span m="79590">a</span> <span m="79650">problem</span>
  <span m="79990">many</span> <span m="80160">of</span> <span m="80250">you</span>
  <span m="80370">are</span> <span m="80520">currently</span> <span m="81000">thinking</span>
  <span m="81360">about,</span> <span m="81760">which</span> <span m="81840">is</span>
  <span m="82380">what</span> <span m="82660">data</span> <span m="82900">set</span>
  <span m="83190">should</span> <span m="83370">I</span> <span m="83460">get</span>
  <span m="83640">my</span> <span m="83820">hands</span> <span m="84180">on?</span>
  <span m="84810">Right,</span> <span m="85020">so</span> <span m="85140">we</span>
  <span m="85260">have</span> <span m="85560">a</span> <span m="85650">variety</span>
  <span m="86100">of</span> <span m="86200">data</span> <span m="86420">sets.</span>
  <span m="86700">Some</span> <span m="87000">are</span> <span m="87150">sensitive</span>
  <span m="87630">in</span> <span m="87690">nature,</span> <span m="88170">right?</span>
  <span m="88380">So</span> <span m="88500">think</span> <span m="88710">of</span>
  <span m="88890">internal</span> <span m="90000">network</span> <span m="90390">traffic</span>
  <span m="91140">that</span> <span m="91290">we're</span> <span m="91440">trying</span>
  <span m="91710">to</span> <span m="91800">collect.</span> <span m="92520">No</span>
  <span m="92820">one's</span> <span m="93060">going</span> <span m="93150">to</span>
  <span m="93270">let</span> <span m="93450">us</span> <span m="94650">hand</span>
  <span m="94800">this</span> <span m="94920">over</span> <span m="95100">to</span>
  <span m="95220">graduate</span> <span m="95640">students</span> <span m="96600">to</span>
  <span m="96720">kind</span> <span m="96960">of</span> <span m="97530">work</span>
  <span m="97890">on,</span> <span m="98160">and</span> <span m="98250">then</span>
  <span m="98400">more</span> <span m="98580">importantly,</span> <span m="99030">publish.</span></p><p><span
  m="99870">So</span> <span m="99990">the</span> <span m="100080">first</span> <span
  m="100380">thing</span> <span m="100500">that</span> <span m="100620">we</span>
  <span m="100710">wanted</span> <span m="100950">to</span> <span m="101040">do</span>
  <span m="101190">was</span> <span m="101400">look</span> <span m="101610">for</span>
  <span m="102000">a</span> <span m="102090">data</span> <span m="102270">set</span>
  <span m="102630">that</span> <span m="102780">was</span> <span m="103110">kind</span>
  <span m="103380">of</span> <span m="103530">open</span> <span m="104020">and</span>
  <span m="104200">out</span> <span m="104430">there.</span> <span m="105060">And</span>
  <span m="105330">we're</span> <span m="105540">fortunate</span> <span m="106500">that</span>
  <span m="106680">there</span> <span m="106920">is</span> <span m="107100">a</span>
  <span m="107250">group</span> <span m="107580">in</span> <span m="107670">Japan</span>
  <span m="108210">called</span> <span m="108480">the</span> <span m="108570">MAWI</span>
  <span m="108990">working</span> <span m="109410">group,</span> <span m="110130">which</span>
  <span m="110310">stands</span> <span m="110580">for</span> <span m="110700">the</span>
  <span m="110790">measurement--</span> <span m="111420">and</span> <span m="111630">I'll</span>
  <span m="111920">use</span> <span m="112110">my</span> <span m="112470">cool</span>
  <span m="112710">tool--</span> <span m="113270">the</span> <span m="113730">measurement</span>
  <span m="114240">and</span> <span m="114330">analysis</span> <span m="114840">of</span>
  <span m="114960">wide</span> <span m="115200">area</span> <span m="115500">internet</span>
  <span m="115860">traffic</span> <span m="116400">working</span> <span m="116730">group,</span>
  <span m="117300">that</span> <span m="117450">actually</span> <span m="117750">has</span>
  <span m="118350">10</span> <span m="118630">gig</span> <span m="118880">link</span>
  <span m="119610">that</span> <span m="119790">they've</span> <span m="120000">tapped</span>
  <span m="120750">using</span> <span m="120990">a</span> <span m="121050">network</span>
  <span m="121450">tap.</span> <span m="121950">And</span> <span m="122100">they</span>
  <span m="122220">actually</span> <span m="122520">make</span> <span m="122760">this</span>
  <span m="122940">data</span> <span m="123180">available.</span> <span m="123660">It's</span>
  <span m="123780">actually</span> <span m="124020">continuously</span> <span m="124770">updated</span>
  <span m="125850">even</span> <span m="126150">to</span> <span m="126270">today.</span></p><p><span
  m="127060">So</span> <span m="127470">that's</span> <span m="127740">really</span>
  <span m="127950">cool,</span> <span m="128710">and</span> <span m="128820">this</span>
  <span m="129030">is</span> <span m="129419">within</span> <span m="129780">that.</span>
  <span m="130919">It's</span> <span m="131640">called</span> <span m="131850">the</span>
  <span m="131970">Day-in-the-Life</span> <span m="132750">of</span> <span m="132840">the</span>
  <span m="132960">Internet.</span> <span m="134460">And</span> <span m="134670">so</span>
  <span m="134910">this</span> <span m="135120">has</span> <span m="135240">been</span>
  <span m="135420">going</span> <span m="135690">on</span> <span m="135870">for</span>
  <span m="136020">multiple</span> <span m="136500">years.</span> <span m="137670">The</span>
  <span m="137820">data</span> <span m="138110">set is</span> <span m="138510">reasonably</span>
  <span m="139050">large</span> <span m="139410">when</span> <span m="139560">you</span>
  <span m="139650">convert</span> <span m="140030">it</span> <span m="140190">into</span>
  <span m="140400">what</span> <span m="140550">we</span> <span m="140640">call</span>
  <span m="140850">an</span> <span m="141000">analyst</span> <span m="141420">friendly</span>
  <span m="141840">form,</span> <span m="142660">which</span> <span m="142740">is</span>
  <span m="142800">something</span> <span m="143160">that</span> <span m="143310">you</span>
  <span m="143520">or</span> <span m="143700">I</span> <span m="143910">could</span>
  <span m="144120">read</span> <span m="144540">and</span> <span m="144660">make</span>
  <span m="145440">some</span> <span m="145710">sense</span> <span m="146040">out</span>
  <span m="146250">of.</span> <span m="146630">It's</span> <span m="146730">about</span>
  <span m="146970">20</span> <span m="147240">terabytes</span> <span m="147840">in
  size.</span> <span m="148310">So</span> <span m="148590">a</span> <span m="148830">reasonably</span>
  <span m="149310">large</span> <span m="149600">data</span> <span m="149750">set,</span>
  <span m="149960">not</span> <span m="150190">going</span> <span m="150330">to</span>
  <span m="150450">fit</span> <span m="150750">on</span> <span m="151110">a</span>
  <span m="151170">single</span> <span m="151530">computer</span> <span m="152550">or</span>
  <span m="152700">a</span> <span m="152730">single</span> <span m="153090">node,</span>
  <span m="153450">so</span> <span m="154380">certainly</span> <span m="154860">a</span>
  <span m="155190">good</span> <span m="155400">use</span> <span m="155670">case</span>
  <span m="155910">for</span> <span m="156060">using</span> <span m="156390">high</span>
  <span m="156540">performance</span> <span m="156960">computing</span> <span m="157380">or</span>
  <span m="157440">supercomputing.</span></p><p><span m="158940">And</span> <span
  m="159120">one</span> <span m="159660">additional</span> <span m="160110">piece</span>
  <span m="160470">that</span> <span m="161160">we</span> <span m="161340">should</span>
  <span m="161550">note--</span> <span m="161910">and this</span> <span m="162090">is</span>
  <span m="162150">something</span> <span m="162540">that,</span> <span m="162780">as</span>
  <span m="162960">you're</span> <span m="163140">starting</span> <span m="163500">off</span>
  <span m="163680">your</span> <span m="163770">projects,</span> <span m="164330">you</span>
  <span m="164340">may</span> <span m="164490">also</span> <span m="164790">think</span>
  <span m="165030">about--</span> <span m="165750">IP</span> <span m="166080">addresses</span>
  <span m="166590">are</span> <span m="166710">often</span> <span m="167070">seen</span>
  <span m="167580">as</span> <span m="168390">reasonably</span> <span m="168900">sensitive.</span>
  <span m="169740">So</span> <span m="169890">you</span> <span m="170010">can</span>
  <span m="170160">see</span> <span m="170370">where</span> <span m="170520">traffic</span>
  <span m="170940">is</span> <span m="171060">coming</span> <span m="171360">and</span>
  <span m="171450">going</span> <span m="171720">from.</span> <span m="172450">So</span>
  <span m="172530">in</span> <span m="172710">this</span> <span m="172950">particular</span>
  <span m="173500">data</span> <span m="173700">set,</span> <span m="174000">they've</span>
  <span m="174210">actually</span> <span m="174720">deterministically</span> <span
  m="175650">anonymized</span> <span m="177600">each</span> <span m="177810">of</span>
  <span m="177960">the</span> <span m="178200">IP</span> <span m="178590">addresses.</span>
  <span m="179490">And</span> <span m="179670">as</span> <span m="179910">you're</span>
  <span m="180060">downloading</span> <span m="180540">the</span> <span m="180660">data,</span>
  <span m="181380">you</span> <span m="181530">have</span> <span m="181770">to,</span>
  <span m="182040">essentially,</span> <span m="182520">sign</span> <span m="182970">a</span>
  <span m="183030">user</span> <span m="183390">agreement</span> <span m="183810">saying</span>
  <span m="184080">that</span> <span m="184200">you</span> <span m="184290">will</span>
  <span m="184410">not</span> <span m="184650">attempt</span> <span m="185040">to</span>
  <span m="186120">kind</span> <span m="186330">of</span> <span m="186690">go</span>
  <span m="186870">back</span> <span m="187230">and</span> <span m="187350">figure</span>
  <span m="187620">out</span> <span m="187710">what</span> <span m="187890">the</span>
  <span m="187980">original</span> <span m="188400">IP</span> <span m="188730">addresses</span>
  <span m="189210">were.</span></p><p><span m="189660">So</span> <span m="189810">as</span>
  <span m="189960">you're</span> <span m="190140">coming</span> <span m="190500">up</span>
  <span m="190680">with</span> <span m="190860">the</span> <span m="190920">data</span>
  <span m="191220">sets--</span> <span m="191490">and</span> <span m="191580">I</span>
  <span m="191640">think</span> <span m="191790">Jeremy is</span> <span m="192150">going</span>
  <span m="192270">to</span> <span m="192330">talk</span> <span m="192540">a</span>
  <span m="192600">lot</span> <span m="192810">more</span> <span m="193020">about</span>
  <span m="193320">this</span> <span m="194230">in</span> <span m="194380">the</span>
  <span m="194460">next</span> <span m="194700">part--</span> <span m="195780">you</span>
  <span m="195900">might</span> <span m="196110">think</span> <span m="196380">about,</span>
  <span m="196830">you</span> <span m="196890">know,</span> <span m="197010">are</span>
  <span m="197190">there</span> <span m="197370">certain</span> <span m="197730">fields</span>
  <span m="198240">in</span> <span m="198360">the</span> <span m="198450">data</span>
  <span m="198750">that</span> <span m="198930">I'm</span> <span m="199050">collecting</span>
  <span m="199620">that</span> <span m="199770">might</span> <span m="200040">be</span>
  <span m="200190">deemed</span> <span m="200550">sensitive,</span> <span m="201360">either</span>
  <span m="201690">today</span> <span m="202020">or</span> <span m="202110">in</span>
  <span m="202230">the</span> <span m="202290">future?</span> <span m="203170">And</span>
  <span m="203190">if</span> <span m="203370">so,</span> <span m="203700">are</span>
  <span m="203880">there</span> <span m="204030">just</span> <span m="204240">simple</span>
  <span m="204600">techniques</span> <span m="205080">that</span> <span m="205230">I</span>
  <span m="205320">could</span> <span m="205530">use</span> <span m="205980">to</span>
  <span m="206130">anonymize</span> <span m="206820">the</span> <span m="206940">data?</span>
  <span m="208080">And</span> <span m="208260">then</span> <span m="208410">with</span>
  <span m="209280">a</span> <span m="209340">decent</span> <span m="210120">end</span>
  <span m="210270">user</span> <span m="210630">agreement,</span> <span m="211170">you</span>
  <span m="211290">might</span> <span m="211500">be</span> <span m="211650">able</span>
  <span m="211860">to</span> <span m="212220">enforce</span> <span m="212780">some</span>
  <span m="213060">level</span> <span m="213450">of</span> <span m="214320">people</span>
  <span m="214650">not</span> <span m="214920">trying</span> <span m="215250">to</span>
  <span m="215370">break</span> <span m="215700">it</span> <span m="216190">and</span>
  <span m="216330">trying</span> <span m="216630">to</span> <span m="216720">go</span>
  <span m="216900">back.</span> <span m="217540">It's</span> <span m="217860">not</span>
  <span m="218070">impossible</span> <span m="218640">to</span> <span m="218760">do</span>
  <span m="218970">it,</span> <span m="219210">but</span> <span m="219420">any</span>
  <span m="219690">legitimate</span> <span m="220170">researcher</span> <span m="220700">who</span>
  <span m="220810">is</span> <span m="220920">using</span> <span m="221220">data</span>
  <span m="222000">really</span> <span m="222300">shouldn't</span> <span m="222570">care</span>
  <span m="222870">about</span> <span m="223080">what</span> <span m="223260">the</span>
  <span m="223380">original</span> <span m="223770">IP</span> <span m="224100">addresses</span>
  <span m="224580">in</span> <span m="224700">this</span> <span m="224850">particular</span>
  <span m="225330">case</span> <span m="225660">are</span> <span m="226050">or</span>
  <span m="226170">maybe</span> <span m="226770">other</span> <span m="227040">such</span>
  <span m="227310">data</span> <span m="227880">within</span> <span m="228210">whatever</span>
  <span m="228480">your</span> <span m="228660">collecting.</span></p><p><span m="230460">All</span>
  <span m="230520">right,</span> <span m="230700">so</span> <span m="230820">just</span>
  <span m="231030">a</span> <span m="231090">quick</span> <span m="231690">definition</span>
  <span m="232260">of</span> <span m="232350">anomaly</span> <span m="232740">detection.</span>
  <span m="233080">I</span> <span m="233190">really</span> <span m="233550">love</span>
  <span m="233760">this</span> <span m="234210">definition</span> <span m="234930">of</span>
  <span m="235380">what</span> <span m="235560">an</span> <span m="235710">outlier</span>
  <span m="236400">is</span> <span m="236880">from</span> <span m="237135">a</span>
  <span m="237390">paper</span> <span m="237690">by</span> <span m="237840">Hawkins.</span>
  <span m="238900">So,</span> <span m="238950">&quot;An</span> <span m="239040">outlier</span>
  <span m="239430">is</span> <span m="239520">an</span> <span m="239610">observation</span>
  <span m="240210">that</span> <span m="240300">deviates</span> <span m="240810">so</span>
  <span m="241020">much</span> <span m="241320">from</span> <span m="241500">other</span>
  <span m="241740">observations</span> <span m="242580">as</span> <span m="242760">to</span>
  <span m="242850">arouse</span> <span m="243250">suspicion</span> <span m="244140">that</span>
  <span m="244260">it</span> <span m="244350">was</span> <span m="244500">generated</span>
  <span m="245160">by</span> <span m="245460">a</span> <span m="245490">different</span>
  <span m="245910">mechanism.&quot;</span> <span m="246970">So</span> <span m="247020">when</span>
  <span m="247170">we're</span> <span m="247290">looking</span> <span m="247590">at</span>
  <span m="247650">network</span> <span m="247980">traffic,</span> <span m="248790">that's</span>
  <span m="249090">what</span> <span m="249270">we're</span> <span m="249360">looking</span>
  <span m="249720">for.</span> <span m="250040">Right?</span></p><p><span m="250260">We're</span>
  <span m="250380">looking</span> <span m="250740">for</span> <span m="251070">these</span>
  <span m="251310">mechanisms</span> <span m="252240">that</span> <span m="252480">are</span>
  <span m="253200">present</span> <span m="253740">in</span> <span m="253830">network</span>
  <span m="254190">traffic</span> <span m="254970">that</span> <span m="255180">deviate</span>
  <span m="255760">so</span> <span m="256079">much</span> <span m="256320">from</span>
  <span m="256500">normal</span> <span m="256829">behavior</span> <span m="257910">that</span>
  <span m="259170">it</span> <span m="259589">arouses</span> <span m="260010">suspicion.</span>
  <span m="260579">And</span> <span m="260670">it</span> <span m="260730">could</span>
  <span m="260910">be</span> <span m="261810">for</span> <span m="262620">a</span>
  <span m="262710">variety</span> <span m="263160">of</span> <span m="263280">reasons.</span>
  <span m="263800">It</span> <span m="263900">could</span> <span m="263940">be</span>
  <span m="264060">somebody</span> <span m="264390">uploaded</span> <span m="264870">this</span>
  <span m="265080">cool</span> <span m="265410">video</span> <span m="266340">of</span>
  <span m="266730">somebody</span> <span m="267060">falling</span> <span m="267450">flat</span>
  <span m="267660">on</span> <span m="267750">their</span> <span m="267870">face,</span>
  <span m="269100">or</span> <span m="269460">it</span> <span m="269580">could</span>
  <span m="269790">be</span> <span m="270030">a</span> <span m="270090">botnet,</span>
  <span m="270750">or</span> <span m="271090">DDoS</span> <span m="271620">attack,</span>
  <span m="271980">or</span> <span m="272070">something</span> <span m="272430">like</span>
  <span m="272640">that.</span></p><p><span m="273150">So</span> <span m="273690">outlier</span>
  <span m="274140">can</span> <span m="274290">be</span> <span m="274380">sometimes</span>
  <span m="274890">referred</span> <span m="275250">to</span> <span m="275610">as</span>
  <span m="275940">an</span> <span m="276060">anomaly,</span> <span m="276660">surprise,</span>
  <span m="277590">or</span> <span m="277740">exception.</span> <span m="278710">And</span>
  <span m="278820">within</span> <span m="279060">the</span> <span m="279150">context</span>
  <span m="279750">of</span> <span m="279870">cyber</span> <span m="280260">networks,</span>
  <span m="280800">these</span> <span m="281010">mechanisms</span> <span m="281640">can</span>
  <span m="281820">be</span> <span m="282000">botnets,</span> <span m="282960">C&amp;C,</span>
  <span m="283530">or</span> <span m="283620">command</span> <span m="283920">and</span>
  <span m="284010">conquer</span> <span m="284430">servers,</span> <span m="285640">insider</span>
  <span m="286140">threats,</span> <span m="286560">or</span> <span m="286650">any</span>
  <span m="286920">other</span> <span m="287610">network</span> <span m="287970">attacks,</span>
  <span m="288300">such</span> <span m="288540">as</span> <span m="289050">distributed</span>
  <span m="289590">denial</span> <span m="289920">of</span> <span m="290010">service</span>
  <span m="290400">or</span> <span m="290490">port</span> <span m="290740">scan</span>
  <span m="291030">attacks.</span></p><p><span m="293010">There</span> <span m="293220">are</span>
  <span m="293430">a</span> <span m="293520">number</span> <span m="293790">of</span>
  <span m="293850">general</span> <span m="294180">techniques</span> <span m="294720">to</span>
  <span m="294840">deal</span> <span m="295170">with</span> <span m="295350">outlier</span>
  <span m="295800">detection.</span> <span m="296670">So</span> <span m="296850">the</span>
  <span m="296970">first</span> <span m="297270">one</span> <span m="297450">is</span>
  <span m="297750">to</span> <span m="297870">look</span> <span m="298080">for</span>
  <span m="298260">changes--</span> <span m="298800">is</span> <span m="298940">to</span>
  <span m="299160">essentially</span> <span m="299580">use</span> <span m="299700">statistics.</span>
  <span m="300570">You</span> <span m="300690">look</span> <span m="300870">at</span>
  <span m="301770">what's</span> <span m="302040">going</span> <span m="302310">on</span>
  <span m="302580">in</span> <span m="302730">your</span> <span m="302850">mechanism,</span>
  <span m="303780">and</span> <span m="303930">you</span> <span m="304020">look</span>
  <span m="304260">for</span> <span m="304530">statistical</span> <span m="305220">anomalies</span>
  <span m="306090">from</span> <span m="306480">that.</span> <span m="307230">And</span>
  <span m="307680">you'll</span> <span m="308070">highlight</span> <span m="308520">those</span>
  <span m="308730">anomalies,</span> <span m="309330">and</span> <span m="309450">then</span>
  <span m="309600">you'll</span> <span m="309720">kind</span> <span m="309900">of</span>
  <span m="310350">drive</span> <span m="310680">deep</span> <span m="310920">into</span>
  <span m="311130">that.</span> <span m="311730">You</span> <span m="311850">could</span>
  <span m="312030">do</span> <span m="312150">clustering.</span> <span m="312780">So</span>
  <span m="312990">if</span> <span m="313110">you're</span> <span m="313560">looking</span>
  <span m="313890">at</span> <span m="313980">unsupervised</span> <span m="314580">learning,</span>
  <span m="314970">you</span> <span m="315090">could</span> <span m="315240">cluster</span>
  <span m="315545">your</span> <span m="315850">data.</span> <span m="316600">And</span>
  <span m="316780">things</span> <span m="317110">that</span> <span m="317230">are</span>
  <span m="317320">really</span> <span m="317800">far</span> <span m="318100">away</span>
  <span m="318430">from</span> <span m="318970">existing</span> <span m="319540">clusters,</span>
  <span m="320170">or</span> <span m="320260">known</span> <span m="320590">clusters,</span>
  <span m="321220">are</span> <span m="321460">probably</span> <span m="321940">something</span>
  <span m="322270">that</span> <span m="322390">you</span> <span m="322510">want</span>
  <span m="322780">to</span> <span m="322930">take</span> <span m="323140">a</span>
  <span m="323200">look</span> <span m="323440">at.</span></p><p><span m="324070">You</span>
  <span m="324190">could</span> <span m="324370">lose--</span> <span m="324900">Similar</span>
  <span m="325270">to</span> <span m="325390">that</span> <span m="325600">is</span>
  <span m="325720">also</span> <span m="325980">distance-based</span> <span m="326680">techniques.</span>
  <span m="327200">So</span> <span m="327220">these</span> <span m="327400">are</span>
  <span m="327460">kind</span> <span m="327670">of</span> <span m="327940">closely</span>
  <span m="328330">related</span> <span m="329530">that</span> <span m="329680">you</span>
  <span m="329800">look</span> <span m="330010">for</span> <span m="330160">observations</span>
  <span m="330880">that</span> <span m="331000">very</span> <span m="331660">significantly</span>
  <span m="332470">from</span> <span m="332680">other</span> <span m="332920">observations</span>
  <span m="333760">in</span> <span m="333910">some</span> <span m="334180">sort</span>
  <span m="334390">of</span> <span m="334510">a</span> <span m="334600">feature</span>
  <span m="334990">space.</span> <span m="336290">And</span> <span m="336340">finally,</span>
  <span m="336700">you</span> <span m="336760">could</span> <span m="336910">use</span>
  <span m="337150">a</span> <span m="337240">model-based</span> <span m="337840">technique,</span>
  <span m="338560">where</span> <span m="338950">you</span> <span m="339280">attempt</span>
  <span m="339670">to</span> <span m="340000">model</span> <span m="340570">the</span>
  <span m="340690">behavior</span> <span m="341530">of</span> <span m="342040">normal--</span>
  <span m="342760">right,</span> <span m="342950">and I</span> <span m="343070">use</span>
  <span m="343270">air</span> <span m="343450">quotes</span> <span m="343750">for</span>
  <span m="343840">the</span> <span m="343930">word</span> <span m="344110">normal--</span>
  <span m="344950">and</span> <span m="345130">then,</span> <span m="345310">you</span>
  <span m="345430">come,</span> <span m="345760">and</span> <span m="345880">you</span>
  <span m="346000">look</span> <span m="346240">for</span> <span m="346390">things</span>
  <span m="346690">that</span> <span m="346840">deviate</span> <span m="347380">from</span>
  <span m="347650">this</span> <span m="347800">background</span> <span m="348250">model.</span>
  <span m="348550">So</span> <span m="348940">all</span> <span m="349120">of</span>
  <span m="349180">these</span> <span m="349360">four</span> <span m="349660">techniques</span>
  <span m="350200">are</span> <span m="350290">approaches</span> <span m="350920">to</span>
  <span m="351370">anomaly</span> <span m="351760">detection</span> <span m="352060">kind</span>
  <span m="352240">of</span> <span m="352330">related</span> <span m="352720">with</span>
  <span m="352870">each</span> <span m="353020">other.</span> <span m="353300">It's</span>
  <span m="353400">not</span> <span m="353440">a</span> <span m="353500">hard</span>
  <span m="353710">and</span> <span m="353830">fast</span> <span m="354970">rule</span>
  <span m="355300">about</span> <span m="355600">how</span> <span m="355860">they</span>
  <span m="356290">deviate</span> <span m="356680">from</span> <span m="356830">each</span>
  <span m="356980">other.</span></p><p><span m="357550">But</span> <span m="357700">for</span>
  <span m="357850">the</span> <span m="358450">popularity</span> <span m="359350">and</span>
  <span m="359470">the</span> <span m="359560">complexity</span> <span m="360310">of</span>
  <span m="360400">network</span> <span m="360790">traffic,</span> <span m="361460">we</span>
  <span m="361540">decide</span> <span m="361840">to</span> <span m="361960">go</span>
  <span m="362170">with</span> <span m="362380">a</span> <span m="362410">model-based</span>
  <span m="362980">technique</span> <span m="363640">because</span> <span m="363910">we</span>
  <span m="364000">found</span> <span m="364270">that</span> <span m="364420">any</span>
  <span m="364660">other</span> <span m="365200">means</span> <span m="365560">of</span>
  <span m="365650">trying</span> <span m="365860">to</span> <span m="365920">represent</span>
  <span m="366400">the</span> <span m="366490">data</span> <span m="366820">would</span>
  <span m="367000">be</span> <span m="367120">difficult.</span> <span m="367860">But</span>
  <span m="367990">this</span> <span m="368140">is</span> <span m="368230">sort</span>
  <span m="368410">of</span> <span m="368530">a</span> <span m="368590">top</span>
  <span m="368860">down</span> <span m="369100">approach</span> <span m="369490">of</span>
  <span m="369580">how</span> <span m="369730">we</span> <span m="369850">kind</span>
  <span m="370030">of</span> <span m="370090">thought</span> <span m="370360">about,</span>
  <span m="370960">well,</span> <span m="371080">let's</span> <span m="371260">look</span>
  <span m="371380">at</span> <span m="371470">network</span> <span m="371740">traffic--</span>
  <span m="372130">let's</span> <span m="372310">think</span> <span m="372460">about</span>
  <span m="372610">anomalies</span> <span m="373180">in</span> <span m="373270">network</span>
  <span m="373570">traffic--</span> <span m="374050">and</span> <span m="374140">let's</span>
  <span m="374320">come</span> <span m="374500">up</span> <span m="374620">with</span>
  <span m="374800">what's</span> <span m="375070">a</span> <span m="375130">good</span>
  <span m="375460">approach</span> <span m="375910">to</span> <span m="376360">address</span>
  <span m="376720">that.</span></p><p><span m="377780">So</span> <span m="377880">when</span>
  <span m="377890">we</span> <span m="377980">talk</span> <span m="378190">about</span>
  <span m="378400">network</span> <span m="378730">attacks--</span> <span m="379540">not</span>
  <span m="379720">to</span> <span m="379810">go</span> <span m="380020">into</span>
  <span m="380620">detail--</span> <span m="381780">there</span> <span m="382000">is</span>
  <span m="382120">a</span> <span m="382180">wide</span> <span m="382510">variety</span>
  <span m="383020">of</span> <span m="383110">network</span> <span m="383500">attacks</span>
  <span m="383920">out</span> <span m="384130">there.</span> <span m="385620">Every</span>
  <span m="385980">day</span> <span m="386210">we</span> <span m="386270">see</span>
  <span m="386540">news</span> <span m="386800">articles</span> <span m="387190">about</span>
  <span m="387430">new</span> <span m="387580">ones.</span> <span m="388210">The</span>
  <span m="388540">focus</span> <span m="388960">of</span> <span m="389050">this</span>
  <span m="389230">work</span> <span m="389560">was</span> <span m="389830">to</span>
  <span m="389950">look</span> <span m="390190">at</span> <span m="390250">just</span>
  <span m="390490">a</span> <span m="390550">couple</span> <span m="390850">of</span>
  <span m="390970">these.</span> <span m="391540">One</span> <span m="391810">was</span>
  <span m="391990">in</span> <span m="392110">this</span> <span m="392230">section</span>
  <span m="392680">that</span> <span m="392770">we</span> <span m="392860">call</span>
  <span m="393070">probing</span> <span m="393490">and</span> <span m="393580">scanning,</span>
  <span m="394300">and</span> <span m="394420">another</span> <span m="394720">was</span>
  <span m="394960">in</span> <span m="395080">this</span> <span m="395380">resource</span>
  <span m="396040">usage</span> <span m="396580">or</span> <span m="396640">resource</span>
  <span m="397180">utilization</span> <span m="397900">area.</span> <span m="398750">And</span>
  <span m="399100">specifically,</span> <span m="399640">we</span> <span m="399760">looked</span>
  <span m="399940">at</span> <span m="400060">port</span> <span m="400360">scanning</span>
  <span m="400870">and</span> <span m="401380">distributed</span> <span m="401890">denial</span>
  <span m="402220">of</span> <span m="402310">service</span> <span m="402670">attacks.</span></p><p><span
  m="404170">As</span> <span m="404290">a</span> <span m="404350">quick</span> <span
  m="404560">example</span> <span m="405130">of</span> <span m="405310">what</span>
  <span m="405580">happens</span> <span m="406240">in</span> <span m="406420">one</span>
  <span m="406660">of</span> <span m="406750">these</span> <span m="406930">network</span>
  <span m="407260">attacks--</span> <span m="407710">so this</span> <span m="407860">is</span>
  <span m="407970">an</span> <span m="408460">attack,</span> <span m="408820">often,</span>
  <span m="409450">within</span> <span m="409780">the</span> <span m="409870">bucket</span>
  <span m="410290">of</span> <span m="410410">probing</span> <span m="410800">and</span>
  <span m="410890">scanning.</span> <span m="411760">So</span> <span m="411880">essentially,</span>
  <span m="412330">what</span> <span m="412540">happens</span> <span m="412960">is</span>
  <span m="413080">you</span> <span m="413200">have</span> <span m="413380">an</span>
  <span m="413470">attacker</span> <span m="414400">that</span> <span m="414740">attempts</span>
  <span m="415210">to</span> <span m="415930">find</span> <span m="416350">out</span>
  <span m="416530">what</span> <span m="416800">ports</span> <span m="417250">are</span>
  <span m="417400">open</span> <span m="417910">on</span> <span m="418360">a</span>
  <span m="418660">victim</span> <span m="419200">or</span> <span m="419380">a</span>
  <span m="419440">target</span> <span m="419920">system.</span> <span m="421090">It</span>
  <span m="421210">does</span> <span m="421480">this</span> <span m="421690">by</span>
  <span m="421840">sending</span> <span m="422230">requests,</span> <span m="423310">similar</span>
  <span m="423670">to</span> <span m="423790">pings,</span> <span m="424900">to</span>
  <span m="425830">a</span> <span m="426640">victim</span> <span m="427030">or</span>
  <span m="427120">a</span> <span m="427180">target</span> <span m="427570">system.</span>
  <span m="429010">If</span> <span m="429280">the</span> <span m="429610">target's</span>
  <span m="430050">system</span> <span m="430570">acknowledges</span> <span m="431530">one</span>
  <span m="431740">of</span> <span m="431860">these</span> <span m="432100">things,</span>
  <span m="433180">you</span> <span m="433330">can</span> <span m="433510">say,</span>
  <span m="433880">oh,</span> <span m="434360">this</span> <span m="434650">particular</span>
  <span m="435250">port</span> <span m="435640">is</span> <span m="435850">open.</span>
  <span m="436810">And</span> <span m="436990">then,</span> <span m="437230">one</span>
  <span m="437470">may</span> <span m="437710">go</span> <span m="438160">and</span>
  <span m="438370">look</span> <span m="438670">at</span> <span m="439210">what</span>
  <span m="439510">software</span> <span m="440200">typically</span> <span m="440710">runs</span>
  <span m="441100">on</span> <span m="441280">those</span> <span m="441520">ports</span>
  <span m="441970">and</span> <span m="442090">attempt</span> <span m="442420">to</span>
  <span m="442540">use</span> <span m="442750">some</span> <span m="442930">of</span>
  <span m="443020">the</span> <span m="443110">known</span> <span m="443380">vulnerabilities</span>
  <span m="444520">of</span> <span m="444670">that</span> <span m="444880">software.</span></p><p><span
  m="446150">So</span> <span m="446200">a</span> <span m="446230">lot</span> <span
  m="446470">of</span> <span m="446530">software</span> <span m="447040">packages</span>
  <span m="447730">have</span> <span m="448240">specific</span> <span m="448810">ports</span>
  <span m="449290">that</span> <span m="449440">they</span> <span m="449590">tend</span>
  <span m="449830">to</span> <span m="449950">use.</span> <span m="450310">So</span>
  <span m="450430">you</span> <span m="450580">can</span> <span m="450760">say,</span>
  <span m="451510">oh,</span> <span m="451920">you</span> <span m="452020">know,</span>
  <span m="452360">port--</span> <span m="453250">I'm</span> <span m="453760">making</span>
  <span m="454150">up</span> <span m="454270">a</span> <span m="454330">number,</span>
  <span m="454630">here--</span> <span m="454780">port</span> <span m="455080">10,000</span>
  <span m="455680">is</span> <span m="455830">open,</span> <span m="456100">and</span>
  <span m="456220">I</span> <span m="456310">know</span> <span m="456520">that's</span>
  <span m="456760">used</span> <span m="457090">by</span> <span m="458830">Microsoft</span>
  <span m="459580">SQL</span> <span m="460030">server</span> <span m="461020">or</span>
  <span m="461200">any</span> <span m="461440">other</span> <span m="461680">piece</span>
  <span m="461920">of</span> <span m="462010">software.</span> <span m="462820">And</span>
  <span m="462940">then</span> <span m="463060">you</span> <span m="463150">can</span>
  <span m="463300">say,</span> <span m="463450">well,</span> <span m="463600">here</span>
  <span m="463730">is</span> <span m="463900">a</span> <span m="463960">known</span>
  <span m="464200">vulnerability</span> <span m="464950">that</span> <span m="465100">I</span>
  <span m="465220">could</span> <span m="465400">use,</span> <span m="466030">and</span>
  <span m="466150">then</span> <span m="466330">I'll</span> <span m="466450">try</span>
  <span m="466890">attacking</span> <span m="467360">with</span> <span m="467490">that.</span>
  <span m="467870">So</span> <span m="468220">this</span> <span m="468370">is</span>
  <span m="468460">just</span> <span m="469030">a</span> <span m="469090">simple</span>
  <span m="469420">technique</span> <span m="469870">that</span> <span m="470050">a</span>
  <span m="470110">lot</span> <span m="470290">of</span> <span m="470380">attackers</span>
  <span m="470830">use,</span> <span m="471040">very</span> <span m="471310">low</span>
  <span m="471490">bar,</span> <span m="471790">very</span> <span m="472060">easy</span>
  <span m="472360">to</span> <span m="472450">do.</span> <span m="472880">You</span>
  <span m="472930">could</span> <span m="473080">write</span> <span m="473290">one</span>
  <span m="473470">by</span> <span m="473620">mistake.</span> <span m="475270">But</span>
  <span m="475540">just</span> <span m="475780">to</span> <span m="475870">find</span>
  <span m="476230">out</span> <span m="476350">what</span> <span m="476530">ports</span>
  <span m="476890">are</span> <span m="477010">open,</span> <span m="477430">and</span>
  <span m="477610">then</span> <span m="477760">try</span> <span m="477970">to</span>
  <span m="478060">use</span> <span m="479050">known</span> <span m="479410">vulnerabilities</span>
  <span m="479755">on</span> <span m="480100">different ports.</span></p><p><span
  m="482200">Now,</span> <span m="482440">the</span> <span m="482800">least</span>
  <span m="483190">common</span> <span m="483520">denominator,</span> <span m="484030">the</span>
  <span m="484630">easiest</span> <span m="485260">piece</span> <span m="485500">of</span>
  <span m="485620">data</span> <span m="486010">to</span> <span m="486100">collect,</span>
  <span m="486880">is</span> <span m="487060">what's</span> <span m="487270">called</span>
  <span m="487630">the</span> <span m="487750">network</span> <span m="488110">packet.</span>
  <span m="488560">I'm</span> <span m="488680">sure</span> <span m="488860">many</span>
  <span m="489250">of</span> <span m="489370">you</span> <span m="489520">are</span>
  <span m="489640">familiar</span> <span m="490090">with</span> <span m="490240">the</span>
  <span m="490330">concept</span> <span m="490840">of</span> <span m="490960">a</span>
  <span m="491020">network</span> <span m="491350">packet.</span> <span m="492700">For</span>
  <span m="492850">those</span> <span m="493210">that</span> <span m="493330">are</span>
  <span m="493390">not,</span> <span m="493660">think</span> <span m="493930">of</span>
  <span m="494050">if</span> <span m="494170">you're</span> <span m="494290">sending</span>
  <span m="494680">a</span> <span m="494740">letter,</span> <span m="495370">it's</span>
  <span m="495580">all</span> <span m="495910">the</span> <span m="496060">material</span>
  <span m="496630">on</span> <span m="496840">the</span> <span m="496990">envelope.</span>
  <span m="497770">So</span> <span m="497910">it's</span> <span m="498040">the</span>
  <span m="498190">address,</span> <span m="498850">where</span> <span m="499120">it's</span>
  <span m="499300">coming</span> <span m="499600">from,</span> <span m="499930">who</span>
  <span m="500140">it's</span> <span m="500290">going</span> <span m="500590">to,</span>
  <span m="501190">plus</span> <span m="501450">a</span> <span m="501790">little</span>
  <span m="502000">bit</span> <span m="502120">of</span> <span m="502240">information</span>
  <span m="502780">of</span> <span m="502860">sort</span> <span m="503050">of</span>
  <span m="503230">what's</span> <span m="503530">in</span> <span m="503710">the</span>
  <span m="503800">package</span> <span m="504370">as</span> <span m="504550">well.</span></p><p><span
  m="506200">The</span> <span m="506300">reason</span> <span m="506530">that</span>
  <span m="506680">we</span> <span m="506830">often</span> <span m="507160">use</span>
  <span m="507400">network</span> <span m="507790">packets--</span> <span m="509020">and</span>
  <span m="509200">I'll</span> <span m="509380">kind</span> <span m="509530">of</span>
  <span m="509590">open</span> <span m="509830">this</span> <span m="509950">up</span>
  <span m="510070">to</span> <span m="510160">the</span> <span m="510220">class.</span>
  <span m="510760">A</span> <span m="510820">lot</span> <span m="511180">of</span>
  <span m="511270">the</span> <span m="511420">cyber</span> <span m="511840">research</span>
  <span m="512350">actually</span> <span m="512590">focuses</span> <span m="513070">on</span>
  <span m="513190">network</span> <span m="513520">packets,</span> <span m="514539">but</span>
  <span m="515080">those</span> <span m="515620">often</span> <span m="516010">form</span>
  <span m="516370">a</span> <span m="516429">very</span> <span m="516640">small</span>
  <span m="516970">percentage</span> <span m="517450">of</span> <span m="517539">the</span>
  <span m="517659">actual</span> <span m="518020">data,</span> <span m="518260">the</span>
  <span m="518350">payloads,</span> <span m="518890">where</span> <span m="519039">actually</span>
  <span m="519309">a</span> <span m="519370">lot</span> <span m="519549">of</span>
  <span m="519640">the</span> <span m="519730">data</span> <span m="520450">actually</span>
  <span m="520900">is.</span> <span m="521500">Can</span> <span m="521620">anyone</span>
  <span m="521950">guess</span> <span m="522250">why</span> <span m="522490">we</span>
  <span m="522640">tend</span> <span m="522820">to</span> <span m="522970">use</span>
  <span m="523140">a</span> <span m="523169">network</span> <span m="523450">packets</span>
  <span m="523809">rather</span> <span m="524080">than</span> <span m="524230">payloads?</span>
  <span m="525640">Not</span> <span m="525950">Albert?</span></p><p><span m="526240">AUDIENCE:</span>
  <span m="526437">Header.</span></p><p><span m="527470">VIJAY GADEPALLY:</span> <span
  m="527590">Sorry,</span> <span m="527710">the</span> <span m="527800">network</span>
  <span m="528110">header.</span> <span m="528390">Yeah,</span> <span m="528610">sorry</span>
  <span m="528850">the</span> <span m="528970">network</span> <span m="529300">header,</span>
  <span m="529780">not</span> <span m="529960">the</span> <span m="530050">packet,</span>
  <span m="530500">yeah.</span> <span m="532590">So,</span> <span m="532740">Yes.</span>
  <span m="533800">Anyone</span> <span m="534130">guess</span> <span m="534340">why</span>
  <span m="534520">we</span> <span m="534670">tend</span> <span m="534850">to</span>
  <span m="534970">use</span> <span m="535180">the</span> <span m="535270">header</span>
  <span m="535570">rather</span> <span m="535840">than</span> <span m="537220">the</span>
  <span m="537340">payload</span> <span m="537670">of</span> <span m="537760">a</span>
  <span m="537820">packet?</span></p><p><span m="538840">AUDIENCE:</span> <span m="539070">Encrypted.</span></p><p><span
  m="539640">VIJAY GADEPALLY:</span> <span m="539765">Yeah,</span> <span m="539890">encryption,</span>
  <span m="540550">exactly.</span> <span m="541090">So</span> <span m="542740">very</span>
  <span m="543070">often,</span> <span m="543700">especially</span> <span m="544120">these</span>
  <span m="544360">days,</span> <span m="545530">the</span> <span m="545890">payload</span>
  <span m="546340">of</span> <span m="546430">the</span> <span m="546520">packet</span>
  <span m="547060">is</span> <span m="547330">typically</span> <span m="547720">encrypted,</span>
  <span m="548530">so</span> <span m="548680">there's</span> <span m="548890">not</span>
  <span m="549160">too</span> <span m="549310">much</span> <span m="549580">that</span>
  <span m="549730">you</span> <span m="549880">can</span> <span m="550030">do</span>
  <span m="550180">with</span> <span m="550360">it.</span> <span m="550880">So</span>
  <span m="551230">using</span> <span m="551560">the</span> <span m="551650">header</span>
  <span m="551920">information--</span> <span m="552730">the</span> <span m="552820">header</span>
  <span m="553090">is</span> <span m="553240">not,</span> <span m="553570">right?</span>
  <span m="553810">It's</span> <span m="553930">the</span> <span m="554080">outside</span>
  <span m="554470">of</span> <span m="554560">the</span> <span m="554680">envelope.</span>
  <span m="555430">The</span> <span m="555580">inside</span> <span m="555940">of</span>
  <span m="556030">the</span> <span m="556150">envelope</span> <span m="556540">is</span>
  <span m="556630">something</span> <span m="556930">that</span> <span m="557050">you</span>
  <span m="557140">cannot</span> <span m="557440">see</span> <span m="557750">by</span>
  <span m="558250">putting</span> <span m="558550">it</span> <span m="558610">up</span>
  <span m="558700">to</span> <span m="558820">the</span> <span m="558910">light.</span>
  <span m="560140">So</span> <span m="560260">that's</span> <span m="560470">why</span>
  <span m="560590">we</span> <span m="560680">tend</span> <span m="560890">to</span>
  <span m="561010">use</span> <span m="561580">the</span> <span m="561710">header</span>
  <span m="561940">of</span> <span m="562030">the</span> <span m="562120">packet.</span></p><p><span
  m="563060">So</span> <span m="564130">the</span> <span m="564340">headers--</span>
  <span m="565510">so</span> <span m="565660">this</span> <span m="565810">is</span>
  <span m="565930">what</span> <span m="566050">a</span> <span m="566140">packet</span>
  <span m="566500">looks</span> <span m="566770">like,</span> <span m="567320">on</span>
  <span m="567460">the</span> <span m="567550">left.</span> <span m="570010">On</span>
  <span m="570130">the</span> <span m="570220">left</span> <span m="570460">side,</span>
  <span m="570670">that's</span> <span m="570850">what</span> <span m="570940">a</span>
  <span m="571000">packet</span> <span m="571330">looks</span> <span m="571570">like.</span>
  <span m="572170">And</span> <span m="572270">if</span> <span m="572290">you</span>
  <span m="572350">kind</span> <span m="572500">of</span> <span m="572590">convert</span>
  <span m="573010">that</span> <span m="573190">into</span> <span m="573400">a</span>
  <span m="573460">human</span> <span m="573760">readable</span> <span m="574180">form,</span>
  <span m="574840">just</span> <span m="575090">the</span> <span m="575140">header</span>
  <span m="575410">information,</span> <span m="576310">this</span> <span m="576520">is</span>
  <span m="576610">the</span> <span m="576730">type</span> <span m="577000">of</span>
  <span m="577090">data</span> <span m="577390">that</span> <span m="577510">you</span>
  <span m="577630">get</span> <span m="577810">out</span> <span m="577930">of</span>
  <span m="578050">it.</span> <span m="578240">So</span> <span m="578290">it</span>
  <span m="578350">gives</span> <span m="578620">you</span> <span m="579760">things</span>
  <span m="580000">that</span> <span m="580090">you</span> <span m="580180">would</span>
  <span m="580300">expect.</span> <span m="580690">What</span> <span m="580840">was</span>
  <span m="580990">the</span> <span m="581080">IP</span> <span m="581380">address</span>
  <span m="581710">that</span> <span m="581800">I</span> <span m="581900">started</span>
  <span m="582470">from?</span> <span m="582880">What</span> <span m="583060">was</span>
  <span m="583210">a</span> <span m="583270">port</span> <span m="583570">that</span>
  <span m="583720">I</span> <span m="583810">started</span> <span m="584200">from?</span>
  <span m="584710">What</span> <span m="584860">was</span> <span m="585010">the</span>
  <span m="585130">destination</span> <span m="585790">IP</span> <span m="586090">address?</span>
  <span m="586870">What</span> <span m="586990">was</span> <span m="588230">the</span>
  <span m="588340">destination</span> <span m="589000">port?</span> <span m="589660">Plus</span>
  <span m="589870">a</span> <span m="589930">bunch</span> <span m="590170">of</span>
  <span m="590260">other</span> <span m="590470">information</span> <span m="591070">about</span>
  <span m="591310">certain</span> <span m="591580">flags</span> <span m="592000">that</span>
  <span m="592120">were</span> <span m="592240">set,</span> <span m="592670">whether</span>
  <span m="592870">it's</span> <span m="593350">what</span> <span m="593590">direction</span>
  <span m="594070">to</span> <span m="594160">flow--</span> <span m="594670">what</span>
  <span m="594880">direction</span> <span m="595360">the</span> <span m="595450">traffic</span>
  <span m="595810">is</span> <span m="595900">moving</span> <span m="596260">in</span>
  <span m="596440">and</span> <span m="596590">stuff</span> <span m="596890">like</span>
  <span m="597070">that,</span> <span m="597610">and</span> <span m="597700">then</span>
  <span m="597820">any</span> <span m="598030">flags</span> <span m="598420">associated</span>
  <span m="598990">with</span> <span m="599170">it,</span> <span m="599530">what</span>
  <span m="599770">type</span> <span m="600070">of</span> <span m="600160">packet</span>
  <span m="600450">it</span> <span m="600700">is,</span> <span m="601090">so what</span>
  <span m="601270">type</span> <span m="601450">of</span> <span m="601510">protocol</span>
  <span m="601960">is</span> <span m="602080">the</span> <span m="602140">packet</span>
  <span m="602470">using,</span> <span m="602860">et</span> <span m="602920">cetera?</span></p><p><span
  m="604570">All</span> <span m="604630">right,</span> <span m="604780">so</span>
  <span m="604900">just</span> <span m="605110">as</span> <span m="605230">a</span>
  <span m="605260">reminder,</span> <span m="605710">the</span> <span m="605800">data</span>
  <span m="606070">we're</span> <span m="606220">using</span> <span m="606730">is</span>
  <span m="607030">from</span> <span m="607210">the</span> <span m="607270">MAWI</span>
  <span m="607600">working</span> <span m="607990">group,</span> <span m="608620">but</span>
  <span m="608700">there</span> <span m="608830">is</span> <span m="609130">a</span>
  <span m="609190">lot</span> <span m="609430">of</span> <span m="609520">other</span>
  <span m="609760">data</span> <span m="610090">out</span> <span m="610300">there</span>
  <span m="611080">that</span> <span m="611200">you</span> <span m="611320">might</span>
  <span m="611500">be</span> <span m="611590">able</span> <span m="611800">to</span>
  <span m="612250">get</span> <span m="612370">your</span> <span m="612490">hands</span>
  <span m="612820">on.</span> <span m="613640">So</span> <span m="613720">one</span>
  <span m="613960">of</span> <span m="614020">the</span> <span m="614140">challenges,</span>
  <span m="614720">how</span> <span m="614830">many</span> <span m="614980">people</span>
  <span m="615280">here</span> <span m="615580">have</span> <span m="615790">worked</span>
  <span m="616090">in</span> <span m="616180">cybersecurity</span> <span m="616960">or</span>
  <span m="617050">done</span> <span m="617650">some</span> <span m="617920">research</span>
  <span m="618370">in</span> <span m="618490">cybersecurity?</span> <span m="620122">So</span>
  <span m="620490">a</span> <span m="620590">handful</span> <span m="621010">of</span>
  <span m="621070">people.</span></p><p><span m="621790">So</span> <span m="622150">one</span>
  <span m="622330">of</span> <span m="622420">the</span> <span m="622540">huge</span>
  <span m="622990">challenges--</span> <span m="623590">this</span> <span m="623800">is</span>
  <span m="623860">something</span> <span m="624250">that</span> <span m="624400">you</span>
  <span m="624550">may</span> <span m="624700">run</span> <span m="624940">into</span>
  <span m="625360">in</span> <span m="626680">your</span> <span m="626860">data</span>
  <span m="627080">sets--</span> <span m="627820">is</span> <span m="629050">ground</span>
  <span m="629410">truth,</span> <span m="630180">is</span> <span m="630340">understanding</span>
  <span m="631030">when--</span> <span m="631460">So</span> <span m="631590">if</span>
  <span m="631690">you're</span> <span m="631810">trying</span> <span m="631990">to</span>
  <span m="632080">find</span> <span m="632440">out</span> <span m="632650">when</span>
  <span m="632980">there</span> <span m="633130">was</span> <span m="633310">an</span>
  <span m="633430">attack</span> <span m="633790">in</span> <span m="633910">your</span>
  <span m="634000">data,</span> <span m="634840">someone</span> <span m="635200">needs</span>
  <span m="635440">to</span> <span m="635560">have--</span> <span m="635860">you</span>
  <span m="635950">know,</span> <span m="636040">there</span> <span m="636160">needs</span>
  <span m="636370">to</span> <span m="636430">be</span> <span m="636550">some</span>
  <span m="636790">ground</span> <span m="637150">truth</span> <span m="637390">associated</span>
  <span m="637990">with</span> <span m="638150">that.</span> <span m="638710">As</span>
  <span m="638830">much</span> <span m="639070">as</span> <span m="639160">we'd</span>
  <span m="639310">all</span> <span m="639490">love</span> <span m="639760">to</span>
  <span m="639850">sit</span> <span m="640030">and</span> <span m="640120">write</span>
  <span m="640360">DDoS</span> <span m="640840">attacks</span> <span m="641230">and</span>
  <span m="641320">port</span> <span m="641570">scan</span> <span m="641830">attacks</span>
  <span m="642190">on</span> <span m="642280">ourselves,</span> <span m="644110">sometimes,</span>
  <span m="644740">you</span> <span m="644800">know,</span> <span m="644920">getting</span>
  <span m="645190">that at</span> <span m="645520">scale</span> <span m="645850">can</span>
  <span m="646030">be</span> <span m="646120">very</span> <span m="646360">difficult.</span></p><p><span
  m="647300">So</span> <span m="647380">for</span> <span m="647530">the</span> <span
  m="647620">purpose</span> <span m="647950">of</span> <span m="648040">this</span>
  <span m="648310">work,</span> <span m="648580">we</span> <span m="648760">used</span>
  <span m="649150">a</span> <span m="649240">synthetic</span> <span m="649660">data</span>
  <span m="649930">generator,</span> <span m="650770">in</span> <span m="650890">which</span>
  <span m="651070">we</span> <span m="651160">took</span> <span m="651450">real</span>
  <span m="652210">internet</span> <span m="652930">traffic</span> <span m="653410">data</span>
  <span m="654040">but</span> <span m="654250">then</span> <span m="654430">injected</span>
  <span m="655030">synthetic</span> <span m="655430">attacks</span> <span m="655870">into</span>
  <span m="656230">it.</span> <span m="657280">And</span> <span m="657640">that</span>
  <span m="657760">was</span> <span m="657880">sort</span> <span m="658090">of</span>
  <span m="658240">our</span> <span m="658480">way</span> <span m="658930">of</span>
  <span m="659320">looking</span> <span m="659620">for--</span> <span m="659890">of</span>
  <span m="660280">establishing</span> <span m="660850">ground</span> <span m="661180">truth.</span></p><p><span
  m="661940">So</span> <span m="661990">the</span> <span m="662080">MAWI</span> <span
  m="662440">working</span> <span m="662800">group</span> <span m="663010">actually</span>
  <span m="663430">does</span> <span m="663910">published</span> <span m="664580">ground</span>
  <span m="664900">truth</span> <span m="665740">based</span> <span m="666130">on</span>
  <span m="666310">a</span> <span m="666370">number</span> <span m="666610">of</span>
  <span m="666700">detectors</span> <span m="667240">that</span> <span m="667360">they</span>
  <span m="667480">have.</span> <span m="667660">A</span> <span m="667690">lot</span>
  <span m="667870">of</span> <span m="667930">these</span> <span m="668080">are</span>
  <span m="668170">heuristics-based</span> <span m="668950">detectors.</span> <span
  m="670420">In</span> <span m="670780">our</span> <span m="671800">use</span> <span
  m="672070">and</span> <span m="672220">in</span> <span m="672370">our</span> <span
  m="672490">looking</span> <span m="672820">at</span> <span m="673060">that</span>
  <span m="673570">ground</span> <span m="673900">truth,</span> <span m="674150">it</span>
  <span m="674210">was</span> <span m="674350">really</span> <span m="674770">difficult</span>
  <span m="675520">to</span> <span m="675640">actually</span> <span m="675880">understand</span>
  <span m="676480">when</span> <span m="676810">an</span> <span m="676960">attack</span>
  <span m="677290">was</span> <span m="677440">occurring.</span></p><p><span m="678760">It</span>
  <span m="679040">was</span> <span m="679130">sort</span> <span m="679360">of</span>
  <span m="679450">like,</span> <span m="679750">somewhere</span> <span m="680200">in</span>
  <span m="680320">this</span> <span m="680530">hour</span> <span m="680920">an</span>
  <span m="681070">attack</span> <span m="681370">occurred.</span> <span m="682060">Which,</span>
  <span m="682240">if</span> <span m="682330">you're</span> <span m="682420">trying</span>
  <span m="682620">to</span> <span m="682680">train</span> <span m="682930">a</span>
  <span m="682960">machine</span> <span m="683290">learning</span> <span m="683560">classifier</span>
  <span m="684220">on</span> <span m="684370">that</span> <span m="684610">or</span>
  <span m="684820">an</span> <span m="684940">anomaly</span> <span m="685330">detector,</span>
  <span m="686140">that's</span> <span m="686500">kind</span> <span m="686770">of</span>
  <span m="686860">vague.</span> <span m="687430">Because</span> <span m="687880">there's</span>
  <span m="688030">a</span> <span m="688090">lot</span> <span m="688420">happening</span>
  <span m="688870">in</span> <span m="689020">an</span> <span m="689140">hour</span>
  <span m="689440">of</span> <span m="689560">internet</span> <span m="689860">traffic,</span>
  <span m="691010">and</span> <span m="691150">so</span> <span m="691270">if</span>
  <span m="691360">it's</span> <span m="691480">somewhere</span> <span m="691840">in</span>
  <span m="691960">that</span> <span m="692080">hour</span> <span m="692320">an</span>
  <span m="692410">attack</span> <span m="692710">occurred,</span> <span m="693850">that</span>
  <span m="694030">can</span> <span m="694180">be</span> <span m="694270">very</span>
  <span m="694450">difficult</span> <span m="694780">to</span> <span m="694870">find.</span>
  <span m="695240">So</span> <span m="695560">that's</span> <span m="695770">sort</span>
  <span m="695920">of</span> <span m="696010">a</span> <span m="696070">reason</span>
  <span m="696370">that</span> <span m="696490">we</span> <span m="696610">focus</span>
  <span m="696940">on</span> <span m="697030">using</span> <span m="697280">a</span>
  <span m="697330">synthetic</span> <span m="697690">attack</span> <span m="697970">generator.</span>
  <span m="698540">Yeah?</span></p><p><span m="699540">AUDIENCE:</span> <span m="699610">Can</span>
  <span m="699680">you</span> <span m="699750">say</span> <span m="699990">a</span>
  <span m="700060">little</span> <span m="700210">bit</span> <span m="700330">more</span>
  <span m="700540">about</span> <span m="700930">what</span> <span m="701170">kind</span>
  <span m="701590">of</span> <span m="703500">data</span> <span m="704020">gets</span>
  <span m="704380">contracted?</span> <span m="705640">You</span> <span m="705980">know,</span>
  <span m="706400">is</span> <span m="706580">it</span> <span m="706680">just</span>
  <span m="706940">additive,</span> <span m="707500">where</span> <span m="707710">you're</span>
  <span m="709360">showing</span> <span m="709810">some</span> <span m="710320">new</span>
  <span m="710860">compromised</span> <span m="712070">post</span> <span m="712570">that</span>
  <span m="712750">is</span> <span m="713150">injecting</span> <span m="713590">data</span>
  <span m="714090">to</span> <span m="714270">some</span> <span m="714560">destination?</span>
  <span m="715950">Is</span> <span m="716110">there</span> <span m="716260">also,</span>
  <span m="716830">like,</span> <span m="717190">return</span> <span m="717520">flows</span>
  <span m="718000">that</span> <span m="718120">are</span> <span m="718270">in</span>
  <span m="718450">there?</span></p><p><span m="718780">VIJAY GADEPALLY:</span> <span
  m="718845">Yep.</span></p><p><span m="719320">AUDIENCE:</span> <span m="719390">OK.</span></p><p><span
  m="719980">VIJAY GADEPALLY:</span> <span m="720070">Yeah,</span> <span m="720160">so</span>
  <span m="720310">the</span> <span m="720400">question</span> <span m="720790">that</span>
  <span m="720850">was</span> <span m="721000">asked</span> <span m="721330">is,</span>
  <span m="721630">you</span> <span m="721720">know,</span> <span m="722020">I</span>
  <span m="722320">guess,</span> <span m="723220">how</span> <span m="723430">sophisticated</span>
  <span m="724210">is</span> <span m="724390">this</span> <span m="724600">tool,</span>
  <span m="725080">and</span> <span m="725260">how</span> <span m="725950">detailed</span>
  <span m="726520">can</span> <span m="726670">you</span> <span m="726790">do</span>
  <span m="726970">it?</span> <span m="727220">So</span> <span m="727660">the</span>
  <span m="727810">exact</span> <span m="728140">details</span> <span m="728590">of</span>
  <span m="728710">that,</span> <span m="729010">I</span> <span m="729100">would</span>
  <span m="729820">probably</span> <span m="730150">forward</span> <span m="730450">you</span>
  <span m="730540">to</span> <span m="730630">Emily,</span> <span m="731290">but</span>
  <span m="731920">from</span> <span m="732160">looking</span> <span m="732520">at</span>
  <span m="733990">what</span> <span m="734140">was</span> <span m="734320">being</span>
  <span m="734530">done,</span> <span m="735010">these</span> <span m="735220">are</span>
  <span m="735280">reasonably</span> <span m="735820">sophisticated.</span> <span
  m="736510">So</span> <span m="736630">it's</span> <span m="736780">not</span> <span
  m="737020">as</span> <span m="737110">simple</span> <span m="737470">as,</span>
  <span m="737680">you</span> <span m="737800">know,</span> <span m="737920">you</span>
  <span m="738010">have</span> <span m="738130">to</span> <span m="738610">give</span>
  <span m="738820">it</span> <span m="738910">a</span> <span m="738970">text</span>
  <span m="739240">file,</span> <span m="739570">all</span> <span m="739780">the</span>
  <span m="739930">IP</span> <span m="740290">addresses,</span> <span m="740840">source</span>
  <span m="741080">and--</span> <span m="742400">But</span> <span m="742600">you</span>
  <span m="742720">do</span> <span m="742900">have</span> <span m="743020">to</span>
  <span m="743110">set</span> <span m="743290">some</span> <span m="743440">parameters.</span></p><p><span
  m="744020">So</span> <span m="744070">what</span> <span m="744250">you</span> <span
  m="744340">can</span> <span m="744490">do,</span> <span m="744740">for</span> <span
  m="744790">example,</span> <span m="745460">if</span> <span m="745540">it's</span>
  <span m="745690">a</span> <span m="745750">DDoS</span> <span m="746200">attack--</span>
  <span m="746650">right,</span> <span m="746920">that's</span> <span m="747310">maybe</span>
  <span m="747580">the</span> <span m="747700">easiest</span> <span m="748090">one</span>
  <span m="748270">to</span> <span m="748390">describe--</span> <span m="749140">is</span>
  <span m="749320">you</span> <span m="749410">would</span> <span m="749560">give</span>
  <span m="750070">maybe</span> <span m="750390">a</span> <span m="750450">range</span>
  <span m="751030">of</span> <span m="751480">IP</span> <span m="751780">addresses</span>
  <span m="752330">and</span> <span m="752350">ports</span> <span m="752740">that</span>
  <span m="752860">you'd</span> <span m="753010">like</span> <span m="753190">to</span>
  <span m="753310">see</span> <span m="753610">injected,</span> <span m="754490">you'd</span>
  <span m="754660">give</span> <span m="754870">it</span> <span m="755200">a</span>
  <span m="755440">flow</span> <span m="756040">rate,</span> <span m="756640">and</span>
  <span m="756760">then</span> <span m="756910">you</span> <span m="757030">could</span>
  <span m="757180">tell</span> <span m="757420">it</span> <span m="757660">what</span>
  <span m="757870">type</span> <span m="758140">of</span> <span m="758260">packets</span>
  <span m="758740">you'd</span> <span m="758890">like</span> <span m="759070">introduced.</span>
  <span m="759550">And</span> <span m="759740">it</span> <span m="759880">sort</span>
  <span m="760060">of</span> <span m="760450">allows</span> <span m="760720">you</span>
  <span m="760780">to</span> <span m="760870">do</span> <span m="761350">a</span>
  <span m="761440">number</span> <span m="761740">of</span> <span m="761830">these</span>
  <span m="762070">different--</span> <span m="763210">this</span> <span m="763450">particular</span>
  <span m="763960">tool</span> <span m="764260">at</span> <span m="764350">least--</span>
  <span m="764830">allows</span> <span m="765130">you</span> <span m="765190">to</span>
  <span m="765550">pick</span> <span m="765790">a</span> <span m="765850">number</span>
  <span m="766090">of</span> <span m="766210">these</span> <span m="766390">different</span>
  <span m="766660">features</span> <span m="767380">that</span> <span m="767530">it</span>
  <span m="767620">then</span> <span m="767800">injects</span> <span m="768300">into</span>
  <span m="768790">the</span> <span m="769000">original</span> <span m="769255">pcap</span>
  <span m="770020">file.</span></p><p><span m="771370">If</span> <span m="771520">you're</span>
  <span m="771640">looking</span> <span m="771880">for</span> <span m="772030">some</span>
  <span m="772270">of</span> <span m="772390">the</span> <span m="772600">other</span>
  <span m="772930">attacks--</span> <span m="773340">so</span> <span m="773410">this</span>
  <span m="773590">is</span> <span m="773680">just</span> <span m="774250">a</span>
  <span m="774310">list</span> <span m="774640">of</span> <span m="774730">the</span>
  <span m="774850">attacks</span> <span m="775330">that</span> <span m="776380">they</span>
  <span m="776500">currently</span> <span m="776920">support,</span> <span m="777400">as</span>
  <span m="777610">of</span> <span m="778030">a</span> <span m="778120">few</span>
  <span m="778330">months</span> <span m="778600">ago,</span> <span m="778810">and</span>
  <span m="779080">they</span> <span m="779200">might</span> <span m="779380">be</span>
  <span m="779530">adding</span> <span m="779800">to</span> <span m="779920">this.</span>
  <span m="781110">You</span> <span m="781170">know,</span> <span m="781270">we</span>
  <span m="781390">focus</span> <span m="781780">on</span> <span m="781870">a</span>
  <span m="781930">few</span> <span m="782200">of</span> <span m="782350">these</span>
  <span m="783110">that</span> <span m="783850">were</span> <span m="784030">also</span>
  <span m="784300">easy</span> <span m="784570">for</span> <span m="784720">us</span>
  <span m="784870">to</span> <span m="784960">reason</span> <span m="785320">and,</span>
  <span m="785410">kind</span> <span m="785620">of,</span> <span m="785680">go</span>
  <span m="785890">back</span> <span m="786130">into</span> <span m="786430">the</span>
  <span m="786580">actual</span> <span m="786940">data</span> <span m="787240">that</span>
  <span m="787360">we</span> <span m="787480">collected</span> <span m="787900">to</span>
  <span m="788020">see</span> <span m="788320">if</span> <span m="788470">the</span>
  <span m="788650">actual</span> <span m="789670">injection</span> <span m="790600">made</span>
  <span m="790870">sense</span> <span m="791260">to</span> <span m="791440">us</span>
  <span m="791590">or</span> <span m="791710">not.</span> <span m="792770">But</span>
  <span m="792850">we</span> <span m="792970">do</span> <span m="793120">have</span>
  <span m="793270">a</span> <span m="793330">number</span> <span m="793540">of</span>
  <span m="793600">different</span> <span m="793870">parameters</span> <span m="794380">that</span>
  <span m="795070">you</span> <span m="795160">could</span> <span m="795310">pick</span>
  <span m="796630">when</span> <span m="796780">you're</span> <span m="796900">doing</span>
  <span m="797140">that.</span></p><p><span m="798770">So</span> <span m="799120">that's</span>
  <span m="799360">just</span> <span m="799540">a</span> <span m="799570">little</span>
  <span m="799810">bit--</span> <span m="800080">You</span> <span m="800160">know,</span>
  <span m="800290">as</span> <span m="800410">we</span> <span m="800500">talked</span>
  <span m="800770">about,</span> <span m="800980">in</span> <span m="801070">the</span>
  <span m="801160">data</span> <span m="801400">conditioning</span> <span m="801910">phase</span>
  <span m="802210">of</span> <span m="802270">the</span> <span m="802330">labeling</span>
  <span m="802780">data,</span> <span m="803320">is</span> <span m="803470">often</span>
  <span m="803770">a</span> <span m="803830">pretty</span> <span m="804070">difficult</span>
  <span m="804460">process.</span> <span m="805630">In</span> <span m="805780">the</span>
  <span m="805870">world</span> <span m="806260">of</span> <span m="806350">cyber</span>
  <span m="807130">anomaly,</span> <span m="807640">in</span> <span m="807820">the</span>
  <span m="807880">world</span> <span m="808150">of</span> <span m="808270">network</span>
  <span m="809230">packets</span> <span m="809630">and</span> <span m="809710">network</span>
  <span m="809980">security,</span> <span m="810820">going</span> <span m="811180">back</span>
  <span m="811540">and</span> <span m="811630">trying</span> <span m="811900">to</span>
  <span m="812020">label</span> <span m="812440">is</span> <span m="812590">an</span>
  <span m="812680">extremely</span> <span m="813640">time</span> <span m="813880">consuming</span>
  <span m="814360">task</span> <span m="814780">and</span> <span m="814930">very</span>
  <span m="815200">difficult</span> <span m="815710">and</span> <span m="815920">up</span>
  <span m="816070">to</span> <span m="816190">a</span> <span m="816250">lot</span>
  <span m="816430">of</span> <span m="816520">interpretation</span> <span m="817300">as</span>
  <span m="817450">to</span> <span m="817570">what</span> <span m="817990">one</span>
  <span m="818650">calls</span> <span m="819220">an</span> <span m="819550">attack.</span>
  <span m="820270">So</span> <span m="820780">while</span> <span m="820990">we</span>
  <span m="821110">did</span> <span m="821350">manually</span> <span m="821920">inspect</span>
  <span m="822730">a</span> <span m="822820">few</span> <span m="823090">of</span>
  <span m="823210">these,</span> <span m="823810">and</span> <span m="823900">that's</span>
  <span m="824080">certainly</span> <span m="824440">not</span> <span m="824650">scalable.</span>
  <span m="825260">So</span> <span m="825580">we</span> <span m="825730">decided</span>
  <span m="826120">to</span> <span m="826210">go</span> <span m="826360">with</span>
  <span m="826530">a</span> <span m="826570">synthetic</span> <span m="826960">attack</span>
  <span m="827260">generator.</span> <span m="827630">And</span> <span m="827710">I'm</span>
  <span m="827800">sure</span> <span m="827950">for some</span> <span m="828160">of</span>
  <span m="828250">your</span> <span m="828400">projects,</span> <span m="828880">you</span>
  <span m="828970">may</span> <span m="829120">also</span> <span m="829420">kind</span>
  <span m="829570">of</span> <span m="829660">think</span> <span m="829870">about</span>
  <span m="831130">is</span> <span m="831340">that</span> <span m="831700">a</span>
  <span m="831910">route</span> <span m="832390">that</span> <span m="832510">you</span>
  <span m="832630">need</span> <span m="832810">to</span> <span m="832930">take,</span>
  <span m="833320">at</span> <span m="833440">least</span> <span m="833670">to</span>
  <span m="833770">start</span> <span m="834040">off</span> <span m="834250">with.</span></p><p><span
  m="836480">OK,</span> <span m="836780">so</span> <span m="836930">this</span> <span
  m="837110">is</span> <span m="837230">the</span> <span m="837350">overall</span>
  <span m="837770">pipeline</span> <span m="838220">of</span> <span m="838340">the</span>
  <span m="838430">system.</span> <span m="839220">So</span> <span m="839450">as</span>
  <span m="839570">I</span> <span m="839660">mentioned</span> <span m="840570">the</span>
  <span m="840670">first</span> <span m="840800">time</span> <span m="840980">we</span>
  <span m="841070">chatted,</span> <span m="841730">we</span> <span m="841880">spent</span>
  <span m="842120">a</span> <span m="842180">majority</span> <span m="842690">of</span>
  <span m="842810">our</span> <span m="842900">time</span> <span m="843260">in</span>
  <span m="843350">the</span> <span m="843680">first</span> <span m="843980">step</span>
  <span m="845570">here,</span> <span m="845780">which</span> <span m="846950">is</span>
  <span m="847100">data</span> <span m="847370">conditioning.</span> <span m="850460">So</span>
  <span m="850610">within</span> <span m="850910">data</span> <span m="851180">conditioning,</span>
  <span m="851810">we</span> <span m="851990">did,</span> <span m="852770">you</span>
  <span m="852920">know,</span> <span m="853010">taking</span> <span m="853400">the</span>
  <span m="853490">raw</span> <span m="853730">data,</span> <span m="854000">which</span>
  <span m="854130">is</span> <span m="854240">downloading</span> <span m="854720">this</span>
  <span m="854870">from</span> <span m="855020">the</span> <span m="855170">internet.</span>
  <span m="856310">This</span> <span m="856550">comes</span> <span m="856820">to</span>
  <span m="856880">you</span> <span m="856970">in</span> <span m="857030">a</span>
  <span m="857090">binary</span> <span m="857630">format,</span> <span m="858390">which</span>
  <span m="858440">is</span> <span m="858560">a</span> <span m="858800">pcap.</span>
  <span m="859340">For</span> <span m="859460">those</span> <span m="859670">who</span>
  <span m="859730">are</span> <span m="859790">familiar</span> <span m="860120">with</span>
  <span m="860240">packet</span> <span m="860540">capture</span> <span m="861470">outputs,</span>
  <span m="861920">that's</span> <span m="862060">that</span> <span m="862280">binary</span>
  <span m="862670">format</span> <span m="863090">that</span> <span m="863180">comes</span>
  <span m="863420">from,</span> <span m="863540">like,</span> <span m="863850">tcpdump,</span>
  <span m="864320">for</span> <span m="864470">example.</span> <span m="865820">We</span>
  <span m="866000">then</span> <span m="866210">convert</span> <span m="866810">that</span>
  <span m="867020">pcap</span> <span m="867440">file</span> <span m="867860">into</span>
  <span m="868070">flows,</span> <span m="869080">parse</span> <span m="869550">that</span>
  <span m="869740">into</span> <span m="869990">human</span> <span m="870260">readable</span>
  <span m="870620">form,</span> <span m="871700">feature</span> <span m="872120">engineer,</span>
  <span m="873170">training</span> <span m="873430">machine</span> <span m="873680">learning</span>
  <span m="873950">classifier,</span> <span m="875030">do</span> <span m="875180">the</span>
  <span m="875270">same</span> <span m="875510">thing</span> <span m="875660">with</span>
  <span m="875780">the</span> <span m="875840">synthetic</span> <span m="876290">data,</span>
  <span m="877310">and</span> <span m="877430">then</span> <span m="878090">get</span>
  <span m="878690">good</span> <span m="878900">results.</span> <span m="880090">Or</span>
  <span m="880430">we</span> <span m="880520">hope</span> <span m="880700">that you</span>
  <span m="881015">get good</span> <span m="881330">results.</span></p><p><span m="883040">So</span>
  <span m="883520">step</span> <span m="883820">one</span> <span m="883990">of</span>
  <span m="884120">data</span> <span m="884330">conditioning</span> <span m="884780">was</span>
  <span m="884960">to</span> <span m="885150">download</span> <span m="885620">the</span>
  <span m="885740">actual</span> <span m="886130">raw</span> <span m="886370">data.</span>
  <span m="887420">The</span> <span m="887510">data</span> <span m="887810">was</span>
  <span m="888070">downloaded</span> <span m="888590">in</span> <span m="888710">a</span>
  <span m="888920">compressed</span> <span m="889380">binary</span> <span m="889820">format,</span>
  <span m="890600">which</span> <span m="890780">is</span> <span m="890870">probably</span>
  <span m="891200">what</span> <span m="891350">a</span> <span m="891410">lot</span>
  <span m="891620">of</span> <span m="891710">you</span> <span m="891800">will</span>
  <span m="891920">get</span> <span m="892070">your</span> <span m="892190">hands</span>
  <span m="892490">on.</span> <span m="892985">A</span> <span m="893240">typical</span>
  <span m="893660">size</span> <span m="894170">of</span> <span m="894320">a</span>
  <span m="894380">single</span> <span m="895640">zip</span> <span m="895940">file</span>
  <span m="896330">or</span> <span m="896450">typical</span> <span m="896780">compressed</span>
  <span m="897140">file is</span> <span m="897470">about</span> <span m="897680">two</span>
  <span m="898220">and</span> <span m="898310">a</span> <span m="898370">half</span>
  <span m="898580">gig.</span> <span m="899390">When</span> <span m="899570">you</span>
  <span m="899930">decompress</span> <span m="900560">that,</span> <span m="900740">it</span>
  <span m="900830">goes</span> <span m="901070">to</span> <span m="901160">about</span>
  <span m="901430">10</span> <span m="901730">gigs,</span> <span m="902060">so about</span>
  <span m="902270">4</span> <span m="902640">x.</span> <span m="903290">And</span>
  <span m="903740">a</span> <span m="904070">single</span> <span m="904520">pcap</span>
  <span m="904970">file</span> <span m="905360">corresponds</span> <span m="906050">to--</span>
  <span m="906200">so</span> <span m="906450">it's</span> <span m="906710">about</span>
  <span m="906920">10</span> <span m="907190">gigs</span> <span m="907430">for</span>
  <span m="907610">about</span> <span m="907880">15</span> <span m="908330">minutes</span>
  <span m="908690">worth</span> <span m="908900">of</span> <span m="908990">traffic.</span></p><p><span
  m="910410">So</span> <span m="910460">if</span> <span m="910550">you're</span> <span
  m="910640">trying</span> <span m="910820">to</span> <span m="910910">do</span> <span
  m="911030">multiple</span> <span m="911510">days,</span> <span m="911840">you</span>
  <span m="911930">can</span> <span m="912050">imagine</span> <span m="912500">how</span>
  <span m="912740">this</span> <span m="912890">starts</span> <span m="913370">to</span>
  <span m="913490">explode</span> <span m="913910">in</span> <span m="914000">terms</span>
  <span m="914270">of</span> <span m="914330">volume.</span> <span m="915320">And</span>
  <span m="915950">about</span> <span m="916220">15</span> <span m="916640">minutes,</span>
  <span m="917810">on</span> <span m="918050">average,</span> <span m="918560">is</span>
  <span m="918680">about</span> <span m="918980">150,000</span> <span m="919460">pack--</span>
  <span m="920420">it</span> <span m="920570">corresponds</span> <span m="921170">to</span>
  <span m="921230">about</span> <span m="921390">150,000</span> <span m="922250">packets</span>
  <span m="922610">per</span> <span m="922730">second.</span> <span m="923580">So</span>
  <span m="923860">this</span> <span m="924050">a</span> <span m="924080">reasonable</span>
  <span m="924500">amount</span> <span m="924740">of</span> <span m="924800">network</span>
  <span m="925100">traffic</span> <span m="925490">that</span> <span m="925640">we're</span>
  <span m="925760">getting</span> <span m="925960">our</span> <span m="926090">hands</span>
  <span m="926360">on,</span> <span m="926810">but</span> <span m="927230">not</span>
  <span m="927530">even</span> <span m="927740">close</span> <span m="928100">to</span>
  <span m="928220">the</span> <span m="928310">types</span> <span m="928580">of</span>
  <span m="928670">volume</span> <span m="929090">that</span> <span m="929240">large</span>
  <span m="929510">scale</span> <span m="929780">providers</span> <span m="930320">have</span>
  <span m="930440">to</span> <span m="930530">deal</span> <span m="930740">with</span>
  <span m="930890">on</span> <span m="930980">a</span> <span m="931010">regular</span>
  <span m="931370">basis.</span></p><p><span m="932540">Once</span> <span m="932810">we</span>
  <span m="932900">have</span> <span m="933110">the</span> <span m="933260">actual--</span>
  <span m="934590">once</span> <span m="934850">we</span> <span m="934970">have</span>
  <span m="935790">the</span> <span m="936020">pcap</span> <span m="936470">file</span>
  <span m="936860">downloaded,</span> <span m="937760">just</span> <span m="938000">the</span>
  <span m="938090">network</span> <span m="938450">packets</span> <span m="938960">don't</span>
  <span m="939200">really</span> <span m="939500">tell</span> <span m="939740">us</span>
  <span m="939890">much.</span> <span m="940100">It's</span> <span m="940230">stuff</span>
  <span m="940490">to</span> <span m="940580">do</span> <span m="940760">things</span>
  <span m="941060">with.</span> <span m="941510">So</span> <span m="941670">what</span>
  <span m="941780">we</span> <span m="941870">want</span> <span m="942050">to</span>
  <span m="942140">do</span> <span m="942290">is</span> <span m="942410">convert</span>
  <span m="942860">this</span> <span m="943040">into</span> <span m="943220">a</span>
  <span m="943280">representation</span> <span m="944420">that's</span> <span m="944930">useful</span>
  <span m="945350">to</span> <span m="945470">do</span> <span m="945620">analysis.</span>
  <span m="946520">And</span> <span m="946640">so</span> <span m="947270">a</span>
  <span m="947330">lot</span> <span m="947600">of</span> <span m="947690">work</span>
  <span m="947960">has</span> <span m="948080">been</span> <span m="948230">done</span>
  <span m="948470">using</span> <span m="948770">network</span> <span m="949150">flows.</span>
  <span m="949940">And</span> <span m="950300">a</span> <span m="950360">network</span>
  <span m="950690">flow</span> <span m="950890">is,</span> <span m="951020">essentially,</span>
  <span m="951530">a</span> <span m="951650">sequence</span> <span m="952280">of</span>
  <span m="953000">packets</span> <span m="953630">from</span> <span m="953840">a</span>
  <span m="953900">single</span> <span m="954200">source</span> <span m="954500">to</span>
  <span m="954620">destination.</span></p><p><span m="955250">So</span> <span m="955340">as</span>
  <span m="955460">you</span> <span m="955550">can</span> <span m="955700">imagine,</span>
  <span m="956420">when</span> <span m="956570">you're</span> <span m="956750">streaming</span>
  <span m="957260">a</span> <span m="957350">YouTube</span> <span m="957740">video,</span>
  <span m="958290">for</span> <span m="958370">example,</span> <span m="959270">it's</span>
  <span m="959480">not</span> <span m="959780">one</span> <span m="960110">big</span>
  <span m="960320">packet</span> <span m="960770">that</span> <span m="960920">comes</span>
  <span m="961220">to</span> <span m="961280">you,</span> <span m="961370">but</span>
  <span m="961490">it's</span> <span m="961670">a</span> <span m="961730">series</span>
  <span m="962360">of</span> <span m="962480">packets.</span> <span m="963650">And</span>
  <span m="963860">so</span> <span m="964160">flow</span> <span m="964580">essentially</span>
  <span m="965030">tries</span> <span m="965390">to</span> <span m="965930">detect</span>
  <span m="966350">that</span> <span m="966680">and</span> <span m="966800">say,</span>
  <span m="967370">OK,</span> <span m="967700">all</span> <span m="967940">of</span>
  <span m="968030">these</span> <span m="968270">things</span> <span m="968600">was</span>
  <span m="969230">a</span> <span m="969290">person</span> <span m="969680">watching</span>
  <span m="970250">this</span> <span m="970460">video.</span> <span m="970820">Right?</span>
  <span m="970990">So</span> <span m="971080">from</span> <span m="971210">this</span>
  <span m="971330">source</span> <span m="971660">to</span> <span m="971750">this</span>
  <span m="971930">destination</span> <span m="972740">within</span> <span m="973040">some</span>
  <span m="973280">time</span> <span m="973580">window</span> <span m="974000">is</span>
  <span m="974150">defined</span> <span m="974510">as</span> <span m="974620">a</span>
  <span m="974690">network</span> <span m="975030">flow.</span></p><p><span m="976350">And</span>
  <span m="976460">so</span> <span m="976580">we</span> <span m="976700">convert</span>
  <span m="977060">each</span> <span m="977240">of</span> <span m="977330">these</span>
  <span m="977480">15</span> <span m="977870">minute</span> <span m="978190">pcap</span>
  <span m="978590">files</span> <span m="979730">into</span> <span m="980300">network</span>
  <span m="980690">flow</span> <span m="980840">representation</span> <span m="981710">using</span>
  <span m="982220">a</span> <span m="982340">tool</span> <span m="982580">called</span>
  <span m="982820">yaf,</span> <span m="983930">which</span> <span m="984140">stands</span>
  <span m="984470">for</span> <span m="984620">yet</span> <span m="984860">another</span>
  <span m="985130">flow</span> <span m="985400">meter.</span> <span m="986460">And</span>
  <span m="986510">so</span> <span m="986660">that</span> <span m="987080">helps</span>
  <span m="987350">us</span> <span m="987500">do</span> <span m="987710">some</span>
  <span m="987950">of</span> <span m="988070">this</span> <span m="989000">flow--</span>
  <span m="989780">establishing</span> <span m="990410">these</span> <span m="990560">network</span>
  <span m="990890">flows.</span> <span m="991800">And</span> <span m="991850">so</span>
  <span m="992000">the</span> <span m="992090">size</span> <span m="992450">of</span>
  <span m="992540">about</span> <span m="992810">15</span> <span m="993230">minutes</span>
  <span m="993560">worth</span> <span m="993800">of</span> <span m="993860">flows</span>
  <span m="994760">goes</span> <span m="995000">to</span> <span m="995120">about</span>
  <span m="995390">two</span> <span m="995600">gigabytes,</span> <span m="996560">and</span>
  <span m="997730">we</span> <span m="997940">set a</span> <span m="998360">time</span>
  <span m="998720">out</span> <span m="998930">of</span> <span m="999080">flow</span>
  <span m="999470">to</span> <span m="999620">be</span> <span m="999740">about</span>
  <span m="999980">five</span> <span m="1000280">minutes.</span></p><p><span m="1001990">OK,</span>
  <span m="1002290">once</span> <span m="1002560">we</span> <span m="1002680">have</span>
  <span m="1002920">the</span> <span m="1003040">flows,</span> <span m="1003730">they're</span>
  <span m="1003970">still</span> <span m="1004570">in</span> <span m="1004690">this</span>
  <span m="1004870">binary</span> <span m="1005290">format.</span> <span m="1005740">We</span>
  <span m="1005860">need</span> <span m="1006010">to</span> <span m="1006100">now</span>
  <span m="1006310">convert</span> <span m="1006700">them</span> <span m="1006910">into</span>
  <span m="1007420">a</span> <span m="1007990">representation</span> <span m="1008830">that</span>
  <span m="1008950">we</span> <span m="1009100">can</span> <span m="1009250">look</span>
  <span m="1009460">at.</span> <span m="1009880">So</span> <span m="1010270">flow</span>
  <span m="1010630">comes</span> <span m="1010960">with</span> <span m="1011140">an</span>
  <span m="1011230">ASCII</span> <span m="1011650">converter</span> <span m="1012130">called</span>
  <span m="1012370">the</span> <span m="1012430">yafscii--</span> <span m="1013480">Sorry,</span>
  <span m="1013690">yaf</span> <span m="1014050">comes</span> <span m="1014320">with</span>
  <span m="1014470">the</span> <span m="1015190">ASCII</span> <span m="1015550">converter</span>
  <span m="1015940">called</span> <span m="1016280">yafscii,</span> <span m="1017920">and</span>
  <span m="1018130">that</span> <span m="1018400">essentially</span> <span m="1018910">converts</span>
  <span m="1019990">the</span> <span m="1020110">data</span> <span m="1020770">from</span>
  <span m="1021010">this</span> <span m="1021160">floor</span> <span m="1021370">representation</span>
  <span m="1022090">into</span> <span m="1022330">a</span> <span m="1022390">tabular</span>
  <span m="1022930">form.</span></p><p><span m="1023920">And</span> <span m="1024190">if</span>
  <span m="1024339">there's</span> <span m="1024550">one</span> <span m="1024760">lesson</span>
  <span m="1025150">that</span> <span m="1025300">I</span> <span m="1025359">think</span>
  <span m="1025569">Jeremy</span> <span m="1025960">will</span> <span m="1026079">talk</span>
  <span m="1026319">to</span> <span m="1026410">you</span> <span m="1026500">a</span>
  <span m="1026530">lot</span> <span m="1026770">about</span> <span m="1027040">next,</span>
  <span m="1027369">it is</span> <span m="1027670">tables,</span> <span m="1028089">tables,</span>
  <span m="1028450">tables.</span> <span m="1029109">People</span> <span m="1029410">love</span>
  <span m="1029710">looking</span> <span m="1030010">at</span> <span m="1030069">tabular</span>
  <span m="1030550">data,</span> <span m="1031220">it's</span> <span m="1031270">very</span>
  <span m="1031690">easy</span> <span m="1031930">to</span> <span m="1032050">understand.</span>
  <span m="1033010">I</span> <span m="1033099">wouldn't</span> <span m="1033310">recommend</span>
  <span m="1033760">it,</span> <span m="1033950">but</span> <span m="1034000">you</span>
  <span m="1034119">could</span> <span m="1034329">open</span> <span m="1034569">this</span>
  <span m="1034720">up</span> <span m="1034869">in</span> <span m="1034960">Excel.</span>
  <span m="1035960">It would be</span> <span m="1036450">huge,</span> <span m="1037780">but</span>
  <span m="1037960">it</span> <span m="1038440">would</span> <span m="1038589">open</span>
  <span m="1038890">up.</span> <span m="1039069">But</span> <span m="1039190">it's</span>
  <span m="1039490">very</span> <span m="1039760">easy</span> <span m="1040060">to,</span>
  <span m="1040480">kind</span> <span m="1040660">of,</span> <span m="1040720">look</span>
  <span m="1040960">at,</span> <span m="1041410">especially</span> <span m="1041770">when</span>
  <span m="1041890">we're</span> <span m="1042010">trying</span> <span m="1042190">to</span>
  <span m="1042280">establish</span> <span m="1042849">truth</span> <span m="1043240">in</span>
  <span m="1043329">the</span> <span m="1043420">data</span> <span m="1043819">and</span>
  <span m="1043950">go</span> <span m="1044140">back</span> <span m="1044410">and</span>
  <span m="1044500">take</span> <span m="1044680">a</span> <span m="1044740">look</span>
  <span m="1044950">at</span> <span m="1045040">it.</span></p><p><span m="1045700">So</span>
  <span m="1046540">for</span> <span m="1046780">our</span> <span m="1046930">pipeline,</span>
  <span m="1047440">we</span> <span m="1047560">take</span> <span m="1047800">the</span>
  <span m="1048210">yaf</span> <span m="1048550">files,</span> <span m="1048930">convert</span>
  <span m="1049200">them</span> <span m="1049320">into</span> <span m="1049480">text</span>
  <span m="1049750">files.</span> <span m="1050720">Each</span> <span m="1050800">of</span>
  <span m="1050890">these</span> <span m="1051070">ASCII</span> <span m="1051490">tables,</span>
  <span m="1051820">so</span> <span m="1051930">again,</span> <span m="1052090">about</span>
  <span m="1052300">15</span> <span m="1052660">minutes</span> <span m="1052900">worth</span>
  <span m="1053080">of</span> <span m="1053170">data,</span> <span m="1053530">is
  about</span> <span m="1053770">eight</span> <span m="1053950">gigabytes</span> <span
  m="1054430">in</span> <span m="1054550">size.</span> <span m="1056050">And</span>
  <span m="1056200">we</span> <span m="1056770">record</span> <span m="1057130">a</span>
  <span m="1057160">number</span> <span m="1057490">of</span> <span m="1057850">different</span>
  <span m="1058330">data</span> <span m="1058570">pieces</span> <span m="1058960">per</span>
  <span m="1059080">flow.</span> <span m="1059620">I</span> <span m="1059800">won't</span>
  <span m="1059890">go</span> <span m="1059980">into</span> <span m="1060130">the</span>
  <span m="1060220">details,</span> <span m="1060730">but</span> <span m="1060880">if</span>
  <span m="1060970">you're</span> <span m="1061120">interested,</span> <span m="1061670">you</span>
  <span m="1061690">can</span> <span m="1061810">kind</span> <span m="1062080">of</span>
  <span m="1062200">look</span> <span m="1062470">at</span> <span m="1063790">what</span>
  <span m="1063970">are</span> <span m="1064090">the</span> <span m="1064660">various</span>
  <span m="1065170">entities</span> <span m="1065800">or</span> <span m="1065920">features</span>
  <span m="1066550">that</span> <span m="1066700">come</span> <span m="1066910">up</span>
  <span m="1067110">in</span> <span m="1067240">a</span> <span m="1067330">network</span>
  <span m="1067720">flow?</span></p><p><span m="1069640">So</span> <span m="1069760">now</span>
  <span m="1069910">that</span> <span m="1070060">we</span> <span m="1070210">have</span>
  <span m="1070420">network</span> <span m="1070840">flows,</span> <span m="1071830">that's</span>
  <span m="1073020">sort</span> <span m="1073240">of</span> <span m="1073390">like</span>
  <span m="1073870">part</span> <span m="1074230">one</span> <span m="1074500">of</span>
  <span m="1074590">data</span> <span m="1074880">conditioning,</span> <span m="1075370">right?</span>
  <span m="1075550">We've</span> <span m="1075730">converted</span> <span m="1076180">it</span>
  <span m="1076270">into</span> <span m="1076420">some</span> <span m="1076630">representation</span>
  <span m="1077410">that</span> <span m="1077530">makes</span> <span m="1077740">sense.</span>
  <span m="1078370">We</span> <span m="1078520">have it</span> <span m="1078790">in</span>
  <span m="1078850">human</span> <span m="1079180">readable</span> <span m="1079570">form.</span>
  <span m="1080320">So,</span> <span m="1080590">step</span> <span m="1080890">one</span>
  <span m="1081130">data</span> <span m="1081340">conditioning</span> <span m="1081790">done.</span></p><p><span
  m="1082360">Now,</span> <span m="1082540">the</span> <span m="1082660">next</span>
  <span m="1082930">thing</span> <span m="1083140">is</span> <span m="1083290">to</span>
  <span m="1083380">convert</span> <span m="1083740">it</span> <span m="1083800">into</span>
  <span m="1083980">something</span> <span m="1084340">that</span> <span m="1084490">actually</span>
  <span m="1084850">makes</span> <span m="1085120">sense</span> <span m="1085540">for</span>
  <span m="1085720">our</span> <span m="1085780">machine</span> <span m="1086140">learning</span>
  <span m="1086440">algorithm.</span> <span m="1087470">And</span> <span m="1087490">so</span>
  <span m="1087640">this</span> <span m="1087820">is</span> <span m="1088190">sort</span>
  <span m="1088420">of</span> <span m="1088490">bucketing</span> <span m="1088960">into</span>
  <span m="1089170">the</span> <span m="1089320">area</span> <span m="1089650">of</span>
  <span m="1089710">feature</span> <span m="1090100">engineering,</span> <span m="1091000">when</span>
  <span m="1091180">we</span> <span m="1091270">kind</span> <span m="1091450">of</span>
  <span m="1091540">think</span> <span m="1091750">back</span> <span m="1092050">at</span>
  <span m="1092335">it.</span> <span m="1092620">And</span> <span m="1092950">so</span>
  <span m="1093190">feature</span> <span m="1093520">engineering</span> <span m="1094060">is</span>
  <span m="1094270">really,</span> <span m="1094970">really</span> <span m="1095170">important.</span>
  <span m="1096470">You'll</span> <span m="1096520">spend</span> <span m="1096760">a</span>
  <span m="1096820">lot</span> <span m="1097030">of</span> <span m="1097090">time</span>
  <span m="1097360">doing</span> <span m="1097660">this</span> <span m="1097990">on</span>
  <span m="1098260">new</span> <span m="1098410">data</span> <span m="1098670">sets.</span></p><p><span
  m="1099560">And</span> <span m="1099700">so,</span> <span m="1099910">each</span>
  <span m="1100120">of</span> <span m="1100210">these</span> <span m="1100390">flows</span>
  <span m="1100810">contains</span> <span m="1101230">about</span> <span m="1101440">21</span>
  <span m="1101950">different</span> <span m="1102250">features.</span> <span m="1103220">And</span>
  <span m="1103510">one</span> <span m="1103720">of</span> <span m="1103840">the--</span>
  <span m="1104260">we</span> <span m="1104350">need</span> <span m="1104500">to</span>
  <span m="1104620">look</span> <span m="1104830">for</span> <span m="1104980">essentially</span>
  <span m="1105430">which</span> <span m="1105640">of</span> <span m="1105730">these</span>
  <span m="1105940">features</span> <span m="1106690">makes</span> <span m="1106990">sense</span>
  <span m="1107320">for</span> <span m="1107470">us</span> <span m="1107620">to</span>
  <span m="1107710">pass</span> <span m="1108010">into</span> <span m="1108190">a</span>
  <span m="1108250">machine</span> <span m="1108610">learning</span> <span m="1108910">model.</span>
  <span m="1109210">Others</span> <span m="1109450">we're</span> <span m="1109540">just</span>
  <span m="1109690">going</span> <span m="1109800">to</span> <span m="1109870">end</span>
  <span m="1109960">up</span> <span m="1110050">training</span> <span m="1110540">on</span>
  <span m="1110650">a</span> <span m="1110905">[? noisy. ?]</span></p><p><span m="1111680">So</span>
  <span m="1111910">we</span> <span m="1112060">have</span> <span m="1112150">to</span>
  <span m="1112240">use</span> <span m="1112420">some</span> <span m="1112660">domain</span>
  <span m="1112960">knowledge,</span> <span m="1113470">right,</span> <span m="1113710">where</span>
  <span m="1113830">we</span> <span m="1113950">talk</span> <span m="1114610">to</span>
  <span m="1114760">experts</span> <span m="1115330">in</span> <span m="1115480">cybersecurity</span>
  <span m="1116110">and</span> <span m="1116200">say,</span> <span m="1116350">well,</span>
  <span m="1116710">you</span> <span m="1116800">know,</span> <span m="1117340">IP</span>
  <span m="1117640">address</span> <span m="1117970">is</span> <span m="1118120">kind</span>
  <span m="1118420">of</span> <span m="1118480">an</span> <span m="1118570">important</span>
  <span m="1118960">thing,</span> <span m="1119530">but</span> <span m="1119680">maybe</span>
  <span m="1119980">this</span> <span m="1120130">other</span> <span m="1120370">flag</span>
  <span m="1120700">is not</span> <span m="1120910">as</span> <span m="1121030">important.</span>
  <span m="1121940">And</span> <span m="1121990">then,</span> <span m="1122080">we</span>
  <span m="1122200">use</span> <span m="1122410">a</span> <span m="1122470">lot</span>
  <span m="1122650">of</span> <span m="1122710">trial</span> <span m="1123010">and</span>
  <span m="1123100">error</span> <span m="1123400">and</span> <span m="1123550">luck,</span>
  <span m="1123820">as</span> <span m="1123970">well,</span> <span m="1124210">to</span>
  <span m="1124360">help</span> <span m="1124560">pick</span> <span m="1124730">some</span>
  <span m="1124900">of</span> <span m="1124960">these</span> <span m="1125140">features.</span></p><p><span
  m="1126860">Once</span> <span m="1127030">we</span> <span m="1127150">have</span>
  <span m="1127330">these--</span> <span m="1128300">Once</span> <span m="1128470">we</span>
  <span m="1128560">kind</span> <span m="1128740">of</span> <span m="1128830">pick</span>
  <span m="1129130">a</span> <span m="1129190">set</span> <span m="1129400">of</span>
  <span m="1129460">features</span> <span m="1129880">that</span> <span m="1130000">we're</span>
  <span m="1130150">interested</span> <span m="1130660">in,</span> <span m="1131230">when</span>
  <span m="1131440">we</span> <span m="1131560">look</span> <span m="1131770">back</span>
  <span m="1132070">at</span> <span m="1132160">the</span> <span m="1132250">anomaly</span>
  <span m="1132610">detection</span> <span m="1133060">literature,</span> <span m="1133870">a</span>
  <span m="1133930">lot</span> <span m="1134140">of</span> <span m="1134230">work</span>
  <span m="1134530">has</span> <span m="1134650">been</span> <span m="1134830">done</span>
  <span m="1135790">with</span> <span m="1135970">this</span> <span m="1136180">concept</span>
  <span m="1136860">of,</span> <span m="1137300">you</span> <span m="1137350">know,</span>
  <span m="1137560">you</span> <span m="1137680">have</span> <span m="1137920">these</span>
  <span m="1138130">flows,</span> <span m="1138550">but</span> <span m="1138670">you</span>
  <span m="1138760">need</span> <span m="1138910">to</span> <span m="1139000">convert</span>
  <span m="1139420">them</span> <span m="1139600">into</span> <span m="1140260">some</span>
  <span m="1140590">other</span> <span m="1140860">format</span> <span m="1141430">that</span>
  <span m="1142090">makes</span> <span m="1142330">sense</span> <span m="1142750">to</span>
  <span m="1142900">look</span> <span m="1143110">for</span> <span m="1143260">anomalies.</span>
  <span m="1143830">So</span> <span m="1143950">it's just</span> <span m="1144100">converting</span>
  <span m="1144520">into</span> <span m="1144700">a</span> <span m="1144730">feature</span>
  <span m="1145090">space</span> <span m="1145750">in</span> <span m="1145840">which</span>
  <span m="1146050">anomalies</span> <span m="1146560">make</span> <span m="1146800">sense.</span></p><p><span
  m="1147710">And</span> <span m="1147760">so</span> <span m="1148190">we</span> <span
  m="1148660">looked</span> <span m="1148900">at</span> <span m="1148990">using</span>
  <span m="1149350">entropy.</span> <span m="1150490">And</span> <span m="1150640">the</span>
  <span m="1150760">basic</span> <span m="1151510">intuition</span> <span m="1152140">behind</span>
  <span m="1152560">this</span> <span m="1152890">is</span> <span m="1153160">that</span>
  <span m="1153460">if</span> <span m="1155440">we're</span> <span m="1155620">looking</span>
  <span m="1155950">at</span> <span m="1156100">various</span> <span m="1156520">flows</span>
  <span m="1157030">between</span> <span m="1157360">different</span> <span m="1157750">fields</span>
  <span m="1158870">and</span> <span m="1159050">that</span> <span m="1159160">the</span>
  <span m="1159280">entropy</span> <span m="1159820">of</span> <span m="1159940">these</span>
  <span m="1160150">flows</span> <span m="1160960">should</span> <span m="1161230">be</span>
  <span m="1161380">roughly</span> <span m="1161860">equal--</span> <span m="1162940">should</span>
  <span m="1163090">be</span> <span m="1163240">roughly</span> <span m="1163810">similar,</span>
  <span m="1164290">should</span> <span m="1164440">be</span> <span m="1164560">about</span>
  <span m="1164800">the</span> <span m="1164920">same,</span> <span m="1165370">not</span>
  <span m="1165580">equal--</span> <span m="1165970">but</span> <span m="1166120">should</span>
  <span m="1166270">be</span> <span m="1166810">unchanging</span> <span m="1167890">when</span>
  <span m="1168430">there</span> <span m="1168640">is</span> <span m="1168760">no</span>
  <span m="1169090">big</span> <span m="1169720">mechanism,</span> <span m="1170470">defined</span>
  <span m="1170890">by</span> <span m="1171040">an</span> <span m="1171160">outlier</span>
  <span m="1171550">detection</span> <span m="1171970">mechanism,</span> <span m="1173020">that's</span>
  <span m="1173260">involved</span> <span m="1173650">with</span> <span m="1173770">changing</span>
  <span m="1174190">the</span> <span m="1174310">entropy.</span></p><p><span m="1175130">So</span>
  <span m="1175210">for</span> <span m="1175360">example,</span> <span m="1176170">just</span>
  <span m="1176350">to</span> <span m="1176440">make</span> <span m="1176620">this</span>
  <span m="1177340">more</span> <span m="1177610">clear,</span> <span m="1178360">if</span>
  <span m="1178480">you're</span> <span m="1178630">having</span> <span m="1178990">a</span>
  <span m="1179140">DDoS</span> <span m="1179590">attack,</span> <span m="1180460">this</span>
  <span m="1180640">is</span> <span m="1180760">typically</span> <span m="1181330">a</span>
  <span m="1181540">number</span> <span m="1182200">of</span> <span m="1182320">different</span>
  <span m="1182920">source</span> <span m="1183370">IP</span> <span m="1183790">addresses</span>
  <span m="1184390">attempting</span> <span m="1184900">to</span> <span m="1185020">talk</span>
  <span m="1185350">to</span> <span m="1185590">a</span> <span m="1185710">single</span>
  <span m="1186100">destination</span> <span m="1186820">IP</span> <span m="1187120">address.</span>
  <span m="1188000">So</span> <span m="1188050">you</span> <span m="1188200">would</span>
  <span m="1188320">expect</span> <span m="1188860">to</span> <span m="1188950">see</span>
  <span m="1189430">an</span> <span m="1189580">increase</span> <span m="1190150">in</span>
  <span m="1190270">the</span> <span m="1190390">entropy</span> <span m="1191230">of</span>
  <span m="1191350">the</span> <span m="1191470">source</span> <span m="1191860">IP</span>
  <span m="1192250">field</span> <span m="1193660">in</span> <span m="1193810">that</span>
  <span m="1193990">particular</span> <span m="1194470">example.</span> <span m="1195190">And</span>
  <span m="1195310">in</span> <span m="1195430">port</span> <span m="1195680">scan</span>
  <span m="1195940">attacks,</span> <span m="1196360">you</span> <span m="1196450">would</span>
  <span m="1196570">probably</span> <span m="1196960">see</span> <span m="1197140">something</span>
  <span m="1197500">on</span> <span m="1197710">the</span> <span m="1198010">destination</span>
  <span m="1198730">port</span> <span m="1199090">entropy</span> <span m="1199690">would</span>
  <span m="1199870">go</span> <span m="1200080">up.</span> <span m="1200580">Right,</span>
  <span m="1200850">that's</span> <span m="1201040">a</span> <span m="1201100">little</span>
  <span m="1201310">bit</span> <span m="1201430">of</span> <span m="1201520">intuition,</span>
  <span m="1202030">it's</span> <span m="1202160">a</span> <span m="1202270">little</span>
  <span m="1202540">bit</span> <span m="1202690">more</span> <span m="1202870">complicated</span>
  <span m="1203440">than</span> <span m="1203590">that.</span> <span m="1203900">But</span>
  <span m="1203950">that's</span> <span m="1204130">a</span> <span m="1204190">very</span>
  <span m="1204430">high</span> <span m="1204580">level</span> <span m="1204880">view</span>
  <span m="1205060">of</span> <span m="1205150">what's</span> <span m="1205390">going</span>
  <span m="1205660">on.</span></p><p><span m="1206330">And</span> <span m="1206410">for</span>
  <span m="1206590">entropy,</span> <span m="1207010">we</span> <span m="1207130">just</span>
  <span m="1207340">use</span> <span m="1207580">the</span> <span m="1207700">standard--</span>
  <span m="1208750">I'm</span> <span m="1208840">sure</span> <span m="1208990">many</span>
  <span m="1209200">of</span> <span m="1209290">you</span> <span m="1209590">who</span>
  <span m="1209890">are</span> <span m="1210010">familiar</span> <span m="1210310">with</span>
  <span m="1210430">information</span> <span m="1210880">theory</span> <span m="1211180">are</span>
  <span m="1211270">very</span> <span m="1211510">familiar</span> <span m="1211900">with</span>
  <span m="1212380">Shannon</span> <span m="1212790">entropy.</span> <span m="1213640">And</span>
  <span m="1213790">we</span> <span m="1214090">compute</span> <span m="1214540">the</span>
  <span m="1214630">flow</span> <span m="1215050">associated</span> <span m="1215660">with</span>
  <span m="1215770">each</span> <span m="1216040">of</span> <span m="1216190">the</span>
  <span m="1216280">features</span> <span m="1216910">that</span> <span m="1217030">we</span>
  <span m="1217190">pinged</span> <span m="1217600">from</span> <span m="1217840">the</span>
  <span m="1217930">network</span> <span m="1218290">flow</span> <span m="1219250">before.</span>
  <span m="1219700">So</span> <span m="1219850">from</span> <span m="1220000">the</span>
  <span m="1220090">feature</span> <span m="1220400">engineering,</span> <span m="1220680">we</span>
  <span m="1220780">picked</span> <span m="1220980">a</span> <span m="1221030">subset</span>
  <span m="1221350">of</span> <span m="1221410">features</span> <span m="1222100">associated</span>
  <span m="1222550">with</span> <span m="1222640">that.</span></p><p><span m="1223540">We</span>
  <span m="1223660">all</span> <span m="1223810">remember</span> <span m="1224110">when</span>
  <span m="1224260">neural</span> <span m="1224500">networks</span> <span m="1224920">are.</span>
  <span m="1225625">This is</span> <span m="1226000">just</span> <span m="1226210">there</span>
  <span m="1226390">for</span> <span m="1226540">completeness.</span> <span m="1228140">So</span>
  <span m="1228220">we</span> <span m="1228340">take</span> <span m="1228640">these</span>
  <span m="1228920">now,</span> <span m="1229360">network</span> <span m="1229780">flow</span>
  <span m="1230050">sees</span> <span m="1230490">these</span> <span m="1230950">entropies</span>
  <span m="1231610">associated</span> <span m="1232240">with</span> <span m="1232390">the</span>
  <span m="1232480">network</span> <span m="1232870">flow,</span> <span m="1234010">we</span>
  <span m="1234190">use</span> <span m="1234490">those</span> <span m="1234820">as</span>
  <span m="1235030">input</span> <span m="1235450">features</span> <span m="1236410">for</span>
  <span m="1236950">a</span> <span m="1237430">neural</span> <span m="1237790">network</span>
  <span m="1238180">model.</span> <span m="1238900">Now,</span> <span m="1239050">you'll</span>
  <span m="1239170">recall</span> <span m="1240310">from</span> <span m="1240490">the</span>
  <span m="1240580">neural</span> <span m="1240820">network</span> <span m="1241540">talk</span>
  <span m="1241840">that</span> <span m="1241960">we</span> <span m="1242080">had</span>
  <span m="1242830">last</span> <span m="1243160">week,</span> <span m="1243700">we</span>
  <span m="1243850">have</span> <span m="1244090">inputs</span> <span m="1244870">and</span>
  <span m="1245080">outputs,</span> <span m="1246010">we</span> <span m="1246160">have</span>
  <span m="1246310">weights</span> <span m="1246640">associated</span> <span m="1247240">with</span>
  <span m="1247450">them,</span> <span m="1247990">and</span> <span m="1248080">then</span>
  <span m="1248170">we</span> <span m="1248260">have</span> <span m="1248350">this</span>
  <span m="1248500">nonlinear</span> <span m="1249040">equation</span> <span m="1249580">that</span>
  <span m="1249700">sort</span> <span m="1249910">of</span> <span m="1249970">represents</span>
  <span m="1250480">inputs</span> <span m="1250810">and</span> <span m="1250930">outputs</span>
  <span m="1253030">at</span> <span m="1253130">each</span> <span m="1253390">of</span>
  <span m="1253480">the</span> <span m="1253570">layers.</span> <span m="1253900">That</span>
  <span m="1253980">was</span> <span m="1254110">the</span> <span m="1254200">equation.</span>
  <span m="1254515">I could</span> <span m="1254830">see</span> <span m="1255040">Barry</span>
  <span m="1255970">giving</span> <span m="1256240">me</span> <span m="1256360">the</span>
  <span m="1256450">cue</span> <span m="1256660">that</span> <span m="1256810">I'm</span>
  <span m="1256900">walking</span> <span m="1257230">towards</span> <span m="1257620">the</span>
  <span m="1257680">slides.</span></p><p><span m="1257935">AUDIENCE:</span> <span
  m="1258020">Oh</span> <span m="1258105">no.</span></p><p><span m="1260740">VIJAY
  GADEPALLY:</span> <span m="1260860">So</span> <span m="1260980">the</span> <span
  m="1261100">features</span> <span m="1263320">that</span> <span m="1263440">we</span>
  <span m="1263560">have</span> <span m="1263770">over</span> <span m="1263980">here</span>
  <span m="1265030">correspond</span> <span m="1265720">to</span> <span m="1266050">the</span>
  <span m="1266230">various</span> <span m="1266750">entropies</span> <span m="1267290">that</span>
  <span m="1267400">we've</span> <span m="1267580">computed</span> <span m="1267970">in</span>
  <span m="1268030">the</span> <span m="1268120">previous</span> <span m="1268450">step.</span>
  <span m="1269050">And</span> <span m="1269170">the</span> <span m="1269410">outputs</span>
  <span m="1269830">of</span> <span m="1269920">this</span> <span m="1270100">network</span>
  <span m="1270520">correspond</span> <span m="1271210">to</span> <span m="1271600">a</span>
  <span m="1271900">class</span> <span m="1272380">of</span> <span m="1272530">attack.</span>
  <span m="1273190">So</span> <span m="1273490">in</span> <span m="1273640">particular,</span>
  <span m="1274250">we</span> <span m="1274300">focused</span> <span m="1274750">on,</span>
  <span m="1275470">obviously,</span> <span m="1275830">no</span> <span m="1276010">attack,</span>
  <span m="1277420">DDoS</span> <span m="1277870">attacks,</span> <span m="1278290">port</span>
  <span m="1278590">scans,</span> <span m="1279040">network</span> <span m="1279370">scans,</span>
  <span m="1279790">and</span> <span m="1279910">P2P</span> <span m="1280390">network</span>
  <span m="1280720">scans.</span></p><p><span m="1282430">The</span> <span m="1282880">model</span>
  <span m="1283300">itself</span> <span m="1284170">had</span> <span m="1284380">three</span>
  <span m="1284650">hidden</span> <span m="1284860">layers</span> <span m="1285340">with</span>
  <span m="1285520">130</span> <span m="1286440">and</span> <span m="1286540">100</span>
  <span m="1286900">nodes,</span> <span m="1287590">respectively,</span> <span m="1288600">and</span>
  <span m="1289000">an</span> <span m="1289270">output</span> <span m="1289570">layer.</span>
  <span m="1289870">And</span> <span m="1290020">we</span> <span m="1290110">used</span>
  <span m="1290380">ReLU</span> <span m="1290740">activation.</span> <span m="1291760">I'm</span>
  <span m="1291910">happy</span> <span m="1292160">to</span> <span m="1292270">talk</span>
  <span m="1292540">in</span> <span m="1292630">more</span> <span m="1292840">depth</span>
  <span m="1293080">about</span> <span m="1293320">why</span> <span m="1293530">we</span>
  <span m="1293650">selected</span> <span m="1294100">these,</span> <span m="1294400">but</span>
  <span m="1294520">I'll</span> <span m="1294610">save</span> <span m="1294820">that</span>
  <span m="1295000">for</span> <span m="1295120">another</span> <span m="1295420">time.</span></p><p><span
  m="1297310">And</span> <span m="1298150">going</span> <span m="1298750">through</span>
  <span m="1298900">this</span> <span m="1299050">process,</span> <span m="1299480">we</span>
  <span m="1299580">actually</span> <span m="1299710">had</span> <span m="1299890">very</span>
  <span m="1300100">good</span> <span m="1300250">results.</span> <span m="1301430">So</span>
  <span m="1301720">that's</span> <span m="1302030">sort</span> <span m="1302260">of</span>
  <span m="1302320">the</span> <span m="1302410">short</span> <span m="1303010">form</span>
  <span m="1303400">of</span> <span m="1303490">the</span> <span m="1303580">research</span>
  <span m="1305020">work.</span> <span m="1305660">But</span> <span m="1305710">what</span>
  <span m="1305860">I</span> <span m="1305950">wanted</span> <span m="1306250">to</span>
  <span m="1306370">really</span> <span m="1306670">emphasize</span> <span m="1307420">is</span>
  <span m="1308230">the</span> <span m="1308350">amount</span> <span m="1308680">of</span>
  <span m="1308830">effort</span> <span m="1309160">that</span> <span m="1309310">went</span>
  <span m="1309490">into</span> <span m="1309700">the</span> <span m="1309820">data</span>
  <span m="1310060">conditioning,</span> <span m="1310690">the</span> <span m="1310840">importance</span>
  <span m="1311590">of</span> <span m="1312130">collecting</span> <span m="1312550">data,</span>
  <span m="1312970">anonymizing</span> <span m="1313690">data,</span> <span m="1314530">making</span>
  <span m="1314860">it</span> <span m="1315670">human</span> <span m="1315970">readable,</span>
  <span m="1316420">converting</span> <span m="1316900">it into</span> <span m="1317110">a</span>
  <span m="1317170">format</span> <span m="1317650">that</span> <span m="1317770">people</span>
  <span m="1318100">understand,</span> <span m="1319450">and</span> <span m="1319690">then</span>
  <span m="1320110">kind</span> <span m="1320350">of</span> <span m="1320650">walking</span>
  <span m="1321130">through</span> <span m="1321400">the</span> <span m="1321530">sort</span>
  <span m="1321760">of--</span> <span m="1321890">it</span> <span m="1322210">was</span>
  <span m="1322390">certainly</span> <span m="1322720">an</span> <span m="1322810">iterative</span>
  <span m="1323140">process.</span> <span m="1323560">As</span> <span m="1323680">much</span>
  <span m="1323890">as</span> <span m="1323980">this</span> <span m="1324100">is</span>
  <span m="1324190">a</span> <span m="1324250">very</span> <span m="1324460">short</span>
  <span m="1324790">form</span> <span m="1325150">of</span> <span m="1325270">what</span>
  <span m="1325450">we</span> <span m="1325570">did,</span> <span m="1326200">this</span>
  <span m="1326740">took</span> <span m="1327010">a</span> <span m="1327070">long</span>
  <span m="1327400">time</span> <span m="1327700">to</span> <span m="1327790">get</span>
  <span m="1328000">to</span> <span m="1328120">these</span> <span m="1328330">results.</span></p><p><span
  m="1329050">And</span> <span m="1329320">what</span> <span m="1329500">we're</span>
  <span m="1329630">presenting</span> <span m="1330070">over</span> <span m="1330310">here</span>
  <span m="1330700">is</span> <span m="1331030">the</span> <span m="1331390">attack</span>
  <span m="1331840">type</span> <span m="1332200">and the</span> <span m="1332330">intensity.</span>
  <span m="1332940">So</span> <span m="1332980">this</span> <span m="1333130">is</span>
  <span m="1333220">the</span> <span m="1333310">ground</span> <span m="1333670">truth</span>
  <span m="1334030">from</span> <span m="1334360">the</span> <span m="1334450">synthetic</span>
  <span m="1334900">data</span> <span m="1335170">generator,</span> <span m="1336100">and</span>
  <span m="1336280">then</span> <span m="1337090">this</span> <span m="1337360">is</span>
  <span m="1337450">sort</span> <span m="1337690">of</span> <span m="1337750">the</span>
  <span m="1337870">prediction</span> <span m="1338440">that</span> <span m="1338590">our</span>
  <span m="1338680">model</span> <span m="1339040">has</span> <span m="1339490">across</span>
  <span m="1339850">the</span> <span m="1339940">site.</span> <span m="1340610">And</span>
  <span m="1340630">this is</span> <span m="1340780">a</span> <span m="1340870">confusion</span>
  <span m="1341320">matrix.</span> <span m="1341770">So</span> <span m="1341870">a</span>
  <span m="1341970">higher</span> <span m="1342130">number</span> <span m="1342550">or</span>
  <span m="1342700">a</span> <span m="1342760">darker</span> <span m="1343930">blue</span>
  <span m="1344530">indicates</span> <span m="1344980">that</span> <span m="1345100">we</span>
  <span m="1345220">did</span> <span m="1345460">a</span> <span m="1345520">really</span>
  <span m="1345820">good</span> <span m="1345970">job.</span> <span m="1346700">And</span>
  <span m="1346750">we've</span> <span m="1346960">also</span> <span m="1347290">used</span>
  <span m="1347710">varying</span> <span m="1348580">intensities</span> <span m="1349540">of</span>
  <span m="1349810">these</span> <span m="1350080">in</span> <span m="1350160">attacks.</span>
  <span m="1350560">So</span> <span m="1351130">certainly,</span> <span m="1351490">if</span>
  <span m="1351580">we</span> <span m="1351670">have</span> <span m="1351850">strong,</span>
  <span m="1352490">which</span> <span m="1352600">means</span> <span m="1352840">we've</span>
  <span m="1353440">injected</span> <span m="1353890">about</span> <span m="1354040">20,000</span>
  <span m="1354610">packets</span> <span m="1355030">in</span> <span m="1355090">the</span>
  <span m="1355180">15</span> <span m="1355540">minutes,</span> <span m="1357130">we</span>
  <span m="1357910">can</span> <span m="1358030">detect</span> <span m="1358360">those</span>
  <span m="1358600">really,</span> <span m="1359000">really</span> <span m="1359140">well.</span>
  <span m="1359950">As</span> <span m="1360170">you</span> <span m="1360280">have</span>
  <span m="1360520">weaker</span> <span m="1360880">and</span> <span m="1360970">weaker</span>
  <span m="1361330">attacks,</span> <span m="1362500">our</span> <span m="1363670">system</span>
  <span m="1364060">doesn't</span> <span m="1364330">do</span> <span m="1364570">as</span>
  <span m="1364840">well.</span> <span m="1365110">it's</span> <span m="1365520">quite</span>
  <span m="1365900">reasonable,</span> <span m="1366460">but</span> <span m="1367030">certainly</span>
  <span m="1367390">an</span> <span m="1367480">area</span> <span m="1367930">of</span>
  <span m="1368630">ongoing</span> <span m="1369100">research.</span></p><p><span
  m="1370430">So</span> <span m="1370510">with</span> <span m="1370630">that,</span>
  <span m="1371330">I</span> <span m="1371430">just</span> <span m="1371470">wanted</span>
  <span m="1371700">to</span> <span m="1372580">hand</span> <span m="1372730">it</span>
  <span m="1372820">over</span> <span m="1373060">to</span> <span m="1373240">Jeremy.</span>
  <span m="1373750">But</span> <span m="1374200">these</span> <span m="1374410">are</span>
  <span m="1374470">some</span> <span m="1375010">initial</span> <span m="1375400">work</span>
  <span m="1376050">and</span> <span m="1376300">results</span> <span m="1376690">of</span>
  <span m="1376770">detecting</span> <span m="1377150">and</span> <span m="1377440">classifying</span>
  <span m="1377570">network</span> <span m="1377920">attacks.</span> <span m="1378640">The</span>
  <span m="1378760">keynotes</span> <span m="1379360">was--</span> <span m="1380050">data</span>
  <span m="1380290">conditioning</span> <span m="1380830">was</span> <span m="1381010">where</span>
  <span m="1381160">we</span> <span m="1381310">ended</span> <span m="1381520">up</span>
  <span m="1381610">spending</span> <span m="1382090">the</span> <span m="1382150">majority</span>
  <span m="1382690">of</span> <span m="1382780">the</span> <span m="1382900">time.</span>
  <span m="1383890">Cleaning</span> <span m="1384340">up</span> <span m="1384460">the</span>
  <span m="1384550">collected</span> <span m="1385030">data,</span> <span m="1385750">coming</span>
  <span m="1386200">up</span> <span m="1386380">with--</span> <span m="1386560">We</span>
  <span m="1387460">spent</span> <span m="1387730">a</span> <span m="1387790">lot</span>
  <span m="1388030">of</span> <span m="1388120">time</span> <span m="1388360">trying</span>
  <span m="1388540">to</span> <span m="1388600">figure</span> <span m="1389140">out</span>
  <span m="1389290">how</span> <span m="1389440">to</span> <span m="1389530">label</span>
  <span m="1389860">this</span> <span m="1390070">data</span> <span m="1391030">because</span>
  <span m="1391390">we</span> <span m="1391540">were</span> <span m="1391900">just</span>
  <span m="1392170">unable</span> <span m="1392560">to</span> <span m="1392740">really</span>
  <span m="1393010">do</span> <span m="1393160">it.</span> <span m="1393400">And</span>
  <span m="1393500">finally,</span> <span m="1394060">we</span> <span m="1394240">ended</span>
  <span m="1394420">up</span> <span m="1394510">going</span> <span m="1394780">the</span>
  <span m="1394870">synthetic</span> <span m="1395590">generator</span> <span m="1396100">path.</span>
  <span m="1396670">But</span> <span m="1397390">we</span> <span m="1397750">actually</span>
  <span m="1397990">did</span> <span m="1398110">spend</span> <span m="1398380">a</span>
  <span m="1398410">significant</span> <span m="1398860">amount</span> <span m="1399070">of</span>
  <span m="1399130">time</span> <span m="1399350">to</span> <span m="1399400">try</span>
  <span m="1399520">to</span> <span m="1399610">figure</span> <span m="1399820">that</span>
  <span m="1400030">out.</span> <span m="1400640">And</span> <span m="1400660">then,</span>
  <span m="1400900">we</span> <span m="1401020">spent</span> <span m="1401230">a</span>
  <span m="1401260">lot</span> <span m="1401470">of</span> <span m="1401530">time</span>
  <span m="1401740">and</span> <span m="1401830">feature</span> <span m="1402130">in</span>
  <span m="1402190">engineering,</span> <span m="1402730">which</span> <span m="1403060">did</span>
  <span m="1403210">consist</span> <span m="1403600">of</span> <span m="1403660">a</span>
  <span m="1403720">lot</span> <span m="1403900">of</span> <span m="1403960">trial</span>
  <span m="1404260">and</span> <span m="1404380">error</span> <span m="1404980">and
  a lot</span> <span m="1405250">of that</span> <span m="1405550">stuff</span> <span
  m="1405790">like</span> <span m="1405940">that.</span> <span m="1406920">OK,</span>
  <span m="1407260">thank</span> <span m="1407500">you.</span></p>
type: course
uid: 220f355503e86e36bb1588e0277a066c

---
None