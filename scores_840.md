
This file summarizes the running time averages to solve the planted problems with Ids <ids> given temperatures <temperatures> and with 588 sub graphs.

## Ids
ids = xrange(0, 500, 50)

## Temperatures and results

# Run on AWS GPU instance
temps = [
        # The best temperatures are:  [2, 1, 0.5]
        [2, 1, .5],  # Entry:  0 , average:  13.3117861748
        [2, 1, .75, .5],  # Entry:  1 , average:  20.2947582483
        [3, 2, 1, .5],  # Entry:  2 , average:  17.4434875727
        [3, 2.5, 2, 1, .5],  # Entry:  3 , average:  19.547585392
        [2, 1.5, 1, .5],  # Entry:  4 , average:  20.8302713871
        [3, 2, 1.5, 1, .5],  # Entry:  5 , average:  19.3308734655
        [4, 3, 2, 1.5, 1, .5],  # Entry:  6 , average:  14.8875025034
        [5, 4, 3, 2, 1.5, 1, .5],  # Entry:  7 , average:  27.8071509838
        [3.2, 2.7, 2, 1.5, 1, .5],  # Entry:  8 , average:  20.2458056211
        drange(.5, 3, .1)[::-1],  # Entry:  9 , average:  60.7998099327
        drange(.5, 3, .2)[::-1],  # Entry:  10 , average:  38.2872646093
        drange(.5, 3, .25)[::-1],  # Entry:  11 , average:  38.3439232111
        drange(.5, 3, .33)[::-1],  # Entry:  12 , average:  44.2030246019
        drange(.5, 3, .4)[::-1],  # Entry:  13 , average:  17.6037395954
        drange(.5, 3, .5)[::-1],  # Entry:  14 , average:  30.0171941996
        drange(.5, 4, .1)[::-1],  # Entry:  15 , average:  114.104996014
        drange(.5, 4, .2)[::-1],  # Entry:  16 , average:  41.3118901491
        drange(.5, 4, .25)[::-1],  # Entry:  17 , average:  32.4862995148
        drange(.5, 4, .33)[::-1],  # Entry:  18 , average:  33.488809824
        drange(.5, 4, .4)[::-1],  # Entry:  19 , average:  27.7889359951
        drange(.5, 4, .5)[::-1],  # Entry:  20 , average:  25.9325739861
        drange(.5, 5, .1)[::-1],  # Entry:  21 , average:  141.376545811
        drange(.5, 5, .2)[::-1],  # Entry:  22 , average:  55.319022584
        drange(.5, 5, .25)[::-1],  # Entry:  23 , average:  52.4933824778
        drange(.5, 5, .33)[::-1],  # Entry:  24 , average:  52.3246892691
        drange(.5, 5, .4)[::-1],  # Entry:  25 , average:  38.026649189
        drange(.5, 5, .5)[::-1],  # Entry:  26 , average:  31.1827017784
        drange(.5, 6, .1)[::-1],  # Entry:  27 , average:  103.698758221
        drange(.5, 6, .2)[::-1],  # Entry:  28 , average:  106.287009883
        drange(.5, 6, .25)[::-1],  # Entry:  29 , average:  48.9025055885
        drange(.5, 6, .33)[::-1],  # Entry:  30 , average:  47.3761648655
        drange(.5, 6, .4)[::-1],  # Entry:  31 , average:  40.2947982788
        drange(.5, 6, .5)[::-1],  # Entry:  32 , average:  29.0548914194
        drange(.5, 7, .1)[::-1],  # Entry:  33 , average:  110.649698639
        drange(.5, 7, .2)[::-1],  # Entry:  34 , average:  78.7636207342
        drange(.5, 7, .25)[::-1],  # Entry:  35 , average:  45.1702190161
        drange(.5, 7, .33)[::-1],  # Entry:  36 , average:  65.0479057312
        drange(.5, 7, .4)[::-1],  # Entry:  37 , average:  28.2847656965
        drange(.5, 7, .5)[::-1],  # Entry:  38 , average:  26.6654751301
    ]





# AWS Again, all with drandge:

Temps:
 temps = [
        [2, 1, .5],
        [2, 1, .75, .5],
        [3, 2, 1, .5],
        [3, 2.5, 2, 1, .5],
        [2, 1.5, 1, .5],
        [3, 2, 1.5, 1, .5],
        [4, 3, 2, 1.5, 1, .5],
        [5, 4, 3, 2, 1.5, 1, .5],
        [3.2, 2.7, 2, 1.5, 1, .5],
        drandge(.5, 1.5, .1)[::-1],
        drandge(.5, 1.5, .2)[::-1],
        drandge(.5, 1.5, .25)[::-1],
        drandge(.5, 1.5, .33)[::-1],
        drandge(.5, 1.5, .4)[::-1],
        drandge(.5, 1.5, .5)[::-1],
        drandge(.5, 2, .1)[::-1],
        drandge(.5, 2, .2)[::-1],
        drandge(.5, 2, .25)[::-1],
        drandge(.5, 2, .33)[::-1],
        drandge(.5, 2, .4)[::-1],
        drandge(.5, 2, .5)[::-1],
        drandge(.5, 2.5, .1)[::-1],
        drandge(.5, 2.5, .2)[::-1],
        drandge(.5, 2.5, .25)[::-1],
        drandge(.5, 2.5, .33)[::-1],
        drandge(.5, 2.5, .4)[::-1],
        drandge(.5, 2.5, .5)[::-1],
        drandge(.5, 3, .1)[::-1],
        drandge(.5, 3, .2)[::-1],
        drandge(.5, 3, .25)[::-1],
        drandge(.5, 3, .33)[::-1],
        drandge(.5, 3, .4)[::-1],
        drandge(.5, 3, .5)[::-1],
        drandge(.5, 3.5, .1)[::-1],
        drandge(.5, 3.5, .2)[::-1],
        drandge(.5, 3.5, .25)[::-1],
        drandge(.5, 3.5, .33)[::-1],
        drandge(.5, 3.5, .4)[::-1],
        drandge(.5, 3.5, .5)[::-1],
    ]


Scores:

----------------------------------------
Entry:  [2, 1, 0.5] , average:  17.813770092

Entry:  [2, 1, 0.75, 0.5] , average:  23.3223579888

Entry:  [3, 2, 1, 0.5] , average:  19.0279186249

Entry:  [3, 2.5, 2, 1, 0.5] , average:  22.7256708536

Entry:  [2, 1.5, 1, 0.5] , average:  23.5387159848

Entry:  [3, 2, 1.5, 1, 0.5] , average:  23.7401738019

Entry:  [4, 3, 2, 1.5, 1, 0.5] , average:  23.7525321927

Entry:  [5, 4, 3, 2, 1.5, 1, 0.5] , average:  25.7166982803

Entry:  [3.2, 2.7, 2, 1.5, 1, 0.5] , average:  25.4196040907

Entry:  [1.4643451222424, 0.8999999999999999, 0.7999999999999999, 0.7, 0.6, 0.5] , average:  4
0.4220024829

Entry:  [1.0750401173775104, 1.0532721859641623, 0.8532721859641623, 0.6532721859641624, 0.5] 
, average:  37.1828566494

Entry:  [0.9919532433369712, 0.5] , average:  15.0913146205

Entry:  [1.2215744116438836, 0.5] , average:  14.1556271625

Entry:  [1.463873882936399, 1.0638738829363992, 0.5] , average:  19.8002281394

Entry:  [1.0645717705336415, 0.9007667259723099, 0.5] , average:  22.3613868961

Entry:  [1.9592242123831987, 1.650018191277749, 1.3945204524338983, 1.26781207476921, 0.788275
28846599, 0.716608284002114, 0.5551309783117171, 0.5098830819744531, 0.5] , average:  52.59805
3268

Entry:  [1.66521038248314, 1.46521038248314, 1.1408470860861664, 0.5] , average:  25.154272587
8

Entry:  [1.627725734120549, 1.128825472447228, 1.0, 0.75, 0.5] , average:  33.2624761252

Entry:  [1.7355262554350022, 0.9405121557339224, 0.5] , average:  18.9711719179

Entry:  [1.4409294075920775, 1.0409294075920776, 0.7493370554375539, 0.5] , average:  26.68538
18631

Entry:  [1.1367238311484429, 1.0767169794886446, 0.5] , average:  20.9984695692

Entry:  [2.404439734001205, 2.120761109979266, 2.020761109979266, 1.46157857430766, 1.36157857
43076598, 1.005196076776726, 0.5] , average:  35.8781502514

Entry:  [2.3898329168534573, 2.189832916853457, 1.5295729378879663, 0.9025911140708975, 0.5] ,
 average:  25.6325553827

Entry:  [2.288825147212053, 2.172454538868742, 1.9039262323998911, 1.6572459631942187, 1.16547
9648811118, 1.065218010385137, 0.5] , average:  35.0630066004

Entry:  [2.2175406849309787, 1.865487270674661, 1.7687079114312205, 1.363962627320078, 1.08811
04545097418, 0.5] , average:  32.541108438

Entry:  [2.3404049068601944, 1.940434235645193, 1.5404342356451928, 0.899708543605269, 0.5] , 
average:  26.9105753436

Entry:  [2.3987061054285115, 2.0918896646233245, 1.8558542845356916, 1.5483130713629352, 1.3226792146258772, 0.5982961315306171, 0.5] , average:  34.6203585858

Entry:  [2.896902375555568, 2.7969023755555678, 2.4740428522561184, 2.3740428522561183, 2.3293396450862787, 1.7595271904936196, 1.4330280208059325, 1.3171663435378118, 1.2439971960878546, 0.7757583549633615, 0.5] , average:  46.0366396933

Entry:  [2.8494602972136907, 2.6494602972136905, 2.1898616962675326, 1.717837196996872, 1.2999999999999998, 1.0999999999999999, 0.8999999999999999, 0.7, 0.5] , average:  39.2808282175

Entry:  [2.75742377597702, 2.2136056878254164, 1.545870616696976, 1.295870616696976, 0.95966245946934, 0.8616660942359057, 0.75, 0.5] , average:  34.1783152857

Entry:  [2.9944650408504163, 2.6971348001112734, 2.180871035115891, 1.976922419616829, 1.4592877020437163, 0.8300000000000001, 0.5] , average:  29.4450768986

Entry:  [2.7124618900808173, 2.4199227879758283, 2.031627925380983, 1.5029719702053734, 1.153831050099516, 0.9276927300131954, 0.5] , average:  27.4894392767

Entry:  [2.263702830340598, 1.6731961574000216, 1.3788361482386207, 0.5] , average:  21.6545889587

Entry:  [3.4437095532681683, 2.9935168145836646, 2.7081154925470923, 2.1112021518851467, 1.56364912143735, 1.0684482601885652, 0.9684482601885652, 0.5] , average:  28.1135463099

Entry:  [3.054949171846888, 2.722300956823709, 2.5223009568237087, 1.9492511002066908, 1.7935968561246205, 1.5935968561246205, 1.3935968561246206, 0.9760397107047347, 0.5921708610153731, 0.5] , average:  39.3418834286

Entry:  [3.3262469309680243, 3.2371052902249, 2.9871052902249, 2.871275637527963, 2.353253537803863, 1.940980853936915, 1.391535110129727, 1.1782385675785971, 0.9282385675785971, 0.5] , average:  26.980692327

Entry:  [3.4969701044648627, 3.1669701044648626, 2.533199056295934, 2.5000864899679214, 2.470548488749065, 2.3344941278126465, 1.9113148620626508, 1.09408743875525, 1.0235373253600328, 0.5] , average:  37.2718138094

Entry:  [2.8330985558081774, 1.9821164694375564, 1.8684562115784757, 1.5628901740237113, 1.310620313072285, 0.5] , average:  17.834696826

Entry:  [3.018467786088808, 2.5954396458677516, 2.218224541924909, 1.6344894413789637, 0.6925850251500808, 0.5] , average:  26.0772488513

----------------------------------------
The best temperatures are:  [1.2215744116438836, 0.5]  with a time of:  14.1556271625