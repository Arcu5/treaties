	Throughout US history, presidents and senators have worked together to create agreements and
 accords on the international scale through treaties. “[The President] He shall have Power,
 by and with the Advice and Consent of the Senate, to make Treaties, provided two thirds of
 the Senators present concur; and he shall nominate, and by and with the Advice and Consent
 of the Senate”(Article II, section 2). Hundreds of these documents are stored on the Library
 of Congress website, yet it is often difficult and tedious for historical researchers,
 students and teachers alike to effectively analyze trends and quickly navigate from one
 large block of text to another. Our project for the Library of Congress challenge is a
 data visualization of all US signed treaties passed by Senate from 1949-2017. Using
 data downloaded from congress.gov, we converted the data from CSV to JSON format to
 make it easier to work with. We then implemented a custom responsive data
 visualization(treatySwarmPlot.html) with JavaScript and the D3 library.
 The end result was a graph that plotted each treaty as a bubble along a date received by
 the president of each treaty to its corresponding treaty topic. Using a program written in
 python, we were then able to extract the foreign countries each treaty is signed with which
 was challenging due to the many names a given country may go by. The dropdown menu and
 autocomplete textbooks allows for the user to filter and optimize the graph to their liking
 , or to isolate a specific set of treaties signed with a certain country. Given that the graph
 is a data visualization tool, we hope that users may be able to spot trends and understand the
 procession of historical events and their us to international legislative counterparts by a
 visual, interactive and effective way which would otherwise be tedious and dull. Such trends 
 include the unprecedented amount of Criminal and Extradition treaties during the mid to late 
 90s. Exploration of each treaty is simple as the corresponding link to the congress.gov site,
 among with additional information, is accessible by hovering the cursor over the treaty bubble. 

 Contributors: Ilya Bronshtein, Carter Nielson, Alan Gomez-Tagle 
https://docs.google.com/document/d/129FxBQP7zEPmbOACtasMv89YpTx5Hb-GvKGTvfwQf2A/edit