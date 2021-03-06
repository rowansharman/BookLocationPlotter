---
title: Project Evolution
layout: template
filename: projectEvolution
---

## YO TEAM! INPUT/EDITS APPRECIATED! CHANGE ANYTHING YOU DON'T AGREE WITH, ESPECIALLY IN THE REVISITING LEARNING GOALS SECTION.

# Project Evolution

### The beginning of the journey...
At the start of the project, we had only three things: a desire to work with maps and visualization, a barcode scanner, and a curiosity about where things come from. The original project idea was an interactive visualization of global commerce that taught a user about the origin of the materials that make up different products. As we further defined our learning goals and our sense of scope, this idea evolved into what it is today.

Within the first few weeks of work, we determined a general code structure with the class "Book" at its center. A book object contains information about a book, most of which is included in the data that belongs to an ISBN code (such as the title, author and year a book was published) but some of which we needed to find for ourselves (specifically, the locations of the author, publisher and plot). We chose to text mine from Wikipedia to obtain these locations, which half the team tackled while others worked with Python's Plotly library to plot the locations once we found them, and developing the classBook.

In the beginning stages of work, our most arduous struggles involved text mining these locations from Wikipedia. Documentation of Wikipedia's API is sparse and often unhelpful, which resulted in a long process of exploration, trial and error in order to build the structures we needed. We wrote over 100 lines of code that ended up being simplified down to 3.

<img src="https://github.com/SamEpp/BookLocationPlotter/blob/master/pictures/mess1.png">

**Figure 1: A snapshot/screenshot in time when we were in the midst of our "exploratory" approach to Wikipedia text mining.**

Once we figured out the first stage of text mining, we progressed onward toward our next challenge: integrating the code different teammates had worked on individually. This in itself turned out to be fairly straightforward. However, through testing a variety of ISBN codes, we ran into a diversity of Wikipedia-related errors we weren't expecting that hadn't appeared when building the Wikipedia in isolation. Through an intensive debugging process, we determined that
## SAM IS A BOSS AND I NEED HER TO TELL ME EXACTLY WHAT SHE FIXED. PREFERABLY WITH EXAMPLE CODE. THANKS BAE

### Cleaning it up...
After writing a working script that takes an ISBN as input and returns a map with the book's locations plotted on it, our next step was to handle all common errors in a way such that the code continued running when it couldn't find one of the locations, and at least returned the information it did find. Once the errors were handled, our next goal became reducing the number of times the text mining failed and produced the message we had just created: "Location was not found on Wikipedia."

While a few team members worked towards this goal by revisiting our text mining code, others made progress on it by coaxing Plotly into recognizing and plotting cities in addition to countries. This solved the failures that occurred when a search for a location returned a city name, which Plotly did not know how to handle.

### Revisiting our original learning goals...
Sarah was interested in working with Plotly and getting more practice with merge conflicts, which she did by building the Plotly integration and being named the team's "Merge Conflict Queen" by the end of the project. Rowan wanted to work with hardware and human interfacing, which he achieved through integrating the barcode scanner and human interaction with the rest of the code. Sam's goal was to improve her text mining skills and practice writing better written, more advanced code, which she achieved by heading up the text mining aspect of the project. Gracey was interested in learning to work with different files that were written in parallel to each other and integrating them into one functional program, which she achieved by tackling the integration aspect of the program. Lastly, all 4 members of the team wanted to practice creating clean, clear documentation, which we achieved together through robust commenting on our code and building this website.

### All in all...
We feel we did a good job balancing the pursuit of our learning goals with the pursuit of a satisfactory final product. We're proud of both the project and personal progress we made. We hope you enjoy learning about our process and hopefully find our finished product useful!
