### Al Madhi (الماضي):
The past tense in Arabic is called `الماضي` (Al Madhi). It is used to describe actions that have already happened. The past tense is formed by adding the appropriate prefix and suffix to the verb root.

#### Below is the flowchart for Past Tense (الماضي):

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {'darkMode': true}, "flowchart" : { "curve" : "basis" } } }%%
flowchart LR
%% Nodes
    al-madhi("الماضي <br> (Past)")

    ghaib-muzakkar("مذكر")
    ghaib-muzakkar-mufrad("ذَهَبَ <br> قَالَ <br> ضَرَبَ")
    ghaib-muzakkar-musana("ذَهَبَا <br> قَالا <br> ضَرَبَا")
    ghaib-muzakkar-jamma("ذَهَبُوا <br> قَالُو <br> ضَرَبُو")
    ghaib-muannath("مؤنث")
    ghaib-muannath-mufrad("ذَهَبَتْ <br>قَالَتْ <br> ضَرَبَتْ")
    ghaib-muannath-musana("ذَهَبَتَا <br>قَالَتَا <br> ضَرَبَتَا")
    ghaib-muannath-jamma("ذَهَبْنَ <br>قُلْنَ <br> ضَرَبْنَ")


    mukhatab-muzakkar("مذكر")
    mukhatab-muzakkar-mufrad("ذَهَبْتَ <br> قُلْتَ <br> ضَرَبْتَ")
    mukhatab-muzakkar-musana("ذَهَبْتُمَا <br>قُلْتُمَا <br> ضَرَبْتُمَا")
    mukhatab-muzakkar-jamma("ذَهَبْتُمْ <br>قُلْتُمْ <br> ضَرَبْتُمْ")
    mukhatab-muannath("مؤنث")
    mukhatab-muannath-mufrad("ذَهَبْتِ <br>قُلْتِ <br> ضَرَبْتِ")
    mukhatab-muannath-musana("ذَهَبْتُمَا <br>قُلْتُمَا <br> ضَرَبْتُمَا")
    mukhatab-muannath-jamma("ذَهَبْتُنَّ <br> قُلْتُنَّ <br> ضَرَبْتُنَّ")


    mutakallim-muzakkar("مذكر/ مؤنث")
    mutakallim-muzakkar-mufrad("ذَهَبْتُ <br> قُلْتُ <br> ضَرَبْتُ")
    mutakallim-muzakkar-musana("ذَهَبْنَا <br>قُلْنَا <br> ضَرَبْنَا")


    ghaib("غائب <br> (Absent)")
    mukhatab("مخاطب <br> (Addressee)")
    mutakallim("متكلم <br> (Speaker)")

subgraph "Past Tense (الماض)"

    al-madhi --> mutakallim
    mutakallim -->mutakallim-muzakkar
    mutakallim-muzakkar -->|مثنى/جمع|mutakallim-muzakkar-musana
    mutakallim-muzakkar -->|مفرد|mutakallim-muzakkar-mufrad


    al-madhi --> mukhatab
    mukhatab --> mukhatab-muzakkar
    mukhatab --> mukhatab-muannath
    mukhatab-muannath -->|جمع|mukhatab-muannath-jamma
    mukhatab-muannath -->|مثنى|mukhatab-muannath-musana
    mukhatab-muannath -->|مفرد|mukhatab-muannath-mufrad
    mukhatab-muzakkar -->|جمع|mukhatab-muzakkar-jamma
    mukhatab-muzakkar -->|مثنى|mukhatab-muzakkar-musana
    mukhatab-muzakkar -->|مفرد|mukhatab-muzakkar-mufrad

    al-madhi --> ghaib
    ghaib --> ghaib-muannath
    ghaib --> ghaib-muzakkar
    ghaib-muannath -->|جمع|ghaib-muannath-jamma
    ghaib-muannath -->|مثنى|ghaib-muannath-musana
    ghaib-muannath -->|مفرد|ghaib-muannath-mufrad
    ghaib-muzakkar -->|جمع|ghaib-muzakkar-jamma
    ghaib-muzakkar -->|مثنى|ghaib-muzakkar-musana
    ghaib-muzakkar -->|مفرد|ghaib-muzakkar-mufrad

end

    classDef commonStyle fill:#d3d3d3,stroke:#333,stroke-width:2px,color:#000
    classDef blueShade fill:#add8e6,stroke:#333,stroke-width:2px,color:#000
    classDef pinkShade fill:#ffb6c1,stroke:#333,stroke-width:2px,color:#000
    classDef greenShade fill:#bfb,stroke:#333,stroke-width:2px,color:#000
    class amr,mukhatab commonStyle;
    class mukhatab-muzakkar,ghaib-muzakkar,mutakallim-muzakkar blueShade;
    class mukhatab-muannath,ghaib-muannath pinkShade;
    class al-madhi,amr,mukhatab,mukhatab-muzakkar-mufrad,mukhatab-muzakkar-musana,mukhatab-muzakkar-jamma,mukhatab-muannath-mufrad,mukhatab-muannath-musana,mukhatab-muannath-jamma greenShade;
    class mutakallim,mutakallim-muzakkar-musana,mutakallim-muzakkar-mufrad,ghaib,ghaib-muzakkar-mufrad,ghaib-muzakkar-musana,ghaib-muzakkar-jamma,ghaib-muannath-mufrad,ghaib-muannath-musana,ghaib-muannath-jamma greenShade;
```

[Previous](../al-mudhari/readme.md) | [Next](../al-amr/readme.md) | [Examples](../examples.md)