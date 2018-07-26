
Lab 1.5: Document Structure--this section is under construction
==================================
Access the github repository. The instructions below are specific to the configuration of this document. Some docs have different structures

General Structure
-----------------------------------------------------------

The format of this doc is all in the docs directory

|image502|

 #. important directories
 
  - _static
   - Images are stored in docs/_static/Class1
  - class2 - Text formatting and dicument structure are  defined in this section
   - class2.rst   Contains the structure of the top level title in the index
   - labinfo.rst  Contains the text of the top level title in the index
   - module**#**     Think about this as chapters. Each chapter has 2 components
    - module**#**.rst   Contains the structure of the top level title in the index
    - lab1.rst  Contains the text of the top level title in the index **After cloning a document edit this text**
    
|image503|

Clone an existing doc to a new repository
-----------------------------------------------------------
  #. Access your github repository
  #. Select Repositories
  
   |image504|
   
  #. Click the new button
   - name the new repository and click **Create repository** button
 
   |image505|
   
  #. Select the **Import Code** button 
  #. Input the source for the new repository 
  #. Select the **Begin Import Button**
   
   |image506|
   
   .# You will recieve an email when the import is complete. This takes a few minutes
Adding Sections
-----------------------------------------------------------
 #. Create module**#**.rst and a lab1.rst in a new directory under docs/class2.
 
  - copy the contents from an existing  module**#**.rst
  - navigate to docs/class2
  - Click the **Create new file** button
  - enter module**#**/module**#**.rst  **Note: # wil be your new subdirectory**
  - Paste the contents from the existing module**#**.rst into the new file
  - copy the beginning of the contents from an existing  lab1.rst **This helps with consistent formatting. You will probably replace all the text**
  - navigate to docs/class2/module**#** **Note: you created a new module# in the prior steps**
  - Click the **Create new file** button
  - enter /lab1.rst  **Note: # will be your new subdirectory**
  - Paste the partial contents from the existing lab1.rst into the new file
  
|image501|

 #. Edit the new lab1.rst as sescribed in the preceeding chapter 



Static Content (images) 
-----------------------------------------------------------

 #. Images can be created usign the windows snipping tool and saving them as filename.png
 #. Import images
 
  - Navigate to the docs/_static/class1
  - Click the **Upload files button**
  - Drag the files to the screen
  - Press the **commit** button at the bottom
 #. images are embedded in a document by surrounding the reference with vertical bar  example **|imagexxx|**
 #. each image requires a pointer with sizing parameters 
  |image507|

.. |image3| image:: /_static/class1/image3.png
   :width: 3.58333in
   :height: 4.96875in
.. |image501| image:: /_static/class1/image501.png
   :width: 6.25126in
   :height: 3.65672in
.. |image502| image:: /_static/class1/image502.png
   :width: 6.25126in
   :height: 3.65672in
.. |image503| image:: /_static/class1/image503.png
   :width: 6.25126in
   :height: 3.65672in
.. |image504| image:: /_static/class1/image504.png
   :width: 6.25126in
   :height: 3.65672in
.. |image505| image:: /_static/class1/image505.png
   :width: 6.25126in
   :height: 3.65672in
.. |image506| image:: /_static/class1/image506.png
   :width: 6.25126in
   :height: 3.65672in
