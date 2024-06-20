# Used Car Market Study

This is a document for a personal project of mine, recording my effort to help my family and I find a new car.

## 1) Specification and needs - Planning Phase
We've outlayed in simple words our desires:
* Would cost 45-50k ILS max
* Good fuel economy
* Automatic transmission
* A reloaible car brand and model that will requie minimal maintanane
* our aspirations from a car:
    - Travel from A to B without public transport (at the very least to Tel-aviv and back)
    - Off-road & 4x4 driving caplibity for leasure
    - Carrying capacity for heavier-industrial loads
    - Carry at least 4 passsagnes in comfort
  
### What the questions im trying to answer?
* What are the total average stats of the current market?
* What is the effect of other, non-standard factors on price and by how much?
* How price deacy over previous ownerships?
* what is the most common and brand or car models in the market?
* Which region is the cheapest to buy at?
* How do specific models are in comparison to others in terms fo fuel economy, value, comfort and safety?
* I've seen that many liting include "special" features, what's their effect on price and should i bother buying a car with such things?
* Price trend over kilometrage (is there an optimal time to buy an older car?)
* is there an more optimal specs that give a favourble insurance rather than just buying the smallerst car possible?
* creative exploration:
  - corrarlation between price and: house power, engine size, owner, wheel-drive

### The data i'll be needing
* scraped 1200 car listing off Yad2
* selected to following filters:
    - vehicle type: קרוסאובר, ג׳יפ, רכב משפחתי, רכב מיני, מיניוואן, טנדר
    - Max price: 48000 ILS
    - Year of manufaccure: 2010 at the earliest
    - location: צפון, מרכז, השרון, חדרה
* Car price
* Fuel consumption rate
* Ownership #
* Car name and model, brand and sub-model
* where it sold
* engine size
* seats
* present features
* user ratings and their sub-cat ratings



## 2) Colletion Phase

1. I've headed to the one of the biggest online used car martket places, Yad2
2. Using WebScrapper.io start to outlay the data value and structures i want to extract
3. I've marked around 1400 lisitngs over the last 30 pages on that day (28/5)
4. Ran the scpits and got a table running 37k raw data points

## 3) Processing Phase
Now it was to convert the raw data into a dabase containing tables and categorized column values




