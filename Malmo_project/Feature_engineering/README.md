<h2 id="feature-engineering">Feature engineering</h2>


<ul>
<li>Feature</li>
</ul>


<table width=100% valign=top >
  <tr>
    <td width=10%>Short version</td>
    <td width=20%>Feature</td>
    <td>Description</td>
    <td width=20%>Used libraries / Source</td>
  </tr>
  <tr>
    <td colspan="4">Landuse features - Share of h3 grid cell</td>
  </tr>
  <tr>
    <td>f0</td>
    <td>landuse_0</td>
    <td>Residential building land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f01</td>
    <td>landuse_1</td>
    <td>Special residential building land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f03</td>
    <td>landuse_3</td>
    <td>Commercial land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f04</td>
    <td>landuse_4</td>
    <td>Industrial land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f05</td>
    <td>landuse_5</td>
    <td>Water area</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f07</td>
    <td>landuse_7</td>
    <td>Land for community facilities</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f08</td>
    <td>landuse_8</td>
    <td>Railway land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f12</td>
    <td>landuse_12</td>
    <td>Special building land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f13</td>
    <td>landuse_13</td>
    <td>Special building land for a specific purpose</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f14</td>
    <td>landuse_14</td>
    <td>Redevelopment area</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f15</td>
    <td>landuse_15</td>
    <td>Agricultural land</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f16</td>
    <td>landuse_16</td>
    <td>Religion</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f17</td>
    <td>landuse_17</td>
    <td>Education</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f18</td>
    <td>landuse_18</td>
    <td>Green space</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f19</td>
    <td>landuse_19</td>
    <td>Buildings of all kinds</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td colspan="4">Number of all POIs within k-neighbour cells</td>
  </tr>
  <tr>
    <td>f20</td>
    <td>poi_20</td>
    <td>Stores, service providers, restaurants, cafés, bars</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f21</td>
    <td>poi_21</td>
    <td>Sports centers, gyms, soccer fields, running tracks</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f22</td>
    <td>poi_22</td>
    <td>Hotels</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f25</td>
    <td>poi_25</td>
    <td>Healthcare facilities</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f26</td>
    <td>poi_26</td>
    <td>Elementary, secondary schools</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f27</td>
    <td>poi_27</td>
    <td>Kindergartens</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f28</td>
    <td>poi_28</td>
    <td>Event venues, theatres, movie theatres, museums</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f29</td>
    <td>poi_29</td>
    <td>Libraries</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f30</td>
    <td>poi_30</td>
    <td>Public institutions</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f31</td>
    <td>poi_31</td>
    <td>Tourist attractions</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td colspan="4">Distance to the closest object of the corresponding category in m</td>
  </tr>
  <tr>
    <td>f32</td>
    <td>dist_32</td>
    <td>University</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f33</td>
    <td>dist_33</td>
    <td>Bus station</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f34</td>
    <td>dist_34</td>
    <td>Railway station / Light rail station / Metro</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f35</td>
    <td>dist_35</td>
    <td>Cycle paths</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td>f36</td>
    <td>dist_36</td>
    <td>Arterial road</td>
    <td>osmnx</td>
  </tr>
  <tr>
    <td colspan="4">Number of persons living within a grid cell</td>
  </tr>  
  <tr>
    <td>f38</td>
    <td>pop_38</td>
    <td>Population</td>
    <td>[RegSo](https://www.statistikdatabasen.scb.se/pxweb/en/ssd/START__BE__BE0101/)</td>
  </tr>
  <tr>
    <td colspan="4">Target</td>
  </tr>
  <tr>
    <td>target</td>
    <td>outgoing_trips</td>
    <td>Number of e-scooter trips that started in each grid cell during the observation period</td>
    <td>raw data</td>
  </tr>
</table>



- The approach for determining the features of a dataset for machine learning models largely follows the approach outlined in the paper ["Prediction of Bike-sharing Trip Counts."](https://onlinelibrary.wiley.com/doi/10.1111/gean.12354)