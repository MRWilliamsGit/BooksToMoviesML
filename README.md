# Books To Movies ML

This is a project to gain insight on what novels become profitable novel adaptations.</br>
Collaborators: Leo Corelli, Miranda Morris, Maria Williams

Data Sources:</br>
https://www.imdb.com</br>
https://www.librarything.com</br>
https://developer.nytimes.com

Code Files:</br>
NYTBestsellersAPI_history.ipynb - script to run New York Times API to pull the Bestsellers list</br>
IMDb_Scraper_Full.ipynb - script to create dataset of IMDb information</br>
Library_Thing_Scraper_Full.ipynb - script to create dataset of LibraryThing information</br>
Library_Thing_Cleanup.ipynb - scrip to clean Library thing files</br>
Leo_final.ipynb - script to combine, clean, and model data

Data Files:</br>
NYCBestsellers - file generated by NYTBestsellersAPI_history.ipynb</br>
IMDbScrapeFull, IMDbScrape2 - files generated by IMDb_Scraper_Full.ipynb</br>
CleanMovieData - IMDb files combined, cleaned, and reduced to observations with both budget and worldwide revenue figures</br>
LibraryThingFull - file generated by Library_Thing_Scraper_Full.ipynb</br>
libthing_clean1 - LibraryThing file with preliminary cleaning
Books To Movies Powerpoint - powerpoint slides to support presentation of project</br>

How to Run Demo:</br>
1) chromedriver must be installed</br>
2) run NYTBestsellersAPI_history.ipynb to generate list of New York Times bestsellers</br>
3) run IMDb_Scraper_Full.ipynb to generate IMDb dataset</br>
4) run Library_Thing_Scraper_Full, which uses CleanMovieData to generate LibraryThing dataset</br>
5) run Library_Thing_Cleanup.ipynb to perform preliminary cleanup of the LibraryThing dataset</br>
6) run Leo_final.ipynb to combine, clean, and model data
