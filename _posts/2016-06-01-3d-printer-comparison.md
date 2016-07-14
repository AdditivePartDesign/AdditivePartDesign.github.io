---
layout: post
title:  "3D Printers: $200,000 VS $2500"
categories: 3d printers
---

Disclaimer: All of the views discussed in this post are my own and do not reflect the viewpoints of my employer or the manufactures of the products I use in this post. 

After touring the Caterpillar additive manufacturing lab I made an observation that the quality of the prints done on their state of the art Stratasys FDM machine were not that much more impressive than what I have seen on desktop hobbist machines. With that said, I decided to do a little science experiment and compare two parts done on a very expensive professional machine and an enthusiast level home desktop 3D printer. The model I chose was an actual manufacturing fixture used to help lay ribbon cables during electronic hardware manufacturing. In the past these were injection molded but with the power of additive manufacturing and FDM 3D printing methods these parts can be made in house without the need of machining and tooling. The printers going head to head in this comparison are the Lulzbot Taz 5 3D printer and a Stratasys Fortus 380 MC. (Disclaimer: I do not own or am paid to speak on behalf of either of these companies, I just use their products to perform parts of my job). The Stratasys printed part was printed with ABS material, 100% infill with a standard layer height on normal detail settings. Not having direct access to the machine I was not able to extract any real nitty gritty details on the overall print set up. For the Lulzbot print that I created I used HIPS material with a 0.5mm nozzle, 0.1mm layer height, 25% infill, 4 top and bottom solid layers, 45 mm/s print speed with standard acceleration, 240C extrusion temperature, 110C bed temperature, and an extrusion width of 0.6mm. Both prints took upwards of 18 hours to complete on both machines.
After a long wait I came in to the office in the morning to see that the Lulzbot was able to come through and finish printing the part without any problems. I was immediately impressed with the results. The following pictures show what the part looked like directly off the printer bed.

![Image 1](/images/posts/3d-printer-comparison/image1.png)

![Image 2](/images/posts/3d-printer-comparison/image2.png)

![Image 3](/images/posts/3d-printer-comparison/image3.png)

I removed the support material as best as I could and started snapping pictures comparing the two parts. The black part was the one printed on the Stratasys professional printer and the green part was the version printed on the Lulzbot Taz5. My initial reaction was that the overall top layer surface finish was very close. The Stratasys printed part was better. But in all honesty, not obviously better. It was difficult to get a true comparison of the RAW print surface finish because anything that gets used on the floor is normally printed with 100% infill, sanded and acetone sealed in order to eliminate any burrs or rough spots that could damage electrical components. Which was the case in this instance with the professional printed part. The following pictures show the initial comparison.

![Image 4](/images/posts/3d-printer-comparison/image4.png)

I then compared some of the more detailed features of the part. First was one of the mounting tabs on the side of the part. Unfortunately I was a huge dummy and didn’t check if there were adequate supports under all of the features of the part. In this case, half of the feature was missing due to inadequate supports but the top half of the feature turned out very good. Of the part that actually printed, I would confidently say that it was of the same quality from printer to printer.

![Image 5](/images/posts/3d-printer-comparison/image5.png)

![Image 6](/images/posts/3d-printer-comparison/image6.png)

The detail around the two mounting holes was compared. There was a little bit of a gap around the top layers and the edge of the holes on the Lulzbot printed part. If I were to print this again I would double the amount of top and bottom solid layers due to the small layer height in order to eliminate this defect. However I was still impressed with the overall quality of this feature.

![Image 7](/images/posts/3d-printer-comparison/image7.png)

![Image 8](/images/posts/3d-printer-comparison/image8.png)

And now comes the part where the Stratasys printed part has a huge advantage, the surfaces that contact with the support material. With the Lulzbot Taz 5 the support structure is built out of the same material as the final product which leaves lots of burrs and rough areas from where the supports are pulled off the part. The Stratasys machine uses a separate dissolvable support material that can be washed away with a special salt water solution. This gives it a huge advantage in regards that you will have to do minimal sanding in order to get a decent finished product. Again the Stratasys produced part was sanded and sealed but still has a superior finish. The following pictures show the side of the part that interfaces with the support structures.

![Image 9](/images/posts/3d-printer-comparison/image9.png)

![Image 10](/images/posts/3d-printer-comparison/image10.png)

Because this is an actual 3D printed production tool it has the part number 3D printed in to it. The Stratasys part number was painted orange to better identify it on the floor but the overall detail of the text was significantly better than the Lulzbot printed part. For confidentiality sake the entirerty of the part number was cut off. The following pictures show this feature.

![Image 11](/images/posts/3d-printer-comparison/image11.png)

![Image 12](/images/posts/3d-printer-comparison/image12.png)

One defect I observed on the Lulzbot printed part was the blade portion of the tool had a split in it from not bonding correctly. This was most likely a cause of pushing the 0.5mm nozzle to its limits in terms of layer height but a little glue and some pressure would fix this split no problem.

![Image 13](/images/posts/3d-printer-comparison/image13.png)

![Image 14](/images/posts/3d-printer-comparison/image14.png)

The last comparison I made was of the overall quality of the round features where a ribbon cable would lay over. Both parts performed incredibly well in this regard. The Stratasys produced part slightly edged out the Lulzbot printed part but with sanding and sealing I am sure I could get the lulzbot printed part to perform as good as the Stratasys produced part. The following pictures show the round edge of the tool.

![Image 15](/images/posts/3d-printer-comparison/image15.png)

![Image 16](/images/posts/3d-printer-comparison/image16.png)

**Conclusion**

At this point you are probably thinking “man that expensive Stratasys printer does a really good job compared to the hobby printer” but in my opinion it is not a big enough leap in quality to justify the enormous price tag. With some tweaks to my G code and use of a nozzle that is more suited for higher resolution prints I am confident that I could produce a part that would be very close to the quality of the Stratasys produced part. Both parts functioned identically for their designed tasks which make it difficult for me to make a business case out of purchasing such an expensive machine. On the contrary I do not know how much effort it takes to get the excellent quality prints that the Stratasys produces. If it is as simple as selecting a print quality and walking away the saved engineering time may pay for itself in the long run. Overall both printers performed incredibly well and are amazing tools for creating manufacturing fixturing. However, unless you are in the need of super high resolution and tight tolerances the Stratasys printer is tough to justify. In addition, when one is in the market for high resolution and tight tolerances one would usually lean towards a machined part anyway over a 3D printed one which makes it even more difficult for me to recommend such an expensive machine.

The next experiment I would like to do would be to get both of these parts on a CMM machine and see how accurate the parts are dimensionally speaking. For this experiment it would require me to sand and seal the Lulzbot printed part so that it was a true head to head in terms of dimensional tolerances and surface finish. I do have a feeling that this is where the Stratasys produced part will really shine and is where the cost can really be justified. But at this point in the game I can’t recommend the professional machine if you are in the market of just getting things done.
