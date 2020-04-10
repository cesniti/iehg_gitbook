---
description: Edition 2.5
---

# Product Specification for bathymetric Inland ENCs

This page contains Edition 2.5 of the Product Specification for bathymetric Inland ENCs, which is intended to become an appendix of a future **European InlandECDIS Standard Edition 2.5**, Section 2.

The bathymetric Inland ENC is a S-57 based product in addition to the already existing products \(ENC, Inland ENC\).  
The content of bathymetric Inland ENCs is limited to the bathymetry data only and can therefore only be used together with Inland ENCs. The depth information can be encoded by means of the object classes depth area \(DEPARE, depare\), dredged area \(DRGARE\), depth contour \(DEPCNT\) and soundings \(SOUNDG\). Navigable areas without depths information are encoded as unsurveyed areas \(UNSARE\). Meta data is used to provide information about the pre-mentioned feature objects \(e.g. accuracy and quality information\). The use of bathymetric Inland ENCs facilitates the incorporation of survey-sensor based depth information during the ENC production process. This is because the bathymetry is stored in separate datasets which are simply replaced when new depth data is available.  
The Product Specification for bathymetric Inland ENCs is a set of specifications intended to enable chart producers to produce a consistent bathymetric Inland ENC, and manufacturers to use that data efficiently in an Inland ECDIS that satisfies the Performance Standard for Inland ECDIS \(Section 1\).

A bathymetric Inland ENC must be produced in accordance with the rules defined in this Specification and must be encoded using:

* the bathymetric Inland ENC Feature Catalogue and
* the rules described in the [Inland ENC Encoding Guide](../ienc-product-specification-2.5/ienc-encoding-guide-2.3.6.md)

The Inland ENC Product Specification has been adopted by the Inland ENC Harmonization Group \(IEHG\) and is applicable in North and South America, Russia, Europe and Asia. It is intended, that the Product Specification meets the basic needs for Inland ENC applications worldwide.

{% file src="../../../.gitbook/assets/prodspec\_bathienc\_2\_5.pdf" caption="Product Specification for bathymetric Inland ENCs Ed 2.5 \(pdf\)" %}

{% file src="../../../.gitbook/assets/bienc\_test\_cells.zip" caption="bathymetric Inland ENC test cells \(zip\)" %}

