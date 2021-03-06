**Get List Of Countries**
----
Returns List of Countries in JSON format.

* **URL**

```ruby
http://10.0.52.243:8080/birthcertificate/countries
```
 
* **Method:**

```ruby
POST
```
  
* **Data Params**

None
 
* **Example Request**
 
```ruby
curl --location --request POST 'http://10.0.52.243:8080/rest/api/v1/Countries'
```
  
* **Example Response**
   
* **Success Response:**

```ruby
**Code:** 200 <br />
**Description:** successful operation <br />
```
  
>  * **Code:** 200 <br />


>  * **Body:** <br />

```ruby
 [
  {
   "ISO_Code": "675",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:45:29.492Z",
    "RestrictedExport": "1",
    "NationalityAra": "قبرصية",
    "NationalityEnu": "CYPRIOTE",
    "DescriptionArabic": "قبرص",
    "DescriptionEnglish": "Cyprus",
    "Description": "قبرص",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:45:29.492Z",
    "createdDate": "2018-09-03T12:52:22.228Z"
  },
  {
    "ISO_Code": "508",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "انغولية",
    "NationalityEnu": "ANGOLIAN",
    "DescriptionArabic": "انغولا",
    "DescriptionEnglish": "Angola",
    "Description": "انغولا",
    "ActiveInd": "Active",
    "changedDate": "2018-11-28T09:50:37.922Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "729",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "يوهتان",
    "NationalityEnu": "BHUTAN",
    "DescriptionArabic": "بوهتان",
    "DescriptionEnglish": "Bhutan",
    "Description": "بوهتان",
    "ActiveInd": "Active",
    "changedDate": "2018-12-11T08:04:12.261Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "540",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر سانت هيلانة",
    "NationalityEnu": "SAINT HELENIAN",
    "DescriptionArabic": "جزر سانت هيلانة",
    "DescriptionEnglish": "Saint Helena Islands",
    "Description": "جزر سانت هيلانة",
    "ActiveInd": "Active",
    "changedDate": "2018-11-28T12:04:33.637Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "652",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تازخستانيه",
    "NationalityEnu": "تازخستانيه",
    "DescriptionArabic": "تازخستان",
    "DescriptionEnglish": "تازخستان",
    "Description": "تازخستان",
    "ActiveInd": "Active",
    "changedDate": "2020-03-08T09:39:58.629Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "830",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "هايتيه",
    "NationalityEnu": "HAITIAN",
    "DescriptionArabic": "هايتي",
    "DescriptionEnglish": "Haiti",
    "Description": "هايتي",
    "ActiveInd": "Active",
    "changedDate": "2020-03-30T13:07:51.532Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "839",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غرانادا",
    "NationalityEnu": "GRENADA",
    "DescriptionArabic": "غرانادا",
    "DescriptionEnglish": "Grenada",
    "Description": "غرانادا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "528",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بورنجي",
    "NationalityEnu": "BURUNDIAN",
    "DescriptionArabic": "بورنجي",
    "DescriptionEnglish": "Burundi",
    "Description": "بورنجي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "897",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر فيرجن",
    "NationalityEnu": "VIRGIN ISLANDS",
    "DescriptionArabic": "جزر فيرجن",
    "DescriptionEnglish": "Virgin Islands",
    "Description": "جزر فيرجن",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "993",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مينماري",
    "NationalityEnu": "MYANMARIAN",
    "DescriptionArabic": "ميانمار",
    "DescriptionEnglish": "Myanmar",
    "Description": "ميانمار",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "322",
    "CountryGroup": "Non_Local",
    "Restricted": true,
    "CurrencyName": "ليرة لبنانية",
    "CurrencyValue": 3500,
    "LastCurrencyUpdate": "2018-09-18T19:03:25.403Z",
    "PhoneCode": "961",
    "RestrictedExport": "0",
    "NationalityAra": "لبنانية",
    "NationalityEnu": "LEBANESE",
    "DescriptionArabic": "لبنان",
    "DescriptionEnglish": "Lebanon",
    "Description": "لبنان",
    "ActiveInd": "Active",
    "changedDate": "2020-03-26T13:40:52.202Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "995",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "اندوراي",
    "NationalityEnu": "ANDORRIAN",
    "DescriptionArabic": "إمارة اندورا",
    "DescriptionEnglish": "PRINCIPALITY OF ANDORRA",
    "Description": "إمارة اندورا",
    "ActiveInd": "Active",
    "changedDate": "2020-03-26T14:22:56.079Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "600",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "599",
    "RestrictedExport": "1",
    "NationalityAra": "كوراساوي",
    "NationalityEnu": "CURACAOI",
    "DescriptionArabic": "كوراساو",
    "DescriptionEnglish": "CURACAO",
    "Description": "كوراساو",
    "ActiveInd": "Active",
    "changedDate": "2018-12-12T08:33:35.977Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "907",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "استونيا",
    "NationalityEnu": "ESTONIAN",
    "DescriptionArabic": "استونيا",
    "DescriptionEnglish": "estonia",
    "Description": "استونيا",
    "ActiveInd": "Active",
    "changedDate": "2020-02-19T14:44:35.540Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "852",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "باليز",
    "NationalityEnu": "BELIZE",
    "DescriptionArabic": "باليز",
    "DescriptionEnglish": "Belize",
    "Description": "باليز",
    "ActiveInd": "Active",
    "changedDate": "2020-03-24T11:35:54.782Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "736",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار سنغافوري",
    "CurrencyValue": 3.5,
    "LastCurrencyUpdate": "2019-03-27T13:46:49.868Z",
    "RestrictedExport": "1",
    "NationalityAra": "سنغافورية",
    "NationalityEnu": "SINGAPORE",
    "DescriptionArabic": "سنغافورة",
    "DescriptionEnglish": "Singapore",
    "Description": "سنغافورة",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:46:49.868Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "672",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كوسوفو",
    "NationalityEnu": "KOSOVO",
    "DescriptionArabic": "كوسوفو",
    "DescriptionEnglish": "kosovo",
    "Description": "كوسوفو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "692",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "البانية",
    "NationalityEnu": "ALBANIAN",
    "DescriptionArabic": "البانيا",
    "DescriptionEnglish": "Albania",
    "Description": "البانيا",
    "ActiveInd": "Active",
    "changedDate": "2021-01-18T14:34:24.318Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "800",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:45:05.629Z",
    "PhoneCode": "1",
    "RestrictedExport": "1",
    "NationalityAra": "امريكيه",
    "NationalityEnu": "AMERICAN",
    "DescriptionArabic": "امريكا",
    "DescriptionEnglish": "USA",
    "Description": "امريكا",
    "ActiveInd": "Active",
    "changedDate": "2020-05-27T08:42:19.526Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "644",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سويدية",
    "NationalityEnu": "SWEDISH",
    "DescriptionArabic": "السويد",
    "DescriptionEnglish": "Sweden",
    "Description": "السويد",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "762",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "باباء",
    "NationalityEnu": "باباء",
    "DescriptionArabic": "باباء",
    "DescriptionEnglish": "باباء",
    "Description": "باباء",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "846",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سانت لويسا",
    "NationalityEnu": "SAINT LUCIA",
    "DescriptionArabic": "سانت لوسيا",
    "DescriptionEnglish": "Saint Lucia",
    "Description": "سانت لوسيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "532",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ملاوية",
    "NationalityEnu": "MALAWIAN",
    "DescriptionArabic": "ملاوي",
    "DescriptionEnglish": "Malawi",
    "Description": "ملاوي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "715",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "روبية باكستانية",
    "CurrencyValue": 320,
    "LastCurrencyUpdate": "2019-03-27T13:24:31.522Z",
    "RestrictedExport": "1",
    "NationalityAra": "باكستانية",
    "NationalityEnu": "PAKISTANI",
    "DescriptionArabic": "باكستان",
    "DescriptionEnglish": "Pakistan",
    "Description": "باكستان",
    "ActiveInd": "Active",
    "changedDate": "2020-02-18T12:29:35.833Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "853",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فيجيه",
    "NationalityEnu": "FIJIAN",
    "DescriptionArabic": "جزر فيجي",
    "DescriptionEnglish": "Fiji Island",
    "Description": "جزر فيجي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "733",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "نيبالية",
    "NationalityEnu": "NEPALESE",
    "DescriptionArabic": "نيبال",
    "DescriptionEnglish": "Nepal",
    "Description": "نيبال",
    "ActiveInd": "Active",
    "changedDate": "2018-12-17T11:03:39.100Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "665",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:19:44.308Z",
    "RestrictedExport": "1",
    "NationalityAra": "يونانية",
    "NationalityEnu": "GREEK",
    "DescriptionArabic": "اليونان",
    "DescriptionEnglish": "Greece",
    "Description": "اليونان",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:19:44.308Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "642",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "45",
    "RestrictedExport": "1",
    "NationalityAra": "دنماركية",
    "NationalityEnu": "DANISH",
    "DescriptionArabic": "الدنمارك",
    "DescriptionEnglish": "Denmark",
    "Description": "الدنمارك",
    "ActiveInd": "Active",
    "changedDate": "2018-11-28T08:52:27.275Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "511",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "بر أثيوبي",
    "CurrencyValue": 65,
    "LastCurrencyUpdate": "2019-03-27T13:46:21.373Z",
    "RestrictedExport": "1",
    "NationalityAra": "اثيوبية",
    "NationalityEnu": "ETHIOPIAN",
    "DescriptionArabic": "اثيوبيا",
    "DescriptionEnglish": "Ethiopia",
    "Description": "اثيوبيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:46:21.373Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "774",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "هبريديز",
    "NationalityEnu": "HEBRIDES",
    "DescriptionArabic": "هبريديز",
    "DescriptionEnglish": "Hebrides",
    "Description": "هبريديز",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "502",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تشادية",
    "NationalityEnu": "CHADI",
    "DescriptionArabic": "تشاد",
    "DescriptionEnglish": "Chad",
    "Description": "تشاد",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "645",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "كرونا نرويجية",
    "CurrencyValue": 20,
    "LastCurrencyUpdate": "2019-03-27T13:46:02.719Z",
    "RestrictedExport": "1",
    "NationalityAra": "نرويجية",
    "NationalityEnu": "NORWEGIAN",
    "DescriptionArabic": "النرويج",
    "DescriptionEnglish": "Norway",
    "Description": "النرويج",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:46:02.719Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "653",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ترفيزستانيه",
    "NationalityEnu": "ترفيزستانيه",
    "DescriptionArabic": "ترفيزستان",
    "DescriptionEnglish": "ترفيزستان",
    "Description": "ترفيزستان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "842",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سونت سيرات",
    "NationalityEnu": "سونت سيرات",
    "DescriptionArabic": "سونت سيرات",
    "DescriptionEnglish": "سونت سيرات",
    "Description": "سونت سيرات",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "342",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "درهم مغربي",
    "CurrencyValue": 25,
    "LastCurrencyUpdate": "2019-03-27T13:37:29.928Z",
    "PhoneCode": "212",
    "RestrictedExport": "1",
    "NationalityAra": "مغربية",
    "NationalityEnu": "MOROCCAN",
    "DescriptionArabic": "المغرب",
    "DescriptionEnglish": "Morocco",
    "Description": "المغرب",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:37:29.928Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "885",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "باراغواي",
    "NationalityEnu": "PARAGUAYAN",
    "DescriptionArabic": "باراغواي",
    "DescriptionEnglish": "Baraguay",
    "Description": "باراغواي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "513",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ساحل العاج",
    "NationalityEnu": "IVORIAN",
    "DescriptionArabic": "ساحل العاج",
    "DescriptionEnglish": "Ivory Coast",
    "Description": "ساحل العاج",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "724",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كوريا الشمالية",
    "NationalityEnu": "KOREAN",
    "DescriptionArabic": "كوريا الشمالية",
    "DescriptionEnglish": "North Korea",
    "Description": "كوريا الشمالية",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "728",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كمبودية",
    "NationalityEnu": "CAMBODIAN",
    "DescriptionArabic": "كمبوديا",
    "DescriptionEnglish": "Cambodia",
    "Description": "كمبوديا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "996",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مدغشقر",
    "NationalityEnu": "MADAGASCAR",
    "DescriptionArabic": "مدغشقر",
    "DescriptionEnglish": "Rep. of  Madagascar",
    "Description": "مدغشقر",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "827",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "الدومينكانيه",
    "NationalityEnu": "DOMINICAN",
    "DescriptionArabic": "الدومينكان",
    "DescriptionEnglish": "Dominican",
    "Description": "الدومينكان",
    "ActiveInd": "Active",
    "changedDate": "2018-12-12T08:33:35.962Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "888",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غايانا الفرنسيه",
    "NationalityEnu": "GUIANIAN",
    "DescriptionArabic": "غايانا الفرنسيه",
    "DescriptionEnglish": "French Guiana",
    "Description": "غايانا الفرنسيه",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "655",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سوفيتية",
    "NationalityEnu": "SOVIET",
    "DescriptionArabic": "الاتحاد السوفيتي",
    "DescriptionEnglish": "Soviet",
    "Description": "الاتحاد السوفيتي",
    "ActiveInd": "Active",
    "changedDate": "2021-03-17T19:33:47.114Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "893",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بروني",
    "NationalityEnu": "BRUNEI",
    "DescriptionArabic": "بروني",
    "DescriptionEnglish": "Brunei",
    "Description": "بروني",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "832",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جمايكا",
    "NationalityEnu": "JAMAICAN",
    "DescriptionArabic": "جمايكا",
    "DescriptionEnglish": "Jamaica",
    "Description": "جمايكا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "702",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غينيا الجديده",
    "NationalityEnu": "GUINEAN",
    "DescriptionArabic": "غينيا الجديده",
    "DescriptionEnglish": "New Guinea",
    "Description": "غينيا الجديده",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "722",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تايوانيه",
    "NationalityEnu": "TAIWANESE",
    "DescriptionArabic": "تايوان",
    "DescriptionEnglish": "Taiwan",
    "Description": "تايوان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "666",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "صربيه",
    "NationalityEnu": "SERBIA",
    "DescriptionArabic": "صربيا",
    "DescriptionEnglish": "SERBIA",
    "Description": "صربيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "828",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سلفادوريه",
    "NationalityEnu": "SALVADOR",
    "DescriptionArabic": "السلفادور",
    "DescriptionEnglish": "Salvador",
    "Description": "السلفادور",
    "ActiveInd": "Active",
    "changedDate": "2018-12-12T13:41:37.833Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "527",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بوتسوانية",
    "NationalityEnu": "BOTSWANAN",
    "DescriptionArabic": "بوتسوانا",
    "DescriptionEnglish": "Botswana",
    "Description": "بوتسوانا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "734",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ين ياباني",
    "CurrencyValue": 260,
    "LastCurrencyUpdate": "2019-03-27T13:39:55.170Z",
    "RestrictedExport": "1",
    "NationalityAra": "يابانية",
    "NationalityEnu": "JAPANESE",
    "DescriptionArabic": "اليابان",
    "DescriptionEnglish": "Japan",
    "Description": "اليابان",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:39:55.170Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "771",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "نورو",
    "NationalityEnu": "نورو",
    "DescriptionArabic": "نورو",
    "DescriptionEnglish": "نورو",
    "Description": "نورو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "908",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "رواندي",
    "NationalityEnu": "RWANDA",
    "DescriptionArabic": "جمهورية رواندا",
    "DescriptionEnglish": "Republic of Rwanda",
    "Description": "جمهورية رواندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "721",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يوان صيني",
    "CurrencyValue": 20,
    "LastCurrencyUpdate": "2019-03-27T13:34:07.210Z",
    "RestrictedExport": "1",
    "NationalityAra": "الصين الشعبية",
    "NationalityEnu": "CHINESE",
    "DescriptionArabic": "الصين الشعبية",
    "DescriptionEnglish": "China",
    "Description": "الصين الشعبية",
    "ActiveInd": "Active",
    "changedDate": "2020-05-28T12:07:39.165Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "826",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كوستاريكيه",
    "NationalityEnu": "COSTARICAN",
    "DescriptionArabic": "كوستاريكا",
    "DescriptionEnglish": "Costarica",
    "Description": "كوستاريكا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "343",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "222",
    "RestrictedExport": "1",
    "NationalityAra": "موريتانية",
    "NationalityEnu": "MAURITANIAN",
    "DescriptionArabic": "موريتانيا",
    "DescriptionEnglish": "Mauritania",
    "Description": "موريتانيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "990",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سلوفيني",
    "NationalityEnu": "SLOVENIA",
    "DescriptionArabic": "سلوفينيا",
    "DescriptionEnglish": "slovenia",
    "Description": "سلوفينيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "680",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تشكوسلوفاكية",
    "NationalityEnu": "CZECHOSLOVAKIAN",
    "DescriptionArabic": "تشيكوسلوفاكيا",
    "DescriptionEnglish": "Czechoslovakia",
    "Description": "تشيكوسلوفاكيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "737",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مالديفية",
    "NationalityEnu": "MALDIVES",
    "DescriptionArabic": "مالديف",
    "DescriptionEnglish": "Maldives",
    "Description": "مالديف",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "731",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فيتنامية",
    "NationalityEnu": "VIETNAMESE",
    "DescriptionArabic": "فيتنام",
    "DescriptionEnglish": "Vietnam",
    "Description": "فيتنام",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "316",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال عماني",
    "CurrencyValue": 1,
    "LastCurrencyUpdate": "2019-03-27T13:43:06.406Z",
    "PhoneCode": "968",
    "RestrictedExport": "1",
    "NationalityAra": "عمانية",
    "NationalityEnu": "OMANI",
    "DescriptionArabic": "سلطنة عمان",
    "DescriptionEnglish": "Oman",
    "Description": "سلطنة عمان",
    "ActiveInd": "Active",
    "changedDate": "2021-06-15T09:26:25.965Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "825",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "باربيدوسيه",
    "NationalityEnu": "BARBADOS",
    "DescriptionArabic": "باربيدوس",
    "DescriptionEnglish": "Barbados",
    "Description": "باربيدوس",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "831",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "هندوراسيه",
    "NationalityEnu": "HONDURASIA",
    "DescriptionArabic": "هندوراس",
    "DescriptionEnglish": "Honduras",
    "Description": "هندوراس",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "514",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "زامبيا",
    "NationalityEnu": "ZAMBIAN",
    "DescriptionArabic": "زامبيا",
    "DescriptionEnglish": "Zambia",
    "Description": "زامبيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "312",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دينار كويتي",
    "CurrencyValue": 0.7,
    "LastCurrencyUpdate": "2019-03-27T13:41:11.961Z",
    "PhoneCode": "965",
    "RestrictedExport": "1",
    "NationalityAra": "كويتية",
    "NationalityEnu": "KUWAIT",
    "DescriptionArabic": "الكويت",
    "DescriptionEnglish": "Kuwait",
    "Description": "الكويت",
    "ActiveInd": "Active",
    "changedDate": "2020-11-25T08:44:44.266Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "670",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "يوغسلافية",
    "NationalityEnu": "YUGOSLAVIAN",
    "DescriptionArabic": "يوغسلافيا",
    "DescriptionEnglish": "Yugoslavia",
    "Description": "يوغسلافيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "636",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "378",
    "RestrictedExport": "1",
    "NationalityAra": "سان ريمو",
    "NationalityEnu": "SAN MARINO",
    "DescriptionArabic": "سان مارينو",
    "DescriptionEnglish": "San Marino",
    "Description": "سان مارينو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "523",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مالاغاسي",
    "NationalityEnu": "MALAGASY",
    "DescriptionArabic": "مالاغاسي",
    "DescriptionEnglish": "Malagasy",
    "Description": "مالاغاسي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "542",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر ساوتومي",
    "NationalityEnu": "SAOTOMEAN",
    "DescriptionArabic": "جزر ساوتومي",
    "DescriptionEnglish": "Sao Tome and Pricipe",
    "Description": "جزر ساوتومي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "535",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر القمر",
    "NationalityEnu": "COMORAN",
    "DescriptionArabic": "جزر القمر",
    "DescriptionEnglish": "Comoro Islands",
    "Description": "جزر القمر",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "730",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تيلندية",
    "NationalityEnu": "THAI",
    "DescriptionArabic": "تايلند",
    "DescriptionEnglish": "Thailand",
    "Description": "تايلند",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "310",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال سعودي",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:35:46.312Z",
    "PhoneCode": "966",
    "RestrictedExport": "1",
    "NationalityAra": "سعودي",
    "NationalityEnu": "SAUDIAN",
    "DescriptionArabic": "السعودية",
    "DescriptionEnglish": "Saudia Arabia",
    "Description": "السعودية",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:33.954Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "883",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بوليفيه",
    "NationalityEnu": "BOLIVIAN",
    "DescriptionArabic": "بوليفيا",
    "DescriptionEnglish": "Bolivia",
    "Description": "بوليفيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "321",
    "CountryGroup": "Non_Local",
    "Restricted": true,
    "CurrencyName": "ليرة سورية",
    "CurrencyValue": 1200,
    "LastCurrencyUpdate": "2019-03-27T13:36:41.711Z",
    "PhoneCode": "963",
    "RestrictedExport": "0",
    "NationalityAra": "سورية",
    "NationalityEnu": "SYRIAN",
    "DescriptionArabic": "سوريا",
    "DescriptionEnglish": "Syria",
    "Description": "سوريا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:36:41.711Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "516",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سنغالية",
    "NationalityEnu": "SENEGALESE",
    "DescriptionArabic": "السنغال",
    "DescriptionEnglish": "Sengal",
    "Description": "السنغال",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "778",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ج توكلو",
    "NationalityEnu": "ج توكلو",
    "DescriptionArabic": "ج توكلو",
    "DescriptionEnglish": "ج توكلو",
    "Description": "ج توكلو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "848",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تركس وكايكس",
    "NationalityEnu": "TURKS AND CAICOS",
    "DescriptionArabic": "تركس وكايكس",
    "DescriptionEnglish": "Turks and Caicos",
    "Description": "تركس وكايكس",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "650",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:30:11.407Z",
    "PhoneCode": "49",
    "RestrictedExport": "1",
    "NationalityAra": "المانية",
    "NationalityEnu": "GERMAN",
    "DescriptionArabic": "المانيا",
    "DescriptionEnglish": "Germany",
    "Description": "المانيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:30:11.407Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "810",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار كندي",
    "CurrencyValue": 3.5,
    "LastCurrencyUpdate": "2019-03-27T13:27:09.769Z",
    "RestrictedExport": "1",
    "NationalityAra": "كنديه",
    "NationalityEnu": "CANADIAN",
    "DescriptionArabic": "كندا",
    "DescriptionEnglish": "Canada",
    "Description": "كندا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:27:09.769Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "314",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال قطري",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:36:52.226Z",
    "PhoneCode": "974",
    "RestrictedExport": "1",
    "NationalityAra": "قطرية",
    "NationalityEnu": "QATARI",
    "DescriptionArabic": "قطر",
    "DescriptionEnglish": "Qatar",
    "Description": "قطر",
    "ActiveInd": "Active",
    "changedDate": "2020-09-20T10:45:13.613Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "651",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بلاروسيا",
    "NationalityEnu": "BELARUS",
    "DescriptionArabic": "روسيا البيضاء",
    "DescriptionEnglish": "BELARUS",
    "Description": "روسيا البيضاء",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "880",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بيرو",
    "NationalityEnu": "PERUSAL",
    "DescriptionArabic": "بيرو",
    "DescriptionEnglish": "Peru",
    "Description": "بيرو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "667",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ليتوانية",
    "NationalityEnu": "LITHUANIAN",
    "DescriptionArabic": "ليتوانيا",
    "DescriptionEnglish": "Lithuania",
    "Description": "ليتوانيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "525",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فلبينية",
    "NationalityEnu": "PHILIPPINO",
    "DescriptionArabic": "الفلبين",
    "DescriptionEnglish": "Philippines",
    "Description": "الفلبين",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "884",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "اوروغواي",
    "NationalityEnu": "URUGUAYAN",
    "DescriptionArabic": "اوروغواي",
    "DescriptionEnglish": "Uruguay",
    "Description": "اوروغواي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "350",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "جنيه سوداني",
    "CurrencyValue": 110,
    "LastCurrencyUpdate": "2019-03-27T13:36:19.881Z",
    "PhoneCode": "249",
    "RestrictedExport": "1",
    "NationalityAra": "سودانية",
    "NationalityEnu": "SUDANESE",
    "DescriptionArabic": "السودان",
    "DescriptionEnglish": "Sudan",
    "Description": "السودان",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:36:19.881Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "524",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فلتا العليا",
    "NationalityEnu": "BURKINABE",
    "DescriptionArabic": "فلتا العليا",
    "DescriptionEnglish": "Upper Volta",
    "Description": "فلتا العليا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "001",
    "CountryGroup": "Local",
    "Restricted": false,
    "CurrencyName": "دينار اردني",
    "PhoneCode": "962",
    "RestrictedExport": "1",
    "CurrencyNameEnu": "JOD",
    "NationalityAra": "اردني",
    "NationalityEnu": "JORDANIAN",
    "DescriptionArabic": "الاردن",
    "DescriptionEnglish": "JORDAN",
    "Description": "الاردن",
    "ActiveInd": "Active",
    "changedDate": "2022-03-21T09:23:20.749Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "763",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جوسولومون",
    "NationalityEnu": "SOLOMON ISLAND",
    "DescriptionArabic": "جزر سولومون",
    "DescriptionEnglish": "Solomon Island",
    "Description": "جزر سولومون",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "503",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مالية",
    "NationalityEnu": "MALIAN",
    "DescriptionArabic": "مالي",
    "DescriptionEnglish": "Mali",
    "Description": "مالي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "887",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فولكلاند",
    "NationalityEnu": "FAULKLAND",
    "DescriptionArabic": "فولكلاند",
    "DescriptionEnglish": "Faulkland",
    "Description": "فولكلاند",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "719",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "رينجيت ماليزي",
    "CurrencyValue": 10,
    "LastCurrencyUpdate": "2019-03-27T13:40:55.490Z",
    "RestrictedExport": "1",
    "NationalityAra": "ماليزية",
    "NationalityEnu": "MALAYSIAN",
    "DescriptionArabic": "ماليزيا",
    "DescriptionEnglish": "Malaysia",
    "Description": "ماليزيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:40:55.490Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "352",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ارترية",
    "NationalityEnu": "ARETIRIAN",
    "DescriptionArabic": "ارتريا",
    "DescriptionEnglish": "Aretiria",
    "Description": "ارتريا",
    "ActiveInd": "Active",
    "changedDate": "2021-03-16T08:44:36.156Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "648",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مالطية",
    "NationalityEnu": "MALTESE",
    "DescriptionArabic": "مالطا",
    "DescriptionEnglish": "Malta",
    "Description": "مالطا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "112",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "220",
    "RestrictedExport": "1",
    "NationalityAra": "جامبي",
    "NationalityEnu": "GAMBIAN",
    "DescriptionArabic": "جامبيا",
    "DescriptionEnglish": "GAMBIA",
    "Description": "جامبيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "898",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سنتالوسيا",
    "NationalityEnu": "SAINTLUCIA",
    "DescriptionArabic": "سنتالوسيا",
    "DescriptionEnglish": "Saintlucia",
    "Description": "سنتالوسيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "699",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كرواتي",
    "NationalityEnu": "CORATIAN",
    "DescriptionArabic": "كرواتيا",
    "DescriptionEnglish": "Croatia",
    "Description": "كرواتيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "773",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غينيه",
    "NationalityEnu": "GUINEAN",
    "DescriptionArabic": "غينيه",
    "DescriptionEnglish": "Guinea",
    "Description": "غينيه",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "890",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بوسنيه",
    "NationalityEnu": "BOSNIAN HERZOGEVINIAN",
    "DescriptionArabic": "البوسنه والهرسك",
    "DescriptionEnglish": "Bosnia and Herzegovina",
    "Description": "البوسنه والهرسك",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "506",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "يوغندية",
    "NationalityEnu": "UGANDANN",
    "DescriptionArabic": "يوغندا",
    "DescriptionEnglish": "Uganda",
    "Description": "يوغندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "835",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "البهاما",
    "NationalityEnu": "BAHAMAS",
    "DescriptionArabic": "البهاما",
    "DescriptionEnglish": "Bahamas",
    "Description": "البهاما",
    "ActiveInd": "Active",
    "changedDate": "2021-12-27T16:09:44.268Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "717",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال إيراني",
    "CurrencyValue": 95000,
    "LastCurrencyUpdate": "2019-03-27T13:39:41.240Z",
    "RestrictedExport": "1",
    "NationalityAra": "ايرانية",
    "NationalityEnu": "IRANIAN",
    "DescriptionArabic": "ايران",
    "DescriptionEnglish": "Iran",
    "Description": "ايران",
    "ActiveInd": "Active",
    "changedDate": "2021-05-30T07:07:10.801Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "992",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "لينششتانيه",
    "NationalityEnu": "LEICHTENSTEINIAN",
    "DescriptionArabic": "لينششتاين",
    "DescriptionEnglish": "leichtenstein",
    "Description": "لينششتاين",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "889",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "اوكراني",
    "NationalityEnu": "UKRAINIAN",
    "DescriptionArabic": "اوكرانيا",
    "DescriptionEnglish": "Ukraine",
    "Description": "اوكرانيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "537",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ناميبية",
    "NationalityEnu": "NAMIBIAN",
    "DescriptionArabic": "ناميبيا",
    "DescriptionEnglish": "Namibia",
    "Description": "ناميبيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "317",
    "CountryGroup": "Non_Local",
    "Restricted": true,
    "CurrencyName": "ريال يمني",
    "CurrencyValue": 600,
    "LastCurrencyUpdate": "2018-09-18T19:00:16.142Z",
    "PhoneCode": "967",
    "RestrictedExport": "0",
    "NationalityAra": "يمنية",
    "NationalityEnu": "YEMENI",
    "DescriptionArabic": "اليمن",
    "DescriptionEnglish": "Yemen",
    "Description": "اليمن",
    "ActiveInd": "Active",
    "changedDate": "2018-09-18T19:00:16.142Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "881",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كولومبيه",
    "NationalityEnu": "COLOMBIAN",
    "DescriptionArabic": "كولومبيا",
    "DescriptionEnglish": "Colombia",
    "Description": "كولومبيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "663",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مقدونيه",
    "NationalityEnu": "MAKDONIAN",
    "DescriptionArabic": "مقدونيا",
    "DescriptionEnglish": "Makdonia",
    "Description": "مقدونيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "739",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "هونغ كونغ",
    "NationalityEnu": "HONG KONG",
    "DescriptionArabic": "هونغ كونغ",
    "DescriptionEnglish": "Hong Kong",
    "Description": "هونغ كونغ",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "768",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ج جيللبرت",
    "NationalityEnu": "ج جيللبرت",
    "DescriptionArabic": "ج جيللبرت",
    "DescriptionEnglish": "ج جيللبرت",
    "Description": "ج جيللبرت",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "991",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "قرغيزيه",
    "NationalityEnu": "KYRGYZIAN",
    "DescriptionArabic": "جمهورية قرغيز",
    "DescriptionEnglish": "Kyrgyz Republic",
    "Description": "جمهورية قرغيز",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "994",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كيرجستانيه",
    "NationalityEnu": "KYRGYZSTAN",
    "DescriptionArabic": "كيرجستان",
    "DescriptionEnglish": "kyrgyzstan",
    "Description": "كيرجستان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "340",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دينار تونسي",
    "CurrencyValue": 7,
    "LastCurrencyUpdate": "2019-03-27T13:34:53.324Z",
    "PhoneCode": "216",
    "RestrictedExport": "1",
    "NationalityAra": "تونسية",
    "NationalityEnu": "TUNISIAN",
    "DescriptionArabic": "تونس",
    "DescriptionEnglish": "Tunisia",
    "Description": "تونس",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:34:53.324Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "510",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "زائيرية",
    "NationalityEnu": "ZAIRIAN",
    "DescriptionArabic": "زائير",
    "DescriptionEnglish": "Zaire",
    "Description": "زائير",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "776",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ج الباسفيك",
    "NationalityEnu": "ج الباسفيك",
    "DescriptionArabic": "ج الباسفيك",
    "DescriptionEnglish": "ج الباسفيك",
    "Description": "ج الباسفيك",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "531",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تايلندي",
    "NationalityEnu": "TAILAND",
    "DescriptionArabic": "تايلند",
    "DescriptionEnglish": "TAILAND",
    "Description": "تايلند",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "876",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال برازيلي",
    "CurrencyValue": 4,
    "PhoneCode": "962",
    "RestrictedExport": "1",
    "NationalityAra": "ج ويل",
    "NationalityEnu": "ج ويل",
    "DescriptionArabic": "الالللل",
    "DescriptionEnglish": "test",
    "Description": "الالللل",
    "ActiveInd": "Active",
    "changedDate": "2021-08-30T07:29:23.137Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "850",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ريال برازيلي",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:29:54.743Z",
    "RestrictedExport": "1",
    "NationalityAra": "برازيليه",
    "NationalityEnu": "BRAZILIAN",
    "DescriptionArabic": "البرازيل",
    "DescriptionEnglish": "Brazil",
    "Description": "البرازيل",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:29:54.743Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "683",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "شيكيه",
    "NationalityEnu": "CZECH",
    "DescriptionArabic": "تشيك",
    "DescriptionEnglish": "Czech",
    "Description": "تشيك",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "685",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بولونية",
    "NationalityEnu": "POLISH",
    "DescriptionArabic": "بولونيا",
    "DescriptionEnglish": "Poland",
    "Description": "بولونيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "860",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فنزويليه",
    "NationalityEnu": "VENEZUELIAN",
    "DescriptionArabic": "فنزويلا",
    "DescriptionEnglish": "Venezuela",
    "Description": "فنزويلا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "740",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مكاو",
    "NationalityEnu": "MACAU",
    "DescriptionArabic": "مكاو",
    "DescriptionEnglish": "Macau",
    "Description": "مكاو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "512",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غانا",
    "NationalityEnu": "GHANAIAN",
    "DescriptionArabic": "غانا",
    "DescriptionEnglish": "Ghana",
    "Description": "غانا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "843",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "انتينيل",
    "NationalityEnu": "انتينيل",
    "DescriptionArabic": "انتينيل",
    "DescriptionEnglish": "انتينيل",
    "Description": "انتينيل",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "643",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "فرنك سويسري",
    "CurrencyValue": 3,
    "LastCurrencyUpdate": "2019-03-27T13:34:17.187Z",
    "PhoneCode": "41",
    "RestrictedExport": "1",
    "NationalityAra": "سويسرية",
    "NationalityEnu": "SWISS",
    "DescriptionArabic": "سويسرا",
    "DescriptionEnglish": "SwitzerLand",
    "Description": "سويسرا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:34:17.187Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "820",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:43:16.604Z",
    "RestrictedExport": "1",
    "NationalityAra": "مكسيكيه",
    "NationalityEnu": "MEXICAN",
    "DescriptionArabic": "المكسيك",
    "DescriptionEnglish": "Mexico",
    "Description": "المكسيك",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:43:16.604Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "662",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:44:10.147Z",
    "PhoneCode": "006",
    "RestrictedExport": "1",
    "NationalityAra": "روسيه",
    "NationalityEnu": "RUSSIAN",
    "DescriptionArabic": "روسيا",
    "DescriptionEnglish": "Russia",
    "Description": "روسيا",
    "ActiveInd": "Active",
    "changedDate": "2021-03-08T12:20:17.710Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "899",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بنينيه",
    "NationalityEnu": "BENIN",
    "DescriptionArabic": "بنين",
    "DescriptionEnglish": "Benin",
    "Description": "بنين",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "701",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "روبية هندية",
    "CurrencyValue": 160,
    "LastCurrencyUpdate": "2019-03-27T13:44:25.029Z",
    "RestrictedExport": "1",
    "NationalityAra": "هندية",
    "NationalityEnu": "INDIAN",
    "DescriptionArabic": "الهند",
    "DescriptionEnglish": "India",
    "Description": "الهند",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:44:25.029Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "718",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "روبية أندونيسية",
    "CurrencyValue": 33000,
    "LastCurrencyUpdate": "2019-03-27T13:35:29.299Z",
    "RestrictedExport": "1",
    "NationalityAra": "اندونيسية",
    "NationalityEnu": "ANDONISIAN",
    "DescriptionArabic": "اندونيسا",
    "DescriptionEnglish": "Indonesia",
    "Description": "اندونيسا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:35:29.299Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "723",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سيرلنكية",
    "NationalityEnu": "SRILANKAN",
    "DescriptionArabic": "سيرلانكا",
    "DescriptionEnglish": "Sri Lanka",
    "Description": "سيرلانكا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "630",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:37:56.656Z",
    "PhoneCode": "39",
    "RestrictedExport": "1",
    "NationalityAra": "ايطالية",
    "NationalityEnu": "ITALIAN",
    "DescriptionArabic": "ايطاليا",
    "DescriptionEnglish": "Italy",
    "Description": "ايطاليا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:37:56.656Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "320",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:23:05.444Z",
    "PhoneCode": "964",
    "RestrictedExport": "1",
    "NationalityAra": "عراقية",
    "NationalityEnu": "IRAQI",
    "DescriptionArabic": "العراق",
    "DescriptionEnglish": "Iraq",
    "Description": "العراق",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:23:05.444Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "833",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سوريناميه",
    "NationalityEnu": "SURINAM",
    "DescriptionArabic": "سورينام",
    "DescriptionEnglish": "Surinam",
    "Description": "سورينام",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "741",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تيمور",
    "NationalityEnu": "تيمور",
    "DescriptionArabic": "تيمور",
    "DescriptionEnglish": "تيمور",
    "Description": "تيمور",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "815",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غرينلندا",
    "NationalityEnu": "GREENLANDAR",
    "DescriptionArabic": "غرينلندا",
    "DescriptionEnglish": "Greenland",
    "Description": "غرينلندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "637",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "موناكو",
    "NationalityEnu": "MONACO",
    "DescriptionArabic": "موناكو",
    "DescriptionEnglish": "Monaco",
    "Description": "موناكو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "313",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "درهم إماراتي",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:36:31.817Z",
    "PhoneCode": "971",
    "RestrictedExport": "1",
    "NationalityAra": "اماراتية",
    "NationalityEnu": "EMIRATE",
    "DescriptionArabic": "الامارات",
    "DescriptionEnglish": "UAE",
    "Description": "الامارات",
    "ActiveInd": "Active",
    "changedDate": "2022-03-08T11:09:18.966Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "331",
    "CountryGroup": "Non_Local",
    "Restricted": true,
    "CurrencyName": "دينار ليبي",
    "CurrencyValue": 5,
    "LastCurrencyUpdate": "2018-09-18T19:02:41.667Z",
    "PhoneCode": "218",
    "RestrictedExport": "0",
    "NationalityAra": "ليبية",
    "NationalityEnu": "LIBYAN",
    "DescriptionArabic": "ليبيا",
    "DescriptionEnglish": "Libya",
    "Description": "ليبيا",
    "ActiveInd": "Active",
    "changedDate": "2020-07-02T12:01:37.385Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "656",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "مانات",
    "CurrencyValue": 4,
    "LastCurrencyUpdate": "2019-03-27T13:29:29.840Z",
    "RestrictedExport": "1",
    "NationalityAra": "اذربيجانيه",
    "NationalityEnu": "AZERBAIJANI",
    "DescriptionArabic": "اذربيجان",
    "DescriptionEnglish": "Azerbaijan",
    "Description": "اذربيجان",
    "ActiveInd": "Active",
    "changedDate": "2020-06-09T07:37:48.502Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "765",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جفيكيه",
    "NationalityEnu": "جفيكيه",
    "DescriptionArabic": "جفيكي",
    "DescriptionEnglish": "جفيكي",
    "Description": "جفيكي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "896",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "برتغالية",
    "NationalityEnu": "PORTUGESE",
    "DescriptionArabic": "البرتغال",
    "DescriptionEnglish": "Portugal",
    "Description": "البرتغال",
    "ActiveInd": "Active",
    "changedDate": "2021-06-27T13:02:47.921Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "891",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:39:25.930Z",
    "RestrictedExport": "1",
    "NationalityAra": "اوزبكية",
    "NationalityEnu": "UZBEKISTAN",
    "DescriptionArabic": "اوزباكستان",
    "DescriptionEnglish": "Uzbekistan",
    "Description": "اوزباكستان",
    "ActiveInd": "Active",
    "changedDate": "2020-06-09T06:41:48.363Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "732",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "منغولية",
    "NationalityEnu": "MANGOLLIAN",
    "DescriptionArabic": "منغوليا",
    "DescriptionEnglish": "Mangolla",
    "Description": "منغوليا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "906",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "راند جنوب أفريقي",
    "CurrencyValue": 35,
    "LastCurrencyUpdate": "2019-03-27T13:33:32.990Z",
    "RestrictedExport": "1",
    "NationalityAra": "جنوب افريقيه",
    "NationalityEnu": "SOUTH AFRICA",
    "DescriptionArabic": "جنوب افريقيا",
    "DescriptionEnglish": "SOUTH AFRICA",
    "Description": "جنوب افريقيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:33:32.990Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "625",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:29:14.937Z",
    "PhoneCode": "33",
    "RestrictedExport": "1",
    "NationalityAra": "فرنسية",
    "NationalityEnu": "FRENCH",
    "DescriptionArabic": "فرنسا",
    "DescriptionEnglish": "France",
    "Description": "فرنسا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:29:14.937Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "529",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "افريقيا الوسطى",
    "NationalityEnu": "CENTRAI AFRICA",
    "DescriptionArabic": "افريقيا الوسطى",
    "DescriptionEnglish": "Central Africa",
    "Description": "افريقيا الوسطى",
    "ActiveInd": "Active",
    "changedDate": "2021-03-15T10:52:43.385Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "851",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غيانا",
    "NationalityEnu": "GUYANA",
    "DescriptionArabic": "غيانا",
    "DescriptionEnglish": "guyana",
    "Description": "غيانا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "509",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "زيمبابوية",
    "NationalityEnu": "ZIMBABWE",
    "DescriptionArabic": "زيمبابويه",
    "DescriptionEnglish": "Zimbabwe",
    "Description": "زيمبابويه",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "330",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "جنيه مصري",
    "CurrencyValue": 40,
    "LastCurrencyUpdate": "2019-03-27T13:40:19.490Z",
    "PhoneCode": "962",
    "RestrictedExport": "1",
    "NationalityAra": "مصرية",
    "NationalityEnu": "EGYPTIaaaN",
    "DescriptionArabic": "مصر",
    "DescriptionEnglish": "Egypt",
    "Description": "مصر",
    "ActiveInd": "Active",
    "changedDate": "2021-09-29T07:38:12.658Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "767",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بولوليزيه",
    "NationalityEnu": "بولوليزيه",
    "DescriptionArabic": "بولوليزيا",
    "DescriptionEnglish": "بولوليزيا",
    "Description": "بولوليزيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "902",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "شيشانيه",
    "NationalityEnu": "CHECHENIA",
    "DescriptionArabic": "جمهورية الشيشان",
    "DescriptionEnglish": "Chechian",
    "Description": "جمهورية الشيشان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "355",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "211",
    "RestrictedExport": "1",
    "NationalityAra": "جنوب السودان",
    "NationalityEnu": "SOUTH SUDAN",
    "DescriptionArabic": "جنوب السودان",
    "DescriptionEnglish": "South Sudan",
    "Description": "جنوب السودان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "837",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بيليزيه",
    "NationalityEnu": "BELIZEAN",
    "DescriptionArabic": "بيليز",
    "DescriptionEnglish": "BELIZE",
    "Description": "بيليز",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "635",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:42:54.530Z",
    "PhoneCode": "34",
    "RestrictedExport": "1",
    "CurrencyNameEnu": "euro",
    "NationalityAra": "اسبانية",
    "NationalityEnu": "SPANISH",
    "DescriptionArabic": "اسبانيا",
    "DescriptionEnglish": "Spain",
    "Description": "اسبانيا",
    "ActiveInd": "Active",
    "changedDate": "2021-03-14T09:56:10.260Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "886",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غايافا",
    "NationalityEnu": "غايافا",
    "DescriptionArabic": "غايافا",
    "DescriptionEnglish": "غايافا",
    "Description": "غايافا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "003",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "شيكل إسرائيلي",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:37:04.929Z",
    "PhoneCode": "970",
    "RestrictedExport": "1",
    "NationalityAra": "فلسطيني",
    "NationalityEnu": "PALESTINIAN 48",
    "DescriptionArabic": "فلسطين 48",
    "DescriptionEnglish": "Palestine",
    "Description": "فلسطين 48",
    "ActiveInd": "Active",
    "changedDate": "2020-03-24T13:39:50.671Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "000",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "شيكل إسرائيلي",
    "CurrencyValue": 0.126,
    "LastCurrencyUpdate": "2021-09-14T11:28:29.870Z",
    "PhoneCode": "972",
    "RestrictedExport": "1",
    "CurrencyNameEnu": "",
    "NationalityAra": "اسرائيلي",
    "NationalityEnu": "ISRAELI",
    "DescriptionArabic": "اسرائيل",
    "DescriptionEnglish": "Israel",
    "Description": "اسرائيل",
    "ActiveInd": "Active",
    "changedDate": "2021-09-14T11:28:29.870Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "903",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بوسنيه",
    "NationalityEnu": "BOSNIAN",
    "DescriptionArabic": "البوسنه",
    "DescriptionEnglish": "Bosnia",
    "Description": "البوسنه",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "905",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "داغستاني",
    "NationalityEnu": "DAGHESTANI",
    "DescriptionArabic": "داغستان",
    "DescriptionEnglish": "Daghestan",
    "Description": "داغستان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "664",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "لاتفيه",
    "NationalityEnu": "LATVIAN",
    "DescriptionArabic": "لاتفيا",
    "DescriptionEnglish": "Latvia",
    "Description": "لاتفيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "845",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سانت كيتس ونيفس",
    "NationalityEnu": "SAINT KITTS AND NEVIS",
    "DescriptionArabic": "سانت كيتس ونيفس",
    "DescriptionEnglish": "Saint Kitts and Nevis",
    "Description": "سانت كيتس ونيفس",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "526",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "داهومي",
    "NationalityEnu": "DAHOMEY",
    "DescriptionArabic": "داهومي",
    "DescriptionEnglish": "Dahomey",
    "Description": "داهومي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "892",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بوركينافاسو",
    "NationalityEnu": "BURKINA FASO",
    "DescriptionArabic": "بوركينافاسو",
    "DescriptionEnglish": "Burkina Faso",
    "Description": "بوركينافاسو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "822",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "نيكارغويه",
    "NationalityEnu": "NICARAGUA",
    "DescriptionArabic": "نيكارغوا",
    "DescriptionEnglish": "Nicaragua",
    "Description": "نيكارغوا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "501",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "234",
    "RestrictedExport": "1",
    "NationalityAra": "نيجيرية",
    "NationalityEnu": "NIGERIAN",
    "DescriptionArabic": "نيجيريا",
    "DescriptionEnglish": "Nigeria",
    "Description": "نيجيريا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "539",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر رونيو",
    "NationalityEnu": "جزر رونيو",
    "DescriptionArabic": "جزر رونيو",
    "DescriptionEnglish": "جزر رونيو",
    "Description": "جزر رونيو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "769",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غواميه",
    "NationalityEnu": "GUAM",
    "DescriptionArabic": "غوام",
    "DescriptionEnglish": "Guam",
    "Description": "غوام",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "690",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بلغارية",
    "NationalityEnu": "BULGARIAN",
    "DescriptionArabic": "بلغاريا",
    "DescriptionEnglish": "Bulgaria",
    "Description": "بلغاريا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "725",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "وان كوري",
    "CurrencyValue": 2600,
    "LastCurrencyUpdate": "2019-03-27T13:38:35.807Z",
    "RestrictedExport": "1",
    "NationalityAra": "كوريا الجنوبية",
    "NationalityEnu": "SOUTH KOREA",
    "DescriptionArabic": "كوريا الجنوبية",
    "DescriptionEnglish": "South Korea",
    "Description": "كوريا الجنوبية",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:38:35.807Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "522",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "الكمرون",
    "NationalityEnu": "CAMEROONIAN",
    "DescriptionArabic": "الكمرون",
    "DescriptionEnglish": "Cameroon",
    "Description": "الكمرون",
    "ActiveInd": "Active",
    "changedDate": "2018-12-12T13:13:37.802Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "505",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ليبيرية",
    "NationalityEnu": "LIBERIAN",
    "DescriptionArabic": "ليبيرية",
    "DescriptionEnglish": "Liberia",
    "Description": "ليبيرية",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "904",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "قرغيزيه",
    "NationalityEnu": "QARGEEZIAN",
    "DescriptionArabic": "قرغيزيا",
    "DescriptionEnglish": "Qargeezia",
    "Description": "قرغيزيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "341",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دينار جزائري",
    "CurrencyValue": 350,
    "LastCurrencyUpdate": "2021-05-06T11:05:13.532Z",
    "PhoneCode": "213",
    "RestrictedExport": "1",
    "NationalityAra": "جزائرية",
    "NationalityEnu": "ALGERIAN",
    "DescriptionArabic": "الجزائر",
    "DescriptionEnglish": "Algeria",
    "Description": "الجزائر",
    "ActiveInd": "Active",
    "changedDate": "2021-05-06T11:05:13.532Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "726",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "لاوس",
    "NationalityEnu": "LAOTIAN",
    "DescriptionArabic": "لاوس",
    "DescriptionEnglish": "Laos",
    "Description": "لاوس",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "681",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تشيكيه",
    "NationalityEnu": "CZECH",
    "DescriptionArabic": "التشيك",
    "DescriptionEnglish": "Al Czech",
    "Description": "التشيك",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "775",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "نيو",
    "NationalityEnu": "NIUE",
    "DescriptionArabic": "نيو",
    "DescriptionEnglish": "Niue",
    "Description": "نيو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "518",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "نيجيرية",
    "NationalityEnu": "NIGERIAN",
    "DescriptionArabic": "النيجر",
    "DescriptionEnglish": "Niger",
    "Description": "النيجر",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "111",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyValue": 150,
    "LastCurrencyUpdate": "2019-06-02T11:14:56.376Z",
    "PhoneCode": "230",
    "RestrictedExport": "1",
    "NationalityAra": "موريشوسيه",
    "NationalityEnu": "MAURITIAN",
    "DescriptionArabic": "موريشوس",
    "DescriptionEnglish": "Mauritius",
    "Description": "موريشوس",
    "ActiveInd": "Active",
    "changedDate": "2019-06-02T11:14:56.376Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "691",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "هنجارية",
    "NationalityEnu": "HUNGARIAN",
    "DescriptionArabic": "هنجاريا",
    "DescriptionEnglish": "Hungary",
    "Description": "هنجاريا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "735",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سيكيم",
    "NationalityEnu": "سيكيم",
    "DescriptionArabic": "سيكيم",
    "DescriptionEnglish": "سيكيم",
    "Description": "سيكيم",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "761",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ساموا",
    "NationalityEnu": "SAMWA",
    "DescriptionArabic": "ساموا",
    "DescriptionEnglish": "Samwa",
    "Description": "ساموا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "658",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "طاجكستانيه",
    "NationalityEnu": "TAGIK",
    "DescriptionArabic": "طاجكستان",
    "DescriptionEnglish": "Tajikistan",
    "Description": "طاجكستان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "720",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "ليرة تركية",
    "CurrencyValue": 13,
    "LastCurrencyUpdate": "2019-03-27T13:24:45.883Z",
    "RestrictedExport": "1",
    "NationalityAra": "تركية",
    "NationalityEnu": "TURKISH",
    "DescriptionArabic": "تركيا",
    "DescriptionEnglish": "Turkey",
    "Description": "تركيا",
    "ActiveInd": "Active",
    "changedDate": "2021-01-06T11:29:41.381Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "654",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ارمينيه",
    "NationalityEnu": "ARMANIAN",
    "DescriptionArabic": "ارمينيا",
    "DescriptionEnglish": "Armenia",
    "Description": "ارمينيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "764",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جكوك",
    "NationalityEnu": "جكوك",
    "DescriptionArabic": "جكوك",
    "DescriptionEnglish": "جكوك",
    "Description": "جكوك",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "882",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "أكوادور",
    "NationalityEnu": "ECUADORAN",
    "DescriptionArabic": "أكوادور",
    "DescriptionEnglish": "Ecuador",
    "Description": "أكوادور",
    "ActiveInd": "Active",
    "changedDate": "2018-12-17T13:02:43.987Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "849",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سانت مارتن",
    "NationalityEnu": "SINT MAARTEN",
    "DescriptionArabic": "سانت مارتن",
    "DescriptionEnglish": "Sint Maarten",
    "Description": "سانت مارتن",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "641",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:32:06.798Z",
    "PhoneCode": "32",
    "RestrictedExport": "1",
    "NationalityAra": "بلجيكية",
    "NationalityEnu": "BELGIAN",
    "DescriptionArabic": "بلجيكا",
    "DescriptionEnglish": "Belgium",
    "Description": "بلجيكا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:32:06.798Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "507",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تنزانية",
    "NationalityEnu": "TANZANIAN",
    "DescriptionArabic": "تنزانيا",
    "DescriptionEnglish": "Tanzania",
    "Description": "تنزانيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "682",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سلوفاكيه",
    "NationalityEnu": "SLOVAKIAN",
    "DescriptionArabic": "سلوفاكيا",
    "DescriptionEnglish": "Slovakia",
    "Description": "سلوفاكيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "900",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "اسكتلنديه",
    "NationalityEnu": "SCOTISH",
    "DescriptionArabic": "اسكتلندا",
    "DescriptionEnglish": "Scotland",
    "Description": "اسكتلندا",
    "ActiveInd": "Active",
    "changedDate": "2018-12-19T10:39:34.908Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "517",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سيراليون",
    "NationalityEnu": "SEIRRALEONE",
    "DescriptionArabic": "سيراليون",
    "DescriptionEnglish": "Seirraleone",
    "Description": "سيراليون",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "870",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:38:21.368Z",
    "RestrictedExport": "1",
    "NationalityAra": "تشيليه",
    "NationalityEnu": "CHILEAN",
    "DescriptionArabic": "تشيلي",
    "DescriptionEnglish": "Chile",
    "Description": "تشيلي",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:38:21.368Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "844",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بورتوريكيه",
    "NationalityEnu": "PUERTORICAN",
    "DescriptionArabic": "بورتوريكو",
    "DescriptionEnglish": "Puerto Rico",
    "Description": "بورتوريكو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.243Z"
  },
  {
    "ISO_Code": "555",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "1-268",
    "RestrictedExport": "1",
    "NationalityAra": "انتيغوا و باربودا",
    "NationalityEnu": "ANTIGUAN AND BARBUDAN",
    "DescriptionArabic": "انتيغوا و باربودا",
    "DescriptionEnglish": "ANTIGUA AND BARBUDA",
    "Description": "انتيغوا و باربودا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "657",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أمريكي",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:24:12.899Z",
    "RestrictedExport": "1",
    "NationalityAra": "كازخستانيه",
    "NationalityEnu": "KAZAKHISTAN",
    "DescriptionArabic": "كازخستان",
    "DescriptionEnglish": "kazakhistan",
    "Description": "كازخستان",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:24:12.899Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "533",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بولندية",
    "NationalityEnu": "POLISH",
    "DescriptionArabic": "بولندا",
    "DescriptionEnglish": "Poland",
    "Description": "بولندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "836",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بيرميويا",
    "NationalityEnu": "بيرميويا",
    "DescriptionArabic": "بيرميويا",
    "DescriptionEnglish": "بيرميويا",
    "Description": "بيرميويا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "841",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مارتينيد",
    "NationalityEnu": "MARTINIQUE",
    "DescriptionArabic": "مارتينيد",
    "DescriptionEnglish": "Martinique",
    "Description": "مارتينيد",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "520",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "توجو",
    "NationalityEnu": "TOGOLESE",
    "DescriptionArabic": "توجو",
    "DescriptionEnglish": "Togo",
    "Description": "توجو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "631",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "379",
    "RestrictedExport": "1",
    "NationalityAra": "الفاتيكان",
    "NationalityEnu": "VATICAN",
    "DescriptionArabic": "الفاتيكان",
    "DescriptionEnglish": "Vatican City",
    "Description": "الفاتيكان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "649",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "لكسمبرغ",
    "NationalityEnu": "LUXEMBURG",
    "DescriptionArabic": "لكسمبرغ",
    "DescriptionEnglish": "Luxemburg",
    "Description": "لكسمبرغ",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "716",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بنغاليه",
    "NationalityEnu": "BANGLADESHI",
    "DescriptionArabic": "بنغلادش",
    "DescriptionEnglish": "Bangladesh",
    "Description": "بنغلادش",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "536",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "موزمبيقية",
    "NationalityEnu": "MOZAMBICAN",
    "DescriptionArabic": "موزمبيق",
    "DescriptionEnglish": "Mozambigue",
    "Description": "موزمبيق",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "875",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "أرجنتينيه",
    "NationalityEnu": "ARGENTINIAN",
    "DescriptionArabic": "الأرجنتين",
    "DescriptionEnglish": "Argentina",
    "Description": "الأرجنتين",
    "ActiveInd": "Active",
    "changedDate": "2021-03-18T10:59:35.983Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "546",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "شيلينغ كيني",
    "CurrencyValue": 1.5,
    "RestrictedExport": "1",
    "NationalityAra": "لوكسمبورغية",
    "NationalityEnu": "LUXEMBOURG",
    "DescriptionArabic": "لوكسمبورغ",
    "DescriptionEnglish": "Luxembourg",
    "Description": "لوكسمبورغ",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "504",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "شيلينغ كيني",
    "CurrencyValue": 230,
    "LastCurrencyUpdate": "2019-03-27T13:45:48.294Z",
    "RestrictedExport": "1",
    "NationalityAra": "كينية",
    "NationalityEnu": "KENYAN",
    "DescriptionArabic": "كينيا",
    "DescriptionEnglish": "Kenya",
    "Description": "كينيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:45:48.294Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "829",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غواتيماليه",
    "NationalityEnu": "GUATEMALAN",
    "DescriptionArabic": "غواتيمالا",
    "DescriptionEnglish": "Guatemala",
    "Description": "غواتيمالا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "750",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دولار أسترالي",
    "CurrencyValue": 3.5,
    "LastCurrencyUpdate": "2019-03-27T13:40:34.430Z",
    "RestrictedExport": "1",
    "NationalityAra": "استرالية",
    "NationalityEnu": "AUSTRALIAN",
    "DescriptionArabic": "استراليا",
    "DescriptionEnglish": "Australia",
    "Description": "استراليا",
    "ActiveInd": "Active",
    "changedDate": "2021-03-14T09:08:54.187Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "530",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كونجو",
    "NationalityEnu": "CONGO",
    "DescriptionArabic": "كونجو",
    "DescriptionEnglish": "Congo",
    "Description": "كونجو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "534",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "افريقيا الجنوبية",
    "NationalityEnu": "SOUTH AFRICA",
    "DescriptionArabic": "افريقيا الجنوبية",
    "DescriptionEnglish": "South Africa",
    "Description": "افريقيا الجنوبية",
    "ActiveInd": "Active",
    "changedDate": "2018-12-12T09:15:44.133Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "772",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كلدونينيه",
    "NationalityEnu": "كلدونينيه",
    "DescriptionArabic": "كلدونيا",
    "DescriptionEnglish": "كلدونيا",
    "Description": "كلدونيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "640",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:40:10.031Z",
    "PhoneCode": "43",
    "RestrictedExport": "1",
    "NationalityAra": "نمساوية",
    "NationalityEnu": "AUSTRIAN",
    "DescriptionArabic": "النمسا",
    "DescriptionEnglish": "Austria",
    "Description": "النمسا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:40:10.032Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "610",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "جنيه استرليني",
    "CurrencyValue": 2,
    "LastCurrencyUpdate": "2019-03-27T13:42:23.523Z",
    "PhoneCode": "44",
    "RestrictedExport": "1",
    "NationalityAra": "بريطانية",
    "NationalityEnu": "BRITISH",
    "DescriptionArabic": "بريطانيا",
    "DescriptionEnglish": "UNITED KINGDOM",
    "Description": "بريطانيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:42:23.523Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "315",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دينار بحريني",
    "CurrencyValue": 1,
    "LastCurrencyUpdate": "2019-03-27T13:43:58.772Z",
    "PhoneCode": "973",
    "RestrictedExport": "1",
    "NationalityAra": "بحرينية",
    "NationalityEnu": "BAHRAINI",
    "DescriptionArabic": "البحرين",
    "DescriptionEnglish": "Bahrain",
    "Description": "البحرين",
    "ActiveInd": "Active",
    "changedDate": "2020-09-09T10:44:38.040Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "545",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر الرأس الاخضر",
    "NationalityEnu": "LABO CAMARINES NORTE",
    "DescriptionArabic": "جزر الرأس الاخضر",
    "DescriptionEnglish": "Labo Camarines Norte",
    "Description": "جزر الرأس الاخضر",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "727",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بورما",
    "NationalityEnu": "BURMESE",
    "DescriptionArabic": "بورما",
    "DescriptionEnglish": "Burma",
    "Description": "بورما",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "541",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جزر سيشل",
    "NationalityEnu": "SEYCHELLES",
    "DescriptionArabic": "جزر سيشل",
    "DescriptionEnglish": "Seychelles",
    "Description": "جزر سيشل",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "351",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "252",
    "RestrictedExport": "1",
    "NationalityAra": "صومالية",
    "NationalityEnu": "SOMALI",
    "DescriptionArabic": "الصومال",
    "DescriptionEnglish": "Somalia",
    "Description": "الصومال",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "824",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ترينيداد/ توباغو",
    "NationalityEnu": "TRINIDAD TOBAGO",
    "DescriptionArabic": "ترينيداد/ توباغو",
    "DescriptionEnglish": "Trinidad/Tobago",
    "Description": "ترينيداد/ توباغو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "519",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غينية",
    "NationalityEnu": "GUINEAN",
    "DescriptionArabic": "غينيا",
    "DescriptionEnglish": "Guinea",
    "Description": "غينيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "638",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 1.5,
    "PhoneCode": "353",
    "RestrictedExport": "1",
    "NationalityAra": "ايرلندية",
    "NationalityEnu": "IRISH",
    "DescriptionArabic": "ايرلندا",
    "DescriptionEnglish": "Ireland",
    "Description": "ايرلندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "620",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:42:09.963Z",
    "PhoneCode": "31",
    "RestrictedExport": "1",
    "NationalityAra": "هولاندية",
    "NationalityEnu": "DUTCH",
    "DescriptionArabic": "هولندا",
    "DescriptionEnglish": "NETHERLANDS",
    "Description": "هولندا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:42:09.963Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "693",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "مجري",
    "NationalityEnu": "ALMAJAR",
    "DescriptionArabic": "المجر",
    "DescriptionEnglish": "ALMAJAR",
    "Description": "المجر",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "838",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كابمان",
    "NationalityEnu": "كابمان",
    "DescriptionArabic": "كابمان",
    "DescriptionEnglish": "كابمان",
    "Description": "كابمان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "840",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "غواديلون",
    "NationalityEnu": "GUADELOUPE",
    "DescriptionArabic": "غواديلون",
    "DescriptionEnglish": "Guadeloupe",
    "Description": "غواديلون",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "847",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "سانت بيير",
    "NationalityEnu": "SAINT PRERRE",
    "DescriptionArabic": "سانت بيير",
    "DescriptionEnglish": "Saint Prerre",
    "Description": "سانت بيير",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "639",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ايسلندية",
    "NationalityEnu": "ICELANDER",
    "DescriptionArabic": "ايسلند",
    "DescriptionEnglish": "Iceland",
    "Description": "ايسلند",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "742",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ريوكو",
    "NationalityEnu": "ريوكو",
    "DescriptionArabic": "ريوكو",
    "DescriptionEnglish": "ريوكو",
    "Description": "ريوكو",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "901",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 1.5,
    "RestrictedExport": "1",
    "NationalityAra": "مولدوفيه",
    "NationalityEnu": "MOLDOVIAN",
    "DescriptionArabic": "مولدوفا",
    "DescriptionEnglish": "Moldova",
    "Description": "مولدوفا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "660",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "يورو",
    "CurrencyValue": 2.25,
    "LastCurrencyUpdate": "2019-03-27T13:29:43.376Z",
    "RestrictedExport": "1",
    "NationalityAra": "رومانية",
    "NationalityEnu": "ROMANIAN",
    "DescriptionArabic": "رومانيا",
    "DescriptionEnglish": "Romania",
    "Description": "رومانيا",
    "ActiveInd": "Active",
    "changedDate": "2019-03-27T13:29:43.376Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "823",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "بنميه",
    "NationalityEnu": "PANAMANIAN",
    "DescriptionArabic": "بنما",
    "DescriptionEnglish": "Panama",
    "Description": "بنما",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "895",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ليتوانيه",
    "NationalityEnu": "LITHUANIAN",
    "DescriptionArabic": "ليتوانيا",
    "DescriptionEnglish": "Lithuania",
    "Description": "ليتوانيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "659",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "جورجيه",
    "NationalityEnu": "GEORGIAN",
    "DescriptionArabic": "جورجيا",
    "DescriptionEnglish": "Georgia",
    "Description": "جورجيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "770",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ج ميرواي",
    "NationalityEnu": "ج ميرواي",
    "DescriptionArabic": "ج ميرواي",
    "DescriptionEnglish": "ج ميرواي",
    "Description": "ج ميرواي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "821",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "كوبيه",
    "NationalityEnu": "CUBAN",
    "DescriptionArabic": "كوبا",
    "DescriptionEnglish": "Cuba",
    "Description": "كوبا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "781",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "واليسوفروتانا",
    "NationalityEnu": "WALLIS AND FUTUNA",
    "DescriptionArabic": "واليسوفروتانا",
    "DescriptionEnglish": "Wallis and Futuna",
    "Description": "واليسوفروتانا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "646",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "فنلندية",
    "NationalityEnu": "FINN",
    "DescriptionArabic": "فنلندا",
    "DescriptionEnglish": "Finland",
    "Description": "فنلندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "779",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تونغا",
    "NationalityEnu": "TONGA",
    "DescriptionArabic": "تونغا",
    "DescriptionEnglish": "Tonga",
    "Description": "تونغا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "714",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "افغانستانية",
    "NationalityEnu": "AFGHAN",
    "DescriptionArabic": "افغانستان",
    "DescriptionEnglish": "Afghanistan",
    "Description": "افغانستان",
    "ActiveInd": "Active",
    "changedDate": "2021-03-15T09:14:38.784Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "002",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "شيكل إسرائيلي",
    "CurrencyValue": 9,
    "LastCurrencyUpdate": "2019-03-27T13:37:09.040Z",
    "PhoneCode": "970",
    "RestrictedExport": "1",
    "NationalityAra": "فلسطيني",
    "NationalityEnu": "PALESTINIAN",
    "DescriptionArabic": "فلسطين",
    "DescriptionEnglish": "Palestine",
    "Description": "فلسطين",
    "ActiveInd": "Active",
    "changedDate": "2022-02-28T07:40:09.147Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "353",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "253",
    "RestrictedExport": "1",
    "NationalityAra": "جيبوتية",
    "NationalityEnu": "DGIBOUTIAN",
    "DescriptionArabic": "جيبوتي",
    "DescriptionEnglish": "Djibouti",
    "Description": "جيبوتي",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "554",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "PhoneCode": "64",
    "RestrictedExport": "1",
    "NationalityAra": "نيوزلندية",
    "NationalityEnu": "NEW ZEALAND",
    "DescriptionArabic": "نيوزيلندا",
    "DescriptionEnglish": "New Zealand",
    "Description": "نيوزيلندا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "834",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "انتينيه",
    "NationalityEnu": "انتينيه",
    "DescriptionArabic": "انتينا",
    "DescriptionEnglish": "انتينا",
    "Description": "انتينا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "661",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "تركمانستانيه",
    "NationalityEnu": "TURKMENISTANI",
    "DescriptionArabic": "تركمانستان",
    "DescriptionEnglish": "Turkmenistan",
    "Description": "تركمانستان",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "521",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "زمبيق",
    "NationalityEnu": "ZAMBIGUE",
    "DescriptionArabic": "زمبيق",
    "DescriptionEnglish": "zambigue",
    "Description": "زمبيق",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "515",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "RestrictedExport": "1",
    "NationalityAra": "ناميبيا",
    "NationalityEnu": "NAMIBIAN",
    "DescriptionArabic": "ناميبيا",
    "DescriptionEnglish": "Namibia",
    "Description": "ناميبيا",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T12:52:23.041Z",
    "createdDate": "2018-09-03T12:52:22.259Z"
  },
  {
    "ISO_Code": "Qui",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "Et aut deserunt nisi commodo libero",
    "PhoneCode": "In volu",
    "RestrictedExport": "1",
    "CurrencyNameEnu": "Debitis non culpa temporibus cupiditate perspiciatis dolores",
    "NationalityAra": "Minima ex ullamco commodi in id fugiat deserunt rerum sit saepe nesciunt vel dolores",
    "NationalityEnu": "Laborum Quis aute aut tenetur quis quod corrupti cupiditate repudiandae ut qui quis voluptas eiusmod pariatur Fugit",
    "DescriptionArabic": "الوصف بالعربي",
    "DescriptionEnglish": "Ex aut adipisicing sit suscipit consectetur neque reprehenderit enim est eos et",
    "Description": "الوصف بالعربي",
    "ActiveInd": "Active",
    "changedDate": "2021-09-14T11:06:59.128Z",
    "createdDate": "2021-09-14T11:06:48.339Z"
  },
  {
    "ISO_Code": "999",
    "CountryGroup": "Non_Local",
    "Restricted": false,
    "CurrencyName": "دينار",
    "PhoneCode": "962",
    "RestrictedExport": "1",
    "NationalityAra": "اردنية",
    "DescriptionArabic": "الاردن سفارة",
    "DescriptionEnglish": "jordan s",
    "Description": "الاردن سفارة",
    "ActiveInd": "Active",
    "changedDate": "2021-10-21T06:44:10.282Z",
    "createdDate": "2021-10-21T06:43:10.491Z"
  }
]  
```

 
  

  
**Get List Of Cities**
----
Returns List of Cities in JSON format.

* **URL**

```ruby
http://10.0.52.243:8080/birthcertificate/cities
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> **BODY raw**
 
  
```ruby
{
   "ISO_Code": "001"
}
 ```  
 
* **Example Request**

> **Curl**

```ruby
 curl -X POST "http://10.0.52.243:8080/birthcertificate/cities" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"ISO_Code\": \"001\"}"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```
[
  {
    "Code": "13",
    "DescriptionArabic": "الزرقاء",
    "DescriptionEnglish": "Zarqa",
    "Description": "الزرقاء",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:34.485Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "21",
    "DescriptionArabic": "اربد",
    "DescriptionEnglish": "Irbid",
    "Description": "اربد",
    "ActiveInd": "Active",
    "changedDate": "2021-03-23T09:14:38.770Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "11",
    "DescriptionArabic": "العاصمة",
    "DescriptionEnglish": "Amman",
    "Description": "العاصمة",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:36.329Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "22",
    "DescriptionArabic": "المفرق",
    "DescriptionEnglish": "Mafraq",
    "Description": "المفرق",
    "ActiveInd": "Active",
    "changedDate": "2021-03-16T11:54:15.594Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "23",
    "DescriptionArabic": "جرش",
    "DescriptionEnglish": "Jerash",
    "Description": "جرش",
    "ActiveInd": "Active",
    "changedDate": "2018-11-18T13:49:35.840Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "14",
    "DescriptionArabic": "مأدبا",
    "DescriptionEnglish": "Madaba",
    "Description": "مأدبا",
    "ActiveInd": "Active",
    "changedDate": "2018-11-25T12:32:58.136Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "12",
    "DescriptionArabic": "البلقاء",
    "DescriptionEnglish": "Balqa",
    "Description": "البلقاء",
    "ActiveInd": "Active",
    "changedDate": "2020-07-29T09:44:56.315Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "32",
    "DescriptionArabic": "الطفيله",
    "DescriptionEnglish": "Tafilah",
    "Description": "الطفيله",
    "ActiveInd": "Active",
    "changedDate": "2018-11-25T12:18:56.791Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "33",
    "DescriptionArabic": "معان",
    "DescriptionEnglish": "Ma'an",
    "Description": "معان",
    "ActiveInd": "Active",
    "changedDate": "2018-11-25T12:33:01.874Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "24",
    "DescriptionArabic": "عجلون",
    "DescriptionEnglish": "Ajloun",
    "Description": "عجلون",
    "ActiveInd": "Active",
    "changedDate": "2018-12-20T15:07:35.075Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "31",
    "DescriptionArabic": "الكرك",
    "DescriptionEnglish": "Karak",
    "Description": "الكرك",
    "ActiveInd": "Active",
    "changedDate": "2018-11-25T10:54:59.389Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  },
  {
    "Code": "34",
    "DescriptionArabic": "العقبة",
    "DescriptionEnglish": "Aqaba",
    "Description": "العقبة",
    "ActiveInd": "Active",
    "changedDate": "2018-09-19T07:44:35.961Z",
    "createdDate": "2018-09-03T12:54:58.303Z"
  }
]
```

>  **Response headers :**

```
Date: Thu, 24 Mar 2022 11:14:27 GMT
Cache-Control: no-store
Content-Type: application/json;charset=utf-8
Content-Length: 2503
```


**Get List Of Departements**
----
Returns List of Departements in JSON format.

* **URL**

```ruby
http://10.0.52.243:8080/birthcertificate/departments
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> **BODY raw**
 
  
```ruby
{
"IsoCode":"001",
"ServiceType":"Birth_Certificate",
"DepartmentType":"02"
}
 ```  
 
* **Example Request**

> **Curl**

```ruby
curl -X POST "http://10.0.52.243:8080/birthcertificate/departments" -H "accept: application/json" -H "Content-Type: application/json" -d "{\"IsoCode\":\"001\",\"ServiceType\":\"Birth_Certificate\",\"DepartmentType\":\"02\"}"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```
[
  {
    "Code": "201",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "السلط   تلفون 05554921",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "السلط",
    "EnglishIssuanceAuthority": "AL SALT",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "201",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "السلط",
    "DescriptionEnglish": "AL SALT",
    "Description": "السلط",
    "ActiveInd": "Active",
    "changedDate": "2021-12-27T16:09:42.077Z",
    "createdDate": "2018-09-05T19:26:56.329Z"
  },
  {
    "Code": "701",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "الطفيله   تلفون 03341116",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "الطفيلة",
    "EnglishIssuanceAuthority": "AL TAFILA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "701",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "الطفيلة",
    "DescriptionEnglish": "AL TAFILA",
    "Description": "الطفيلة",
    "ActiveInd": "Active",
    "changedDate": "2021-12-27T16:09:45.428Z",
    "createdDate": "2018-09-05T19:26:56.329Z"
  },
  {
    "Code": "601",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": true,
    "PrintingInd": true,
    "AddressDetails": "العقبه    تلفون 03313864",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "العقبة",
    "EnglishIssuanceAuthority": "AL AQABA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "601",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": true,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "العقبة",
    "DescriptionEnglish": "AL AQABA",
    "Description": "العقبة",
    "ActiveInd": "Active",
    "changedDate": "2020-09-06T14:29:59.316Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "001",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "جبل عمان / الدوار الاول    تلفون  636370",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "عمان الغربيه",
    "EnglishIssuanceAuthority": "AMMAN",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "001",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "عمان الغربيه",
    "DescriptionEnglish": "AMMAN",
    "Description": "عمان الغربيه",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:35.204Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "003",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "عمان / المحطه   تلفون    4882968",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "ماركا",
    "EnglishIssuanceAuthority": "MARKA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "003",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "ماركا",
    "DescriptionEnglish": "MARKA",
    "Description": "ماركا",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:33.626Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "005",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "صويلح   تلفون  5357428",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "صويلح",
    "EnglishIssuanceAuthority": "SWEILEH",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "005",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": true,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "صويلح",
    "DescriptionEnglish": "SWEILEH",
    "Description": "صويلح",
    "ActiveInd": "Active",
    "changedDate": "2022-03-24T06:19:58.063Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "101",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "الزرقاء   تلفون 09983821",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "الزرقاء",
    "EnglishIssuanceAuthority": "ZARQA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "101",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "الزرقاء",
    "DescriptionEnglish": "ZARQA",
    "Description": "الزرقاء",
    "ActiveInd": "Active",
    "changedDate": "2022-03-08T11:09:18.989Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "009",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "سحاب    تلفون 721175",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "سحاب",
    "EnglishIssuanceAuthority": "SAHAB",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "009",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "سحاب",
    "DescriptionEnglish": "SAHAB",
    "Description": "سحاب",
    "ActiveInd": "Active",
    "changedDate": "2021-09-02T13:30:06.110Z",
    "createdDate": "2018-09-05T19:26:56.334Z"
  },
  {
    "Code": "006",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "IP_Address_From": "10.69.10.70",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "جبل الحسين/عمان   تلفون 4610278",
    "AdditionalServiceFees": 0,
    "IP_Address_To": "10.69.10.76",
    "ArabicIssuanceAuthority": "جبل الحسين",
    "EnglishIssuanceAuthority": "JABAL ALHUSSEIN",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "004",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": false,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "جبل الحسين",
    "DescriptionEnglish": "JABAL ALHUSSEIN",
    "Description": "جبل الحسين",
    "ActiveInd": "Active",
    "changedDate": "2022-03-21T09:23:20.741Z",
    "createdDate": "2018-09-05T19:26:56.335Z"
  },
  {
    "Code": "004",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": true,
    "PrintingInd": true,
    "AddressDetails": "وادي السير   تلفون  814407",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "وادي السير ",
    "EnglishIssuanceAuthority": "wadi alsir",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "005",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "وادي السير",
    "DescriptionEnglish": "WADI ALSIR",
    "Description": "وادي السير",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:36.313Z",
    "createdDate": "2018-09-05T19:26:56.335Z"
  },
  {
    "Code": "002",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "عمان / دوار الشرق الاوسط   تلفون 4754932",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "الاشرفيه",
    "EnglishIssuanceAuthority": "AL ASHRAFEA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "002",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": false,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "الاشرفيه",
    "DescriptionEnglish": "AL ASHRAFEA",
    "Description": "الاشرفيه",
    "ActiveInd": "Active",
    "changedDate": "2022-01-11T10:50:38.384Z",
    "createdDate": "2018-09-05T19:26:56.335Z"
  },
  {
    "Code": "008",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "الجيزه   تلفون 08560138",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "الجيزه",
    "EnglishIssuanceAuthority": "AL JEZA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "008",
    "OnlineInd": true,
    "CivilOfficeInd": true,
    "InternalOffice": true,
    "PrintingButton": "Printing",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "الجيزه",
    "DescriptionEnglish": "AL JEZA",
    "Description": "الجيزه",
    "ActiveInd": "Active",
    "changedDate": "2021-12-27T16:23:41.158Z",
    "createdDate": "2018-09-05T19:26:56.336Z"
  },
  {
    "Code": "904",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": false,
    "AddressDetails": "العقبه    تلفون 03313864",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "العقبه",
    "EnglishIssuanceAuthority": "AQABA",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "904",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": false,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "غزة / العقبة",
    "DescriptionEnglish": " AQABA",
    "Description": "غزة / العقبة",
    "ActiveInd": "Active",
    "changedDate": "2019-02-17T14:45:38.004Z",
    "createdDate": "2018-09-05T19:26:56.336Z"
  },
  {
    "Code": "079",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "خلدا ام السماق تلاع العلي",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "تلاع العلي",
    "EnglishIssuanceAuthority": "TILA ALALI",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "079",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "Printing",
    "PassportFileInd": false,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "تلاع العلي",
    "DescriptionEnglish": "TILA ALALI",
    "Description": "تلاع العلي",
    "ActiveInd": "Active",
    "changedDate": "2018-12-20T08:14:55.581Z",
    "createdDate": "2018-09-05T19:26:56.337Z"
  },
  {
    "Code": "018",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": true,
    "PrintingInd": true,
    "AddressDetails": "طبربور",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "عمان المركز",
    "EnglishIssuanceAuthority": "AMMAN CENTER",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "EmbassyCode": "018",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "عمان المركز",
    "DescriptionEnglish": "AMMAN CENTER",
    "Description": "عمان المركز",
    "ActiveInd": "Active",
    "changedDate": "2022-02-17T13:14:35.735Z",
    "createdDate": "2018-09-05T19:26:56.343Z"
  },
  {
    "Code": "091",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": false,
    "AddressDetails": "قصر العدل",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "عمان",
    "EnglishIssuanceAuthority": "amman",
    "PrintingExport": "0",
    "DepartmentTypeExport": "1",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": false,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": false,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "محطة قصر العدل",
    "DescriptionEnglish": "amman",
    "Description": "محطة قصر العدل",
    "ActiveInd": "Active",
    "changedDate": "2020-08-09T07:45:05.107Z",
    "createdDate": "2020-08-09T07:42:06.054Z"
  },
  {
    "Code": "069",
    "HasEmployee": false,
    "HasManager": false,
    "DepartmentType": "CSPD_Office",
    "MainOfficeInd": false,
    "PrintingInd": true,
    "AddressDetails": "حي نزال مقابل حلويات العنبتاوي",
    "AdditionalServiceFees": 0,
    "ArabicIssuanceAuthority": "عمان",
    "EnglishIssuanceAuthority": "amman",
    "PrintingExport": "1",
    "DepartmentTypeExport": "1",
    "OnlineInd": false,
    "CivilOfficeInd": true,
    "InternalOffice": true,
    "PrintingButton": "ViewAndPrinting",
    "PassportFileInd": true,
    "CheckIPAddress": false,
    "embassyInd": false,
    "DescriptionArabic": "حي نزال ",
    "DescriptionEnglish": "hai nzaal ",
    "Description": "حي نزال ",
    "ActiveInd": "Active",
    "changedDate": "2021-06-20T08:58:59.084Z",
    "createdDate": "2021-06-20T08:55:46.585Z"
  }
]
```

>  **Response headers :**

```
 cache-control: no-store 
 content-length: 1375 
 content-type: application/json;charset=utf-8 
 date: Fri, 25 Mar 2022 20:06:51 GMT 
```

**Get List Of Marital Status**
----
Returns List of Marital Status in JSON format.

* **URL**

```ruby
http://10.0.52.243:8080/birthcertificate/martialstatus
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> None
 
* **Example Request**

> **Curl**

```ruby
curl -X POST "http://10.0.52.243:8080/birthcertificate/martialstatus" -H "accept: application/json"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```
[
  {
    "Code": "02",
    "DescriptionArabic": "متزوج/ متزوجة",
    "DescriptionEnglish": "Married",
    "Description": "متزوج/ متزوجة",
    "ActiveInd": "Active",
    "changedDate": "2022-03-20T13:28:13.441Z",
    "createdDate": "2018-09-03T13:04:56.283Z"
  },
  {
    "Code": "03",
    "DescriptionArabic": "مطلق / مطلقة",
    "DescriptionEnglish": "DIVORCE",
    "Description": "مطلق / مطلقة",
    "ActiveInd": "Active",
    "changedDate": "2022-03-08T11:01:00.017Z",
    "createdDate": "2018-09-03T13:05:12.600Z"
  },
  {
    "Code": "04",
    "DescriptionArabic": "ارمل / ارملة",
    "DescriptionEnglish": "WIDOWED",
    "Description": "ارمل / ارملة",
    "ActiveInd": "Active",
    "changedDate": "2021-03-16T11:29:36.394Z",
    "createdDate": "2018-09-03T13:05:22.088Z"
  },
  {
    "Code": "05",
    "DescriptionArabic": "متزوجه من اجنبي",
    "DescriptionEnglish": "MARRIAGE FROM FOREIGN",
    "Description": "متزوجه من اجنبي",
    "ActiveInd": "Active",
    "changedDate": "2018-12-24T08:36:35.994Z",
    "createdDate": "2018-09-03T13:05:31.816Z"
  },
  {
    "Code": "06",
    "DescriptionArabic": "ارملة الاجنبي",
    "DescriptionEnglish": "WIDOWED FOREIGN",
    "Description": "ارملة الاجنبي",
    "ActiveInd": "Active",
    "changedDate": "2018-12-17T09:32:39.880Z",
    "createdDate": "2018-09-03T13:05:44.967Z"
  },
  {
    "Code": "07",
    "DescriptionArabic": "زوجة المفقود",
    "DescriptionEnglish": "MISS WIFE",
    "Description": "زوجة المفقود",
    "ActiveInd": "Active",
    "changedDate": "2022-02-28T07:40:09.100Z",
    "createdDate": "2018-09-03T13:05:58.616Z"
  },
  {
    "Code": "10",
    "DescriptionArabic": "زوجة الغائب",
    "DescriptionEnglish": "The Absent Wife",
    "Description": "زوجة الغائب",
    "ActiveInd": "Active",
    "changedDate": "2018-09-03T13:06:48.009Z",
    "createdDate": "2018-09-03T13:06:33.270Z"
  },
  {
    "Code": "11",
    "DescriptionArabic": "زوجة أجنبي ابناء اردني",
    "DescriptionEnglish": "FOREIGN WIFE JOR SON",
    "Description": "زوجة أجنبي ابناء اردني",
    "ActiveInd": "Active",
    "changedDate": "2020-04-14T09:41:43.519Z",
    "createdDate": "2018-09-03T13:07:00.270Z"
  },
  {
    "Code": "01",
    "DescriptionArabic": "أعزب/ عزباء",
    "DescriptionEnglish": "Single",
    "Description": "أعزب/ عزباء",
    "ActiveInd": "Active",
    "changedDate": "2022-03-21T09:23:20.714Z",
    "createdDate": "2020-07-29T08:02:56.202Z"
  },
  {
    "Code": "Saepe repudiandae necessitatibus accusantium molestiae aspernatur a quidem aspernatur aperiam",
    "DescriptionArabic": "الوصف بالعربي",
    "DescriptionEnglish": "Et corporis magna nemo eos asperiores voluptate ipsam magnam eum veniam sequi",
    "Description": "الوصف بالعربي",
    "ActiveInd": "Active",
    "changedDate": "2021-09-14T11:05:33.078Z",
    "createdDate": "2021-09-14T11:05:22.516Z"
  }
]
```

>  **Response headers :**

```
Date: Thu, 24 Mar 2022 11:12:20 GMT
Cache-Control: no-store
Content-Type: application/json;charset=utf-8
Content-Length: 2584
```

**Get Applicant Data**
----
Returns the applicant's data and the list of beneficiaries associated with the applicant in JSON format.

* **URL**

```ruby
http://10.0.52.243:8080/birthcertificate/applicantes
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> **BODY raw**
 
  
```ruby
{
    "NAT_NO": "string"
}
 ```  
 
* **Example Request**

> **Curl**

```ruby
curl -X POST "http://10.0.52.243:8080/birthcertificate/applicantes" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"NAT_NO\": \"9932028787"\"}"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```

```

>  **Response headers :**

```
Date: Thu, 24 Mar 2022 11:23:42 GMT
Cache-Control: no-store
Content-Type: application/json;charset=utf-8
Content-Length: 764
```

**Get Beneficiary Birth Data
----
Returns Beneficiary Birth Data in JSON format.

* **URL**

```ruby
http://localhost:8083/birthcertificate/beneficiaries
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> **BODY raw**
 
  
```ruby
{
    "NAT_NO": "string"
}
 ```  
 
* **Example Request**

> **Curl**

```ruby
curl -X POST "http://10.0.52.243:8080/birthcertificate/beneficiaries" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"NAT_NO\": \"9932028787"\"}"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```
{
  "FirstNameARA": "هديل",
  "SecondNameARA": "فؤاد",
  "ThirdNameARA": "سالم",
  "FamilyNameARA": "عيسوه",
  "FirstNameENU": "Hadeel",
  "SecondNameENU": "Fuad",
  "ThirdNameENU": "Salem",
  "FamilyNameENU": "eisouh",
  "Gender": "Female",
  "NationalId": "9932028787",
  "BirthDate": "1993-09-06T00:00:00.000Z",
  "FFirstNameARA": "فؤاد",
  "FSecondNameARA": "سالم",
  "FFamilyNameARA": "عيسوه",
  "MFirstNameARA": "وفاء",
  "MSecondNameARA": "يعقوب",
  "MFamilyNameARA": "مراد",
  "MFirstNameENU": "Wafa",
  "FSecondNameENU": "Salem",
  "FFamilyNameENU": "eisouh",
  "EnglishNameInd": false,
  "CivilOffice": "عجلون",
  "CivilRegistrationNumber": "024/073",
  "ReligionARA": "Christian",
  "SerialNumber": "9932028787",
  "FullName": "هديل فؤاد سالم عيسوه",
  "PlaceOfBirthARA": "عجلون",
  "PlaceOfBirthENU": "AJLOUN",
  "FatherReligionARA": "Christian",
  "MotherReligionARA": "Christian",
  "FatherReligionENU": "Christian",
  "MotherReligionENU": "Christian",
  "ReligionENU": "Christian",
  "FFirstNameENU": "Fuad",
  "WrittenDateARA": "السادس من ايلـــــــول لعام الف وتسعمائه و ثلاثة وتسعين ميلادي",
  "WrittenDateENU": " Sixth OF September Nineteen Ninety Three",
  "CivilStatus": "Live",
  "MSecondNameENU": "Yacoub",
  "MFamilyNameENU": "Murad",
  "ArNationality": "اردني",
  "EnNationality": "JORDANIAN",
  "EventNumber": "00046/001692",
  "BirthRegisterType": "3",
  "CheckDigit": "ك",
  "CivilOfficeENU": "AJLOUN",
  "WantedInd": false
}
```

>  **Response headers :**

```
Date: Thu, 24 Mar 2022 12:51:29 GMT
Cache-Control: no-store
Content-Type: application/json;charset=utf-8
Content-Length: 1397
```
**Get Prerequisit**
----
Returns the prerequisite for the requested service in JSON format.

* **URL**

```ruby
http://localhost:8083/birthcertificate/prerequisit
```

* **Method:**

```ruby
POST
```
  
* **Data Params**

> **BODY raw**
 
```ruby
{
 "ServiceType": "string",
 "UserLanguage": "string"
}
 ```  
 
* **Example Request**

> **Curl**

```ruby
curl -X POST "http://localhost:8083/birthcertificate/prerequisit" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"ServiceType\": \"Birth_Certificate\", \"UserLanguage\": \"ar_JO\"}"
```
   
* **Example Response**

**Success Response:**
 
> **Code:** 200  
> **Description:** successful operation <br />
      
	 
> **Response body :**

```
{
  "Prerequisit": "شهادة ميلاد"
}
```

>  **Response headers :**

```
Date: Wed, 23 Mar 2022 20:27:23 GMT
Cache-Control: no-store
Content-Type: application-Json;charset=utf-8
Content-Length: 39
```







