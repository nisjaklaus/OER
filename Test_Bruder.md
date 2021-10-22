<!--
author:   Denise Klaus

version:  0.0.1

language: de

narrator: Deutsch Male

comment:  Das ist eine Test Datei, um sich mit GitHub
          vertraut zu machen
-->

# Ergebnisse des Bekanntmachens

Hier finden sich die Features von LiaScript, die mir für das Projekt relevant schienen.

## Kapitel 1 - Text

In diesem Kapitel zeige ich, wie man die Schrift formatieren kann.

### Schriftformatierung

~~Man kann den Text beispielsweise unterstreichen~~

**oder fett schreiben**

_oder kursiv schreiben_ (mit Zeichen wie \* durch einen zusätzlichen \ )

;-) Smileys gehen auch.

Man kann den Text auch **einfärben**<!-- style="color: pink" --> die Schriftgröße<!-- style="color: turquoise; font-size: 4rem;" --> ändern.

Man kann auch <br/> Absätze erzwingen.

> "Ein Zitat kann man auch einfügen"
>
> -- sagte Jemand

<details>

<summary>Öffne mich</summary>

Hier könnte man zusätzliche Informationen einfügen.

- Oder
- auch
- eine
- Liste

> Man kann Sachen auch einfach hervorheben, ohne zu zitieren.

</details>

### Gesprochener Text

{{!> 1 Deutsch Male}}
Man kann sich Abschnitte auch vorlesen lassen

{{!> 2 Deutsch Female}}
und dafür verschiedene Sprecher verwenden

{{!> US English Male}}
which could be useful for adding paragraphs in English.[^1]

[^1]: Fußnoten sind auch möglich

## Kapitel 2 - Medien

### Bilder, Videos etc.

![Mein Bild](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg "Character sheets für Trashtalk")

**Eine Galerie mit Bildern**

Man kann innerhalb der Galerie die einzelnen Bilder inspizieren durch das Lupensymbol

![img1](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg)
![img2](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg)
![img3](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg)
![img4](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg)
![img5](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg)

---
Man kann Themen mit so einem Strich trennen.

<br/>

!?[Trashtalk](https://youtu.be/tr-nDcJQFDA "Man kann Video-URLs einfügen")

?[a horse](https://www.w3schools.com/html/horse.mp3 "Audios sind auch möglich")

?[music.youtube](https://music.youtube.com/watch?v=dLekLK_vUvI&feature=share "oder Sounds von Youtube Music")

?[soundcloud](https://soundcloud.com/glennmorrison/beethoven-moonlight-sonata "oder von Soundcloud")

---

**Eine Multimedia-Galerie**

!?[Trashtalk](https://youtu.be/tr-nDcJQFDA "In eine Galerie")
![img1](https://raw.githubusercontent.com/nisjaklaus/OER/main/CharacterDesignIdeas.jpg "kann man natürlich auch")
?[music.youtube](https://music.youtube.com/watch?v=dLekLK_vUvI&feature=share "Beschreibungen hinzufügen")

## Kapitel 3 - Diagramme etc.

### Quiz
Es gibt einen ganzen Haufen verschiedener Quiz-Arten für LiaScript

---

**Wer ließt das hier?**

[(X)] Frau Bruder
[( )] Ein Wurm
[(X)] Denise

Hierbei handelt es sich um ein Multiple- oder Single-Choice Quiz. <br/>
In diesem Fall sind zwei Antworten korrekt.

---

**Was benötigt wer?**

[   [Nuss]        (Vase)          [Kirsche]   ]
[    [X]           [ ]             [ ]     ]  Eichhörnchen
[    ( )           (X)             ( )     ]  Gespenst

---
Es gibt auch Textfeld-Antworten. <br/>
Man kann auch Hinweise angeben lassen.

<br/>

**Lieblingstestsatz der Programmierer (deutsche Version)?**

    [[Hallo Welt!]]
    [[?]] Sie sprechen gerne den ganzen Planeten an
    [[?]] Vor allem grüßen sie gerne

---
Es ist auch möglich aus Antwortmöglichkeiten wählen zu lassen

<br/>

Ein Apfel und eine Brine ergeben?

    [[ ($Nashi-Birne$) | $Holz$ | ($Obstsalat$) ]]

### Tabellen & Diagramme

Man kann Tabellen erstellen und freigeben, ob man diese als Diagramm ausgeben lassen kann und auch als welcher Typ vom Diagramm. <br/>
Hier einige Beispiele:

<br/>

<!-- data-type="PieChart" -->
| Tier        | Katze    | Maus     | Löwe   |
|:----------- | :-------:| :-------:| ------:|
| Größe in %  |   30     |    10    |   60   |
| Name        |    Tanja |     Igor |  Katze |



<!-- data-type="line" -->
| Tier        | Katze    | Maus     | Löwe   |
|:----------- | :-------:| :-------:| ------:|
| Größe in %  |   30     |    10    |   60   |
| Name        |    Tanja |     Igor |  Katze |

<!-- data-type="bar" -->
| Tier        | Katze    | Maus     | Löwe   |
|:----------- | :-------:| :-------:| ------:|
| Größe in %  |   30     |    10    |   60   |
| Name        |    Tanja |     Igor |  Katze |

### Verlinkungen
Man kann Links einfügen, entweder als [Hyperlink](https://youtu.be/tr-nDcJQFDA)

oder als QR Code:

[qr-code](https://youtu.be/tr-nDcJQFDA "Scan mich!!")

## Kapitel 4 - Ausblick

Dies waren die für das Projekt vermutlich interessantesten Features.
Man kann allerdings noch viel mehr mit LiaScript machen. <br/>
Beispielsweise lassen sich nicht nur Videos, Fotos und Sounds verlinken und einbetten. LiaScript kann weitere Formate wie beispielsweise Simulationen oder 3D-Modelle laden. <br/>
Zudem kann man in LiaScript auch mit HTML und Programmiersprachen wie JavaScript und Python arbeiten, was die Möglichkeiten natürlich stark erweitert. [Hier](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaTemplates/processingjs/master/README.md#8) ist ein Beispiel.
