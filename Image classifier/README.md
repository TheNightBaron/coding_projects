The image classifier project began as a means for me to learn and experiment with Deep Learning, specifically, computer vision. 
Over the course of 4 years in my undergraduate studies, I amassed hundreds of photos of me, my friends, and some background images with no faces. I wanted to build a model that could classify into:
<ul>
<li>images with humans in it</li>
<li>images without humans in it</li>
</ul>
Once I had all pictures with humans in it, the next step of the process was to build another model that could identify the faces of the people involved.

To achieve all of the above, I broke down the end-to-end process into multiple steps:
<ol>
<li>Scrape images from Google of male and female teenagers, and random images which can be classified as 'Noise' or 'Non-humans'</li>
<li>Manually split the images into 2 groups: 'Humans' and 'Non-humans'</li>
<li>Train and fine-tune a CNN on the classified images</li>
<li>Use haarcascades algorithm on the 'Humans' images to identify human faces and extract them into a separate folder</li>
<li>Manually classify a subset of the faces (since they are faces of my friends)
</li>
<li>Train a CNN on the classified faces and then use it on the unclassified faces to finish the project</li>
</ol>

An intermediate step would be to link the images of faces generated using haarcascades to the original images so that it becomes easier for me to identify which face came from which image. It also makes it easier for me to name the images if I want to follow a specific convention such as 'name1_name2_date_place' or some other nameing convention.
