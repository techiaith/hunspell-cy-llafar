[English text below](#hunspell-spoken-cy)

# Hunspell CY Llafar

Mae'r fersiwn hwn o Hunspell wedi ei deilwra yn arbennig at anghenion y trawsgrifwyr sydd yn cyfrannu at fanc trawsgrifiadau Uned Technolegau Iaith Prifysgol Bangor. Mae'n cynnwys nifer o ffurfiau llafar  sy'n cydymffurfio gyda chonfensiynau trawsgrifio verbatim y project hwnnw (gw. https://git.techiaith.bangor.ac.uk/data-porth-technolegau-iaith/banc-trawsgrifiadau-bangor#confensiynau-trawsgrifio am fwy o fanylion). Ceir ynddo ffurfiau llafar megis *ch'mod*, *rwbath*, *sicir* a *gweud*.

Cafodd y fersiwn hwn o Hunspell ei diweddaru ym mis Mawrth 2025. Mae'r diweddariad yn cynnwys ffurfiau llafer ychwanegol  (gan gynnwys *lyfli*, *ugian* a *wsos*).

I'w ddefnyddio o fewn eich cod:

```
pip install hunspell
```

yna


```
import hunspell


cy_speller = hunspell.HunSpell('/usr/share/hunspell/cy_GB_llafar.dic', '/usr/share/hunspell/cy_GB.aff')
word = "kamsillafiad"
cy_speller.spell(word)

>>> False
```

Am ragor o fanlion, gweler:

https://github.com/blatinier/pyhunspell

Ariannwyd y diweddariad hwn gan Lywodraeth Cymru.


# Hunspell Spoken CY

This version of Hunspell has been specially tailored to the needs of the transcribers who contribute to Bangor University Language Technology Unit's transcription bank. It contains a number of spoken forms which comply with the verbatim transcription conventions of that project (see [https://git.techiaith.bangor.ac.uk/data-porth-technologiau-iaith/banc- transcripts-bangor#conventions-transcript](https://git.techiaith.bangor.ac.uk/data-porth-technolegau-iaith/banc-trawsgrifiadau-bangor#transcription-conventions) for more details). It contains a number of spoken forms such as *ch'mod*, *rwbath*, *sicir* and *gweud*.

This version of Hunspell was updated in March 2025. The update includes additional verbatim forms (including *lyfli*, *ugian* a *wsos*).

To use in your code:

```
pip install hunspell
```

then

```
import hunspell


cy_speller = hunspell.HunSpell('/usr/share/hunspell/cy_GB_llafar.dic', '/usr/share/hunspell/cy_GB.aff')
word = "kamsillafiad"
cy_speller.spell(word)

>>> False
```

For more details, see:

https://github.com/blatinier/pyhunspell

This update was funded by the Welsh Government.
