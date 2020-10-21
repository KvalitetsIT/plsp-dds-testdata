# plsp-dds-testdata

XML templates: http://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/

Vedr. anvendelse af CDA Document Viewer til fremsøgning af dokumenter
 * Der kræves login for adgang til CDA Vieweren
 * Der skal vælges "Default MOCES" certifikat ved søgningen

##  1. Birgitte Holst Søgaard 0504899756

DTG: https://stamdata.nspop.dk/dtg-webservice/persons/0504899756

| Nr  | Testens formål                                                                       | Template                                                                                                                                                                                                                 | Dokument id                                      | Faktisk xml                                                                           | Cda viewer link           |
| --- | --- | --- | --- | --- | --- | 
| 0101 | Kommune, minimum indhold                                                            | [APD_Example_1_1_apd_minimum.xml](http://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_1_apd_minimum.xml)                                          | test0101-7953-49ce-8653-cp0504899756^1.2.208.184 | [XML](./xmlfiler/101_0504899756_DK-APD_Example_1_1_apd_minimum.xml)                   | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=0504899756&uniqueID=test0101-7953-49ce-8653-cp0504899756%5e1.2.208.184) |
| 0102 | Kommune, to aftaler med samme repeterende ID (test0100-0001-4162-ba28-cp0504899756) | [DK-APD_Example_1_4_apd_municipality_a.xml](http://svn.medcom.dk/svn/drafts/Standarder/HL7/Appointment/Eksempler/2.0/DK-APD_Example_1_4_apd_municipality_a.xml)                                                          | test0102-7953-49ce-8653-cp0504899756^1.2.208.184 | [XML](./xmlfiler/102_0504899756_DK-APD_Example_1_4_apd_municipality_a.xml)            | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=0504899756&uniqueID=test0102-7953-49ce-8653-cp0504899756%5e1.2.208.184) |
| 0103 | Kommune, to aftaler med samme repeterende ID (test0100-0001-4162-ba28-cp0504899756) | [DK-APD_Example_1_4_apd_municipality_a.xml](http://svn.medcom.dk/svn/drafts/Standarder/HL7/Appointment/Eksempler/2.0/DK-APD_Example_1_4_apd_municipality_a.xml)                                                          | test0103-7953-49ce-8653-cp0504899756^1.2.208.184 | [XML](./xmlfiler/103_0504899756_DK-APD_Example_1_4_apd_municipality_a.xml)            | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=0504899756&uniqueID=test0103-7953-49ce-8653-cp0504899756%5e1.2.208.184) |
| 0104 | Kommune, tidspunktet er vejledende (i fremtiden)                                    | [DK-APD_Example_1_10_apd_municipality_morning_sbj.xml](https://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_10_apd_municipality_morning_sbj.xml)  | test0104-7953-49ce-8653-cp0504899756^1.2.208.184 | [XML](./xmlfiler/104_0504899756_DK-APD_Example_1_10_apd_municipality_morning_sbj.xml) | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=0504899756&uniqueID=test0104-7953-49ce-8653-cp0504899756%5e1.2.208.184) |
| 0105 | Kommune, overstået aftale                                                           | [APD_Example_1_1_apd_minimum.xml](http://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_1_apd_minimum.xml)                                          | test0105-7953-49ce-8653-cp0504899756^1.2.208.184 | [XML](./xmlfiler/105_0504899756_DK-APD_Example_1_1_apd_minimum.xml)                   | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=0504899756&uniqueID=test0105-7953-49ce-8653-cp0504899756%5e1.2.208.184) |

##  2. Mads Svendsen 2202789083

DTG: https://stamdata.nspop.dk/dtg-webservice/persons/2202789083

| Nr  | Testens formål                                                                       | Template                                                                                                                                                                                                                 | Dokument id                                      | Faktisk xml                                                                           | Cda viewer link           |
| --- | --- | --- |--- | --- | --- | 
| 0201 | Region, aftale i fremtiden hvor start og sluttidspunkt er ikke samme dato           | [DK-APD_Example_1_12_apd_region_days.xml](https://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_12_apd_region_days.xml)                            | test0201-7953-49ce-8653-cp2202789083^1.2.208.184 | [XML](./xmlfiler/201_2202789083_DK-APD_Example_1_12_apd_region_days.xml)              | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=2202789083&uniqueID=test0201-7953-49ce-8653-cp2202789083%5e1.2.208.184) |
| 0202 | Region, aftale uden tidspunkt                                                       | [DK-APD_Example_1_7_apd_region_all_day.xml)](https://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_7_apd_region_all_day.xml)                       | test0202-7953-49ce-8653-cp2202789083^1.2.208.184 | [XML](./xmlfiler/202_2202789083_DK-APD_Example_1_7_apd_region_all_day)                | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=2202789083&uniqueID=test0202-7953-49ce-8653-cp2202789083%5e1.2.208.184) |
| 0203 | Region, overstået aftale                                                            | [DK-APD_Example_1_5_apd_region.xml](http://svn.medcom.dk/svn/releases/Standarder/HL7/Appointment/Eksempler/2.0/APD-DK_2_0_1_Testprotokol_v1.0/DK-APD_Example_1_5_apd_region.xml)                                         | test0203-7953-49ce-8653-cp2202789083^1.2.208.184 | [XML](./xmlfiler/203_2202789083_DK-APD_Example_1_5_apd_region.xml)                    | [Dokument](https://cdaviewer.medcom.dk/cdaviewer-test1/search?patientID=2202789083&uniqueID=test0203-7953-49ce-8653-cp2202789083%5e1.2.208.184) |

##  3. Fie Jørgensen 0705683972
(IKKE APP AKTIV)

DTG: https://stamdata.nspop.dk/dtg-webservice/persons/0705683972

| Nr  | Testens formål                                                                       | Template                                                                                                                                                                                                                 | Dokument id                                      | Faktisk xml                                                                           | Cda viewer link           |
| --- | --- | --- |--- | --- | --- | 
| 0301 | Kommune, aftale i fremtid | []()  |  |  |  |
| 0302 | Kommune, overstået aftale | []()  |  |  |  |
| 0303 | Region, aftale i fremtid | []()  |  |  |  |
| 0304 | Region, overstået aftale | []()  |  |  |  |

##  4. Grete Larsen 0404849086

DTG: https://stamdata.nspop.dk/dtg-webservice/persons/0404849086

| Nr  | Testens formål                                                                       | Template                                                                                                                                                                                                                 | Dokument id                                      | Faktisk xml                                                                           | Cda viewer link           |
| --- | --- | --- |--- | --- | --- | 
| 0401 | Navne- og adressebeskyttelse | []()  |  |  |  |


##  5. Hans Petersen 1710194919

DTG: https://stamdata.nspop.dk/dtg-webservice/persons/1710194919

| Nr  | Testens formål                                                                       | Template                                                                                                                                                                                                                 | Dokument id                                      | Faktisk xml                                                                           | Cda viewer link           |
| --- | --- | --- |--- | --- | --- | 
| 0501 | Barn | []()  |  |  |  |


