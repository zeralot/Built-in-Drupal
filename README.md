# Check drupal site

Tool that check the input site is built with Drupal or not

## Requirements

* Python 2.7 or Python 3.4+
* Works on Linux, windows

---
### Check header

From an input file, check header and return site with version of Drupal
> $ python Check_Header.py [inputFile] [outputFile]

```
$ python Check_Header.py \input\input_1.txt output_1.txt
```

---

### Check CHANGELOG.txt

From an input file return site with version of Drupal and update version date by checking CHANGELOG.txt content
> $ python Check_CHANGELOG.py [inputFile] [outputFile]

```
$ python Check_CHANGELOG.py \input\input_1.txt output_1.txt
```

---

### Check Drupal

Combine 2 methods above: Check CHANGELOG.txt first then if not check header of the site
> $ python Check_Drupal.py [inputFile] [outputFile]

```
$ python Check_Drupal.py \input\input_1.txt output_1.txt
```
output file such as below: 
```
bayandbeach.com|Drupal 7.66, 2019-04-17
asted.symbiotic.coop|Drupal 7.66, 2019-04-17
asteame.com|Drupal 7.65, 2019-03-20
awex.es|Drupal 7.xx
booksunvalley.com|N/A
```
---

## Built With

* [Python2.7](https://docs.python.org/2.7/)
* [Python3.6](https://docs.python.org/2.6/)

## Authors
### zeralot

