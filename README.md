# Google-Season-of-Docs-2019-Project-Report

## Google Season of Docs 2019 | OpenSCAD | Themistoklis Spanoudis

## Project: Create an OpenSCAD Tutorial

![](/Report_Assets/racing_car_with_spoiler.jpg)

### Work done

Although OpenSCAD has sufficient and detailed documentation it was lacking a structured tutorial aimed at potential users with little to no programming or CAD knowledge. Potential users who fall under this category had reported that the software was inaccessible to them.

The contribution of this project is the development of a structured tutorial consisted of step by step examples and exercises designed to quickly ease new users into OpenSCAD’s scripting language and available features. The topics of the tutorial are arranged in way that allows users to get started with creating their own models straight away and to increase the number of tools available at their disposal as they move on to more advanced topics.

Special emphasis is placed from the beginning on parametric design principles that will enable the users to build rapidly modifiable and reusable designs which is one of the key strengths of OpenSCAD.

The created tutorial is published as a new Wikibook which is suitable for both online study sessions as well as offline through the download as pdf option. The majority of the presented examples and solutions to exercises as are available as separate OpenSCAD scripts for direct use.

The tutorial on Wikibooks is under a CC-BY-SA license as required by Wikibooks, while the code examples available on GitHub are under a CC0 license.

### Links to work done

The tutorial’s Wikibook which was completely created during this project can be found [here.](https://en.wikibooks.org/wiki/OpenSCAD_Tutorial)

Each separate chapter of the tutorial’s Wikibook downloaded as a pdf file can be found [here.](https://github.com/s-themis/Google-Season-of-Docs-2019-Project-Report/tree/master/Downloaded_Tutorial) The pdf files were added to capture the state of the created tutorial in an easily accessible place as of the completion of this project. Alternatively, that state of the tutorial on Wikibooks is also available through the revision history in the following links.

* [Root page](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial&oldid=3606168)
* [Chapter 1](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_1&oldid=3602948)
* [Chapter 2](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_2&oldid=3602970)
* [Chapter 3](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_3&oldid=3602981)
* [Chapter 4](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_4&oldid=3603011)
* [Chapter 5](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_5&oldid=3603034)
* [Chapter 6](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_6&oldid=3603104)
* [Chapter 7](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_7&oldid=3603112)
* [Chapter 8](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_8&oldid=3603120)
* [Chapter 9](https://en.wikibooks.org/w/index.php?title=OpenSCAD_Tutorial/Chapter_9&oldid=3603133)

The accompanying OpenSCAD script files of the examples and solutions can be found [here.](https://github.com/openscad/documentation/tree/gsod-2019/OpenSCAD_Tutorial/Tutorial_Files) The linked branch corresponds to the final [commit.](https://github.com/openscad/documentation/commit/5d5097ff8bb0560337a318e6ba665c1d11e5e96a)

### Current state of the project

At its current state this project is a complete tutorial that has been upload to Wikibooks, while all accompanying files are available at GitHub. The tutorial currently covers a large portion of OpenSCAD’s syntax and features which can be used to create arbitrarily complex models. 

The tutorial is ready to be used by potential OpenSCAD users who lack a programming or CAD background or even by existing users who would like to make more parameterized designs.

### Challenges and learnings

The main challenge was narrowing down the specific audience that would be targeted by the tutorial and coming up with the appropriate sequence of topics and presentation style to minimize confusion and maximize the learning rate. 

After an iteration on a couple of topics it was clear that the tutorial would need to assume zero programming and CAD knowledge as this was the most underrepresented group according to the existing documentation. It also became clear that all topics would be introduced through examples that would give the opportunity to present the corresponding ideas and syntax while providing additional context when necessary. Another conclusion that was made was that the user would need to be engaged throughout the tutorial by building models and by putting new knowledge in practice. This was achieved by including exercises throughout the tutorial that motivate the immediate use of newly learned skills.

I was also pointed to a great presentation “What nobody tells you about documentation” by Daniele Procida from PyCon Australia which gives a very nice overview of the different types of documentation and the ideal characteristics of each one. This presentation has also been a guiding influence in choosing the sequence of the presented topics as well as the specific examples and exercises for each one.

### Potential extensions

This tutorial was intentionally built on Wikibooks which is a platform that promotes continuous updates and contributions on existing books. Depending on received feedback and common requests following the release of this tutorial, potential extensions could include increased number of examples and exercises and/or coverage of specific additional topics.
