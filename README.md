# OCR postcorrection

## Resources

### errors.txt

A collection of isolated OCR errors from the cleaned ACL anthology reference corpus (https://web.eecs.umich.edu/~lahiri/acl_arc.html).

### ACL-benchmark

A benchmark with random paragraphs from the ACL corpus (downloaded from [Universität Heidelberg](https://www.cl.uni-heidelberg.de/english/research/downloads/resource_pages/ACL_corrected/ACL_corrected.shtml), because it was not available through the [original source](https://acl-arc.comp.nus.edu.sg/)), with a manually corrected ground truth.
The benchmark is presented in our paper about Tokenization Repair (under review).
Here, it is filtered for OCR errors, excluding whitespace errors and hyphenation errors.

## Related work by our group

- For the correction of hyphenation errors, see [Improved Dehyphenation of Line Breaks for PDF Text Extraction (Bachelor thesis by Mari Hernaes, 2019)](http://ad-publications.informatik.uni-freiburg.de/theses/Bachelor_Mari_Hernaes_2019.pdf).
- For the correction of whitespace errors, see [Tokenization Repair in the Presence of Spelling Errors (arXiv 2020)](https://arxiv.org/abs/2010.07878) + our upcoming paper (under review).
- For the correction of spelling errors, see [Neural Language Models for Spelling Correction (Master thesis by Matthias Hertel, 2019)](http://ad-publications.informatik.uni-freiburg.de/theses/Master_Matthias_Hertel_2019.pdf).