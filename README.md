Thank you for checking out my HTML, CSS, and Javascript project for GetCoding!

My original intention was to build the framework to solve a problem I enocuntered at my current job. There are thousands of historic mineral assessment reports from Newfoundland and labrador which have been scanned to PDF format and are non-searchable. Digitizing data from these reports is slow and expensive, so I wanted to explore different ways to extract and present digitized data in these reports. 

Solving this problem is difficult. Discussing it with my coach, we decided that other modules in the GetCoding program may be more suited towards some of the funcitonality I want to build here. 

What I came up with are three sub-projects which each investigate different aspects of the app I eventually want to build. The GIS Project was my original vision of the app, and it includes some cool search functionality of real historic assessment data. The Optical Charachter Recognition project (OCR Project) was a brief investigation into the Tesseract API. OCR will be core to what I want to do in the future. Finally, I wanted to investigate a GIS API which would provide the main UI/UX expirence as users select and download digitized historic data. I used the ArcGIS API incorporating some real mineral claims and mineral showings data in Newfoundland and Labrador. Please note that all the data I display here was downloaded January 2nd, 2023, and is thus only accurate to that date. 

My main HTML, CSS, and Javascript showcase project is Chris' Rocks. This project was built to showcase some rock samples from my personal collection. I've collected there rocks in many different locations from Goose Bay, Labrador, to a shop outside of Zion National Park in Utah, U.S.A. With this project, I want to highlight background but also create an interactive visually appealing page. 

![IntroPage](https://user-images.githubusercontent.com/34209214/223201101-8cfcdbdd-8d80-472d-8fa7-d9958e674df3.png)

Navigation for Chris' Rocks is shown above. If you hover over the rock type images, you'll see a brief description of what each rock type is, in addition to a popup of the rock type following your cursor. There are four in total, Igneous, Sedimentary, Metamorphic, and Economic (the kind of rocks you make money from!). Scrolling down while on this main page, you'll see a short slideshow of a few images related to how I collected these rocks. To the left are four buttons which change the layout of the 12 rock samples form my collection I've picked to display. If you hover over the rock sample its name will follow your cursor, and if you click on the images additional information about that rock sample will appear. 

![image](https://user-images.githubusercontent.com/34209214/223204427-04b30b6d-6bd4-4a66-82b5-7b56027cbd21.png)

Clicking on the first of the three sub-projects, GIS Project, you will see a page identical to the above image. Toward the top right of the page you will see four elements. A search bar, drop-down search tool, and search button. To search through a database, type in a particular historic mining company, for example "Noranda". Ensure the "companies" is selected from the drop down list, then click search. A footer element will appear with the results of your search query. Clickin on the menu icon in the uppermost right corner of the app will open a hidden menu to the right. Clicking on these options will load different background images representitive of different types of historic minearl exploraiton data. 

Image of OCR PROJECT!

Clicking on the second of the three sub-projects, OCR Project, you will see an image identical to the above. Here, you may upload image only data in a language supported by the drop down optsions adjacent to the browse button. This image should have some text for the Tesseract OCR algorithm to recognize. Four versions of your uploaded image will pop up in addition to the regnized text. These four popups represent typical processing steps duirng OCR, but are not implemented here, and only for show. 

![image](https://user-images.githubusercontent.com/34209214/223206044-2e950705-db32-4b3d-b1f5-166a460893fc.png)

Finally, clicking on the last of the three sub-projects, ArcGIS API, you will see a zoomed out map of Newfoundland and Labrador. There are many white circles with a number inside of them. These circles cluster all mineral showings in a particual area to make the map less busy. As you zoom into the app and play around you will see all sorts of mineral showings from accross the province. The grey transparent polygons overlaying the topography are the current (Janurary 2nd, 2023) minearl exploraiton claims on the island. You can click on any mineral showing or grey polygon for additonal details, as the above example shows for Buchans.

Thank you, and I hope you enjoy!

Chris W.
