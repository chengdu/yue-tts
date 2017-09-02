Yuet - Tiny Cantonese TTS engine
========
<em><i>Cantonese speech synthesis engine for offline embedded system.</i></em><br>

Features
========
<ol>
<li><b>*Accuracy</b>, high precision, accurate <a href="http://sevenuc.com/en/ai.html"> Chinese word segmentation</a> based on natural language understanding, accurate pronunciation of the variants of character pronunciation in different words with text contextual analysis.
</li>
<li><b> Naturalness</b>, tone changes with prosody conversion, appropriate breaks for words in long sentences, and emphasis on the correct words. High naturalness of synthesised speech for mixed text input, the mixed content can be any Chinese, English, number, symbols and all other possible characters defined in Unicode 8.0, it was compatible with HKSCS-2004 (Big5, ISO 10646). The default encoding of text is UTF-8. </li>
<li><b> Intelligent</b>, detect unknown words (unknown names of things, place, person and organisation etc) intelligently, handle all kinds of Chinese punctuations. Artificial intelligence for the pronunciation of "Chinese Number String" to translated "Chinese Readings", such as date time, price, units of measure, phone number, post code, money symbols, license plate, brand name, product model, etc. </li>
<li><b> Tiny</b>, small memory footprint and storage, extremely small computing resource required. The precompiled binary (library, .dll, .so, .a) is about 200Kb and plus the compressed data, data + program binary &lt;4MB, extremely small space occupied. </li>
<li><b> Offline</b>, platform independent, PCM audio output don't require a server or network connection. In-memory output or Wav format file will be produced by default. </li>
<li><b> Self-contained</b>, instant, high speed, handle any length of text, the category of the text can be in any field, any industry, the engine is based on natural language processing, no require of any external dictionary or corpus. The compressed database can process any Chinese text of any industry. Reading news, speaking novels smoothly,  deal with text context intelligently, produce and playback voice continuously without time limit.</li>
<li><b> Automatic translation</b>, true words and pure pronunciation of the language, speech synthesis for the entire file or paragraph of text, and output the corresponding Yale, or Jyutping romanisation text. Mandarin words will be automatically translated into Cantonese by default, see <a href="http://www.sevenuc.com/en/translation.html"> some examples </a> in that page.</li>
<li> Both female and male voice supported, and child voice supported by algorithm generating with female voice. </li>
<li> Portable, cross platform, written in pure ANSI C from scratch without external dependancies. </li>
<li> Anywhere, running on AVR, ARM, PIC, MIPS embedded systems such as toy, watch, robot and iPhone, Android, etc, mobile platforms, of course any normal desktops, and embedded in products, such as news paper or ebook reader, story teller, language learning tool, chat, help desk and game agent, translation assistant and so on. </li>
<li> Embeddable, can be loaded into memory and embedded in other programs. </li>
</ol>
<span class="title">Why Another TTS Engine?</span><br><br>
The features of Yuet is the reason to develop another Chinese TTS engine.<br>
<ol>
<li> Although there's so many TTS engine that can process Chinese text, but none of them can satisfy the requirements and generate speech based on <b>clear word border</b>, emphasis on the appropriate words, including the engines from Google, Apple (Nuance), Microsoft, and NeoSpeech, iFLYTEK, eSpeak, Ekho, PiTL etc. The engine of Yuet is based on Chinese word segmentation and natural language understanding that differs compared to them. </li>
<li> Minimising the size of Yuet to fit embedded system to an <b>extremely small size</b> is the design goal to pursue, and also the design philosophy of the software. The engine of Cantonese all-in-one standalone is only 4MB, whereas common solutions mentioned above from the famous companies even requires well over 500~600MB of storage. For embedded system, ultra-small footprint can have many advantages, e.g. high flexibility for programming, performance and dramatically reduced the hardware costs, etc. </li>
<li> <b>Offline</b>, embedded TTS engine has the ability to avoid troubles caused by instability of network connection, and the high cost of the development and maintenance of the backend servers. </li>
<li> <b>Independent, complete</b>. Yuet can handle any content of text, detect unknown words intelligently, <b>no require of any extra dictionary</b>. The category of the content can be in any field, any industry, e.g. architecture, agriculture, biology, business, commerce, communications, computer, electronics, environment, education, finance, industry, mechanical, oil, mining, law &amp; polities, government, military, transport, engineering, medicine, physics &amp; chemistry, sports, news, etc. </li>
<li> And other reasons to develop yet another Chinese TTS engine. </li>
</ol>

Yuet in action
========
<br>
There is an English-Chinese dictionary app demonstrate the features of the engine and has the same name on App Store. see Yuet in action, download the app on iTunes, <a href="https://itunes.apple.com/us/app/yue/id898134235?mt=8"> Yuet - Cantonese and Hong Kong slang </a>

References
========
Download:<a href="javascript:void(0)">&nbsp;API document&nbsp;<img src="http://sevenuc.com/images/download.png"> (deprecated)</a><br>
<a href="javascript:void(0)"><img src="http://sevenuc.com/images/download.png">&nbsp;uctts_0.2.26.tar.gz (deprecated)</a>
(7.7MB,&nbsp;md5:&nbsp;1f5ce2b7fb5628efa2bd7823e59de38d)<br>
This program is a command line tool (standalone executable) that can segment Chinese text into words, generate Yale romanisation of the input text. Try it, you'll be amazed at how accurate the engine is. It can segment any of the business sentences in the attached material into words with 100% correct output.<br>
Home: <a href="http://www.sevenuc.com/en/tts.html">http://www.sevenuc.com/en/tts.html</a><br>

Keywords
========
Chinese Text Segmentation, Chinese Word Segmentation, Chinese Text Classification, Natural Language Understanding, Natural Language Processing, TTS, Text-to-Speech, Speech Synthesis, Speech Synthesiser, Child Voice Synthesis, ASR, Automated Speech Recognition, Yale, 語音合成, 音聲合成, 童音合成,  語音識別, 音聲認識,  おんせいごうせい,   النص إلى ك لام,   Canton, Cantonese, Hong Kong, Macau,  Macao,  Chinese,  China,  grammar,  dictionary, lexicon, moji, kanji, hanja, pronunciation, dialect, argot, jargon, slang, etymology,  ข้อความที่จะพูด,  Metinden Konuşmaya, Text till tal, Besedilo v govor, Tekst na mowę, Tekst til tale, Teks Ucapan untuk, Текст в речь, 텍스트 음성 변환, Κείμενο σε Ομιλία, Teksti puheeksi, Tekst til tale, Текст към говор, Texto a voz, Literature, Linguistics, 単語分割エンジン, 単語分割, 斷詞, 分詞, 中文斷詞, 中文分詞, 文本分類, 人工智能, 人工智慧, 模式識別, 機器學習, 機械学習, 自然語言處理, 自然言語処理, 粵語, 廣東話, 香港, 澳門, 中國語, 語法, 語言學, 計算語言學, 耶魯, 字典,  詞典, 詞彙, 漢字, 發音, 方言, 隱語, 行話, 俚語, 詞源<br>



