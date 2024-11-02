### Verb Types (`أقسام الفعل`):
There are four types of verbs in Arabic Grammar:
1. `فعل صحيح (Sound Verb)`
2. `فعل مهموز (Hamza Verb)`
3. `فعل مضعف (Doubled Verb)`
4. `فعل معتل (Weak Verb)`
   - There are five types of `فعل معتل (Weak Verb)`
   - `معتل المثال: The first root letter is weak`
   - `معتل الأجوف: The middle root letter is weak`
   - `معتل الناقص: The last root letter is weak`
   - `معتل اللفيف مقرون: Two weak letters consecutive`
   - `معتل اللفيف مفروق: Two weak letters separated by a strong letter`


#### Below is the flowchart for Types of Verb (`أقسام الفعل`):

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {'darkMode': true}, "flowchart" : { "curve" : "basis" } } }%%
flowchart LR
subgraph "Types of Verb (أقسام الفعل)"
A("فعل") --> |1| B("فعل صحيح (Sound Verb)")
A --> |2|C("فعل مهموز (Hamza Verb)")
A --> |3|D("فعل مضعف (Doubled Verb)")
A --> |4|E("فعل معتل (Weak Verb)")

B --> |definition| B1>"No weak letters (حروف العلة) in the root"]
B1 --> |example| B2("كتب (kataba) - He wrote <br> سمع (sami'a) - He heard")

C --> |definition| C1>"Contains a Hamza (ء) in one of the root letters"]
C1 --> |example| C2("أخذ (akhadha) - He took <br> سأل (sa'ala) - He asked <br> He read (qara'a) قَرَأَ")


D --> |definition| D1>"Contains a repeated root letter <br> with a shadda (شدة) on it"]
D1 --> |example| D2("ردّ (radda) - He replied <br> شَدَّ (shadda) - He tightened")

end
subgraph WeakVerb

E --> |definition| E1>"Contains one or more weak letters (حروف العلة) in its root <br>
    there are five types of فعل معتل (Weak Verb)"]
E1 --> |1|E2("معتل المثال: The first root letter is weak")
E2 --> |example| E3("وعد (waʿada) - He promised")
E1 --> |2|E4("معتل الأجوف: The middle root letter is weak")
E4 --> |example| E5("قال (qāla) - He said")
E1 --> |3|E6("معتل الناقص: The last root letter is weak")
E6 --> |example| E7("دعا (daʿā) - He called")
E1 --> |4|E8("معتل اللفيف مقرون: Two weak letters consecutive")
E8 --> |example| E9("روي (rawa) - He narrated")
E1 --> |5|E10("معتل اللفيف مفروق: Two weak letters separated by a strong letter")
E10 --> |example| E11("وقي (waqi) - He protected")
end

%% Styles
classDef greenShade fill:#bfb,stroke:#333,stroke-width:2px,color:#000
class A,B,C,D,E,B1,B2,C1,C2,D1,D2,E1,E2,E3,E4,E5,E6,E7,E8,E9,E10,E11 greenShade;
```

[Previous](../readme.md) | [Next](../different-tenses/readme.md) | [Examples](../examples.md)