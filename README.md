# Post App

## Terms

All english terms written in uppercase relate to an element of the application.

**Item**: an Item is either a Package or a Letter. 

An Item has:
* a Type (Package or Letter)
* a Receiver
* a receive date.

**Package**: A Package is a post package.

**Letter**: A Letter is a simple letter (not unlike E-Mail but physical).

**Receiver**: A Receiver is the person who has received post.

A Receiver has:
* A Military Grade
* A name

**Military Grade**

A list of Swiss Military Grades can be found [here](https://de.wikipedia.org/wiki/Grade_der_Schweizer_Armee).

# Specification

## App

The app must work on modern browsers and must be usable in all common mobile phone formats. The app must be accessible by web.

## Configuration

Configuration should not be a criteria for the first version but it must be possible to easily change the deployment strategy for the app for further usage by others.

## Administration
### Add new Item

The Administrator must be able to add a new Item.

### Remove checked-out packages

The Administrator must be able to remove a checked out item. The removal of an Item is definitive.

## Check state of packages to check out

### List Packages and Letters (with arrival date and time sitting around)

A User must be able to see the list of currently listed packages for check out.

## Public stats about the amount of packages received over time

Users must be able to see the historical data about the amount of packages received per day.

# Todo

* Clarify specification (if needed).
* Rework the terms as table for better readability.
* ... Add new todos as time goes by and ~~strike~~ done elements
