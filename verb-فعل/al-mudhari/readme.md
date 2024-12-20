### Present/Future Tense (المضارع):
The present and future tense in Arabic is called `المضارع` (Al Mudhari'). It is used to describe actions that are happening now or will happen in the future. The present tense is formed by adding the appropriate prefix and suffix to the verb root.

#### Below is the flowchart for Present/Future Tense (المضارع):

```mermaid

%%{init: {'theme': 'dark', 'themeVariables': {'darkMode': true}, "flowchart" : { "curve" : "basis" } } }%%
flowchart LR
%% Nodes
    al-mudari("المضارع <br> (Present/Future)")

    ghaib-muzakkar("مذكر")
    ghaib-muzakkar-mufrad("يَذْهَبُ <br> يَقُولُ <br> يَضْرِبُ")
    ghaib-muzakkar-musana("يَذْهَبَانِ <br> يَقُولَانِ <br> يَضْرِبَانِ")
    ghaib-muzakkar-jamma("يَذْهَبُونَ <br> يَقُولُونَ <br> يَضْرِبُونَ")
    ghaib-muannath("مؤنث")
    ghaib-muannath-mufrad("تَذْهَبُ <br> تَقُولُ <br> تَضْرِبُ")
    ghaib-muannath-musana("تَذْهَبَانِ <br> تَقُولَانِ <br> تَضْرِبَانِ")
    ghaib-muannath-jamma("يَذْهَبْنَ <br> يَقُلْنَ <br> يَضْرِبْنَ")


    mukhatab-muzakkar("مذكر")
    mukhatab-muzakkar-mufrad("تَذْهَبُ <br> تَقُولُ <br> تَضْرِبُ")
    mukhatab-muzakkar-musana("تَذْهَبَانِ <br> تَقُولَانِ <br> تَضْرِبَانِ")
    mukhatab-muzakkar-jamma("تَذْهَبُونَ <br> تَقُولُونَ <br> تَضْرِبُونَ")
    mukhatab-muannath("مؤنث")
    mukhatab-muannath-mufrad("تَذْهَبِينَ <br> تَقُولِينَ <br> تَضْرِبِينَ")
    mukhatab-muannath-musana("تَذْهَبَانِ <br> تَقُولَانِ <br> تَضْرِبَانِ")
    mukhatab-muannath-jamma("تَذْهَبْنَ <br> تَقُلْنَ <br> تَضْرِبْنَ")


    mutakallim-muzakkar("مذكر/ مؤنث")
    mutakallim-muzakkar-mufrad("اَذْهَبُ <br> أُقولُ <br> اَضْرِبُ")
    mutakallim-muzakkar-musana("نَذْهَبُ <br> نُقَولُ <br> نَضْرِبُ")



    ghaib("غائب <br> (Absent)")
    mukhatab("مخاطب <br> (Addressee)")
    mutakallim("متكلم <br> (Speaker)")

    subgraph "Present/Future Tense (المضارع)"

        al-mudari --> mutakallim
        mutakallim -->mutakallim-muzakkar
        mutakallim-muzakkar -->|مثنى/جمع|mutakallim-muzakkar-musana
        mutakallim-muzakkar -->|مفرد|mutakallim-muzakkar-mufrad


        al-mudari --> mukhatab
        mukhatab --> mukhatab-muzakkar
        mukhatab --> mukhatab-muannath
        mukhatab-muannath -->|جمع|mukhatab-muannath-jamma
        mukhatab-muannath -->|مثنى|mukhatab-muannath-musana
        mukhatab-muannath -->|مفرد|mukhatab-muannath-mufrad
        mukhatab-muzakkar -->|جمع|mukhatab-muzakkar-jamma
        mukhatab-muzakkar -->|مثنى|mukhatab-muzakkar-musana
        mukhatab-muzakkar -->|مفرد|mukhatab-muzakkar-mufrad

        al-mudari --> ghaib
        ghaib --> ghaib-muannath
        ghaib --> ghaib-muzakkar
        ghaib-muannath -->|جمع|ghaib-muannath-jamma
        ghaib-muannath -->|مثنى|ghaib-muannath-musana
        ghaib-muannath -->|مفرد|ghaib-muannath-mufrad
        ghaib-muzakkar -->|جمع|ghaib-muzakkar-jamma
        ghaib-muzakkar -->|مثنى|ghaib-muzakkar-musana
        ghaib-muzakkar -->|مفرد|ghaib-muzakkar-mufrad

    end

%% Styles
    classDef blueShade fill:#add8e6,stroke:#333,stroke-width:2px,color:#000
    classDef pinkShade fill:#ffb6c1,stroke:#333,stroke-width:2px,color:#000
    classDef greenShade fill:#bfb,stroke:#333,stroke-width:2px,color:#000
    class mukhatab-muzakkar,ghaib-muzakkar,mutakallim-muzakkar blueShade;
    class mukhatab-muannath,ghaib-muannath pinkShade;
    class al-mudari,amr,mukhatab,mukhatab-muzakkar-mufrad,mukhatab-muzakkar-musana,mukhatab-muzakkar-jamma,mukhatab-muannath-mufrad,mukhatab-muannath-musana,mukhatab-muannath-jamma greenShade;
    class ghaib-muannath-jamma,ghaib-muannath-musana,ghaib-muannath-mufrad,ghaib-muzakkar-jamma,ghaib-muzakkar-musana,ghaib-muzakkar-mufrad greenShade;
    class mutakallim-muzakkar-jamma,mutakallim-muzakkar-musana,mutakallim-muzakkar-mufrad greenShade;
    class ghaib,mutakallim greenShade;
```

[Previous](../different-tenses/readme.md) | [Next](../al-madhi/readme.md) | [Examples](../examples.md)