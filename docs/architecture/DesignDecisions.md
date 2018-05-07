Design Decisions
================

## Usage of NINE

NINE will be used as our API to get the List of Courses and/or details of Courses. 

Why using NINE:
- NINE is already being used by many other Departments. (Standard for many other Departments)
- NINE has already some useful APIs integrated
- Integrating our own API functionality will be supported by the maintainer of NINE

Currently supported APIs by NINE can be found [here](https://nine.wi.hm.edu/help).

## Web-Interface for the administrators

There will be a Web-Interface for the Administrators.

The Web-Interface must do the following things:
- Add Courses to the Course List
- Change Courses and Course Description
- Export Excel/CSV/(or similar) of the taken Courses from the Students
- Send Messages

### Why choose a Web-Interface?

A Web-Interface gives the Admin more freedome and simplicity. Changing the Course-List or Details via a App is probably more difficult and confusing than doing it on a PC. 
The other option would be to implement the Admin features into the App itself.... but this would be way more effort and not as clear as a Web-Interface.
