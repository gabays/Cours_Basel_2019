PDEN 2019

# Corpus encoding - Exercice

Simon Gabay

11 décembre 2019

---
Open a new document 
![80% center](../img/Oxygen_1.png)

---

Search for "TEI all"
![80% center](../img/Oxygen_2.png)

---

We now need to adapt the schema
![80% center](../img/Oxygen_3.png)

---
We need to select the ELTeC schema, so we remove the general one

```xml
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml"
	schematypens="http://purl.oclc.org/dsdl/schematron"?>
```

with

```xml
<?xml-model href="https://github.com/COST-ELTEC/Schemas/raw/master/eltec-0.rng" type="application/xml" 
            schematypens="http://relaxng.org/ns/structure/1.0"?>
    <?xml-model href="https://github.com/COST-ELTEC/Schemas/raw/master/eltec-0.rng" type="application/xml" 
            schematypens="http://purl.oclc.org/dsdl/schematron"?>
```
If required, choose "Allow and remember"

---

