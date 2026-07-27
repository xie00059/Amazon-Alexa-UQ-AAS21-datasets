# UQ-AAS21 — A Comprehensive Dataset of Amazon Alexa Skills

UQ-AAS21 is a large-scale dataset covering **65,195 Amazon Alexa skills** crawled
from the Amazon Alexa skill store (data up to May 2021). It captures **16
attributes per skill**, including metadata, ratings, permissions, and privacy
policy links, and was built to give the research community a comprehensive,
well-formatted, publicly available resource where none previously existed.

The dataset underpins follow-up studies, including large-scale privacy
compliance analyses (ASE 2022).

## What's included

The dataset is split into two parts (16 attributes total; skill name appears in both):

**UQ-AAS21-I: basic skill information (11 attributes):**
skill name, page path, developer, supported languages, average rating, number of
ratings, price, in-skill purchase, wake-up words, icon, and category.

**UQ-AAS21-II: privacy-related information (6 attributes):**
skill path, requested permissions (12 subtypes, e.g. email address, location,
full name), invocation name, description, developer privacy policy (DPP) link,
and developer terms-of-use (DTOU) link.

All data is publicly available information only, and no user-identifying or private
data was collected. Data is pre-processed and formatted (per-category tables,
easily loadable into pandas).

## Citation

If you use this dataset, please cite:

```bibtex
@InProceedings{UQAAS21_ADMA2021,
  author    = {Xie, Fuman and Zhang, Yanjun and Wei, Hanlin and Bai, Guangdong},
  title     = {UQ-AAS21: A Comprehensive Dataset of Amazon Alexa Skills},
  booktitle = {Advanced Data Mining and Applications (ADMA)},
  year      = {2021},
  pages     = {159--173}
}
```

## License

Released under the **Open Data Commons Attribution License (ODC-BY 1.0)**:
http://opendatacommons.org/licenses/by/1.0/

You are free to share, create, and adapt from the database, provided you
attribute it as specified. For any public use or redistribution, you must make
the license clear and keep intact any notices on the original database. See the
full [ODC-BY 1.0 license text](http://opendatacommons.org/licenses/by/1.0/) for
the exact terms.
