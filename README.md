# NumberToWords
A PHP class for converting numbers (figures) to words in specified currency code.


# Supported Currencies
EUR, GBP, GHC, GHS, MUR, NGN, USD, XAF, XOF


# Test
_$obj = new NumberToWords();_

_echo $obj->convert(3490948028.56, "NGN");_

Displays **Three Billion, Four Hundred and Ninety Million, Nine Hundred and Forty-Eight Thousand, and Twenty-Eight Naira, Fifty-Six Kobo**
