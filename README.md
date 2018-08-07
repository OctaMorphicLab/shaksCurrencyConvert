Shaks Testing Composer Library
=========================

hello muntaha, this is for you testing my composer library. 


Requirements
============

* PHP >= 5.5

Installation
============

    composer require shakeelcse09/shaks-currency:dev-master

Add the autoload in index.php if not inclded

	include_once 'vendor/autoload.php';

Usage
=====

In the Controller, use this trait

    use shakeelcse09/ShaksCurrency/ShaksCurrency;
    
in the method 

    $shaks = new ShaksCurrency();
    echo $shaks->greetings('muntaha');  // returns "hello muntaha"



Credits
=======

* Logicians Ponir about pip discussion
