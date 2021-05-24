# This folder contains the data necessary to run the code :)

## scPDSI Data

Full scPDSI data available [here](https://psl.noaa.gov/data/gridded/data.pdsi.html)

_Dai, A., K. E. Trenberth, and T. Qian, 2004: A global data set of Palmer Drought Severity Index for 1870-2002: Relationship with soil moisture and effects of surface warming. J. Hydrometeorology, 5, 1117-1130._

### The original scPDSI Data has this information:

* Format: classic

* Global Attributes:
 * title           = 'Global Monthly Dai Palmer Drought Severity Index'
 * history         = 'created Apr 2013 from data at NCAR webpage:updated Nov 2015 from new dataset version'
 * References      = 'https://www.esrl.noaa.gov/psd/data/gridded/data.pdsi.html'
 * original_source = 'NCAR/UCAR: A Dai http://www.cgd.ucar.edu/cas/catalog/climind/pdsi.html.'
 * comments        = 'original creation date: Thu Oct 25 15:25:40 MDT 2012 at NCAR. Updated at PSD Oct 2016 with corrected NCAR data'
 * Conventions     = 'COARDS'
 * details         = 'see ncar for more detials and updates'
 * description     = '
                   Monthly Self-calibrated Palmer Drought Severity Index (scPDSI)     
                   calculated using observed surface air temperature (HadCRUT4 from   
                   http://www.cru.uea.ac.uk/cru/data/temperature/ ) and               
                   precipitation (from Dai et al. (1997, J.Clim: for 1870-1947) +     
                   Chen et al. (2002, J. Hydromet.: for 1948-1978 + GPCP v2.2 for     
                   1979-present. The Dai and Chen P data were adjusted to have the    
                   same mean as the GPCP data over the 1979-1996 period).             
                   Calibration (or reference) period is 1950-1979.                    
                   Wind speed and air pressure data were from 20CR v2. Other data     
                   were based on CRU TS3.22. Documention:  	                   
                   Dai, A., 2011a: Characteristics and trends in various forms of the 
                   Palmer Drought Severity Index (PDSI) during 1900-2008. J. Geophys. 
                   Res., 116, D12115, doi:10.1029/2010JD015541.			   
                   Dai, A., K. E. Trenberth, and T. Qian, 2004: A global data set of  
                   Palmer Drought Severity Index for 1870-2002: Relationship with soil
                   moisture and effects of surface warming. J. Hydrometeorology, 5,   
                   1117-1130. Data source: Dr. A. Dai/NCAR (adai@ucar.edu). See       
                   http://www.cgd.ucar.edu/cas/catalog/climind/pdsi.html for updates. 
                   WARNING: PDSI and scPDSI over the higher latitudes (e.g., >50deg.) 
                   may not be a good proxy of soil moisutre content. Also, PDSI and   
                   scPDSI are highly autocorrelated indices not good at resolving     
                   sub-seasonal variations.  Please use with caution!                 
                   This is a normalized version so that every grid box has the same   
                   s.d. as that in the central U.S. during the calibr. period (1950-79)'
 * dataset_title   = 'Palmer Drought Severity Index'

* Dimensions:
 * lon  = 144
 * lat  = 55
 * time = 1980  (UNLIMITED)

* Variables:
 * pdsi
  * Size:       144x55x1980
  * Dimensions: lon,lat,time
  * Datatype:   single
  * Attributes:
    * statistic               = 'Mean'
    * missing_value           = -99999
    * dataset                 = 'Dai Palmer Drought Severity Index: Self-calibrated'
    * long_name               = 'Monthly Self-calibrated Palmer Drought Severity Index using Penman-Monteith PE'
    * level_desc              = 'Surface'
    * var_desc                = 'Palmer Drought Severity Index'
    * least_significant_digit = 2
    * units                   = 'Standardized Units of Relative Dry and Wet'
    * actual_range            = [-8.1602      8.1601]
    * valid_range             = [-100  100]
 * lon 
  * Size:       144x1
  * Dimensions: lon
  * Datatype:   single
  * Attributes:
    * units         = 'degrees_east'
    * long_name     = 'Longitude'
    * actual_range  = [-178.75        178.75]
    * standard_name = 'longitude'
    * axis          = 'X'
 * lat 
  * Size:       55x1
  * Dimensions: lat
  * Datatype:   single
  * Attributes:
   * units         = 'degrees_north'
   * long_name     = 'Latitude'
   * actual_range  = [-58.75        76.25]
   * standard_name = 'latitude'
   * axis          = 'Y'
* time
 * Size:       1980x1
 * Dimensions: time
 * Datatype:   double
 * Attributes:
   * units         = 'hours since 1800-01-01 00:00:0.0'
   * actual_range  = [438288  1883904]
   * long_name     = 'Time'
   * delta_t       = '0000-01-00 00:00:00'
   * avg_period    = '0000-01-00 00:00:00'
   * standard_name = 'time'
   * axis          = 'T'
