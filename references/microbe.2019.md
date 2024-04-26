Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2019-08

----------

# microbe.2019

**Table of Contents**
- [2019-08](#2019-08)
- [2019-07](#2019-07)
- [2019-05-19](#2019-05-19)
- [2019-05-12](#2019-05-12)
- [2019-05-03](#2019-05-03)
- [2019-03-24](#2019-03-24)
- [2019-03-20](#2019-03-20)
- [2019-03-11](#2019-03-11)
- [2019-03-02](#2019-03-02)
- [featuring](#featuring)
- [updates](#updates)
- [hydrothermal vent](#hydrothermal-vent) 熱水噴出孔
- [nutritional_groups](#nutritional_groups) 栄養的分類
- [temperature](#temperature) 温度
  - [psychrophile](#psychrophile) 低温菌
- [porphyrin](#porphyrin) ポルフィリン
  - [hemoglobin](#hemoglobin) ヘモグロビン
- [unclassified](#unclassified)
- [metasub](#metasub)
- [blast](#blast)
- [codon](#codon)
- [transcriptome](#transcriptome)
- [microbedb](#microbedb)
- [wiebler](#wiebler)
- [definition](#definition)

----------
## definition

https://github.com/haruosuz/ksbn/blob/master/2018/README.2018.3.md
Keyword 遺伝，メンデルの法則，遺伝子型，表現型，対立遺伝子
https://github.com/haruosuz/ksbn/blob/master/2018/README.2018.4.md

https://ja.wikipedia.org/wiki/対立遺伝子#遺伝子型と表現型
allele
個体がもつ対立遺伝子の組合せを遺伝子型 (genotype) と呼ぶ。これに対して、見かけ上現れる形質を表現型 (phenotype) と呼ぶ。

https://ja.wikipedia.org/wiki/表現型
phenotype

https://ja.wikipedia.org/wiki/遺伝子型
genotype
ある遺伝子が存在しても、その形質が発現しない場合もあり、表出する形質（表現型）と遺伝子型は必ずしも 1:1 に対応しない。例えば、ヒトのABO式血液型ならば、A型というひとつの表現型に対してAAとAOという二つの遺伝子型があり得る。

----------
## 2019-07


https://github.com/haruosuz/DS4GD/blob/master/2019/CaseStudy.md#ncbi-genome-list

https://doi.org/10.7875/togotv.2015.037
2015-05-15 GOLD -Genomes Online Database- の使い方

----------
### taxonomy

https://ja.wikipedia.org/wiki/分類学
taxonomy

https://ja.wikipedia.org/wiki/生物の分類

https://ja.wikipedia.org/wiki/階級_(生物学)
門・綱・目・科・属・種などの、分類の階層のこと。分類階級

http://idsc.tokyo-eiken.go.jp/epid/y2016/tbkj3705/
分類における最小単位は「種：species」であり、各々の進化系統についてさらに上位の分類として「属：genus」、「科：family」として体系化されている。このような「種」や「属」という概念の中で、生物の個体はさらに「種」の下位概念である「株：strain」という表現も用いられ、その名が汎用されている。

https://ja.wikipedia.org/wiki/タイプ_(分類学)
原核生物では純粋培養された生菌株がタイプとして認められる。その菌株を基準株 (type strain) という。


### BacDive

https://bacdive.dsmz.de/
BacDive | The Bacterial Diversity Metadatabase

"Arthrobacter"の検索結果
https://bacdive.dsmz.de/search?search=Actinobacteria&submit=

https://github.com/haruosuz/mgsa/blob/master/references/README.memo.md#bacdive

### mutation

http://www.med.kitasato-u.ac.jp/~molgen/sub9.html
遺伝子変異の記述法
```
I. DNAレベルでの記載法
　1. 塩基置換（Substitution）の場合
　2.	塩基の欠失（deletion）の場合
　3.	塩基の重複（duplication）の場合
　4. 塩基の挿入（insertion）の場合
　5. 挿入と欠失の組合せの場合（Deletion/insertion, Indel）
II. タンパク質レベルでの記載法
　1.	アミノ酸置換の場合

　5. フレームシフト変異の場合
```

https://ja.wikipedia.org/wiki/点突然変異
あるいは1塩基置換
	• トランジション変異：
	• トランスバージョン変異：

http://nesseiken.info/Chiba_lab/index.php?cmd=read&page=授業%2FH24%2F進化生物学I%2F系統樹に関する基本用語
	• 極性が未決定の形質（unpolarized character）　変化の方向性が決まっていない形質
		• 　　例：DNAの塩基置換は A→Tでも、T→Aでも起こる。

https://www.quora.com/What-does-it-mean-by-mutation-is-directionless-What-does-direction-mean-in-biology
What does it mean by 'mutation is directionless'? What does direction mean in biology? - Quora

https://www.ncbi.nlm.nih.gov/pubmed/22315421
Proc Natl Acad Sci U S A. 2012 Feb 21;109(8):3065-70. doi: 10.1073/pnas.1121491109. Epub 2012 Feb 6.
Genomic epidemiology of the Escherichia coli O104:H4 outbreaks in Europe, 2011.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3286951/
Among these four isolates, we found only two SNPs relative to a published genome from the German outbreak, TY2482 (9): two of the isolates showed no differences relative to the reference, and two showed one SNP each (nucleotide positions 224851 and 1096014) (Table 2;  
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3286951/table/t02/
```
Table 2.
SNPs identified within E. coli O104:H4 outbreak isolates
SNP position	Gene/region	Isolates	SNP*	Substitution
```

http://wiki.pitagora-galaxy.org/wiki/index.php/Workflows#Orione
orione-live-supplement	微生物NGS解析：リードの前処理、リシーケンシング、de novoアセンブリ、RNA-Seq、メタゲノム

https://jp.illumina.com/content/dam/illumina-marketing/apac/japan/documents/pdf/publication_microbiology-j.pdf
[PDF]総説：微生物ゲノム研究 - イルミナ株式会社

研究室において、モデル生物のゲノムは時間経過とともに変異を蓄積します11,12。
全ゲノムリシーケンス
中立進化モデル
中立変異を蓄積

全ゲノムシーケンスおよびソーシャルネットワーク解析
レファレンスゲノム
SNP

https://www.ncbi.nlm.nih.gov/pubmed/21345102
N Engl J Med. 2011 Feb 24;364(8):730-9. doi: 10.1056/NEJMoa1003176.
Whole-genome sequencing and social-network analysis of a tuberculosis outbreak.
Gardy JL1, 

----------
## 2019-07-14

https://www.ncbi.nlm.nih.gov/pubmed/23829079
Pol J Microbiol. 2013;62(1):67-72.
Efficiency of selected mutagens in generating Xanthophyllomyces dendrorhous strains hyperproducing astaxanthin.
Stachowiak B1.
http://www.pjm.microbiology.pl/archive/vol6212013067.pdf
Selection procedure.

https://www.ncbi.nlm.nih.gov/pubmed/29615045
Microb Cell Fact. 2018 Apr 3;17(1):53. doi: 10.1186/s12934-018-0898-7.
A common mechanism explains the induction of aerobic fermentation and adaptive antioxidant response in Phaffia rhodozyma.
Martínez-Cárdenas A1, Chávez-Cabrera C1,2, Vasquez-Bahena JM3, Flores-Cotera LB4.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5883411/

aox, which encodes an alternative oxidase protein.

alternative oxidase (AOX) 

Fig. 3
Relative expression levels of aox and asy in cells of P. rhodozyma grown in the cultures − Cu and +Cu. 

----------
## Wiebler

https://www.ncbi.nlm.nih.gov/pubmed/29720413
Proc Biol Sci. 2018 May 16;285(1878). pii: 20180241. doi: 10.1098/rspb.2018.0241.
Urea hydrolysis by gut bacteria in a hibernating frog: evidence for urea-nitrogen recycling in Amphibia.
Wiebler JM1, Kohl KD2, Lee RE Jr1, Costanzo JP3.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5966601/
Urea hydrolysis by gut bacteria in a hibernating frog: evidence for urea-nitrogen recycling in Amphibia
- All microbial sequences have been uploaded to the NCBI Short Read Archive (SRA) under accession PRJNA432152.
- We attempted to determine which among the observed genera had at least one member that potentially can catabolize urea by querying the Kyoto Encyclopedia of Genes and Genomes (KEGG), an online resource that contains gene catalogues from sequenced organisms, for entries having urease-encoding genes using the KEGG orthology (KO) identifiers K01427, K01428, K01429, K01430 and K14048. 
- https://www.genome.jp/dbget-bin/www_bget?ko:K01427	
URE
urease [EC:3.5.1.5]
- https://www.genome.jp/dbget-bin/www_bget?ko:K01428
ureC
urease subunit alpha [EC:3.5.1.5]
- https://www.genome.jp/dbget-bin/www_bget?ko:K01429
ureB
urease subunit beta [EC:3.5.1.5]

https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA432152
Gut microbiome of hibernating frogs
Gut microbiome of hibernating frogs Targeted loci environmental
We compared the microbial inventories of hibernating and active frogs.

https://www.genome.jp/dbget-bin/www_bget?ko:K01427

https://www.genome.jp/dbget-bin/www_bget?ko:K01428
Name	
ureC
Definition	
urease subunit alpha [EC:3.5.1.5]

バッチ効果 Batch Effect
https://github.com/haruosuz/statistics/blob/master/README.md#batch-effect



----------
## microbedb
http://microbedb.jp

https://integbio.jp/dbcatalog/record/nbdc01181
MicrobeDB.jp - Integbio データベースカタログ
本DBは，微生物に関する多種多様な情報を遺伝子・系統・環境の3つの軸に沿って整理統合し，セマンティックWeb技術を利用して単一の検索ウィンドウからそれらの情報を検索可能な統合DBです。

https://dbarchive.biosciencedbc.jp/jp/microbedb/desc.html
データベースの説明 - MicrobeDB.jp | LSDB Archive

http://togotv.dbcls.jp/20181221.html
2018-12-21 微生物統合データベースMicrobeDB.jpの活用法 @ 第41回日本分子生物学会年会
約10分

https://events.biosciencedbc.jp/images/exhibition/20181128_mori.pdf
微生物統合データベース MicrobeDB.jpの. 活用法. Nov. 28, 2018.

https://events.biosciencedbc.jp/sympo/togo2018/poster/
シンポジウム トーゴーの日シンポジウム2018 ポスター発表
https://events.biosciencedbc.jp/images/togo2018/poster58_2018.pdf
58	藤澤貴智	情報・システム研究機構 国立遺伝学研究所
生命情報研究センター	MicrobeDB.jp ポータル: 統合微生物データベースのポータルサイト構築
https://events.biosciencedbc.jp/images/togo2018/poster60_2018.pdf
59	森宙史	情報・システム研究機構 国立遺伝学研究所
生命情報研究センター	MicrobeDB.jpのメタゲノム解析パイプライン

https://togotv.dbcls.jp/20180111.html
2018-01-11 微生物研究開発における微生物統合データベースMicrobeDB.jpの利用法
約27分

https://researchmap.jp/himori/
森宙史 - 研究者 - researchmap

----------
## transcriptome
https://ja.wikipedia.org/wiki/トランスクリプトーム

http://www.iu.a.u-tokyo.ac.jp/~kadota/
門田　幸二のホームページ
「トランスクリプトーム解析」「(Rで)マイクロアレイデータ解析」と「(Rで)塩基配列解析」
- NGS(RNA-seq)解析関連
- マイクロアレイ解析関連
- 
- 門田幸二,「トランスクリプトーム解析の現況2013（詳細版）」, 東京大学大学院農学生命科学研究科第123回アグリバイオインフォマティクスセミナー, 東京大学(東京), 2013.11.01
- 門田幸二,「トランスクリプトーム解析の現況：マイクロアレイ vs. RNA-seq」, 生命医薬情報学連合大会 「オミックス・計算　そして創薬」・オミックス解析における実務者意見交換会, タワーホール船堀(東京), 2013.10.30

http://www.iu.a.u-tokyo.ac.jp/~kadota/r_seq.html
(Rで)塩基配列解析
(last modified 2019/05/31, since 2010)

http://www.iu.a.u-tokyo.ac.jp/~kadota/r.html
(Rで)マイクロアレイデータ解析
(last modified 2019/03/17, since 2005)

https://www.subioplatform.com/ja/products/subioplatform/rna-seq-vs-microarray
RNA-Seq vs. マイクロアレイ | Subio Platform

2013-01-29
https://tenure5.vbl.okayama-u.ac.jp/HM_blog/?p=557
RNAseqとマイクロアレイによるmRNAの定量ーある解析例 | 酵母とシステムバイオロジー


----------
## codon

https://github.com/haruosuz/codon/blob/master/README.md

https://github.com/haruosuz/codon/blob/master/README.md#heterologous-gene-expression
異種遺伝子発現

https://github.com/haruosuz/codon/blob/master/README.md#tools
ツール

https://github.com/haruosuz/codon/blob/master/README.md#growth-rate
増殖速度

### Xanthophyllomyces dendrorhous

https://github.com/haruosuz/codon/blob/master/README.md#database
データベース
Codon Usage Database
http://www.kazusa.or.jp/codon/cgi-bin/showcodon.cgi?species=5421
```
Xanthophyllomyces dendrorhous [gbpln]: 32 CDS's (11219 codons)
fields: [triplet] [frequency: per thousand] ([number])
UUU 19.1(   214)  UCU 16.8(   189)  UAU 12.7(   142)  UGU  4.0(    45)
UUC 27.5(   308)  UCC 18.4(   206)  UAC 20.3(   228)  UGC  6.0(    67)
UUA  7.4(    83)  UCA 11.1(   124)  UAA  1.2(    13)  UGA  1.2(    14)
UUG 20.1(   226)  UCG 15.6(   175)  UAG  0.4(     5)  UGG 15.3(   172)

CUU 24.4(   274)  CCU 23.7(   266)  CAU  8.6(    97)  CGU  4.4(    49)
CUC 30.8(   346)  CCC 18.8(   211)  CAC 12.7(   143)  CGC  2.2(    25)
CUA  9.3(   104)  CCA 11.1(   124)  CAA 10.1(   113)  CGA 22.6(   254)
CUG 13.4(   150)  CCG 10.6(   119)  CAG 18.1(   203)  CGG  7.9(    89)

AUU 16.1(   181)  ACU 12.4(   139)  AAU  6.6(    74)  AGU  8.1(    91)
AUC 34.2(   384)  ACC 20.5(   230)  AAC 20.9(   235)  AGC  8.4(    94)
AUA  3.0(    34)  ACA 10.3(   116)  AAA 14.6(   164)  AGA 12.3(   138)
AUG 22.6(   254)  ACG  8.3(    93)  AAG 36.8(   413)  AGG  8.9(   100)

GUU 20.1(   226)  GCU 27.1(   304)  GAU 26.0(   292)  GGU 17.8(   200)
GUC 30.8(   346)  GCC 27.5(   308)  GAC 26.9(   302)  GGC 12.3(   138)
GUA  6.7(    75)  GCA 13.7(   154)  GAA 26.0(   292)  GGA 27.4(   307)
GUG 12.3(   138)  GCG  9.7(   109)  GAG 36.4(   408)  GGG  9.1(   102)
```

https://www.ncbi.nlm.nih.gov/pubmed/25887493
BMC Genomics. 2015 Apr 13;16:293. doi: 10.1186/s12864-015-1493-5.
Codon usage and codon context bias in Xanthophyllomyces dendrorhous.
Baeza M1, Alcaíno J2, Barahona S3, Sepúlveda D4, Cifuentes V5.

- https://github.com/haruosuz/DS4GD/blob/master/2019/CaseStudy.md#ncbi-genome-list
- https://www.ncbi.nlm.nih.gov/genome/browse/#!/overview/Xanthophyllomyces%20dendrorhous
- https://www.ncbi.nlm.nih.gov/genome/browse/#!/eukaryotes/Xanthophyllomyces%20dendrorhous

```
$grep "Xanthophyllomyces dendrorhous" overview.txt 
Xanthophyllomyces dendrorhous	Eukaryota	Fungi	Basidiomycetes	19.5195	-	-	-	2
Xanthophyllomyces dendrorhous virus L1A	Viruses	dsRNA viruses	Totiviridae	0.004655	1	-	-1
Xanthophyllomyces dendrorhous virus L1B	Viruses	dsRNA viruses	Totiviridae	0.004619	1	-	-1
```

----------
## blast

https://doi.org/10.7875/togotv.2019.108
2019-05-24 NCBIを使ってアミノ酸配列を検索して取得する

https://doi.org/10.7875/togotv.2017.023
2017-03-21 NCBI BLASTの使い方 〜基本編〜 2017

2018-11-09
https://togotv.dbcls.jp/ajacs2018025.html
ゲノムデータベースと次世代シークエンスデータベース
Protein BLAST も試してみましょう
GTFII-I のアミノ酸配列を UniProtKB/SwissProt データベースに対して検索した結果

https://togotv.dbcls.jp/ja/genome.html
ゲノム、核酸配列・構造解析

----------
## metasub

データ解析コンテスト CAMDA 2017 challenge (http://camda2017.bioinf.jku.at/doku.php)
において、MetaSUBのメタゲノム配列データを用いて、複数のAcinetobacterを同定したと報告されています。
https://www.ncbi.nlm.nih.gov/pubmed/29743119
Biol Direct. 2018 May 9;13(1):9. doi: 10.1186/s13062-018-0211-z.
Profiling microbial strains in urban environments using metagenomic sequencing data.
Zolfo M1, Asnicar F1, Manghi P1, Pasolli E1, Tett A1, Segata N2.
- We applied three complementary methods on the 1614 metagenomes of the CAMDA 2017 challenge. With MetaMLST we identified 121 known sequence-types from 15 species of clinical relevance. For instance, we identified several Acinetobacter strains that were close to the nosocomial opportunistic pathogen A. nosocomialis.

https://github.com/haruosuz/metasub/blob/master/README.md#olympiome
オリンピック前後の微生物群集の変化

https://t.co/LOOfyINmXi Brazilian Researchers Profile Microbiome of Rio Before, During, After Olympic Games | GenomeWeb

https://github.com/haruosuz/metasub/blob/master/README.md#csd
6月21日 グローバル シティ サンプリング デー の目的
http://metasub.org/global-city-sampling-day/
```
The data generated from these days will be used to address the key aims of the MetaSUB study:
1. To create geospatial metagenomic and forensic genetic maps
2. Identify and track antimicrobial resistance markers (AMRs) in the urban built environment
3. Identify novel biosynthetic gene clusters (BCGs) for drug discovery
```

https://www.youtube.com/watch?v=0FSiRhkZKp8 【ICF2017】バイオテクノロジーセッション
都市の微生物遺伝子解析プロジェクトMetaSUB
```
10:00- ヒトの微生物群集
12:00- 都市の微生物群集
13:00- 都市（ニューヨークの地下鉄）のメタゲノム
15:40- 世界中の都市のメタゲノム（MetaSUB）
16:40- Global City Sampling Day
18:05- オリンピック
18:40- 携帯電話（StuckOnU）
```

https://www.rtri.or.jp/rd/news/human/human_201603.html
公益財団法人鉄道総合技術研究所｜人間科学ニュース 2016年3月号（第202号）
遺伝子で鉄道の環境を見る
例えば鉄道では、路線ごとの環境の特徴の有無が分かることで、路線ごとに適した施策を行う事ができます。また、外国からの観光客や労働者等の増加が見込まれ環境の変化が考えられますが、その変化が予測可能となることで有効な施策を提案することが可能となるでしょう。さらに、環境中の生物の伝播（移動）の様子が把握できれば、インフルエンザなどの感染症の発生時の対策やバイオテロなどの不測の事態に備えるための有用な情報が得られるかもしれません。

https://wired.jp/special/2016/biology/
「微生物から新しいデザインがはじまる」
NY地下鉄の細菌マップ

https://www.ted.com/talks/jessica_green_are_we_filtering_the_wrong_microbes?language=ja
ジェシカ・グリーン「微生物を正しく取り除くために」
今この瞬間にも あなた方は 微生物を互いに交換し合っています

https://www.kinokuniya.co.jp/f/dsg-01-9784314011440
マイクロバイオームの世界―あなたの中と表面と周りにいる何兆もの微生物たち
第3章　私たちの体表やまわりに何がいるか？
スキン・ゲーム｜ジャマーとキーボードの共通点は？｜へそ｜最初のマイクロバイオームを獲得する｜地下鉄｜わが家は心――と微生物――のありか


https://github.com/haruosuz/microbe/blob/master/references/README.memo.md#featuring

感染症の増加要因として、都市化による過密/人口の集中、交通機関の発達による高速移動や国際交流の激増が挙げられます。
http://www.med.osaka-cu.ac.jp/hostdefense/ITLectApr01.html


https://ja.wikipedia.org/wiki/実験計画法
次に、品種・施肥量・圃場の3因子につき各3水準を設定するとしよう。一般には全部で 3 x 3 x 3 = 27 通りの実験が必要である。しかし、交互作用が無視できる場合には表2 に示すように9通りに減らすことができ、この方法は一般には予備実験として利用できる（


https://www3.nhk.or.jp/news/html/20190518/k10011921101000.html
地下鉄構内のＰＭ2.5 閉鎖空間で高濃度「実態調査を」 | NHKニュース

----------
## 2019-05-19

https://link.springer.com/article/10.1007/s002030000163
Carotenoids of an Antarctic psychrotolerant bacterium, Sphingobacterium antarcticus, and a mesophilic bacterium, Sphingobacterium multivorum | SpringerLink

In vitro studies with synthetic membranes of phosphatidylcholine demonstrated that the major pigment was bound to the membranes and decreased their fluidity


https://www.ls.toyaku.ac.jp/~lcb-7/keywords/lowtemp.html
低温適応
低温では常温菌や好熱菌はほとんど生育できないが、低温菌は細胞内の諸機構が低温に適応して生育速度を維持している。低温で生育の遅くなる最大の理由は酵素反応速度がアーレニウスの法則に従って急速に低下することによる。本文で述べたように、低温菌の酵素は酵素反応速度が低温で低下しないような機構を獲得している。
常温菌が低温で生育できないもう一つの理由は低温での細胞膜の流動性の低下にある。膜脂質の流動性が膜タンパク質の機能発現にとって重要であるが、膜脂質は低温で液晶状態からゲル状態へ相転移をおこして流動性を低下させる。低温菌は脂質の不飽和度を増加させて相転移温度を低下させ、低温での膜脂質流動性を確保することにより低温に適応している。

https://www.brh.co.jp/seimeishi/journal/062/research_1.html
RESEARCH ─ 研究を通して ─：生きた膜を支える脂質の分子運動
4. 脂質の分子運動の恒常性
一般に脂質の分子運動が低下する低温環境下では、拡散しやすい脂質分子の割合を増やし、脂質の分子運動を一定に保とうとする。逆に高温環境下では、拡散しにくい脂質分子を増やして分子運動を抑制する。
　このような温度に対する膜脂質の適応を恒流動性適応（註6）と呼ぶ。

5. 膜脂質と体温
　一方、先述したように、低温環境に適応した生物では、膜を拡散しやすい脂質分子で構成する恒流動性適応が観察される。これは個体の至適体温を低温側にシフトし、同時に過度の流動性を防ぐため高温を避けるという性質をもたらす。

----------
## 2019-05-12

https://github.com/haruosuz/ksbn/blob/master/2018/README.2018.4.md#amr
抗生物質

https://github.com/haruosuz/r4bioinfo/blob/master/R_Avril_Coghlan/README.md#uniprot
UniProtウェブサイト (http://www.uniprot.org) にアクセスし、ウェブページ上部の検索ボックスにUniProt accession [ Q9CD83 ] を入力して、"Search"ボタンを押す:  

https://github.com/haruosuz/bioinfo/blob/master/README.md#blast
http://doi.org/10.7875/togotv.2017.023 NCBI BLASTの使い方 〜基本編〜 2017
https://github.com/haruosuz/DS4GD/blob/master/2019/CaseStudy.md#blast
BLAST(Basic Local Alignment Search Tool) はNCBIで開発された配列類似性検索のためのツール。

抗菌＜除菌＜殺菌＜滅菌
https://github.com/haruosuz/microbe/blob/master/references/README.memo.md#definition

人工環境の微生物
https://github.com/haruosuz/microbe/blob/master/references/README.MoBE.md#review
https://twitter.com/NatureRevMicro/status/1031916837896957952
Nature Rev Microbiol on Twitter: "In this Review, @gilbertjacka and @stephensbrent discuss the microbiology of the built environment and consider how research in this area is changing the types of materials we use in buildings and how our built environments affect human health. @built_envi https://t.co/e9zEX2K9aC… https://t.co/d7riEhN2lT"
10:52 AM - 21 Aug 2018

以下の動画 (1:57:22) で9分程度 (12:00-20:40) クリストファー・メイソン(ワイル・コーネル・メディスン大学 生理学・生物物理学 准教授) によりMetaSUBプロジェクトについて紹介されています。
https://www.youtube.com/watch?v=0FSiRhkZKp8 【ICF2017】バイオテクノロジーセッション - YouTube
NASAと共同で実施した宇宙実験から都市の微生物遺伝子解析プロジェクトMetaSUBまで、未来の都市環境デザインについて、ハードウェア、ソフトウェア、そしてウェットウェア(バイオテクノロジー)の観点から議論を展開します。
https://www.youtube.com/watch?v=rOPJt8pvYlM 【ICF2017】Biotechnology Session - YouTube
```
10:00- Human microbiome
12:00- Urban microbiome
13:00- PathoMap (New York City microbiome)
15:40- MetaSUB
16:40- Global City Sampling Day (CSD)
18:00- Olympiome
18:40- StuckOnU
20:40- International Space Station
1:57:22
```

----------
## 2019-05-03

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4882832/
ProCarDB: a database of bacterial carotenoids
http://bioinfo.imtech.res.in/servers/procardb/
Prokaryotic Bacterial Carotenoid DataBase Info
The database also provides information of the pathways involved in the synthesis of carotenoids, enzymes, encoding genes, bacterial species possessing carotenoids.

https://ja.wikipedia.org/wiki/脂質

誘導脂質 (Derived lipid) - 単純脂質や複合脂質から、加水分解によって誘導される化合物。
カロテノイド (Carotenoid))

非極性脂質(Non polar lipids)または中性脂質(Neutral lipids)
カロテノイド

----------
## 2019-03-24

https://github.com/haruosuz/r4bioinfo/tree/master/R_Avril_Coghlan#the-ncbi-sequence-database
NCBI配列データベース

https://twitter.com/hashtag/jsbba2019
日本農芸化学会2019年度大会事務局
https://twitter.com/sugargroove/status/1108211332048781313
Shinya Fushinobu on Twitter: "ジュニア農芸化学会2019、大会２日目の25日（月）に開かれます。 より多くの方に高校生のポスター発表をご審査頂くため、大会に参加される皆様は、是非、ジュニアの会場にもお越しください。交流会・表彰式の参加も歓迎いたします。何卒よろしくお願いします！ #jsbba2019 https://t.co/kQcqPD7r7m… https://t.co/uIaLADCt3X"

http://www.nikkei-science.com/page/sci_book/bessatu/51185.html
進化が語る 現在・過去・未来 | 日経サイエンス
http://www.nikkei-science.com/page/magazine/1003/201003_036.html
深海底のロストシティーが語る生命の起源
熱水噴出孔

https://www.sgmj.org/sgmj2019/program.html
第13回日本ゲノム微生物学会年会 - プログラム・日程表
タイトル	北極と南極の雪を赤く染める藻類の地理的分布
演者	瀬川 高弘（山梨大学　総合分析実験センター）

https://kimuraseminar.wordpress.com/第1回%E3%80%80進化学セミナーのお知らせ/
13:30-15:00 古代DNA（瀬川高弘　山梨大学、森宙史　国立遺伝学研究所）内容
https://kimuraseminar.wordpress.com/2017年8月5日-古代dna/

----------
## 2019-03-11

異なる環境（ヒト、土壌、建造環境である国際宇宙ステーション）に由来する細菌（黄色ブドウ球菌、セレウス菌）のゲノム配列解析に関する研究論文です。
https://www.ncbi.nlm.nih.gov/pubmed/30637341 Pangenomic Approach To Understanding Microbial Adaptations within a Model Built Environment, the International Space Station, Relative to Human Hosts and Soil.

ヒト（皮膚・腸内）微生物群集解析に関連して
法微生物学 Forensic Microbiology に関する情報です。
https://github.com/haruosuz/microbe/blob/master/references/README.microbiome.md#forensic

建造環境の微生物 Microbiology of the Built Environment に関する情報です。
https://github.com/haruosuz/microbe/blob/master/references/README.MoBE.md



----------
## featuring
----------
## updates
## 2019
### 2019-03-18

https://twitter.com/tomatom01987693/status/1107126896649601025
トマン on Twitter: "100年以上にわたり子宮と胎児は無菌状態と考えられ, 児は産道で初めて細菌に暴露されると考えられてきた. が, 近年の研究では正常妊娠・出産例の胎盤, 羊水, 胎便から細菌が検出され, これら細菌の正常な胎児発育への関与が想定されている. (Nature. 2018; 553: 264-266) https://t.co/c9kane7jTz… https://t.co/ThmM8mjXXD"
11:49 PM - 16 Mar 2019

----------
## hydrothermal vent
熱水噴出孔 

http://www.kashiwashobo.co.jp/book/b286870.html
世界は細菌にあふれ、人は細菌によって生かされる
安部　恵子 訳

https://www.youtube.com/channel/UCnZK1E7WoLpFNIHHChgVMtw
I Contain Multitudes - YouTube
 Ed Yong

https://www.youtube.com/watch?v=8W_ywzhkR90&list=PLWYyvE5z4B2j4SIAVRtlxNkQF40nv8Ia-
How Giant Tube Worms Survive at Hydrothermal Vents | I Contain Multitudes - YouTube

https://ja.wikipedia.org/wiki/熱水噴出孔
チューブワームには口も消化管もなく、バクテリアを体内に寄生させる。

https://ja.wikipedia.org/wiki/チューブワーム
硫黄酸化細菌と細胞内共生している。

https://ja.wikipedia.org/wiki/硫黄細菌
上記のような化学合成生物である硫黄細菌のほかに、光合成細菌である緑色硫黄細菌・紅色硫黄細菌などを含めて硫黄細菌とよぶ場合もある[2]。

https://ja.wikipedia.org/wiki/化学合成生物
化学合成生物（かがくごうせいせいぶつ Chemotroph）は、周囲環境にある電子供与体の酸化によってエネルギーを得る生物である。化学栄養生物とも言う[1][2]。 使う分子は有機物の場合もあるし無機物を使う例もある。前者の場合は化学合成有機栄養生物（chemoorganotroph）、後者の場合は化学合成無機栄養生物（chemolithotroph）と言う。化学合成生物は、太陽光エネルギーを利用する光合成生物と対比する称呼である。

http://photosyn.jp/pwiki/index.php?化学無機栄養%28生物%29
化学無機栄養(生物)[chemolithotrophy (chemolithotroph)] †

https://kotobank.jp/word/化学合成無機栄養生物-762904
化学合成独立栄養生物，無機栄養生物，独立栄養生物，独立栄養体，自家栄養生物ともいわれる生物，すなわちエネルギーの獲得と自己の体成分の合成を無機物のみからできる生物のうち光を必要としないもの．硫黄細菌，鉄細菌，硝化細菌，水素細菌など．

https://www.weblio.jp/content/化学合成無機栄養生物
chemoautotroph
独立栄養の生物で、無機物の酸化に伴うエネルギーを利用して生活するもの。硝酸細菌など。

----------
## nutritional_groups
栄養的分類

https://en.wikipedia.org/wiki/Primary_nutritional_groups

https://www.academickids.com/encyclopedia/index.php/Primary_nutritional_groups
ja:栄養的分類

http://www.research.kobe-u.ac.jp/ans-koala/bunrui.html
栄養的分類 - Wikiwand

http://www.research.kobe-u.ac.jp/ans-koala/bunrui.html
細菌の栄養的分類

----------
## 2019-03-20

DNAまたはタンパク質の配列を検索する手順は以下のページに記載されています。
https://github.com/haruosuz/DS4GD/blob/master/2018giga/CaseStudy.md#assignment-0

UniProtウェブサイトで“cold shock protein”を検索した結果です。
https://www.uniprot.org/uniprot/?query=Cold+Shock+Protein&sort=score

----------
## temperature
温度

最適増殖温度の異なる細菌（好熱菌・常温菌・低温菌）

https://github.com/haruosuz/mgsa/blob/master/references/README.memo.md#bacdive
https://twitter.com/BacDive/status/1095559495651115009
BacDive on Twitter: "Find here an interesting example how @BacDive data can be used to correlate microbial growth temperatues with temperature optima of enzymes: https://t.co/XWenohoc5W #biodiversity #bacteria #microbiology"
12:45 AM - 13 Feb 2019

ゲノム配列から最適増殖温度の予測
https://www.ncbi.nlm.nih.gov/pubmed/30689741
Bioinformatics. 2019 Sep 15;35(18):3224-3231. doi: 10.1093/bioinformatics/btz059.
Predicting the optimal growth temperatures of prokaryotes using only genome derived features.
Sauer DB1, Wang DN1.
https://academic.oup.com/bioinformatics/article-abstract/35/18/3224/5301315
The accuracy can be further improved for specific taxonomic clades or by excluding psychrophiles. 
https://github.com/DavidBSauer/OGT_prediction

https://www.ncbi.nlm.nih.gov/pubmed/28187704
BMC Genomics. 2017 Feb 10;18(1):151. doi: 10.1186/s12864-017-3543-7.
The nucleotide composition of microbial genomes indicates differential patterns of selection on core and accessory genomes.
Bohlin J1, Eldholm V2, Pettersson JH2, Brynildsrud O2, Snipen L3.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5303225/
Factors that show some association with genomic base composition in microbes include genome size [4–6], oxygen and nitrogen abundance [7, 8] as well as uptake of foreign DNA from conjugation, transformation and transduction [9–15]. Optimal growth temperature may influence genomic DNA composition and although this is a field of debate [16–19], there is some evidence for a role of growth temperature in shaping the GC content of individual genes [20] and ribosomal RNA [21]. 

https://www.ncbi.nlm.nih.gov/pubmed/23754727
Environ Microbiol Rep. 2013 Jun;5(3):468-74. doi: 10.1111/1758-2229.12035. Epub 2013 Feb 5.
Growth temperatures of archaeal communities can be estimated from the guanine-plus-cytosine contents of 16S rRNA gene fragments.
Kimura H1, Mori K, Yamanaka T, Ishibashi J.

微生物のライフスタイルとゲノムの特徴
https://www.ncbi.nlm.nih.gov/pubmed/23024607
Curr Genomics. 2012 Apr;13(2):153-62.
Microbial lifestyle and genome signatures.
Dutta C1, Paul S.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3308326/
i) Microorganisms Thriving at High Temperatures
Regression analyses of the sequence data for thermophilic, mesophilic (OGT = 20-50°C) and psychrophilic (OGT <20°C) bacteria revealed linear relationships between OGT and a combination of purine and pyrimidine dimer compositions, RR +YY – RY – YR, where R= A/G, Y = C/T), the correlation coefficient being 0.66 [144, 145]. 

最大増殖速度の予測
https://www.ncbi.nlm.nih.gov/pubmed/20090831
PLoS Genet. 2010 Jan 15;6(1):e1000808. doi: 10.1371/journal.pgen.1000808.
The systemic imprint of growth and its uses in ecological (meta)genomics.
Vieira-Silva S1, Rocha EP.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2797632/
Second, selection for these traits depends on optimal growth temperature: for similar generation times purifying selection is stronger in psychrophiles, intermediate in mesophiles, and lower in thermophiles. 

最適増殖温度と同義コドン使用
https://www.ncbi.nlm.nih.gov/pubmed/16989961
Gene. 2006 Dec 30;385:128-36. Epub 2006 Aug 22.
Synonymous codon usage and its potential link with optimal growth temperature in prokaryotes.
Lobry JR1, Necşulea A.
We report the unusual clustering of an Archaeal psychrophile with the thermophilic and hyperthermophilic species on the synonymous codon usage factorial map; the other psychrophiles in our study cluster with the mesophilic species. 

好熱菌と常温菌のコドン使用の違い
https://www.ncbi.nlm.nih.gov/pubmed/12364606
Nucleic Acids Res. 2002 Oct 1;30(19):4272-7.
Synonymous codon usage is subject to selection in thermophilic bacteria.
Lynn DJ1, Singer GA, Hickey DA.

https://www.ncbi.nlm.nih.gov/pubmed/20371310
Biophys J. 2010 Apr 7;98(7):1109-18. doi: 10.1016/j.bpj.2009.11.048.
Thermal adaptation of viruses and bacteria.
Chen P1, Shakhnovich EI.

原核生物の増殖温度データベース
https://www.ncbi.nlm.nih.gov/pubmed/14734322
Bioinformatics. 2004 Jan 22;20(2):276-8.
PGTdb: a database providing growth temperatures of prokaryotes.
Huang SL1, Wu LC, Liang HK, Pan KT, Horng JT, Ko MT.

2011
https://www.jstage.jst.go.jp/article/cookeryscience/44/1/44_88/_pdf
　また，細菌は発育温度域によって，表  に示したように，
低温性細菌（Psychrophiles），中温性細菌（Mesophiles）お
よび高温性細菌（Thermophiles）に分けられる。

mesophilic (中温が好適な温度環境である性質) 中温性の

- https://ja.wikipedia.org/wiki/好熱菌 thermophile
- https://ja.wikipedia.org/wiki/低温菌 psychrophile

----------
### psychrotolerant

https://www.sci.hokudai.ac.jp/bio/bio/耐冷性細菌（耐冷菌、低温菌）/
耐冷性細菌（耐冷菌、低温菌）
好冷菌と同様に０℃でも生育可能ですが20℃以上でも生育できる細菌を耐冷性細菌（耐冷菌、低温菌）と呼びます。好冷菌は恒常的に低温が保たれている環境（極域や深海など）でなければ生存できませんが、耐冷菌は常温域でも生育できるため、わたしたちの身近な環境にも見いだされます。

----------
### psychrophile
低温菌、好冷菌、寒冷生物

https://www.ncbi.nlm.nih.gov/pubmed/28515455
Sci Rep. 2017 May 17;7(1):2055. doi: 10.1038/s41598-017-02191-4.
Comparative genomic analysis reveals the environmental impacts on two Arcticibacter strains including sixteen Sphingobacteriaceae species.
Shen L1,2,3, Liu Y4,5, Xu B1,2, Wang N2,6, Zhao H1,2, Liu X1, Liu F7.
How the genomic diversity of species is driven by geographical isolation and environmental factors are not well understood for cold environments. 

https://www.ncbi.nlm.nih.gov/pubmed/26637477
FEMS Microbiol Ecol. 2016 Feb;92(2). pii: fiv154. doi: 10.1093/femsec/fiv154. Epub 2015 Dec 3.
Cold adaptive traits revealed by comparative genomic analysis of the eurypsychrophile Rhodococcus sp. JG3 isolated from high elevation McMurdo Dry Valley permafrost, Antarctica.
Goordial J1, Raymond-Bouchard I2, Zolotarov Y2, de Bethencourt L, Ronholm J2, Shapiro N3, Woyke T3, Stromvik M2, Greer CW4, Bakermans C5, Whyte L2.

https://www.ncbi.nlm.nih.gov/pubmed/24671034
EMBO Rep. 2014 May;15(5):508-17. doi: 10.1002/embr.201338170. Epub 2014 Mar 26.
Some like it cold: understanding the survival strategies of psychrophiles.
De Maayer P1, Anderson D, Cary C, Cowan DA.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4210084/
Reviews
総説
A keyword search for “psychrophile” against the GOLD database 17 shows that 83 complete or permanent draft psychrophile genomes have been sequenced, with another 102 genomes targeted or incomplete (Table ​(Table1).1). 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4210084/table/tbl1/
Table 1
Current status of genome sequencing of psychrophiles
好冷菌のゲノム配列解読状況

----------
## porphyrin
ポルフィリン

https://ja.wikipedia.org/wiki/ポルフィリン
ポルフィリンや類似化合物の金属錯体は、生体内でヘム、クロロフィル、シアノコバラミン（ビタミンB12）などとして存在

https://kotobank.jp/word/ポルフィリン-134697
- ポルフィンを基本骨格とし，周囲にある水素原子を他の原子もしくは原子団で置換して得られる化合物の総称。ポルフィリンの誘導体はヘモグロビン，チトクローム，クロロフィルなどの形で広く動植物中に存在する。
- ポルフィリンに鉄，銅，マグネシウムが結合した分子内錯塩は天然に存在し，生理的に重要なものが少なくない。例えばチトクロム，カタラーゼ，ヘモグロビンなどは鉄ポルフィリン誘導体のヘムやヘマチンを含有しており，植物の葉緑体にはマグネシウムポルフィリンとしてのクロロフィル(葉緑素)が含まれる。

![](https://kotobank.jp/image/dictionary/eiyo/f000005500.jpg)

![https://drug-net.jp/hemoglobin.html](https://drug-net.jp/femg.jpg)

https://ja.wikipedia.org/wiki/ヘム

チトクローム
https://ja.wikipedia.org/wiki/シトクロム
cytochrome）は、酸化還元機能を持つヘム鉄を含有する、ヘムタンパク質の一種である。

https://ja.wikipedia.org/wiki/クロロフィル
Chlorophyll) 
マグネシウム以外では、亜鉛が配位した例。金属がはずれ、2つの水素で置換された物質はフェオフィチンと呼ばれる。抽出されたクロロフィルでは、化学反応によって中心元素を人工的に置換することができる。特に銅が配位したものはマグネシウムのものよりも光や酸に対して安定であり、化粧品や食品への添加物として利用される[3]。

http://www.onsenmaru.com/topics/T-350/T-355-ikablood-N.htm
　では、ヘモシアニンとヘモグロビンとは何が違うのでしょうか。まず、基本成分の差から。
```
　　ヘモグロビン = ヘム （鉄イオン＋ポルフィリン）＋ タンパク質
　　ヘモシアニン = 銅イオン＋タンパク質
```

https://ja.wikipedia.org/wiki/ヘモシアニン
酸素の結合力は、ポルフィリン環内に鉄が配位されたヘモグロビンよりも弱い。

### hemoglobin
ヘモグロビン

https://ja.wikipedia.org/wiki/ヘモグロビン
ヘモグロビン分子全体(α2β2)の分子量は約64,500であり、ヘムを4つ含む。ヘムは価数が2価の鉄原子を中央に配位したポルフィリン誘導体である。このヘムの鉄原子に酸素が結合し、血液中を通って各組織へ運搬する。

https://github.com/haruosuz/ksbn/blob/master/2018/README.2018.4.md#5-7
図 1.グロビン，ミオグロビン，ヘモグロビンの系統樹

https://github.com/haruosuz/ksbn/blob/master/2018/README.2018.4.md#5-7
Keyword 遺伝子重複，ホモログ，パラログ，オーソログ，水平伝播
http://www.discoveryandinnovation.com/bioinformatics/glossary_detail/homolog.html
Glossary Detail - Homolog
![](http://www.discoveryandinnovation.com/bioinformatics/glossary_detail/images/orthologs.jpg)

2018/10/03
https://ultrabem-branch3.com/informatics/bioinformatics/homolog.html
ホモログ、オーソログ、パラログの定義と違い
- Homologous なタンパク質の例: ヘモグロビン、ミオグロビン、β-グロビンは全て共通祖先に由来する相同なタンパク質である。
- Paralogous なタンパク質の例: ヒトの α-グロビンと β-グロビンは互いにパラロガスである。
- Orthologous なタンパク質の例: ヒトのヘモグロビンは、マウスのヘモグロビンと互いにオーソロガスである。

Jan 9, 2018
https://www.slideshare.net/DDBJslide/allinone2016-85895385
[All-in-one2016] ゲノム配列と蛋白質立体構造の統合的検索とモデリング
アミノ酸配列の変化と立体構造の変化の相関(グロビン族） 立体構造の変化はアミノ酸配列の変化と相関 配列が３０％以上一致していれば、RMSDは２Å以下
![](https://image.slidesharecdn.com/kawabata-180109063341/95/allinone2016-6-638.jpg?cb=1515479718)

----------

## unclassified

https://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q143288254
ヘモグロビンはヘムというポルフィリンに鉄を持つ構造を中心とし、回りをたんぱく質に取り巻かれた構造になっています。このポルフィリンの中心にマグネシウムがあるのがクロロフィル（葉緑素）です。ポルフィリンの中心に銅がくるのはヘモシアニンです。蛸、イカ、貝などの薄紫色の血液はこれが原因です。他に動植物を問わず、広く存在するチトクロ－ムという呼吸を司る物質（電子を伝達する役割です）が、同じようにヘムの中心に鉄をもちます。生物に起源のごく初期に出現した物質です。今DNAばかりが注目されていますが、これらのポルフィリンを持つ構造など、他にも注目すべき物質は多数あります。

[Essential細胞生物学（原書第4版）](http://www.nankodo.co.jp/g/g9784524261994/)
- 14　ミトコンドリアと葉緑体でのエネルギー生産
p.467-468.: 
図14-24. ミトコンドリアの電子伝達系では、先に進むほど酸化還元電位が高くなる。
　さまざまな金属複合体の酸化還元電位は、その複合体が電子伝達系のどこで使われるかによる。鉄硫黄中心 iron-sulfur center は電子に対する親和性が比較的低いので、電子伝達系の前半で重要である。たとえば、NADH脱水素酵素複合体の鉄一硫黄中心は電子をユビキノンに渡す。伝達系の後半では、通常、シトクロムタンパクに強固に結合するヘム基の鉄原子が電子伝達に使われる (図 14-25)。このようなヘム基は、シトクロムc還元酵素やシトクロムc酸化酵素複合体のようなシトクロム cytochrome を色づける (シトクロムという名称は、ギリシャ語で“色”を意味する chroma による)。
図14-25. ヘム基中の鉄は電子受容体となる。
シトクロムc酸化酵素 cytochrome c oxidase は、呼吸鎖の最後にある電子運搬体で, 酸化還元電位は最も高い。このタンパク複合体はシトクロムcから電子を受け取ることでシトクロムを酸化するので、こう名づけられた。

----------

http://kagakubar.com/evolution/05.html
進化の歴史｜科学バー
第5話
偶然性の重視
◎ダーウィンの「自然選択説」
ダーウィンの「自然選択説」は、このようなデザイン論や目的論を否定する。彼は、集団中に偶然に生ずるたくさんの変異のなかからさまざまな環境によりよく適応した個体が生き残ることによって、進化が起るとした。多様な生物が進化する仕組みとして自然選択説を考えたのであった。目的論に頼らなくても、ランダムに起きる変異のなかからより適応した個体が選択されることによって、結果的に進化に方向性を与えられるのだ。無目的な偶然的な現象によって、生物の合目的性がもたらされるというこの考えは、画期的なものであった。

----------




----------
## 2019-03-02

Subject: 最先端科学プログラム：都市の微生物、感染症、腸と脳、心を操る微生物、皮膚・腸内細菌、beewolf

----------
https://github.com/haruosuz/metasub/blob/master/README.md
都市の微生物、世界中で採集　綿棒使い、街の環境考える参考に

https://github.com/haruosuz/metasub/blob/master/README.md#csd
MetaSUB国際コンソーシアムでは、都市建造環境（地下鉄、バスなどの公共交通システム）の微生物群集を調査するために、2019年6月21日 (金) Global City Sampling Day (CSD) に世界同時サンプリングを実施する予定です。

----------
http://www.nikkei-science.com/?tag=感染症
感染症 | 日経サイエンス

----------
https://www.kinokuniya.co.jp/f/dsg-01-9784314011570
腸と脳 
【ためし読みはこちらから】 https://www.kinokuniya.co.jp/banner/9784314011570.pdf

http://sciencebook.blog110.fc2.com/blog-entry-2222.html
『 ミニ特集：心の健康と腸内フローラ 』

https://www.microbe.net/2015/12/23/near-perfect-balance-in-a-microbiome-paper-hopeful-yet-no-hype-the-microbiome-of-the-built-environment-and-mental-health/
建造環境の微生物群集とメンタルヘルス 

----------
http://www.kawade.co.jp/np/isbn/9784309253527/
あなたの体は９割が細菌 :アランナ・コリン,矢野　真千子｜河出書房新社

https://diamond.jp/articles/-/131873
抗生物質を安易に使うと危険！人体の9割は細菌でできている | 要約の達人 from flier | ダイヤモンド・オンライン

https://diamond.jp/articles/-/131873?page=2
◆二一世紀の病気
◇人体は微生物生態系に満ちている
　人体のうち外界と接しているのは皮膚だけではない。消化管など私たちが体内だと思っている場所も「外側」であり、微生物の棲息地となっている。中でもその多くを抱えているのは腸であり、腸の中には常に肝臓と同じ重量に相当する1.5キロの細菌がいるという。

https://diamond.jp/articles/-/131873?page=3
◆あらゆる病気は腸からはじまる
◇カロリー計算で体重コントロールはできない

◇心を操る微生物
自閉症だけでなく、統合失調症などと診断される病気も腸内細菌の組成比が影響しているという研究結果が出たのはごく最近のことだ。

◇抗生物質が微生物集団の構成を変える

https://diamond.jp/articles/-/131873?page=4
◇産道にいる微生物
先進国ではお産の三割程度が帝王切開で行われるが、帝王切開で生まれた子は感染症やアレルギー、さらには自閉症や肥満になりやすいというデータもある。

◇母乳の中にいる微生物
粉ミルクで育つ赤ん坊は感染症にかかりやすい。乳幼児突然死症候群で死亡するリスクも二倍だ。そして、皮膚炎や喘息、過体重にもなりやすい。

https://diamond.jp/articles/-/131873?page=5
◇他人の糞便を分けてもらう

https://www.ted.com/talks/rob_knight_how_our_microbes_make_us_who_we_are/transcript?language=ja#t-445571
ロブ・ナイト: 微生物がどのようにして私達を作っているのか | TED Talk
普通分娩で産まれた赤ちゃんは 基本的に母親の膣内微生物叢を持ち 一方 帝王切開で産まれた赤ちゃんの 微生物は全て皮膚常在菌となります 帝王切開で産まれた人は 微生物との関わりがある 嘆息 アレルギーそして肥満さえも 普通分娩の人より罹り易く 出産と健康との関係が 考えられています 

https://www.pbs.org/video/microbes-from-mom-vaginal-birth-vs-c-section-mf6ctd/
Microbes from Mom — Vaginal Birth vs C-Section | Season 1 Episode 10 | I Contain Multitudes | PBS
https://www.youtube.com/watch?v=YB0WDp-Stys
Microbes from Mom — Vaginal Birth vs C-Section - YouTube

----------
http://www.kashiwashobo.co.jp/book/b286870.html
世界は細菌にあふれ、人は細菌によって生かされる
I Contain Multitudes: The Microbes Within Us and a Grander View of Life 
Ed Yong  (著)

https://www.pbs.org/video/a-wasp-moms-gift-blankets-of-bacteria-wudslq/
A Wasp Mom’s Gift: Blankets of Bacteria | Season 1 Episode 5 | I Contain Multitudes | PBS
https://www.youtube.com/watch?v=2vf0SilBNRQ
A Wasp Mom’s Gift: Blankets of Bacteria | I Contain Multitudes - YouTube

http://news.line.me/issue/oa-natgeomagjp/06e5cc327597
卵みずから毒ガス放ち巣を守る、寄生バチで発見 (ナショナル ジオグラフィック日本版) - LINEアカウントメディア
https://natgeo.nikkeibp.co.jp/atcl/news/19/020700091/
卵みずから毒ガス放ち巣を守る、ハチで発見 | ナショナルジオグラフィック日本版サイト
https://www.biorxiv.org/content/10.1101/495085v2
Nitric oxide radicals are emitted by wasp eggs to kill mold fungi | bioRxiv

----------






