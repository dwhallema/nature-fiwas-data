<a
name="Top" />
<h1>Wildland fire impacts on water supply (FIWAS) data for the contiguous United States</h1>

Authors: Dennis W. Hallema, Ge Sun, Peter V. Caldwell and Steven G. McNulty (Edited by David J. Rugg).  

Description: Wildland fire impacts on water supply (FIWAS) data for the contiguous U.S., used in our 2018 Nature Communications paper. These data were used as part of an assessment of these impacts in affected locations, and their management implications. 

How to Cite: These data were collected using funding from the U.S. Government and can be used without additional permissions or fees. If you use these data in a publication, presentation, or other research product please use both of these citations: 

* [Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; McNulty, Steven G. 2019. Wildland fire impacts on water supply (FIWAS) data for the contiguous United States. Fort Collins, CO: Forest Service Research Data Archive. https://doi.org/10.2737/RDS-2019-0012](https://doi.org/10.2737/RDS-2019-0012) 

* [Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; Norman, Steven P.; Cohen, Erika C.; Liu, Yongqiang; Bladon, Kevin D.; McNulty, Steven G. 2018. Burned forests impact water supplies. Nature Communications 9(1): 1307. https://doi.org/10.1038/s41467-018-03735-6](https://doi.org/10.1038/s41467-018-03735-6) 

---

## Research Data Publication File Index  


|File|Folder|Description|
|---|---|---|
|_metadata_RDS-2019-0012.html|&nbsp;|Metadata file in HTML format containing a description of the content, quality, and other characteristics of the data.|
|_metadata_RDS-2019-0012.xml|&nbsp;|Metadata file in Extensible Markup Language (XML) format containing a description of the content, quality, and other characteristics of the data.|
|watershedSynthesis.csv|\Data|Comma-delimited ASCII text file containing data from 1984 - 2013 for the 32 CONUS watersheds that had &gt; 19% of their area burned. Data include fire name, date, and type; ecoregion code; hydrological information; and climate model information.|
|watersheds.* (dbf, kmz, prj, sbn, sbx, shp, and shx)|\Data\spatial|Standard set of seven files that describe a shapefile containing point and vector data for the 168 CONUS watersheds that had burns over &gt; 1% of their area.|
|wshd#_m.csv; wshd#_y.csv|\Data\tabular|336 files containing tabular time series data for the 168 CONUS watersheds that burned over &gt; 1% of their area from 1984 - 2013. Each watershed has two files: wshd#_m.csv and wshd#_y.csv, where # refers to the 7-8 digit USGS gage station ID, "_m" indicates monthly data, and "_y" indicates yearly aggregated data.|
|14-1-06-18_final_report.pdf|\Supplements|Joint Fire Science Program final report for JFSP Project ID: 14-1-06-18 "Effects of wildfires and fuel treatment strategies on watershed water quantity across the contiguous United States".|
|Supp Fig XX StaID_Year_StateCode_FireName.png|\Supplements\GTR_figures|Set of 32 figures in Portable Network Graphics format showing elevation, land cover and burn severity maps for the 32 CONUS watersheds burned over >19% of their area. XX is the 2-digit figure number ranging from 01 to 32; StaID is the USGS gaging station ID; Year is the year of the fire, StateCode is the standard 2-character code for the state in which the fire occurred; FireName is the name of the fire as listed by the MTBS database. Figures reproduced from Appendix B of the Hallema et al. 2019 General Technical Report.|
  
  
  <h2>Metadata:</h2>
  <ul>
   <li>
    <a
     href="#Identification_Information">Identification_Information</a>
   </li>
   <li>
    <a
     href="#Data_Quality_Information">Data_Quality_Information</a>
   </li>
   <li>
    <a
     href="#Spatial_Reference_Information">Spatial_Reference_Information</a>
   </li>
   <li>
    <a
     href="#Entity_and_Attribute_Information">Entity_and_Attribute_Information</a>
   </li>
   <li>
    <a
     href="#ID0ECEAC">
                  Distribution_Information
               </a>
   </li>
   <li>
    <a
     href="#Metadata_Reference_Information">Metadata_Reference_Information</a>
   </li>
  </ul>
  <a
   name="Identification_Information" />
  <dl>
   <dt>
    <i>Identification_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Citation:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Citation_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Originator: </i>Hallema, Dennis W.</dt>
         <dt>
          <i>Originator: </i>Sun, Ge</dt>
         <dt>
          <i>Originator: </i>Caldwell, Peter V.</dt>
         <dt>
          <i>Originator: </i>McNulty, Steven G.</dt>
         <dt>
          <i>Publication_Date: </i>2019</dt>
         <dt>
          <i>Title: </i>
         </dt>Wildland fire impacts on water supply (FIWAS) data for the contiguous United States<dt><i>Geospatial_Data_Presentation_Form: </i>tabular digital data</dt><dt><i>Publication_Information: </i></dt><dd><dl><dt><i>Publication_Place: </i>Fort Collins, CO</dt><dt><i>Publisher: </i>Forest Service Research Data Archive</dt></dl></dd><dt><i>Online_Linkage: </i><a
           href="https://doi.org/10.2737/RDS-2019-0012">https://doi.org/10.2737/RDS-2019-0012</a></dt></dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Description:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Abstract:</i>
       </dt>
       <dd>We obtained data about 168 locations across the contiguous United States (CONUS) that were affected by wildland fire during the period 1984 - 2013. Wildland fire locations, dates, extent, and burn severity were obtained from the Monitoring Trends in Burn Severity (MTBS) dataset. We obtained watershed attributes (watershed boundaries, drainage areas, and perimeters) and daily time series of river flow from the GAGES-II dataset (Geospatial Attributes of Gages for Evaluating Streamflow, version II). The boundaries of the water resource regions were acquired from the Watershed Boundary Database. Climate data were extracted from the daily high resolution (1×1 kilometer) Daymet v3 dataset, and obtained the gridded PRISM (Parameter-elevation Regressions on Independent Slopes Model) dataset. For topographic data (elevation, slope, and aspect), we used the highest resolution version (244×244 meter) of the Global Multi-resolution Terrain Elevation Data 2010, principally obtained during the Shuttle Radar Topography Mission. Finally, we obtained land cover data from the 2001 National Land Cover Database (NLCD).</dd>
       <dt>
        <i>Purpose:</i>
       </dt>
       <dd>Wildland fire impacts on surface freshwater resources have not previously been measured, nor factored into regional water management strategies. However, large wildland fires are increasing and raise concerns about fire impacts on potable water. Therefore, we collected data from across the contiguous United States as part of an assessment of these impacts in the 5 years following wildland fire in affected locations, and their management implications.</dd>
      </dl>
     </dd>
     <dt>
      <i>Time_Period_of_Content:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Time_Period_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Range_of_Dates/Times:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Beginning_Date: </i>1984</dt>
           <dt>
            <i>Ending_Date: </i>2013</dt>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Currentness_Reference:</i>
       </dt>
       <dd>Observed</dd>
      </dl>
     </dd>
     <dt>
      <i>Status:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Progress: </i>Complete</dt>
       <dt>
        <i>Maintenance_and_Update_Frequency: </i>None planned</dt>
      </dl>
     </dd>
     <dt>
      <i>Spatial_Domain:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Description_of_Geographic_Extent:</i>
       </dt>
       <dd>contiguous United States</dd>
       <dt>
        <i>Bounding_Coordinates:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>West_Bounding_Coordinate: </i>-124.81300</dt>
         <dt>
          <i>East_Bounding_Coordinate: </i>-67.06300</dt>
         <dt>
          <i>North_Bounding_Coordinate: </i>52.75000</dt>
         <dt>
          <i>South_Bounding_Coordinate: </i>25.00000</dt>
        </dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Keywords:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Theme:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Theme_Keyword_Thesaurus: </i>ISO 19115 Topic Category</dt>
         <dt>
          <i>Theme_Keyword: </i>economy</dt>
         <dt>
          <i>Theme_Keyword: </i>environment</dt>
         <dt>
          <i>Theme_Keyword: </i>geoscientificInformation</dt>
         <dt>
          <i>Theme_Keyword: </i>society</dt>
        </dl>
       </dd>
       <dt>
        <i>Theme:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Theme_Keyword_Thesaurus: </i>National Research &amp; Development Taxonomy</dt>
         <dt>
          <i>Theme_Keyword: </i>Climate change</dt>
         <dt>
          <i>Theme_Keyword: </i>Climate change effects</dt>
         <dt>
          <i>Theme_Keyword: </i>Ecology, Ecosystems, &amp; Environment</dt>
         <dt>
          <i>Theme_Keyword: </i>Hydrology, watersheds, sedimentation</dt>
         <dt>
          <i>Theme_Keyword: </i>Landscape ecology</dt>
         <dt>
          <i>Theme_Keyword: </i>Fire</dt>
         <dt>
          <i>Theme_Keyword: </i>Fire effects on environment</dt>
         <dt>
          <i>Theme_Keyword: </i>Natural Resource Management &amp; Use</dt>
         <dt>
          <i>Theme_Keyword: </i>Ecosystem services</dt>
         <dt>
          <i>Theme_Keyword: </i>Policies and law</dt>
         <dt>
          <i>Theme_Keyword: </i>Water</dt>
        </dl>
       </dd>
       <dt>
        <i>Theme:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Theme_Keyword_Thesaurus: </i>None</dt>
         <dt>
          <i>Theme_Keyword: </i>wildfire</dt>
         <dt>
          <i>Theme_Keyword: </i>streamflow</dt>
         <dt>
          <i>Theme_Keyword: </i>hydrology</dt>
         <dt>
          <i>Theme_Keyword: </i>climate change</dt>
         <dt>
          <i>Theme_Keyword: </i>Joint Fire Science Program</dt>
         <dt>
          <i>Theme_Keyword: </i>JFSP</dt>
        </dl>
       </dd>
       <dt>
        <i>Place:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Place_Keyword_Thesaurus: </i>None</dt>
         <dt>
          <i>Place_Keyword: </i>contiguous United States</dt>
        </dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Access_Constraints: </i>None</dt>
     <dt>
      <i>Use_Constraints:</i>
     </dt>
     <dd>These data were collected using funding from the U.S. Government and can be used without additional permissions or fees. If you use these data in a publication, presentation, or other research product please use both of these citations: <br />
<br />
Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; McNulty, Steven G. 2019. Wildland fire impacts on water supply (FIWAS) data for the contiguous United States. Fort Collins, CO: Forest Service Research Data Archive. https://doi.org/10.2737/RDS-2019-0012<br />
<br />
Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; Norman, Steven P.; Cohen, Erika C.; Liu, Yongqiang; Bladon, Kevin D.; McNulty, Steven G. 2018. Burned forests impact water supplies. Nature Communications 9(1): 1307. https://doi.org/10.1038/s41467-018-03735-6</dd>
     <dt>
      <i>Point_of_Contact:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Contact_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Contact_Person_Primary:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Contact_Person: </i>Dennis W. Hallema</dt>
           <dt>
            <i>Contact_Organization: </i>USDA Forest Service, Southern Research Station</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Address:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Address_Type: </i>mailing</dt>
           <dt>
            <i>Address: </i>3041 E Cornwallis Rd</dt>
           <dt>
            <i>City: </i>Research Triangle Park</dt>
           <dt>
            <i>State_or_Province: </i>North Carolina</dt>
           <dt>
            <i>Postal_Code: </i>27709</dt>
           <dt>
            <i>Country: </i>United States of America</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Voice_Telephone: </i>Prefer contact via email</dt>
         <dt>
          <i>Contact_Electronic_Mail_Address: </i>
          <TT>dennis.hallema@usda.gov</TT>
         </dt>
        </dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Data_Set_Credit:</i>
     </dt>
     <dd>This dataset was supported by the USDA Forest Service, Southern Research Station and the Joint Fire Science Program (grant # 14-1-06-18 (Ge Sun, PI). D.W. Hallema is supported by the Forest Service Research Participation Program administered by the Oak Ridge Institute for Science and Education (ORISE) through an interagency agreement between the U.S. Department of Energy and the USDA Forest Service. ORISE is managed by Oak Ridge Associated Universities (ORAU) under DOE contract number DE-AC05-06OR23100. <br />
<br />
All opinions expressed are the authors' and do not necessarily reflect the policies and views of USDA, DOE, or ORAU/ORISE. The authors thank Danny C. Lee and Erika C. Cohen for support.</dd>
     <dt>
      <i>Cross_Reference:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Citation_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Originator: </i>Hallema, Dennis W.</dt>
         <dt>
          <i>Originator: </i>Sun, Ge</dt>
         <dt>
          <i>Originator: </i>Caldwell, Peter V.</dt>
         <dt>
          <i>Originator: </i>Norman, Steven P.</dt>
         <dt>
          <i>Originator: </i>Cohen, Erika C.</dt>
         <dt>
          <i>Originator: </i>Liu, Yongqiang</dt>
         <dt>
          <i>Originator: </i>Ward, Eric J.</dt>
         <dt>
          <i>Originator: </i>McNulty, Steven G.</dt>
         <dt>
          <i>Publication_Date: </i>2016</dt>
         <dt>
          <i>Title: </i>
         </dt>Assessment of wildland fire impacts on watershed annual water yield: Analytical framework and case studies in the United States<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Ecohydrology</dt><dt><i>Issue_Identification: </i>10(2): e1794</dt></dl></dd><dt><i>Online_Linkage: </i><a
           href="https://doi.org/10.1002/eco.1794">https://doi.org/10.1002/eco.1794</a></dt></dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Cross_Reference:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Citation_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Originator: </i>Hallema, Dennis W.</dt>
         <dt>
          <i>Originator: </i>Sun, Ge</dt>
         <dt>
          <i>Originator: </i>Bladon, Kevin D.</dt>
         <dt>
          <i>Originator: </i>Norman, Steven P.</dt>
         <dt>
          <i>Originator: </i>Caldwell, Peter V.</dt>
         <dt>
          <i>Originator: </i>Liu, Yongqiang</dt>
         <dt>
          <i>Originator: </i>McNulty, Steven G.</dt>
         <dt>
          <i>Publication_Date: </i>2017</dt>
         <dt>
          <i>Title: </i>
         </dt>Regional patterns of postwildfire streamflow response in the Western United States: The importance of scale-specific connectivity<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Hydrological Processes</dt><dt><i>Issue_Identification: </i>31(14): 2852-2598</dt></dl></dd><dt><i>Online_Linkage: </i><a
           href="https://doi.org/10.1002/hyp.11208">https://doi.org/10.1002/hyp.11208</a></dt></dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Cross_Reference:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Citation_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Originator: </i>Hallema, Dennis W.</dt>
         <dt>
          <i>Originator: </i>Sun, Ge</dt>
         <dt>
          <i>Originator: </i>Caldwell, Peter V.</dt>
         <dt>
          <i>Originator: </i>Norman, Steven P.</dt>
         <dt>
          <i>Originator: </i>Cohen, Erika C.</dt>
         <dt>
          <i>Originator: </i>Liu, Yongqiang</dt>
         <dt>
          <i>Originator: </i>Bladon, Kevin D.</dt>
         <dt>
          <i>Originator: </i>McNulty, Steven G.</dt>
         <dt>
          <i>Publication_Date: </i>2018</dt>
         <dt>
          <i>Title: </i>
         </dt>Burned forests impact water supplies<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Nature Communications</dt><dt><i>Issue_Identification: </i>9: 1307</dt></dl></dd><dt><i>Online_Linkage: </i><a
           href="https://doi.org/10.1038/s41467-018-03735-6">https://doi.org/10.1038/s41467-018-03735-6</a></dt></dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Cross_Reference:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Citation_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Originator: </i>Hallema, Dennis W.</dt>
         <dt>
          <i>Originator: </i>Sun, Ge</dt>
         <dt>
          <i>Originator: </i>Caldwell, Peter V.</dt>
         <dt>
          <i>Originator: </i>Robinne, François-Nicolas</dt>
         <dt>
          <i>Originator: </i>Bladon, Kevin D.</dt>
         <dt>
          <i>Originator: </i>Norman, Steven P.</dt>
         <dt>
          <i>Originator: </i>Liu, Yongqiang</dt>
         <dt>
          <i>Originator: </i>Cohen, Erika</dt>
         <dt>
          <i>Originator: </i>McNulty, Steven G.</dt>
         <dt>
          <i>Publication_Date: </i>2019</dt>
         <dt>
          <i>Title: </i>
         </dt>Wildland fire impacts on water yields across the contiguous United States<dt><i>Geospatial_Data_Presentation_Form: </i>document</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>General Technical Report</dt><dt><i>Issue_Identification: </i>SRS-238</dt></dl></dd><dt><i>Publication_Information: </i></dt><dd><dl><dt><i>Publication_Place: </i>Asheville, NC</dt><dt><i>Publisher: </i>U.S. Department of Agriculture, Forest Service, Southern Research Station</dt></dl></dd><dt><i>Other_Citation_Details: </i></dt><dd>109 p.</dd><dt><i>Online_Linkage: </i><a
           href="https://www.fs.usda.gov/treesearch/pubs/58095">https://www.fs.usda.gov/treesearch/pubs/58095</a></dt></dl>
       </dd>
      </dl>
     </dd>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
  <a
   name="Data_Quality_Information" />
  <dl>
   <dt>
    <i>Data_Quality_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Attribute_Accuracy:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Attribute_Accuracy_Report:</i>
       </dt>
       <dd>The accuracy of the various attributes is reported by their sources. Please see the Source Information citations for relevant information.</dd>
      </dl>
     </dd>
     <dt>
      <i>Logical_Consistency_Report:</i>
     </dt>
     <dd>The variables retain the logical consistency reported by their sources, and were consistent enough for our modeling work.</dd>
     <dt>
      <i>Completeness_Report:</i>
     </dt>
     <dd>The variables retain the completeness reported by their sources, and were complete enough for our modeling work.</dd>
     <dt>
      <i>Lineage:</i>
     </dt>
     <dl>
      <dt>
       <i>Methodology:</i>
      </dt>
      <dl>
       <dt>
        <i>Methodology_Type: </i>Lab</dt>
       <dt>
        <i>Methodology_Description:</i>
       </dt>
       <dd>Effects of wildfire on water supplies were modeled; methods are described more fully in the articles listed under Cross References.</dd>
      </dl>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>United States Geological Survey</dt>
            <dt>
             <i>Publication_Date: </i>2016</dt>
            <dt>
             <i>Title: </i>
            </dt>USGS Water Data for the Nation<dt><i>Geospatial_Data_Presentation_Form: </i>tabular digital data</dt><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.5066/F7P55KJN">https://doi.org/10.5066/F7P55KJN</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Type_of_Source_Media: </i>Online</dt>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Range_of_Dates/Times:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Beginning_Date: </i>1984</dt>
              <dt>
               <i>Ending_Date: </i>2014</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>water data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Thornton, P.E.</dt>
            <dt>
             <i>Originator: </i>Thornton, M.M.</dt>
            <dt>
             <i>Originator: </i>Mayer, B.W.</dt>
            <dt>
             <i>Originator: </i>Wei, Y.</dt>
            <dt>
             <i>Originator: </i>Devarakonda, R.</dt>
            <dt>
             <i>Originator: </i>Vose, R.S.</dt>
            <dt>
             <i>Originator: </i>Cook, R.B.</dt>
            <dt>
             <i>Publication_Date: </i>2016</dt>
            <dt>
             <i>Title: </i>
            </dt>Daymet: Daily Surface Weather Data on a 1-km Grid for North America, Version 3<dt><i>Geospatial_Data_Presentation_Form: </i>raster digital data</dt><dt><i>Publication_Information: </i></dt><dd><dl><dt><i>Publication_Place: </i>Oak Ridge, Tennessee, USA</dt><dt><i>Publisher: </i>Oak Ridge National Laboratory Distributed Active Archive Center</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.3334/ORNLDAAC/1328">https://doi.org/10.3334/ORNLDAAC/1328</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Range_of_Dates/Times:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Beginning_Date: </i>1980</dt>
              <dt>
               <i>Ending_Date: </i>2014</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>daily weather data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Daly, C.</dt>
            <dt>
             <i>Originator: </i>Halbleib, M.</dt>
            <dt>
             <i>Originator: </i>Smith, J.I.</dt>
            <dt>
             <i>Originator: </i>Gibson, W.P.</dt>
            <dt>
             <i>Originator: </i>Doggett, M.K.</dt>
            <dt>
             <i>Originator: </i>Taylor, G.H.</dt>
            <dt>
             <i>Originator: </i>Curtis, J.</dt>
            <dt>
             <i>Originator: </i>Pasteris, P.P.</dt>
            <dt>
             <i>Publication_Date: </i>2008</dt>
            <dt>
             <i>Title: </i>
            </dt>Physiographically sensitive mapping of climatological temperature and precipitation across the conterminous United States<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>International Journal of Climatology</dt><dt><i>Issue_Identification: </i>28(15): 2031-2064</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.1002/joc.1688">https://doi.org/10.1002/joc.1688</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Range_of_Dates/Times:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Beginning_Date: </i>1980</dt>
              <dt>
               <i>Ending_Date: </i>2014</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>temperature and precipitation data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Sun, G.</dt>
            <dt>
             <i>Originator: </i>Caldwell, P.</dt>
            <dt>
             <i>Originator: </i>Noormets, A.</dt>
            <dt>
             <i>Originator: </i>McNulty, S.G.</dt>
            <dt>
             <i>Originator: </i>Cohen, E. C.</dt>
            <dt>
             <i>Originator: </i>Moore Myers, J.</dt>
            <dt>
             <i>Originator: </i>Domec, J.C.</dt>
            <dt>
             <i>Originator: </i>Treasure, E.</dt>
            <dt>
             <i>Originator: </i>Mu, Q.</dt>
            <dt>
             <i>Originator: </i>Xiao, J.</dt>
            <dt>
             <i>Originator: </i>John, R.</dt>
            <dt>
             <i>Originator: </i>Chen, J.</dt>
            <dt>
             <i>Publication_Date: </i>2011</dt>
            <dt>
             <i>Title: </i>
            </dt>Upscaling key ecosystem functions across the conterminous United States by a water-centric ecosystem model<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Journal of Geophysical Research</dt><dt><i>Issue_Identification: </i>116(G00J05)</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.1029/2010JG001573">https://doi.org/10.1029/2010JG001573</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Range_of_Dates/Times:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Beginning_Date: </i>1980</dt>
              <dt>
               <i>Ending_Date: </i>2012</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Publication Date</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>model information for ecosystem functions</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Danielson, J.J.</dt>
            <dt>
             <i>Originator: </i>Gesch, D.B.</dt>
            <dt>
             <i>Publication_Date: </i>2011</dt>
            <dt>
             <i>Title: </i>
            </dt>Global multi-resolution terrain elevation data 2010 (GMTED2010)<dt><i>Geospatial_Data_Presentation_Form: </i>raster digital data</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>U.S. Geological Survey Open-File Report</dt><dt><i>Issue_Identification: </i>2011–1073</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="https://pubs.usgs.gov/of/2011/1073/pdf/of2011-1073.pdf">https://pubs.usgs.gov/of/2011/1073/pdf/of2011-1073.pdf</a></dt><dt><i>Online_Linkage: </i><a
              href="https://lta.cr.usgs.gov/GMTED2010">https://lta.cr.usgs.gov/GMTED2010</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Single_Date/Time:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Calendar_Date: </i>2010</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>digital elevation data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Eidenshink, J.</dt>
            <dt>
             <i>Originator: </i>Schwind, B.</dt>
            <dt>
             <i>Originator: </i>Brewer, K.</dt>
            <dt>
             <i>Originator: </i>Zhu, Z.-L.</dt>
            <dt>
             <i>Originator: </i>Quayle, B.</dt>
            <dt>
             <i>Originator: </i>Howard, S.</dt>
            <dt>
             <i>Publication_Date: </i>2007</dt>
            <dt>
             <i>Title: </i>
            </dt>A project for monitoring trends in burn severity<dt><i>Geospatial_Data_Presentation_Form: </i>journal article</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Fire Ecology</dt><dt><i>Issue_Identification: </i>3(1):3-21</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.4996/fireecology.0301003">https://doi.org/10.4996/fireecology.0301003</a></dt><dt><i>Online_Linkage: </i><a
              href="http://www.mtbs.gov">http://www.mtbs.gov</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Range_of_Dates/Times:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Beginning_Date: </i>1984</dt>
              <dt>
               <i>Ending_Date: </i>2014</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>wildfire burn severity data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>United States Geological Survey</dt>
            <dt>
             <i>Publication_Date: </i>2016</dt>
            <dt>
             <i>Title: </i>
            </dt>GAGES-II Geospatial Attributes<dt><i>Geospatial_Data_Presentation_Form: </i>vector digital data</dt><dt><i>Online_Linkage: </i><a
              href="https://doi.org/10.5066/F7P55KJN">https://doi.org/10.5066/F7P55KJN</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Single_Date/Time:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Calendar_Date: </i>2011</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>environment attributes related to stream gauges providing water data</dd>
       </dl>
      </dd>
      <dt>
       <i>Source_Information:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Source_Citation:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Citation_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Originator: </i>Homer, C.</dt>
            <dt>
             <i>Originator: </i>Dewitz, J.</dt>
            <dt>
             <i>Originator: </i>Yang, L.</dt>
            <dt>
             <i>Originator: </i>Jin, S.</dt>
            <dt>
             <i>Originator: </i>Danielson, P.</dt>
            <dt>
             <i>Originator: </i>Xian, G.</dt>
            <dt>
             <i>Originator: </i>Coulston, J.</dt>
            <dt>
             <i>Originator: </i>Herold, N.</dt>
            <dt>
             <i>Originator: </i>Wickham, J.</dt>
            <dt>
             <i>Originator: </i>Megown, K.</dt>
            <dt>
             <i>Publication_Date: </i>2011</dt>
            <dt>
             <i>Title: </i>
            </dt>Completion of the 2011 National Land Cover Database for the conterminous United States–representing a decade of land cover change information<dt><i>Geospatial_Data_Presentation_Form: </i>raster digital data</dt><dt><i>Series_Information: </i></dt><dd><dl><dt><i>Series_Name: </i>Photogrammetric Engineering &amp; Remote Sensing</dt><dt><i>Issue_Identification: </i>81(5)</dt></dl></dd><dt><i>Online_Linkage: </i><a
              href="http://www.mrlc.gov/nlcd2011.php">http://www.mrlc.gov/nlcd2011.php</a></dt></dl>
          </dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Time_Period_of_Content:</i>
        </dt>
        <dd>
         <dl>
          <dt>
           <i>Time_Period_Information:</i>
          </dt>
          <dd>
           <dl>
            <dt>
             <i>Single_Date/Time:</i>
            </dt>
            <dd>
             <dl>
              <dt>
               <i>Calendar_Date: </i>2001</dt>
             </dl>
            </dd>
           </dl>
          </dd>
          <dt>
           <i>Source_Currentness_Reference:</i>
          </dt>
          <dd>Ground Condition</dd>
         </dl>
        </dd>
        <dt>
         <i>Source_Contribution:</i>
        </dt>
        <dd>land use and land cover data</dd>
       </dl>
      </dd>
      <dt>
       <i>Process_Step:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Process_Description:</i>
        </dt>
        <dd>Data were collected from a variety of high-resolution datasets describing the conterminous United States landscape with respect to wildland fire, climate, topography, land cover, watershed boundaries, and river flow. Process further described in Hallema et al. (2019).<br />
		<br />
Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; Robinne, François-Nicolas; Bladon, Kevin D.; Norman, Steven P.; Liu, Yongqiang; Cohen, Erika; McNulty, Steven G. 2019. Wildland fire impacts on water yields across the contiguous United States. General Technical Report SRS-238. Asheville, NC: U.S. Department of Agriculture Forest Service, Southern Research Station. 109 p. https://www.fs.usda.gov/treesearch/pubs/58095</dd>
        <dt>
         <i>Process_Date: </i>Unknown</dt>
       </dl>
      </dd>
      <dt>
       <i>Process_Step:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Process_Description:</i>
        </dt>
        <dd>We selected GAGES-II watersheds with a drainage area &gt; 10 square kilometers (km²), approximately the size of a headwater catchment, and a flow record spanning at least 2 decades. In addition, we only selected watersheds with minimal human disturbances or hydrologic infrastructure (e.g., dam, flow diversions, etc.) so the effect of the burn on flow could be isolated from other factors. We combined GAGES-II watershed boundaries with annual MTBS burn severity data, resulting in a dataset with information on burn severity (ordinal classes of underburned or unburned, low, moderate, and high severity) for each 120- × 120-meter (m) subdivision of the burned watersheds. We calculated the fraction of the watershed burned for each burn severity class and for all classes combined. This is the burned area-to-drainage area ratio (BAR).<br />
<br />
The resulting collection contained 168 burned watersheds with a BAR ≥ 1 percent for any degree of burn impacts in any single year between 1984 and 2008.</dd>
        <dt>
         <i>Process_Date: </i>Unknown</dt>
       </dl>
      </dd>
      <dt>
       <i>Process_Step:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Process_Description:</i>
        </dt>
        <dd>After identifying the collection of burned watersheds, we retrieved the corresponding fire dates and summarized data for river flow Q, precipitation P, and snow water equivalent (amount of water contained within the snowpack) SWE. Monthly potential evapotranspiration (PET) was estimated from PRISM gridded climate data with Hamon’s method. Finally, we determined for each burned watershed the NLCD land cover and GMTED2010 topographic characteristics such as elevation, slope, and aspect. We also calculated the watershed shape parameter describing the ratio of watershed perimeter to drainage area (Gravelius’ compactness factor).</dd>
        <dt>
         <i>Process_Date: </i>Unknown</dt>
       </dl>
      </dd>
      <dt>
       <i>Process_Step:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Process_Description:</i>
        </dt>
        <dd>To evaluate wildland fire impacts on annual river flow, we<br />
1. Detected river flow change<br />
<br />
2. Identified changes in water yield ratio<br />
<br />
3. Characterized local wildland fire-climate-environment interactions<br />
<br />
4. Filtered local climate baseline<br />
<br />
5. Computed net impact of wildland fire on river flow</dd>
        <dt>
         <i>Process_Date: </i>Unknown</dt>
       </dl>
      </dd>
      <dt>
       <i>Process_Step:</i>
      </dt>
      <dd>
       <dl>
        <dt>
         <i>Process_Description:</i>
        </dt>
        <dd>Predict potential wildfire effects on surface water yield<br />
<br />
Used the Water Supply Stress Index model (WaSSI), i.e., the WaSSI monthly water balance subroutine, to obtain full-cover assessment of the potential impact of severe wildfire on surface water yield across the large climatic gradient of the CONUS. We defined four scenarios of hypothetical burn impacts and simulated corresponding changes to the water balance in all CONUS watersheds for the period between 2001 and 2010. By comparing the results of each scenario to a baseline scenario representing undisturbed conditions, we obtained an estimate of their hypothetical impact on water supplies.</dd>
        <dt>
         <i>Process_Date: </i>Unknown</dt>
       </dl>
      </dd>
     </dl>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
  <a
   name="Spatial_Reference_Information" />
  <dl>
   <dt>
    <i>Spatial_Reference_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Horizontal_Coordinate_System_Definition:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Planar:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Map_Projection:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Map_Projection_Name: </i>Albers Conical Equal Area</dt>
           <dt>
            <i>Albers_Conical_Equal_Area:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Standard_Parallel: </i>29.5</dt>
             <dt>
              <i>Standard_Parallel: </i>45.5</dt>
             <dt>
              <i>Longitude_of_Central_Meridian: </i>-96</dt>
             <dt>
              <i>Latitude_of_Projection_Origin: </i>37.5</dt>
             <dt>
              <i>False_Easting: </i>0</dt>
             <dt>
              <i>False_Northing: </i>0</dt>
            </dl>
           </dd>
          </dl>
         </dd>
         <dt>
          <i>Planar_Coordinate_Information:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Planar_Coordinate_Encoding_Method: </i>Coordinate Pair</dt>
           <dt>
            <i>Coordinate_Representation:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Abscissa_Resolution: </i>1</dt>
             <dt>
              <i>Ordinate_Resolution: </i>1</dt>
            </dl>
           </dd>
           <dt>
            <i>Planar_Distance_Units: </i>Meters</dt>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Geodetic_Model:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Horizontal_Datum_Name: </i>North American Datum of 1983</dt>
         <dt>
          <i>Ellipsoid_Name: </i>Geodetic Reference System 80</dt>
         <dt>
          <i>Semi-major_Axis: </i>6378137</dt>
         <dt>
          <i>Denominator_of_Flattening_Ratio: </i>298.2572221</dt>
        </dl>
       </dd>
      </dl>
     </dd>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
  <a
   name="Entity_and_Attribute_Information" />
  <dl>
   <dt>
    <i>Entity_and_Attribute_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Overview_Description:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Entity_and_Attribute_Overview:</i>
       </dt>
       <dd>Below is a list of the files included in this data publication.<br />
<br />
DATA FILES<br />
	  <br />
\Data\watershedSynthesis.csv: <br />
Comma-delimited ASCII text file containing data from 1984 - 2013 for the 32 watersheds that had &gt; 19% of their area burned. Data described below.<br />
	  <br />
Station_ID = USGS station ID (unique integer value)<br />
<br />
Fire_date = date the fire started from the Monitoring Trends in Burn Severity (MTBS) database; formatted as yyyy-mm-dd character string<br />
<br />
Fire_name = Name of the fire as listed in the MTBS database<br />
<br />
Fire_type = MTBS fire type; uses the codeset<br />
    WF = wildfire<br />
    RX = prescribed fire<br />
    UNK = type unknown<br />
<br />
Station_name = USGS station name<br />
<br />
Station_class = USGS station classification: Ref or Non-Ref (all stations used in the dataset were reference stations)<br />
<br />
Aggr_ecoregion = USGS aggregated ecoregion; codeset is<br />
     SECstPlain = southeast coastal plains<br />
     SEPlains = southeast plains<br />
     WestMnts = western mountains<br />
     CntlPlains = central plains<br />
     WestPlains = western plains<br />
     WestXeric = western xeric<br />
<br />
Drainage_sqkm = USGS drainage area, in square kilometers<br />
<br />
HUC02 = hydrologic unit code, defined at outlet; 2-digit code ranging from 01 to 21<br />
<br />
HUC02_name = name of the hydrologic unit code<br />
<br />
Gage_lat = latitude of the USGS station in decimal degrees<br />
<br />
Gage_long = longitude of the USGS station in decimal degrees, six decimal place precision<br />
<br />
State = U.S. state in which the gage station is located, expressed as standard U.S. Postal Service 2-letter codeset<br />
<br />
Mean_altitude = average elevation from GMTED2010, meters to six decimal places<br />
<br />
CEM_optbic = optimal Climate Elasticity Model based on Bayesian Information Criterion; enumerated domain of 'cem1', 'cem2', 'cem3', and 'cem4'<br />
<br />
CEM_optbic_rsq = R² of optimal Climate Elasticity Model; real value ranging from 0.0 to 1.0<br />
<br />
CEM_optbic_pval = p-value expressing the probability that the optimal model does not differ from a null model; real value ranging from 0.0 to 1.0<br />
<br />
CEM_delta_climate = change in observed annual streamflow attributed to climate effects, millimeters<br />
<br />
CEM_delta_nonclimate = change in observed annual streamflow attributed to non-climate factors, millimeters<br />
<br />
CEM_delta_climate_% = percent change in observed annual streamflow attributed to climate effects<br />
<br />
CEM_delta_nonclimate_% = percent change in observed annual streamflow attributed to non-climate factors<br />
<br />
<br />
\Data\spatial: <br />
Collection of seven files defining a shapefile containing point and vector data for 168 CONUS watersheds burned over more than 1% of their area (Hallema et al. 2019).  <br />
<br />
<br />
\Data\tabular: <br />
Tabular time series data across 1984 - 2013 for 168 CONUS watersheds burned over more than 1% of their area (Hallema et al. 2019). Collection of 336 comma-delimited ASCII files are named wshd#_m.csv and wshd#_y.csv, where # refers to the 7-8 digit USGS station ID (staid) and "_y" are the yearly aggregated data. Data in each file are:<br />
<br />
Attribute Label, Attribute Definition, Attribute Source, Attribute Domain (Units)<br />
STAID = USGS Station ID (unique integer value)<br />
<br />
POS = POSIX date expressed as YYYY-mm-dd<br />
<br />
PPT_MM = WaSSI PRISM Precipitation expressed in millimeters<br />
<br />
PPT_MMvar = WaSSI PRISM Precipitation variance<br />
<br />
PET_MM = WaSSI PRISM Potential evapotranspiration expressed in millimeters<br />
<br />
YLD_MM = WaSSI Simulated water yield expressed in millimeters<br />
<br />
YLD_MMvar = WaSSI Simulated water yield variance<br />
<br />
yieldmm = GAGES-II Observed water yield expressed in millimeters<br />
<br />
yieldmmvar = Observed water yield variance<br />
<br />
USGS_RC = Daymet/USGS Runoff coefficient; dimensionless<br />
<br />
WAS_RC = Daymet/WaSSI Runoff coefficient; dimensionless<br />
<br />
tmax = Daymet v3 Daily maximum 2-meter air temperature in degrees Celsius<br />
<br />
tmin = Daymet v3 Daily minimum 2-meter air temperature in degrees Celsius<br />
<br />
p = Daymet v3 Daily total precipitation in millimeters, sum of all forms converted to water-equivalent<br />
<br />
swe = Daymet v3 Snow water equivalent in kilograms per square meter; i.e., the amount of water contained within the snowpack<br />
<br />
tmaxmvar = Daymet v3 Daily maximum 2-meter air temperature variance<br />
<br />
tminmvar = Daymet v3 Daily minimum 2-meter air temperature variance<br />
<br />
<br />
SUPPLEMENTS<br />
<br />
\Supplements\14-1-06-18_final_report.pdf: Joint Fire Science Program final report for JFSP Project ID: 14-1-06-18 "Effects of wildfires and fuel treatment strategies on watershed water quantity across the contiguous United States". Report also available online: https://www.firescience.gov/projects/14-1-06-18/project/14-1-06-18_final_report.pdf<br />
<br />
\Supplements\GTR_figures: <br />
Figures showing elevation, land cover and burn severity maps for 32 CONUS watersheds burned over more than 19% of their area (Appendix B, Hallema et al. 2019). <br />
<br />
</dd>
       <dt>
        <i>Entity_and_Attribute_Detail_Citation:</i>
       </dt>
       <dd>Hallema, Dennis W.; Sun, Ge; Caldwell, Peter V.; Robinne, François-Nicolas; Bladon, Kevin D.; Norman, Steven P.; Liu, Yongqiang; Cohen, Erika; McNulty, Steven G. 2019. Wildland fire impacts on water yields across the contiguous United States. General Technical Report SRS-238. Asheville, NC: U.S. Department of Agriculture Forest Service, Southern Research Station. 109 p. https://www.fs.usda.gov/treesearch/pubs/58095</dd>
      </dl>
     </dd>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
  <a
   name="ID0ECEAC" />
  <dl>
   <dt>
    <i>Distribution_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Distributor:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Contact_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Contact_Organization_Primary:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Contact_Organization: </i>USDA Forest Service, Research and Development</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Position: </i>Research Data Archivist</dt>
         <dt>
          <i>Contact_Address:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Address_Type: </i>mailing and physical</dt>
           <dt>
            <i>Address: </i>240 West Prospect Road</dt>
           <dt>
            <i>City: </i>Fort Collins</dt>
           <dt>
            <i>State_or_Province: </i>CO</dt>
           <dt>
            <i>Postal_Code: </i>80526</dt>
           <dt>
            <i>Country: </i>USA</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Voice_Telephone: </i>see Contact Instructions</dt>
         <dt>
          <i>Contact Instructions: </i>This contact information was current as of September 2019. For current information see Contact Us page on: https://doi.org/10.2737/RDS.</dt>
        </dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Resource_Description: </i>RDS-2019-0012</dt>
     <dt>
      <i>Distribution_Liability:</i>
     </dt>
     <dd>Metadata documents have been reviewed for accuracy and completeness. Unless otherwise stated, all data and related materials are considered to satisfy the quality standards relative to the purpose for which the data were collected. However, neither the author, the Archive, nor any part of the federal government can assure the reliability or suitability of these data for a particular purpose. The act of distribution shall not constitute any such warranty, and no responsibility is assumed for a user's application of these data or related materials.<br />
<br />
The metadata, data, or related materials may be updated without notification. If a user believes errors are present in the metadata, data or related materials, please use the information in (1) Identification Information: Point of Contact, (2) Metadata Reference: Metadata Contact, or (3) Distribution Information: Distributor to notify the author or the Archive of the issues.</dd>
     <dt>
      <i>Standard_Order_Process:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Digital_Form:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Digital_Transfer_Information:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Format_Name: </i>SHP</dt>
           <dt>
            <i>Format_Version_Number: </i>see Format Specification</dt>
           <dt>
            <i>Format_Specification:</i>
           </dt>
           <dd>ESRI ArcGIS shapefile (SHP)</dd>
           <dt>
            <i>File_Decompression_Technique: </i>Files zipped with 7-Zip 18.05</dt>
          </dl>
         </dd>
         <dt>
          <i>Digital_Transfer_Option:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Online_Option:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Computer_Contact_Information:</i>
             </dt>
             <dd>
              <dl>
               <dt>
                <i>Network_Address:</i>
               </dt>
               <dd>
                <dl>
                 <dt>
                  <i>Network_Resource_Name:</i>
                  <a
                   TARGET="viewer"
                   href="https://doi.org/10.2737/RDS-2019-0012">https://doi.org/10.2737/RDS-2019-0012</a>
                 </dt>
                </dl>
               </dd>
              </dl>
             </dd>
            </dl>
           </dd>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Digital_Form:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Digital_Transfer_Information:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Format_Name: </i>ASCII</dt>
           <dt>
            <i>Format_Version_Number: </i>see Format Specification</dt>
           <dt>
            <i>Format_Specification:</i>
           </dt>
           <dd>Comma-delimited ASCII text file (CSV)</dd>
           <dt>
            <i>File_Decompression_Technique: </i>Files zipped with 7-Zip 18.05</dt>
          </dl>
         </dd>
         <dt>
          <i>Digital_Transfer_Option:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Online_Option:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Computer_Contact_Information:</i>
             </dt>
             <dd>
              <dl>
               <dt>
                <i>Network_Address:</i>
               </dt>
               <dd>
                <dl>
                 <dt>
                  <i>Network_Resource_Name:</i>
                  <a
                   TARGET="viewer"
                   href="https://doi.org/10.2737/RDS-2019-0012">https://doi.org/10.2737/RDS-2019-0012</a>
                 </dt>
                </dl>
               </dd>
              </dl>
             </dd>
            </dl>
           </dd>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Digital_Form:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Digital_Transfer_Information:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Format_Name: </i>PNG</dt>
           <dt>
            <i>Format_Version_Number: </i>see Format Specification</dt>
           <dt>
            <i>Format_Specification:</i>
           </dt>
           <dd>Portable Network Graphics format file (PNG)</dd>
           <dt>
            <i>File_Decompression_Technique: </i>Files zipped with 7-Zip 18.05</dt>
          </dl>
         </dd>
         <dt>
          <i>Digital_Transfer_Option:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Online_Option:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Computer_Contact_Information:</i>
             </dt>
             <dd>
              <dl>
               <dt>
                <i>Network_Address:</i>
               </dt>
               <dd>
                <dl>
                 <dt>
                  <i>Network_Resource_Name:</i>
                  <a
                   TARGET="viewer"
                   href="https://doi.org/10.2737/RDS-2019-0012">https://doi.org/10.2737/RDS-2019-0012</a>
                 </dt>
                </dl>
               </dd>
              </dl>
             </dd>
            </dl>
           </dd>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Digital_Form:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Digital_Transfer_Information:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Format_Name: </i>PDF</dt>
           <dt>
            <i>Format_Version_Number: </i>see Format Specification</dt>
           <dt>
            <i>Format_Specification:</i>
           </dt>
           <dd>Portable document format file (PDF)</dd>
           <dt>
            <i>File_Decompression_Technique: </i>Files zipped with 7-Zip 18.05</dt>
          </dl>
         </dd>
         <dt>
          <i>Digital_Transfer_Option:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Online_Option:</i>
           </dt>
           <dd>
            <dl>
             <dt>
              <i>Computer_Contact_Information:</i>
             </dt>
             <dd>
              <dl>
               <dt>
                <i>Network_Address:</i>
               </dt>
               <dd>
                <dl>
                 <dt>
                  <i>Network_Resource_Name:</i>
                  <a
                   TARGET="viewer"
                   href="https://doi.org/10.2737/RDS-2019-0012">https://doi.org/10.2737/RDS-2019-0012</a>
                 </dt>
                </dl>
               </dd>
              </dl>
             </dd>
            </dl>
           </dd>
          </dl>
         </dd>
        </dl>
       </dd>
       <dt>
        <i>Fees: </i>None</dt>
      </dl>
     </dd>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
  <a
   name="Metadata_Reference_Information" />
  <dl>
   <dt>
    <i>Metadata_Reference_Information:</i>
   </dt>
   <dd>
    <dl>
     <dt>
      <i>Metadata_Date: </i>20190920</dt>
     <dt>
      <i>Metadata_Contact:</i>
     </dt>
     <dd>
      <dl>
       <dt>
        <i>Contact_Information:</i>
       </dt>
       <dd>
        <dl>
         <dt>
          <i>Contact_Person_Primary:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Contact_Person: </i>Dennis W. Hallema</dt>
           <dt>
            <i>Contact_Organization: </i>USDA Forest Service, Southern Research Station</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Address:</i>
         </dt>
         <dd>
          <dl>
           <dt>
            <i>Address_Type: </i>mailing</dt>
           <dt>
            <i>Address: </i>3041 E Cornwallis Rd</dt>
           <dt>
            <i>City: </i>Research Triangle Park</dt>
           <dt>
            <i>State_or_Province: </i>North Carolina</dt>
           <dt>
            <i>Postal_Code: </i>27709</dt>
           <dt>
            <i>Country: </i>United States of America</dt>
          </dl>
         </dd>
         <dt>
          <i>Contact_Voice_Telephone: </i>Prefer contact via email</dt>
         <dt>
          <i>Contact_Electronic_Mail_Address: </i>
          <TT>dennis.hallema@usda.gov</TT>
         </dt>
        </dl>
       </dd>
      </dl>
     </dd>
     <dt>
      <i>Metadata_Standard_Name: </i>FGDC Biological Data Profile of the Content Standard for Digital Geospatial Metadata</dt>
     <dt>
      <i>Metadata_Standard_Version: </i>FGDC-STD-001.1-1999</dt>
    </dl>
   </dd>
  </dl>
  <a
   href="#Top">Back to Top</a>
