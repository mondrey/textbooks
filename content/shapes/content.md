# Area and Shapes

## Introduction

> section: introduction
> sectionStatus: dev
> id: performance-1

Around the world, street performers delight audiences with their up-close and engaging shows. As shown here in Covent Gardens in London, performers often lay out rope to keep audience members outside of their performing space. 

    figure: x-img(src="https://st3.depositphotos.com/1817276/19080/i/1600/depositphotos_190806246-stock-photo-london-circa-january-2018-knife.jpg" width=600 height=438)

Imagine you are a street performer and you need to lay out a red rope to mark-off your stage. Pick up the red rope below and create a stage on the cobblestones so that:

1. You rope off 200 __or more__ cobblestones.
2. You use 20 meters of rope or less.
3. The space is fully enclosed (the ends of the rope touch each other).
4. The rope does not cross over itself.\ 

\ 

    // [TODO]: INTERACTIVE-01: Performance area 1 (pages 1-2)
    figure: x-geopad(width=600 height=400)
      svg

Now, let’s focus on the shape we made out of the rope and imagine it as a shape drawn on a piece of paper. Recall that perimeter is the length of the boundary, or outside, of a shape, and area is the how much space a shape covers or encloses.

::: .reveal(when="rope-drawn")

Your shape used ${firstArea.ropeUsed.toFixed(2)} meters of rope. So, ${firstArea.ropeUsed.toFixed(2)} meters is the [[perimeter | area | volume ]] of the shape. 

Your shape roped off ${firstArea.cobblestones} cobblestones. So, ${firstArea.cobblestones} cobblestones is the  [[area | perimeter | volume ]] of the shape. 

The shape used ${firstArea.ropeUsed.toFixed(2)} meters of rope. Below, create three different performing spaces with the same length of rope.

:::

---

> id: performance-2

    // [TODO]: INTERACTIVE-02: Performance areas (page 2)
    figure: x-geopad(width=600 height=400)
      svg

You used the [[same | different]] amount of rope each time, but created shapes with [[different | the same]] number of cobblestones roped off. Different shapes with the [[same | different]] perimeter can have [[different | the same]] areas.

---

Now, let’s work on the difference between perimeter and area of a shape. Let’s think through five examples that highlight this difference.

::: column.grow
1. If we need to know how much carpet to buy to for our living room floor, we would need to find the [[area | perimeter]] of our living room floor.
::: column(width=200)
    x-img(width=200 height=133 src="https://st.depositphotos.com/1017986/4242/i/950/depositphotos_42423393-stock-photo-close-up-of-male-hands.jpg")
:::
::: column.grow
2. If we need to know much fencing is needed to surround a field, we would need to find the [[perimeter | area]] of the field.
::: column(width=200)
    x-img(width=200 height=132 src="https://st.depositphotos.com/1653005/3304/i/950/depositphotos_33047243-stock-photo-horse-stables.jpg")
:::
::: column.grow
3. If we need to know how much ribbon we need to decorate the outside a mirror, we would need to find the [[perimeter | area]] of the mirror.
::: column(width=200)
    x-img(width=200 height=200 src="https://st2.depositphotos.com/1192512/5199/v/950/depositphotos_51997521-stock-illustration-big-mirror-with-blurry-reflection.jpg")
:::
::: column.grow
4. If we need to determine how much coastline there is of an island, we would need to find the [[perimeter | area]] of the island.
:::
::: column.grow
5. If we need to know how much material is needed to replace the floor of a gym, we would need to find the [[area | perimeter]] of the gym.
::: column(width=200)
    x-img(width=200 height=133 src="https://static3.depositphotos.com/1006422/205/i/950/depositphotos_2050132-stock-photo-the-gymnasium.jpg")
:::

---

Football clubs often need to replace the grass field after it has been worn down. In 2018, the Estadio Azteca in Mexico City looked like this before the field was replaced.

    figure: x-img(width=600 height=450 src="https://pbs.twimg.com/media/Dr505QhUcAAkArx?format=jpg&name=medium")

Clubs often choose between squares of grass or artificial turf to replace the worn down grass:

::: column(width=300)
    x-img(width=300 height=199 src="https://st.depositphotos.com/1022214/2042/i/950/depositphotos_20421735-stock-photo-artificial-turf.jpg")
::: column(width=300)
    x-img(width=300 height=219 src="https://st3.depositphotos.com/1011434/14373/i/1600/depositphotos_143733669-stock-photo-gardener-applying-turf-rolls.jpg")
:::

---

> id: grass-placement

Below is a picture of a worn out football field. Drag new squares of grass onto the worn out field below to model replacing the grass.

    // [TODO]: INTERACTIVE-03: Field grass placement (page 6)
    figure: .grass-placement.rect-placement
      x-img(width=525 height=350 src="https://static4.depositphotos.com/1008169/329/i/950/depositphotos_3297355-stock-photo-grunge-soccer-field.jpg")
      x-polypad(rotate="no")

Let’s make an estimate of how many squares of grass we’ll need to replace the field. Just look at the picture of the field and make a quick guess. Enter the guess here: [TODO]

::: column.grow
Since it is a square and each side length is 1 [[meter | centimeter | kilometer]], we call this shape a square meter.
::: column(width=200)
    // [TODO]: DIAGRAM-01: Turf square (page 6)
:::

Recall your estimate of the [[area | perimeter ]] of the field is ____ [[square meters | meters | square centimeters]]. We’ll find out later in this chapter how close your estimate is!

---

> id: strip-placement

Now that the new grass is in place, we need to paint the lines on the field.

    figure: x-img(width=600 height=400 src="https://artificialgrassrecyclers.com/wp-content/uploads/2017/04/painting-turf.jpg")

Drag each strip of white onto the field to model painting a while line around the field. One white strip equals one can of paint.

    // [TODO]: INTERACTIVE-04: Field stripes placement (page 7)
    figure: .strip-placement.rect-placement
      div.field(style="width:525px;height:350px;position:absolute;margin-left:75px;background-color:green")
      x-polypad(rotate="no")

Make an estimate of how many cans of paint we’ll need to paint a line around the outside of the field. Just look at the picture of the field and make a quick guess. Enter the guess here: [TODO]

Each can of paint can make a line 1 meter long. Recallyour estimate of the [[perimeter | area ]] of the field is ___ [[meters | square meters | centimeters]]. Again, we’ll find out later how close your estimate is.

---

> id: centimeters

Now, let’s move on to thinking more deeply about the area of rectangles. Below are a bunch of square centimeters. Remember, these are squares whose sides lengths are each [[1]] centimeter long. Drag square centimeters into the rectangle so you fill in the rectangle.

    // [TODO]: INTERACTIVE-05: Rectangle squares (pages 8-9)
    figure: x-geopad(width=600 height=400)
      svg

This rectangle has [[3]] rows, and every row has [[5]] squares, so we used 3 x 5 = [[15]] squares in total. 

Each square is one square centimeter, so the [[area | perimeter]] of this rectangle is [[15]] [[square centimeters | centimeters | square meters]]. 

Again, the length of the side of each square is [[1]] centimeter. So we know, the length of the base of the rectangle is [[5]] centimeters and the length of the height of the rectangle is [[3]] centimeters. The perimeter of the rectangle is [[16]] [[centimeters | square centimeters]].

---

Before we continue on with area and perimeter, let’s discuss some commonly used units for perimeter and area. In this chapter, we’ll use centimeters, meters and kilometers. 

A centimeter is about the [[width of a staple | length of a guitar | distance of about two laps around a track]]. 

A meter is about the [[length of a guitar | width of a staple | distance of about two laps around a track]]. 

A kilometer is about [[distance of about two laps around a track | length of a guitar | width of a staple]]. 

---

Area is the amount of space inside an object., To determine the area of a shape, we’ve been filling up the space inside an object with squares. We could use other shapes as well. You can study that idea in a chapter on tessellations.

Square meters are squares with side lenghts of [[1]] [[meter | centimeter | kilometer]], and square centimeters are [[squares | circles | triangles]] with side lenghts of [[1]] [[centimeter | meter | kilometer]]. So, a square kilometer is a square with side lengths of [[1]] [[kilometer | meter | centimeter]]. 

When we talk about a certain number of square meters, say 7 of them, we can write it as “7 square meters” or “7 m2”. In fact, the “m2’ is read as “meters squared.” Any power of “2” is often read as “squared.” For example,  we can read92 as “9 squared” because we would need to multiply 9 x 9 when finding the [[area | perimeter]] of a square with side length 9. 

---

Sort the units of measure below into those that measure length and those that measure area:

    // [TODO]: INTERACTIVE-06: Measurement units (pages 10-11)

Now, sort the units of measure for area. Each unit of measure is represented in three different ways. Drag each of the labels into the correct square.

---

> id: half-meters

Below is a square meter and a bin of squares that are ½ meter on each side. See how many ½ square meters you need to fill in the square meter:

    // [TODO]: INTERACTIVE-07: Square meter filling (pages 11-12)
    figure: x-geopad(width=600 height=400)
      svg

It takes [[4]] ½ square centimeters to fill in 1 square meter. So, the area of a square with a ½ meter on each side is [[¼]] of the area of 1 square meter.

---

Let’s apply our understanding of area to another example. Begin exploring the area of the rectangle below by dragging in any 3 of the area shapes on the left into the blue rectangle.

    // [TODO]: INTERACTIVE-08: Rectangle filling (pages 12-13)

Let’s see if we can determine the area of the blue rectangle. The base is [[3.5]] centimeters long and the height is [[2.5]] centimeters long. The area of the rectangle is [[8 ¾]] [[square centimeters | centimeters | square meters]].

---

The area of the rectangle is 8 ¾ square centimeters.

    // [TODO]: ANIMATION-01: Rectangle area (page 14)

---

Our first area example has 3 rows of  5 square centimeters each for a total of [[15]] [[square centimeters | centimeters]]. 3 x 5 = [[15]].

This example has [[2 ½]] rows of 3 ½ square centimeters. So, to find the area we could do [[ 2 ½ x 3 ½ ]] which does indeed equal [[8 3/4]]. 

If you forget how to calculate 2 ½ x 3 ½, you can review the chapter on Multiplying and Dividing Fractions. 2 ½ x 3 ½ means 2 ½ groups of 3 ½.

---

    // [TODO]: ANIMATION-02: Areas (pages 15-16)

This arrangement looks familiar! 2 ½ x 3 ½ = [[8 ¾]].

---

So, by counting the number of rows and number of columns, and [[multiplying | adding | subtracting | dividing]] those numbers, we have found the formula for the area of any [[rectangle | circle | triangle]]. 

Area of Rectangle = number of units along the base [[ x | + | -]] number of units along the [[height | diagonal]]. We can abbreviate this formula as:

Area of Rectangle = base  [[ x | + | -]] [[height | base | diagonal]].

---

    // [TODO]: DIAGRAM-01: Rectangle area (page 16)

Let’s think about the perimeter of this same rectangle. Below are some calculations using the side lengths of the rectangle above. Sort the calculations into those that will give you the correct perimeter and those that will not.

    // [TODO]: INTERACTIVE-09: Area calculation sorting (page 17)

---

The perimeter of the rectangle is [[12]] [[centimeters | square meters | square centimeters]].

---

Let’s end this chapter by coming back to our work with the football field. You guessed the area of the field to be  ____ [[square meters | meters]]. Below is the image of the field as well as a picture of your estimation:

    // [TODO]: DIAGRAM-02: Field rectangle comparison (page 17)

It seems that your estimate of the area was [[too big | too small].

---

Now, let’s find the actual area of the football field.

    // [TODO]: DIAGRAM-03: Field dimensions (page 18)

The length of the base is [[110]] [[meters | square meters]] and the length of the height is [[75]] [[meters | square meters]]. This means, we would need [[75]] rows of [[110]] pieces of square meter grass to cover the field. To calculate the area, we need to multiply [[110 x 75]]. This gives us an area of [[8250]] [[square meters | meters]]. Your estimate was ____ square meters away.

---

Let’s revisit your perimeter guess. You guessed the perimeter of the field to be ____ [[ meters | square meters]]. Below is a picture of the field as well as a field with your estimated perimeter.

    // [TODO]: Talk to Philipp about the end of this chapter (I'm not sure what to include)

---

## Parallelograms and Triangles

> section: parallelograms-triangles
> sectionStatus: dev

[TODO]

---

## Polygons

> section: polygons
> sectionStatus: dev
> id: voronoi-1
> goals: eight-points

School districts need an accurate estimate of the number of students that may attend their schools. Below is a map of primary schools in London. In general, students attend the school closest to where they live. Click anywhere on the map to see the distance between that point and all the schools on the map.

    figure: x-geopad(width=600 height=400)
      img(src="images/map-temp.png" width=600 height=400)
      canvas(width=600 height=400)
      svg

{.reveal(when="one-point")} Pick 4 other points on the map.

{.reveal(when="five-points")} _{button.btn.show-voronoi} Create voronoi diagram_

{.reveal(when="voronoi-diagram")} We’ve just made a Voronoi diagram. Each region contains all the points on the map that are closest to the school in that region. Click a few spots in different regions to check.

---

The first person to think about these things was probably [Rene Descartes](bio:descartes) 400 years ago - he was a famous philosopher too!  But they’re named after a Russian mathematician, [Gregory Feodosevich Voronoy](bio:voronoy). Physician John Snow used a version of a Voronoi diagram in 1854 during a [cholera epidemic](https://plus.maths.org/content/uncovering-cause-cholera) In London to locate an infected water pump on Broad Street in London 

In our example, using a Voronoi diagram can help schools make estimates of how many students will attend. In London, about 1500 people live in each square kilometer. To use this statistic, we first need to first know the [[area | perimeter]] of each region in the diagram.

---
> id: voronoi-2

    figure: x-geopad(width=600 height=400)
      svg

Some of these regions are shapes we’ve learned about in previous chapters. [This shape](->.triangle-cell) is a triangle and we can find the area by doing [[1/2]] x base x height.

{.reveal(when="blank-0")} Click on the side of the triangle you want to use as the base.

{.reveal(when="side-selected")} Now draw in the height that corresponds with the base you selected.

{.reveal(when="height-drawn")} The area of this triangle is [TODO] [[0]] [[square km | km]].

{.text-center.reveal(when="blank-1 blank-2")} `(1500 "\ people") / (1 "\ square km") = (input(0) "\ people") / ([TODO] "\ square km")`

---
> id: voronoi-3

[TODO] people live closest to that school and that can be a good starting point for the school to use to estimate how many students might attend that school. Next, the schools would want to use other statistics to estimate how many of those people are elementary aged students.

The other regions are more complicated. Some have [4 sides](->.four-sided). Some have [5 sides](->.five-sided). And some have [6 sides](->.six-sided).

    // [TODO]: Probably don't need geopad for this
    figure: x-geopad(width=600 height=400)
      svg

---
> id: sort-polygons
> goals: cards-sorted

All of these regions in the Voronoi diagram are examples of polygons. A polygon is a closed, two-dimensional shape with straight sides that do not cross each other. A polygon does not have any holes in the shape. Click on a card below and drag it to the “Polygon” or “Non Polygon” side.

    include ../shared/components/binary-swipe

::: x-binary-swipe(a-title="Polygons" b-title="Not Polygons")
      
{div.card.c-red(solution="a" comment="polygon-regular")} Card #1 - Regular Polygon

{div.card.c-teal(solution="b" comment="not-polygon-curved")} Card #2 - NOT a Polygon

{div.card.c-green(solution="b" comment="not-polygon-hole")} Card #3 - NOT a Polygon

{div.card.c-orange(solution="a" comment="polygon-irregular")} Card #4 - Irregular Polygon

{div.card.c-blue(solution="a" comment="polygon-irregular")} Card #5 - Irregular Polygon

{div.card.c-yellow(solution="b" comment="not-polygon-closed")} Card #6 - Not a polygon

{div.card.c-teal(solution="a" comment="polygon-regular")} Card #7 - Regular polygon

{div.card.c-orange(solution="b" comment="not-polygon-crossing")} Card #8 - Not a Polygon

{div.card.c-blue(solution="b" comment="not-polygon-curved")} Card #9 - Not a polygon

{div.card.c-red(solution="a" comment="polygon-irregular")} Card #10 - Irregular Polygon

{div.card.c-purple(solution="a" comment="polygon-voronoi")} Card #11 - Polygon

:::

---

A regular polygon has [[all equal | all different]] side lengths.

---
> id: populations

Let’s revisit the Voronoi diagram and find out how many people live in one of the regions with 5 sides. Note the [region outlined in white](->.population-pentagon) in the image below.

    // [TODO]: Voronoi region area exercise
    figure: x-geopad(width=600 height=400).voronoi-1
      svg

Just by looking at this region, it seems that [[more | less]] students will attend the school in this region than the school in the triangular region we explored above. The region looks similar in size, so it’s hard to be sure just by looking. Let’s find its area by splitting it up into rectangles and triangles and compare the area to the area of the triangular region.

::: .reveal(when="blank-0")

| The total area is equal to the area of the rectangle plus the area of [[2]] triangles. | Total Area = Area of Rect + Area of Triangle 1 + Area of Triangle 2 |
| Area of a rectangle = b x h and Area of a triangle = [[½]] x b x h | Total Area = b x h + ½ x b x h + ½ x b x h |
| Click on the base and height of the rectangle | Total area = # x # + ½ x b x h + ½ x b x h |
| Click on the base you want to use for triangle #1 and then draw in the corresponding height. | Total area = # x # + ½ x # x # + ½ x b x h |
| Click on the base you want to use for triangle #2 and then draw in the corresponding height. | Total area = # x # + ½ x # x # + ½ x # x #Calculate the area of each shape |
| Calculate the area of each shape | Total area = [[#]] + [[#]] + [[#]] |
| Calculate the total area | Total area = [[#]] sq km |

:::

{.reveal(when="area-calculated")} [TODO]: People equation

{.reveal(when="people-calculated")} So, indeed more students will likely attend the school in the pentagon region than the triangular region.

---
> id: polygon-names
> goals: names-matched

We give different names to polygons based on how many sides they have. You may remember some of the names. Drag the names on top of the correct shapes.

    include ../shared/components/relation
    x-relation
      .item(slot="domain" match="5") Pentagon
      .item(slot="domain" match="6") Hexagon
      .item(slot="domain" match="7") Septagon/Heptagon
      .item(slot="domain" match="8") Octagon
      .item(slot="domain" match="9") Nonagon
      .item(slot="domain" match="10") Decagon
      .item(slot="range" name="5") 5 sides
      .item(slot="range" name="6") 6 sides
      .item(slot="range" name="7") 7 sides
      .item(slot="range" name="8") 8 sides
      .item(slot="range" name="9") 9 sides
      .item(slot="range" name="10") 10 sides

---
> id: jerusalem

### Polygons in real life

Let’s practice using these names by looking at some examples of polygons out in the world.

The Dome of the Rock is an Islamic Shrine in the Old City of Jerusalem. Built in 692 BCE, the base is a regular [[octagon | pentagon | hexagon]].

::: column(width=300)

    x-img(src="https://static4.depositphotos.com/1010232/271/i/950/depositphotos_2712874-stock-photo-dome-of-the-rock-jerusalem.jpg" width=300 height=199)

::: column(width=300)

    x-img(src="https://ak7.picdn.net/shutterstock/videos/20482537/thumb/8.jpg" with=300 height=169)

:::

---
> id: giants-causeway

The Giant’s Causeway in Northern Ireland is made up of over 40,000 polygonal basalt (a type of igneous rock) columns sticking out of the sea. The column outlined in white in [the photo](->.column-photo) is a [[hexagon | pentagon | octagon]].

::: column(width=300)

    x-img(src="https://st2.depositphotos.com/1457640/9876/i/950/depositphotos_98761548-stock-photo-giants-causeway-and-cliffs-in.jpg" width=300 height=200)

::: column(width=300)

    object(type="image/svg+xml" data="/resources/shapes/images/giants-causeway-shape.svg" width=300 height=219).column-photo

:::

---
> id: signs

Most traffic signs are polygons - some regular and some irregular:

::: column(width=160 parent="padded-thin")

    // https://depositphotos.com/9417440/stock-illustration-set-of-14-highway-sign.html
    x-img(src="images/sign-1.jpg" width=160 height=160)

{.caption} [[Regular Octagon | Regular Hexagon | Regular Pentagon]]

::: column(width=160)

    x-img(src="images/sign-2.jpg" width=160 height=160)

{.caption} [[Irregular | Regular]] pentagon

::: column(width=160)

    x-img(src="images/sign-3.jpg" width=160 height=160)

{.caption} Regular triangle

::: column(width=160)

    x-img(src="images/sign-4.jpg" width=160 height=160)

{.caption} Regular [[quadrilateral | triangle | diamond]]

:::

---
> id: animals

Polygons show up in all sorts of natural objects - honeycomb and starfish - to name a few. The
10-sided starfish is a [[decagon | nonagon | octagon]]:

::: column(width=300)

    x-img(src="https://static8.depositphotos.com/1491329/1068/i/950/depositphotos_10680850-stock-photo-worker-bees-on-honeycomb.jpg" width=300 height=199)

::: column(width=300)

    x-img(src="https://st.depositphotos.com/1054213/2023/i/950/depositphotos_20238089-stock-photo-starfish-asterias-rubens.jpg" width=300 height=200)

:::

---
> id: nature-voronoi

The ground of a dried out desert, the skin patterns on giraffes, and dragonfly wings look strikingly similar to Voronoi diagrams!

::: column(width=150)

    x-img(src="https://static9.depositphotos.com/1013513/1148/i/950/depositphotos_11488218-stock-photo-drought-land-and-hot-weather.jpg" width=150 height=100)

::: column(width=150)

    x-img(src="https://static5.depositphotos.com/1011160/517/i/950/depositphotos_5177840-stock-photo-texture-of-dry-cracked-soil.jpg" width=150 height=100)

::: column(width=150)

    x-img(src="https://st.depositphotos.com/1594920/1698/i/950/depositphotos_16982455-stock-photo-somali-giraffe-commonly-known-as.jpg" width=150 height=109)

::: column(width=150)

    x-img(src="https://static3.depositphotos.com/1003348/177/i/950/depositphotos_1773326-stock-photo-dragonfly.jpg" width=150 height=100)

:::

---
> id: flags
> goals: flags-matched

Lastly, many flags use polygons. Drag the name of each country to the correct flag. Just make a guess if you’re not sure!

    x-relation
      .item(slot="domain" match="canada" comment=true)
        object(type="image/svg+xml" data="https://upload.wikimedia.org/wikipedia/commons/d/d9/Flag_of_Canada_%28Pantone%29.svg")
      .item(slot="domain" match="south-africa" comment=true)
        object(type="image/svg+xml" data="https://upload.wikimedia.org/wikipedia/commons/a/af/Flag_of_South_Africa.svg")
      .item(slot="domain" match="finland" comment=true)
        object(type="image/svg+xml" data="/resources/shapes/images/finland.svg")
      .item(slot="domain" match="nepal" comment=true)
        object(type="image/svg+xml" data="https://upload.wikimedia.org/wikipedia/commons/9/9b/Flag_of_Nepal.svg")
      .item(slot="range" name="canada") Canada
      .item(slot="range" name="south-africa") South Africa
      .item(slot="range" name="finland") Finland
      .item(slot="range" name="nepal") Nepal

---
> id: poly-verts
> goals: verts-moved

The hexagons in the South African flag and the pentagon in the Nepalese flag may not appear to be the standard image you may have in your head of a pentagon and a hexagon. Move around the vertices (these are the points where the edges meet) in the regular polygons below to make some irregular polygons of your own.

::: column.grow(width=220)

    // pentagon
    x-geopad(width=220 height=220): svg
      circle.move(name="a" cx=16.304 cy=71.944)
      circle.move(name="b" cx=119.065 cy=15.526)
      circle.move(name="c" cx=204.477 cy=95.823)
      circle.move(name="d" cx=154.503 cy=201.868)
      circle.move(name="e" cx=38.206 cy=187.109)
      path(name="pentagon" x="polygon(a,b,c,d,e)")

::: column.grow(width=220)

    // hexagon
    x-geopad(width=220 height=220): svg
      circle.move(name="f" cx=17.191 cy=123.874)
      circle.move(name="g" cx=51.786 cy=35.629)
      circle.move(name="h" cx=145.507 cy=21.466)
      circle.move(name="i" cx=204.632 cy=95.55)
      circle.move(name="j" cx=170.037 cy=183.795)
      circle.move(name="k" cx=76.316 cy=197.958)
      path(name="hexagon" x="polygon(f,g,h,i,j,k)")

::: column.grow(width=220)

    // octagon
    x-geopad(width=220 height=220): svg
      circle.move(name="l" cx=202.682 cy=93.196)
      circle.move(name="m" cx=163.59 cy=31.852)
      circle.move(name="n" cx=92.572 cy=16.119)
      circle.move(name="o" cx=31.229 cy=55.21)
      circle.move(name="p" cx=15.495 cy=126.229)
      circle.move(name="q" cx=54.587 cy=187.572)
      circle.move(name="r" cx=125.605 cy=203.306)
      circle.move(name="s" cx=186.948 cy=164.214)
      path(name="octagon" x="polygon(l,m,n,o,p,q,r,s)")

:::

---
> id: simple-tangram
> goals: tangram-complete

### Tangram

Below are 7 polygons. Move and rotate the polygons to completely fill in the square

    figure: .tangram
      .simple-tangram-bg
      x-polypad

::: .reveal(when="tangram-complete")

The set of these 7 polygons is called a tangram. The tangram is an ancient Chinese puzzle invented over 1,000 years ago during the Song Dynasty. In Chinese, the puzzle is called 七巧板. Pronounced “Chi-Chiao Pan,” this translates to “the seven intriguing pieces.” The goal of the puzzle is to use all 7 pieces to form any number of images. Below are just some of the shapes you can try to make at the [Tangram](https://mathigon.org/tangram) activity on Mathigon!

    // [TODO]: Image

In 1815, Shan Chiao published “New Figures of the Tangram” which contained 374 tangram puzzles!

:::

---
> id: football-polygons

### Area of Polygons

Now that we have a firm understanding of polygons, let’s revisit thinking about the area of polygons. The football below is made up of 12 black [[pentagons | hexagons | octagons]] and 20 white [[hexagons | pentagons | octagons]]. The mathematical name for this is 3D shape is a truncated icosahedron. A football is slightly more rounded than a true truncated icosahedron since the pentagons and hexagons bulge out due to the air pressure inside.

    // [TODO]: Image

Most footballs are made of synthetic leather. Manufacturers make so many footballs that they pay great attention to the amount of synthetic leather they need to produce each football. Let’s find the amount of synthetic leather needed to make one professional football.

    // [TODO]: Football 'unfolding' animation

    // [TODO]: Pentagon and hexagon diagram/animation

| A football is made up of [[12]] pentagons and [[20]] hexagons | Total Area = 12 pentagons + 20 hexagons |
| Let’s split the pentagon into [[5]] congruent triangles and the hexagon into [[6]] congruent triangles..  Note - at this point, the triangles will appear on the pentagon and hexagon | Total Area = 12 x (Area of 5 triangles) + 20 x (Area of 6 triangles) |
| The area formula for a triangle is [[½]] x base x height. | Total area = 12 x (5 x ½ x b x h) + 20 x (6 x ½ x b x h) |
| In the pentagon, click on the side you want to use as the base and then draw in the height. | Total area = 12 x  (5 x ½ x 4.56 x 3.138) + 20 x (6 x ½ x b x h) |
| Calculate the area of one pentagon and one hexagon | Total area = 12 x [[35.7732]] + 20 x [[54.0223]] |
| Calculate the area of the 12 pentagons and the 20 hexagons | Total area = [[429.28]] + [[1080.45]] |
| Calculate the total area | Total area = [[1509.73]] square cm |
{.grid}

Recently, football manufacturers have begun to experiment with different shaped panels other than hexagons and pentagons. Here are some of the official footballs from the recent men’s World Cup tournaments.

::: column(width=160 parent="padded-thin")

    // https://commons.wikimedia.org/wiki/File:Teamgeist_Ball_World_Cup_2006_Brazil_vs._Croatia.jpg
    x-img(src="images/ball-2006.jpg" width=160 height=160 credit="Jürgen Siebert, CC-BY-SA")

{.caption} 2006 World Cup

::: column(width=160)

    x-img(src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Jo%27bulani.jpg" width=160 height=160)

{.caption} 2010 World Cup

::: column(width=160)

    x-img(src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Deutsches_Fu%C3%9Fballmuseum_2015_3.jpg/1280px-Deutsches_Fu%C3%9Fballmuseum_2015_3.jpg" width=160 height=160)

{.caption} 2014 World Cup

::: column(width=160)

    x-img(src="https://upload.wikimedia.org/wikipedia/commons/5/50/Adidas_Telstar_18_in_Russia_vs._Argentina.jpg" width=160 height=160)

{.caption} 2018 World Cup

:::

While these designs are creative and interesting, some studies have shown that the different shaped panels impact how the ball travels through the air!

---
> id: area-methods

Below is a polygon from a different Voronoi diagram. Each grid represents 1 square kilometer. Let’s find the area of this region in a few different ways.

    // [TODO]: Polygon image

    // [TODO]: Polygon area methods exercise

No matter which approach we take, the area of the pentagon is 27.5 square units!

---
> id: currys-paradox-1
> goals: blank-0 blank-1 triangle-rearranged triangle-slid

### Curry’s Paradox

Throughout our work on area, we have often used the idea that as parts of a shape are moved around, the area stays the same - as long as the pieces don’t overlap and all the pieces are used.

    figure: .triangle-tangram
      svg.solution-outline
      x-polypad(rotate="no")
    x-gesture(target=".triangle-tangram x-polypad svg" slide="25,325" offset="-50, -150")

{.reveal(when="triangle-complete")} We’ve made a triangle with a base of 13 units and a height of 5 units. The area of this triangle is [[32.5]] square units. So, the area of these 4 pieces must also be [[32.5]] square units.

::: .reveal(when="blank-0 blank-1")

    x-slider(steps=1000 speed=1 continuous).rearrange-triangle

:::

{.reveal(when="triangle-rearranged")} This triangle also has a base of [[13]] and a height of [[5]] so the area of the triangle has stayed the same at 32.5 square units. However, now it seems the area of the 4 pieces is one [[less than | more than]] the area of the triangle! How can this be when we expect the area of shapes to stay the same when we move them around? Move the slider back and forth to see this again.

---
> id: currys-paradox-2
> goals: blank-0 blank-1 blank-2 blank-3 blank-4

This situation is called Curry’s Paradox. A paradox is a statement or situation that contradicts itself. This paradox, created by American mathematician [Haskell Curry](bio:curry), is that the area of the 4 pieces first seemed to equal 32.5 square units and then they seem to equal 31.5 square units!

Let’s take the shape apart and find the area of each piece to help us see what’s happening here. 

    figure: .tangram-polys
      x-polypad(rotate="no")

The red triangle has a base of 8 and a height of 3, so the area of the red triangle is [[12]] square units. The area of the blue triangle is [[5]] square units. The area of the green hexagon is [[8]] square units and the area of the orange hexagon is [[7]] square units. So, the total area of all the pieces when pulled apart is [[32]] square units. However, in the first arrangement, they seem to make a triangle with an area of 32.5 square units and in the second arrangement, they seem to have an area of 31.5 square units. The area of these 4 pieces seems to be changing as we are moving them around! What is going on here?

---
> id: currys-paradox-3
> goals: first-zoom


Well, it turns out that neither of the shapes we made using the 4 pieces are in fact triangles. Below is the 1st arrangement. It looks like the red and blue triangles line up perfectly, but they do not. Move the slider below to zoom in on the green line connecting the corners of two triangles.

    figure: .zoom-1
      x-polypad(rotate="no")
    x-slider(steps=1000 speed=1 continuous).zoom-s-1

---
> id: currys-paradox-4

While the blue and red seem to line up so the ends connect with a straight line, they do not.  Using the formula ½ x b x h to find the area of this [shape](->.paradox-poly) made by the 4 pieces is incorrect because the shape [[is not | is]] a triangle. The area of this shape is 32 square units. Using ½ x b x h, we got 32.5 square units. The extra ½ unit came from the amount of space in between the green line and the actual line connecting the endpoints of the red and blue triangle.

    figure: .triangle-ref
      x-polypad(rotate="no")

---
> id: currys-paradox-5
> goals: second-zoom

In the 2nd arrangement, the shapes also seem to make a triangle with the same total area, but we’ve used one additional square unit. So, our first thought was that the area of these 4 shapes decreased by one. Move the slider below to zoom in on the green line connecting the corners of two triangles.

    figure: .zoom-2
      x-polypad(rotate="no")
    x-slider(steps=1000 speed=1 continuous).zoom-s-2

---
> id: currys-paradox-6

Adding the extra square unit into this arrangement of the 4 pieces causes the triangles to bulge outside of the green line. So, this arrangement is not a triangle either! The total area of the pieces is remaining constant at 32!

So, we’ve made sense of this paradox. The area of the green triangle is 32.5 square units and the area of the 4 pieces is 32 square units. The pieces do NOT fit perfectly inside the triangle. When we tried just using the 4 pieces, we still had ½ of a square unit to fill in within the triangle. At first, we just didn’t notice the ½ of the square unit missing.

    figure: .paradox-comparison
      x-polypad(rotate="no")

In the second arrangement, we added in an additional square unit to make the 4 pieces fit inside the green triangle. Again, it seemed to fit, but it actually was ½ square unit too big. Our eyes just couldn’t perceive the extra ½ square unit. 

Phew! Our fundamental idea that the area of shapes remains the same regardless of the arrangement of the shapes remains true. We’ll use this idea to explore circles in the next few chapters.

---

## Circles and Circumferences

> section: circles
> sectionStatus: dev

In the previous chapters, we’ve been exploring and learning about shapes with straight side lengths. Of course, many interesting items - all sorts of foods, entertaining attractions, objects in nature, and tires, just to name a few - all have curved edges.

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1689882/1219/i/950/depositphotos_12195072-stock-photo-grapefruit-isolated-on-white-background.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://static3.depositphotos.com/1005504/200/i/950/depositphotos_2003912-stock-photo-london-eye.jpg"  width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1872017/1625/i/950/depositphotos_16253565-stock-photo-top-view-of-pizza-margherita.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1001469/2018/i/950/depositphotos_20187853-stock-photo-automobile-tire-isolated-on-white.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://lh3.googleusercontent.com/ur9ajZgRO1ENrL4gl5CrRuMe2DOucBJoKeFP7wsgNqv6axRuCqDOUoM7xVufuSeQf0uGITvFzT5li2WE05052xknJMMRiv_HNquH6gGTFnYYzL-p4PmlMHLDL82-0ufc9kwEH16b" width=110 height=110)

:::

As you likely know, a circle is the line connecting all points that are the same distance away from a center point.

    // ANIMATION-01: Construct circle

The Indianapolis Motor Speedway in Indiana in the United States is one of the most well-known race tracks in the world.

::: column.grow(width=350)

    x-img(src="https://st3.depositphotos.com/2942339/35223/i/1600/depositphotos_352234002-stock-photo-indianapolis-circa-march-2020-gate.jpg" width=350 height=255)

::: column.grow(width=350)

    x-img(src="https://image.shutterstock.com/z/stock-photo-may-indianapolis-in-helio-castroneves-of-brazil-heads-through-the-turns-to-practice-1407372011.jpg" width=350 height=257)

:::

The Indianapolis 500 is the most famous race at the track. In this race, cars must drive 500 miles. This race began in 1911 and it is the world's oldest car race still taking place today. Teams supporting the drivers must change the times many times during a race. The rubber on the tires wears out quickly because of the heat that is generated when driving at high speeds. The tires need to be changed after about 52,000 revolutions. While this may seem like a lot, the average tire on a car can last upwards of [[31,000,000 | 310,000, 3,100,000]] revolutions.

Drivers make pit stops during the race to have the tires changed and refuel.

::: column(width=560)

    iframe(width="560" height="315" src="https://www.youtube-nocookie.com/embed/ql5h00xcHLQ" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

:::

Teams need to know when to make a pit stop. If they wait too long and wear out the tires, their speed will decrease and they’ll run the risk of this happening...

::: column(width=560)

    iframe(width="560" height="315" src="https://www.youtube-nocookie.com/embed/ZMZJ3ZaEcIQ" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

:::

---
> id: wheels

Let’s try to determine the number of laps the cars can go before a pit stop is needed. To answer this, we need to think about how far a tire travels in one revolution. Below are 4 vehicles with very different tire sizes. Move each vehicle so the tire makes one full rotation.

    // INTERACTIVE-01: Wheel distances (page 3)

    figure: .wheel-distances
      include svg/wheels.svg
      button.btn.reset Reset

---

The distance the vehicle travels in one revolution of the tire is the same as the distance [[around | across]] the tire. In general, distance around a shape is the [[perimeter | area]] of the shape. However, the perimeter of a circle has a unique name - the circumference.

    // DIAGRAM: Tire and track

To determine how far the car goes in one revolution of the tire, we need to know the [[circumference | area ] of each tire. We also need to know the length of each lap. The straight-aways are simple enough. However, each of the four turns come together to form a [[full | half]] circle, so we’ll also need a way to calculate the distance around that full circle.

We could use a piece of string and a ruler to determine the distance around a tire. Or we could use some sort of flexible measuring tool. Or we could walk around a circular track to determine the distance. However, it would be helpful if there was some relationship between the straight distance across a circle and the distance around a circle. Straight lines are much easier to measure with tools such as rulers and tape measures. We are going to explore this idea in this chapter.

---
> id: encasement-estimation
> goals: eight-sides

In our previous geometry chapters, we used what we had learned about earlier shapes to help us with new ones. For example, we re-arranged parallelograms into rectangles to understand how to find the area of parallelograms. Let’s first find an estimate of the distance around the tire by using what we know about the perimeter of polygons. Place the square around the circle so it totally encloses the circle.

    // INTERACTIVE-02: Tire circumference estimation (page 5)

    figure: .tire-circumference
      img(src="https://st.depositphotos.com/1001469/2018/i/950/depositphotos_20187853-stock-photo-automobile-tire-isolated-on-white.jpg")
      svg

The tire fits inside the square, so the circumference of the tire is [[less than | more than]] the perimeter of the square. The perimeter of the _{span.shape-name}square_ is [[108]] cm so the distance around the tire is less than 108 cm.

    // [TODO]: consider using inline variable slider instead
    x-slider.tire-encasement.reveal(steps=4 when="blank-0 blank-1")

---

As we increase the number of sides of the polygon, our estimate gets closer and closer to the distance around the tire. This process helps get a good estimate of the circumference around a circle. But what if we need to be exact? Can we use the straight lines in a circle to help find the circumference? Before exploring this further, let’s learn some of the names of the parts of a circle.

The RADIUS of a circle is a line from the center of the circle to a point on the circle. The DIAMETER of a circle is a line connecting two points on the circle that passes through the center point.

    // DIAGRAM: Radius and diameter

---

> id: radii-diameters
> goals: radii-diameters-drawn

Draw 3 radii (this is the plural for radius!) and 3 diameters on the circle below: 

    figure: x-geopad(width=400 height=400)
      svg

---

Now, let’s identify parts of a circle in the objects below:

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1689882/1219/i/950/depositphotos_12195072-stock-photo-grapefruit-isolated-on-white-background.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://static3.depositphotos.com/1005504/200/i/950/depositphotos_2003912-stock-photo-london-eye.jpg"  width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1872017/1625/i/950/depositphotos_16253565-stock-photo-top-view-of-pizza-margherita.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://st.depositphotos.com/1001469/2018/i/950/depositphotos_20187853-stock-photo-automobile-tire-isolated-on-white.jpg" width=110 height=110)

::: column.grow(width=110)

    x-img(src="https://lh3.googleusercontent.com/ur9ajZgRO1ENrL4gl5CrRuMe2DOucBJoKeFP7wsgNqv6axRuCqDOUoM7xVufuSeQf0uGITvFzT5li2WE05052xknJMMRiv_HNquH6gGTFnYYzL-p4PmlMHLDL82-0ufc9kwEH16b" width=110 height=110)

:::

One of the white lines in the grapefruit is a [[radius | diameter | circumference]], A spoke of the ferris wheel is a [[radius | diameter | circumference]]. The crust of the pizza is the [[circumference | radius | diameter]]. The height of the tire is the [[diameter | radius | circumference]]. The width of the log is the [[diameter | radius | circumference]].

While it’s not typical to think of the “diameter” of a square, it could be the line from one side to the other that passes through the center.

    // ANIMATION-02: Diameter of a square

It takes [[4]] “diameters” of a square to wrap around a square and therefore create the perimeter of the square. Upon entering in the 4: In a square, the distance around is 4 times as long as the distance across. Let’s think about this same question with circles. How many diameters of a circle do you think are needed to wrap around the circle? [[--]].

---

> id: diameter-circumference
> goals: diameters-drawn

Let’s find out!

    // INTERACTIVE-04: 'Wrapping' circumference (page 7)
    figure: .diameter-drawing
      x-geopad(width=400 height=400)
        svg
      button.btn.reset Reset

1. Draw a circle. 
2. Drag the diameter outside of the circle and wrap it around the circumference. 
3. Keep doing this until you cover as much of the circumference as possible using full diameters. 
4. Repeat this process with two different sized circles.

---

    // HANDS-ON ICON

This is a great time to step away from your device and try this at home. Find any circular object. It could be something in your kitchen like a glass or a plate or a can of vegetables. Or it could be something in your room like a round clock, or a marker, or a bottle of something. Anything circular will work! Use a piece of string and mark of the length of the diameter. Then use a ruler to place a mark on the string that is 3 diameters long. Wrap the string around the circle and see how close the length of three diameters gets to making it all the way around the circle!

You predicted it would take [[--]] diameters to wrap around the circle. It seems to take a little more than [[3]] diameters to fit around a circle. But what is this “little bit more than?” Can we determine how much of a diameter this is? Is it 1/10 of a diameter? 1/5th of a diameter? 1/4th of the diameter? Before answering this question, let’s work with this idea.

::: column.grow(width=350)

    x-img(src="https://static8.depositphotos.com/1051392/952/i/950/depositphotos_9520930-stock-photo-3d-running-around-diagram.jpg" width=350 height=219)

::: column.grow(width=350)

    x-img(src="https://static6.depositphotos.com/1016225/556/i/950/depositphotos_5562081-stock-photo-barefoot-frame.jpg" width=350 height=350)

:::

Imagine you are going to run around a circular track that has a diameter of 500 meters and you want to estimate how far you’lll run. This distance around the track is [[3]] times as long as the distance across, so you’ll run about [[1500]] meters. This is 1.5 kilometers. The actual distance is a little [[more than | less than]] this, but as an estimate for a distance that you’ll run, this works well.

::: column(width=400)

    x-img(src="https://st2.depositphotos.com/2222024/5609/i/950/depositphotos_56093859-stock-photo-happy-little-orange-havanese-puppy.jpg" width=400 height=267)

:::

Now imagine you want to build a fence to enclose a circular play area for your dog. You have measured the distance across the circle to be 60 meters and you know the distance around the circle is about [[3]] times the distance across. Therefore, you buy 180 meters of fencing. You use all the fencing in an attempt to create perfect circle and find out that you have purchased [[not enough fencing | too much fencing | just the right amount of fencing]].

It takes a little more than 3 diameters to equal the circumference. Using 3 as an approximation is fine for some general estimates, but we need to keep working to get to a point where we can more accurately calculate the circumference of a circle.

---

> id: finding-pi

Let’s see if we can determine how much more of the 4th diameter is needed to fully wrap around the circle. Draw a line below and watch as it is then formed into a circle.

::: column.grow

    // INTERACTIVE-05: Finding PI (pages 9-10)
    x-geopad(width=200 height=200)
      svg

::: column(width=450)

    table.finding-pi.reveal(when="line-drawn")
      tr
        th CIRCUMFERENCE
        th DIAMETER
        th.reveal(when="blank-1") NUMBER OF DIAMETERS NEEDED TO EQUAL CIRCUMFERENCE
      tr
        td.circumference 0
        td.diameter 0
        td.reveal(when="blank-1")
          x-blank-input(solution="3.14")

:::

Let’s think about how many diameters are needed to make the circumference. Determining how many times one number is needed to make another is represented by [[division | multiplication | subtraction]]. 

Dividing the length of the circumference by the length of the diameter will determine how many diameters are needed to equal the circumference. Do that division and enter the value in the table.

Try it again with a different length starting line.

---

The little bit more of the 4th diameter that is needed to wrap around a circle is 0.14 of a diameter. While it took 4 diameters off a square to wrap around the square, it only takes [[3.14]] diameters to fit around a circle.

    // HANDS-ON ICON

Now is another great time to step away from your device and try this on any circle at home. Use a ruler to measure the diameter of a circle. Then, wrap a piece of string around the circle and make a mark where the string meets the starting point. Measure this length of string with a ruler. Divide the circumference by the diameter. Do you get a result close to 3.14?

We’ve now established the idea that the circumference of a circle can be found by measuring the diameter of a circle and [[multiplying | dividing]] it by [[ 3.14 | 4 | 5]]. This idea written as a formula is C = 3.14 x D. Let’s add this formula to our toolkit. Since the diameter is [[double | half]] of the radius, we can also measure the radius, double it and then multiply by 3.14. This gives another version of the formula: C = 3.14 x [[2]] x R.

::: column(width=400)

    x-img(src="https://st2.depositphotos.com/2222024/5609/i/950/depositphotos_56093859-stock-photo-happy-little-orange-havanese-puppy.jpg" width=400 height=267)

:::

Now we can accurately calculate the amount of fencing needed to enclose a circle with a diameter of 60 meters. Recall that 180 meters was [[not enough | too much]] fencing. If the diameter is 60, we find the circumference by multiplying 60 by [[3.14]]. The actual circumference is [[188.4]]. If you can only buy fencing whole-meter sections, you should buy [[189]] meters of fencing. Only using 180 meters of fencing as we originally estimated would have left almost a 10 meter opening!

Some of the earliest civilizations have pondered the question of how many diameters are needed to equal the circumference of a circle. A Babylonian clay tablet dated between 1900 BC to 1600 BC described the number of diameters needed to be 3 ⅛, or 3.125. This is only [[0.15]] away from the 3.14 we established above. The Rhind Mathematical Papyrus from around 1650 shows the Greeks used 3.16 as the number of diameters needed. This is only [[0.02]] from 3.14.

::: column(width=600)

    x-img(src="https://media.britishmuseum.org/media/Repository/Documents/2014_10/5_19/595e9f4b_efb3_481a_9257_a3bb013ab718/mid_00366139_001.jpg" width=600 height=109)

:::

The Shatapatha Brahmans, an Indian text from 400-300 BC, shows that Indians used 3.139. This is only [[0.001]] away from 3.14.

It turns out that 3.14 is not the exact number of diameters needed to equal the circumference. In the 3rd century BCE, Greek mathematician Archimedes placed polygons inside and outside of circles to estimate the number to be 3.1418. 400 years later, Greek mathematician Ptolemy used polygons with 360 sides to estimate the number to be 3.1418.

Through the work of these and other mathematicians around the world, the number became more and more precise. When describing this number, mathematicians would say things like “the quantity which, when the diameter is multiplied by it, yields the circumference,” or other wordy descriptions.

In 1706, William Jones, a Welsh mathematician, simplified things by using a letter of the Greek alphabet to stand for this number. The greek work “perimetros” roughly translates to “around” so Jones used the first letter of the word “perimetros.” The Greek alphabet uses different symbols than the English alphabet. In Greek, “perimetros” is written περίμετρος. The first letter of this word is π and pronounced “Pi” in English. Swiss mathematician Leonard Euler popularized the π symbol when he began using it in 1737. It’s just a coincidence that the English pronunciation of the Greek letter π also happens to be the name of a circular dessert!

::: column(width=480)

    x-img(src="https://media.giphy.com/media/3ohjUZawOtwng26rN6/giphy.gif" width=480 height=360)

:::

So what is the exact value of π? Is it 3.14? 3.141? It turns out that mathematicians have discovered patterns and rules that can determine each next digit of π. Today, mathematicians have programs on supercomputers to determine digits of π. Mathematicians currently know over 30 trillion digits after the decimal point! The first 5 digits of π after the decimal are 3.14159. You’ll learn more about the decimal expansion of π in future mathigon chapters. The most commonly used fractional approximation of π is 22/7 or 3 1/7 since this equals 3.142857.

Let’s not let the ever-expanding decimal expansion of π detract from the simplicity here. The number π represents how many diameters of a circle are needed to equal the circumference.

In the rest of this chapter, we’ll use the approximation of 3.14.

We had written the formulas as C = 3.14 x D and C = 3.14 x 2 x [[R | D]]. Now that we know the Greek letter π is used to represent the exact number of diameters needed to equal the circumference, we can replace 3.14 with π in these formulas. C = π x [[ D | R ]] or C = π x [[2] x R. The formulas are often written without the multiplication symbols as follows: C = πD and C = 2πR. Let’s update our toolkit with these versions of the formulas.

---

> id: circular-highways

Traffic is a concern in cities around the world. In an attempt to keep traffic outside of the city-center, many cities have circular highways going around the city. Let’s explore three examples around the world.

    // INTERACTIVE-06: Circular highways (pages 13-14)
    // [TODO]: Document tabs (if not documented already)

::: tab

#### Rome _{span.check(when="blank-0 blank-1")}_

    figure: .rome
      .map
        include svg/rome.svg
        x-geopad(width=400 height=400)
          svg
      button.btn.reset Reset

Draw in a circle that covers the highway shown. _{span.reveal(when="rome-circle")}Draw in a diameter of the circle._ _{span.reveal(when="rome-diameter")}The distance around this road is [[64.37]] [[km | m | cm]]._

::: tab

#### Moscow _{span.check(when="blank-2")}_

    figure: .moscow
      .map
        include svg/moscow.svg
        x-geopad(width=400 height=400)
          svg
      button.btn.reset Reset

Draw in a circle that covers the highway shown. _{span.reveal(when="moscow-circle")}Draw in a radius of the circle._ _{span.reveal(when="moscow-radius")}The distance around this road is [[15.1]] km._

::: tab

#### London _{span.check(when="blank-5")}_

    figure: .london
      .map
        include svg/london.svg
        x-geopad(width=400 height=400)
          svg
      button.btn.reset Reset

Draw in a circle that covers the highway shown. _{span.reveal(when="london-circle")}The distance around this highway is about [[170]] km. If you instead wanted to drive straight across the circle through the center, this distance is [[54]] km._ _{span.reveal(when="blank-3 blank-4")}This distance is the [[diameter | radius ]] of the circle._

:::

---

::: column(width=400)

    x-img(src="https://st4.depositphotos.com/13193824/19879/i/1600/depositphotos_198799636-stock-photo-young-smiling-woman-sunglasses-riding.jpg" width=400 height=292)

:::

An average road bike tire has a diameter of 68 cm. Recall that the distance a tire travels in one revolution is the same as the [[circumference | diameter]] of the tire. In one revolution of the tires of an average road bike, the bike travels [[214]] cm. The loop around Moscow is 15.1 km. This equals 1,510,000 cm. If you were to ride your bike around this loop, your wheels would make about [[7,056]] revolutions!

    // DIAGRAM: Track

We are now ready to answer the question from the start of the chapter! Recall that the tires need to be changed after about 52,000 revolutions and that we want to know how many laps around the track equals 52,000 tire revolutions.

The diameter of the tire is [[27]] inches so the circumference is [[85]] inches. 52,000 revolutions gives a distance traveled of [[4,420,000]] inches. This equals about 70 miles.

Now, calculate the distance around 1 lap. The 4 straight sections have a total distance of [[7,920]] feet. Combining the 4 turns of the track creates [[1 | ½ | 2]] circles.

    // ANIMATION-03: Lap distance

The radius of the circle is [[840.8]] feet, so the distance around the circle is [[5,280]] feet. Therefore, the total distance of 1 lap is [[13,200]] feet. This equals 2.5 miles.

Each set of tires last 70 miles and the distance around one lap is 2.5 miles, so the tires should be changed after [[28]] laps. 

The race is called the Indy 500 because cars must drive 500 miles. Each lap is 2.5 miles, so the race is [[200]] laps long. That means there are about [[7]] tire changes over the course of the race. That’s a lot of tires!

Let’s end this chapter with one final question. What do you think is longer - the height of the can of tennis balls or the distance around the can? [[the height of the can | the distance around the can]].

    // DIAGRAM: Tennis ball can comparison

A tennis ball has a diameter of 6.7 cm and the can holds 3 of them with no extra room at the top or the bottom. Therefore, the height of the can is [[20.1]] cm.

The distance around the can is the same as the [[circumference | diameter | radius]] of the cap of the can.

    // DIAGRAM: Tennis ball lid overlay

The circumference of the cap is 3.14 x [[D | R]]. The distance around the can is [[21]] cm. The longer distance is the [[distance around the can | height of the can]].

We could have answered this question without doing any calculations! The height of the can is the same as [[3]] diameters of the tennis balls. The distance around the can is 𝞹 [[diameters  radii]]. The number 𝞹 is [[more than | less than]] 3, so the distance around any can (like this can of squash balls) that perfectly holds 3 circular objects is more than the height of that can!

::: column(width=400)

    x-img(src="https://images-na.ssl-images-amazon.com/images/I/61ZdvJup6PL._AC_SX679_.jpg" width=400 height=691)

:::

---

## Area of Circles

> section: circle-area
> sectionStatus: dev

    // DIAGRAM: Pizzas w/diameters (page 1)

At a local pizza place, Tetromino’s Pizza, 1 large pizza costs the same as 2 medium pizzas. Which option do you think you should buy if you want as much pizza as possible? [[1 large | 2 medium]]. To decide which is the better purchase, we need to know the [[area | circumference]] of each circular pizza.

---

> id: slicing-1

As we’ve done in previous chapters, let’s use what we know about polygons to help us understand the area of circles  Estimate the area of each pizza by cutting them into 8 equal triangles.

    // INTERACTIVE-01: Pizza slicing (pages 1-2)
    figure: x-geopad(width=1000 height=400)
      include svg/pizza.svg

{.reveal(when="large-slices medium-slices")} Recall  that the area of a [triangle](/course/shapes/parallelograms-triangles) can be found by using the formula ½ x base x height, as long as the base forms a [[right | acute | obtuse]] angle with the base.

---

The larger triangle has [[170.52]] square cm of pizza and the smaller triangle has [[90.28]] square cm of pizza. In total, 1 large pizza has about [[1,364]] square cm of pizza and the 2 medium pizzas have about [[1,444]] square cm of pizza. So, it seems the 2 medium pizzas give more pizza.

---

This process is helpful for making good estimates, but our answers are [[less than | more than]] the actual areas. Maybe the 1 large pizza actually gives more pizza? Let’s keep working to see if we can develop a process for calculating the exact area of a circle.

---

> id: slicing-2

In the [Circumference](/course/shapes/circles) chapter, we thought about the distance around a square to help us think about the distance around a circle. Let’s take the same approach with area. Below is a square pizza with one dimension labeled as “R.” While it’s not typical to think about the radius of a square, this line is the shortest distance from the center of the square to the outside side length.

    // INTERACTIVE-02: Square slice of square pizza (pages 2-4)
    figure: .slices-2
      include svg/square_pizza.svg

Cut out a square piece of this pizza that is a square with side lengths “R.”

{.reveal(when="sliced")} The area of one of those pieces is [[R x R]]. Recall that this can also be written as `R^2`.

{.reveal(when="blank-0")} If each person receives one of the `R^2`-sized pieces, this pizza can serve [[4]] people.

{.reveal(when="blank-1")} Therefore the area of this square is [[4R^2]]. Each side length of the square is [[2R]], we can also find the area of the square by doing [[2R x 2R]]. This also equals $4R^2$. Either way, we see that it takes 4 “R by R” squares to fill in a square when R represents the radius of the square. Let’s see if we can use this idea to discover a way to find the area of a circle.

---

Below is a circular pizza with the radius labeled.

    // INTERACTIVE-03: Square slice of round pizza (pages 4-6)

Draw in a square with side length “R.”

How many of these “R by R” squares do you think you can make from this pizza if rearranging the pizza is allowed [[--]].

4 `R^2`’s is [[bigger | smaller]] than the area of the pizza. Click on one piece to remove it from the picture.

Let’s see how the extra part of the `R^2` compares to the ¼ of the pizza left.

`3R^2` is just not quite enough to cover up the whole pizza. We need a little bit [[more than | less than]] `3R^2` to cover the pizza. Do you recall another number we’ve learned about in thinking about circles that is a little more than 3? Do you think this could be the same number? Let’s keep exploring this idea and find out!

Before answering this question, let’s come back to our initial pizza question using the idea of `3R^2`

    // DIAGRAM: Pizzas w/diameters (page 7)

The large pizza has a diameter of 44 cm, so the radius is [[22]] cm. The area of one `R^2` with this radius is [[484]] square cm, so `3R^2` for the large pizza is [[1452]] square cm. The radius of the medium pizza is [[16]] cm so `3R^2` for 1 one of the medium pizzas is [[768]] square cm. The area of two of these medium pizzas is [[1536]] square cm.

| | 1 Large Pizza | 2 Medium Pizzas |
| Area estimate using area of triangles | 1364 sq cm |1444 sq cm |
| Area estimate using `3R^2` | 1452 sq cm | 1536 sq cm |

So, using `3R^2` as an estimate for finding the area of a circle gives us a better estimate than splitting the circle into triangles. Unfortunately, `3R^2` is still underestimating the area of a circle.

Delivered pizzas can sometimes sit around for too long and get cold. People often reheat pizzas before eating it.

    // https://www.shutterstock.com/image-photo/tasty-pizza-box-isolated-on-white-116973259
    figure: x-img(src="https://image.shutterstock.com/z/stock-photo-tasty-pizza-in-box-isolated-on-white-116973259.jpg" width=300 height=220)

Unfortunately, most pizzas are too big to fit in standard ovens. Rearrange the 8 slices onto this baking sheet that can fit in the oven.

---

> id: slices-arrangement

    // INTERACTIVE-04: Pizza slices arrangement (pages 8-9)
    figure: x-geopad(width=630 height=700)
      include svg/pizza_2.svg

8 slices is pretty common in pizzas, but it could be cut into any number of equal slices. If we increase the number of slices to ${n1}{n1|8|8,30,1} , the shape begins to look more and more like a [[parallelogram | triangle | square]].

We used all the pizza and the slices aren’t overlapping, so the area of the parallelogram is [[equal to | different than]] the area of the circle. The formula for the area of a parallelogram is base x height when the height makes a [[right | acute | obtuse]] angle with the base._{span.reveal} Click on the side of the parallelogram you want to use as the base._ _{span.reveal} Draw in the height that corresponds with this base._

---

Move the slider back and forth to see the base and height of the parallelogram in the circle.

    // INTERACTIVE-05: QA formula sequence (page 9)

| Student Question and Answer | Formula for Area of Parallelogram |
| | base x height |
| The height of the parallelogram is the same as the [[radius \| diameter \| circumference]] of the circle. | base x radius |
| The base of the parallelogram is the same as half of the [[circumference \| radius \| diameter]] of the circle. | ½ of Circumference x Radius |
| Let’s abbreviate circumference with a C and radius with an [[R \| D]] | ½ x C x R |

The area of the parallelogram is the same as the area of the circle, so we can find the area of a circle by doing ½ x C x R!

---

> id: pizza-rings

People like to eat pizza in all sorts of unusual ways.

    figure: x-img(src="https://media.giphy.com/media/ToMjGpPXUoKCyBGW7lu/giphy.gif" width=300 height=300)

For example, some people cut their pizza into rings rather than slices.

    // DIAGRAM: Pizza rings (page 10)

This pizza becomes a little more difficult to arrange on the baking sheet but it is possible.

    // INTERACTIVE-06: Circle rings (pages 10-11)

::: column(width=340)

    svg.circle-area.blue(width=340 height=245)
      g.labels
        line.reveal(x1=20 y1=156 x2=20 y2=206 marker-start="url(#area-arrow)" marker-end="url(#area-arrow)" when="blank-1")
        line.reveal(x1=34 y1=218 x2=355 y2=218 marker-start="url(#area-arrow)" marker-end="url(#area-arrow)" when="blank-2")
        text.reveal(x=10 y=185 when="blank-1") r
        text.reveal(x=165 y=236 when="blank-2") 2πr
    x-slider(steps=400)

:::

Move the slider to see the rings being arranged on the baking sheet. If we increase the number of rings up to ${n2}{n2|4|4,15,1}, the shape starts to look more and more like a [[triangle | parallelogram | circle]].

We used all the pizza and the rings aren’t overlapping, so the area of the triangle is [[equal to | different than]] the area of the circle. The formula for the area of a triangle is [[½]] x base x height when the height makes a right angle with the base. _{span.reveal} Click on the side of the triangle you want to use as the base._ _{span.reveal} Draw in the height that corresponds with this base._

Move the slider back and forth to see the base and height of the triangle in the circle.

---

    // INTERACTIVE-07: QA formula sequence (page 11)

| Student Question and Answer | Formula for Area of Triangle |
| | ½ x base x height |
| The height of the triangle is the same as the [[radius \| diameter \| circumference]] of the circle. | ½ x base x radius |
| The base of the triangle is the same the [[circumference \| radius \| diameter]] of the circle. | ½ of Circumference x Radius |
| Let’s abbreviate circumference with a C and radius with an [[R \| D]] | ½ x C x R |

So, whether we cut the pizza in the triangular slices or rings, we end up with a formula for the area of the circle as ½ x C x R.

    // HANDS-ON ICON

Can you think of another way to rearrange parts of a circle into other shapes we know how to find the area of? This could be a good time to step away from your device and try this on your own. Perhaps you’ll come up with a new way to rearrange a circle to show that the area formula is ½ x C x R. 

One way to find the area of a circle would be to multiply the length of the radius by the length of the circumference and then multiply it by [[1/2]]. However, to determine the length of the circumference, we would have to use another formula. So, while ½ x C x R is a correct approach to finding the area of a circle, mathematicians prefer to have formulas that are as simple as possible. Let’s work with the formula ½ x C x R and see if we can simplify it.

    // INTERACTIVE-08: QA formula sequence (pages 12-13)

| Student Question and Answer | Formula |
| | ½ x C x R |
| The formula for [circumference](/course/shapes/circles) of a circle is [[𝜋D]] | ½ x 𝜋 x D x R |
| When multiplying, changing the order of the items being multiplying [[does \| does not]] give the same answer. | ½ x D x 𝜋 x R |
| Half of the diameter is equal to the [[radius \| circumference]]. | R x 𝜋 x R |
| When multiplying, changing the order of the items being multiplying [[does \| does not]] give the same answer. | 𝜋 x R x R |
| Multiplying something by itself is the same as raising it an exponent of [[2]]. | `pi R^2` |

The formula for the area of a circle is `pi R^2`. Let’s not lose sight of how exciting this is! Remember that earlier in the chapter, we were trying to determine how many `R^2` are needed to cover a circle:

    // DIAGRAM: Round pizza with square area segments (page 13)

We saw that `4R^2` was [[too big | too small]] and that `3R^2` was a little [[too small | too big]]. We have now proved the exact number of `R^2` we need - 𝜋 “`R^2`” are needed to fill in the circle. Recall from the Circumference chapter, that we often approximate 𝜋 with 3.14. 

𝜋 is a powerful number! not only does it tell us how many [[diameters | radii]] are needed to go around the circumference, it also tells us how many `R^2` are needed to completely fill in a circle. 

When using the formula `pi R^2`, remember to first multiply the radius by itself and then multiply that product by 𝜋. Let’s add this formula to our toolkit. 

We are now ready to answer our original question. Which option has more pizza?

    // DIAGRAM: Pizzas w/diameters (page 14)

    // INTERACTIVE-08: QA formula sequence (page 14)

| Student Question and Answer | Area of 1 Large Pizza | Area of 2 Medium Pizzas |
| Type in the formula we’ll use | `pi R^2` | `2 pi R^2` |
| The radius of the large pizza is [[22]] and the radius of the medium pizza is [[16]] cm | `pi(22)^2` | `2pi(16)^2` |
| Let’s use [[3.14]] as an approximate for 𝜋 | `3.14 x (22)^2` | 2 x 3.14 x (16)^2 |
| Now, square the radius. | 3.14 x [[484]] | 2 x 3.14 x [[256]] |
| Finally, finish the multiplication | [[1519.76]] | [[1607.68]] |

::: .reveal

| 1 Large Pizza | 2 Medium Pizzas |
| Area estimate using area of triangles | 1364 sq cm | 1444 sq cm |
| Area estimate using `3R^2` | 1452 sq cm | 1536 sq cm |
| Area estimate using `3.14R^2` | 1519.76 sq cm | 1607.68 sq cm |

:::

We can now finally conclude that the [[2 medium pizzas | 1 large pizza]] have more pizza!

Some people don’t eat the crust on the pizza. If we compare the 1 large pizza to the two medium pizzas without the crust, which option do you think will be the better purchase? [[2 medium pizzas | 1 large pizza]].

The crust on these pizzas is 4 cm thick.

    // DIAGRAM: Pizzas w/diameters and crust thickness (page 15)

If we are just interested in finding the area of the pizza without the crust, the diameter of the large pizza-only circle is [[36]] cm and the diameter of the medium pizza only-circle is [[24]] cm.

    // INTERACTIVE-09: QA formula sequence (pages 15-16)

| Student Question and Answer | Area of 1 Large Pizza without crust | Area of 2 Medium Pizzas without crust |
| Type in the formula we’ll use | `pi R^2` | `2 pi R^2` |
| The radius of the large pizza is [[18]] and the radius of the medium pizza is [[12]] cm | `pi (18)^2` | `2 pi (12)^2` |
| Let’s use [[3.14]] as an approximate for 𝜋 | `3.14 x (18)^2` | `2 x 3.14 x (12)^2` |
| Now, square the radius. | 3.14 x [[324]] | 2 x 3.14 x [[144]] |
| Finally, finish the multiplication | [[1017.36]] | [[904.32]] |

Compare this with our earlier result:

| | 1 Large Pizza | 2 Medium Pizzas |
| Area with crust | 1519.76 sq cm | 1607.68 sq cm |
| Area without crust | 1017.36 sq cm | 904.32 sq sm |

If you eat the crust, the better purchase is [[2 medium pizzas | 1 large pizza]]. If you don’t eat the crust, the better purchase is [[1 large pizza | 2 medium pizzas]].

Below are three different square pizzas with different sized pepperonis on each pizza.

    // INTERACTIVE-10: Pepperoni coverage (page 17)

Let’s find the amount of each pizza not covered by pepperoni. First, rearrange the pizzas into the order that you think goes from least to greatest in terms of amount of pizza NOT covered by pepperoni.

To find the area of each pizza not covered by pepperoni, we can find the area of the whole pizza and then [[subtract | add | divide]] the area of the pepperoni.

| | Area of Pizza A NOT covered by pepperoni | Area of Pizza B NOT covered by pepperoni | Area of Pizza C NOT covered by pepperoni |
| | Area of Square - Area of [[1]] Circle | Area of Square - Area of [[4]] Circles | Area of Square - Area of [[9]] Circles |
| The formula for the area of a square is base x [[height \| diagonal]] | (b x h) - (1 circle) | (b x h) - (4 circles) | (b x h) - (9 circles) |
| The formula for the area of a circle is [[`pi R^2` \| `pi D` \| `2 pi R`]] | `(b x h) - pi R^2` | `(b x h) - 4 pi R^2` | `(b x h) - 9 pi R^2` |
| The base and height of the square are [[30]] cm. | `(30 x 30) - pi R^2` | `(30 x 30) - 4 pi R^2` | `(30 x 30) - 9 pi R^2` |
| The radius of the pepperoni in Pizza A is [[15]] cm and let’s use [[3.14]] for 𝜋. | `(30 x 30) - (3.14)(15)^2` | `(30 x 30) - 4(3.14)(7.5)^2` | `(30 x 30) - 9(3.14)(5)^2` |
| Calculate the area of the square and the pepperonis. | [[900]] - [[706.5]] | [[900]] - [[706.5]] | [[900]] - [[706.5]] |
| Enter the final answer! | [[193.5]] sq cm | [[193.5]] sq cm | [[193.5]] sq cm |

It turns out all the pizzas have [[the same | different]] areas of pizza not covered by pepperoni!
