# Creating a custom country

## 1. Register the country

* Open `common/country_tags/00_countries.txt`
* Add the custom country's tag into the last section `Modded-in tags`: \<Tag\> = countries/\<country file\>.txt

## 2. Create the country description file

* Create the file called `common/countries/\<country file\>.txt
* Prepare everything. Suggested: copy from a similar country in original game files
* Places to notice: `historical_idea_groups` for AI to behave

## 3. prepare the country infantry color

* Open `common/country_colors/00_country_colors.txt`
* Add the custom country's tag in the end of file
* follow the same structure as other countries, use some color picker to get some fitting RGB color

## 4. Give the country a culture

* Open `common/cultures/00_cultures.txt`
* Add the country's culture into a culture group where it fits, and set the country as primary
* Follow the same structure as others, make names as fit.