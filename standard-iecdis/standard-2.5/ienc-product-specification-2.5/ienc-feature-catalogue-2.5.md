# IENC Feature Catalogue 2.5 corr1

The Feature Catalogue contains all

* features (previously object class)
* attributes and
* enumerations (priviously attribute values)

which are allowed for IENCs. That means, that each feature, attribute and enumeration which is mentioned in the Encoding Guide must be listed in the IENC feature catalogue.

Each item contains a reference to an item in a Feature Data Dictionary. Essential information from the dictionary item are also in the feature catalogue. This includes names and definitions. Therefore the feature catalogue is able to solve dictionary queries.

In addition the catalogue contains feature-attribute bindings specific to IENCs. This binding specifies which attribute can be used for a particular featue and which of its enumearions are allowed. Additionally each binding can define contraints like minimum or maximum values, format or units.

The Inland ENC Feature Catalogue has been adopted by the Inland ENC Harmonization Group (IEHG) and is applicable in North and South America, Russia and Europe. It is intended, that the Feature Catalogue meets the basic needs for Inland ENC applications worldwide.

In edition 2.5 corr1, which has been adopted by IEHG on 16th April 2021, some typograhical errors have been corrected.

{% hint style="info" %}
There is a typing error in edition 2.5 corr1: For the feature Military practice area (MIPARE) the Feature Catalogue is containing the following line:

&#x20;RESTRN  O  value list = "1,2,3,4,5,6,7,8,9,10,11,12,13,14,,2715,16,17,18,19,20,21,22,23,24,25,26"

The value 27 has been inserted in the wrong place and should have been added at the end. The correct value list is:\
"1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27"
{% endhint %}

{% file src="../../../.gitbook/assets/ienc_fc_25_corr1.pdf" %}
Inland ENC Feature Catalogue Ed 2.5 corr1 (pdf)
{% endfile %}

{% file src="../../../.gitbook/assets/ienc_fc_251.xml" %}
Inland ENC Feature Catalogue Ed 2.5 corr1 (xml)
{% endfile %}
