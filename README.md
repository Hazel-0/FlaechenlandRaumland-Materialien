<!--
author:   Hazel-0

email:    sinahasel@duck.com

version:  0.0.1

language: en

narrator: US English Female

comment:  Testing only
-->

# SCORM Test

Let's see if this works.

## Cool content

Look at this!

![Uganda-Grasantilopen](https://upload.wikimedia.org/wikipedia/commons/5/5c/Uganda_Kobs_%28Kobus_thomasi%29_%286857288676%29.jpg) ![Antilope mit Jungtier](https://upload.wikimedia.org/wikipedia/commons/3/37/Ugandan_kobs_%28Kobus_kob_thomasi%29_female_and_calf.jpg) ![Antilopenpaarung](https://upload.wikimedia.org/wikipedia/commons/a/a7/Ugandan_kobs_%28Kobus_kob_thomasi%29_mating_ritual_composite.jpg)

??[Shiba](https://sketchfab.com/3d-models/shiba-faef9fe5ace445e7b2989d1c1ece361c)

<iframe src="https://giphy.com/embed/V6vNqIGP1RiMEwmMGV" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/justin-meme-doge-shibe-V6vNqIGP1RiMEwmMGV">via GIPHY</a></p>

## It's Formatting Time!

with lists and tables

### Lists

+ lets see what we got
* this also works

  - Eins
  - Zwei 
  - Drei
    
    - vier
    - fünf

>> now for something completely different

> "Nor for something completely different"
>
> -- Monty Python

1. dies das ananas
2. mehr ananas

ananas ist eine gute frucht

3. ich mag auch kiwi


### Tables

first line is left aligned = default, second and third is centered, fourth is right aligned 

|Whose | cat | is | cute|
|:---- | :----: | :----: | ----: | 
| ***Your*** | 4| 3| 1|
| ***Their***| 2| 2| 2|
| ***Our*** | 5|9 |7 |

Birds watched

| Bird name   | # observed | Places                    |
| ----------- | ---------- | ------------------------- |
| Robin   | 87         | everywhere                |
| Kingfisher  | 7          | Berlin, Braunschweig, Ise |
| Tree walker | 6          | Braunschweig |


### Playing the accordion

I love accordions.

<details>

<summary>**Honest Textbook ads (click to enlarge)**</summary>

!?[If High School and College Textbooks Were Honest - Honest Ads](https://www.youtube.com/watch?v=lhSjYT7pWkw)

</details>

<details>

<summary>**John Oliver Tonight - Opioid Settlements**</summary>

!?[John Oliver Tonight - Opioid Settlements](https://www.youtube.com/watch?v=Io0yuH1CiA0)

</details>

<details>

<summary>**Shintoism explained**</summary>

!?[Shintoism Explained](https://www.youtube.com/watch?v=mX8cz1LEeXw&pp=ygUUZXhwbGFpbmluZyBzaGludG9pc20%3D)

</details>

## It's Quiz Time!


There are text quizzes [^0](__Text quizzes__ means quizzes with text fields), single choice quizzes, multiple choice quizzes[^1] and other types[^2].

[^1]: A task list with a predefined solution and one or more than one correct option, see [LiaScript documentation on multiple choice](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#65)

[^2]: See [LiaScript documentation on more types](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#71)

###  Single and Multiple Choice

Please guess the solution:

- [[ ]] Eins
- [[x]] Zwei
- [[ ]] Drei

    [[ ]] Eins
    [[x]] Zwei
    [[ ]] Drei

[(x)] Eins
[( )] Zwei
[( )] Drei
[( )] Vier

Wie findest du dieses Quiz?

[[gut] [mittel] [schlecht]]
[(x) (x) (x)]  inhaltlich
[(x) (x) (x)]  funktional
[(x) (x) (x)]  optisch


### Text fields

Variante 1: Wie heißt die Begleiterin von Marlin im Film "Findet Nemo?"

  [[ Dorie ]]

---

Variante 2: Wie heißt die Begleiterin von Marlin im Film "Findet Nemo?"

[[dorie]]
<script>
let input = "@input".trim().toLowerCase()

input == "dorie" || input == "dori"
</script>

---

What did the fish say when he swam into the wall?

[[dam]]
<script>
let input = "@input".trim().toLowerCase()

input == "dam" || input == "damn"
</script>

---

Wie viele Dalmatiner?

[[ 100 | ( 101 ) | 102 | (**viele**) ]]
[[?]] Es ist ein Film

---

Der [[ Kater ]] hat ein [[ oranges ]] Fell.

---

Der __[[ Puter | (Kater) ]]__ hat ein __[[ grünes | (oranges) ]]__ Fell.

### And more

What is $37 + 15$?

    [[52]]
    [[?]] the solution is larger than 50
    [[?]] it is less than 55
    [[?]] it should be an even number
*****
You are a math champion!
*****

---

Randomisierte Antworten:

<!-- data-randomize -->
[(x)] Eins
[( )] Zwei
[( )] Drei
[( )] Vier

---

Wie viele maximale Antwortmöglichkeiten gibt es?

<!-- data-max-trials="3" -->
[( )] Eins
[( )] Zwei
[(x)] Drei
[( )] Vier
***
Drei ist die richtige Antwort
***

---

Can you reveal the solution button?

<!-- data-solution-button="off" -->
[( )] YES
[(X)] NO

---

How many trials are necessary to show the solution button?

<!-- data-solution-button="3" -->
[[3]]

---

How many trials are necessary to show the hints?

<!-- data-hint-button="2" -->
[[2]]
[[?]] The solution is smaller than 3
[[?]] Try an even number

---

Enter the correct numbers:

<!-- data-show-partial-solution -->

``` ascii
                        .----------------------.
                       /                      /|
             .--------+----------------------+ +---------.
            /         |      " [[  24   ]] " |/         /|
  .--------+----------+----------+-----------+---------+ +----------.
 /         |         11          |      "[[   13   ]] "|/          /|
+----------+----------+----------+----------+----------+----------+ +
|      " [[   5   ]] "|          6          |          7          |/
+---------------------+---------------------+---------------------+
```


## Surveys 

### Texteingabe

Was sind deine Lieblingstiere? (Eingabe über Komma)

[[___]]

___

Warum magst du diese Tiere so gerne?

    [[___ ___ ___ ___]]

### Single Choice 

Was ist deine Lieblingsfarbe?

    [(1)] rot
    [(2)] gelb
    [(3)] grün
    [(4)] blau

---

Wie gern magst du die Farbe Orange?

    [(sehr gern)] sehr gern
    [(gern)] gern
    [(nicht so gern)] nicht so gern
    [(gar nicht)] gar nicht

### Multiple Choice 

Was sind deine Lieblingsfarben?

    [[1]] rot
    [[2]] gelb
    [[3]] grün
    [[4]] blau

### Matrix-Fragen

Wie findest du diesen Kurs?

    [(1 toll)(2 ok)(3 so mittel)(4 nicht so toll)(5 furchtbar)]
    [                                             ] inhaltich
    [                                             ] optisch
    [                                             ] funktional

---

Welche Süßigkeiten magst du in welcher Farbe?

[[rot][gelb][grün][blau][braun]]
[                     ] Smarties
[                     ] M&Ms
[                     ] Skittles


## Animations

### Test animations

This only works in presentation or slides mode:

     {{1}}
This is an example for a *single* block animations.

     {{2-3}}
This one will appear on animation step 2 and disappear on 3.

{{4}} This is also ok, but it will look be harder to spot on GitHub.

            {{5-6}}
************************************

This is an example...

| that     | contains |
|----------|----------|
| multiple | blocks.  |

************************************

        {{7}}
*************************************

> "That's all folks!"
>
> -- Bugs Bunny

*************************************

### Inline animations

* no effect here
* but in this line {2}{show ***second***}
* as well as this one {1-2}{show ***first*** remove on __second__}

### Using the Animate.css library

Documentation [see here](https://animate.style/#attention_seekers)

<!--
class="animate__animated animate__backInUp animate__backOutDown"
style="background:#CCC; padding:3rem; min-height: 40vh; border-radius: 3rem"
-->
                 {{1-4}}
*******************************************

This block contains {2}{multiple} inline animations.
With some
{2-3}{styled}<!-- class="animate__animated animate__flash"-->
elements as well.

<!-- class="animate__animated animate__backInDown" -->
                  {{3}}
!?[Animated paintings](https://www.youtube.com/watch?v=-DDphfCnFQc&autoplay=true)

*******************************************

<!--

class="animate__animated animate_backInRight animate__tada" style="background:#CCC; padding:3rem; min-height: 40vh; border-radius: 3rem"
-->
            {{4}} 
********************************************

Tadaaa!

********************************************
