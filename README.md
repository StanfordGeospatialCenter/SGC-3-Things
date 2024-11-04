# SGC-Quickstart

 3 things you can do to jumpstart your use of spatial data in your research and teaching at Stanford (plus more if we have time!). 

 If you have any trouble getting into any of these resources, reach out to us at stanford-geospatial@stanford.edu 

## https://earthworks.stanford.edu 

* Basic search
* Using Facets
  * Resource Class (Roughly corresponds to where/how you would use it)
  * Data Type (Corresponds roughly to 'file type')
  * Provider (What institution is it coming from?)
  * Access (Is it public, or licensed?)
* Downloading
* Code Snippets Example [https://earthworks.stanford.edu/catalog/nyu-2451-34156]
* Cut&Paste to [Google Colab notebook](https://colab.research.google.com)

## ArcGIS Online [https://stanford.maps.arcgis.com]

* https://stanford.maps.arcgis.com SSO Login
* Landing page resources

### Clowns in ArcGIS Online

1. Search for "clowns" in earthworks.stanford.edu
2. Click on the geojson Export As Link, and then right-click and copy the download link
3. Sign into ArcGIS Online, go to Map and Add a Layer from URL
4. Paste the geojson link, and create a Hosted Feature Layer, which should be added to your map
5. Add another layer by searching ArcGIS Online for "congressional" and adding the "USA 118th Congressional Districts (All Territories)" to your map
6. CHange the order of layers
7. Analysis>Tools>Join Data>Spatial Join
	1. 	Input: Clowns
	2. Summary polygon layer: USA 118th Congressional Districts (All Territories)
	3. Output: Clown_Districts
	4. Create Clown Density Map
  

## Google Earth Engine

* Login to [The Google Earth Engine Code Editor](https://code.earthengine.google.com/) with your SUNetID and Password. [If this gives you problems, email stanford-geospatial@stanford.edu from your Stanford email address and ask for access to Google Earth Engine!]
* Check out to the SGC's [Earth Engine 101 tutorial](https://arcg.is/0DmS590)
* Once you are successfully logged in, you can [Clone the SGC Sample Scripts to your own Scripts Repo](https://arcg.is/0DmS590).
* For some more "Flashy" demonstrations, see our [LoveDataWeek Demo Scripts](https://code.earthengine.google.com/?accept_repo=users/maplesstanford/LoveData23SampleScripts)

# More! (time permitting)
## https://Planet.com 

* Getting access to Stanford's Planet.com Enterprise Account
* Searching with Planet Explorer
* Ordering imagery 
* Downloading Planetscope imagery
* Additional Planet Products:
  * [SkySat Archive Access](https://forms.gle/Qi5rC3PkF4gtGdyCA)
  * [SkySat Tasking](https://forms.gle/V9XowiVgcAfxPixi9)

## https://locator.stanford.edu
* What is geocoding?
* How to use locator
* Limitations

