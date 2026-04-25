# Stamp Rally

## Your role

you are a senior web designer building single page website as a developer.

## Business Context
<BusinessContext>
Louisville Hindi Paathshaala (Louisville Hindi School) is organizing its annual Holi Mela (Spring Festival), taking place on Sunday, April 26th, from 12 PM to 6 PM, at 4213 Accomack Dr, Louisville, KY 40241.

Holi, widely known as the Festival of Colors, is one of India’s most joyful spring celebrations. The festival represents the spirit of love, happiness, and togetherness. In recent years, Holi has gained remarkable popularity across Europe and North America, inspiring major cultural events and “Color Run” celebrations on university campuses and in cities nationwide. Its inclusive nature transcends boundaries of race, age, and background, bringing communities together in a vibrant expression of unity.

This year’s Holi Mela will feature a lively blend of Indian cuisine, carnival games, cultural workshops, music and dance performances, and a diverse marketplace of clothing and jewelry vendors. Beginning at 3 PM, the festivities will culminate in the traditional color play, where participants joyfully apply dry colors to friends, family, and fellow attendees.

The event will also highlight the service and leadership of local youth, with volunteer support from Beta Clubs across Louisville’s high schools. We anticipate the presence of local government officials as honored guests.

In this festival, we will counters of 10 vendors. list of vendors, their names & logo is available in the, "List of Vendors" section.

index.html in this folder is the static single page website for this Holi festival and is deployed and running successfully on https://louisvilleholi.com

</BusinessContext>

## List of Vendors

## Functional Requirements
<FunctionalRequirements>
1. If the users visit the counters of these vendors and scan the QR code printed on a physical paper through thier phone then they are eligible for a lucky draw prize. 
2. We need to have a QR code that opens the website https://louisvilleholi.com in the URL it also sends some secure and unique identifier of the vendor.
3. If one user scans the same QR code twice then it should be counted as one stamp.
4. stamps should be displayed as a tile with vendor logo in the tile and vendor name under the tile. 
5. when user scans all the 10 the vendor QR codes then a button is enabled or displayed that says submit these stamps and get eligible for a lucky draw. their should be a text box displayed too where a user must enter an email address before submitting the stamps.
6. We should not allow user to submit stamps without entering email address.
7. email address should accept email address only that should be validated with regular expression.
8. there should be a counter that should tell how many stamps are stamped and how many pending.
9. Stamps and email address would be stored in local storage of the browser in mobile phone and computer browser. 
10. on the click of submit stamp button submit the stamp vendor name, timestamp, email address to a Google spreadsheet exposed through an app script.
11. There should be a reset button that will let them clear all the stamp and email address from the local storage of the phone or computer.
12. if the email address is available in the storage then email address text box should load email address from thier so that the user does not have to type it again.
13. when the QR code is scanned and website opens on the phone browser then Vendor identity is automatically extracted from the URL and stamp is loaded.
14. if for some unforeseen reason user has stamp collected on their phone submit function is not working then display a message they can walk to the Hindi Paathshala counter and submit their stamps manually by taking help from Hindi Paathshala committe representative on the counter. 
15. Print QR codes seperately for all 10 vendors in the, "List of vendors" <ListOfVendor> section seperately so that I can print it seperately and give it to the vendors to print it and Keep it on thier counter. QR code prinout for vendors should include QR Code, Vendor name and thier logo.
16. this stamp rally should be in its own section under hero section of the website.
17. stamp rally should be added to the menu items of the website too.
</FunctionalRequirements>


## Non Functional Requirements
<NonFunctionalRequirements>
1. 95% of the visitors of this website will access this site from thier mobile phone browser. they will use all kinds of phones. e.g. iPhone, Android etc.
2. Try to make it as much secure as we can reasonably make it.
3. when the QR code is scanned and website opens in the browser then it should straight go to the stamp rally section         
<NonFunctionalRequirements>

## what do I need
1. Update index.html to add the functional and non functional requirements listed in, "Functional Requirements"<FunctionalRequirements> and "Non Functional Requirements" <NonFunctionalRequirements> section.

remove the button, "print QR Codes for vendors(organizers only)" from the index.html website. I dont want to show this to the visitors or users of this website. Instead create a new page where we have QR codes for vendors and generate the QR codes with the website domain is https://louisvilleholi.com instead of localhost. 


I have 20 years of experience in software development and working in fortune 40 company as a principal architect and engineer leading a large team for building multi cloud data streaming and data integration platform. I want to do some university eduation to further my career and setup myself for success as I move to middle management to senior leadership roles and also 


Create a new section named, "Stalls & Booths" and the below vendors in that section. These vendors should particiate in the stamp rally feature. for the vendors that have logo use their logo in stamp and for the vendor that does not have logo just use their text short name in the tile

Russian School of Mathematics, Category - Student Education, logo - rsm.png
Rasa & co llc, Category - Clothing & Accesories, No Logo, ShortName - RASA
PureJoy Jewelry, Category - Clothing & Accesories, No Logo, ShortName - PureJoy
Kumon of Springhurst, Jeffersontown and Clarksville, Category - Student Education
Taattva, Category - Clothing & Accesories ShortName - Taattva
Mudra Wealth Creation, Category - Financial Planning, ShortName - MW
Happy collections, Category - Clothing & Accesories, ShortName - HC
Save Soil, Category - Public Awareness, logo - savesoil.png
Laxmi Management, Category - Financial Services, shortName - LM

