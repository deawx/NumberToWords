# NumberToWords
A PHP class for converting numbers (figures) to words in specified currency code.


# Supported Currencies
EUR, GBP, GHC, GHS, MUR, NGN, USD, XAF, XOF


# Test
$obj = new NumberToWords();

echo $obj->convert(3490948028.56, "NGN");

Displays _*Three Billion, Four Hundred and Ninety Million, Nine Hundred and Forty-Eight Thousand, and Twenty-Eight Naira, Fifty-Six Kobo*_
