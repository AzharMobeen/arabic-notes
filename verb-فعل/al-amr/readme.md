### Al Amr (الأمر):
The imperative mood in Arabic is called `الأمر` (Al Amr). It is used to give commands or orders. The imperative mood is formed by adding the appropriate prefix and suffix to the verb root.

#### Below is the flowchart for Imperative Mood (الأمر):

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {'darkMode': true}, "flowchart" : { "curve" : "basis" } } }%%
flowchart LR
%% Nodes
    amr("فعل أمر <br> (Imperative)")

    mukhatab-muzakkar("مذكر")
    mukhatab-muzakkar-mufrad("(go) اِذْهَبْ <br> (say or tell) قُلْ <br> (open) اِفْتَحْ <br> (write) اُكْتُبْ <br> (put/place) ضَعْ <br> (found) جِدْ <br> <asked>اِسْأَلْ/سَلْ")
    mukhatab-muzakkar-musana("اِذْهَبَا <br> قولا <br> اِفْتَحَا <br> اُكْتُبَا <br> ضَعَا <br> جِدَا <br> اِسْأَلا")
    mukhatab-muzakkar-jamma("اِذْهَبُوا <br> قولوا <br> اِفْتَحُوا <br> اُكْتُبُوا <br> ضَعُوا <br> جِدُوا <br> اِسْأَلُوا")
    mukhatab-muannath("مؤنث")
    mukhatab-muannath-mufrad("اِذْهَبِي<br> قولي <br> اِفْتَحِي <br> اُكْتُبِي <br> ضَعِي <br> جِدِي <br> اِسْأَلِي")
    mukhatab-muannath-musana("اِذْهَبَا <br> قولا <br> اِفْتَحَا <br> اُكْتُبَا <br> ضَعَا <br> جِدَا <br> اِسْأَلا")
    mukhatab-muannath-jamma("اِذْهَبْنَ<br> قُلْنَ <br> اِفْتَحْنَ <br> اُكْتُبْنَ <br> ضَعْنَ <br> جِدْنَ <br> اِسْأَلْنَ")

    mukhatab("مخاطب <br> (Addressee)")

subgraph "Imperative Tense (الأمر)"

    amr --> mukhatab
    mukhatab --> mukhatab-muzakkar
    mukhatab --> mukhatab-muannath
    mukhatab-muannath -->|جمع|mukhatab-muannath-jamma
    mukhatab-muannath -->|مثنى|mukhatab-muannath-musana
    mukhatab-muannath -->|مفرد|mukhatab-muannath-mufrad
    mukhatab-muzakkar -->|جمع|mukhatab-muzakkar-jamma
    mukhatab-muzakkar -->|مثنى|mukhatab-muzakkar-musana
    mukhatab-muzakkar -->|مفرد|mukhatab-muzakkar-mufrad

end

%% Styles
    classDef commonStyle fill:#d3d3d3,stroke:#333,stroke-width:2px,color:#000
    classDef blueShade fill:#add8e6,stroke:#333,stroke-width:2px,color:#000
    classDef pinkShade fill:#ffb6c1,stroke:#333,stroke-width:2px,color:#000
    classDef greenShade fill:#bfb,stroke:#333,stroke-width:2px,color:#000
    class amr,mukhatab commonStyle;
    class mukhatab-muzakkar blueShade;
    class mukhatab-muannath pinkShade;
    class amr,mukhatab,mukhatab-muzakkar-mufrad,mukhatab-muzakkar-musana,mukhatab-muzakkar-jamma,mukhatab-muannath-mufrad,mukhatab-muannath-musana,mukhatab-muannath-jamma greenShade;
```

[Previous Topic](../al-madhi/readme.md) | [Next Topic](../examples.md) | [Examples](../examples.md)