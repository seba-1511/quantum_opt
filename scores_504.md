
This file summarizes the running time averages to solve the planted problems with Ids <ids> given temperatures <temperatures> and with 504 sub graphs.

## Ids
ids = xrange(0, 500, 50)

## Temperatures and results

# Run on AWS GPU instance
    temps = [
        # The best temperatures are:  [2, 1.5, 1, 0.5]
        [2, 1, .5],  # Entry:  0 , average:  6.08006167412
        [2, 1, .75, .5],  # Entry:  1 , average:  8.63446967602
        [3, 2, 1, .5],  # Entry:  2 , average:  4.28594341278
        [3, 2.5, 2, 1, .5],  # Entry:  3 , average:  11.2874209881
        [2, 1.5, 1, .5],  # Entry:  4 , average:  4.02567346096
        [3, 2, 1.5, 1, .5],  # Entry:  5 , average:  9.17227263451
        [4, 3, 2, 1.5, 1, .5],  # Entry:  6 , average:  12.9710660934
        [5, 4, 3, 2, 1.5, 1, .5],  # Entry:  7 , average:  13.4417264223
        [3.2, 2.7, 2, 1.5, 1, .5],  # Entry:  8 , average:  8.59763152599
        drange(.5, 3, .1)[::-1],  # Entry:  9 , average:  27.6531776667
        drange(.5, 3, .2)[::-1],  # Entry:  10 , average:  13.9443939447
        drange(.5, 3, .25)[::-1],  # Entry:  11 , average:  11.0896609068
        drange(.5, 3, .33)[::-1],  # Entry:  12 , average:  9.04447655678
        drange(.5, 3, .4)[::-1],  # Entry:  13 , average:  6.93130748272
        drange(.5, 3, .5)[::-1],  # Entry:  14 , average:  7.57686486244
        drange(.5, 4, .1)[::-1],  # Entry:  15 , average:  65.001205349
        drange(.5, 4, .2)[::-1],  # Entry:  16 , average:  30.0953076363
        drange(.5, 4, .25)[::-1],  # Entry:  17 , average:  24.6656080961
        drange(.5, 4, .33)[::-1],  # Entry:  18 , average:  15.3797037125
        drange(.5, 4, .4)[::-1],  # Entry:  19 , average:  17.6162266016
        drange(.5, 4, .5)[::-1],  # Entry:  20 , average:  14.4120716572
        drange(.5, 5, .1)[::-1],  # Entry:  21 , average:  123.004396343
        drange(.5, 5, .2)[::-1],  # Entry:  22 , average:  57.3280613661
        drange(.5, 5, .25)[::-1],  # Entry:  23 , average:  31.6118182182
        drange(.5, 5, .33)[::-1],  # Entry:  24 , average:  27.4091967344
        drange(.5, 5, .4)[::-1],  # Entry:  25 , average:  35.4817849874
        drange(.5, 5, .5)[::-1],  # Entry:  26 , average:  15.3356433153
        drange(.5, 6, .1)[::-1],  # Entry:  27 , average:  145.142740059
        drange(.5, 6, .2)[::-1],  # Entry:  28 , average:  71.5834856749
        drange(.5, 6, .25)[::-1],  # Entry:  29 , average:  72.0808825254
        drange(.5, 6, .33)[::-1],  # Entry:  30 , average:  47.0284476519
        drange(.5, 6, .4)[::-1],  # Entry:  31 , average:  25.6613370895
        drange(.5, 6, .5)[::-1],  # Entry:  32 , average:  38.1279673338
        drange(.5, 7, .1)[::-1],  # Entry:  33 , average:  148.960394168
        drange(.5, 7, .2)[::-1],  # Entry:  34 , average:  103.458539939
        drange(.5, 7, .25)[::-1],  # Entry:  35 , average:  44.2248064995
        drange(.5, 7, .33)[::-1],  # Entry:  36 , average:  49.2534312963
        drange(.5, 7, .4)[::-1],  # Entry:  37 , average:  36.1861743927
        drange(.5, 7, .5)[::-1],  # Entry:  38 , average:  36.309117794
    ]

# on laptop:

The best temperatures are:  [0.8300000000000001, 0.5]
        drange(.5, 1, .1)[::-1],  # Entry:  0 , average:  13.6762528896
        drange(.5, 1, .2)[::-1],  # Entry:  1 , average:  7.38200819492
        drange(.5, 1, .25)[::-1],  # Entry:  2 , average:  6.97562570572
        drange(.5, 1, .33)[::-1],  # Entry:  3 , average:  2.65786590576
        drange(.5, 1, .4)[::-1],  # Entry:  4 , average:  3.35053946972
        drange(.5, 1, .5)[::-1],  # Entry:  5 , average:  4.23577251434

The best temperatures are:  [2.0, 1.5, 1.0, 0.5]
        drange(.5, 2.5, .1)[::-1],  # Entry:  0 , average:  19.6650770664
        drange(.5, 2.5, .2)[::-1],  # Entry:  1 , average:  26.4916772127
        drange(.5, 2.5, .25)[::-1],  # Entry:  2 , average:  10.1017335892
        drange(.5, 2.5, .33)[::-1],  # Entry:  3 , average:  9.68981463909
        drange(.5, 2.5, .4)[::-1],  # Entry:  4 , average:  6.91152791977
        drange(.5, 2.5, .5)[::-1],  # Entry:  5 , average:  4.79928133488


The best temperatures are:  [3.0, 2.5, 2.0, 1.5, 1.0, 0.5]

        drange(.5, 3.5, .1)[::-1],  # Entry:  0 , average:  51.7976029158
        drange(.5, 3.5, .2)[::-1],  # Entry:  1 , average:  26.7826597929
        drange(.5, 3.5, .25)[::-1],  # Entry:  2 , average:  18.5598556995
        drange(.5, 3.5, .33)[::-1],  # Entry:  3 , average:  19.8484629154
        drange(.5, 3.5, .4)[::-1],  # Entry:  4 , average:  9.07285785675
        drange(.5, 3.5, .5)[::-1],  # Entry:  5 , average:  7.03486213684

----------------------------------------
    Entry:  [1.295363513556973, 1.1370910490717816, 0.8663611333891299, 0.5540298758899966, 0.5722564984221442, 0.34044045940064804, 0.46207699073072417, 0.5] , average:  12.9802982569

    Entry:  [1.320928970865951, 0.6464033979012733, 0.5] , average:  5.0402053833

    Entry:  [1.190408675138777, 0.5212825860704385, 0.5] , average:  7.66624901295

    Entry:  [0.9496075153850372, 0.5] , average:  2.49613871574

    Entry:  [1.349648799428517, 0.5] , average:  3.53614706993

    Entry:  [1.0861097808033815, 0.9816004629738976, 0.5] , average:  5.49470305443

----------------------------------------
The best temperatures are:  [0.9496075153850372, 0.5]  with a time of:  2.49613871574

----------------------------------------
    Entry:  [2.0276005075246775, 2.211985156635013, 1.6634060657808556, 1.138649684619786, 0.8959315203312589, 0.8235613706441828, 0.5792159378614099, 0.4631919021773707, 0.49552895547656406, 0.309839358344611, 0.04255521695512959, 0.21417309178784674, 0.13982187039094762, 0.5] , average:  23.7077642202

    Entry:  [2.4854589913853538, 2.4696732290416414, 2.172364824502271, 1.8087089534446552, 1.7506638638040488, 1.879174253342487, 1.8232191860721068, 1.2163331217753148, 1.3418206280962333, 1.3649871938843956, 1.069902785898595, 1.2533740006459606, 0.8206965702728533, 1.0519345140364909, 0.4314453423492728, -0.1834889204644239, -0.15697871509291667, 0.05897455026037879, 0.20654878069351118, 0.5] , average:  19.2770659447

    Entry:  [2.35496665560745, 2.051529634891325, 1.7644633569263393, 1.7673504909042899, 1.457282852881696, 1.0565884675391666, 1.0461922107895374, 0.5] , average:  18.0210843086

    Entry:  [2.2053395286477993, 1.7798164085817205, 1.70323290616255, 1.6310465370131118, 1.7153314491140912, 1.6669308967120338, 1.7333199210609567, 1.4737173167182216, 1.049100139323602, 0.7193713225454839, 0.70305548703017, 0.5] , average:  16.3994230747

    Entry:  [2.0917013379087144, 2.119672277674339, 2.005984438965533, 2.100876061651771, 1.222727577123759, 1.045760363276802, 1.07003582977524, 0.5] , average:  10.271694994

    Entry:  [2.331460656800809, 1.6764963013673113, 1.5529606453697662, 1.2645064549041383, 1.2588720462937741, 0.5] , average:  6.22562360764

----------------------------------------
The best temperatures are:  [2.331460656800809, 1.6764963013673113, 1.5529606453697662, 1.2645064549041383, 1.2588720462937741, 0.5]  with a time of:  6.22562360764

----------------------------------------
    Entry:  [2.1208553056309203, 1.5988291164057606, 1.0082612201044343, 0.5] , average:  6.78659632206

    Entry:  [1.9214394860219357, 1.2501656181089118, 1.0501656181089118, 0.8501656181089119, 0.5] , average:  3.64330825806

    Entry:  [1.9808527719628413, 1.4076337677878326, 0.847285514658148, 0.5288766222906417, 0.5] , average:  7.42890737057

    Entry:  [2.352827617767742, 2.082036908851122, 1.727608942518862, 1.4651891278790348, 1.1262481848229544, 1.0202459623302733, 0.5] , average:  6.48322291374

    Entry:  [1.8082433087049412, 1.456274345065959, 1.239504687279859, 0.5] , average:  5.85254929066

    Entry:  [2.440472586464009, 2.3704616419168376, 2.0542753311351065, 1.7402195371881821, 1.2797846738375287, 0.8982478231752415, 0.5] , average:  10.5449937344

----------------------------------------
The best temperatures are:  [1.9214394860219357, 1.2501656181089118, 1.0501656181089118, 0.8501656181089119, 0.5]  with a time of:  3.64330825806

----------------------------------------
    Entry:  [2.3539785917272127, 1.9551284571407586, 1.8551284571407585, 1.805175499196448, 1.548675932266142, 1.448675932266142, 1.251457004221363, 1.151457004221363, 0.6, 0.5] , average:  15.2437860966

    Entry:  [2.0975924588179273, 1.8975924588179272, 1.8098601302630044, 1.8071076186940433, 1.6071076186940434, 0.9157175132315807, 0.7157175132315807, 0.5157175132315808, 0.5] , average:  12.9133517742

    Entry:  [2.3196210324767335, 2.0696210324767335, 1.7450040156192939, 1.4950040156192939, 1.0311119814408058, 0.8070111347701647, 0.5570111347701647, 0.5] , average:  6.81295905113

    Entry:  [2.199689140476156, 1.4626593058257742, 1.435775211876574, 1.2835871184611907, 0.8710813386481184, 0.5] , average:  10.407371521

    Entry:  [1.9977241675220836, 1.9092580588152872, 1.5092580588152873, 0.9, 0.5] , average:  6.69869623184

    Entry:  [2.185482922855813, 1.8606626895613854, 1.054461323874637, 0.5] , average:  6.90046658516

----------------------------------------
The best temperatures are:  [1.9977241675220836, 1.9092580588152872, 1.5092580588152873, 0.9, 0.5]  with a time of:  6.69869623184

----------------------------------------
    Entry:  [2.1487352764062813, 1.8987352764062815, 1.1781770553720512, 0.5] , average:  6.69794201851

    Entry:  [1.9992182011811201, 1.9598983730591766, 1.6298983730591765, 1.2998983730591764, 0.9698983730591764, 0.5] , average:  5.36291782856

    Entry:  [2.4365186743775302, 2.0365186743775303, 1.5951257727226937, 1.3123451441105807, 0.5] , average:  8.33879504204

    Entry:  [1.6573806247705425, 0.898183979536579, 0.5] , average:  2.24856796265

    Entry:  [1.9214394860219357, 1.2501656181089118, 1.0501656181089118, 0.8501656181089119, 0.5] , average:  3.80998680592

----------------------------------------
The best temperatures are:  [1.6573806247705425, 0.898183979536579, 0.5]  with a time of:  2.24856796265

----------------------------------------
    Entry:  [1.4510053679020292, 1.0841668362338357, 0.8389158789441735, 0.7, 0.6, 0.5] , average:  10.1099694252

    Entry:  [1.4096212751223247, 1.2841600067345793, 1.0841600067345794, 0.5] , average:  7.16514053345

    Entry:  [0.7709911544615956, 0.75, 0.5] , average:  6.0714140892

    Entry:  [0.8650262775974622, 0.5] , average:  5.77611205578

    Entry:  [1.3240989549974809, 0.5] , average:  4.3561093092

    Entry:  [1.414563718671825, 0.5] , average:  2.58305370808

----------------------------------------
The best temperatures are:  [1.414563718671825, 0.5]  with a time of:  2.58305370808
----------------------------------------
    Entry:  [1.1350046093740767, 0.7499260187685062, 0.5] , average:  4.85098209381

    Entry:  [1.0656847051278784, 0.7, 0.5] , average:  9.92133233547

    Entry:  [1.1672379556658412, 0.5255032053470213, 0.5] , average:  3.17225000858

    Entry:  [1.1461379710081256, 0.5] , average:  1.98943941593

    Entry:  [1.1697712885848572, 0.834443131350537, 0.5] , average:  4.91527647972

    Entry:  [0.5] , average:  3.99849221706

----------------------------------------
The best temperatures are:  [1.1461379710081256, 0.5]  with a time of:  1.98943941593