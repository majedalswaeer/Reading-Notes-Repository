# REST

## Who is Roy Fielding?
* Ans: Roy Fielding wrote the first web servers, that sent documents across the internet,also, he he did a ton of research explaining why the web works the way it does.

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?
* Ans: because we just needed to talk to a small group of machines.also, they weren't designed to be used like that.

## What is the HTTP protocol that Fielding and his friends created?
* Ans: the protocol was about applying verbs to nouns, like when we go to a web page the browser does an HTTP GET on the URL you typed in and back comes a web page.

## What does a GET do?
* Ans: when we are using a web browser, browsers pretty much just GET stuff. They don't do a lot of other types of interaction with resources. This is a problem because it has led many people to assume that HTTP is just for GET'ing. But HTTP is actually a general purpose protocol for applying verbs to nouns.

## What does a POST do?
* Ans: means one system needs to add something to another system.

## What does PUT do?
* Ans: means one system wants to replace something in another system.

## What does PATCH do?
* Ans: to do a partial update we use PATCH