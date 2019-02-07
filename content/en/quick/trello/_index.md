+++
title = "Trello"
weight = 20
+++

## Trello sample

This example shows how using the semantic model, you can set the rules for moving cards in a Trello board to manage a hypothetical business process.

{{% button href="SemanticTrelloBoard.zip" icon="fas fa-download" %}}Download Trello sample project{{% /button %}}

## Setup project

1. Extract the archive and open **SemanticTrelloBoard** folder in MPS as a project(File->Open->(select folder in window)).
1. Choose solution on the left pane [s]SemanticTrelloBoard ([s] - icon means that this is solution);  
1. Right click on it and choose from the popup menu *Module Properties* -> Java tab -> and click «+» under *Libraries* section; then choose file SemanticTrelloBoard.jar located in *libs* folder under **SemanticTrelloBoard** folder. The window *Model Roots* will appear, in this window select *java_classes* from the dropdown list.
1. If you have empty line before line with SemanticTrelloBoard.jar in *Libraries* section. Then click *Apply* button and *OK* button.
1. In the main MPS menu choose *Run -> Edit Configurations* -> change working directory to **SemanticTrelloBoard** folder
1. Click Build -> Rebuild project

## Configure
In predicate 'start' of TrelloBoard semantic model you can see call to domain function **TrelloBoard.DLS.start** with 4 arguments: **app key**, **delay time** in milliseconds, **board id**, and **access_token**. This is configuration parameters for **TrelloBoardDSL** domain model, you may want to change these parameters, if you want to connect this example semantic model with your own trello board. Or just leave those from the example to connect to [d0sl example trello board](https://trello.com/b/r0W9zMhZ/d0sl-sample-project)

### How to get *app key* and *access_token* for your own trello board
1. First, you need to get *app key*. To do this:
    - Login to trello
    - Go to [https://trello.com/app-key](https://trello.com/app-key)
    - Save your api *app key* and put it into the first argument 
2. Then you need get *access_token*. Here is the guide on how to get it [here](https://developers.trello.com/page/authorization).
3. You can get *board id* from your board’s  URL. For example, d0sl sample’s trello board URL is ```https://trello.com/b/r0W9zMhZ/d0sl-sample-project```, and *board id* is ```r0W9zMhZ```
4. Delay time means time between updates(calls to the predicate *checkBoard* in the example semantic model)

{{% notice warning %}}
The name of predicate should be _checkBoard_ and it's args are standard. DO NOT CHANGE THEM!
{{% /notice %}}

## Run
Just choose *Run..* from the popup menu on the *TrelloBoard* model(Right-click on TrelloBoard -> run 'Node test')
