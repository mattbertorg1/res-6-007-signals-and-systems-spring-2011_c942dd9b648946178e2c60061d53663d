---
about_this_resource_text: '<p><strong>Topics covered:</strong> Conversion of continuous-time
  to discrete-time signals through sampling; Digital differentiaion, half-sample delay;
  Demonstration: sampling a continuous-time signal, filtering sequences with a low-pass
  filter, reconstructing a continuous-time signal using bandlimited interpolation.</p><p><strong>Instructor:</strong>
  Prof. Alan V. Oppenheim</p>'
course_id: res-6-007-signals-and-systems-spring-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: Q7aZNgY18b4
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Video-YouTube-Stream
  type: Video
  uid: e82ae9b38164caf815f2bc91e3e66907
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/Q7aZNgY18b4/default.jpg
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8b50c9988a75000ed2a89693f857a17e
- id: Video-InternetArchive-MP4
  media_location: http://archive.org/download/MITRES.6.007S11/MITRES_6-007S11lec18_300k.mp4
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Video-Internet Archive-MP4
  type: Video
  uid: ba65fb4137643d8dd6654e612afbdfee
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-18-discrete-time-processing/id458320213?i=113398882
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Video-iTunes U-MP4
  type: Video
  uid: bb2a5c377038fe83ea264a5f1c2d3b21
- id: 3Play-3PlayYouTubeid-MP4
  media_location: Q7aZNgY18b4
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f45e409734dba9d1b75e2411d2fcce2c
- id: Q7aZNgY18b4.srt
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  technical_location: https://ocw.mit.edu/resources/res-6-007-signals-and-systems-spring-2011/video-lectures/lecture-18-discrete-time-processing-of-continuous-time-signals/Q7aZNgY18b4.srt
  title: 3play caption file
  type: null
  uid: b3433b5e504f87cb9ca8d97210305c27
- id: Q7aZNgY18b4.pdf
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  technical_location: https://ocw.mit.edu/resources/res-6-007-signals-and-systems-spring-2011/video-lectures/lecture-18-discrete-time-processing-of-continuous-time-signals/Q7aZNgY18b4.pdf
  title: 3play pdf file
  type: null
  uid: 4730355239bdc0bad0097e01e7a7d419
- id: Caption-3Play YouTube id-SRT
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c256e95624513f9c7a1e2ed74f403559
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 65a9127bbfb6e04209299642da1c3167
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 5e5a973b3cb7da6e941faf5a159b3d22
inline_embed_id: 73667836lecture18:discrete-timeprocessingofcontinuous-timesignals14624181
layout: video
order_index: null
parent_uid: a781d5ac598bc6063ba6ac8138e446cf
related_resources_text: <p>Discrete-Time Processing of Continuous-Time Signals (<img
  alt="This resource may not render correctly in a screen reader." src="/images/inacessible.gif"
  /><a target="_blank" href="./resolveuid/9d7dd2f5a1a5281cbc6767e3e6188d8d">PDF</a>)</p>
  <p>&nbsp;</p>
short_url: lecture-18-discrete-time-processing-of-continuous-time-signals
technical_location: https://ocw.mit.edu/resources/res-6-007-signals-and-systems-spring-2011/video-lectures/lecture-18-discrete-time-processing-of-continuous-time-signals
template_type: Tabbed
title: 'Lecture 18: Discrete-Time Processing of Continuous-Time Signals'
transcript: '<p><span m=''6770''>[MUSIC PLAYING]</span> </p><p><span m=''42070''>PROFESSOR:
  Last</span> <span m=''42370''>time,</span> <span m=''42890''>we</span> <span m=''43150''>began</span>
  <span m=''43710''>the</span> <span m=''44160''>discussion</span> <span m=''45000''>of</span>
  <span m=''46020''>discreet-time</span> <span m=''46840''>processing</span> <span
  m=''47680''>of</span> <span m=''48010''>continuous-time</span> <span m=''49050''>signals.</span>
  <span m=''50510''>And,</span> <span m=''51520''>as</span> <span m=''51730''>a</span>
  <span m=''51780''>reminder,</span> <span m=''53030''>let</span> <span m=''53220''>me</span>
  <span m=''53700''>review</span> <span m=''54410''>the</span> <span m=''54750''>basic</span>
  <span m=''55230''>notion.</span> <span m=''56170''>The</span> <span m=''56300''>idea</span>
  <span m=''56920''>was</span> <span m=''57650''>that</span> <span m=''58510''>we</span>
  <span m=''60090''>convert</span> <span m=''60950''>from</span> <span m=''61450''>a</span>
  <span m=''61560''>continuous-time</span> <span m=''62410''>signal</span> <span m=''63880''>to</span>
  <span m=''64090''>a</span> <span m=''64140''>sequence</span> <span m=''65370''>through</span>
  <span m=''65660''>an</span> <span m=''65950''>operation</span> <span m=''66980''>which</span>
  <span m=''67620''>I</span> <span m=''68650''>represent</span> <span m=''69370''>as</span>
  <span m=''69900''>a</span> <span m=''70070''>continuous</span> <span m=''70680''>to</span>
  <span m=''70800''>discrete</span> <span m=''71240''>time</span> <span m=''71520''>converter.</span>
  <span m=''72890''>And</span> <span m=''73680''>then</span> <span m=''74950''>that</span>
  <span m=''76170''>sequence</span> <span m=''77590''>is</span> <span m=''77790''>used</span>
  <span m=''78470''>as</span> <span m=''79200''>the</span> <span m=''79390''>input</span>
  <span m=''80070''>to</span> <span m=''81870''>an</span> <span m=''81970''>appropriate</span>
  <span m=''82740''>discreet-time</span> <span m=''83470''>system.</span> <span m=''85000''>And</span>
  <span m=''85720''>after</span> <span m=''86370''>appropriate</span> <span m=''86920''>discreet-time</span>
  <span m=''87610''>processing,</span> <span m=''88960''>that</span> <span m=''89250''>sequence</span>
  <span m=''89960''>is</span> <span m=''90860''>converted</span> <span m=''91910''>back</span>
  <span m=''92510''>to</span> <span m=''93110''>a</span> <span m=''93850''>continuous-time</span>
  <span m=''94810''>signal</span> <span m=''95820''>through an</span> <span m=''96380''>operation</span>
  <span m=''97340''>which</span> <span m=''97760''>I</span> <span m=''97870''>label</span>
  <span m=''98420''>as</span> <span m=''98950''>a</span> <span m=''99610''>discrete</span>
  <span m=''100410''>to</span> <span m=''100960''>continuous</span> <span m=''101550''>time</span>
  <span m=''101840''>converter.</span> </p><p><span m=''104180''>Now,</span> <span
  m=''105000''>in</span> <span m=''105140''>the</span> <span m=''105190''>lecture</span>
  <span m=''105790''>last</span> <span m=''106160''>time,</span> <span m=''106700''>we</span>
  <span m=''107730''>carried</span> <span m=''108070''>out</span> <span m=''108270''>some</span>
  <span m=''108380''>analysis</span> <span m=''109630''>which</span> <span m=''110200''>related</span>
  <span m=''110750''>for</span> <span m=''111080''>us</span> <span m=''111750''>the</span>
  <span m=''112120''>spectra</span> <span m=''113230''>in</span> <span m=''113450''>the</span>
  <span m=''113550''>first</span> <span m=''114240''>step</span> <span m=''114800''>of</span>
  <span m=''114910''>this</span> <span m=''115110''>operation.</span> <span m=''116250''>Namely</span>
  <span m=''116860''>in</span> <span m=''116960''>the</span> <span m=''117040''>transformation</span>
  <span m=''118020''>from</span> <span m=''118450''>a</span> <span m=''119140''>continuous-time</span>
  <span m=''119790''>time</span> <span m=''120730''>signal</span> <span m=''121820''>to</span>
  <span m=''122320''>a</span> <span m=''122390''>sequence.</span> <span m=''123520''>And</span>
  <span m=''124000''>let</span> <span m=''124190''>me,</span> <span m=''124290''>by</span>
  <span m=''124520''>the</span> <span m=''124630''>way,</span> <span m=''125020''>draw</span>
  <span m=''125300''>your</span> <span m=''125510''>attention</span> <span m=''126180''>to</span>
  <span m=''126300''>the</span> <span m=''126400''>fact</span> <span m=''127290''>that,</span>
  <span m=''127550''>in</span> <span m=''127700''>the</span> <span m=''127790''>real</span>
  <span m=''128120''>world,</span> <span m=''129030''>this</span> <span m=''129289''>operation</span>
  <span m=''131270''>is</span> <span m=''132300''>essentially</span> <span m=''132970''>implemented</span>
  <span m=''134110''>by</span> <span m=''134670''>what</span> <span m=''135030''>you</span>
  <span m=''135200''>would</span> <span m=''135360''>typically</span> <span m=''135810''>label</span>
  <span m=''136410''>as</span> <span m=''136920''>an</span> <span m=''137070''>analog</span>
  <span m=''137540''>to</span> <span m=''137650''>digital</span> <span m=''138050''>converter,</span>
  <span m=''139080''>if</span> <span m=''139310''>in</span> <span m=''139440''>fact</span>
  <span m=''140340''>the</span> <span m=''140780''>discreet-time</span> <span m=''141430''>processing</span>
  <span m=''142280''>is</span> <span m=''142480''>being</span> <span m=''142770''>done</span>
  <span m=''143050''>digitally.</span> <span m=''143990''>Now,</span> <span m=''144710''>it''s</span>
  <span m=''144900''>important</span> <span m=''145230''>to</span> <span m=''145270''>emphasize</span>
  <span m=''145850''>that</span> <span m=''145950''>it''s</span> <span m=''146110''>not</span>
  <span m=''146290''>exactly</span> <span m=''146970''>what</span> <span m=''147200''>an</span>
  <span m=''147300''>analog</span> <span m=''147700''>to</span> <span m=''147810''>digital</span>
  <span m=''148190''>converter</span> <span m=''148970''>does,</span> <span m=''149800''>but,</span>
  <span m=''150290''>in</span> <span m=''150410''>some</span> <span m=''150670''>sense</span>
  <span m=''151050''>at</span> <span m=''151120''>least,</span> <span m=''152240''>you</span>
  <span m=''152430''>should</span> <span m=''152680''>think</span> <span m=''153080''>of</span>
  <span m=''153350''>this</span> <span m=''153550''>mapping</span> <span m=''154060''>from</span>
  <span m=''154240''>continuous-time</span> <span m=''155100''>to</span> <span m=''155190''>discreet-time</span>
  <span m=''156420''>in</span> <span m=''156550''>very</span> <span m=''156790''>much</span>
  <span m=''157080''>the</span> <span m=''157180''>same</span> <span m=''157550''>way</span>
  <span m=''158000''>that</span> <span m=''158240''>one</span> <span m=''158430''>would</span>
  <span m=''158580''>think</span> <span m=''158870''>of</span> <span m=''158980''>an</span>
  <span m=''159070''>analog</span> <span m=''159500''>to</span> <span m=''159600''>digital</span>
  <span m=''159980''>converter.</span> <span m=''160760''>And</span> <span m=''160890''>the</span>
  <span m=''160960''>mapping</span> <span m=''161340''>back</span> <span m=''161740''>then</span>
  <span m=''163820''>corresponds,</span> <span m=''165460''>in</span> <span m=''165600''>some</span>
  <span m=''165850''>sense,</span> <span m=''166430''>to</span> <span m=''167790''>what</span>
  <span m=''167990''>would</span> <span m=''168150''>happen</span> <span m=''168680''>with</span>
  <span m=''169030''>a</span> <span m=''169160''>digital</span> <span m=''169860''>to</span>
  <span m=''170170''>analog</span> <span m=''170670''>converter.</span> </p><p><span
  m=''172330''>Well,</span> <span m=''172670''>let</span> <span m=''172840''>me</span>
  <span m=''172990''>review</span> <span m=''173770''>what</span> <span m=''174220''>is</span>
  <span m=''174410''>involved</span> <span m=''175010''>in</span> <span m=''175120''>the</span>
  <span m=''175200''>mapping</span> <span m=''175680''>from</span> <span m=''176620''>the</span>
  <span m=''176850''>continuous-time</span> <span m=''177610''>signal</span> <span
  m=''178110''>to</span> <span m=''178220''>the</span> <span m=''178320''>sequence.</span>
  <span m=''179460''>And,</span> <span m=''180250''>let</span> <span m=''180460''>me</span>
  <span m=''180590''>stress</span> <span m=''180980''>again</span> <span m=''181590''>that,</span>
  <span m=''182130''>this</span> <span m=''182350''>operation</span> <span m=''183220''>is</span>
  <span m=''183570''>basically--</span> <span m=''184470''>in</span> <span m=''184610''>the</span>
  <span m=''185050''>continuous</span> <span m=''185590''>to</span> <span m=''185650''>discreet-time</span>
  <span m=''186310''>conversion--</span> <span m=''187400''>a</span> <span m=''187700''>two-step</span>
  <span m=''188260''>process.</span> <span m=''190170''>In</span> <span m=''190700''>the</span>
  <span m=''190810''>first</span> <span m=''191140''>part</span> <span m=''191360''>of</span>
  <span m=''191400''>the</span> <span m=''191470''>process,</span> <span m=''192810''>the</span>
  <span m=''193050''>continuous-time</span> <span m=''193940''>signal</span> <span
  m=''195150''>is</span> <span m=''195770''>modulated</span> <span m=''196850''>with</span>
  <span m=''197110''>impulse</span> <span m=''197610''>train,</span> <span m=''198600''>where</span>
  <span m=''199530''>the</span> <span m=''200740''>period</span> <span m=''201130''>of</span>
  <span m=''201220''>the</span> <span m=''201330''>impulse</span> <span m=''201780''>train</span>
  <span m=''202210''>is</span> <span m=''202340''>capital</span> <span m=''202870''>T.</span>
  <span m=''204040''>And</span> <span m=''204590''>so</span> <span m=''205110''>we</span>
  <span m=''205240''>have</span> <span m=''205470''>a</span> <span m=''205510''>continuous-time</span>
  <span m=''206130''>time</span> <span m=''206940''>impulse</span> <span m=''207430''>train</span>
  <span m=''207730''>signal</span> <span m=''208780''>which</span> <span m=''209040''>captures</span>
  <span m=''209980''>the</span> <span m=''210080''>samples</span> <span m=''211290''>of</span>
  <span m=''211940''>the</span> <span m=''212080''>original</span> <span m=''212510''>continuous-time</span>
  <span m=''213370''>signal.</span> </p><p><span m=''215470''>That</span> <span m=''216270''>impulse</span>
  <span m=''216780''>train</span> <span m=''217700''>is</span> <span m=''217970''>then</span>
  <span m=''219040''>put</span> <span m=''219270''>through</span> <span m=''219460''>an</span>
  <span m=''219550''>operation</span> <span m=''221140''>which,</span> <span m=''222280''>essentially,</span>
  <span m=''223500''>re-labels</span> <span m=''224710''>the</span> <span m=''224820''>samples</span>
  <span m=''226520''>so</span> <span m=''226880''>that</span> <span m=''227580''>the</span>
  <span m=''228370''>sample</span> <span m=''229100''>values,</span> <span m=''229670''>the</span>
  <span m=''229800''>impulse</span> <span m=''230400''>areas,</span> <span m=''231450''>are</span>
  <span m=''232730''>re-labeled</span> <span m=''233580''>as</span> <span m=''233790''>sequence</span>
  <span m=''234400''>values.</span> <span m=''235400''>And</span> <span m=''236010''>the</span>
  <span m=''236140''>result</span> <span m=''236650''>of</span> <span m=''236770''>that</span>
  <span m=''237230''>conversion</span> <span m=''238050''>is</span> <span m=''238320''>then</span>
  <span m=''239080''>the</span> <span m=''239520''>sequence</span> <span m=''240350''>x
  of</span> <span m=''240665''>n.</span> <span m=''242020''>So</span> <span m=''242290''>the</span>
  <span m=''242420''>overall</span> <span m=''242850''>process,</span> <span m=''243420''>then,</span>
  <span m=''243950''>is</span> <span m=''244490''>a</span> <span m=''245180''>sampling</span>
  <span m=''245790''>process,</span> <span m=''246930''>followed</span> <span m=''247510''>by</span>
  <span m=''248150''>what</span> <span m=''248470''>is</span> <span m=''248630''>simply,</span>
  <span m=''249690''>in</span> <span m=''249850''>this</span> <span m=''250070''>box,</span>
  <span m=''250610''>a</span> <span m=''250900''>re-labeling</span> <span m=''251370''>process.</span>
  <span m=''252510''>And,</span> <span m=''253710''>although</span> <span m=''254210''>as</span>
  <span m=''254390''>I</span> <span m=''255200''>indicated</span> <span m=''256050''>just</span>
  <span m=''256269''>a</span> <span m=''256320''>minute</span> <span m=''256579''>ago,</span>
  <span m=''257480''>that</span> <span m=''257750''>is</span> <span m=''258110''>essentially</span>
  <span m=''258630''>what</span> <span m=''258829''>an</span> <span m=''258899''>analog</span>
  <span m=''259329''>to</span> <span m=''259430''>digital</span> <span m=''259810''>converter</span>
  <span m=''260339''>does.</span> <span m=''261100''>An</span> <span m=''261180''>analog</span>
  <span m=''261589''>to</span> <span m=''261740''>digital</span> <span m=''262079''>converter</span>
  <span m=''262490''>doesn''t</span> <span m=''262810''>necessarily</span> <span m=''264340''>carry</span>
  <span m=''264680''>it</span> <span m=''264770''>out</span> <span m=''265290''>in</span>
  <span m=''265460''>those</span> <span m=''265730''>two</span> <span m=''266180''>steps,</span>
  <span m=''267140''>but</span> <span m=''267580''>particularly,</span> <span m=''268580''>in</span>
  <span m=''269350''>terms</span> <span m=''269830''>of</span> <span m=''270280''>carrying</span>
  <span m=''270670''>through</span> <span m=''270900''>an</span> <span m=''270990''>analysis,</span>
  <span m=''272160''>thinking</span> <span m=''272530''>of</span> <span m=''272680''>it</span>
  <span m=''272880''>as</span> <span m=''273030''>a</span> <span m=''273110''>two-step</span>
  <span m=''273610''>process</span> <span m=''274180''>is</span> <span m=''274320''>particularly</span>
  <span m=''274890''>convenient.</span> </p><p><span m=''276890''>Now</span> <span
  m=''277520''>we</span> <span m=''279010''>talked</span> <span m=''279350''>last</span>
  <span m=''279710''>time</span> <span m=''280190''>about</span> <span m=''281220''>what</span>
  <span m=''281710''>this</span> <span m=''282280''>mapping</span> <span m=''282890''>from</span>
  <span m=''283200''>continuous-time</span> <span m=''284050''>to</span> <span m=''284140''>discreet-time</span>
  <span m=''285440''>means,</span> <span m=''285910''>both</span> <span m=''286240''>in</span>
  <span m=''286370''>the</span> <span m=''286470''>time</span> <span m=''286770''>domain,</span>
  <span m=''287300''>and</span> <span m=''287540''>terms</span> <span m=''287890''>of</span>
  <span m=''287990''>the</span> <span m=''288070''>spectra.</span> <span m=''289210''>And</span>
  <span m=''289460''>in</span> <span m=''289530''>particular,</span> <span m=''290310''>in</span>
  <span m=''290430''>the</span> <span m=''290540''>time</span> <span m=''290850''>domain</span>
  <span m=''291890''>we</span> <span m=''292610''>begin</span> <span m=''293250''>with</span>
  <span m=''293450''>the</span> <span m=''293530''>continuous-time</span> <span m=''294370''>signal,</span>
  <span m=''296940''>which</span> <span m=''297200''>is</span> <span m=''297330''>then</span>
  <span m=''297770''>sampled</span> <span m=''298330''>with</span> <span m=''298470''>an</span>
  <span m=''298550''>impulse</span> <span m=''299010''>train</span> <span m=''299970''>and</span>
  <span m=''300370''>converted</span> <span m=''301300''>to</span> <span m=''301470''>a</span>
  <span m=''301540''>sequence</span> <span m=''302720''>by</span> <span m=''303530''>simply</span>
  <span m=''304010''>generating</span> <span m=''304620''>a</span> <span m=''304670''>sequence</span>
  <span m=''305990''>whose</span> <span m=''306340''>values</span> <span m=''307200''>are</span>
  <span m=''307810''>the</span> <span m=''308020''>areas</span> <span m=''308780''>of</span>
  <span m=''309350''>the</span> <span m=''309480''>impulses.</span> <span m=''310490''>And</span>
  <span m=''311400''>I</span> <span m=''311520''>stress</span> <span m=''311930''>the</span>
  <span m=''312020''>fact</span> <span m=''312460''>that</span> <span m=''312590''>what</span>
  <span m=''312790''>this</span> <span m=''312970''>corresponds</span> <span m=''313720''>to,</span>
  <span m=''314420''>essentially,</span> <span m=''315220''>is</span> <span m=''316040''>a</span>
  <span m=''316140''>normalization</span> <span m=''317050''>of</span> <span m=''317150''>the</span>
  <span m=''317260''>time</span> <span m=''317620''>axis,</span> <span m=''318730''>essentially,</span>
  <span m=''319310''>by</span> <span m=''319600''>dividing</span> <span m=''320110''>the</span>
  <span m=''320220''>time</span> <span m=''320520''>axis</span> <span m=''320900''>by</span>
  <span m=''321030''>capital</span> <span m=''321590''>T.</span> </p><p><span m=''323950''>In</span>
  <span m=''324200''>the</span> <span m=''324690''>frequency</span> <span m=''325260''>domain,</span>
  <span m=''326350''>then,</span> <span m=''326970''>we</span> <span m=''327170''>had</span>
  <span m=''327680''>the</span> <span m=''328410''>spectrum</span> <span m=''329150''>of</span>
  <span m=''329290''>the</span> <span m=''329430''>original</span> <span m=''329810''>signal,</span>
  <span m=''331350''>which,</span> <span m=''332070''>because</span> <span m=''332490''>of</span>
  <span m=''332570''>the</span> <span m=''332650''>sampling</span> <span m=''333150''>process,</span>
  <span m=''334050''>is</span> <span m=''335080''>replicated</span> <span m=''336940''>at</span>
  <span m=''338140''>integer</span> <span m=''338480''>multiples</span> <span m=''339250''>of</span>
  <span m=''339760''>the</span> <span m=''340210''>sampling</span> <span m=''340760''>frequency</span>
  <span m=''341390''>omega</span> <span m=''341760''>sub</span> <span m=''341980''>s,</span>
  <span m=''342420''>or</span> <span m=''342660''>2</span> <span m=''342850''>pi</span>
  <span m=''343140''>over</span> <span m=''343380''>capital</span> <span m=''343900''>T.</span>
  <span m=''345620''>And</span> <span m=''345780''>then,</span> <span m=''346090''>in</span>
  <span m=''346260''>converting</span> <span m=''347510''>the</span> <span m=''348490''>impulses</span>
  <span m=''349440''>to</span> <span m=''349640''>a</span> <span m=''349690''>sequence,</span>
  <span m=''350910''>we</span> <span m=''351230''>are</span> <span m=''351480''>essentially</span>
  <span m=''353090''>normalizing</span> <span m=''353940''>the</span> <span m=''354020''>frequency</span>
  <span m=''354650''>axis,</span> <span m=''355580''>so</span> <span m=''355960''>that</span>
  <span m=''357050''>the</span> <span m=''357150''>frequency</span> <span m=''357680''>2</span>
  <span m=''357890''>pi</span> <span m=''358170''>over</span> <span m=''358420''>capital</span>
  <span m=''358950''>T</span> <span m=''359690''>gets</span> <span m=''359960''>re-labeled</span>
  <span m=''360570''>as</span> <span m=''360720''>2</span> <span m=''360920''>pi.</span>
  <span m=''361970''>And</span> <span m=''362240''>the</span> <span m=''362310''>resulting</span>
  <span m=''362930''>discreet-time</span> <span m=''363600''>spectrum</span> <span
  m=''364710''>looks</span> <span m=''365130''>like</span> <span m=''365610''>I</span>
  <span m=''365790''>indicate</span> <span m=''366300''>here.</span> <span m=''367110''>Which</span>
  <span m=''367540''>really</span> <span m=''368110''>is</span> <span m=''368860''>nothing</span>
  <span m=''369220''>more</span> <span m=''369780''>than</span> <span m=''370190''>a</span>
  <span m=''370410''>frequency</span> <span m=''371030''>scaling</span> <span m=''372310''>corresponding</span>
  <span m=''373100''>to</span> <span m=''373220''>the</span> <span m=''373320''>associated</span>
  <span m=''374010''>time</span> <span m=''374290''>scaling.</span> <span m=''375140''>So</span>
  <span m=''375360''>the</span> <span m=''375460''>mapping</span> <span m=''376430''>from</span>
  <span m=''377200''>the</span> <span m=''377390''>impulse</span> <span m=''377840''>train</span>
  <span m=''378120''>spectrum</span> <span m=''378760''>to</span> <span m=''378940''>the</span>
  <span m=''379070''>discreet-time</span> <span m=''379780''>spectrum</span> <span
  m=''380900''>corresponds</span> <span m=''381890''>to</span> <span m=''382350''>a</span>
  <span m=''382420''>mapping</span> <span m=''383450''>specified</span> <span m=''384380''>by</span>
  <span m=''385130''>capital</span> <span m=''385580''>omega</span> <span m=''386070''>equal</span>
  <span m=''386410''>to</span> <span m=''386500''>small</span> <span m=''386880''>omega</span>
  <span m=''387280''>times</span> <span m=''387620''>capital</span> <span m=''388110''>T.</span>
  </p><p><span m=''389800''>And</span> <span m=''390110''>equivalently,</span> <span
  m=''391540''>it''s</span> <span m=''391880''>the</span> <span m=''391960''>frequency</span>
  <span m=''393410''>2</span> <span m=''393620''>pi</span> <span m=''394010''>over</span>
  <span m=''394270''>capital</span> <span m=''394820''>T,</span> <span m=''395470''>which</span>
  <span m=''395790''>is,</span> <span m=''396660''>of</span> <span m=''396810''>course,</span>
  <span m=''397140''>the</span> <span m=''397230''>sampling</span> <span m=''397730''>frequency</span>
  <span m=''399060''>which</span> <span m=''399390''>gets</span> <span m=''399670''>normalized</span>
  <span m=''401160''>to</span> <span m=''401860''>the</span> <span m=''401960''>frequency</span>
  <span m=''402650''>2</span> <span m=''402880''>pi.</span> <span m=''404730''>And</span>
  <span m=''405050''>so,</span> <span m=''405550''>in</span> <span m=''405800''>the</span>
  <span m=''406020''>frequency</span> <span m=''406560''>domain,</span> <span m=''407900''>there</span>
  <span m=''408240''>is</span> <span m=''408490''>a</span> <span m=''408540''>frequency</span>
  <span m=''409070''>normalization</span> <span m=''410560''>associated</span> <span
  m=''411640''>with</span> <span m=''411820''>the</span> <span m=''411890''>fact</span>
  <span m=''412800''>that</span> <span m=''414610''>corresponding</span> <span m=''415470''>to</span>
  <span m=''415620''>this</span> <span m=''415880''>spectrum</span> <span m=''417680''>is</span>
  <span m=''418540''>a</span> <span m=''419190''>time</span> <span m=''419620''>sequence</span>
  <span m=''420400''>or</span> <span m=''420570''>discreet-time</span> <span m=''421290''>sequence,</span>
  <span m=''422350''>as</span> <span m=''422900''>I</span> <span m=''423000''>showed</span>
  <span m=''423350''>previously,</span> <span m=''424720''>and</span> <span m=''424950''>the</span>
  <span m=''425030''>discreet-time</span> <span m=''425750''>sequence</span> <span
  m=''426890''>is</span> <span m=''427500''>related</span> <span m=''428430''>to</span>
  <span m=''430370''>the</span> <span m=''430470''>original</span> <span m=''430900''>continuous-time</span>
  <span m=''432000''>signal</span> <span m=''434470''>through</span> <span m=''435050''>a</span>
  <span m=''435160''>time</span> <span m=''435490''>normalization.</span> <span m=''436600''>In</span>
  <span m=''436790''>other</span> <span m=''436990''>words,</span> <span m=''438980''>these</span>
  <span m=''439480''>sequence</span> <span m=''440080''>values</span> <span m=''441220''>are</span>
  <span m=''441820''>simply</span> <span m=''442240''>samples</span> <span m=''442770''>of</span>
  <span m=''442840''>the</span> <span m=''442940''>continuous-time</span> <span m=''443760''>signal</span>
  <span m=''444730''>with</span> <span m=''445240''>the</span> <span m=''445360''>time</span>
  <span m=''445730''>axis</span> <span m=''446510''>renormalized.</span> </p><p><span
  m=''450090''>Now,</span> <span m=''450600''>what</span> <span m=''450780''>we</span>
  <span m=''450880''>want</span> <span m=''451050''>to</span> <span m=''451120''>consider--</span>
  <span m=''451910''>this</span> <span m=''452120''>is</span> <span m=''452390''>the</span>
  <span m=''452540''>conversion</span> <span m=''453050''>from</span> <span m=''453270''>continuous-time</span>
  <span m=''453970''>to</span> <span m=''454070''>discreet-time--</span> <span m=''455260''>what</span>
  <span m=''455380''>we</span> <span m=''455500''>want</span> <span m=''455640''>to</span>
  <span m=''455700''>consider</span> <span m=''456170''>now</span> <span m=''456710''>is</span>
  <span m=''457530''>the</span> <span m=''457720''>overall</span> <span m=''458280''>system</span>
  <span m=''459120''>which</span> <span m=''459960''>implements</span> <span m=''460660''>not</span>
  <span m=''460850''>just</span> <span m=''461070''>the</span> <span m=''461160''>conversion,</span>
  <span m=''461820''>but</span> <span m=''462000''>filtering,</span> <span m=''462780''>and</span>
  <span m=''462960''>then</span> <span m=''463540''>coming</span> <span m=''463830''>back</span>
  <span m=''464120''>out</span> <span m=''464260''>of</span> <span m=''464330''>the</span>
  <span m=''464420''>conversion</span> <span m=''464980''>back</span> <span m=''465260''>to</span>
  <span m=''465360''>continuous-time.</span> <span m=''467630''>So</span> <span m=''468250''>let''s</span>
  <span m=''468560''>look</span> <span m=''468910''>at</span> <span m=''469350''>the</span>
  <span m=''469740''>overall</span> <span m=''470210''>system.</span> <span m=''471400''>And</span>
  <span m=''472040''>the</span> <span m=''472150''>overall</span> <span m=''472530''>system,</span>
  <span m=''473070''>of</span> <span m=''473160''>course,</span> <span m=''473560''>as</span>
  <span m=''473740''>I''ve</span> <span m=''475100''>stressed</span> <span m=''475610''>several</span>
  <span m=''475960''>times</span> <span m=''476340''>in</span> <span m=''476400''>the</span>
  <span m=''476470''>past,</span> <span m=''478060''>consists</span> <span m=''478780''>of</span>
  <span m=''479500''>first,</span> <span m=''480210''>the</span> <span m=''481080''>sampling</span>
  <span m=''481650''>process,</span> <span m=''484420''>conversion</span> <span m=''485310''>to</span>
  <span m=''485460''>an</span> <span m=''485540''>impulse</span> <span m=''486030''>train,</span>
  <span m=''488150''>and</span> <span m=''489650''>the</span> <span m=''489980''>impulse</span>
  <span m=''490400''>train</span> <span m=''491030''>converted</span> <span m=''491520''>to</span>
  <span m=''491650''>a</span> <span m=''491710''>sequence.</span> </p><p><span m=''493530''>That</span>
  <span m=''493800''>sequence</span> <span m=''494720''>is</span> <span m=''495040''>then</span>
  <span m=''495710''>processed</span> <span m=''497020''>through</span> <span m=''497740''>our</span>
  <span m=''498430''>discreet-time</span> <span m=''499450''>filter.</span> <span
  m=''501180''>And</span> <span m=''501940''>after</span> <span m=''502400''>the</span>
  <span m=''503030''>discreet-time</span> <span m=''503470''>time</span> <span m=''503710''>processing,</span>
  <span m=''505060''>the</span> <span m=''505170''>result</span> <span m=''505640''>of</span>
  <span m=''505770''>that</span> <span m=''506250''>is</span> <span m=''506910''>converted</span>
  <span m=''507770''>back</span> <span m=''508530''>to</span> <span m=''509030''>an</span>
  <span m=''509160''>impulse</span> <span m=''509680''>train.</span> <span m=''510700''>So</span>
  <span m=''511410''>this</span> <span m=''511640''>resulting</span> <span m=''512130''>process</span>
  <span m=''512780''>sequence</span> <span m=''514010''>is</span> <span m=''514909''>then</span>
  <span m=''515150''>converted</span> <span m=''515710''>back</span> <span m=''516289''>to</span>
  <span m=''516409''>an</span> <span m=''516520''>impulse</span> <span m=''516990''>train.</span>
  <span m=''517980''>And</span> <span m=''518169''>then,</span> <span m=''518520''>finally,</span>
  <span m=''518980''>we</span> <span m=''519130''>carry</span> <span m=''519570''>out</span>
  <span m=''520049''>the</span> <span m=''520699''>desampling</span> <span m=''521750''>process</span>
  <span m=''522929''>by</span> <span m=''523700''>simply</span> <span m=''524150''>using</span>
  <span m=''524780''>a</span> <span m=''524870''>low-pass</span> <span m=''525440''>filter</span>
  <span m=''528370''>with</span> <span m=''528660''>a</span> <span m=''528720''>cutoff</span>
  <span m=''529080''>associated</span> <span m=''529760''>with</span> <span m=''529900''>the</span>
  <span m=''529970''>sampling</span> <span m=''530430''>frequency</span> <span m=''530940''>that</span>
  <span m=''531050''>we</span> <span m=''531180''>used.</span> </p><p><span m=''533170''>Now,</span>
  <span m=''533880''>typically</span> <span m=''534630''>in</span> <span m=''535080''>a</span>
  <span m=''535170''>system</span> <span m=''535980''>like</span> <span m=''536240''>that--</span>
  <span m=''536500''>which</span> <span m=''536680''>implements</span> <span m=''537620''>discreet-time</span>
  <span m=''538220''>processing</span> <span m=''538840''>of</span> <span m=''538920''>continuous-time</span>
  <span m=''539460''>time</span> <span m=''539710''>signals--</span> <span m=''541690''>we</span>
  <span m=''541800''>need</span> <span m=''541980''>to</span> <span m=''542110''>ensure</span>
  <span m=''542640''>in</span> <span m=''542770''>one</span> <span m=''542970''>way</span>
  <span m=''543110''>or</span> <span m=''543280''>another</span> <span m=''544190''>that</span>
  <span m=''544850''>the</span> <span m=''545980''>bandwidth</span> <span m=''547030''>of</span>
  <span m=''547180''>the</span> <span m=''547320''>input</span> <span m=''547860''>is</span>
  <span m=''548430''>sufficiently</span> <span m=''549120''>limited,</span> <span
  m=''549880''>so</span> <span m=''550100''>that</span> <span m=''550250''>we</span>
  <span m=''550400''>avoid</span> <span m=''550740''>aliasing.</span> <span m=''552010''>One</span>
  <span m=''552220''>way</span> <span m=''552360''>to</span> <span m=''552460''>do</span>
  <span m=''552630''>that</span> <span m=''553040''>is</span> <span m=''554010''>to</span>
  <span m=''554210''>force</span> <span m=''554600''>it</span> <span m=''554790''>one</span>
  <span m=''554980''>way</span> <span m=''555130''>or</span> <span m=''555270''>another,</span>
  <span m=''555770''>or</span> <span m=''556300''>simply</span> <span m=''556660''>know</span>
  <span m=''556900''>that</span> <span m=''557010''>our</span> <span m=''557130''>signal</span>
  <span m=''557940''>satisfies</span> <span m=''558660''>the</span> <span m=''559000''>bandwidth</span>
  <span m=''559190''>constraint.</span> <span m=''560160''>Although,</span> <span
  m=''560730''>a</span> <span m=''560870''>fairly</span> <span m=''561230''>typical</span>
  <span m=''561690''>thing</span> <span m=''561940''>to</span> <span m=''562070''>do</span>
  <span m=''562870''>in</span> <span m=''563010''>addition</span> <span m=''563650''>to</span>
  <span m=''564190''>this</span> <span m=''564360''>sampling</span> <span m=''564850''>process</span>
  <span m=''566100''>is</span> <span m=''566880''>to</span> <span m=''567100''>include</span>
  <span m=''568300''>what</span> <span m=''568540''>is</span> <span m=''568720''>referred</span>
  <span m=''569200''>to</span> <span m=''570530''>an</span> <span m=''570770''>anti-aliasing</span>
  <span m=''572070''>filter.</span> <span m=''573440''>In</span> <span m=''573590''>other</span>
  <span m=''573780''>words,</span> <span m=''574280''>this</span> <span m=''574490''>is</span>
  <span m=''574630''>a</span> <span m=''574680''>filter</span> <span m=''575500''>that</span>
  <span m=''575780''>would</span> <span m=''576540''>band-limit</span> <span m=''577580''>the</span>
  <span m=''577730''>input</span> <span m=''578890''>at</span> <span m=''579410''>at</span>
  <span m=''579570''>least</span> <span m=''579970''>half</span> <span m=''580260''>the</span>
  <span m=''580340''>sampling</span> <span m=''580830''>frequency,</span> <span m=''581980''>so</span>
  <span m=''582260''>that</span> <span m=''582700''>we</span> <span m=''583090''>are</span>
  <span m=''583960''>guaranteed,</span> <span m=''584640''>then,</span> <span m=''585150''>that</span>
  <span m=''585640''>there</span> <span m=''586000''>is</span> <span m=''586250''>no</span>
  <span m=''586500''>aliasing</span> <span m=''587660''>that''s</span> <span m=''587850''>carried</span>
  <span m=''588260''>out</span> <span m=''588580''>in</span> <span m=''588710''>this</span>
  <span m=''588910''>process.</span> <span m=''590400''>And</span> <span m=''590950''>it''s</span>
  <span m=''591100''>important</span> <span m=''592160''>to</span> <span m=''592280''>stress</span>
  <span m=''592900''>that,</span> <span m=''594340''>in</span> <span m=''594490''>this</span>
  <span m=''594690''>kind</span> <span m=''594910''>of</span> <span m=''595000''>processing--</span>
  <span m=''595610''>discreet-time</span> <span m=''596280''>processing</span> <span
  m=''596860''>of</span> <span m=''596950''>continuous-time</span> <span m=''597680''>signals--</span>
  <span m=''599190''>except</span> <span m=''599620''>in</span> <span m=''599680''>certain</span>
  <span m=''600140''>special</span> <span m=''600630''>situations,</span> <span m=''601620''>it''s</span>
  <span m=''602130''>very</span> <span m=''602400''>important</span> <span m=''603370''>to</span>
  <span m=''603530''>avoid</span> <span m=''603930''>aliasing</span> <span m=''604570''>because</span>
  <span m=''605320''>we''re</span> <span m=''605510''>going</span> <span m=''605760''>to</span>
  <span m=''605900''>want</span> <span m=''606620''>to</span> <span m=''606750''>do</span>
  <span m=''607020''>a</span> <span m=''607080''>reconstruction</span> <span m=''608090''>after</span>
  <span m=''608450''>we</span> <span m=''608580''>do</span> <span m=''609050''>the</span>
  <span m=''609140''>sampling</span> <span m=''609400''>and</span> <span m=''609660''>processing.</span>
  </p><p><span m=''613260''>OK,</span> <span m=''613600''>now,</span> <span m=''614430''>this</span>
  <span m=''614650''>is</span> <span m=''614820''>the</span> <span m=''614930''>sequence</span>
  <span m=''615390''>of</span> <span m=''615470''>steps</span> <span m=''615850''>in</span>
  <span m=''615910''>the</span> <span m=''616010''>time</span> <span m=''616310''>domain.</span>
  <span m=''617070''>Let''s</span> <span m=''617370''>examine</span> <span m=''618230''>what</span>
  <span m=''618450''>happens</span> <span m=''619020''>as</span> <span m=''619150''>a</span>
  <span m=''619220''>consequence</span> <span m=''619880''>of</span> <span m=''620010''>this</span>
  <span m=''620430''>in</span> <span m=''620530''>the</span> <span m=''620610''>frequency</span>
  <span m=''621140''>domain.</span> <span m=''623240''>Well,</span> <span m=''624270''>let''s</span>
  <span m=''624890''>choose</span> <span m=''625290''>some</span> <span m=''625700''>type</span>
  <span m=''626010''>of</span> <span m=''626360''>simple</span> <span m=''626730''>representative</span>
  <span m=''627400''>spectrum.</span> <span m=''628500''>And,</span> <span m=''628710''>of</span>
  <span m=''628790''>course,</span> <span m=''629080''>what''s</span> <span m=''629270''>important</span>
  <span m=''629720''>about</span> <span m=''630080''>it</span> <span m=''630300''>is</span>
  <span m=''630740''>that</span> <span m=''631760''>the</span> <span m=''632320''>spectrum</span>
  <span m=''632840''>we</span> <span m=''633040''>choose</span> <span m=''633530''>is</span>
  <span m=''633670''>band-limited,</span> <span m=''634750''>or</span> <span m=''635060''>that</span>
  <span m=''635420''>there''s</span> <span m=''635620''>an</span> <span m=''635700''>anti-aliasing</span>
  <span m=''636570''>filter.</span> <span m=''637470''>And</span> <span m=''637940''>it''s</span>
  <span m=''638090''>not</span> <span m=''638270''>the</span> <span m=''638340''>shape,</span>
  <span m=''638650''>of</span> <span m=''638770''>course,</span> <span m=''639230''>that</span>
  <span m=''639530''>is</span> <span m=''639880''>critical.</span> </p><p><span m=''641080''>And</span>
  <span m=''641600''>as</span> <span m=''642160''>we</span> <span m=''642290''>work</span>
  <span m=''642580''>our</span> <span m=''642720''>way</span> <span m=''642900''>through</span>
  <span m=''643120''>the</span> <span m=''643220''>system,</span> <span m=''644200''>this</span>
  <span m=''644600''>is</span> <span m=''644900''>the</span> <span m=''645140''>continuous-time</span>
  <span m=''646010''>spectrum.</span> <span m=''647460''>After</span> <span m=''647820''>sampling,</span>
  <span m=''648960''>that</span> <span m=''649440''>spectrum</span> <span m=''650040''>is</span>
  <span m=''650210''>replicated</span> <span m=''651180''>at</span> <span m=''652390''>multiples</span>
  <span m=''653310''>of</span> <span m=''653530''>the</span> <span m=''653600''>sampling</span>
  <span m=''654090''>frequency--</span> <span m=''654690''>integer</span> <span m=''655030''>multiples</span>
  <span m=''655560''>of</span> <span m=''655640''>the</span> <span m=''655700''>sampling</span>
  <span m=''656180''>frequency--</span> <span m=''656840''>and</span> <span m=''656940''>so</span>
  <span m=''657670''>there</span> <span m=''657790''>would</span> <span m=''657910''>be</span>
  <span m=''658050''>another</span> <span m=''658310''>one</span> <span m=''658470''>over</span>
  <span m=''658720''>here,</span> <span m=''658990''>and</span> <span m=''659090''>another</span>
  <span m=''659390''>one</span> <span m=''659560''>over</span> <span m=''659800''>here,</span>
  <span m=''660010''>et</span> <span m=''660110''>cetera.</span> <span m=''661380''>And</span>
  <span m=''661570''>then,</span> <span m=''662030''>in</span> <span m=''662840''>converting</span>
  <span m=''663310''>to</span> <span m=''663450''>a</span> <span m=''663500''>discreet-time</span>
  <span m=''664190''>sequence,</span> <span m=''664930''>there</span> <span m=''665370''>is</span>
  <span m=''666210''>the</span> <span m=''666310''>associated</span> <span m=''667910''>frequency</span>
  <span m=''668480''>normalization,</span> <span m=''669840''>so</span> <span m=''670180''>that</span>
  <span m=''670420''>the</span> <span m=''670500''>sampling</span> <span m=''671020''>frequency</span>
  <span m=''672330''>gets</span> <span m=''672980''>normalized</span> <span m=''674150''>to</span>
  <span m=''674300''>a</span> <span m=''674360''>frequency</span> <span m=''675280''>of</span>
  <span m=''675420''>2</span> <span m=''675620''>pi.</span> <span m=''677230''>OK,</span>
  <span m=''677580''>now,</span> <span m=''678130''>at</span> <span m=''678290''>that</span>
  <span m=''678570''>point,</span> <span m=''680420''>where</span> <span m=''680660''>we</span>
  <span m=''680860''>are</span> <span m=''681350''>in</span> <span m=''682430''>the</span>
  <span m=''682960''>system</span> <span m=''684680''>is</span> <span m=''685490''>at</span>
  <span m=''686670''>this</span> <span m=''686950''>point,</span> <span m=''687840''>so</span>
  <span m=''688090''>that</span> <span m=''688380''>we''ve</span> <span m=''689000''>converted</span>
  <span m=''689490''>to</span> <span m=''689610''>a</span> <span m=''689670''>sequence.</span>
  <span m=''690750''>We</span> <span m=''690920''>now</span> <span m=''691520''>want</span>
  <span m=''691780''>to</span> <span m=''691890''>carry</span> <span m=''692300''>out</span>
  <span m=''692480''>some</span> <span m=''692610''>filtering,</span> <span m=''693570''>and</span>
  <span m=''693770''>then,</span> <span m=''693990''>after</span> <span m=''694350''>that</span>
  <span m=''694580''>filtering,</span> <span m=''695520''>convert</span> <span m=''695950''>back</span>
  <span m=''696240''>to</span> <span m=''696350''>a</span> <span m=''696430''>continuous-time</span>
  <span m=''697240''>signal.</span> </p><p><span m=''700060''>All</span> <span m=''700130''>right,</span>
  <span m=''700350''>so,</span> <span m=''701000''>here</span> <span m=''701210''>we</span>
  <span m=''701390''>are</span> <span m=''701790''>at</span> <span m=''702430''>the</span>
  <span m=''703150''>spectrum</span> <span m=''703930''>associated</span> <span m=''705240''>with</span>
  <span m=''705790''>the</span> <span m=''706810''>sequence.</span> <span m=''709040''>And</span>
  <span m=''709190''>now,</span> <span m=''709790''>the</span> <span m=''710260''>processing</span>
  <span m=''710980''>that</span> <span m=''711110''>we''re</span> <span m=''711230''>carrying</span>
  <span m=''711780''>out</span> <span m=''712500''>is</span> <span m=''713040''>linear</span>
  <span m=''713410''>time</span> <span m=''713720''>and variant</span> <span m=''714270''>filtering</span>
  <span m=''715010''>in</span> <span m=''715220''>the</span> <span m=''715400''>discreet-time</span>
  <span m=''716170''>domain.</span> <span m=''717380''>And</span> <span m=''717500''>what</span>
  <span m=''717700''>that</span> <span m=''717930''>corresponds</span> <span m=''718650''>to,</span>
  <span m=''718830''>then,</span> <span m=''719300''>is</span> <span m=''719950''>multiplying</span>
  <span m=''721300''>this</span> <span m=''721560''>spectrum</span> <span m=''722720''>by</span>
  <span m=''723490''>the</span> <span m=''723600''>filter</span> <span m=''723970''>frequency</span>
  <span m=''724520''>response.</span> <span m=''725080''>And</span> <span m=''725170''>I''ve</span>
  <span m=''725300''>chosen</span> <span m=''726470''>a</span> <span m=''726650''>particular</span>
  <span m=''727610''>shape.</span> <span m=''728250''>And</span> <span m=''728480''>again,</span>
  <span m=''728820''>it''s</span> <span m=''729000''>not</span> <span m=''729180''>the</span>
  <span m=''729250''>shape</span> <span m=''729590''>that''s</span> <span m=''729750''>important</span>
  <span m=''730230''>to</span> <span m=''730320''>the</span> <span m=''730430''>discussion,</span>
  <span m=''731950''>but</span> <span m=''732220''>the</span> <span m=''732310''>fact,</span>
  <span m=''732740''>for</span> <span m=''732890''>example,</span> <span m=''733480''>that</span>
  <span m=''733630''>it</span> <span m=''733720''>has</span> <span m=''734150''>a</span>
  <span m=''734310''>particular</span> <span m=''734790''>cutoff frequency,</span>
  <span m=''735750''>which</span> <span m=''735980''>we will</span> <span m=''736470''>track</span>
  <span m=''737400''>as</span> <span m=''737710''>we</span> <span m=''737800''>work</span>
  <span m=''738070''>through</span> <span m=''738310''>this.</span> </p><p><span m=''739790''>And</span>
  <span m=''740020''>so</span> <span m=''740220''>now,</span> <span m=''741200''>the</span>
  <span m=''741640''>spectrum</span> <span m=''742360''>of</span> <span m=''742500''>y
  of</span> <span m=''742830''>n,</span> <span m=''743650''>the</span> <span m=''743800''>output</span>
  <span m=''744350''>of</span> <span m=''744470''>the</span> <span m=''744550''>digital</span>
  <span m=''744970''>filter,</span> <span m=''745870''>is</span> <span m=''746030''>the</span>
  <span m=''746110''>product</span> <span m=''746830''>of</span> <span m=''747020''>this</span>
  <span m=''747300''>spectrum,</span> <span m=''748370''>and</span> <span m=''749330''>the</span>
  <span m=''750120''>Fourier</span> <span m=''750570''>transform,</span> <span m=''751230''>or</span>
  <span m=''751320''>frequency</span> <span m=''751850''>response,</span> <span m=''752510''>of</span>
  <span m=''752800''>the</span> <span m=''752940''>digital</span> <span m=''753290''>filter.</span>
  </p><p><span m=''756320''>Now,</span> <span m=''756760''>in</span> <span m=''756910''>working</span>
  <span m=''757250''>our</span> <span m=''757380''>way</span> <span m=''757580''>through,</span>
  <span m=''758330''>we''re</span> <span m=''758510''>going</span> <span m=''758710''>to</span>
  <span m=''758850''>take</span> <span m=''759060''>the</span> <span m=''759200''>output</span>
  <span m=''759550''>of</span> <span m=''759600''>the</span> <span m=''759680''>filter</span>
  <span m=''761290''>and</span> <span m=''761710''>undo</span> <span m=''762140''>the</span>
  <span m=''762270''>two-step</span> <span m=''762780''>process.</span> <span m=''763880''>So</span>
  <span m=''764120''>we</span> <span m=''764250''>now</span> <span m=''764450''>want</span>
  <span m=''764570''>to</span> <span m=''764650''>take</span> <span m=''764930''>that</span>
  <span m=''765140''>sequence,</span> <span m=''766080''>convert</span> <span m=''766510''>it
  to</span> <span m=''766620''>an</span> <span m=''766700''>impulse</span> <span m=''767160''>train,</span>
  <span m=''768610''>and</span> <span m=''768740''>then</span> <span m=''768900''>take</span>
  <span m=''769140''>that</span> <span m=''769330''>impulse</span> <span m=''769790''>train</span>
  <span m=''770400''>and</span> <span m=''770600''>desample</span> <span m=''771550''>through</span>
  <span m=''771770''>a</span> <span m=''771840''>low-pass</span> <span m=''772370''>filter.</span>
  <span m=''773460''>So,</span> <span m=''774450''>here</span> <span m=''774650''>we</span>
  <span m=''774830''>are</span> <span m=''775330''>now</span> <span m=''775740''>at</span>
  <span m=''775940''>the</span> <span m=''776090''>output</span> <span m=''776480''>of</span>
  <span m=''776530''>the</span> <span m=''776620''>digital</span> <span m=''776980''>filter.</span>
  <span m=''779220''>We</span> <span m=''779420''>then</span> <span m=''780200''>convert</span>
  <span m=''780680''>that</span> <span m=''781240''>to</span> <span m=''781400''>an</span>
  <span m=''781480''>impulse</span> <span m=''781950''>train.</span> <span m=''782340''>Well</span>
  <span m=''782490''>that''s</span> <span m=''782770''>really</span> <span m=''783090''>undoing</span>
  <span m=''783520''>the</span> <span m=''783640''>original</span> <span m=''784030''>time</span>
  <span m=''784330''>normalization.</span> </p><p><span m=''785730''>And</span> <span
  m=''785880''>so,</span> <span m=''786060''>what</span> <span m=''786250''>that</span>
  <span m=''786490''>means,</span> <span m=''786970''>is</span> <span m=''787270''>that</span>
  <span m=''787890''>we</span> <span m=''788920''>are</span> <span m=''789880''>undoing</span>
  <span m=''790440''>the</span> <span m=''790520''>frequency</span> <span m=''791120''>normalization.</span>
  <span m=''792080''>In</span> <span m=''792250''>particular,</span> <span m=''793410''>we''re</span>
  <span m=''793540''>dividing</span> <span m=''794120''>the</span> <span m=''794200''>frequency</span>
  <span m=''794820''>axis</span> <span m=''795990''>by</span> <span m=''796820''>capital</span>
  <span m=''797320''>T.</span> <span m=''798120''>Whereas,</span> <span m=''798970''>this</span>
  <span m=''799210''>point</span> <span m=''800110''>in</span> <span m=''800680''>y</span>
  <span m=''800960''>of</span> <span m=''801070''>omega</span> <span m=''802160''>was</span>
  <span m=''802430''>2</span> <span m=''802630''>pi,</span> <span m=''803490''>now</span>
  <span m=''803950''>it''s</span> <span m=''804150''>2</span> <span m=''804320''>pi</span>
  <span m=''804610''>over</span> <span m=''804870''>capital</span> <span m=''805370''>T.</span>
  <span m=''806600''>What</span> <span m=''806790''>that</span> <span m=''807000''>means</span>
  <span m=''807420''>is</span> <span m=''807620''>that,</span> <span m=''808730''>equivalently,</span>
  <span m=''809540''>we''re</span> <span m=''809680''>multiplying</span> <span m=''810390''>this</span>
  <span m=''810620''>spectrum</span> <span m=''811810''>by</span> <span m=''812580''>the</span>
  <span m=''812990''>frequency</span> <span m=''813550''>response</span> <span m=''814240''>of</span>
  <span m=''814370''>the</span> <span m=''814450''>digital</span> <span m=''814850''>filter,</span>
  <span m=''815830''>but</span> <span m=''816030''>now</span> <span m=''816270''>linearly-scaled</span>
  <span m=''817590''>in</span> <span m=''817700''>frequency,</span> <span m=''818880''>so</span>
  <span m=''819150''>that</span> <span m=''819590''>what</span> <span m=''819780''>was</span>
  <span m=''819940''>a</span> <span m=''820030''>cutoff frequency</span> <span m=''820940''>of</span>
  <span m=''821040''>omega</span> <span m=''821440''>sub</span> <span m=''821620''>c</span>
  <span m=''822450''>is</span> <span m=''822640''>now</span> <span m=''822940''>cutoff
  frequency</span> <span m=''824030''>of</span> <span m=''824380''>omega</span> <span
  m=''824830''>sub c,</span> <span m=''825740''>divided</span> <span m=''826320''>by</span>
  <span m=''826500''>capital</span> <span m=''827060''>T.</span> </p><p><span m=''828590''>So</span>
  <span m=''829610''>now,</span> <span m=''830310''>the</span> <span m=''830420''>next</span>
  <span m=''830640''>step</span> <span m=''830880''>in</span> <span m=''830960''>the</span>
  <span m=''831040''>process</span> <span m=''831810''>is</span> <span m=''832550''>the</span>
  <span m=''832710''>reconstructing</span> <span m=''833760''>low-pass</span> <span
  m=''834350''>filter.</span> <span m=''835290''>And</span> <span m=''835490''>what</span>
  <span m=''835680''>that</span> <span m=''835910''>extracts</span> <span m=''836680''>is</span>
  <span m=''836820''>simply</span> <span m=''837470''>the</span> <span m=''837570''>portion</span>
  <span m=''838270''>of</span> <span m=''838860''>this</span> <span m=''839090''>periodic</span>
  <span m=''839680''>spectrum</span> <span m=''840470''>around</span> <span m=''840740''>the</span>
  <span m=''840860''>origin.</span> <span m=''842020''>And</span> <span m=''842220''>so</span>
  <span m=''842420''>finally,</span> <span m=''843270''>then,</span> <span m=''844070''>the</span>
  <span m=''844150''>spectrum</span> <span m=''844870''>of</span> <span m=''845050''>the</span>
  <span m=''845210''>output</span> <span m=''846270''>of</span> <span m=''846420''>the</span>
  <span m=''846550''>overall</span> <span m=''847000''>system</span> <span m=''848280''>will</span>
  <span m=''848520''>be</span> <span m=''849220''>the</span> <span m=''849310''>spectrum</span>
  <span m=''850110''>of</span> <span m=''850290''>the</span> <span m=''850450''>input</span>
  <span m=''851920''>multiplied</span> <span m=''853330''>by</span> <span m=''854460''>a</span>
  <span m=''854530''>frequency</span> <span m=''855140''>response,</span> <span m=''857090''>which</span>
  <span m=''857910''>is</span> <span m=''858550''>the</span> <span m=''859230''>digital</span>
  <span m=''859680''>filter</span> <span m=''860160''>frequency</span> <span m=''860730''>response</span>
  <span m=''861820''>frequency</span> <span m=''862520''>scaled</span> <span m=''863730''>by</span>
  <span m=''864080''>dividing</span> <span m=''865040''>that</span> <span m=''865780''>digital</span>
  <span m=''866130''>filter</span> <span m=''866470''>frequency</span> <span m=''867040''>axis</span>
  <span m=''867790''>by</span> <span m=''867950''>capital</span> <span m=''868215''>T.</span>
  </p><p><span m=''870360''>OK,</span> <span m=''871300''>now,</span> <span m=''872320''>what</span>
  <span m=''872500''>we</span> <span m=''872620''>can</span> <span m=''872790''>ask</span>
  <span m=''873350''>is,</span> <span m=''874000''>we''ve</span> <span m=''874350''>got</span>
  <span m=''874570''>this</span> <span m=''874770''>processing--</span> <span m=''875580''>we''ve</span>
  <span m=''875740''>converted</span> <span m=''876170''>to</span> <span m=''876250''>discreet-time,</span>
  <span m=''876660''>and</span> <span m=''876980''>we''ve</span> <span m=''877170''>gone</span>
  <span m=''877390''>back</span> <span m=''877640''>to</span> <span m=''877740''>continuous-time,</span>
  <span m=''879060''>and</span> <span m=''879180''>one</span> <span m=''879380''>can</span>
  <span m=''879550''>ask</span> <span m=''880030''>now</span> <span m=''880980''>what</span>
  <span m=''881590''>equivalent,</span> <span m=''882570''>overall</span> <span m=''883530''>continuous-time</span>
  <span m=''884360''>system</span> <span m=''884830''>does</span> <span m=''885010''>that</span>
  <span m=''885220''>correspond</span> <span m=''885900''>to?</span> <span m=''886970''>In</span>
  <span m=''887070''>other</span> <span m=''887210''>words,</span> <span m=''887500''>if</span>
  <span m=''887630''>we--</span> <span m=''888550''>that,</span> <span m=''888740''>of</span>
  <span m=''888830''>course,</span> <span m=''889120''>is</span> <span m=''889260''>a</span>
  <span m=''889320''>continuous-time</span> <span m=''890090''>system,</span> <span
  m=''890560''>it''s</span> <span m=''890680''>a</span> <span m=''890730''>continuous-time</span>
  <span m=''891470''>input</span> <span m=''891800''>and</span> <span m=''891910''>continuous-time</span>
  <span m=''892430''>time</span> <span m=''892700''>output--</span> <span m=''893790''>and</span>
  <span m=''894500''>the</span> <span m=''894660''>overall</span> <span m=''895110''>system,</span>
  <span m=''896680''>then,</span> <span m=''897580''>would</span> <span m=''897750''>be</span>
  <span m=''897960''>one</span> <span m=''898480''>that</span> <span m=''898590''>would</span>
  <span m=''898800''>give</span> <span m=''898980''>us</span> <span m=''899210''>exactly</span>
  <span m=''899730''>the</span> <span m=''899830''>same</span> <span m=''900330''>output</span>
  <span m=''900800''>spectrum</span> <span m=''901340''>as</span> <span m=''901530''>we''re</span>
  <span m=''901640''>getting.</span> <span m=''902540''>Well,</span> <span m=''902840''>what
  is that?</span> </p><p><span m=''904200''>What</span> <span m=''904360''>we</span>
  <span m=''904500''>have</span> <span m=''905030''>is</span> <span m=''905230''>an</span>
  <span m=''905310''>output</span> <span m=''905740''>spectrum,</span> <span m=''906740''>which</span>
  <span m=''907030''>is</span> <span m=''907470''>the</span> <span m=''907610''>product</span>
  <span m=''908480''>of</span> <span m=''909000''>the</span> <span m=''909120''>input</span>
  <span m=''909560''>spectrum</span> <span m=''910610''>and</span> <span m=''911210''>the</span>
  <span m=''911310''>digital</span> <span m=''911780''>filter</span> <span m=''912210''>frequency</span>
  <span m=''912790''>characteristic</span> <span m=''913950''>frequency-scaled.</span>
  <span m=''916150''>And</span> <span m=''916370''>so,</span> <span m=''916830''>in</span>
  <span m=''917000''>fact,</span> <span m=''918010''>the</span> <span m=''918690''>resulting</span>
  <span m=''921570''>continuous-time</span> <span m=''922110''>time</span> <span m=''922360''>filter</span>
  <span m=''923290''>is</span> <span m=''923420''>simply</span> <span m=''924180''>the</span>
  <span m=''924720''>digital</span> <span m=''925110''>filter</span> <span m=''926040''>with</span>
  <span m=''927080''>an</span> <span m=''927210''>appropriate</span> <span m=''927880''>frequency</span>
  <span m=''928350''>scaling.</span> <span m=''929120''>In</span> <span m=''929290''>other</span>
  <span m=''929470''>words,</span> <span m=''929890''>with</span> <span m=''930030''>the</span>
  <span m=''930110''>frequency</span> <span m=''930690''>axis</span> <span m=''931120''>divided</span>
  <span m=''931560''>by</span> <span m=''931710''>capital</span> <span m=''932240''>T.</span>
  <span m=''934390''>So</span> <span m=''934780''>said</span> <span m=''935040''>another</span>
  <span m=''935360''>way,</span> <span m=''937120''>if</span> <span m=''937780''>we</span>
  <span m=''940600''>show</span> <span m=''941050''>here</span> <span m=''941740''>the</span>
  <span m=''942200''>frequency</span> <span m=''942840''>response</span> <span m=''943740''>of</span>
  <span m=''944580''>the</span> <span m=''947210''>original</span> <span m=''948070''>digital</span>
  <span m=''948490''>filter,</span> <span m=''950410''>then</span> <span m=''951090''>the</span>
  <span m=''951510''>corresponding</span> <span m=''953160''>continuous-time</span>
  <span m=''954110''>filter</span> <span m=''955630''>would</span> <span m=''956150''>be</span>
  <span m=''956990''>this,</span> <span m=''957720''>frequency-scaled.</span> </p><p><span
  m=''959470''>And</span> <span m=''959630''>then,</span> <span m=''959810''>because</span>
  <span m=''960500''>of</span> <span m=''960900''>the</span> <span m=''961160''>associated</span>
  <span m=''961810''>low-pass</span> <span m=''962360''>filtering</span> <span m=''962930''>and</span>
  <span m=''963040''>the</span> <span m=''963130''>reconstruction,</span> <span m=''964520''>we</span>
  <span m=''964700''>would</span> <span m=''965160''>select</span> <span m=''965700''>out</span>
  <span m=''966060''>just</span> <span m=''966440''>one</span> <span m=''966720''>of</span>
  <span m=''966810''>these</span> <span m=''967030''>periods--</span> <span m=''967510''>in</span>
  <span m=''967600''>particular,</span> <span m=''967890''>the</span> <span m=''968180''>portion</span>
  <span m=''968580''>around</span> <span m=''968840''>the</span> <span m=''968950''>origin.</span>
  <span m=''970070''>And</span> <span m=''970960''>the</span> <span m=''971090''>essential</span>
  <span m=''971530''>consequence</span> <span m=''972220''>of</span> <span m=''972310''>that</span>
  <span m=''972740''>is that</span> <span m=''973170''>the</span> <span m=''973270''>corresponding</span>
  <span m=''974490''>continuous-time</span> <span m=''975360''>filter,</span> <span
  m=''975900''>then,</span> <span m=''976710''>is</span> <span m=''977580''>given</span>
  <span m=''977860''>by</span> <span m=''978100''>this.</span> <span m=''978790''>And</span>
  <span m=''979250''>these</span> <span m=''979570''>two</span> <span m=''980060''>are</span>
  <span m=''980240''>related</span> <span m=''981150''>simply</span> <span m=''981860''>by</span>
  <span m=''982630''>a</span> <span m=''982870''>linear</span> <span m=''983320''>scaling</span>
  <span m=''984000''>of</span> <span m=''984150''>the</span> <span m=''984240''>frequency</span>
  <span m=''984810''>axis.</span> <span m=''985840''>And</span> <span m=''986010''>note</span>
  <span m=''986570''>that,</span> <span m=''987020''>where</span> <span m=''987260''>the</span>
  <span m=''987380''>digital</span> <span m=''987750''>filter</span> <span m=''988140''>has</span>
  <span m=''988320''>a</span> <span m=''988400''>cutoff</span> <span m=''988830''>frequency</span>
  <span m=''989530''>of</span> <span m=''989680''>omega</span> <span m=''990050''>sub</span>
  <span m=''990200''>c,</span> <span m=''991190''>the</span> <span m=''991390''>continuous-time</span>
  <span m=''992230''>filter</span> <span m=''992830''>has</span> <span m=''993040''>a</span>
  <span m=''993100''>cutoff</span> <span m=''993500''>frequency</span> <span m=''994200''>of</span>
  <span m=''994350''>omega</span> <span m=''994710''>sub</span> <span m=''994870''>c</span>
  <span m=''995680''>divided</span> <span m=''996170''>by</span> <span m=''996320''>capital</span>
  <span m=''996880''>T.</span> </p><p><span m=''998560''>So</span> <span m=''999140''>that''s</span>
  <span m=''999560''>the</span> <span m=''1000240''>linear</span> <span m=''1000560''>frequency</span>
  <span m=''1001070''>scaling.</span> <span m=''1001750''>And,</span> <span m=''1002580''>by</span>
  <span m=''1002740''>the</span> <span m=''1002830''>way,</span> <span m=''1003020''>plant</span>
  <span m=''1003970''>away</span> <span m=''1004350''>for</span> <span m=''1004550''>now--</span>
  <span m=''1004960''>and</span> <span m=''1005070''>we''ll</span> <span m=''1005260''>return</span>
  <span m=''1005580''>to</span> <span m=''1005690''>this</span> <span m=''1005860''>point</span>
  <span m=''1006120''>later--</span> <span m=''1008170''>the</span> <span m=''1008580''>observation</span>
  <span m=''1009950''>that</span> <span m=''1010670''>even</span> <span m=''1010970''>if</span>
  <span m=''1011100''>the</span> <span m=''1011190''>digital</span> <span m=''1011610''>filter</span>
  <span m=''1012470''>frequency</span> <span m=''1012960''>response</span> <span m=''1013680''>is</span>
  <span m=''1013900''>fixed,</span> <span m=''1014790''>which</span> <span m=''1015190''>we</span>
  <span m=''1015340''>would</span> <span m=''1015450''>assume</span> <span m=''1015790''>it</span>
  <span m=''1015850''>is,</span> <span m=''1017020''>by</span> <span m=''1017720''>changing</span>
  <span m=''1018270''>the</span> <span m=''1018350''>sampling</span> <span m=''1018860''>frequency,</span>
  <span m=''1019570''>in</span> <span m=''1019720''>fact,</span> <span m=''1020380''>what</span>
  <span m=''1020520''>we''re</span> <span m=''1020740''>able</span> <span m=''1021060''>to</span>
  <span m=''1021180''>do</span> <span m=''1022190''>is</span> <span m=''1022440''>affect</span>
  <span m=''1022930''>a</span> <span m=''1023010''>linear</span> <span m=''1023370''>scaling</span>
  <span m=''1024130''>all</span> <span m=''1024329''>of</span> <span m=''1024660''>the</span>
  <span m=''1024990''>equivalent</span> <span m=''1025510''>continuous-time</span>
  <span m=''1026410''>filter.</span> </p><p><span m=''1029170''>OK,</span> <span m=''1029390''>well,</span>
  <span m=''1029550''>this</span> <span m=''1029730''>is</span> <span m=''1030430''>pretty</span>
  <span m=''1030609''>much</span> <span m=''1030849''>the</span> <span m=''1030950''>process</span>
  <span m=''1031630''>and</span> <span m=''1031730''>the</span> <span m=''1031829''>analysis,</span>
  <span m=''1032960''>but</span> <span m=''1033579''>to</span> <span m=''1034190''>highlight</span>
  <span m=''1035430''>a</span> <span m=''1035520''>number</span> <span m=''1035819''>of</span>
  <span m=''1035869''>the</span> <span m=''1036010''>issues</span> <span m=''1036470''>and</span>
  <span m=''1036569''>emphasize</span> <span m=''1037160''>these</span> <span m=''1037390''>points,</span>
  <span m=''1038319''>what</span> <span m=''1038740''>I''d</span> <span m=''1039200''>like</span>
  <span m=''1039589''>to</span> <span m=''1041170''>do</span> <span m=''1041500''>is</span>
  <span m=''1041720''>illustrate</span> <span m=''1042690''>some</span> <span m=''1043030''>of</span>
  <span m=''1043170''>this</span> <span m=''1043819''>with</span> <span m=''1044359''>a</span>
  <span m=''1044530''>videotape</span> <span m=''1045220''>demonstration</span> <span
  m=''1046359''>that,</span> <span m=''1047040''>in</span> <span m=''1047180''>fact,</span>
  <span m=''1048060''>was</span> <span m=''1048650''>made</span> <span m=''1049180''>originally</span>
  <span m=''1049840''>as</span> <span m=''1050150''>part</span> <span m=''1050410''>of</span>
  <span m=''1050470''>another</span> <span m=''1050810''>course--</span> <span m=''1051230''>a</span>
  <span m=''1051300''>course</span> <span m=''1052310''>devoted</span> <span m=''1053210''>entirely</span>
  <span m=''1054200''>to</span> <span m=''1055390''>digital</span> <span m=''1055870''>signal</span>
  <span m=''1056250''>processing,</span> <span m=''1056930''>which</span> <span m=''1057270''>essentially</span>
  <span m=''1057880''>is</span> <span m=''1058120''>discreet-time</span> <span m=''1058530''>time</span>
  <span m=''1058750''>processing,</span> <span m=''1059950''>whether</span> <span
  m=''1060270''>or</span> <span m=''1060310''>not</span> <span m=''1060570''>it''s</span>
  <span m=''1060690''>related</span> <span m=''1061100''>to</span> <span m=''1061200''>continuous-time</span>
  <span m=''1061980''>signals.</span> <span m=''1063060''>And</span> <span m=''1063570''>what</span>
  <span m=''1063730''>I''d</span> <span m=''1063860''>like</span> <span m=''1064180''>to</span>
  <span m=''1064830''>now</span> <span m=''1065700''>focus</span> <span m=''1066210''>on</span>
  <span m=''1066630''>are</span> <span m=''1067140''>some</span> <span m=''1067400''>of</span>
  <span m=''1067460''>the</span> <span m=''1067540''>details</span> <span m=''1068180''>of</span>
  <span m=''1068240''>that</span> <span m=''1068460''>demonstration.</span> </p><p><span
  m=''1070980''>In</span> <span m=''1071230''>the</span> <span m=''1071640''>demonstration,</span>
  <span m=''1073360''>the</span> <span m=''1074350''>specific</span> <span m=''1075530''>impulse</span>
  <span m=''1076040''>response</span> <span m=''1077010''>that</span> <span m=''1077450''>is</span>
  <span m=''1078430''>used</span> <span m=''1078990''>for</span> <span m=''1079130''>the</span>
  <span m=''1079790''>digital</span> <span m=''1080140''>filter,</span> <span m=''1080700''>or</span>
  <span m=''1080940''>discreet-time</span> <span m=''1081600''>filter,</span> <span
  m=''1082120''>is</span> <span m=''1082790''>the</span> <span m=''1082880''>one</span>
  <span m=''1083430''>that</span> <span m=''1083740''>I</span> <span m=''1083880''>show</span>
  <span m=''1084240''>here.</span> <span m=''1086160''>And</span> <span m=''1086820''>the</span>
  <span m=''1087390''>associated</span> <span m=''1089500''>frequency</span> <span
  m=''1090110''>response</span> <span m=''1091030''>is</span> <span m=''1091780''>the</span>
  <span m=''1091880''>frequency</span> <span m=''1092360''>response</span> <span m=''1093070''>of</span>
  <span m=''1093550''>a</span> <span m=''1093780''>discreet-time,</span> <span m=''1095190''>low-pass</span>
  <span m=''1095830''>filter,</span> <span m=''1096460''>as</span> <span m=''1096840''>I</span>
  <span m=''1096930''>indicate</span> <span m=''1097410''>below.</span> <span m=''1098800''>And</span>
  <span m=''1099660''>the</span> <span m=''1099790''>cutoff</span> <span m=''1100150''>frequency</span>
  <span m=''1100620''>of</span> <span m=''1100680''>that</span> <span m=''1100880''>filter--</span>
  <span m=''1101520''>as</span> <span m=''1101670''>I</span> <span m=''1101760''>indicate,</span>
  <span m=''1102400''>the</span> <span m=''1102480''>filter</span> <span m=''1102840''>was</span>
  <span m=''1103030''>designed</span> <span m=''1103570''>as</span> <span m=''1103740''>a</span>
  <span m=''1104280''>discreet-time</span> <span m=''1104890''>filter</span> <span
  m=''1105260''>with</span> <span m=''1105380''>a</span> <span m=''1105460''>cutoff</span>
  <span m=''1105860''>frequency</span> <span m=''1106560''>of</span> <span m=''1106690''>pi</span>
  <span m=''1107250''>over</span> <span m=''1107560''>5.</span> </p><p><span m=''1108680''>And</span>
  <span m=''1108940''>let</span> <span m=''1109080''>me</span> <span m=''1109210''>just</span>
  <span m=''1109700''>draw</span> <span m=''1109910''>your</span> <span m=''1110100''>attention</span>
  <span m=''1110550''>to</span> <span m=''1110660''>the</span> <span m=''1110750''>fact</span>
  <span m=''1111670''>that</span> <span m=''1112250''>pi</span> <span m=''1112540''>over</span>
  <span m=''1112850''>5</span> <span m=''1113550''>is</span> <span m=''1114040''>also</span>
  <span m=''1115220''>a</span> <span m=''1115380''>10th</span> <span m=''1116740''>of</span>
  <span m=''1117370''>2</span> <span m=''1117600''>pi.</span> <span m=''1119200''>And</span>
  <span m=''1119490''>so</span> <span m=''1120370''>in</span> <span m=''1120520''>fact</span>
  <span m=''1121170''>the</span> <span m=''1121810''>digital</span> <span m=''1122470''>or</span>
  <span m=''1122600''>discreet-time</span> <span m=''1123350''>filter</span> <span
  m=''1123740''>cutoff</span> <span m=''1124140''>frequency</span> <span m=''1125240''>is</span>
  <span m=''1125420''>a</span> <span m=''1125510''>10th</span> <span m=''1125930''>of</span>
  <span m=''1126040''>2</span> <span m=''1126260''>pi.</span> <span m=''1127250''>And</span>
  <span m=''1127410''>as</span> <span m=''1127550''>I''ll</span> <span m=''1127640''>stress</span>
  <span m=''1128220''>again</span> <span m=''1128540''>shortly,</span> <span m=''1129620''>remember</span>
  <span m=''1130050''>that,</span> <span m=''1130310''>in</span> <span m=''1130540''>the</span>
  <span m=''1131230''>frequency</span> <span m=''1131680''>normalization</span> <span
  m=''1132690''>or</span> <span m=''1132940''>unnormalization,</span> <span m=''1134590''>2</span>
  <span m=''1134820''>pi</span> <span m=''1135670''>represents,</span> <span m=''1136580''>in</span>
  <span m=''1136710''>effect,</span> <span m=''1137180''>the</span> <span m=''1137260''>sampling</span>
  <span m=''1137760''>frequency.</span> <span m=''1138940''>And</span> <span m=''1139120''>so</span>
  <span m=''1139970''>the</span> <span m=''1140080''>consequence</span> <span m=''1140750''>of</span>
  <span m=''1140850''>that</span> <span m=''1141190''>is</span> <span m=''1141440''>that</span>
  <span m=''1141970''>the</span> <span m=''1142100''>cutoff frequency</span> <span
  m=''1143080''>really,</span> <span m=''1143550''>is</span> <span m=''1143730''>going</span>
  <span m=''1143970''>to</span> <span m=''1144100''>be</span> <span m=''1144240''>associated</span>
  <span m=''1145400''>with</span> <span m=''1145530''>a</span> <span m=''1145630''>10th</span>
  <span m=''1146410''>of</span> <span m=''1146660''>the</span> <span m=''1146750''>sampling</span>
  <span m=''1147200''>frequency.</span> <span m=''1147760''>But,</span> <span m=''1148310''>for</span>
  <span m=''1148430''>now,</span> <span m=''1148650''>keep</span> <span m=''1148880''>in</span>
  <span m=''1148970''>mind</span> <span m=''1149300''>that</span> <span m=''1149430''>it''s</span>
  <span m=''1149560''>just</span> <span m=''1149720''>simply</span> <span m=''1150070''>a
  10th</span> <span m=''1150530''>of</span> <span m=''1150720''>2 pi.</span> </p><p></p><p><span
  m=''1153040''>Now,</span> <span m=''1153770''>the</span> <span m=''1154230''>equivalent</span>
  <span m=''1156810''>continuous-time</span> <span m=''1158000''>system,</span> <span
  m=''1158910''>in</span> <span m=''1159040''>terms</span> <span m=''1159580''>of</span>
  <span m=''1159720''>the</span> <span m=''1159810''>impulse</span> <span m=''1160260''>response,</span>
  <span m=''1161350''>is,</span> <span m=''1161540''>of</span> <span m=''1161660''>course,</span>
  <span m=''1162310''>a</span> <span m=''1162660''>band-limited</span> <span m=''1163600''>interpolation</span>
  <span m=''1167780''>of</span> <span m=''1167890''>the</span> <span m=''1168330''>impulse</span>
  <span m=''1168770''>response</span> <span m=''1170100''>associated</span> <span
  m=''1170890''>with</span> <span m=''1171200''>the</span> <span m=''1171350''>discreet-time</span>
  <span m=''1172320''>filter.</span> <span m=''1173380''>And</span> <span m=''1173730''>in</span>
  <span m=''1173790''>the</span> <span m=''1173860''>frequency</span> <span m=''1174390''>domain,</span>
  <span m=''1174940''>the</span> <span m=''1175030''>frequency</span> <span m=''1175520''>response</span>
  <span m=''1176260''>is</span> <span m=''1177080''>correspondingly</span> <span m=''1177820''>a</span>
  <span m=''1178110''>time-scaled,</span> <span m=''1182550''>frequency</span> <span
  m=''1183030''>scaled</span> <span m=''1183920''>version</span> <span m=''1184310''>of</span>
  <span m=''1184380''>the</span> <span m=''1184460''>frequency</span> <span m=''1184970''>response.</span>
  <span m=''1186290''>So,</span> <span m=''1186850''>in</span> <span m=''1186980''>fact,</span>
  <span m=''1187450''>in</span> <span m=''1187680''>the</span> <span m=''1188000''>frequency</span>
  <span m=''1188610''>domain</span> <span m=''1189210''>and</span> <span m=''1189330''>in</span>
  <span m=''1189400''>the</span> <span m=''1189520''>time</span> <span m=''1189810''>domain</span>
  <span m=''1190900''>related</span> <span m=''1191410''>to</span> <span m=''1191700''>the</span>
  <span m=''1191820''>continuous-time</span> <span m=''1193070''>signal,</span> <span
  m=''1195690''>the</span> <span m=''1196230''>associated</span> <span m=''1196890''>impulse</span>
  <span m=''1197320''>response</span> <span m=''1198100''>is</span> <span m=''1198810''>what</span>
  <span m=''1199130''>I</span> <span m=''1199300''>indicate</span> <span m=''1199820''>here--</span>
  <span m=''1200540''>a</span> <span m=''1200940''>band-limited</span> <span m=''1201650''>interpolation</span>
  <span m=''1203030''>of</span> <span m=''1203160''>the</span> <span m=''1203270''>discreet-time</span>
  <span m=''1204490''>impulse</span> <span m=''1204950''>response</span> <span m=''1205950''>and</span>
  <span m=''1206570''>time scale,</span> <span m=''1207360''>in</span> <span m=''1207500''>fact.</span>
  <span m=''1209340''>And</span> <span m=''1209570''>the</span> <span m=''1209650''>frequency</span>
  <span m=''1210170''>response--</span> <span m=''1211000''>following</span> <span
  m=''1211470''>the</span> <span m=''1211530''>discussion</span> <span m=''1212140''>that</span>
  <span m=''1212410''>we''ve</span> <span m=''1212680''>previously</span> <span m=''1213220''>gone</span>
  <span m=''1213510''>through--</span> <span m=''1214410''>is</span> <span m=''1214910''>a</span>
  <span m=''1215110''>frequency-scaled</span> <span m=''1216020''>version</span> <span
  m=''1216960''>of</span> <span m=''1217210''>the</span> <span m=''1217300''>one</span>
  <span m=''1217470''>associated</span> <span m=''1218170''>with</span> <span m=''1218320''>the</span>
  <span m=''1218390''>digital</span> <span m=''1218750''>filter.</span> </p><p><span
  m=''1220630''>Well,</span> <span m=''1220990''>the</span> <span m=''1221090''>first</span>
  <span m=''1221390''>thing</span> <span m=''1221650''>that</span> <span m=''1221980''>I''ll</span>
  <span m=''1222070''>want</span> <span m=''1222520''>to</span> <span m=''1222670''>look</span>
  <span m=''1222970''>at</span> <span m=''1223390''>is</span> <span m=''1224050''>the</span>
  <span m=''1224190''>impulse</span> <span m=''1224660''>response.</span> <span m=''1225980''>And</span>
  <span m=''1226150''>when</span> <span m=''1226370''>we</span> <span m=''1226510''>do,</span>
  <span m=''1227600''>let</span> <span m=''1227910''>me</span> <span m=''1228470''>just</span>
  <span m=''1229220''>indicate</span> <span m=''1230100''>that</span> <span m=''1231190''>in</span>
  <span m=''1231660''>the</span> <span m=''1231870''>actual</span> <span m=''1232370''>implementation</span>
  <span m=''1233930''>things</span> <span m=''1234310''>are</span> <span m=''1234420''>slightly</span>
  <span m=''1234990''>different</span> <span m=''1235640''>than</span> <span m=''1236130''>they</span>
  <span m=''1236350''>are</span> <span m=''1236870''>associated</span> <span m=''1237600''>with</span>
  <span m=''1237770''>the</span> <span m=''1237900''>ideal</span> <span m=''1238300''>analysis.</span>
  <span m=''1239720''>In</span> <span m=''1239850''>particular,</span> <span m=''1241780''>in</span>
  <span m=''1242070''>converting</span> <span m=''1242930''>from</span> <span m=''1243610''>a</span>
  <span m=''1244790''>discreet-time</span> <span m=''1245530''>sequence</span> <span
  m=''1246920''>to</span> <span m=''1247320''>the</span> <span m=''1247450''>continuous-time</span>
  <span m=''1248310''>signal,</span> <span m=''1249620''>whereas</span> <span m=''1250530''>this</span>
  <span m=''1251170''>way</span> <span m=''1251370''>of</span> <span m=''1251490''>looking</span>
  <span m=''1251880''>at</span> <span m=''1252070''>it</span> <span m=''1252220''>is</span>
  <span m=''1252440''>convenient</span> <span m=''1253560''>in</span> <span m=''1253650''>the</span>
  <span m=''1253730''>context</span> <span m=''1254340''>of</span> <span m=''1254430''>the</span>
  <span m=''1254560''>analysis,</span> <span m=''1256090''>in</span> <span m=''1256530''>fact,</span>
  <span m=''1256970''>the</span> <span m=''1257060''>way</span> <span m=''1257240''>it''s</span>
  <span m=''1257480''>done</span> <span m=''1258440''>is</span> <span m=''1258670''>using</span>
  <span m=''1259630''>a</span> <span m=''1259740''>more</span> <span m=''1260010''>or</span>
  <span m=''1260070''>less</span> <span m=''1261070''>standard</span> <span m=''1262830''>digital</span>
  <span m=''1263220''>to</span> <span m=''1263340''>analog</span> <span m=''1263860''>converter.</span>
  </p><p><span m=''1264840''>And</span> <span m=''1264930''>what</span> <span m=''1265560''>a</span>
  <span m=''1265650''>digital</span> <span m=''1266090''>to</span> <span m=''1266200''>analog</span>
  <span m=''1266590''>converter</span> <span m=''1267240''>does,</span> <span m=''1267700''>as</span>
  <span m=''1267850''>I</span> <span m=''1267940''>indicated</span> <span m=''1268530''>in</span>
  <span m=''1268620''>the</span> <span m=''1268690''>previous</span> <span m=''1269170''>lecture,</span>
  <span m=''1270190''>is</span> <span m=''1271270''>to</span> <span m=''1271440''>convert</span>
  <span m=''1271850''>the</span> <span m=''1271940''>sequence</span> <span m=''1273380''>not</span>
  <span m=''1273670''>to</span> <span m=''1273800''>an</span> <span m=''1273900''>impulse</span>
  <span m=''1274380''>train</span> <span m=''1275020''>but,</span> <span m=''1275200''>in</span>
  <span m=''1275310''>fact,</span> <span m=''1275710''>to</span> <span m=''1275790''>go</span>
  <span m=''1276110''>directly</span> <span m=''1276710''>through</span> <span m=''1277310''>a</span>
  <span m=''1277400''>zero-order</span> <span m=''1278100''>hold.</span> <span m=''1278930''>And</span>
  <span m=''1279150''>so,</span> <span m=''1279520''>usually</span> <span m=''1279970''>what</span>
  <span m=''1280140''>comes</span> <span m=''1280440''>out</span> <span m=''1280640''>of</span>
  <span m=''1281030''>a</span> <span m=''1281250''>digital</span> <span m=''1281650''>to</span>
  <span m=''1281720''>analog</span> <span m=''1282140''>converter</span> <span m=''1283620''>is</span>
  <span m=''1283880''>a</span> <span m=''1283970''>staircase</span> <span m=''1285340''>type</span>
  <span m=''1285610''>of</span> <span m=''1285930''>signal</span> <span m=''1286580''>associated</span>
  <span m=''1287390''>with</span> <span m=''1287570''>a</span> <span m=''1287590''>zero-order</span>
  <span m=''1288240''>hold.</span> <span m=''1289150''>And</span> <span m=''1289310''>then,</span>
  <span m=''1289880''>the</span> <span m=''1290020''>result</span> <span m=''1290480''>of</span>
  <span m=''1290600''>that</span> <span m=''1291110''>is</span> <span m=''1291700''>low-pass</span>
  <span m=''1292360''>filtered</span> <span m=''1292860''>to</span> <span m=''1293000''>do</span>
  <span m=''1293160''>the</span> <span m=''1293260''>reconstruction.</span> </p><p><span
  m=''1294590''>So</span> <span m=''1295460''>what</span> <span m=''1295640''>we''ll</span>
  <span m=''1295790''>want</span> <span m=''1295950''>to</span> <span m=''1296010''>look</span>
  <span m=''1296300''>at,</span> <span m=''1296610''>then,</span> <span m=''1297050''>is</span>
  <span m=''1297950''>that</span> <span m=''1298190''>reconstruction,</span> <span
  m=''1299410''>first</span> <span m=''1300000''>with</span> <span m=''1300350''>just</span>
  <span m=''1300690''>an</span> <span m=''1300790''>impulse</span> <span m=''1301240''>input.</span>
  <span m=''1302170''>And</span> <span m=''1302380''>so,</span> <span m=''1302950''>what</span>
  <span m=''1303160''>we''ll</span> <span m=''1303340''>see</span> <span m=''1304280''>after</span>
  <span m=''1304670''>the</span> <span m=''1304790''>low-pass</span> <span m=''1305360''>filter,</span>
  <span m=''1306780''>for</span> <span m=''1307240''>the</span> <span m=''1307420''>impulse</span>
  <span m=''1307870''>response,</span> <span m=''1309200''>is</span> <span m=''1310750''>a</span>
  <span m=''1310930''>smooth</span> <span m=''1311330''>curve</span> <span m=''1311650''>like</span>
  <span m=''1311990''>this.</span> <span m=''1312900''>But</span> <span m=''1313310''>also,</span>
  <span m=''1314030''>as</span> <span m=''1314460''>part</span> <span m=''1314720''>of</span>
  <span m=''1314810''>the</span> <span m=''1314890''>demonstration,</span> <span m=''1316360''>what</span>
  <span m=''1316890''>I''ll</span> <span m=''1317120''>do,</span> <span m=''1317320''>just</span>
  <span m=''1317600''>to</span> <span m=''1318060''>show</span> <span m=''1318360''>the</span>
  <span m=''1318440''>zero-order</span> <span m=''1319090''>hold,</span> <span m=''1319840''>is</span>
  <span m=''1320000''>to</span> <span m=''1320150''>take</span> <span m=''1320730''>the</span>
  <span m=''1320790''>low-pass</span> <span m=''1321300''>filter</span> <span m=''1321690''>out</span>
  <span m=''1321910''>temporarily</span> <span m=''1323460''>and</span> <span m=''1323650''>then</span>
  <span m=''1324460''>put</span> <span m=''1324630''>it</span> <span m=''1324740''>back</span>
  <span m=''1325060''>in.</span> <span m=''1325610''>So</span> <span m=''1326170''>first,</span>
  <span m=''1326570''>let''s</span> <span m=''1326870''>just</span> <span m=''1327140''>look</span>
  <span m=''1327430''>at</span> <span m=''1327810''>the</span> <span m=''1327920''>filter</span>
  <span m=''1328310''>impulse</span> <span m=''1328690''>response.</span> </p><p><span
  m=''1331010''>What</span> <span m=''1331130''>we</span> <span m=''1331250''>see</span>
  <span m=''1331510''>here</span> <span m=''1331900''>is</span> <span m=''1332320''>the</span>
  <span m=''1332850''>impulse</span> <span m=''1333340''>response</span> <span m=''1334190''>of</span>
  <span m=''1334660''>the</span> <span m=''1334790''>overall</span> <span m=''1335220''>system.</span>
  <span m=''1337040''>And</span> <span m=''1338060''>we</span> <span m=''1338600''>observe,</span>
  <span m=''1338960''>for</span> <span m=''1339070''>one</span> <span m=''1339290''>thing,</span>
  <span m=''1339540''>that</span> <span m=''1339740''>it''s</span> <span m=''1339930''>a</span>
  <span m=''1339970''>symmetrical</span> <span m=''1340600''>impulse</span> <span
  m=''1341000''>response.</span> <span m=''1341620''>In</span> <span m=''1341720''>other</span>
  <span m=''1341920''>words,</span> <span m=''1342250''>corresponds</span> <span m=''1343000''>to</span>
  <span m=''1343250''>a</span> <span m=''1343460''>linear</span> <span m=''1343810''>phase</span>
  <span m=''1344200''>filter.</span> <span m=''1345170''>We</span> <span m=''1345300''>could</span>
  <span m=''1345420''>also</span> <span m=''1345730''>look</span> <span m=''1345980''>at</span>
  <span m=''1346060''>the</span> <span m=''1346150''>impulse</span> <span m=''1346600''>response</span>
  <span m=''1347420''>before</span> <span m=''1347870''>the</span> <span m=''1348190''>desampling</span>
  <span m=''1348950''>low-pass</span> <span m=''1349530''>filter--</span> <span m=''1349910''>let''s</span>
  <span m=''1350230''>take</span> <span m=''1350520''>out</span> <span m=''1350700''>the</span>
  <span m=''1350770''>desampling</span> <span m=''1351340''>low-pass</span> <span
  m=''1351850''>filter</span> <span m=''1352390''>slowly--</span> <span m=''1354050''>and</span>
  <span m=''1354870''>what</span> <span m=''1355430''>we</span> <span m=''1355670''>observe</span>
  <span m=''1356330''>is,</span> <span m=''1356750''>basically,</span> <span m=''1357350''>the</span>
  <span m=''1357500''>output</span> <span m=''1358300''>of</span> <span m=''1358470''>the</span>
  <span m=''1358700''>digital</span> <span m=''1359120''>to</span> <span m=''1359220''>analog</span>
  <span m=''1359760''>converter.</span> </p><p><span m=''1360570''>Which,</span> <span
  m=''1361420''>of</span> <span m=''1361520''>course,</span> <span m=''1361830''>is</span>
  <span m=''1361960''>a</span> <span m=''1362040''>staircase,</span> <span m=''1362760''>or</span>
  <span m=''1362830''>boxcar,</span> <span m=''1363440''>function,</span> <span m=''1364220''>not</span>
  <span m=''1364510''>an</span> <span m=''1364590''>impulse</span> <span m=''1365040''>train.</span>
  <span m=''1365425''>In</span> <span m=''1365810''>the</span> <span m=''1365970''>real</span>
  <span m=''1366230''>world,</span> <span m=''1366910''>the</span> <span m=''1367240''>output</span>
  <span m=''1367620''>of</span> <span m=''1367720''>a</span> <span m=''1367950''>D
  to A</span> <span m=''1368140''>converter,</span> <span m=''1368640''>generally,</span>
  <span m=''1369190''>is</span> <span m=''1369330''>a</span> <span m=''1369380''>boxcar</span>
  <span m=''1370200''>type</span> <span m=''1370460''>of</span> <span m=''1370550''>function.</span>
  <span m=''1371590''>We</span> <span m=''1371830''>can</span> <span m=''1372000''>put</span>
  <span m=''1372340''>the</span> <span m=''1372730''>desampling</span> <span m=''1373160''>filter</span>
  <span m=''1373530''>back</span> <span m=''1373840''>in</span> <span m=''1374030''>now</span>
  <span m=''1374560''>and</span> <span m=''1375460''>notice</span> <span m=''1375990''>that</span>
  <span m=''1376320''>the</span> <span m=''1376440''>effect</span> <span m=''1376840''>of</span>
  <span m=''1376920''>the</span> <span m=''1377170''>desampling</span> <span m=''1377650''>filter</span>
  <span m=''1378180''>is,</span> <span m=''1378330''>basically,</span> <span m=''1379230''>to</span>
  <span m=''1379610''>smooth</span> <span m=''1380180''>out</span> <span m=''1380740''>the</span>
  <span m=''1381220''>rough</span> <span m=''1381570''>edges</span> <span m=''1382200''>in</span>
  <span m=''1382780''>the</span> <span m=''1382980''>boxcar</span> <span m=''1384210''>output</span>
  <span m=''1384680''>from</span> <span m=''1384830''>the</span> <span m=''1384910''>D
  to A</span> <span m=''1385330''>converter.</span> </p><p><span m=''1388570''>OK,</span>
  <span m=''1389120''>so,</span> <span m=''1389970''>that''s</span> <span m=''1390400''>the</span>
  <span m=''1390520''>impulse</span> <span m=''1390950''>response</span> <span m=''1391440''>of
  the</span> <span m=''1391530''>system.</span> <span m=''1392210''>Now,</span> <span
  m=''1392810''>what</span> <span m=''1393080''>I''d</span> <span m=''1393450''>like</span>
  <span m=''1393730''>to</span> <span m=''1393840''>show</span> <span m=''1394370''>is</span>
  <span m=''1394710''>the</span> <span m=''1394990''>frequency</span> <span m=''1395910''>response</span>
  <span m=''1396410''>of</span> <span m=''1396460''>the</span> <span m=''1396540''>system.</span>
  <span m=''1397650''>And</span> <span m=''1398020''>to</span> <span m=''1398120''>measure</span>
  <span m=''1398370''>the</span> <span m=''1398470''>frequency</span> <span m=''1398990''>response,</span>
  <span m=''1399520''>of</span> <span m=''1399620''>course,</span> <span m=''1399930''>what</span>
  <span m=''1400240''>we</span> <span m=''1400390''>can</span> <span m=''1400570''>do</span>
  <span m=''1400980''>is</span> <span m=''1401740''>put</span> <span m=''1402090''>a</span>
  <span m=''1402580''>sine</span> <span m=''1403020''>wave</span> <span m=''1404040''>into</span>
  <span m=''1404330''>the</span> <span m=''1404680''>system</span> <span m=''1405940''>and</span>
  <span m=''1406690''>look</span> <span m=''1407090''>at</span> <span m=''1407620''>the</span>
  <span m=''1408260''>sinusoidal</span> <span m=''1409010''>output.</span> </p><p><span
  m=''1409780''>So,</span> <span m=''1410110''>in</span> <span m=''1410240''>particular</span>
  <span m=''1410820''>now,</span> <span m=''1411210''>what</span> <span m=''1411400''>will</span>
  <span m=''1411560''>happen</span> <span m=''1412030''>is</span> <span m=''1412350''>that,</span>
  <span m=''1413230''>with</span> <span m=''1413520''>the</span> <span m=''1413590''>system,</span>
  <span m=''1414990''>we</span> <span m=''1415530''>will</span> <span m=''1415920''>put</span>
  <span m=''1416150''>in</span> <span m=''1416510''>a</span> <span m=''1416780''>continuous-time</span>
  <span m=''1417790''>sinusoid,</span> <span m=''1418540''>which</span> <span m=''1418730''>is</span>
  <span m=''1418810''>sampled,</span> <span m=''1420170''>converted</span> <span m=''1421050''>to</span>
  <span m=''1421220''>a</span> <span m=''1421300''>sequence.</span> <span m=''1423350''>The</span>
  <span m=''1423810''>sampled</span> <span m=''1424590''>continuous-time</span> <span
  m=''1425320''>sinusoid</span> <span m=''1426160''>is</span> <span m=''1426460''>a</span>
  <span m=''1426630''>discreet-time</span> <span m=''1427340''>sinusoid.</span> <span
  m=''1428670''>That</span> <span m=''1428940''>goes</span> <span m=''1429560''>through</span>
  <span m=''1429850''>the</span> <span m=''1429960''>digital</span> <span m=''1430340''>filter</span>
  <span m=''1430980''>and</span> <span m=''1431270''>gets</span> <span m=''1432330''>attenuated,
  or</span> <span m=''1432650''>amplified</span> <span m=''1433560''>appropriately.</span>
  <span m=''1435110''>And</span> <span m=''1435290''>then</span> <span m=''1435790''>the</span>
  <span m=''1435960''>output</span> <span m=''1436370''>of</span> <span m=''1436480''>that</span>
  <span m=''1436900''>is</span> <span m=''1437870''>converted</span> <span m=''1438520''>back--</span>
  <span m=''1438930''>and</span> <span m=''1439010''>that''s,</span> <span m=''1439400''>again,</span>
  <span m=''1439790''>a</span> <span m=''1439860''>sinusoidal</span> <span m=''1440580''>output--</span>
  <span m=''1441450''>that</span> <span m=''1441740''>gets</span> <span m=''1442130''>converted</span>
  <span m=''1442620''>back</span> <span m=''1443470''>to</span> <span m=''1444320''>a</span>
  <span m=''1444860''>continuous-time</span> <span m=''1445840''>sinusoid.</span>
  <span m=''1448000''>Theoretically,</span> <span m=''1448860''>as</span> <span m=''1449020''>I</span>
  <span m=''1449110''>indicate</span> <span m=''1449610''>here--</span> <span m=''1449920''>but</span>
  <span m=''1450090''>again,</span> <span m=''1450580''>as</span> <span m=''1450810''>we</span>
  <span m=''1450920''>just</span> <span m=''1451110''>saw,</span> <span m=''1451460''>really,</span>
  <span m=''1451760''>represented</span> <span m=''1452410''>by</span> <span m=''1453300''>a</span>
  <span m=''1453370''>zero-order</span> <span m=''1454020''>hold,</span> <span m=''1454510''>followed</span>
  <span m=''1454960''>by</span> <span m=''1455420''>a</span> <span m=''1455520''>low-pass</span>
  <span m=''1456060''>filter.</span> <span m=''1457680''>So,</span> <span m=''1458280''>that''s</span>
  <span m=''1458890''>the</span> <span m=''1459070''>overall</span> <span m=''1459790''>operation,</span>
  <span m=''1461060''>with</span> <span m=''1461500''>one</span> <span m=''1462120''>modification</span>
  <span m=''1463000''>from</span> <span m=''1463150''>the</span> <span m=''1463230''>diagram</span>
  <span m=''1463820''>that</span> <span m=''1463920''>we</span> <span m=''1464060''>have</span>
  <span m=''1464350''>here.</span> </p><p><span m=''1465310''>In</span> <span m=''1466280''>this</span>
  <span m=''1466690''>particular</span> <span m=''1467500''>diagram</span> <span m=''1468320''>I''ve</span>
  <span m=''1468540''>included</span> <span m=''1470150''>and</span> <span m=''1470430''>anti-aliasing</span>
  <span m=''1471610''>filter.</span> <span m=''1472540''>In</span> <span m=''1472680''>fact,</span>
  <span m=''1473220''>in</span> <span m=''1473350''>the</span> <span m=''1473430''>demonstration</span>
  <span m=''1474770''>there</span> <span m=''1475010''>is</span> <span m=''1475150''>no</span>
  <span m=''1475540''>anti-aliasing</span> <span m=''1476550''>filter.</span> <span
  m=''1477510''>And</span> <span m=''1478120''>so,</span> <span m=''1478710''>in</span>
  <span m=''1478850''>fact,</span> <span m=''1480420''>the</span> <span m=''1480920''>input</span>
  <span m=''1481650''>is</span> <span m=''1481960''>a</span> <span m=''1482320''>sinusoidal</span>
  <span m=''1482740''>input</span> <span m=''1483280''>which</span> <span m=''1483580''>is</span>
  <span m=''1483750''>not</span> <span m=''1485370''>band-limited</span> <span m=''1486700''>by</span>
  <span m=''1486960''>virtue</span> <span m=''1487400''>of</span> <span m=''1487490''>an</span>
  <span m=''1487580''>anti-aliasing</span> <span m=''1488330''>filter.</span> <span
  m=''1488990''>It''s</span> <span m=''1489210''>only,</span> <span m=''1490120''>of</span>
  <span m=''1490240''>course,</span> <span m=''1491160''>band-limited</span> <span
  m=''1491780''>appropriately</span> <span m=''1493170''>if</span> <span m=''1493610''>we</span>
  <span m=''1494000''>choose</span> <span m=''1494310''>the</span> <span m=''1494390''>sinusoidal</span>
  <span m=''1495350''>frequency</span> <span m=''1495910''>that</span> <span m=''1496150''>way.</span>
  </p><p><span m=''1497530''>So,</span> <span m=''1498080''>there</span> <span m=''1498300''>is</span>
  <span m=''1498410''>no</span> <span m=''1498560''>anti-aliasing</span> <span m=''1499330''>filter,</span>
  <span m=''1499900''>and</span> <span m=''1500430''>this</span> <span m=''1500630''>is</span>
  <span m=''1500770''>the</span> <span m=''1500860''>system.</span> <span m=''1502070''>And</span>
  <span m=''1503060''>one</span> <span m=''1503510''>consequence</span> <span m=''1504240''>of</span>
  <span m=''1504380''>that</span> <span m=''1505100''>is</span> <span m=''1505430''>that,</span>
  <span m=''1506220''>in</span> <span m=''1506370''>fact,</span> <span m=''1506900''>if</span>
  <span m=''1507060''>we</span> <span m=''1508040''>sweep</span> <span m=''1508860''>the</span>
  <span m=''1509020''>input</span> <span m=''1509400''>sinusoid</span> <span m=''1510740''>only</span>
  <span m=''1511190''>up</span> <span m=''1511450''>to</span> <span m=''1511740''>half</span>
  <span m=''1512100''>the</span> <span m=''1512370''>sampling</span> <span m=''1512870''>frequency,</span>
  <span m=''1513740''>we''ll</span> <span m=''1513900''>see</span> <span m=''1514120''>no</span>
  <span m=''1514320''>aliasing.</span> <span m=''1515490''>But</span> <span m=''1515670''>if</span>
  <span m=''1515850''>we</span> <span m=''1515960''>let</span> <span m=''1516130''>it</span>
  <span m=''1516320''>sweep</span> <span m=''1516470''>past</span> <span m=''1516910''>that,</span>
  <span m=''1517230''>we''re</span> <span m=''1517360''>going</span> <span m=''1517590''>to</span>
  <span m=''1517700''>get</span> <span m=''1517910''>aliasing.</span> </p><p><span
  m=''1519100''>Now,</span> <span m=''1519500''>in</span> <span m=''1519660''>the</span>
  <span m=''1519740''>demonstration,</span> <span m=''1520950''>the</span> <span m=''1521750''>sampling</span>
  <span m=''1522290''>rate</span> <span m=''1522790''>that''s</span> <span m=''1523020''>picked</span>
  <span m=''1523560''>for</span> <span m=''1523660''>this</span> <span m=''1523860''>part</span>
  <span m=''1524070''>of</span> <span m=''1524110''>the</span> <span m=''1524190''>demonstration</span>
  <span m=''1525430''>is</span> <span m=''1525580''>a</span> <span m=''1525660''>20</span>
  <span m=''1525950''>kilohertz</span> <span m=''1526460''>sampling</span> <span m=''1526930''>rate.</span>
  <span m=''1528790''>That</span> <span m=''1528980''>means,</span> <span m=''1529290''>based</span>
  <span m=''1529620''>on</span> <span m=''1529730''>the</span> <span m=''1529790''>sampling</span>
  <span m=''1530260''>theorem,</span> <span m=''1531170''>that</span> <span m=''1531470''>as</span>
  <span m=''1531680''>long</span> <span m=''1531950''>as</span> <span m=''1532120''>the</span>
  <span m=''1532240''>input</span> <span m=''1532600''>frequency</span> <span m=''1533490''>is</span>
  <span m=''1534290''>below</span> <span m=''1534630''>10</span> <span m=''1534940''>kilohertz</span>
  <span m=''1536360''>we</span> <span m=''1536510''>get</span> <span m=''1536740''>no</span>
  <span m=''1536910''>aliasing.</span> <span m=''1539300''>When</span> <span m=''1539400''>the</span>
  <span m=''1539540''>input</span> <span m=''1539920''>frequency</span> <span m=''1540460''>goes</span>
  <span m=''1540700''>beyond</span> <span m=''1541130''>10</span> <span m=''1541380''>kilohertz</span>
  <span m=''1541845''>,</span> <span m=''1543010''>that</span> <span m=''1543900''>higher</span>
  <span m=''1544280''>frequency</span> <span m=''1544990''>is</span> <span m=''1545170''>going</span>
  <span m=''1545390''>to</span> <span m=''1545530''>get</span> <span m=''1545770''>aliased</span>
  <span m=''1546300''>down</span> <span m=''1546760''>into</span> <span m=''1547030''>a</span>
  <span m=''1547100''>lower</span> <span m=''1547380''>frequency.</span> </p><p><span
  m=''1548670''>A</span> <span m=''1548780''>consequence</span> <span m=''1549470''>of</span>
  <span m=''1549560''>that,</span> <span m=''1549870''>then,</span> <span m=''1550230''>is</span>
  <span m=''1550490''>that</span> <span m=''1550730''>as</span> <span m=''1550940''>we</span>
  <span m=''1551060''>go</span> <span m=''1551290''>through</span> <span m=''1551500''>the</span>
  <span m=''1551590''>processing,</span> <span m=''1553300''>and</span> <span m=''1553930''>we</span>
  <span m=''1554080''>demonstrate</span> <span m=''1554690''>the</span> <span m=''1554770''>frequency</span>
  <span m=''1555270''>response</span> <span m=''1555750''>of</span> <span m=''1555830''>the</span>
  <span m=''1555910''>system,</span> <span m=''1557450''>what</span> <span m=''1557650''>we''ll</span>
  <span m=''1557840''>see</span> <span m=''1558330''>in</span> <span m=''1558970''>the</span>
  <span m=''1559250''>output</span> <span m=''1560300''>is</span> <span m=''1561130''>no</span>
  <span m=''1561390''>aliasing</span> <span m=''1562050''>when</span> <span m=''1562190''>the</span>
  <span m=''1562310''>input</span> <span m=''1562730''>is</span> <span m=''1562910''>below</span>
  <span m=''1563220''>10</span> <span m=''1563530''>kilohertz.</span> <span m=''1564660''>As</span>
  <span m=''1564870''>the</span> <span m=''1565040''>input</span> <span m=''1565760''>sweeps</span>
  <span m=''1566420''>past</span> <span m=''1566840''>10</span> <span m=''1567080''>kilohertz--</span>
  <span m=''1568310''>when</span> <span m=''1568570''>we</span> <span m=''1568720''>let</span>
  <span m=''1568940''>it,</span> <span m=''1569060''>which</span> <span m=''1569290''>we</span>
  <span m=''1569420''>will</span> <span m=''1569640''>eventually</span> <span m=''1570260''>in</span>
  <span m=''1570370''>the</span> <span m=''1570450''>demonstration--</span> <span
  m=''1571880''>then,</span> <span m=''1572390''>in</span> <span m=''1572560''>fact,</span>
  <span m=''1573400''>that</span> <span m=''1573690''>frequency,</span> <span m=''1574370''>as</span>
  <span m=''1574560''>it</span> <span m=''1574620''>finally</span> <span m=''1574980''>shows</span>
  <span m=''1575380''>up</span> <span m=''1575590''>here,</span> <span m=''1576460''>will</span>
  <span m=''1576710''>begin</span> <span m=''1577380''>to</span> <span m=''1577780''>be</span>
  <span m=''1578010''>aliased</span> <span m=''1578740''>down</span> <span m=''1579170''>into</span>
  <span m=''1579470''>a</span> <span m=''1579540''>lower</span> <span m=''1579820''>frequency.</span>
  <span m=''1581870''>Another</span> <span m=''1582150''>way</span> <span m=''1582600''>of</span>
  <span m=''1582780''>thinking</span> <span m=''1583110''>about</span> <span m=''1583460''>that</span>
  <span m=''1584000''>is</span> <span m=''1584270''>that,</span> <span m=''1584930''>when</span>
  <span m=''1585200''>we</span> <span m=''1586120''>watch</span> <span m=''1586640''>the</span>
  <span m=''1586890''>frequency</span> <span m=''1587450''>response</span> <span m=''1588220''>of</span>
  <span m=''1588370''>the</span> <span m=''1588460''>system,</span> <span m=''1591100''>as</span>
  <span m=''1591780''>we</span> <span m=''1591960''>look</span> <span m=''1592160''>at</span>
  <span m=''1592310''>the</span> <span m=''1593090''>digital</span> <span m=''1594350''>filter</span>
  <span m=''1594740''>frequency</span> <span m=''1595300''>response,</span> <span
  m=''1596500''>what</span> <span m=''1596760''>we''re</span> <span m=''1596930''>sweeping</span>
  <span m=''1597750''>as</span> <span m=''1598610''>we</span> <span m=''1599250''>go</span>
  <span m=''1599500''>from</span> <span m=''1599750''>0</span> <span m=''1601310''>up</span>
  <span m=''1601610''>to</span> <span m=''1602530''>10</span> <span m=''1602810''>kilohertz</span>
  <span m=''1604620''>in the</span> <span m=''1604800''>input</span> <span m=''1605180''>frequency</span>
  <span m=''1605920''>is</span> <span m=''1606230''>this</span> <span m=''1606460''>portion</span>
  <span m=''1607030''>of</span> <span m=''1607180''>the</span> <span m=''1607270''>frequency</span>
  <span m=''1607800''>response.</span> </p><p><span m=''1609010''>As</span> <span
  m=''1609230''>we</span> <span m=''1609360''>sweep</span> <span m=''1609770''>from</span>
  <span m=''1609950''>10</span> <span m=''1610230''>kilohertz</span> <span m=''1611330''>out</span>
  <span m=''1611550''>to</span> <span m=''1611670''>20</span> <span m=''1612000''>kilohertz,</span>
  <span m=''1612990''>what</span> <span m=''1613170''>we''ll</span> <span m=''1613330''>see</span>
  <span m=''1613840''>is</span> <span m=''1614520''>this</span> <span m=''1614770''>portion</span>
  <span m=''1615430''>of</span> <span m=''1615590''>the</span> <span m=''1615680''>frequency</span>
  <span m=''1616210''>response.</span> <span m=''1617170''>In</span> <span m=''1617280''>other</span>
  <span m=''1617440''>words,</span> <span m=''1617730''>we''ll</span> <span m=''1617840''>see</span>
  <span m=''1618120''>it</span> <span m=''1618630''>periodically</span> <span m=''1619380''>replicated.</span>
  <span m=''1620880''>Or,</span> <span m=''1621690''>if</span> <span m=''1622090''>we</span>
  <span m=''1622540''>look</span> <span m=''1622910''>at</span> <span m=''1623380''>the</span>
  <span m=''1624520''>corresponding</span> <span m=''1625230''>continuous-time</span>
  <span m=''1626520''>frequency</span> <span m=''1627020''>response,</span> <span
  m=''1628040''>what</span> <span m=''1628230''>it</span> <span m=''1628330''>means,</span>
  <span m=''1628650''>really,</span> <span m=''1629300''>is</span> <span m=''1629560''>that</span>
  <span m=''1630350''>sweeping</span> <span m=''1630980''>from</span> <span m=''1631610''>0</span>
  <span m=''1632640''>to</span> <span m=''1632790''>10</span> <span m=''1633090''>kilohertz</span>
  <span m=''1634340''>is</span> <span m=''1634510''>moving</span> <span m=''1634890''>up</span>
  <span m=''1635070''>this</span> <span m=''1635310''>way.</span> <span m=''1636190''>And</span>
  <span m=''1636380''>then</span> <span m=''1636600''>sweeping</span> <span m=''1637030''>from</span>
  <span m=''1637260''>10</span> <span m=''1637530''>kilohertz</span> <span m=''1638550''>to</span>
  <span m=''1638710''>20</span> <span m=''1639040''>kilohertz</span> <span m=''1640210''>on</span>
  <span m=''1640360''>the</span> <span m=''1640500''>input,</span> <span m=''1642090''>really</span>
  <span m=''1642410''>because</span> <span m=''1642760''>of</span> <span m=''1642840''>the</span>
  <span m=''1642990''>aliasing,</span> <span m=''1645340''>reflects</span> <span m=''1645830''>itself</span>
  <span m=''1646330''>in</span> <span m=''1646460''>the</span> <span m=''1646560''>digital</span>
  <span m=''1646950''>filter</span> <span m=''1647980''>by</span> <span m=''1648850''>looking</span>
  <span m=''1649220''>back</span> <span m=''1649970''>toward</span> <span m=''1650200''>lower</span>
  <span m=''1650460''>frequencies.</span> <span m=''1651590''>And</span> <span m=''1651770''>so</span>
  <span m=''1651960''>the</span> <span m=''1652050''>continuous-time</span> <span
  m=''1652870''>filter</span> <span m=''1653690''>sweeps</span> <span m=''1654710''>back</span>
  <span m=''1655050''>down</span> <span m=''1655940''>from</span> <span m=''1656310''>10</span>
  <span m=''1656590''>kilohertz</span> <span m=''1657350''>back</span> <span m=''1658350''>to</span>
  <span m=''1658460''>0.</span> </p><p><span m=''1660520''>OK,</span> <span m=''1660990''>so,</span>
  <span m=''1661570''>that''s</span> <span m=''1661820''>what</span> <span m=''1661960''>we''ll</span>
  <span m=''1662090''>see,</span> <span m=''1662590''>and</span> <span m=''1662840''>we''ll</span>
  <span m=''1662970''>see</span> <span m=''1663200''>it</span> <span m=''1663320''>in</span>
  <span m=''1663620''>several</span> <span m=''1664020''>different</span> <span m=''1664280''>ways</span>
  <span m=''1664700''>as</span> <span m=''1664900''>explained</span> <span m=''1665320''>in</span>
  <span m=''1665400''>the</span> <span m=''1665470''>demonstration.</span> <span m=''1666560''>So</span>
  <span m=''1666750''>now</span> <span m=''1667300''>let''s</span> <span m=''1667640''>look</span>
  <span m=''1668010''>at</span> <span m=''1668520''>the</span> <span m=''1668620''>frequency</span>
  <span m=''1669130''>response</span> <span m=''1669620''>of the</span> <span m=''1669720''>filter.</span>
  </p><p><span m=''1671930''>Now</span> <span m=''1672140''>what</span> <span m=''1672270''>we''d</span>
  <span m=''1672390''>like</span> <span m=''1672630''>to</span> <span m=''1672710''>illustrate</span>
  <span m=''1673370''>is</span> <span m=''1673640''>the</span> <span m=''1673870''>frequency</span>
  <span m=''1674440''>response</span> <span m=''1675200''>of</span> <span m=''1675740''>the</span>
  <span m=''1676240''>equivalent</span> <span m=''1676770''>continuous-time</span>
  <span m=''1677610''>filter.</span> <span m=''1678610''>And</span> <span m=''1678710''>we</span>
  <span m=''1678820''>can</span> <span m=''1678960''>do</span> <span m=''1679170''>that</span>
  <span m=''1679620''>by</span> <span m=''1680020''>sweeping</span> <span m=''1680500''>the</span>
  <span m=''1680580''>filter</span> <span m=''1681010''>with</span> <span m=''1681160''>sinusoidal</span>
  <span m=''1681920''>input.</span> <span m=''1682880''>So,</span> <span m=''1683550''>what</span>
  <span m=''1683730''>we''ll</span> <span m=''1683880''>see</span> <span m=''1684130''>in</span>
  <span m=''1684200''>this</span> <span m=''1684400''>demonstration</span> <span m=''1685400''>is,</span>
  <span m=''1686360''>on</span> <span m=''1686520''>the</span> <span m=''1686650''>upper</span>
  <span m=''1686890''>trace,</span> <span m=''1687470''>the</span> <span m=''1687580''>input</span>
  <span m=''1687980''>sinusoid,</span> <span m=''1688830''>on</span> <span m=''1688940''>the</span>
  <span m=''1689020''>lower</span> <span m=''1689270''>trace,</span> <span m=''1689620''>the</span>
  <span m=''1689750''>output</span> <span m=''1690180''>sinusoid,</span> <span m=''1691770''>using</span>
  <span m=''1692160''>a</span> <span m=''1692230''>20</span> <span m=''1692510''>kilohertz</span>
  <span m=''1693010''>sampling</span> <span m=''1693530''>rate,</span> <span m=''1693960''>and</span>
  <span m=''1694100''>a</span> <span m=''1694150''>sweep</span> <span m=''1694740''>from</span>
  <span m=''1695040''>0</span> <span m=''1695400''>to</span> <span m=''1695530''>10</span>
  <span m=''1695800''>kilohertz.</span> <span m=''1696420''>In</span> <span m=''1696510''>other</span>
  <span m=''1696700''>words,</span> <span m=''1697170''>a</span> <span m=''1697260''>sweep</span>
  <span m=''1697680''>from</span> <span m=''1697840''>0</span> <span m=''1698430''>to,</span>
  <span m=''1698870''>effectively,</span> <span m=''1699510''>pi,</span> <span m=''1700590''>in</span>
  <span m=''1700730''>terms</span> <span m=''1701080''>of</span> <span m=''1701180''>the</span>
  <span m=''1701250''>digital</span> <span m=''1701610''>filter.</span> </p><p><span
  m=''1703320''>So</span> <span m=''1704450''>what</span> <span m=''1704740''>we''ll</span>
  <span m=''1704970''>observe</span> <span m=''1705530''>as</span> <span m=''1705820''>the</span>
  <span m=''1705930''>input</span> <span m=''1706260''>frequency</span> <span m=''1706840''>increases,</span>
  <span m=''1708060''>is</span> <span m=''1708430''>that</span> <span m=''1708580''>the</span>
  <span m=''1708710''>output</span> <span m=''1709110''>sinusoid</span> <span m=''1709900''>will</span>
  <span m=''1710110''>have,</span> <span m=''1710510''>essentially,</span> <span m=''1711010''>constant</span>
  <span m=''1711450''>amplitude</span> <span m=''1712760''>up</span> <span m=''1712990''>to</span>
  <span m=''1713100''>the</span> <span m=''1713190''>cutoff frequency</span> <span
  m=''1714110''>of</span> <span m=''1714180''>the</span> <span m=''1714260''>filter,</span>
  <span m=''1714840''>and</span> <span m=''1715020''>then</span> <span m=''1715670''>approximately</span>
  <span m=''1716430''>zero</span> <span m=''1716840''>amplitude</span> <span m=''1717370''>past.</span>
  <span m=''1718170''>So</span> <span m=''1718760''>let''s</span> <span m=''1719070''>now</span>
  <span m=''1719480''>sweep</span> <span m=''1719860''>the</span> <span m=''1719950''>filter</span>
  <span m=''1720470''>frequency</span> <span m=''1721070''>response.</span> <span
  m=''1726580''>And</span> <span m=''1728280''>there</span> <span m=''1728720''>is</span>
  <span m=''1728910''>the</span> <span m=''1729160''>filter</span> <span m=''1729750''>cutoff</span>
  <span m=''1730120''>frequency.</span> </p><p><span m=''1735300''>Now,</span> <span
  m=''1735800''>we</span> <span m=''1735940''>can</span> <span m=''1736100''>also</span>
  <span m=''1736720''>observe</span> <span m=''1737360''>the</span> <span m=''1737530''>filter</span>
  <span m=''1737910''>frequency</span> <span m=''1738410''>response</span> <span m=''1738950''>in</span>
  <span m=''1739310''>several</span> <span m=''1739780''>other</span> <span m=''1739980''>ways.</span>
  <span m=''1740840''>One</span> <span m=''1741050''>way</span> <span m=''1741240''>in</span>
  <span m=''1741320''>which</span> <span m=''1741530''>we</span> <span m=''1741660''>can</span>
  <span m=''1741820''>observe</span> <span m=''1742220''>it</span> <span m=''1742400''>is</span>
  <span m=''1742710''>by</span> <span m=''1743780''>looking,</span> <span m=''1744180''>also,</span>
  <span m=''1744960''>at</span> <span m=''1745530''>the</span> <span m=''1745900''>amplitude</span>
  <span m=''1746530''>of</span> <span m=''1746610''>the</span> <span m=''1746750''>output</span>
  <span m=''1747390''>sinusoid</span> <span m=''1747960''>as</span> <span m=''1748640''>a</span>
  <span m=''1749510''>function</span> <span m=''1749880''>of</span> <span m=''1749960''>frequency,</span>
  <span m=''1750710''>rather</span> <span m=''1751060''>than</span> <span m=''1751230''>as</span>
  <span m=''1751360''>a</span> <span m=''1751410''>function</span> <span m=''1751840''>of</span>
  <span m=''1751950''>time.</span> <span m=''1752980''>And</span> <span m=''1753370''>so</span>
  <span m=''1753730''>we''ll observe</span> <span m=''1754160''>that</span> <span
  m=''1754510''>on</span> <span m=''1754710''>the</span> <span m=''1754810''>left-hand</span>
  <span m=''1755620''>scope.</span> </p><p><span m=''1756530''>While</span> <span
  m=''1756770''>on</span> <span m=''1756880''>the</span> <span m=''1756960''>right-hand</span>
  <span m=''1757460''>scope,</span> <span m=''1757840''>we''ll</span> <span m=''1757960''>have</span>
  <span m=''1758130''>the</span> <span m=''1758210''>same</span> <span m=''1758500''>trace</span>
  <span m=''1758940''>the</span> <span m=''1759280''>we</span> <span m=''1759420''>just</span>
  <span m=''1759720''>saw,</span> <span m=''1760570''>namely</span> <span m=''1760990''>two</span>
  <span m=''1761170''>traces--</span> <span m=''1761760''>the</span> <span m=''1761890''>upper</span>
  <span m=''1762110''>trace is</span> <span m=''1762570''>the</span> <span m=''1762690''>inputs</span>
  <span m=''1763140''>sinusoid,</span> <span m=''1764170''>the</span> <span m=''1764270''>lower</span>
  <span m=''1764520''>trace is</span> <span m=''1764990''>the</span> <span m=''1765110''>output</span>
  <span m=''1765580''>sinusoid.</span> <span m=''1766800''>And,</span> <span m=''1767180''>in</span>
  <span m=''1767370''>addition</span> <span m=''1767800''>to</span> <span m=''1767960''>observing</span>
  <span m=''1768830''>the</span> <span m=''1768930''>frequency</span> <span m=''1769490''>response,</span>
  <span m=''1770460''>let''s</span> <span m=''1770730''>also</span> <span m=''1771070''>listen</span>
  <span m=''1771750''>to</span> <span m=''1771880''>the</span> <span m=''1772030''>output</span>
  <span m=''1772430''>sinusoid</span> <span m=''1773580''>and</span> <span m=''1774700''>observe</span>
  <span m=''1775290''>the</span> <span m=''1775430''>attenuation</span> <span m=''1776340''>in</span>
  <span m=''1776470''>the</span> <span m=''1776620''>output</span> <span m=''1777120''>as</span>
  <span m=''1777420''>we</span> <span m=''1777540''>go</span> <span m=''1777730''>from</span>
  <span m=''1777920''>the</span> <span m=''1777990''>filter</span> <span m=''1778320''>passband</span>
  <span m=''1778730''>to</span> <span m=''1779040''>the</span> <span m=''1779120''>filter</span>
  <span m=''1779480''>stopband.</span> <span m=''1780520''>Again,</span> <span m=''1780800''>a</span>
  <span m=''1780870''>20</span> <span m=''1781160''>kilohertz</span> <span m=''1781640''>sampling</span>
  <span m=''1782100''>rate</span> <span m=''1782750''>and</span> <span m=''1782910''>a</span>
  <span m=''1782960''>sweep range</span> <span m=''1784040''>from</span> <span m=''1784180''>0</span>
  <span m=''1784550''>to</span> <span m=''1784700''>10</span> <span m=''1784950''>kilohertz.</span>
  </p><p><span m=''1793290''>Now,</span> <span m=''1793550''>of</span> <span m=''1793640''>course,</span>
  <span m=''1793940''>we''re in</span> <span m=''1794120''>the</span> <span m=''1794220''>filter</span>
  <span m=''1794535''>stopband.</span> <span m=''1798360''>Now,</span> <span m=''1799340''>if</span>
  <span m=''1799870''>we</span> <span m=''1800360''>increase</span> <span m=''1800940''>the</span>
  <span m=''1801020''>sweep</span> <span m=''1801420''>range</span> <span m=''1802140''>from</span>
  <span m=''1803070''>10</span> <span m=''1803300''>kilohertz</span> <span m=''1803870''>the</span>
  <span m=''1803980''>20</span> <span m=''1804310''>kilohertz,</span> <span m=''1805500''>so</span>
  <span m=''1805690''>that</span> <span m=''1805870''>the</span> <span m=''1806060''>sweep</span>
  <span m=''1806300''>range</span> <span m=''1806660''>is</span> <span m=''1806790''>equal</span>
  <span m=''1807110''>to</span> <span m=''1807210''>the</span> <span m=''1807300''>sampling</span>
  <span m=''1807880''>frequency,</span> <span m=''1809010''>in</span> <span m=''1809180''>essence,</span>
  <span m=''1809650''>that</span> <span m=''1809870''>corresponds</span> <span m=''1810620''>to</span>
  <span m=''1810730''>sweeping</span> <span m=''1811160''>out</span> <span m=''1811310''>the</span>
  <span m=''1811390''>digital</span> <span m=''1811780''>filter</span> <span m=''1812720''>from</span>
  <span m=''1813240''>0</span> <span m=''1813740''>to</span> <span m=''1813910''>2</span>
  <span m=''1814120''>pi.</span> <span m=''1815110''>And,</span> <span m=''1815270''>in</span>
  <span m=''1815350''>that</span> <span m=''1815590''>case,</span> <span m=''1815900''>we''ll</span>
  <span m=''1816040''>begin</span> <span m=''1816450''>to</span> <span m=''1816570''>see</span>
  <span m=''1817320''>some</span> <span m=''1817620''>of</span> <span m=''1817700''>the</span>
  <span m=''1817790''>periodicity</span> <span m=''1818810''>in</span> <span m=''1818960''>the</span>
  <span m=''1819050''>digital</span> <span m=''1819400''>filter</span> <span m=''1819750''>frequency</span>
  <span m=''1820260''>response.</span> <span m=''1821210''>So</span> <span m=''1821840''>let''s</span>
  <span m=''1822370''>do</span> <span m=''1822550''>that</span> <span m=''1822880''>now</span>
  <span m=''1823380''>with</span> <span m=''1823550''>a</span> <span m=''1823630''>20</span>
  <span m=''1823910''>kilohertz</span> <span m=''1824420''>sampling</span> <span m=''1824910''>rate</span>
  <span m=''1825570''>and</span> <span m=''1825680''>a</span> <span m=''1825890''>sweep</span>
  <span m=''1826150''>range</span> <span m=''1826580''>of</span> <span m=''1826650''>0</span>
  <span m=''1827020''>to</span> <span m=''1827170''>20</span> <span m=''1827470''>kilohertz.</span>
  </p><p><span m=''1832790''>Now</span> <span m=''1833030''>as</span> <span m=''1833130''>we</span>
  <span m=''1833250''>come</span> <span m=''1833630''>near</span> <span m=''1833860''>2</span>
  <span m=''1834060''>pi,</span> <span m=''1837490''>we</span> <span m=''1837700''>get</span>
  <span m=''1837990''>back</span> <span m=''1838190''>the</span> <span m=''1838681''>past-band.</span>
  <span m=''1841140''>And,</span> <span m=''1841780''>finally,</span> <span m=''1842240''>back</span>
  <span m=''1842680''>to</span> <span m=''1843170''>a</span> <span m=''1843450''>0</span>
  <span m=''1843830''>to</span> <span m=''1843950''>10</span> <span m=''1844240''>kilohertz</span>
  <span m=''1844760''>sweep,</span> <span m=''1845450''>so</span> <span m=''1845630''>that</span>
  <span m=''1845780''>we''re</span> <span m=''1846020''>again</span> <span m=''1846290''>sweeping</span>
  <span m=''1846880''>only</span> <span m=''1847330''>from</span> <span m=''1847660''>0</span>
  <span m=''1848030''>to</span> <span m=''1848190''>pi</span> <span m=''1849130''>with</span>
  <span m=''1849530''>regard</span> <span m=''1849940''>to</span> <span m=''1850030''>the</span>
  <span m=''1850130''>digital</span> <span m=''1850480''>filter.</span> </p><p><span
  m=''1865070''>Now,</span> <span m=''1865640''>an</span> <span m=''1865750''>important</span>
  <span m=''1866130''>observation</span> <span m=''1867100''>is</span> <span m=''1867560''>that,</span>
  <span m=''1868130''>with</span> <span m=''1868570''>the</span> <span m=''1869670''>digital</span>
  <span m=''1870380''>or</span> <span m=''1870560''>discreet-time</span> <span m=''1871600''>filter</span>
  <span m=''1872370''>cutoff frequency</span> <span m=''1873280''>fixed</span> <span
  m=''1873930''>as</span> <span m=''1874880''>I''ve</span> <span m=''1875040''>indicated</span>
  <span m=''1875610''>here--</span> <span m=''1876130''>and</span> <span m=''1876700''>I</span>
  <span m=''1876810''>remind</span> <span m=''1877250''>you</span> <span m=''1877460''>that</span>
  <span m=''1878230''>what</span> <span m=''1878690''>the</span> <span m=''1878810''>cutoff
  frequency</span> <span m=''1879430''>is,</span> <span m=''1880110''>is</span> <span
  m=''1880370''>a</span> <span m=''1880450''>10th</span> <span m=''1880890''>of</span>
  <span m=''1881000''>2</span> <span m=''1881200''>pi--</span> <span m=''1882370''>with</span>
  <span m=''1882790''>that</span> <span m=''1883060''>cutoff frequency</span> <span
  m=''1884000''>fixed,</span> <span m=''1885090''>because</span> <span m=''1885770''>of</span>
  <span m=''1885970''>the</span> <span m=''1886060''>normalization</span> <span m=''1887170''>that</span>
  <span m=''1887300''>we get</span> <span m=''1888250''>as</span> <span m=''1888800''>we</span>
  <span m=''1888990''>come</span> <span m=''1889250''>back</span> <span m=''1889650''>to</span>
  <span m=''1890020''>a</span> <span m=''1890470''>continuous-time</span> <span m=''1891390''>filter,</span>
  <span m=''1892480''>in</span> <span m=''1892640''>fact,</span> <span m=''1893220''>what</span>
  <span m=''1893440''>we</span> <span m=''1894030''>have</span> <span m=''1894560''>is</span>
  <span m=''1895080''>a</span> <span m=''1895220''>cutoff frequency</span> <span m=''1897040''>that</span>
  <span m=''1897460''>is</span> <span m=''1898230''>dependent</span> <span m=''1899000''>on</span>
  <span m=''1899600''>the</span> <span m=''1899690''>sampling</span> <span m=''1900170''>frequency</span>
  <span m=''1900920''>or</span> <span m=''1901070''>on</span> <span m=''1901140''>the</span>
  <span m=''1901210''>sampling</span> <span m=''1901670''>period.</span> <span m=''1902620''>And,</span>
  <span m=''1902780''>more</span> <span m=''1902950''>specifically,</span> <span m=''1904150''>since</span>
  <span m=''1904660''>the</span> <span m=''1904850''>discreet-time,</span> <span m=''1905620''>or</span>
  <span m=''1905740''>digital,</span> <span m=''1906580''>filter</span> <span m=''1907050''>or</span>
  <span m=''1907120''>has</span> <span m=''1907330''>a</span> <span m=''1907400''>cutoff
  frequency</span> <span m=''1908780''>which</span> <span m=''1909110''>is</span>
  <span m=''1909230''>a</span> <span m=''1909320''>10th</span> <span m=''1909600''>of</span>
  <span m=''1909760''>2</span> <span m=''1910010''>pi,</span> <span m=''1911480''>the</span>
  <span m=''1911600''>normalization,</span> <span m=''1912610''>as</span> <span m=''1912840''>you</span>
  <span m=''1912970''>recall,</span> <span m=''1914010''>is</span> <span m=''1914450''>that</span>
  <span m=''1915120''>2</span> <span m=''1915350''>pi,</span> <span m=''1916050''>in</span>
  <span m=''1916630''>discreet-time</span> <span m=''1917290''>frequency,</span> <span
  m=''1918620''>corresponds</span> <span m=''1919510''>to</span> <span m=''1919900''>omega</span>
  <span m=''1920320''>sub</span> <span m=''1920530''>s,</span> <span m=''1920780''>the</span>
  <span m=''1920860''>sampling</span> <span m=''1921320''>frequency,</span> <span
  m=''1922180''>in</span> <span m=''1922330''>terms</span> <span m=''1922650''>of</span>
  <span m=''1922750''>continuous-time</span> <span m=''1923580''>frequency.</span>
  <span m=''1925180''>The</span> <span m=''1925300''>consequence</span> <span m=''1926230''>is</span>
  <span m=''1926670''>that</span> <span m=''1927390''>this</span> <span m=''1927720''>cutoff
  frequency,</span> <span m=''1929380''>in</span> <span m=''1929540''>fact,</span>
  <span m=''1930100''>is</span> <span m=''1931070''>1/10</span> <span m=''1933180''>of--</span>
  <span m=''1933970''>not</span> <span m=''1934230''>2</span> <span m=''1934400''>pi</span>
  <span m=''1934740''>now</span> <span m=''1935010''>because</span> <span m=''1935340''>of</span>
  <span m=''1935400''>the</span> <span m=''1935480''>normalization--</span> <span
  m=''1936680''>it''s</span> <span m=''1936880''>1/10</span> <span m=''1937970''>of</span>
  <span m=''1938440''>the</span> <span m=''1938550''>sampling</span> <span m=''1939040''>frequency.</span>
  </p><p><span m=''1940180''>So,</span> <span m=''1940900''>consequently,</span> <span
  m=''1942280''>as</span> <span m=''1942910''>we</span> <span m=''1943440''>change</span>
  <span m=''1943850''>the</span> <span m=''1943970''>sampling</span> <span m=''1944500''>frequency,</span>
  <span m=''1945780''>what</span> <span m=''1945980''>will</span> <span m=''1946140''>happen</span>
  <span m=''1946790''>is</span> <span m=''1947160''>that,</span> <span m=''1947480''>even</span>
  <span m=''1947770''>with</span> <span m=''1947950''>the</span> <span m=''1948020''>discreet-time</span>
  <span m=''1948650''>filter</span> <span m=''1949010''>cutoff</span> <span m=''1949550''>fixed,</span>
  <span m=''1951250''>the</span> <span m=''1951360''>cutoff</span> <span m=''1951760''>frequency</span>
  <span m=''1952620''>of</span> <span m=''1953320''>the</span> <span m=''1953470''>equivalent</span>
  <span m=''1953870''>continuous-time</span> <span m=''1954670''>filter</span> <span
  m=''1955310''>will</span> <span m=''1955530''>change.</span> <span m=''1957810''>Now,</span>
  <span m=''1958540''>that''s</span> <span m=''1958960''>what</span> <span m=''1959310''>I</span>
  <span m=''1959490''>want</span> <span m=''1959710''>to</span> <span m=''1959770''>demonstrate.</span>
  <span m=''1960570''>But</span> <span m=''1961120''>let</span> <span m=''1961310''>me</span>
  <span m=''1961640''>again</span> <span m=''1961930''>stress</span> <span m=''1962470''>and</span>
  <span m=''1962600''>ask</span> <span m=''1962830''>you</span> <span m=''1962900''>to</span>
  <span m=''1962980''>keep</span> <span m=''1963240''>in</span> <span m=''1963340''>mind</span>
  <span m=''1964370''>that</span> <span m=''1964790''>this</span> <span m=''1964960''>demonstration</span>
  <span m=''1965710''>is</span> <span m=''1965880''>done</span> <span m=''1966330''>without</span>
  <span m=''1966880''>an</span> <span m=''1967010''>anti-aliasing</span> <span m=''1967900''>filter</span>
  <span m=''1968430''>in.</span> </p><p><span m=''1969480''>And</span> <span m=''1971200''>we</span>
  <span m=''1971540''>are</span> <span m=''1971890''>going</span> <span m=''1972130''>to</span>
  <span m=''1972270''>be</span> <span m=''1972470''>changing</span> <span m=''1973010''>the</span>
  <span m=''1973090''>sampling</span> <span m=''1973590''>frequency</span> <span m=''1974790''>and,</span>
  <span m=''1975310''>so</span> <span m=''1975570''>keep</span> <span m=''1975820''>in</span>
  <span m=''1975950''>mind</span> <span m=''1976610''>that,</span> <span m=''1977390''>as</span>
  <span m=''1978280''>we</span> <span m=''1978430''>look</span> <span m=''1978670''>at</span>
  <span m=''1978800''>this,</span> <span m=''1979820''>as</span> <span m=''1980650''>the</span>
  <span m=''1981060''>input</span> <span m=''1981540''>frequency</span> <span m=''1982780''>sweeps</span>
  <span m=''1983400''>past</span> <span m=''1984090''>half</span> <span m=''1984390''>the</span>
  <span m=''1984470''>sampling</span> <span m=''1984940''>frequency--</span> <span
  m=''1985560''>whatever</span> <span m=''1986000''>sampling</span> <span m=''1986390''>frequency</span>
  <span m=''1986930''>we</span> <span m=''1987060''>happen</span> <span m=''1987360''>to</span>
  <span m=''1987410''>be</span> <span m=''1987530''>looking</span> <span m=''1987900''>at--</span>
  <span m=''1988680''>then,</span> <span m=''1989220''>because</span> <span m=''1989730''>of</span>
  <span m=''1989790''>the</span> <span m=''1989870''>fact</span> <span m=''1990190''>that</span>
  <span m=''1990310''>there''s</span> <span m=''1990500''>no</span> <span m=''1990670''>anti-aliasing</span>
  <span m=''1991550''>filter</span> <span m=''1992180''>we''ll</span> <span m=''1992630''>get</span>
  <span m=''1992760''>aliasing.</span> <span m=''1994360''>In</span> <span m=''1994510''>other</span>
  <span m=''1994680''>words,</span> <span m=''1995080''>the</span> <span m=''1995160''>frequency</span>
  <span m=''1996000''>and</span> <span m=''1996110''>the</span> <span m=''1996180''>digital</span>
  <span m=''1996590''>filter,</span> <span m=''1997170''>or</span> <span m=''1997230''>discreet-time</span>
  <span m=''1997830''>filter,</span> <span m=''1998800''>as</span> <span m=''1999010''>we</span>
  <span m=''1999110''>sweep</span> <span m=''1999420''>the</span> <span m=''1999530''>input</span>
  <span m=''1999870''>frequency</span> <span m=''2000460''>up,</span> <span m=''2001040''>will</span>
  <span m=''2001200''>move</span> <span m=''2001920''>up</span> <span m=''2002120''>in</span>
  <span m=''2002240''>frequency</span> <span m=''2003420''>until</span> <span m=''2003730''>we</span>
  <span m=''2003860''>get</span> <span m=''2004550''>past</span> <span m=''2004890''>half
  the</span> <span m=''2005280''>sampling</span> <span m=''2005680''>frequency</span>
  <span m=''2006440''>and</span> <span m=''2006620''>then</span> <span m=''2006780''>essentially</span>
  <span m=''2007440''>will</span> <span m=''2007620''>move</span> <span m=''2007840''>back</span>
  <span m=''2008130''>down</span> <span m=''2008400''>in</span> <span m=''2008490''>frequency.</span>
  <span m=''2011170''>Consequently,</span> <span m=''2011780''>what</span> <span m=''2011980''>we''ll</span>
  <span m=''2012150''>get,</span> <span m=''2012640''>then--</span> <span m=''2013570''>or
  what</span> <span m=''2013850''>we''ll</span> <span m=''2013940''>see--</span> <span
  m=''2014280''>are</span> <span m=''2014510''>periodic</span> <span m=''2015060''>replications</span>
  <span m=''2015960''>of</span> <span m=''2016210''>the</span> <span m=''2016340''>frequency</span>
  <span m=''2016840''>response</span> <span m=''2017460''>when</span> <span m=''2017640''>we</span>
  <span m=''2017750''>swept</span> <span m=''2018060''>past</span> <span m=''2019170''>half</span>
  <span m=''2019370''>the</span> <span m=''2019460''>sampling</span> <span m=''2019900''>frequency.</span>
  </p><p><span m=''2020910''>All</span> <span m=''2021000''>right,</span> <span m=''2021210''>so</span>
  <span m=''2021350''>now,</span> <span m=''2022180''>let''s</span> <span m=''2022480''>look</span>
  <span m=''2022910''>at</span> <span m=''2023760''>the</span> <span m=''2023850''>same</span>
  <span m=''2024150''>digital</span> <span m=''2024490''>filter,</span> <span m=''2025440''>but</span>
  <span m=''2025750''>the</span> <span m=''2025830''>frequency</span> <span m=''2026360''>response,</span>
  <span m=''2027780''>as</span> <span m=''2028500''>we</span> <span m=''2029340''>change</span>
  <span m=''2030040''>the</span> <span m=''2030140''>sampling</span> <span m=''2030570''>frequency.</span>
  <span m=''2032980''>Now,</span> <span m=''2033370''>what</span> <span m=''2033730''>we</span>
  <span m=''2033860''>would</span> <span m=''2033990''>like</span> <span m=''2034290''>to</span>
  <span m=''2034540''>demonstrate</span> <span m=''2035360''>is</span> <span m=''2035490''>the</span>
  <span m=''2035610''>effect</span> <span m=''2035980''>of</span> <span m=''2036070''>changing</span>
  <span m=''2036560''>the</span> <span m=''2036640''>sampling</span> <span m=''2037150''>frequency.</span>
  <span m=''2038450''>And</span> <span m=''2039150''>we</span> <span m=''2039320''>know</span>
  <span m=''2041510''>that</span> <span m=''2041660''>the</span> <span m=''2041760''>effective</span>
  <span m=''2042210''>filter</span> <span m=''2042550''>cutoff</span> <span m=''2042930''>frequency</span>
  <span m=''2043740''>is</span> <span m=''2043930''>tied</span> <span m=''2044480''>to</span>
  <span m=''2044960''>the</span> <span m=''2045490''>sampling</span> <span m=''2046020''>frequency</span>
  <span m=''2047170''>and,</span> <span m=''2047320''>for</span> <span m=''2047420''>this</span>
  <span m=''2047630''>particular</span> <span m=''2048139''>filter,</span> <span m=''2049050''>corresponds</span>
  <span m=''2049810''>to</span> <span m=''2049969''>a</span> <span m=''2050050''>10th</span>
  <span m=''2050730''>of</span> <span m=''2050870''>the</span> <span m=''2051100''>sampling</span>
  <span m=''2051590''>frequency.</span> <span m=''2052719''>Consequently,</span> <span
  m=''2053489''>if</span> <span m=''2053620''>we</span> <span m=''2053730''>double</span>
  <span m=''2054080''>the</span> <span m=''2054159''>sampling</span> <span m=''2054639''>frequency,</span>
  <span m=''2055300''>we</span> <span m=''2055460''>should</span> <span m=''2055690''>double</span>
  <span m=''2056120''>the</span> <span m=''2056860''>effective</span> <span m=''2057520''>filter</span>
  <span m=''2057949''>passband</span> <span m=''2058350''>width,</span> <span m=''2059489''>or</span>
  <span m=''2060020''>double</span> <span m=''2060520''>the</span> <span m=''2060690''>filter</span>
  <span m=''2061070''>cutoff</span> <span m=''2061489''>frequency.</span> </p><p><span
  m=''2062730''>And,</span> <span m=''2063280''>so,</span> <span m=''2063639''>let''s</span>
  <span m=''2064080''>do</span> <span m=''2064270''>that</span> <span m=''2064550''>now.</span>
  <span m=''2065100''>Again</span> <span m=''2065449''>a</span> <span m=''2065679''>0
  to</span> <span m=''2065770''>10</span> <span m=''2066120''>kilohertz</span> <span
  m=''2066639''>sweep</span> <span m=''2067010''>range,</span> <span m=''2067889''>but</span>
  <span m=''2068179''>a</span> <span m=''2068409''>40</span> <span m=''2069070''>kilohertz</span>
  <span m=''2069620''>sampling</span> <span m=''2070060''>frequency.</span> <span
  m=''2074690''>And</span> <span m=''2075090''>we</span> <span m=''2075539''>should</span>
  <span m=''2075989''>observe</span> <span m=''2076279''>that</span> <span m=''2076570''>the</span>
  <span m=''2076699''>filter</span> <span m=''2077164''>cutoff</span> <span m=''2077629''>frequency</span>
  <span m=''2078094''>has</span> <span m=''2078560''>now</span> <span m=''2078860''>doubled</span>
  <span m=''2079630''>out to</span> <span m=''2079750''>four</span> <span m=''2080199''>kilohertz.</span>
  <span m=''2083469''>Now,</span> <span m=''2084090''>let''s</span> <span m=''2084540''>begin</span>
  <span m=''2084909''>to</span> <span m=''2085020''>decrease</span> <span m=''2085550''>the</span>
  <span m=''2085639''>filter</span> <span m=''2086010''>sampling</span> <span m=''2086480''>frequency.</span>
  <span m=''2087889''>So</span> <span m=''2088150''>from</span> <span m=''2088320''>40,</span>
  <span m=''2088719''>let''s</span> <span m=''2089000''>change</span> <span m=''2089409''>the</span>
  <span m=''2089670''>sampling</span> <span m=''2090110''>frequency</span> <span m=''2090650''>to</span>
  <span m=''2090760''>20</span> <span m=''2091060''>kilohertz.</span> <span m=''2092730''>We</span>
  <span m=''2092920''>should</span> <span m=''2093130''>see</span> <span m=''2093380''>the</span>
  <span m=''2093639''>cutoff</span> <span m=''2094030''>frequency</span> <span m=''2094770''>cut</span>
  <span m=''2094960''>in</span> <span m=''2095060''>half.</span> </p><p><span m=''2105970''>Now,</span>
  <span m=''2106180''>we</span> <span m=''2106290''>can</span> <span m=''2106450''>go</span>
  <span m=''2106950''>even</span> <span m=''2107250''>further.</span> <span m=''2107710''>We</span>
  <span m=''2107870''>can</span> <span m=''2108070''>cut</span> <span m=''2108280''>the</span>
  <span m=''2108360''>sampling</span> <span m=''2108810''>frequency</span> <span m=''2109350''>down</span>
  <span m=''2109610''>to</span> <span m=''2109700''>10</span> <span m=''2110060''>kilohertz.</span>
  <span m=''2110650''>And</span> <span m=''2110740''>remember</span> <span m=''2111140''>that</span>
  <span m=''2111420''>the</span> <span m=''2111660''>sweep</span> <span m=''2112070''>range
  is</span> <span m=''2112510''>0</span> <span m=''2112800''>to</span> <span m=''2112920''>10</span>
  <span m=''2113200''>kilohertz.</span> <span m=''2113800''>So</span> <span m=''2113900''>now</span>
  <span m=''2114140''>we''ll</span> <span m=''2114290''>be</span> <span m=''2114410''>sweeping</span>
  <span m=''2114890''>from</span> <span m=''2115090''>0</span> <span m=''2115460''>to</span>
  <span m=''2115580''>2</span> <span m=''2115780''>pi.</span> <span m=''2123830''>So</span>
  <span m=''2124060''>as</span> <span m=''2124150''>we</span> <span m=''2124250''>get</span>
  <span m=''2124440''>close</span> <span m=''2124910''>to</span> <span m=''2125160''>2</span>
  <span m=''2125400''>pi,</span> <span m=''2125710''>we''ll</span> <span m=''2125880''>see</span>
  <span m=''2126060''>the</span> <span m=''2126160''>passband</span> <span m=''2126780''>again.</span>
  <span m=''2129240''>And,</span> <span m=''2130170''>now,</span> <span m=''2130680''>let''s</span>
  <span m=''2131000''>cut</span> <span m=''2131250''>down</span> <span m=''2131450''>the</span>
  <span m=''2131520''>sampling</span> <span m=''2131960''>frequency</span> <span m=''2132760''>even</span>
  <span m=''2133040''>further,</span> <span m=''2133940''>to</span> <span m=''2134170''>5</span>
  <span m=''2134530''>kilohertz.</span> <span m=''2140990''>Here</span> <span m=''2141140''>we</span>
  <span m=''2141280''>are</span> <span m=''2141580''>at</span> <span m=''2141790''>2
  pi.</span> <span m=''2145020''>And</span> <span m=''2145250''>then</span> <span
  m=''2145830''>at</span> <span m=''2146490''>4pi.</span> </p><p><span m=''2149390''>All</span>
  <span m=''2149500''>right,</span> <span m=''2149750''>so,</span> <span m=''2150360''>that</span>
  <span m=''2150890''>illustrates</span> <span m=''2151550''>the</span> <span m=''2151650''>effect</span>
  <span m=''2152030''>of</span> <span m=''2152110''>changing</span> <span m=''2152570''>the</span>
  <span m=''2152650''>sampling</span> <span m=''2153150''>frequency.</span> <span
  m=''2154610''>Now</span> <span m=''2155070''>let''s</span> <span m=''2155640''>conclude</span>
  <span m=''2156070''>this</span> <span m=''2156270''>demonstration</span> <span m=''2157080''>of</span>
  <span m=''2157160''>the</span> <span m=''2157270''>effect</span> <span m=''2157750''>of</span>
  <span m=''2157920''>the</span> <span m=''2157990''>sampling</span> <span m=''2158460''>frequency</span>
  <span m=''2159000''>on</span> <span m=''2159070''>the</span> <span m=''2159140''>filter</span>
  <span m=''2159520''>cutoff</span> <span m=''2159950''>frequency</span> <span m=''2161040''>by</span>
  <span m=''2161180''>carrying</span> <span m=''2161630''>out</span> <span m=''2161810''>some</span>
  <span m=''2161950''>filtering</span> <span m=''2162620''>on</span> <span m=''2162920''>some</span>
  <span m=''2163140''>live</span> <span m=''2163430''>audio.</span> <span m=''2164810''>What</span>
  <span m=''2165460''>we''ll</span> <span m=''2165770''>watch,</span> <span m=''2166240''>in</span>
  <span m=''2166320''>this</span> <span m=''2166530''>case,</span> <span m=''2167090''>is</span>
  <span m=''2167740''>the</span> <span m=''2168220''>output</span> <span m=''2169060''>audio</span>
  <span m=''2169870''>waveform</span> <span m=''2171130''>as</span> <span m=''2171360''>a</span>
  <span m=''2171410''>function</span> <span m=''2171850''>of</span> <span m=''2171960''>time</span>
  <span m=''2172640''>on</span> <span m=''2173160''>the</span> <span m=''2173370''>single</span>
  <span m=''2173760''>tray</span> <span m=''2174010''>scope,</span> <span m=''2174970''>and</span>
  <span m=''2175220''>also</span> <span m=''2175940''>we''ll</span> <span m=''2176520''>listen</span>
  <span m=''2176880''>to</span> <span m=''2177000''>the</span> <span m=''2177160''>output.</span>
  <span m=''2178220''>We''ll</span> <span m=''2178410''>begin it</span> <span m=''2178880''>with</span>
  <span m=''2179060''>a</span> <span m=''2179100''>40</span> <span m=''2179440''>kilohertz</span>
  <span m=''2180000''>sampling</span> <span m=''2180700''>rate,</span> <span m=''2181480''>then</span>
  <span m=''2181870''>reduce</span> <span m=''2182280''>that</span> <span m=''2182530''>to</span>
  <span m=''2182630''>20</span> <span m=''2182940''>kilohertz,</span> <span m=''2183590''>10</span>
  <span m=''2183870''>kilohertz,</span> <span m=''2184440''>and</span> <span m=''2184510''>then</span>
  <span m=''2184640''>5</span> <span m=''2184980''>kilohertz.</span> <span m=''2186100''>And</span>
  <span m=''2186340''>in</span> <span m=''2186440''>each</span> <span m=''2186630''>of</span>
  <span m=''2186710''>those</span> <span m=''2186950''>cases,</span> <span m=''2187660''>the</span>
  <span m=''2187820''>effective</span> <span m=''2188280''>filter</span> <span m=''2188630''>cutoff</span>
  <span m=''2189040''>frequency,</span> <span m=''2190120''>then,</span> <span m=''2190430''>is</span>
  <span m=''2190610''>cut</span> <span m=''2190800''>in</span> <span m=''2190910''>half</span>
  <span m=''2191600''>from</span> <span m=''2191770''>4</span> <span m=''2192100''>kilohertz,</span>
  <span m=''2192640''>to</span> <span m=''2192810''>2</span> <span m=''2193130''>kilohertz,</span>
  <span m=''2194110''>to</span> <span m=''2194240''>1</span> <span m=''2194520''>kilohertz,</span>
  <span m=''2195270''>and</span> <span m=''2195440''>then</span> <span m=''2195590''>to</span>
  <span m=''2195690''>500</span> <span m=''2196250''>cycles.</span> </p><p><span m=''2197080''>So</span>
  <span m=''2197300''>let''s</span> <span m=''2197530''>begin</span> <span m=''2197900''>with</span>
  <span m=''2198040''>a</span> <span m=''2198080''>40</span> <span m=''2198420''>kilohertz</span>
  <span m=''2198910''>sampling</span> <span m=''2199350''>frequency,</span> <span
  m=''2200120''>or</span> <span m=''2200290''>an</span> <span m=''2200340''>effective</span>
  <span m=''2200780''>filter</span> <span m=''2201440''>cutoff</span> <span m=''2201840''>frequency</span>
  <span m=''2202550''>of</span> <span m=''2202610''>4</span> <span m=''2202980''>kilohertz.</span>
  <span m=''2209950''>Now,</span> <span m=''2210550''>let''s</span> <span m=''2210940''>reduce</span>
  <span m=''2211200''>that</span> <span m=''2211490''>a</span> <span m=''2211780''>20</span>
  <span m=''2211990''>kilohertz</span> <span m=''2212360''>sampling</span> <span m=''2213030''>frequency,</span>
  <span m=''2214090''>or a 2</span> <span m=''2214200''>kilohertz</span> <span m=''2214760''>filter.</span>
  <span m=''2220090''>Then</span> <span m=''2220900''>a</span> <span m=''2221020''>10</span>
  <span m=''2221260''>kilohertz</span> <span m=''2221800''>sampling</span> <span m=''2222250''>frequency.</span>
  <span m=''2227950''>And,</span> <span m=''2228570''>finally,</span> <span m=''2229060''>a</span>
  <span m=''2229110''>5</span> <span m=''2229450''>kilohertz</span> <span m=''2230000''>sampling</span>
  <span m=''2230450''>frequency</span> <span m=''2231130''>corresponding</span> <span
  m=''2231890''>to</span> <span m=''2232310''>a</span> <span m=''2232740''>500</span>
  <span m=''2233140''>cycle</span> <span m=''2234150''>equivalent</span> <span m=''2234830''>analog</span>
  <span m=''2235340''>filter.</span> <span m=''2240280''>Alright,</span> <span m=''2241150''>now,</span>
  <span m=''2241430''>let''s</span> <span m=''2241800''>finally</span> <span m=''2242130''>conclude</span>
  <span m=''2242670''>by</span> <span m=''2243450''>returning</span> <span m=''2243800''>to</span>
  <span m=''2244690''>a</span> <span m=''2244760''>little</span> <span m=''2245010''>higher</span>
  <span m=''2245350''>quality</span> <span m=''2245810''>ragtime</span> <span m=''2246560''>by</span>
  <span m=''2246920''>changing</span> <span m=''2247418''>the sampling</span> <span
  m=''2247916''>frequency</span> <span m=''2248414''>back</span> <span m=''2248912''>to</span>
  <span m=''2249410''>40</span> <span m=''2249908''>kilohertz.</span> </p><p><span
  m=''2257880''>Alright,</span> <span m=''2258240''>well,</span> <span m=''2258770''>hopefully</span>
  <span m=''2259800''>what</span> <span m=''2260020''>you''ve</span> <span m=''2260170''>seen</span>
  <span m=''2260510''>in</span> <span m=''2260620''>the</span> <span m=''2260700''>demonstration</span>
  <span m=''2261660''>and</span> <span m=''2262620''>in</span> <span m=''2262760''>this</span>
  <span m=''2262980''>lecture</span> <span m=''2265630''>gives</span> <span m=''2265870''>you</span>
  <span m=''2266270''>a</span> <span m=''2266350''>sense</span> <span m=''2266730''>and
  a</span> <span m=''2266820''>feeling</span> <span m=''2267460''>for</span> <span
  m=''2268190''>the</span> <span m=''2268300''>analysis</span> <span m=''2269630''>and</span>
  <span m=''2269980''>the</span> <span m=''2270070''>use</span> <span m=''2270350''>of</span>
  <span m=''2271420''>discreet-time</span> <span m=''2272780''>filters</span> <span
  m=''2273850''>for</span> <span m=''2274000''>processing</span> <span m=''2274730''>continuous-time</span>
  <span m=''2275540''>signals.</span> <span m=''2276160''>And</span> <span m=''2277160''>as</span>
  <span m=''2277480''>you</span> <span m=''2277590''>may</span> <span m=''2277760''>be</span>
  <span m=''2277950''>aware,</span> <span m=''2278650''>and</span> <span m=''2278920''>as</span>
  <span m=''2279090''>I''ve</span> <span m=''2279240''>tried</span> <span m=''2279500''>to</span>
  <span m=''2279550''>indicate</span> <span m=''2280480''>previously</span> <span
  m=''2280980''>in</span> <span m=''2281060''>the</span> <span m=''2281130''>past,</span>
  <span m=''2282100''>this,</span> <span m=''2282350''>in</span> <span m=''2282460''>fact,</span>
  <span m=''2282810''>is</span> <span m=''2283370''>one</span> <span m=''2283730''>very</span>
  <span m=''2284020''>important--</span> <span m=''2284520''>but</span> <span m=''2284660''>not</span>
  <span m=''2284880''>the</span> <span m=''2285030''>only--</span> <span m=''2285375''>but</span>
  <span m=''2285720''>one</span> <span m=''2286050''>very</span> <span m=''2286340''>important</span>
  <span m=''2287680''>context</span> <span m=''2288670''>in</span> <span m=''2288860''>which</span>
  <span m=''2289390''>discreet-time</span> <span m=''2290060''>filtering</span> <span
  m=''2290900''>is</span> <span m=''2291070''>used.</span> <span m=''2292000''>And</span>
  <span m=''2292430''>this,</span> <span m=''2292640''>in</span> <span m=''2292740''>fact,</span>
  <span m=''2293630''>is</span> <span m=''2294270''>an</span> <span m=''2294420''>area</span>
  <span m=''2294860''>that</span> <span m=''2295260''>is</span> <span m=''2295450''>developing</span>
  <span m=''2295950''>rapidly</span> <span m=''2296480''>because</span> <span m=''2296890''>of</span>
  <span m=''2296970''>the</span> <span m=''2297070''>fact</span> <span m=''2297970''>that</span>
  <span m=''2299220''>microprocessors,</span> <span m=''2300450''>digital</span> <span
  m=''2300800''>technology,</span> <span m=''2301670''>computers,</span> <span m=''2302210''>et</span>
  <span m=''2302490''>cetera</span> <span m=''2303390''>afford</span> <span m=''2304380''>considerable</span>
  <span m=''2305100''>flexibility</span> <span m=''2306250''>in</span> <span m=''2306940''>carrying</span>
  <span m=''2307430''>out</span> <span m=''2307950''>digital</span> <span m=''2308560''>processing</span>
  <span m=''2309170''>of</span> <span m=''2309250''>signals.</span> <span m=''2310710''>And</span>
  <span m=''2313080''>when</span> <span m=''2313310''>digital</span> <span m=''2313680''>processing</span>
  <span m=''2314390''>is</span> <span m=''2314520''>used,</span> <span m=''2315070''>that</span>
  <span m=''2316440''>naturally</span> <span m=''2317540''>corresponds</span> <span
  m=''2318780''>to</span> <span m=''2321300''>implementing</span> <span m=''2322000''>the</span>
  <span m=''2322090''>processing</span> <span m=''2323220''>and</span> <span m=''2323470''>analyzing</span>
  <span m=''2324190''>it</span> <span m=''2324380''>in</span> <span m=''2324510''>discreet-time.</span>
  </p><p><span m=''2328100''>Now,</span> <span m=''2329800''>in</span> <span m=''2330310''>the</span>
  <span m=''2330430''>next</span> <span m=''2330710''>lecture</span> <span m=''2331410''>we''ll</span>
  <span m=''2331980''>be</span> <span m=''2332120''>continuing</span> <span m=''2332880''>on</span>
  <span m=''2333460''>another</span> <span m=''2334410''>aspect--</span> <span m=''2334980''>developing</span>
  <span m=''2335420''>another</span> <span m=''2335710''>aspect--</span> <span m=''2336460''>of</span>
  <span m=''2337310''>sampling.</span> <span m=''2338400''>And,</span> <span m=''2338550''>in</span>
  <span m=''2338660''>particular,</span> <span m=''2339530''>what</span> <span m=''2339760''>we''ll</span>
  <span m=''2339900''>be</span> <span m=''2340040''>talking</span> <span m=''2340470''>about</span>
  <span m=''2341020''>is</span> <span m=''2341830''>sampling</span> <span m=''2342550''>of</span>
  <span m=''2342680''>discreet-time</span> <span m=''2343340''>signals.</span> <span
  m=''2344760''>As</span> <span m=''2344950''>I''ll</span> <span m=''2345080''>indicate</span>
  <span m=''2345570''>there,</span> <span m=''2346390''>one</span> <span m=''2346620''>of</span>
  <span m=''2346740''>the</span> <span m=''2346850''>contexts</span> <span m=''2347610''>in</span>
  <span m=''2347720''>which</span> <span m=''2348440''>discreet-time</span> <span
  m=''2349140''>sampling,</span> <span m=''2349790''>in</span> <span m=''2349900''>fact,</span>
  <span m=''2350610''>plays</span> <span m=''2350940''>an</span> <span m=''2351020''>important</span>
  <span m=''2351470''>role</span> <span m=''2352890''>is</span> <span m=''2353420''>in</span>
  <span m=''2353540''>the</span> <span m=''2353630''>context</span> <span m=''2354720''>in</span>
  <span m=''2354870''>which</span> <span m=''2355570''>we</span> <span m=''2356010''>are</span>
  <span m=''2356540''>processing</span> <span m=''2357420''>continuous-time</span>
  <span m=''2358180''>signals</span> <span m=''2359060''>using</span> <span m=''2359430''>discreet-time</span>
  <span m=''2360060''>processing.</span> <span m=''2361170''>Where,</span> <span m=''2361570''>in</span>
  <span m=''2361680''>fact,</span> <span m=''2362420''>one</span> <span m=''2362810''>step</span>
  <span m=''2363370''>that</span> <span m=''2363520''>we</span> <span m=''2363640''>might</span>
  <span m=''2363850''>want</span> <span m=''2364030''>to</span> <span m=''2364100''>take--</span>
  <span m=''2364430''>in</span> <span m=''2364510''>addition</span> <span m=''2364920''>to</span>
  <span m=''2365020''>the</span> <span m=''2365100''>steps</span> <span m=''2365430''>so</span>
  <span m=''2365530''>we''ve</span> <span m=''2365680''>talked</span> <span m=''2366000''>about</span>
  <span m=''2366260''>here--</span> <span m=''2367130''>is</span> <span m=''2367620''>an</span>
  <span m=''2367720''>additional</span> <span m=''2368150''>sampling</span> <span
  m=''2368660''>process</span> <span m=''2369820''>following</span> <span m=''2370820''>whatever</span>
  <span m=''2371470''>kinds</span> <span m=''2371850''>of</span> <span m=''2371940''>filtering</span>
  <span m=''2372760''>that</span> <span m=''2373030''>we</span> <span m=''2373160''>do.</span>
  </p><p><span m=''2373770''>Well,</span> <span m=''2374050''>that''s</span> <span
  m=''2374300''>a</span> <span m=''2374350''>discussion</span> <span m=''2375040''>and</span>
  <span m=''2375280''>a</span> <span m=''2375360''>topic</span> <span m=''2375910''>that</span>
  <span m=''2376090''>we''ll</span> <span m=''2376240''>be</span> <span m=''2376350''>going</span>
  <span m=''2376650''>into</span> <span m=''2377000''>in</span> <span m=''2377080''>the</span>
  <span m=''2377160''>next</span> <span m=''2377420''>lecture.</span> <span m=''2377930''>Thank</span>
  <span m=''2378170''>you.</span> </p>'
type: course
uid: 65a9127bbfb6e04209299642da1c3167

---
None