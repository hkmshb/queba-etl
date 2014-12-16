
queba-etl
=========

A lightweight Extract-Transform-Load tool for QuEBA. 

It converts manually or teller compiled (computer generated) customer payment 
records into a format that is easily consumed by QuEBA.

This implementation provides a stand-alone web application which uses 
[Bottle](http://bottlepy.org), a micro web-framework for python. However, it is 
so structured to allow easy integration into a [Django](http://djangoproject.com) 
project.

