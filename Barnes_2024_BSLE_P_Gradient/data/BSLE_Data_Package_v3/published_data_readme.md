# how to download public data

To be able to run the scripts in this repo, one must download files from this associated data package: 
> Grieger S ; Aronstein P ; Bailey J ; Barnes M ; Barton R ; Bladon K D ; Chu R ; Forbes B ; Garayburu-Caruso V A ; Graham E B ; Goldman A E ; Homolka K ; Kew W ; Lipton A S ; McKever S A ; Munson K M ; Myers C R ; Nieto-Pereira N ; O'Day P ; Otenburg O ; Regier T ; Renteria L ; Roebuck A ; Scheibe T D ; Torgeson J M ; Toyoda J G ; Wagner S ; Winston I ; Young R P ; Myers-Pigg A (2022): Organic matter concentration and composition of experimentally burned open air and muffle furnace vegetation chars across differing burn severity and feedstock types from Pacific Northwest, USA (v3). River Corridor and Watershed Biogeochemistry SFA, ESS-DIVE repository. Dataset. doi:10.15485/1894135 accessed via https://data.ess-dive.lbl.gov/datasets/doi:10.15485/1894135

Download these files: 
-   v1_BSLE_Metadata_and_Protocols.zip
-   v3_BSLE_Data.zip (Version number may change with subsequent releases)

Within the `data` folder, if it doesn't already exist, create a new folder called "BSLE_Data_Package_v3". Insert unzipped versions of the two folders downloaded above. Maintain the original folders and folder names.

Once downloaded this is what your newly downloaded files should look like: 

``` 
rcsfa-RC3-BSLE_P/Barnes_2024_BSLE_P_Gradient/data/BSLE_Data_Package_v3
├── published_data_readme.md
├── v1_BSLE_Metadata_and_Protocols
│   ├── BLSE_IGSN-Mapping.csv
│   ├── BSLE_Burn_and_Laboratory_Metadata.csv
│   ├── BSLE_Burn_Protocol.pdf
│   ├── BSLE_Laboratory_Protocol.pdf
│   ├── BSLE_Vegetation_Collection_Metadata.csv
│   └── BSLE_Vegetation_Collection_Protocol.pdf
└── v3_BSLE_Data
    ├── BSLE_13C-NMR_Methods.csv
    ├── BSLE_31P-NMR.csv
    ├── BSLE_31P-NMR_Methods.csv
    ├── BSLE_B5CA_B6CA.csv
    ├── BSLE_CN.csv
    ├── BSLE_EEMs
    │   ├── Absorbance
    │   │   ├── BSLE_0001A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0001B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0001C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0002A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0002B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0002C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0003A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0003B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0003C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0004A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0004B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0004C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0005A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0005B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0005C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0006A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0006B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0006C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0007A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0007B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0007C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0008A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0008B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0008C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0009A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0009B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0009C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0010A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0010B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0010C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0011A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0011B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0011C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0012A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0012B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0012C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0013A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0013B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0013C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0014A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0014B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0014C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0016A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0016B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0016C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0017A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0017B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0017C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0018A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0018B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0018C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0019A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0019B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0019C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0020A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0020B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0020C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0021A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0021B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0021C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0022A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0022B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0022C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0023A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0023B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0023C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0024B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0024C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0025A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0025B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0025C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0026A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0026B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0026C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0027A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0027B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0027C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0028A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0028B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0028C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0029A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0029B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0029C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0030A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0030B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0030C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0031A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0031B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0031C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0032A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0032B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0032C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0033A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0033B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0033C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0034A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0034B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0034C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0035A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0035B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0035C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0036A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0036B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0036C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0037A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0037B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0037C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0038A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0038B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0038C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0039A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0039B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0039C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0040A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0040B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0040C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0041A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0041B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0041C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0042A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0042B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0042C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0043A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0043B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0043C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0044A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0044B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0044C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0045A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0045B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0045C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0046A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0046B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0046C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0047A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0047B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0047C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0050A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0050B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0050C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0051A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0051B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0051C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0052A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0052B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0052C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0055A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0055B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0055C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0056A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0056B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0056C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0057A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0057B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0057C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0058A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0058B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0058C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0060A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0060B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0060C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0061A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0061B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0061C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0063A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0063B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0063C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0065A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0065B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0065C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0066A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0066B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0066C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0067A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0067B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0067C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0068A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0068B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0068C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0070A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0070B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0070C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0071A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0071B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0071C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0072A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0072B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0072C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0073A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0073B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0073C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0079A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0079B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0079C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0083A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0083B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0083C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0084A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0084B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0084C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0085A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0085B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0085C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0086A-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0086B-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_0086C-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank1-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank10-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank11-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank12-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank13-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank14-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank16-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank17-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank19-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank2-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank21-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank22-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank23-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank24-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank25-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank26-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank3-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank4-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank5-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank6-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank7-filt0.2_DilCorr_Abs.dat
    │   │   ├── BSLE_Blank8-filt0.2_DilCorr_Abs.dat
    │   │   └── BSLE_Blank9-filt0.2_DilCorr_Abs.dat
    │   ├── EEMs_Matlab_Code.txt
    │   ├── EEMs_Matlab_Code_Instructions.txt
    │   ├── Fluorescence
    │   │   ├── BSLE_0001A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0001B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0001C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0002A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0002B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0002C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0003A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0003B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0003C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0004A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0004B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0004C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0005A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0005B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0005C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0006A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0006B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0006C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0007A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0007B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0007C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0008A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0008B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0008C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0009A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0009B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0009C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0010A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0010B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0010C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0011A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0011B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0011C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0012A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0012B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0012C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0013A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0013B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0013C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0014A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0014B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0014C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0016A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0016B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0016C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0017A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0017B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0017C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0018A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0018B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0018C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0019A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0019B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0019C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0020A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0020B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0020C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0021A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0021B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0021C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0022A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0022B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0022C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0023A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0023B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0023C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0024B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0024C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0025A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0025B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0025C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0026A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0026B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0026C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0027A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0027B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0027C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0028A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0028B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0028C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0029A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0029B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0029C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0030A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0030B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0030C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0031A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0031B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0031C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0032A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0032B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0032C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0033A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0033B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0033C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0034A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0034B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0034C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0035A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0035B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0035C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0036A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0036B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0036C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0037A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0037B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0037C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0038A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0038B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0038C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0039A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0039B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0039C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0040A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0040B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0040C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0041A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0041B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0041C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0042A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0042B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0042C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0043A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0043B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0043C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0044A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0044B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0044C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0045A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0045B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0045C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0046A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0046B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0046C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0047A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0047B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0047C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0050A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0050B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0050C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0051A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0051B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0051C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0052A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0052B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0052C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0055A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0055B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0055C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0056A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0056B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0056C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0057A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0057B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0057C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0058A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0058B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0058C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0060A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0060B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0060C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0061A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0061B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0061C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0063A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0063B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0063C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0065A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0065B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0065C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0066A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0066B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0066C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0067A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0067B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0067C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0068A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0068B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0068C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0070A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0070B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0070C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0071A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0071B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0071C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0072A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0072B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0072C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0073A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0073B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0073C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0079A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0079B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0079C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0083A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0083B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0083C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0084A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0084B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0084C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0085A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0085B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0085C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0086A-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0086B-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_0086C-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank1-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank10-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank11-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank12-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank13-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank14-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank16-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank17-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank19-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank2-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank21-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank22-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank23-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank24-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank25-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank26-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank3-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank4-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank5-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank6-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank7-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   ├── BSLE_Blank8-filt0.2_DilCorr_IFE_RamNorm.dat
    │   │   └── BSLE_Blank9-filt0.2_DilCorr_IFE_RamNorm.dat
    │   ├── SampleLog.csv
    │   └── SpectralIndicesExport.txt
    ├── BSLE_EEMs_Methods.csv
    ├── BSLE_FTICR
    │   ├── Formularity_Log_Processing_v2.R
    │   ├── FTICR_Data
    │   │   ├── BSLE_0001A-filt0.2.txt
    │   │   ├── BSLE_0001B-filt0.2.txt
    │   │   ├── BSLE_0001C-filt0.2.txt
    │   │   ├── BSLE_0002A-filt0.2.txt
    │   │   ├── BSLE_0002B-filt0.2.txt
    │   │   ├── BSLE_0002C-filt0.2.txt
    │   │   ├── BSLE_0003A-filt0.2.txt
    │   │   ├── BSLE_0003B-filt0.2.txt
    │   │   ├── BSLE_0003C-filt0.2.txt
    │   │   ├── BSLE_0004A-filt0.2.txt
    │   │   ├── BSLE_0004B-filt0.2.txt
    │   │   ├── BSLE_0004C-filt0.2.txt
    │   │   ├── BSLE_0005A-filt0.2.txt
    │   │   ├── BSLE_0005B-filt0.2.txt
    │   │   ├── BSLE_0005C-filt0.2.txt
    │   │   ├── BSLE_0006A-filt0.2.txt
    │   │   ├── BSLE_0006B-filt0.2.txt
    │   │   ├── BSLE_0006C-filt0.2.txt
    │   │   ├── BSLE_0007A-filt0.2.txt
    │   │   ├── BSLE_0007B-filt0.2.txt
    │   │   ├── BSLE_0007C-filt0.2.txt
    │   │   ├── BSLE_0008A-filt0.2.txt
    │   │   ├── BSLE_0008B-filt0.2.txt
    │   │   ├── BSLE_0008C-filt0.2.txt
    │   │   ├── BSLE_0009A-filt0.2.txt
    │   │   ├── BSLE_0009B-filt0.2.txt
    │   │   ├── BSLE_0009C-filt0.2.txt
    │   │   ├── BSLE_0010A-filt0.2.txt
    │   │   ├── BSLE_0010B-filt0.2.txt
    │   │   ├── BSLE_0010C-filt0.2.txt
    │   │   ├── BSLE_0011A-filt0.2.txt
    │   │   ├── BSLE_0011B-filt0.2.txt
    │   │   ├── BSLE_0011C-filt0.2.txt
    │   │   ├── BSLE_0012A-filt0.2.txt
    │   │   ├── BSLE_0012B-filt0.2.txt
    │   │   ├── BSLE_0012C-filt0.2.txt
    │   │   ├── BSLE_0013A-filt0.2.txt
    │   │   ├── BSLE_0013B-filt0.2.txt
    │   │   ├── BSLE_0013C-filt0.2.txt
    │   │   ├── BSLE_0014A-filt0.2.txt
    │   │   ├── BSLE_0014B-filt0.2.txt
    │   │   ├── BSLE_0014C-filt0.2.txt
    │   │   ├── BSLE_0016A-filt0.2.txt
    │   │   ├── BSLE_0016B-filt0.2.txt
    │   │   ├── BSLE_0016C-filt0.2.txt
    │   │   ├── BSLE_0017A-filt0.2.txt
    │   │   ├── BSLE_0017B-filt0.2.txt
    │   │   ├── BSLE_0017C-filt0.2.txt
    │   │   ├── BSLE_0018A-filt0.2.txt
    │   │   ├── BSLE_0018B-filt0.2.txt
    │   │   ├── BSLE_0018C-filt0.2.txt
    │   │   ├── BSLE_0019A-filt0.2.txt
    │   │   ├── BSLE_0019B-filt0.2.txt
    │   │   ├── BSLE_0019C-filt0.2.txt
    │   │   ├── BSLE_0020A-filt0.2.txt
    │   │   ├── BSLE_0020B-filt0.2.txt
    │   │   ├── BSLE_0020C-filt0.2.txt
    │   │   ├── BSLE_0021A-filt0.2.txt
    │   │   ├── BSLE_0021B-filt0.2.txt
    │   │   ├── BSLE_0021C-filt0.2.txt
    │   │   ├── BSLE_0022A-filt0.2.txt
    │   │   ├── BSLE_0022B-filt0.2.txt
    │   │   ├── BSLE_0022C-filt0.2.txt
    │   │   ├── BSLE_0023A-filt0.2.txt
    │   │   ├── BSLE_0023B-filt0.2.txt
    │   │   ├── BSLE_0023C-filt0.2.txt
    │   │   ├── BSLE_0024A-filt0.2.txt
    │   │   ├── BSLE_0024B-filt0.2.txt
    │   │   ├── BSLE_0024C-filt0.2.txt
    │   │   ├── BSLE_0025A-filt0.2.txt
    │   │   ├── BSLE_0025B-filt0.2.txt
    │   │   ├── BSLE_0025C-filt0.2.txt
    │   │   ├── BSLE_0026A-filt0.2.txt
    │   │   ├── BSLE_0026B-filt0.2.txt
    │   │   ├── BSLE_0026C-filt0.2.txt
    │   │   ├── BSLE_0027A-filt0.2.txt
    │   │   ├── BSLE_0027B-filt0.2.txt
    │   │   ├── BSLE_0027C-filt0.2.txt
    │   │   ├── BSLE_0028A-filt0.2.txt
    │   │   ├── BSLE_0028B-filt0.2.txt
    │   │   ├── BSLE_0028C-filt0.2.txt
    │   │   ├── BSLE_0029A-filt0.2.txt
    │   │   ├── BSLE_0029B-filt0.2.txt
    │   │   ├── BSLE_0029C-filt0.2.txt
    │   │   ├── BSLE_0030A-filt0.2.txt
    │   │   ├── BSLE_0030B-filt0.2.txt
    │   │   ├── BSLE_0030C-filt0.2.txt
    │   │   ├── BSLE_0031A-filt0.2.txt
    │   │   ├── BSLE_0031B-filt0.2.txt
    │   │   ├── BSLE_0031C-filt0.2.txt
    │   │   ├── BSLE_0032A-filt0.2.txt
    │   │   ├── BSLE_0032B-filt0.2.txt
    │   │   ├── BSLE_0032C-filt0.2.txt
    │   │   ├── BSLE_0033A-filt0.2.txt
    │   │   ├── BSLE_0033B-filt0.2.txt
    │   │   ├── BSLE_0033C-filt0.2.txt
    │   │   ├── BSLE_0034A-filt0.2.txt
    │   │   ├── BSLE_0034B-filt0.2.txt
    │   │   ├── BSLE_0034C-filt0.2.txt
    │   │   ├── BSLE_0035A-filt0.2.txt
    │   │   ├── BSLE_0035B-filt0.2.txt
    │   │   ├── BSLE_0035C-filt0.2.txt
    │   │   ├── BSLE_0036A-filt0.2.txt
    │   │   ├── BSLE_0036B-filt0.2.txt
    │   │   ├── BSLE_0036C-filt0.2.txt
    │   │   ├── BSLE_0037A-filt0.2.txt
    │   │   ├── BSLE_0037B-filt0.2.txt
    │   │   ├── BSLE_0037C-filt0.2.txt
    │   │   ├── BSLE_0038A-filt0.2.txt
    │   │   ├── BSLE_0038B-filt0.2.txt
    │   │   ├── BSLE_0038C-filt0.2.txt
    │   │   ├── BSLE_0039A-filt0.2.txt
    │   │   ├── BSLE_0039B-filt0.2.txt
    │   │   ├── BSLE_0039C-filt0.2.txt
    │   │   ├── BSLE_0040A-filt0.2.txt
    │   │   ├── BSLE_0040B-filt0.2.txt
    │   │   ├── BSLE_0040C-filt0.2.txt
    │   │   ├── BSLE_0041A-filt0.2.txt
    │   │   ├── BSLE_0041B-filt0.2.txt
    │   │   ├── BSLE_0041C-filt0.2.txt
    │   │   ├── BSLE_0042A-filt0.2.txt
    │   │   ├── BSLE_0042B-filt0.2.txt
    │   │   ├── BSLE_0042C-filt0.2.txt
    │   │   ├── BSLE_0043A-filt0.2.txt
    │   │   ├── BSLE_0043B-filt0.2.txt
    │   │   ├── BSLE_0043C-filt0.2.txt
    │   │   ├── BSLE_0044A-filt0.2.txt
    │   │   ├── BSLE_0044B-filt0.2.txt
    │   │   ├── BSLE_0044C-filt0.2.txt
    │   │   ├── BSLE_0045A-filt0.2.txt
    │   │   ├── BSLE_0045B-filt0.2.txt
    │   │   ├── BSLE_0045C-filt0.2.txt
    │   │   ├── BSLE_0046A-filt0.2.txt
    │   │   ├── BSLE_0046B-filt0.2.txt
    │   │   ├── BSLE_0046C-filt0.2.txt
    │   │   ├── BSLE_0047A-filt0.2.txt
    │   │   ├── BSLE_0047B-filt0.2.txt
    │   │   ├── BSLE_0047C-filt0.2.txt
    │   │   ├── BSLE_0050A-filt0.2.txt
    │   │   ├── BSLE_0050B-filt0.2.txt
    │   │   ├── BSLE_0050C-filt0.2.txt
    │   │   ├── BSLE_0051A-filt0.2.txt
    │   │   ├── BSLE_0051B-filt0.2.txt
    │   │   ├── BSLE_0051C-filt0.2.txt
    │   │   ├── BSLE_0052A-filt0.2.txt
    │   │   ├── BSLE_0052B-filt0.2.txt
    │   │   ├── BSLE_0052C-filt0.2.txt
    │   │   ├── BSLE_0055A-filt0.2.txt
    │   │   ├── BSLE_0055B-filt0.2.txt
    │   │   ├── BSLE_0055C-filt0.2.txt
    │   │   ├── BSLE_0056A-filt0.2.txt
    │   │   ├── BSLE_0056B-filt0.2.txt
    │   │   ├── BSLE_0056C-filt0.2.txt
    │   │   ├── BSLE_0057A-filt0.2.txt
    │   │   ├── BSLE_0057B-filt0.2.txt
    │   │   ├── BSLE_0057C-filt0.2.txt
    │   │   ├── BSLE_0058A-filt0.2.txt
    │   │   ├── BSLE_0058B-filt0.2.txt
    │   │   ├── BSLE_0058C-filt0.2.txt
    │   │   ├── BSLE_0060A-filt0.2.txt
    │   │   ├── BSLE_0060B-filt0.2.txt
    │   │   ├── BSLE_0060C-filt0.2.txt
    │   │   ├── BSLE_0061A-filt0.2.txt
    │   │   ├── BSLE_0061B-filt0.2.txt
    │   │   ├── BSLE_0061C-filt0.2.txt
    │   │   ├── BSLE_0063A-filt0.2.txt
    │   │   ├── BSLE_0063B-filt0.2.txt
    │   │   ├── BSLE_0063C-filt0.2.txt
    │   │   ├── BSLE_0065A-filt0.2.txt
    │   │   ├── BSLE_0065B-filt0.2.txt
    │   │   ├── BSLE_0065C-filt0.2.txt
    │   │   ├── BSLE_0066A-filt0.2.txt
    │   │   ├── BSLE_0066B-filt0.2.txt
    │   │   ├── BSLE_0066C-filt0.2.txt
    │   │   ├── BSLE_0067A-filt0.2.txt
    │   │   ├── BSLE_0067B-filt0.2.txt
    │   │   ├── BSLE_0067C-filt0.2.txt
    │   │   ├── BSLE_0068A-filt0.2.txt
    │   │   ├── BSLE_0068B-filt0.2.txt
    │   │   ├── BSLE_0068C-filt0.2.txt
    │   │   ├── BSLE_0070A-filt0.2.txt
    │   │   ├── BSLE_0070B-filt0.2.txt
    │   │   ├── BSLE_0070C-filt0.2.txt
    │   │   ├── BSLE_Blank1-filt0.2.txt
    │   │   ├── BSLE_Blank10-filt0.2.txt
    │   │   ├── BSLE_Blank11-filt0.2.txt
    │   │   ├── BSLE_Blank12-filt0.2.txt
    │   │   ├── BSLE_Blank13-filt0.2.txt
    │   │   ├── BSLE_Blank14-filt0.2.txt
    │   │   ├── BSLE_Blank15-filt0.2.txt
    │   │   ├── BSLE_Blank16-filt0.2.txt
    │   │   ├── BSLE_Blank17-filt0.2.txt
    │   │   ├── BSLE_Blank18-filt0.2.txt
    │   │   ├── BSLE_Blank19-filt0.2.txt
    │   │   ├── BSLE_Blank2-filt0.2.txt
    │   │   ├── BSLE_Blank20-filt0.2.txt
    │   │   ├── BSLE_Blank21-filt0.2.txt
    │   │   ├── BSLE_Blank22-filt0.2.txt
    │   │   ├── BSLE_Blank23-filt0.2.txt
    │   │   ├── BSLE_Blank24-filt0.2.txt
    │   │   ├── BSLE_Blank3-filt0.2.txt
    │   │   ├── BSLE_Blank4-filt0.2.txt
    │   │   ├── BSLE_Blank5-filt0.2.txt
    │   │   ├── BSLE_Blank6-filt0.2.txt
    │   │   ├── BSLE_Blank7-filt0.2.txt
    │   │   ├── BSLE_Blank8-filt0.2.txt
    │   │   └── BSLE_Blank9-filt0.2.txt
    │   ├── FTICR_Instructions-Report_Generation_SOP_21T-Thermo.pdf
    │   └── Hawkes_neg.ref
    ├── BSLE_FTICR_Methods.csv
    ├── BSLE_ICP.csv
    ├── BSLE_ICP_PNMR.csv
    ├── BSLE_ICP_Solid.csv
    ├── BSLE_InstallationMethods.csv
    ├── BSLE_MBD.csv
    ├── BSLE_P-NMR_Spiking_Table.pdf
    ├── BSLE_P-XANES_Methods.csv
    ├── BSLE_pH.csv
    ├── BSLE_Thermocouple.csv
    ├── BSLE_XANES
    │   ├── P-XANES_Ref_Cmpd
    │   │   ├── P-XANES_RefCmpd_Table.pdf
    │   │   ├── Pi_Al_GibbSorb_std.xmu
    │   │   ├── Pi_Al_Precip_std.xmu
    │   │   ├── Pi_Al_std.xmu
    │   │   ├── Pi_Apatite_CaDefHydroxy_std.xmu
    │   │   ├── Pi_Apatite_Carbonate_std.xmu
    │   │   ├── Pi_Apatite_Fluor_std.xmu
    │   │   ├── Pi_Apatite_Hydroxy_std.xmu
    │   │   ├── Pi_Ca_Dibasic_std.xmu
    │   │   ├── Pi_Ca_Mono_std.xmu
    │   │   ├── Pi_Ca_Octa_std.xmu
    │   │   ├── Pi_Ca_Precip_std.xmu
    │   │   ├── Pi_Ca_Pyro_std.xmu
    │   │   ├── Pi_Ca_Tri_std.xmu
    │   │   ├── Pi_Fe_FerriSorb_std.xmu
    │   │   ├── Pi_Fe_GoethSorb_std.xmu
    │   │   ├── Pi_Fe_Precip_std.xmu
    │   │   ├── Pi_Fe_Pyro_std.xmu
    │   │   ├── Pi_Fe_std.xmu
    │   │   ├── Pi_K_Di_std.xmu
    │   │   ├── Pi_K_Pyro_std.xmu
    │   │   ├── Pi_Mg_Di_std.xmu
    │   │   ├── Pi_Mg_Pyro_std.xmu
    │   │   ├── Pi_Mg_Tri_std.xmu
    │   │   ├── Pi_Na_Di_std.xmu
    │   │   ├── Pi_Na_Mono_std.xmu
    │   │   ├── Pi_Na_Pyro_std.xmu
    │   │   ├── Pi_Na_Tri_std.xmu
    │   │   ├── Pi_NH4_Di_std.xmu
    │   │   ├── Pi_NH4_Mg_std.xmu
    │   │   ├── Pi_NH4_Mono_std.xmu
    │   │   ├── Po_Al_DNA_GibbSorb_2_std.xmu
    │   │   ├── Po_Al_DNA_GibbSorb_std.xmu
    │   │   ├── Po_Al_PA_GibbSorb_std.xmu
    │   │   ├── Po_Al_PA_Precip_std.xmu
    │   │   ├── Po_Ca_Lecithin_std.xmu
    │   │   ├── Po_Ca_PA_std.xmu
    │   │   ├── Po_Fe_DNA_FerriSorb_std.xmu
    │   │   ├── Po_Fe_DNA_GoethSorb_std.xmu
    │   │   ├── Po_Fe_PA_FerriSorb_2_std.xmu
    │   │   ├── Po_Fe_PA_FerriSorb_std.xmu
    │   │   ├── Po_Fe_PA_GoethSorb_std.xmu
    │   │   ├── Po_Fe_PA_Precip_std.xmu
    │   │   ├── Po_Na_AMP_std.xmu
    │   │   ├── Po_Na_ATP_std.xmu
    │   │   ├── Po_Na_DNA_std.xmu
    │   │   └── Po_Na_PA_std.xmu
    │   └── P-XANES_Samples
    │       ├── BSLE_0001-filt0.7_P-XANES.xmu
    │       ├── BSLE_0001-part_P-XANES.xmu
    │       ├── BSLE_0001-solid_P-XANES.xmu
    │       ├── BSLE_0002-filt0.7_P-XANES.xmu
    │       ├── BSLE_0002-part_P-XANES.xmu
    │       ├── BSLE_0002-solid_P-XANES.xmu
    │       ├── BSLE_0003-filt0.7_P-XANES.xmu
    │       ├── BSLE_0003-part_P-XANES.xmu
    │       ├── BSLE_0003-solid_P-XANES.xmu
    │       ├── BSLE_0004-filt0.7_P-XANES.xmu
    │       ├── BSLE_0004-part_P-XANES.xmu
    │       ├── BSLE_0004-solid_P-XANES.xmu
    │       ├── BSLE_0005-filt0.7_P-XANES.xmu
    │       ├── BSLE_0005-solid_P-XANES.xmu
    │       ├── BSLE_0006-filt0.7_P-XANES.xmu
    │       ├── BSLE_0006-part_P-XANES.xmu
    │       ├── BSLE_0006-solid_P-XANES.xmu
    │       ├── BSLE_0007-filt0.7_P-XANES.xmu
    │       ├── BSLE_0007-part_P-XANES.xmu
    │       ├── BSLE_0007-solid_P-XANES.xmu
    │       ├── BSLE_0008-filt0.7_P-XANES.xmu
    │       ├── BSLE_0008-part_P-XANES.xmu
    │       ├── BSLE_0008-solid_P-XANES.xmu
    │       ├── BSLE_0009-filt0.7_P-XANES.xmu
    │       ├── BSLE_0009-part_P-XANES.xmu
    │       ├── BSLE_0009-solid_P-XANES.xmu
    │       ├── BSLE_0010-filt0.7_P-XANES.xmu
    │       ├── BSLE_0010-part_P-XANES.xmu
    │       ├── BSLE_0010-solid_P-XANES.xmu
    │       ├── BSLE_0011-filt0.7_P-XANES.xmu
    │       ├── BSLE_0011-part_P-XANES.xmu
    │       ├── BSLE_0011-solid_P-XANES.xmu
    │       ├── BSLE_0012-filt0.7_P-XANES.xmu
    │       ├── BSLE_0012-part_P-XANES.xmu
    │       ├── BSLE_0012-solid_P-XANES.xmu
    │       ├── BSLE_0013-filt0.7_P-XANES.xmu
    │       ├── BSLE_0013-part_P-XANES.xmu
    │       ├── BSLE_0013-solid_P-XANES.xmu
    │       ├── BSLE_0014-filt0.7_P-XANES.xmu
    │       ├── BSLE_0014-part_P-XANES.xmu
    │       ├── BSLE_0014-solid_P-XANES.xmu
    │       ├── BSLE_0016-filt0.7_P-XANES.xmu
    │       ├── BSLE_0016-part_P-XANES.xmu
    │       ├── BSLE_0016-solid_P-XANES.xmu
    │       ├── BSLE_0017-filt0.7_P-XANES.xmu
    │       ├── BSLE_0017-part_P-XANES.xmu
    │       ├── BSLE_0017-solid_P-XANES.xmu
    │       ├── BSLE_0050-filt0.7_P-XANES.xmu
    │       ├── BSLE_0050-part_P-XANES.xmu
    │       ├── BSLE_0050-solid_P-XANES.xmu
    │       ├── BSLE_0051-filt0.7_P-XANES.xmu
    │       ├── BSLE_0051-part_P-XANES.xmu
    │       ├── BSLE_0051-solid_P-XANES.xmu
    │       ├── BSLE_0052-filt0.7_P-XANES.xmu
    │       ├── BSLE_0052-part_P-XANES.xmu
    │       ├── BSLE_0052-solid_P-XANES.xmu
    │       ├── BSLE_0058-filt0.7_P-XANES.xmu
    │       ├── BSLE_0058-part_P-XANES.xmu
    │       ├── BSLE_0058-solid_P-XANES.xmu
    │       ├── BSLE_0067-solid_P-XANES.xmu
    │       ├── BSLE_0068-solid_P-XANES.xmu
    │       ├── BSLE_0071-solid_P-XANES.xmu
    │       ├── BSLE_0072-solid_P-XANES.xmu
    │       └── BSLE_0073-solid_P-XANES.xmu
    ├── v2_BSLE_13C-NMR.csv
    ├── v2_BSLE_NPOC_TN.csv
    └── v3_BSLE_Methods_Codes.csv

```
