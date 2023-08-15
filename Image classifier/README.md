<h1>Image Classifier Project</h1>

<strong>Objective</strong>: To build a Face Recognition System from scratch using Deep Convolutional Neural Network (CNN)

<strong>Sub-tasks</strong>:
<ol>
<li><h4>Data collection and cleaning</h4></li>
  <ol>
<li>Scrape images from Google of male and female teenagers, and random images which can be classified as 'Noise' or 'Non-humans'</li>
<li>Manually split the images into 2 groups: 'Humans' and 'Non-humans'</li>
  </ol>
<li><h4>Model training</h4></li>
  <ol>
<li>Train and fine-tune a CNN on the classified images</li>
<li>Use haarcascades algorithm on the 'Humans' images to identify human faces and extract them into a separate folder</li>
<li>Manually classify a subset of the faces (since they are faces of my friends)
</li>
<li>Train a CNN on the classified faces and then use it on the unclassified faces to finish the project</li>
</ol>
</ol>
</br>

<strong>Additional Notes</strong>\
An intermediate step would be to link the images of faces generated using haarcascades to the original images so that it becomes easier to identify which face came from which image. It also makes it easier to name the images if one wants to follow a specific convention such as 'name1_name2_date_place' or some other naming convention.
