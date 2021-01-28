<h3>What To Predict?</h3>
<hr>
The natural log of the sum of all transactions per user.
<br><br>

<h3>What Features Are in The Data?</h3>
<hr>
<table>
  <tr>
    <td>1</td>
    <td><b>fullVisitorId</b></td>
    <td>A unique identifier for each user of the Google Merchandise Store.</td>
  </tr>
  <tr>
    <td>2</td>
    <td><b>channelGrouping</b></td>
    <td>The channel via which the user came to the Store.</td>
  </tr>
  <tr>
    <td>3</td>
    <td><b>date</b></td>
    <td>The date on which the user visited the Store.</td>
  </tr>
  <tr>
    <td>4</td>
    <td><b>device</b></td>
    <td><i>[nested jstor]</i> The specifications for the device used to access the Store.</td>
  </tr>
  <tr>
    <td>5</td>
    <td><b>geoNetwork</b></td>
    <td><i>[nested jstor]</i> This section contains information about the geography of the user.</td>
  </tr>
  <tr>
    <td>6</td>
    <td><b>socialEngagementType</b></td>
    <td>Engagement type, either "Socially Engaged" or "Not Socially Engaged".</td>
  </tr>
  <tr>
    <td>7</td>
    <td><b>totals</b></td>
    <td><i>[nested jstor]</i> This section contains aggregate values across the session.</td>
  </tr>
  <tr>
    <td>8</td>
    <td><b>trafficSource</b></td>
    <td><i>[nested jstor]</i> This section contains information about the Traffic Source from which the session originated.</td>
  </tr>
  <tr>
    <td>9</td>
    <td><b>visitId</b></td>
    <td>An identifier for this session. This is part of the value usually stored as the _utmb cookie. This is only unique to the user. For a completely unique ID, you should use a combination of fullVisitorId and visitId.</td>
  </tr>
  <tr>
    <td>10</td>
    <td><b>visitNumber</b></td>
    <td>The session number for this user. If this is the first session, then this is set to 1.</td>
  </tr>
  <tr>
    <td>11</td>
    <td><b>visitStartTime</b></td>
    <td>The timestamp (expressed as POSIX time).</td>
  </tr>
  <tr>
    <td>12</td>
    <td><b>hits</b></td>
    <td><i>[nested jstor]</i> This row and nested fields are populated for any and all types of hits. Provides a record of all page visits.</td>
  </tr>
  <tr>
    <td>13</td>
    <td><b>customDimensions</b></td>
    <td><i>[nested jstor]</i> This section contains any user-level or session-level custom dimensions that are set for a session. This is a repeated field and has an entry for each dimension that is set.</td>
  </tr>
  <tr>
    <td>14</td>
    <td><b>totals</b></td>
    <td>This set of columns mostly includes high-level aggregate data.</td>
  </tr>
</table>
<br><br>

<h3>Data Cleaning and Wrangling</h3>
<hr>
<br><br>

<h3>EDA</h3>
<hr>
<br><br>

<h3>Modeling</h3>
<hr>
