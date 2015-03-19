# owlslider
Integrate owl slider into sage project

Custom posttype slide toevoegen om de slides te laden


Todo
Formaten?
Volgorde?



# Dependancies

OwlCarousel 2

Binnen dit pakket heb ik de main in bower aangepast, als dat mislukt of als er een nieuw pakket owl is geintalleerd, dan moet de bower op het project worden aangepast (kan altijd voor de zekerheid)

| pakket      | Overrides | 
|-------------|-----------|-------------|
| owlcarousel | Yes       | Main override in project aanpassen:

 "overrides": {
    "owl.carousel": {
      "main": [
        "./dist/owl.carousel.js",
        "./dist/assets/owl.carousel.css"
      ]
    },