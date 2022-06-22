
# Welcome to Prayer Times FREE API

**Prayer Times API** is a free api made by Pawan Osman, you can use it in any app for free unlimited.

## How to use Prayer Times API?
You can use it by sending `HTTP GET` Request to endpoint below:

| Query | Definition |
|--|--|
| country | The country code|
| city | The city name|
| month | The month number 01->12 |
| day | The day number 01->31 |


GET https://api.pawan.krd/prayertimes?country=iq&city=erbil&month=6&day=22

**Response**
You will get json response like this:

    {
      "state": true,
      "country": "iq",
      "city": "sulaymaniyah",
      "month": "06",
      "day": "22",
      "date": "06-22",
      "times": {
        "fajr": "03:09",
        "sunrise": "04:43",
        "dhuhr": "12:04",
        "asr": "15:51",
        "maghrib": "19:20",
        "isha": "20:30"
      },
      "queries": "[country, city, month, day]"
    }


## Supported Countries

| Name | Code |
|--|--|
| United Arab Emirates | ae |
| Germany | de |
| France | fr |
| United Kingdom | gb |
| Iraq | iq |
| Iran | ir |
| Kuwait | kw |
| Syria | sy |

## Supported Cities


### United Arab Emirates Cities

| Name | Code |
|--|--|
| Abu Dhabi | abu dhabi |
| Dubai| dubai |


### Germany Cities

| Name | Code |
|--|--|
| Aachen | aachen |
| Berlin | berlin |
| Hamburg | hamburg |
| Munich | munich |

### France Cities

| Name | Code |
|--|--|
| Paris| paris |

### United Kingdom Cities

| Name | Code |
|--|--|
| Birmingham | birmingham |
| London | london |

### Iraq Cities

| Name | Code |
|--|--|
| Erbil | erbil |
| Baghdad | baghdad |
| Kirkuk | kirkuk |
| Duhok | duhok |
| Zakho | zakho |
| Akre | akre |
| Sulaymaniyah | sulaymaniyah |
| Halabja | halabja |
| Koysinjaq | koysinjaq |
| Qalat Dizah | qalat dizah |
| Darbandikhan | darbandikhan |
| Kifri | kifri |
| Khanaqin | khanaqin |
| Al-Shikhan | al-shikhan |
| Tuz khurma | tuz khurma |
| Bardarash | bardarash |
| Qasrok | qasrok |
| Amarah | amarah |
| Baqubah | baqubah |
| Basrah | basrah |
| Diwaniyah | diwaniyah |
| Hillah | hillah |
| Karbala | karbala |
| Kut | kut |
| Mosul | mosul |
| Najaf | najaf |
| Nasiriyah | nasiriyah |
| Ramadi | ramadi |
| Samawah | samawah |
| Tikrit | tikrit |


### Iran Cities

| Name | Code |
|--|--|
| Baneh | baneh |
| Dehgolan | dehgolan |
| Kamyaran | kamyaran |
| Marivan | marivan |
| Paveh | paveh |
| Piranshahr | piranshahr |
| Sanandaj | sanandaj |
| Saqqez | saqqez |
| Sanandaj | sanandaj|
| Urmia | urmia |


### Kuwait Cities

| Name | Code |
|--|--|
| Abdali | baneh |
| Al Asimah | al asimah |
| Bubiyan Island | bubiyan island |
| Failaka Island | failaka island |
| Salmiya | salmiya |
| Umm Al Maradim Island | umm al maradim island |

### Syria Cities

| Name | Code |
|--|--|
| Aleppo | aleppo |
| Damascus | damascus |
| Deir Ez-Zor | deir ez-zor |
| Hama | hama |
| Homs | homs |
| Latakia | latakia |



#### Data is from this repository: https://github.com/kosratdev/muslim-data-ios

