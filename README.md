# Happynews
A Hackernews clone, except for happy news. Built using GraphQL, graphene and Django.

# Motivation
Was feeling somewhat down in the dumps and needed a pick-me-up. Simultaneously, I wanted to make a GraphQL server. I managed to accomplish both.

# Tech and Frameworks Used
Django, GraphQL and Graphene. No frontend, rip, but all queries and mutations work in Insomnia and GraphiQL. Also got fancy with GraphQL Relay at the end.

# Special Features
Users are able to search for keywords in descriptions for related links. It also implements pagination.

# Installation
If you plan to run this (which I hope you do) do note this was the virtual environment I was working with: 
aniso8601==7.0.0
Django==2.1.4
django-environ==0.4.5
django-filter==2.0.0
django-graphql-jwt==0.1.5
graphene==2.1.8
graphene-django==2.2.0
graphql-core==2.3.1
graphql-relay==2.0.1
promise==2.3
PyJWT==1.7.1
pytz==2019.3
Rx==1.6.1
singledispatch==3.4.0.3
six==1.14.0

# How to Use?
Search for articles. Post articles. Cast votes for articles that make you happiest! Do all this through queries and mutations.

# Credits
Shoutout to this tutorial for being incredibly clear and easy to follow. One of the best tutorials I've found for GraphQL integration with Django: https://www.howtographql.com/graphql-python/0-introduction/

