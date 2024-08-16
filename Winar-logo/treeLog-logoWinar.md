# Winar INC logo treeLog

## aseprite

### blocks

![blocks](1.%20aseprite/sprites/blocks.png)

* dotmatrix-colorPalette
* blockmat
* 3blockCorner
* 3block
* 6block

### colormat

![colormat](1.%20aseprite/sprites/colormat.png)

colormat consists of 2 layers, `deck` & `keel`

diagram; <kbd>2 digit</kbd> = <kbd>binary</kbd> = `1pixel` unit

``` txt
deck
            00##**
          1100##
  11    001100    110011
0011  110011    110011
0011001100    110011
00110011    110011
001100    110011
0011    110011
00
                    keel
```

### how we did the drawing?

![gif-preview-winar](1.%20aseprite/sprites/gif-preview-winar.gif)

deck
* take 2 `6block` pillars beside each other like an increasing high line chart 📈
* take 5 `3block` pillars beside each other like an increasing high line chart 📈
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the top
* take 1 `3blockCorner` and place it beside the 3block stack
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the top

the distance between the deck & the keel = `2pixel` unit

keel
* lay down a `3block` pillar horizontally & in line with 2nd `6block` pillar
* stack 6 on top of each other like an increasing high line chart 📈
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the right

### frameart

![winar-inc_bg_r252-g252-b252](1.%20aseprite/sprites/winar-inc.png)

---

## illustrator

### blocks

![blocks](2.%20illustrator/sprites/blocks.webp)

* dotmatrix-lg-72px
* dotmatrix-dg-72px

### blockmat

![blockmat](2.%20illustrator/sprites/blockmat.webp)

* 6block
* 3block
* 3blockCorner

### colormat

![colormat](2.%20illustrator/sprites/colormat.webp)

colormat is divided into 2 groups, the deck & keel

deck:

![colormat-deck](2.%20illustrator/sprites/colormat-deck.webp)

* take 2 `6block` pillars beside each other like an increasing high line chart 📈
* take 5 `3block` pillars beside each other like an increasing high line chart 📈
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the top
* take 1 `3blockCorner` and place it beside the 3block stack
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the top

keel:

![colormat-keel](2.%20illustrator/sprites/colormat-keel.webp)

* lay down a `3block` pillar horizontally & in line with 2nd `6block` pillar
* stack 6 on top of each other like an increasing high line chart 📈
  > it is important to note that it should be aligned from the bottom with a 1 pixel gap to the right

the distance between the deck & the keel = `2pixel` unit

### rainbowmat

![rainbowmat](2.%20illustrator/sprites/rainbowmat.webp)

rainbowmat purpose:
* better view of individual squares
* better view of tracing

### cutmat

![cutmat](2.%20illustrator/sprites/cutmat.webp)

* select the outside edge squares
* cut the corner points of each squares turning them into a right-angled triangle

notice how at [how we did the drawing](#how-we-did-the-drawing), it was mentioned that "the distance between the deck & the keel = `2pixel` unit", but here we did nothing but joined the deck & keel

once done, the logo should have a tracing like this below;

![tracemat](2.%20illustrator/sprites/tracemat.webp)

### frameart

![frameart](2.%20illustrator/sprites/frameart.webp)