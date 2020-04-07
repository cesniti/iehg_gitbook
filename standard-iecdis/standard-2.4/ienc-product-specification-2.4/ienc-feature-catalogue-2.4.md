# IENC Feature Catalogue 2.5

The Feature Catalogue contains all

* features \(previously object class\)
* attributes and
* enumerations \(priviously attribute values\)

which are allowed for IENCs. That means, that each feature, attribute and enumeration which is mentioned in the Encoding Guide must be listed in the IENC feature catalogue.

Each item contains a reference to an item in a Feature Data Dictionary. Essential information from the dictionary item are also in the feature catalogue. This includes names and definitions. Therefore the feature catalogue is able to solve dictionary queries.

In addition the catalogue contains feature-attribute bindings specific to IENCs. This binding specifies which attribute can be used for a particular featue and which of its enumearions are allowed. Additionally each binding can define contraints like minimum or maximum values, format or units.

The Inland ENC Feature Catalogue has been adopted by the Inland ENC Harmonization Group \(IEHG\) and is applicable in North and South America, Russia and Europe. It is intended, that the Feature Catalogue meets the basic needs for Inland ENC applications worldwide.

{% hint style="warning" %}
The first version of the Feature Catalogue had a typing error in the enumeration of "LITCHR\_18" \(long-flash alternating\). The value "189" had been incorrectly entered. This error has been corrected in the corr1 of the Fetaure Catalogue. Several numerical identifiers of elements had to be corrected to ensure backward compatibility. This error has been corrected in the corr2 of the Feature Catalogue.
{% endhint %}

{% file src="../../../.gitbook/assets/ienc\_fc\_2.5.pdf" caption="Inland ENC Feature Catalogue Ed 2.5 \(pdf\)" %}

