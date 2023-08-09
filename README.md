# website

For all code to SDIC website located at http://www.civil.uwaterloo.ca/snarasim/
This also contains the archives of all previous sites.

Author of website (Sept 2016-Aug 2018): Nicholas Charron
Author of website (Aug 2018): Dylan Dowling

To update:
Home		 	- To change banner, add the image to the "Images" folder and update the image source in <img src="" /> to point to the updated URL
				- To change the about us section, modify within the paragraph <p></p> tags as required
				- To update news, remove the oldest story, and copy the previous stories one spot down in the list. Copy everything between <a href=""> and </a> for each story to transfer image, date, and headline
				- When news is updated, try to include an appropriate number of "filler" h2s for the newsbox to the right of it (approx 8 lines of code below last story on same row)
		
Research		- To add images and captions as required, copy a complete row and modify as needed
				- To add a whole new section, copy a complete section and modify as needed

Research Pages	- To add information, simply type in between <p> </p> tags. 
				- To add images, copy between the <div class="research"> and </div> tags and modify the image source and caption as needed
				- To add or update publications, copy an existing <li> entry and modify info as required
				- To add or update student photos, change the source and name as required. If more than 3 students involved, copy the whole section ( <div class="row"> to </div> ) and modify pictures, links, and names

People			- To modify existing students, change images and names as required, keeping consistent formatting
				- To add new students, uncomment code as required to complete a row. If a new row is required, copy and existing <div class="row"> to </div> and update the images and names as required

Publications	- To add additional publications in an existing year, copy an <li> entry and modify information as required.
				- To add a publication in a new year, add a new <h2>YEAR</h2> tag, copy the <ul> to </ul> and add/modify/delete the <li> entries as required

Facilities		- To add images and captions as required, copy a complete row and modify as needed
				- To add a whole new section, copy a complete section and modify as needed
				
News			- To add news stories, copy the existing stories down a section.
				- If already at the end of a row, copy a complete row from <div class="row"> to </div> to create a new row and modify as needed.

Contact			- No modifications anticipated.

To create new pages:
General			- To create a new page, use the "template.html" file and Save As a new page, followed by modifying the template as required. Ensure that this page is linked correctly in the menu or other area(s) as required.
				- In the <head> area, change the page title <title) from "TEMPLATE | SDIC Lab | University of Waterloo" to "PAGETITLE | SDIC Lab | University of Waterloo" (of course, filling in the actual page title there)

Research Pages	- To create a new page, use the file "research-template.html" and Save As a new page with an appropriate file name, followed by modifying the template as required. Ensure that the new research page is linked correctly on the main research page as required.
				- In the <head> area, change the page title <title) from "TEMPLATE | SDIC Lab | University of Waterloo" to "PAGETITLE | SDIC Lab | University of Waterloo" (where PAGETITLE is a 1-3 short word description of your work. DO NOT BE WORDY.)
				- Change the <h1>Project Title</h1> to the title of your project. This title may be in full, although it is recommended to stay concise
				- Fill in project information and images
				- Ensure images and their associated captions remain within the same <div class="research"> </div> tags
				- Add any publications by copying the existing entry. Ensure you update the href in the <a> tag to point to your URL
				- Update student photos. If more than 3 students involved, copy the whole section ( <div class="row"> to </div> ) and modify pictures, links, and names
				- Update collaborators in the list provided, adding new <li></li> as required.
				- If no publications currently exist, comment out using <!-- as the open comment and --> to close the comment