# Hunspell CY Llafar

Mae'r fersiwn hwn o Hunspell wedi ei deilwra yn arbennig at anghenion y trawsgrifwyr sydd yn cyfrannu at fanc trawsgrifiadau Uned Technolegau Iaith Prifysgol Bangor. Mae'n cynnwys nifer o ffurfiau llafar  sy'n cydymffurfio gyda chonfensiynau trawsgrifio verbatim y project hwnnw (gw. https://git.techiaith.bangor.ac.uk/data-porth-technolegau-iaith/banc-trawsgrifiadau-bangor#confensiynau-trawsgrifio am fwy o fanylion). Ceir ynddo ffurfiau llafar megis *ch'mod*, *rwbath*, *sicir* a *gweud*.

*This version of Hunspell has been specially tailored to the needs of the transcribers who contribute to Bangor University Language Technology Unit's transcription bank. It contains a number of spoken forms which comply with the verbatim transcription conventions of that project (see [https://git.techiaith.bangor.ac.uk/data-porth-technologiau-iaith/banc- transcripts-bangor#conventions-transcript](https://git.techiaith.bangor.ac.uk/data-porth-technolegau-iaith/banc-trawsgrifiadau-bangor#transcription-conventions) for more details). It contains a number of spoken forms such as *ch'mod*, *rwbath*, *sicir* and *gweud*.*

I'w ddefnyddio o fewn eich cod:

*To use in your code:*

```
pip install hunspell
```

yna

*then*

```
import hunspell


cy_speller = hunspell.HunSpell('/usr/share/hunspell/cy_GB_llafar.dic', '/usr/share/hunspell/cy_GB.aff')
word = "kamsillafiad"
cy_speller.spell(word)

>>> False
```

Am ragor o fanlion, gweler:

*For more details, see:*

https://github.com/blatinier/pyhunspell

Ariannwyd y diweddariad hwn gan Lywodraeth Cymru.

*This update was funded by the Welsh Government.*
