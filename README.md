# Art-Gallery
Database Management Project
ER Diagram
Relational Diagram - BCNF form
Query

Database for keeping Art object records at National Art Gallery


Scope of Database:

It involves keeping records of all art object details: types of the art in the inventory, artist associated with the art, the intrinsic art style of the artist, prices for which arts are bidded and sold, buyers of the art objects of various types, places where the gallery conducts the exhibitions, details of arts showcased in each exhibition, venue of the exhibition affiliated with art displays.

Description:

National Art Gallery conducts a number of exhibitions at various locations across the country. These exhibitions offer a wide display of art objects in them. For these art objects to be showcased into various of their art exhibitions, they keep a considerably good stock of inventory round the clock. Any art is a unique piece by the artist. So it can be displayed at only one single exhibition at a specific time.

An art object can be of three types: Painting, Sculpture or a Print Making. Each art has it artist. These artists are affiliated to the art gallery as the major or regular contributors. Each exhibition conducted at a time have some amount of art pieces displayed from the inventory available at that time. Some arts are not for sale but just meant for show case while the rest are for bidding. At the end of an exhibition if the art is not yet sold, it will remain intact in the inventory and can be displayed again in some other exhibition. Now based on the buyer and the price at which he buys an art, the total earnings of the Art Gallery will be accounted for a year.

For an art, typically we record and maintain attributes: Art Title, Art ID, Artist ID, Art type, Year of intake, Sale status. For each art, we record its minute details based on how is it made, with what material is it made, who is artist by attributes: Art ID, Material, Height, Weight, Width, Paint Type, etc. For each exhibition entries we record attributes: Art ID, Art Title, Exhibition Name. Likewise whenever an art piece is sold at a price after bidding, the record will be added in the Sold Objects table. 

Following are some sample queries :-

List all the Artists which are from India.
List all the Arts which are used in London Art Gallery in year 2016
List all the Painting Arts of type “color paint” and height < 15 inches
List the title and  object type of Art of style “Abstract”

