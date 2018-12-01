# KARPLUS-STRONG合成

> Karplus-Strong(KS)アルゴリズムは撥弦とドラムの合成法であり, 遅延列, または波形テーブル繰り返し（recirculating wavetable）の原理にも基づく効率的な方法である（Karplus and Strong 1983; Jeffe and Smith 1983）.
>
> コンピュータ音楽 歴史・テクノロジー・アート (原題 : The Computer Music Tntorial. 1996), 著 Curtis Roads. 訳・監修 青柳龍也・小坂直敏・平田圭二・堀内靖雄. 東京電機大学出版局 2001 235  

<br>
数十から数百サンプルの短い波形テーブルを遅延させて繰り返す（1秒に数百回）ことでギターやスネアのような音を合成できる。  
delayオペレータとフィードバックを用いて実装する。