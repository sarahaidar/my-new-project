
# Painting with AI
Final project for the Building AI course
## Summary
The goal of this project is to develop a recipe recommendation system that offers recipes based on user preferences, dietary constraints, and available ingredients. The technology will use machine learning techniques to present the user with personalized cooking suggestions.
## Background
Many individuals struggle to find fresh and intriguing recipes to cook at home, and they frequently end up cooking the same foods over and over. Furthermore, those with dietary limitations may have difficulty finding recipes that meet their requirements. This project seeks to address these issues by offering tailored recipe recommendations.
## How is it used?
The user will enter into the system their dietary restrictions, preferred ingredients, and any other preferences. This information, combined with machine learning techniques, will be used by the system to offer recipes that meet the user's preferences. The user can then browse the suggested recipes and choose one to prepare. Users may also be able to review recipes and submit input, further personalizing the recommendations.
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Hamburger and fries]
(https://www.pexels.com/sv-se/foto/brod-mat-smorgas-restaurang-2983101/)
![Brownie]
(https://unsplash.com/photos/LjtviHokbr4.jpg)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
   totPop = sum(pop)
   totFish = sum(fishers)
   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
main()
```
## Data sources and AI methods
A database of recipes and their ingredients, as well as information about the user's tastes and dietary constraints, will be used by the system. To produce tailored recipe recommendations, machine learning algorithms such as collaborative filtering, content-based filtering, and natural language processing may be employed.
[Twitter API](https://developer.twitter.com/en/docs)
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
## Challenges
Ensure that the recommendations are correct and appropriate to the user's preferences is one of the project's challenges. Furthermore, there may be ethical concerns about advocating recipes that are harmful or may hurt someone with certain dietary restrictions.
## What next?
Additional functionality like as meal planning, grocery list production, and connectivity with smart home devices could be added to the project. Collaboration with nutritionists and chefs may help increase the quality of the recipe suggestions.
## Acknowledgments
* Precipe ideas and insperation from https://recept.se and https://www.koket.se 
* Food images from Unsplash and Pexels
 <br>[Köket](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks)
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
