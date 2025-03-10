# Chapter 4: The layout

## Useful links

  * [Steno Jig's "Learn the Steno Keyboard" Drills](https://joshuagrams.github.io/steno-jig/learn-keyboard.html)
  * [Steno Jig's Own Drills](https://joshuagrams.github.io/steno-jig/form.html)
* [Chapter 4 test](#chapter-4-test)

## Finger positions

Recall this graphic from chapter 2:

![](img/2-key-positions.png)

I recommend keeping this graphic in a convenient place to refer to. The yellow circles indicate the resting home position of your fingers. Your fingers should be curled and resting on the cracks of the keys. It's important to memorize this layout to the point that you are able to press the right key when prompted for.

The best way to go about memorizing this layout is splitting it into memorable chunks and doing a lot of drills. It's one thing to know which finger is responsible for which key(s), but the most effective way of building muscle memory for the layout is simply drilling it.

### The backspace key

From here on, you can play around with the keys and press random things to see what you get for fun. You could also jump right into the drills. In any case, it's very important to know how to backspace what Plover outputs. For this, press the asterisk key (`*`) and Plover will delete the last translation caused by the last stroke.

What's important to note is that doing so **does not delete the last word** necessarily. Try this: press the stroke `PAOEU` into a text editor. You should see the word "pie" outputted by Plover. Now, press the stroke `THOPB`. You should now see that Plover backspaces the "ie" and replaces it with "ython" to give you the word "python".

What you've just done is write a multistroke outline for the word "python"; to delete this, you will need to press the asterisk key twice. Try it out!

You can also watch this GIF:

![](img/4-python.gif)

Notice how pressing the asterisk once doesn't delete the word—it only deletes the last stroke and therefore leaves the `PAOEU` (pie) stroke alone.

For now, this isn't very crucial at the moment as the majority of words covered in these early chapters are written with one stroke. However, do keep in mind that the asterisk does not behave like a backspace key in the traditional sense.

## Steno Jig

> If you are using Javelin, make sure to read [Appendix C](Appendix-C.md#chapter-4) for instructions on setting up your keyboard with these drills.

For learning the layout, Steno Jig has some helpful ["Learn the Steno Keyboard"](https://joshuagrams.github.io/steno-jig/learn-keyboard.html) drills.

For each drill, you may choose to enable hints, which show where each key is located on the steno layout. Ultimately, you want to be able to do these drills without using any hints. Do not worry about the "Speed (strokes per minute)" parameter just yet.

If you are unsure where to start, these 5 drills are recommended (select them in the dropdown menu):

* Left hand, bottom row
* Right hand, full bottom row
* Left hand, top row
* Right hand, full top row
* Vowels

In order to do the drills, you must disable all your dictionaries by unchecking them in Plover's main window:

![](img/4-main-window.png)

Click on the check marks next to each dictionary to disable them. After you've done this, Plover will output raw steno when you write a key. Simply press the key that is prompted during the drills. If you make a mistake, press the asterisk key to backspace.

### Why does Plover output a hyphen?

With your dictionaries unchecked, try pressing the right side "T" key (or really any consonant key on the right side). You'll notice that Plover outputs `-T` with a hyphen. The hyphen indicates that this "T" is on the right side of the keyboard. If you are prompted to press `S`, you must press the "S" key on the left side. If you see `-S`, this indicates that the S is on the right side and so you must press the right side "S" key.

This hyphen is included in all strokes that contain only right hand consonant keys. If you were to press the right hand "R", "P", and "L" keys, Plover would output `-RPL`. If a stroke contains a vowel or the asterisk, however, the hyphen is omitted. This syntax of raw steno makes it easy to differentiate repeat letter keys on both sides of the keyboard.

### How should I start?

If you'd like, you can just jump right into the drills; that is a valid way to learn the layout. However, I would suggest coming up with mnemonics first just to make the memorization process a little bit easier. These should be personal as they're more likely to stick.

For example, these are some mnemonics I used when first starting off:

1. Left hand, bottom row (`SKWR`)
   * <ins>s</ins>ome <ins>k</ins>ettle <ins>v</ins>alley <ins>r</ins>ailway (`SKWR`)
     * A historical railway in my area ("v" is not quite "W", but it was close enough)

2. Right hand, full bottom row (`-RBGSZ`)
    * <ins>r</ins>ed, <ins>b</ins>lue, <ins>g</ins>reen (`RBG`)
      * Like "RGB" but not quite
   * Bottom right pinkie key is `-S` just like bottom left pinkie
   * The "Z" sound is similar to "S" and is immediately to the right of `-S`
   * `-Z` is also on the end, just like in the alphabet

3. Left hand, top row (`#TPH`)
   * ha<ins>s</ins>h is right above `S`
   * <ins>t</ins>he <ins>p</ins>ower of <ins>h</ins>ydrogen ("TPH")
     * As in the chemistry term "pH"

4. Right hand, full top row (`-FPLTD`)
   * Index <ins>f</ins>inger presses `-F`
   * <ins>p</ins>ersonal <ins>l</ins>earning <ins>t</ins>ime (`-PLT`)
     * You can also combine the previous key with this mnemonic where `-F` represents an expletive (`-FPLTD`)
   * The "D" sound is just the voiced "T" sound and is right next to `-T` (`-D`)


5. Vowels (`AOEU`)
   * <ins>a</ins>y y<ins>o</ins>, <ins>eu</ins>! (`AOEU`)
     * An individual really passionate about the European Union
   * You could also pronounce "ao" as "ow" for someone who dislikes the European Union

Clearly some of these mnemonics are rather silly (and also very specific), but that makes them easier to remember for me. I do encourage you to come up with your own! At some point, the keys will become natural to you and you will not need to recall any mnemonics. **It is at this point that you should proceed to the test.**

### Other drills

If, after a few days, you feel pretty comfortable practising the [previous drills](#steno-jig), you may want to try other practice material. The [other Steno Jig drills](https://joshuagrams.github.io/steno-jig/learn-keyboard.html) are fair game:

![](img/4-supplemental-drills.png)

The drills outside of the red box incorporate theory you have not learned yet, and are not recommended.

If you have already done these drills and are quite comfortable, I would recommend moving onto the test.

## Chapter 4 test

For this test, we will also be using Steno Jig. This time, we will be making a custom drill here:

![](img/4-custom-drill.png)

[Click here](https://joshuagrams.github.io/steno-jig/form.html) to take you to the page shown above.

Copy and paste the following into the text box:

```
SAP HUD SOG TOD WET POG ROD KUS PEB ROR WEZ WEL TER TAT WEF KAB WES SAP TAS RET TAD PEP SEB KOF TUZ PEF HEL PUB RAT WAF TAB RAS HUP WUP PEZ SOF HUR PUZ SOB POT KED WUD SAG RAP RAL ROL WOZ KAD KAT KOB RAD TAR SAL ROF SOR WOT HUF TUR KAF HOR SOD KOT SEF RED HAP PAP KEG KOZ TUS SOZ TAG HAS TAF HES HOL WUR TEB HAB HER PER TOP HAZ POL WOS HOP SUT TOR REL PAT SER WUS PUP KAG POD SUB HED SAB SUL TEF SOL
```

This test is a little different to previous drills in that you are writing entire strokes rather than single keys. Consonants on the left side of a vowel should be pressed with the left hand, and consonants on the right side should be pressed with the right hand. So `SAP` would be written like:

<steno-outline stroke="SAP" width="100%" alt="SAP on the steno layout"></steno-outline>

**It is important that you press all three keys all at once for every stroke you are prompted to write (do not press each key letter by letter).**

Select "Shuffle words" and make sure your dictionaries are also unchecked just like in previous drills. Once you have done so, you are ready to go!

### Recommended completion goal

This is only a suggestion if you are unsure of when to move on to the next chapter; it is not a strict requirement!

**You should be able to complete this test in 10 minutes or fewer with an accuracy of at least 90%.**

### Extra practice

```
KEP SAT TEP REF PUT KUR RAB KUF RAG WUT KUB ROB TUF TOT WUL WUF KEZ ROT KAZ KEF RUT PUG RAF SUR REP TUD TOS SEZ SUD KUL KAP TOZ ROZ PAB KUT PUS KOD RUG TED HOT SAS HAG HEZ SUZ WAT KUP HAT PAL HOZ POS PAD PUR KOR PAZ TEZ REZ ROS KUZ WOL TUP HUG HOB HAR RER TOG REG TUB HUL PAR TOF WUZ PUL HEG POR RUL SEL TOB KER HOF SUF RUF WUG WER RUR SAD SOT TUG REB SES HAD HOG KEB POP TES KOG HUZ KAS SAF HEB
```

```
TEL KOL POB KUD HAL TUT ROP WAD WAL TAP RES SEG WOG RUB WOP PUD WAG PED WAS PUF HET KOS WEP HOS KAR SOP RUD KOP TET HUS TOL PET HAF HEF SAZ WAR SEP SUG TUL RUP KET WOF KEL SOS HOD RAZ PES KAL WAB SUS HEP WEG SUP PEG HUB WOD KES PAF SAR PEL WEB TEG SET WOB PAS POF RAR WOR WUB POZ ROG HUT WAZ WED KUG TAZ SED RUZ TAL RUS WAP PAG
```
