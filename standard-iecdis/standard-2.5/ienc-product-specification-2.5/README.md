# IENC Product Specification 2.5

This page conatins the edition 2.5 of the Product Specification for Inland ENCs, which might become an annex of a future **European InlandECDIS Standard Edition 2.5, Section 2**. The Inland ENC Product Specification is a set of specifications intended to enable chart producers to produce a consistent Inland ENC, and manufacturers to use that data efficiently in an Inland ECDIS that satisfies the Performance Standard for Inland ECDIS. An Inland ENC must be produced in accordance with the rules defined in this Specification and must be encoded using:

* the Inland ENC Feature Catalogue and
* the rules described in the Inland ENC Encoding Guide

The Inland ENC Product Specification has been adopted by the Inland ENC Harmonization Group (IEHG) and is applicable in North and South America, Russia, Europe and Asia. It is intended, that the Product Specification meets the basic needs for Inland ENC applications worldwide.&#x20;

{% hint style="info" %}
The attributes 18020 lc\_lg1, 18018 lc\_bm1 and 18019 lc\_bm2 have been deleted in edition 2.3 because they have never been used by chart producers. The numerical codes have been reused for other attributes in edition 2.4. IEHG advises application builders who are using combined Feature Catalogues covering several Editions to delete the three old attributes from their catalogues.
{% endhint %}

{% file src="../../../.gitbook/assets/prodspec_ienc_2_5.pdf" %}
Product Specification for Inland ENCs Ed 2.5 (pdf)
{% endfile %}

{% file src="../../../.gitbook/assets/prodspec_ienc_2_5_trackchanges.pdf" %}
Track changes version of the Product Specification (2.5)
{% endfile %}

{% hint style="info" %}
Two tables in the original edition 2.5 of the Product Specification were still containing references to edition 2.4. This had to be corrected because systems would not have been able to recognize an Inland ENC as edition 2.5, if the cell header would still have referred to edition 2.4. Please use the corrected version for implementation.
{% endhint %}

{% file src="../../../.gitbook/assets/ProdSpec_IENC_2_5_corr.pdf" %}
