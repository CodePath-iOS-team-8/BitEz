Original App Design Project - README Template
===

# Bitez

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Bitez is an app that allow users to share their food experience with each other! 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Food & Drink Sharing
- **Mobile:** Users make posts using camera
- **Story:** Like to share food reviews and what you friends are eating? BitEz is here to help you!
- **Market:** Fairly small, little to no similar apps
- **Habit:** Daily basis for food
- **Scope:** Among friends, should be not so hard to scope

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
* Users can create accounts that they can sign up and log in to. 
* Users can upload a photo to the app along with a description
* Users can search for the location of the restaurant by giving restaurant name, correlating to the location their photo is taken; 
* Users cannot see other user's post until they have posted. 

**Optional Nice-to-have Stories**

* Users can leave comments on 
* Users can click on "learn more" and get information of the specific restaurant on a new view controller. 

### 2. Screen Archetypes

* Login Screen
   * Users can log in
* Sign up Screen
   * Users can sign up 
* Feed Screen
    * Uers can view a feed of posts 
    * Users cannot see the unblurred posts until they make a post themselves. 
* Post Screen
    * Users can post a new photo to their feed
    * Users can post a description'
* Search Screen
    * From Post screen, Users can choose the specific restaurant given the location the picture is taken, and the name of the restaurant 
* Restaurant Screen
    * Users can see information about the restaurant, including hours, images, rating, and website.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Screen 

**Flow Navigation** (Screen to Screen)

* Login Screen
   * -> Feed Screen 
* Sign up Screen
   * -> Login Screen
   * -> Feed Screen 
* Feed Screen
   * -> Post Screen -> Search Screen
   * -> Restaurant Screen

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="https://i.ibb.co/4T3PWF3/IMG-E20-EAE14878-F-1.jpg" alt="IMG-E20-EAE14878-F-1" width="600">

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
