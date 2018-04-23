# How to calculate routes from major roads using the Bing Map Route web service


<p>This example demonstrates how to calculate routes to the destination point from major roads using the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteDataProvider_CalculateRoutesFromMajorRoadstopic"><u>BingRouteDataProvider.CalculateRoutesFromMajorRoads</u></a> method.</p><p>Before route calculation, specify destination point coordinates (<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapGeoPoint_Latitudetopic"><u>GeoPoint.Latitude</u></a> and <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapGeoPoint_Longitudetopic"><u>GeoPoint.Longitude</u></a>). In addition, you can specify optional parameters: the destination name, driving or walking route travel mode using the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteOptions_Modetopic"><u>BingRouteOptions.Mode</u></a> property and route optimization options to calculate an optimal route either by time or by distance via the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteOptions_RouteOptimizationtopic"><u>BingRouteOptions.RouteOptimization</u></a> property.</p><p>To start the application, click the <strong>Calculate Routes From Major Roads</strong> button.  All parameters are passed to the <strong>CalculateMajorRouteRequest</strong> method, and you can see the results in the<strong> rich text box</strong> element and calculated routes on a map. </p><p>The requested results contain the total distance of a route, itinerary item (<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteResult_Distancetopic"><u>BingRouteResult.Distance</u></a>, <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteLeg_Distancetopic"><u>BingRouteLeg.Distance</u></a>, <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingItineraryItem_Distancetopic"><u>BingItineraryItem.Distance</u></a>), the time required to follow the calculated route (<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteResult_Timetopic"><u>BingRouteResult.Time</u></a>) and pass the rout leg and itinerary item (<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingRouteLeg_Timetopic"><u>BingRouteLeg.Time</u></a>, <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingItineraryItem_Timetopic"><u>BingItineraryItem.Time</u></a>). You can also see the maneuvers  associated with the itinerary item (<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingItineraryItem_Maneuvertopic"><u>BingItineraryItem.Maneuver</u></a>) and other parameters.</p><p>Note that if you run this sample as is, you will get a warning message informing that the specified Bing Maps key is invalid. To learn how to register a Bing Maps account and create a key for it, refer to the <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument15102"><u>How to: Get a Bing Maps Key</u></a> tutorial.</p><p><br />
</p>

<br/>


