---
layout: post
title:  Embodied Computation Lab
date:   2017-10-01 00:00:00 -0400
image_path:	/img/embodied computation lab/
cover:  title.jpg
client: Princeton School of Architecture
role: Initial concept design, facade design and machine learning application
location: Princeton, NJ
images: []
active: true
---

---

![embodied computation lab](/img/embodied computation lab/01.jpg)

The Embodied Computation Lab is a new lab facility for the School of Architectura at Princeton University. The goal of the design was to provide a large flexible space in which the university's researchers could experiment with new technologies such as robotics and embedded sensor systems.

---

![embodied computation lab](/img/embodied computation lab/15.jpg)

Although simple in form, the building incorporates a variety of sustainability strategies. One of the most unique is the building's facade, which is composed entirely of reused scaffolding planks salvaged from construction sites around New York City.

These boards are certified by OSHA to meet the structural and durability standards to be used on a construction site. However, due to the wide variety of conditions found on construction sites and the difficulty of ongoing testing they are only certified for one year, after which they are typically thrown away and replaced.

---

![embodied computation lab](/img/embodied computation lab/02.jpg)

To give these boards a new life within the Embodied Computation Lab, we worked with a local salvage company to source 2,000 of these boards for the facade of the building. Looking at the boards, we were struck by how a year spent in a variety of construction site conditions had weathered each board differently, causing the initially standardized boards to reclaim some of their natural material qualities. 

---

![embodied computation lab](/img/embodied computation lab/03.jpg)


In the design of the facade, our goal was to further exaggerate and express the differences within each of the boards. To do this we partnered with local Brooklyn artist [Evan Eisman](http://www.evaneisman.com/), who has been experimenting with sandblasting natural woods in order to reveal their unique grain structures. Noticing that the grain structures are most unique at the knots where branches connected to the trees, we decided to focus the sandblasting only on the locations of the knots.

---

![embodied computation lab](/img/embodied computation lab/04.png)

Manually finding and sandblasting the knots on all 2,000 board would have been extremely challenging and time consuming, so to scale up the process we developed a Machine Learning application using Convolutional Neural Networks to automatically find the location of all knots in images of the boards. We could then feed this data into a custom-designed computer numerically controlled (CNC) sandblasting machine to  sandblast the location of each knot.

---

![embodied computation lab](/img/embodied computation lab/05.png)

To train the Machine Learning model we needed alot of data which classified images of wood boards according to whether or not they contained knots. To generate this data we created a web application which presented a single square image of a wood board and asked the user to click a button specifying if the image contained a knot or not.

---

![embodied computation lab](/img/embodied computation lab/06.jpg)

Using this app, we crowdsourced a training set of over 10,000 classified images which we could use to train the model.

---

![embodied computation lab](/img/embodied computation lab/07.jpg)

After training, the model gave us highly accurate and robust predictions of where knots occurred in images of wood boards.

---

![embodied computation lab](/img/embodied computation lab/08.png)

We could then apply this model to find the locations of knots in each board, and then pass this data to our CNC sandblasting machine to treat all the boards of the facade.

---

![embodied computation lab](/img/embodied computation lab/09.jpg)

![embodied computation lab](/img/embodied computation lab/11.jpg)

![embodied computation lab](/img/embodied computation lab/12.jpg)

These images show the boards being installed on the building facade, and the finished facade in its context on Princeton's wooded campus. This project shows the potential for using advanced tools of computation, Machine Learning, and robotics to work with and reveal the unique features and identity of natural materials.

---

![embodied computation lab](/img/embodied computation lab/14.jpg)

![embodied computation lab](/img/embodied computation lab/13.jpg)

---

Press:

- 12/08/17 - [Architects Newspaper](https://archpaper.com/2017/12/2017-design-awards-for-green-civic/) - Winner of 2017 Best of Design Award for Green - Civic
- 11/01/17 - [Architectural Record](https://www.architecturalrecord.com/articles/13048-the-embodied-computation-lab-by-david-benjamin-at-the-princeton-school-of-architecture) - Featured Project