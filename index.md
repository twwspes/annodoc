---
layout: entry
title: Annodoc annotation documentation support system
---

~~~ conllu
1	妙	EMC=mjiawʰ_LMC=mjiaẁ_OM=mjɛẁ_Pinyin=miào	JJ	ADJ	_	2	amod	_	wonderful;_Sanskrit=sad-;_Tangut=thjo̱_(XHZD3228)
2	法	EMC=puap_LMC=fjyap/faːp_OM=fǎ_Pinyin=fǎ	NN	NOUN	_	4	nn	_	law;_Sanskrit=dharma-;_Tangut=tsji̱r_(XHZD467)
3	蓮華	EMC=lɛn_ɣwaɨ/ɣwɛː_LMC=lian_xɦwaː_OM=ljɛń_xwá_Pinyin=lián_huá	NN	NOUN	_	4	nn	_	white_lotus;_Sanskrit=puṇḍarīka-;_Tangut=wjạ_sej_(XHZD2467_XHZD4751)
4	經	EMC=kɛjŋ_LMC=kjiajŋ_OM=kiŋ_Pinyin=jīng	NN	NOUN	_	8	nn	_	sutra;_Sanskrit=sūtram;_Tangut=lwər_rejr_[lhejr]_(XHZD437_XHZD4343)
5	觀世音	EMC=kwan_ɕiajʰ_ʔim_LMC=kuan_ʂiaj̀_ʔim_OM=kɔn_ʂì_jim_Pinyin=guān_shì_yīn	NR	PROPN	_	6	nn	_	avalokiteśvaraTangut=rjur_ɣiẹ_bio̱_(XHZD4713_XHZD1586_XHZD5593)
6	菩薩	EMC=bɔ_sat_LMC=pfiuə̆_sat_OM=pʰú_sǎ_Pinyin=pú_sà	NN	NOUN	_	8	nn	_	bodhisattvaTangut=tshjɨ_[ɲia]_tsjij_(XHZD5906_XHZD3574)
7	普門	EMC=pʰɔʼ_mən_LMC=pʰuə̆́_mun_OM=pʰǔ_mun_Pinyin=pǔ_mén	NR	PROPN	_	8	nn	_	the_universal_gateway;_Sanskrit=samanta-mukha-;_Tangut=njɨ_ɣa_(XHZD2679_XHZD5689)
8	品	EMC=pʰimʼ_LMC=pʰiḿ_OM=pʰiň_Pinyin=pǐn	NR	PROPN	_	0	root	_	Chapter;_Sanskrit=parivartaḥ;_Tangut=tjij_(XHZD1355)
9	第二十五	EMC=dɛjʰ_ɲiʰ_dʑip_ŋɔʼ_LMC=tɦiaj̀_rì_ʂɦip_ŋuə̆́_OM=tì_rr̩̀_ʂí_ǔ_Pinyin=dì_èr_shí_wǔ	OD	NUM	_	8	ordmod	_	the_25th;_Sanskrit=24
10	。	_	PU	PUNCT	_	8	punct	_	_

~~~

~~~ conllu
1	sad-	sat	NC.JJ..cpd	NOUN	_	2	ATR	_	real;_妙;_དམ་པ;_dam_pa
2	dharma-	dharma	NC.mas..cpd	NOUN	_	4	ATR	_	Buddhist_dharma;_法;_ཆོས་;_chos
3	puṇḍarīka-	puṇḍarīka	NC.mas..cpd	NOUN	_	4	ATR	_	white_lotus;_蓮華;_པདྨ་དཀར་པོ;_pad+ma_dkar_po
4	sūtram	sūtra	NC.neu.sg.nom.i	NOUN	_	0	PRED	_	sacred_thread_or_cord;_經;_;
5	|	|	PU	PUNCT	_	4	AuxK	_	_
6	24	24	JQ.mas.sg.nom.i.ord.n.n	ADJ	_	9	ATR	_	24;_第二十五;_;
7	samanta-	samanta	JQ...cpd.card.n.n	ADJ	_	9	ATR	_	all;_普門;_;
8	mukha-	mukha	NC.neu..cpd	NOUN	_	9	ATR	_	door;_approach;_普門;_;
9	parivartaḥ	parivarta	NC.mas.sg.loc.vii	NOUN	_	0	PRED	_	section;_品;_;
10	||	||	PU	PUNCT	_	9	AuxK	_	_

~~~

~~~ conllu
1	།།	//	PUNCT	PUNCT	_	10	punct	_	_
2	དམ་པ	dam_pa	ADJ	ADJ	_	4	amod	_	excellent|Sanskrit=sad-
3	འི་	'i	ADP	ADP	_	2	case	_	genitive_particle
4	ཆོས་	chos	NOUN	NOUN	_	7	nmod	_	teaching_doctrine;_dharma|Sanskrit=dharma-
5	པདྨ་དཀར་པོ	pad+ma_dkar_po	NOUN	NOUN	_	7	nmod	_	"White_Lotus,_PuNDarIka|Sanskrit=puṇḍarīka-"
6	།	/	PUNCT	PUNCT	_	5	punct	_	|
7	བམ་པོ་	bam_po	NOUN	NOUN	_	10	nmod	_	section
8	བཅུ་གསུམ་པ་	bcu_gsum_pa	ADJ.NumType=Ord	ADJ	NumType=Ord	7	nummod	_	13th
9	སྟེ་	ste	ADP	ADP	_	7	case	_	continuative_or_participial_particle
10	ཐ་མ	tha_ma	NOUN	NOUN	_	0	root	_	"last,_(Sanskrit)_carama"
11	།	/	PUNCT	PUNCT	_	10	punct	_	||

~~~