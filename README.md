# MarvelSuperHero


This is marvel super  hero details web applicaton

There are 4 main functionality inside it

1.To fetch all the marvels superhero from marvel website and display them on home page

2.Whenever user type inside search input box , it should filter the superhero with respect to name

3. Whenever user click on any of the superhero name a new webpage with lots of more information about superhero
like name , image , description , comics ,stories should be displayed there .

4.There are this favourite and unfavourite button on click of which superhero should be added to
favourite suprhero list and this list should be displayed on click of navbar button
![image](https://github.com/sargam-thakare/MarvelSuperHero/assets/76519988/51468a12-df71-405d-9593-b2c05eb37119)



1. To display all the superhero we are using fetch API to fetch all records of superhero from marvel api
and storing those inside an array and to create list we are using Unorderd list and apply map function over array
and mapping array data inside list item and appeding that to UL.
Also we are adding favourite button to it on click of which it will e added to other array with name myfavsuperhero

2.Whenever user click on name of any superhero , we are adding on click listener and passing the superhero character id to URL
and on the superhero details page we are fetching the superhero character id through url and fetching data of that hero
and pushing that data inside array and displaying the data

![image](https://github.com/sargam-thakare/MarvelSuperHero/assets/76519988/44e4aaa4-56b6-48d5-9538-4972616b205e)


3.To search the superhero, we are comparing the value inside search field with name of all superhero anf filtering out the list

4.If user click on fav button it will be comnverted to unfav button and that superhero will be added to myfavsuperhero array list
and when user click os unfav that superhero will be removed from that list. and that list is iterated over on the favourite superhero page
