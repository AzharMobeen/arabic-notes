### Different Tenses:
- Present and Future Tense (`المضارع`)
- Past Tense (`الماضي`)
- Imperative Mood (`الأمر`)

#### Below is the flowchart for Verb Types W.R.T Tenses:

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {'darkMode': true}, "flowchart" : { "curve" : "basis", "nodeSpacing" : 50, "rankSpacing" : 50 } } }%%
flowchart LR

%% Nodes

    fail("فعل اقسام <br> (Verb Types)")
    madhi("فعل ماضٍ <br> (Past)")
    mudari("فعل مضارع <br> (Present)")
    amr("فعل أمر <br> (Imperative)")
    madhi_def>"Action completed in the past"]
    madhi_ex("ذهب")
    mudari_def>"Action happening now or in the future"]
    mudari_ex("يذهب")
    amr_def>"Command to do something"]
    amr_ex("اذهب")


    subgraph "Verb Types W.R.T Tenses"

        fail -->|1| madhi
        fail -->|2| mudari
        fail -->|3| amr

        madhi -->|definition| madhi_def
        madhi_def -->|example| madhi_ex

        mudari -->|definition| mudari_def
        mudari_def -->|example| mudari_ex

        amr -->|definition| amr_def
        amr_def -->|example| amr_ex
    end


    classDef greenShade fill:#bfb,stroke:#333,stroke-width:2px,color:#000
    class fail,madhi,mudari,amr,amr_def,amr_ex,mudari_def,mudari_ex,madhi_def,madhi_ex greenShade;
```

[Previous](../verb-types/readme.md) | [Next](../al-mudhari/readme.md) | [Examples](../examples.md)