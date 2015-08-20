# The Power of Two

Certain numbers will appear around you again and again when you deal with computers. Numbers like 1, 2, 4, 8, 16, 32, 64, 128, 256, 512 and 1024. Some examples: Your computer most likely has 1, 2, 4 or 8 Gigabytes of RAM. It can display 16 million different colors, its sound chip can produce 64 thousand different amplitudes, one byte can store 256 different values. The reason for the unusual omnipresence of these numbers of course is that they are powers of two and your computer works with a binary system. Powers of two are everywhwere. Therefore it is very much worth your time to familiarize yourself with these numbers. It will come in handy no matter if you are programming, have a debate with a sales person when buying a new laptop or decide on a new data plan for your mobile.

- [indian story of chess board and rice/wheat](https://en.wikipedia.org/wiki/Wheat_and_chessboard_problem)
- show the board with numbers
  - 1,2,4,8,16,32,64,128,512,1k,2k ...
- play 2048!
- x^y read: x to the power of y (we write it like this because superscript is not available everywhere)
- point out: 1k stands for x1024 (unlike in the decimal world ([SI prefixes](https://en.wikipedia.org/wiki/Metric_prefix)), where it stands for x1000 as in km and kg)
  - the confusion about whether, for example, G stands for 1024\*1024\*1024 or 1000\*1000\*1000 is exploited by marketing people, most famously when advertising harddisks. Harddsika can store less than you think, because "120GB" actually are what we would call 111.75GB.
  - well, actually: to resolve this, the binary prefixes (1024-baesd) have a trailing `i`. (see [here](https://en.wikipedia.org/wiki/Binary_prefix))
    - 1KiB = 1.024 kB (KiB is pronounced "Kibibyte", something I have never heared in my entire life)
- prefixes are: kilo, Mega, Giga, Tera, Peta, Exa
- point out:
  - 2^1_ = Ki
  - 2^2_ = Mi
  - 2^3_ = Gi
  - 2^4_ = Ti
  - 2^5_ = Pi
  - 2^6_ = Ei

- TODO: mnemotechnic verse for KMGTPE - Kiwis make green things particularily enjoyable – or something. (the stuff you gfind on the web is reversed or otherwise broken)

- things you should know by heart:
  - 2^0 = 1
  - 2^1 = 2
  - 2^2 = 4
  - 2^4 = 16
  - 2^6 = 64 (easy, starts with 6)
  - 2^8 = 256 (one byte has 8 bits, 256 possibilities for the value of a byte)
  - 2^10 = 1024 (easy, starts with 10)

- Quizz:
  - what is 2 to the power of 44? Answer: 16Ti
  - or: what is 2^16? Answer: 64Ki
    - (65,536)
  - or: 2^64 (max. unsinged integer value in 64bit, number of grains of rice on last chessboard square): 16 Ei
   (the 20-digit decimal number 18,446,744,073,709,551,616)
  
2^2048 (typical key length): we have no name for that (617 digit decimal number)
(there are 32317006071311007300714876688669951960444102669715484032130345427524\
65513886789089319720141152291346368871796092189801949411955915049092\
10950881523864482831206308773673009960917501977503896521067960576383\
84067568276792218642619756161838094338476170470581645852036305042887\
57589154106580860755239912393038552191433338966834242068497478656456\
94948561760353263220580778056593310261927084603141502585928641771167\
25943603718461857357598351152301645904403697613233287231227125684710\
82020972515710172693132346967854258065669793504599726835299863821552\
51663894373355436021354332296046453184786049521481935558536110595962\
30656 different keys)

But it is recommended to use a key length of 4096 bits (that's a 1234-digit decimal number)
