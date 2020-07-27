<div class="article"><h1 ><font color="#AAA">class </font>GoToActionError</h1></div>

~~~java
 class GoToActionError extends DJIError 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.mission.error</td></tr><tr valign="top"><td width=15%><font color="#999"><i>Inherits From:</i></td><td width=85%><font color="#999"><code><a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></code></td></tr></table></html>



##### Description:



<font color="#666">The error codes for the <code><a href="/Components/Missions/DJIGoToAction.html#djigotoaction">GoToAction</a></code>.



##### Class Members:



#### Members

<div class="api-row" id="djigotoaction_djigotoactionerror_invalidaltitude"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">final</div><div class="api-col right"><a class="trigger" href="#djigotoaction_djigotoactionerror_invalidaltitude_inline">INVALID_ALTITUDE</a></div></div><div class="inline-doc" id="djigotoaction_djigotoactionerror_invalidaltitude_inline"

><div class="article"><h6 ><font color="#AAA">final </font>INVALID_ALTITUDE</h6></div>

~~~java
 static final GoToActionError
        INVALID_ALTITUDE = new GoToActionError("Altitude of the GoToAction Waypoint mission is not valid, its value should in the range [-200, 500]")
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.mission.error</td></tr></table></html>



##### Description:



<font color="#666">Altitude of the <code><a href="/Components/Missions/DJIGoToAction.html#djigotoaction">GoToAction</a></code> Waypoint mission is not valid, its value should  be in the range [-200, 500].

</div>

<div class="api-row" id="djigotoaction_djigotoactionerror_invalidcoordinates"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">final</div><div class="api-col right"><a class="trigger" href="#djigotoaction_djigotoactionerror_invalidcoordinates_inline">INVALID_COORDINATE</a></div></div><div class="inline-doc" id="djigotoaction_djigotoactionerror_invalidcoordinates_inline"

><div class="article"><h6 ><font color="#AAA">final </font>INVALID_COORDINATE</h6></div>

~~~java
 static final GoToActionError
        INVALID_COORDINATE = new GoToActionError("GPS Coordinate of the GoToAction Waypoint is not valid. "
                                                                + "Lattitude valud should in the range [-90f, 90f] and longitude value should in the range [-180f, 180f]")
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.mission.error</td></tr></table></html>



##### Description:



<font color="#666">GPS Coordinates of the GoToAction Waypoint is not valid. Latitude value should be in  the range [-90f, 90f] and longitude value should be in the range [-180f, 180f].

</div>

<div class="api-row" id="djigotoaction_djigotoactionerror_invalidflightspeed"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">final</div><div class="api-col right"><a class="trigger" href="#djigotoaction_djigotoactionerror_invalidflightspeed_inline">INVALID_FLIGHT_SPEED</a></div></div><div class="inline-doc" id="djigotoaction_djigotoactionerror_invalidflightspeed_inline"

><div class="article"><h6 ><font color="#AAA">final </font>INVALID_FLIGHT_SPEED</h6></div>

~~~java
 static final GoToActionError
        INVALID_FLIGHT_SPEED = new GoToActionError("Flight speed of the GoToAction Waypoint is not valid, its value should be in the range [2, 15]")
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.mission.error</td></tr></table></html>



##### Description:



<font color="#666">Flight speed of the GoToAction Waypoint is not valid. Value should be in range [2, 15] m/s.

</div>



##### Inherited Methods:

<div class="api-row" id="djierror_djisdkflighthuberrorforcode"><div class="api-col left">dji.common.error.DJIError</div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_djisdkflighthuberrorforcode_inline">getDJIError</a></div></div><div class="inline-doc" id="djierror_djisdkflighthuberrorforcode_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDJIError</h6></div>

~~~java
 static DJIError getDJIError(int errorCode) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Returns the specific error in the <code><a href="/Components/SDKError/DJIError_DJISDKFlightHubError.html#djierror_djisdkflighthuberror">DJIFlightHubError</a></code> according to the error code.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">int <font color="#000">errorCode</td><td><font color="#666"><i>errorCode for <code><a href="/Components/SDKError/DJIError_DJISDKFlightHubError.html#djierror_djisdkflighthuberror">DJIFlightHubError</a></code>.</i></td></tr></table></html>

##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">static <a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></td><td><font color="#666"><i>An NSError object initialized with errorCode. If the errorCode was 0, returns nil.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_djiutmisserrorforcodewitherrorcode"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_djiutmisserrorforcodewitherrorcode_inline">getDJIError</a></div></div><div class="inline-doc" id="djierror_djiutmisserrorforcodewitherrorcode_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDJIError</h6></div>

~~~java
 static DJIError getDJIError(int errorCode) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.utmiss</td></tr></table></html>



##### Description:



<font color="#666">Get DJIUTMISSError.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">int <font color="#000">errorCode</td><td><font color="#666"><i>An int value of error code.</i></td></tr></table></html>

##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">static <a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></td><td><font color="#666"><i>An object of <code><a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></code>.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_getdescription"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_getdescription_inline">getDescription</a></div></div><div class="inline-doc" id="djierror_getdescription_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDescription</h6></div>

~~~java
 String getDescription() 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Returns the description of the error code.



##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">String</td><td><font color="#666"><i>The description of the error code.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_setdescription"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_setdescription_inline">setDescription</a></div></div><div class="inline-doc" id="djierror_setdescription_inline"

><div class="article"><h6 ><font color="#AAA">method </font>setDescription</h6></div>

~~~java
 void setDescription(String desc) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Sets the description for the error code.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">String <font color="#000">desc</td><td><font color="#666"><i>Description string.</i></td></tr></table></html></div>

