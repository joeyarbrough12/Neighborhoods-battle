{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-2-28545031ded9>, line 1)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-2-28545031ded9>\"\u001b[0;36m, line \u001b[0;32m1\u001b[0m\n\u001b[0;31m    Capstone Project Week 1.\u001b[0m\n\u001b[0m                   ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "Capstone Project Week 1.\n",
    "The Battle of Neighborhoods | Business obstacles\n",
    "Introduction:\n",
    "\n",
    "The object of this project is to help people understand the best places in their neighborhoods. \n",
    "By showing them step by step helps people to make the right decisions.This will help them to make smart and efficient decisions about choosing a good neighborhood among other neighborhoods in North York, Toranto.\n",
    "\n",
    "Many people move/travel to different states in Canada and need the right information to good housing prices, schools for their children and family. \n",
    "This project is for people looking for better neighborhoods. \n",
    "To facilitate access to cafe, school, super market, medical stores, grocery stores, mall, theater, hospital, like-minded people, etc.\n",
    "\n",
    "This project is created to find reasons why poeple migrtate North of Toronto to find a better neighborhood. \n",
    "apllication usually includes hoiusing square feet, vprice  and colleges, crime rates of that particular area, road conditions, \n",
    "weather conditions, city management for emergency, water and recreational facilities.\n",
    "\n",
    "It will help people become aware of the area and neighborhood before moving to a new city, state, country or place for work or to start a new life.\n",
    "Problem to solve:\n",
    "\n",
    "The main object of this project is to find a better neighborhood in a new city for the person who moves there. Social presence in society in terms of like-minded people. Connectivity to airport, bus stop, city center, markets and other daily needs nearby.\n",
    "\n",
    "    Sorted list of house in terms of housing prices in a ascending or descending order\n",
    "    Sorted list of schools in terms of location, wages, rating and reviews (reviews are very important)(never underestimate the reviews of a community)\n",
    "\n",
    "Location:\n",
    "Like realestate always say \"Location, Location and Location\".\n",
    "Toronto is one of the districts of Toronto, Ontario, Canada. it was one of the fastest-growing jobs and community growth of the region due to its proximity to Old Toronto. It was declared a borough in 1967, and later became a city in 1979, attracting high-density residences, rapid transit, and a number of corporate headquarters in North York City Centre, its central business district. In 1998, North York was amalgamated with the rest of Metropolitan Toronto to form the new city of Toronto and has since been a secondary economic hub of the city outside Downtown Toronto.\n",
    "Foursquare API:\n",
    "\n",
    "This project would use Four-square API as its prime data gathering source as it has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing and details about a business.\n",
    "Work Flow:\n",
    "\n",
    "Using credentials of Foursquare API features of near-by places of the neighborhoods would be mined. Due to http request limitations the number of places per neighborhood parameter would reasonably be set to 100 and the radius parameter would be set to 500.\n",
    "Clustering Approach:\n",
    "\n",
    "To compare the similarities of two cities, we decided to explore neighborhoods, segment them, and group them into clusters to find similar neighborhoods in a big city like New York and Toronto. To be able to do that, we need to cluster data which is a form of unsupervised machine learning: k-means clustering algorithm\n",
    "Libraries Which are Used to Develope the Project:\n",
    "\n",
    "Pandas: For creating and manipulating dataframes.\n",
    "\n",
    "Folium: Python visualization library would be used to visualize the neighborhoods cluster distribution of using interactive leaflet map.\n",
    "\n",
    "Scikit Learn: For importing k-means clustering.\n",
    "\n",
    "JSON: Library to handle JSON files.\n",
    "\n",
    "XML: To separate data from presentation and XML stores data in plain text format.\n",
    "\n",
    "Geocoder: To retrieve Location Data.\n",
    "\n",
    "Beautiful Soup and Requests: To scrap and library to handle http requests.\n",
    "\n",
    "Matplotlib: Python Plotting Module.\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python",
   "language": "python",
   "name": "conda-env-python-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
