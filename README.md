# panConusig
Package for analysis of pan-cancer copy number signatures

Dependencies: GenomicRanges, parallel, pbmcapply, stringr

## For matrix generation: getMatrix()

## For simulation of CN profiles: generateProfile(0:homdel:0-100kb	0
0:homdel:100kb-1Mb	0.0149253731343284
0:homdel:>1Mb	0.00746268656716418
1:LOH:0-100kb	0.0298507462686567
1:LOH:100kb-1Mb	0.0597014925373134
1:LOH:1Mb-10Mb	0.208955223880597
1:LOH:10Mb-40Mb	0.0671641791044776
1:LOH:>40Mb	0.0522388059701493
2:LOH:0-100kb	0
2:LOH:100kb-1Mb	0
2:LOH:1Mb-10Mb	0.00746268656716418
2:LOH:10Mb-40Mb	0.00746268656716418
2:LOH:>40Mb	0
3-4:LOH:0-100kb	0
3-4:LOH:100kb-1Mb	0
3-4:LOH:1Mb-10Mb	0
3-4:LOH:10Mb-40Mb	0
3-4:LOH:>40Mb	0
5-8:LOH:0-100kb	0
5-8:LOH:100kb-1Mb	0
5-8:LOH:1Mb-10Mb	0
5-8:LOH:10Mb-40Mb	0
5-8:LOH:>40Mb	0
9+:LOH:0-100kb	0
9+:LOH:100kb-1Mb	0
9+:LOH:1Mb-10Mb	0
9+:LOH:10Mb-40Mb	0
9+:LOH:>40Mb	0
2:het:0-100kb	0
2:het:100kb-1Mb	0
2:het:1Mb-10Mb	0.0746268656716418
2:het:10Mb-40Mb	0.156716417910448
2:het:>40Mb	0.141791044776119
3-4:het:0-100kb	0
3-4:het:100kb-1Mb	0.0223880597014925
3-4:het:1Mb-10Mb	0.119402985074627
3-4:het:10Mb-40Mb	0.00746268656716418
3-4:het:>40Mb	0.0149253731343284
5-8:het:0-100kb	0
5-8:het:100kb-1Mb	0
5-8:het:1Mb-10Mb	0.00746268656716418
5-8:het:10Mb-40Mb	0
5-8:het:>40Mb	0
9+:het:0-100kb	0
9+:het:100kb-1Mb	0
9+:het:1Mb-10Mb	0
9+:het:10Mb-40Mb	0
9+:het:>40Mb	0
)

## For plotting of CN profiles: plotCNprofile()

## For artifical genome doubling of signatures: getGDsig()

## For assignment of signatures to segments: runAssignment()

## For enumeration of recurrence of signatures across the genome: getRecurrence(), plotRecurrence() 

## For plotting of signature definitions: plotSigDefinitions()

## For simulation of signature recurrence: randomRecurrence()
