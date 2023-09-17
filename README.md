# Mars-Data-Scrape (Module 11 Challenge)

![nicolas-lobos-kGtFjYdm7DI-unsplash](https://github.com/ryodaimatsui/mars-data-scrape/assets/137141385/9f3563b9-7155-47a5-8a78-6fcc58ed28e4)


This challenge, titled ‘Mars-Web-Scrape,’ consists of two distinct parts, with the focused centered on becoming familiar and proficient in scraping data from a given URL.  The first part provides the title and preview summary of articles scraped and extracted from a website and properly stored in a list of dictionaries. To achieve this, the “Browser” from the Python framework known as “Splinter” and the Python library called “BeautifulSoup” are imported.

Similar to the first part, the second part of the challenge utilizes the aforementioned Python library (i.e., BeautifulSoup) and the module "Browser" from the "Splinter" framework, to scrape data from an HTML table. This table contains the following data:

-	‘id’: the identification number of a single transmission from the Curiosity rover
-	‘terrestrial_date’: the date on Earth
-	‘sol’: the number of elapsed sols (Martian days) since Curiosity landed on Mars
-	‘ls’: the solar longitude
-	‘month’: the Martian month
-	‘min_temp’: the minimum temperature, in Celsius, of a single Martian day (sol)
-	‘pressure’: The atmospheric pressure at Curiosity's location
                                              (Source: Penn Data Science Bootcamp)

From the extracted data, a list of lists is created in order to generate a Pandas dataframe for easier viewing. Consequently, the dataframe allows for the changing of data types to ensure that the data is ready for analysis. 

The analysis section includes the calculation of the number of months on Mars, the number of Martian days’ worth of data that exist, the average minimum temperature on the planet, the average daily atmospheric pressure, and the number of terrestrial days that exist in a Martian year. Utilizing this information, several plots are created for data visualization, as seen in the following image.

<img width="668" alt="Screenshot 2023-09-17 at 10 21 14" src="https://github.com/ryodaimatsui/mars-data-scrape/assets/137141385/0a3da38d-838f-45f5-a870-38a7636793df">

As a note, a CSV file containing the data from the dataframe in the second part of the challenge can be found in the "notebooks" folder of this repository. 

