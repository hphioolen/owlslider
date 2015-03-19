# owlslider
Integrate owl slider into sage project

Custom posttype slide toevoegen om de slides te laden


Todo
Formaten?
Volgorde?

# JAVASCRIPT aanpassingen
in Assets/scripts main.js de owl carousel aanzetten:
 
 // Home page
	'home': {
      init: function() {
        // JavaScript to be fired on the home page
         $("#owl-slider").owlCarousel({
	    
		    autoPlay: 6000,       
	        items : 1,
	        loop:true,
	        autoplay: true,
	        animateOut: 'fadeOut'
	       
	
		});

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