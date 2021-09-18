# Project Proposal: Pokédek
By Kevin Duan, Janet Huang, and Matthew Zhang

## What?
Pokédek is a web app that helps people learn about their teammates to promote a more efficient and enjoyable working experience.

Through an interactive web editor, person can easily create their own Pokemon-inspired trading cards highlighting their superpowers, weaknesses, communication preferences, and more. Cards are compiled into a "dek" where people can view each other's cards and obtain a better understanding of who they will be working with.

Example Cards:
<img src="https://i.imgur.com/p3pRHFu.jpg" alt="kevin_card" width=30%/>   <img src="https://i.imgur.com/OPV7AJT.jpg" alt="janet_card" width=30%/> <img src="https://i.imgur.com/qxoVbZF.png" alt="matthew_card" width=30%/>



## Why?
Much of humanity's progress has come through collaboration (see Matt Ridley's take on the [exchange of ideas](https://economictimes.indiatimes.com/exchange-of-ideas-chief-source-of-innovation-matt-ridley/articleshow/9831254.cms)), and teams are becoming increasingly distributed with remote work. Regardless of what kind of work is taking place, a team's success comes down to their ability to work together. Thus, it's crucial for people to understand how their teammates best work, and that's where Pokédek comes in.

The use case for this concept has already been recognized by companies like [Figma](https://www.figma.com/community/file/814575098768004426) and Asana. Oftentimes, teams turn to designers to create cards on behalf of everyone else. This is not feasible in most team settings, so we hope to "democratize" the creation of team trading cards with Pokédek.

## For Whom?
Anyone working in a team environment can benefit from Pokédek. Effective collaboration is a common bottleneck for most teams, and Pokédek will set a strong foundation for your team's success whether you're starting a new group project at school or onboarding a new employee at work.

## How?
Someone from the team starts a deck, and other team members will be added to the deck (via email / link). 

All users create a card for themselves by populating a template through an interactive web editor (more details on this in Scope section). Completed cards are automatically added to the deck for all team members to view.

In the event a user is part of multiple teams (very likely), he/she can reuse the same card for all decks. A user can easily update his/her own card, and decks containing the card will the updated with the latest info. 

## Scope
Pokédek will require significant frontend and backend work, with an emphasis on the frontend load. 

We envision an interactive web editor where the user can populate the card data in the card itself – in other words, it's not just about filling out a plain form then carrying over that data into a card. The user would be able to click on the image rectangle to upload an image, move the slider by dragging their mouse, and edit text directly in the card template's text boxes. The frontend will thus require managing complex interaction effects and styling and potentially caching / debouncing design.

For the backend, the API can be very straightforward an consist of primarily CRUD endpoints. The data model will rely on individual cards, and a "deck" can simply be a container of card / user IDs. 

