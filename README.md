# LeafletTransit 

## What

This is a LeafletJS-based prototype of a real time map for various transit systems, including Miami-Dade Transit and various trolley services.

Live demo is at https://miami-transit.netlify.app. Past demo is at http://www.qtrandev.com/transit

Reload the site often for the latest data to show. (Can use Shift + Reload button for full page refresh)  
Press F12 in your browser to view the Javascript console for any errors.

The following data are shown
* Live buses
* Routes of the live buses and their official route color
* Bus stops of the routes
* Citi bikes
* Points of interest

Depends on https://github.com/CyberStrike/miami-transit-api to retrieve data from http://www.miamidade.gov/transit. During night-time when no bus data is returned, no buses are shown.  
See https://github.com/qtrandev/MiamiTrolleyInfo for past transit related documentation.  

#### Status
Beta. Working out bugs and looking at design.

#### Screenshots
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot1.png" alt="Screenshot 1" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot2.png" alt="Screenshot 2" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot3.png" alt="Screenshot 3" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot4.png" alt="Screenshot 4" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot5.png" alt="Screenshot 5" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot6.png" alt="Screenshot 6" width="50%">
<img src="http://www.qtrandev.com/transit5/screenshots/screenshot7.png" alt="Screenshot 7" width="50%">

## Why
Shows where all the Miami transit options are. Goal: Can you go to one website and see where your bus is or where the citibikes are or where to get off for the landmarks like the American Airlines Arena, etc?

## Who

[Code for Miami](https://github.com/CodeforSouth)

## How
#### Dependencies

JQuery  
AngularJS  
Bootstrap  
LeafletJS  

#### Install

Download as a zip or checkout the files.

#### Deploy

Upload every file and folder to a web server handling static HTML pages.

#### Testing

Use a Javascript debugger to debug such as in Firefox or Chrome.

## Contribute

Pull requests are accepted.  
Add issues and features in issues list.
Make the change yourself by editing the file in the dev branch on GitHub and make a pull request.  
See https://github.com/CodeforSouth/getting-started/wiki/Contributor-Workflow

## Related Projects

[AndroidTransit](https://github.com/qtrandev/AndroidTransit) - Displaying Miami Transit information in an Android app.  
[MeteorTransit](https://github.com/qtrandev/MeteorTransit) - Displaying Miami Transit information in an Meteor app.  

## License

Licensed through Code for America [LICENSE.md file](https://github.com/codeforamerica/ceviche-cms/blob/master/LICENCE.md).

## Attributions

[Miami-Dade Transit](http://www.miamidade.gov/transit)  
[City of Miami Trolley](http://www.miamigov.com/trolley)  
[City of Doral Trolley](http://www.cityofdoral.com/index.php?option=com_content&view=article&id=149&Itemid=339)  
[Citi Bike Miami](http://citibikemiami.com)  
[Any Origin](http://anyorigin.com)  
