## JioSaavn API [Unofficial]
#### JioSaavn API written in Python using Flask  

 ---
###### **NOTE:** You don't need to have JioSaavn link of the song in order to fetch the song details, you can directly search songs by their name. Fetching Songs/Albums/Playlists from URL is also supported in this API.  

 ---

### **Features**:
##### Currently the API can get the following details for a specific song in JSON format:
- **Song Name**
- **Singer Name**
- **Album Name**
- **Album URL**

```json
 {
    "320kbps": "true",
    "album": "Alone",
    "album_url": "https://www.jiosaavn.com/album/alone/7RrbkHgCRho_",
    "albumid": "42283382",
    "artistMap": {
      "Guru Randhawa": "712878",
      "Kapil Sharma": "458733",
      "Sanjoy": "682505"
    },
    "cache_state": "false",
    "copyright_text": "℗ 2023 Super Cassettes Industries Private Limited",
    "disabled": "true",
    "disabled_text": "Pro Only",
    "duration": "235",
    "encrypted_media_path": "NMKyboFo/FhJMh3JGJHSZtD5a0H59WQNFwTT7XATvjL+R1rLExES38VnanDRN1uu",
    "encrypted_media_url": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyqaM9p6Vrcl+te8eR3VWk5usWGhQ96PCNppxvx/xg1q2NKMrvlU5D0xw7tS9a8Gtq",
    "explicit_content": 0,
    "featured_artists": "",
    "featured_artists_id": "",
    "has_lyrics": "true",
    "id": "KmiYF-m-",
    "image": "https://c.saavncdn.com/848/Alone-Punjabi-2023-20230313155628-500x500.jpg",
    "is_dolby_content": false,
    "label": "",
    "label_url": "/label/-albums/6DLuXO3VoTo_",
    "language": "punjabi",
    "lyrics_snippet": "(ninas de ankhen lagg-lagg ke)",
    "media_preview_url": "https://preview.saavncdn.com/848/9c1af8fc5fc4a848b69cc62fe69c9db0_96_p.mp4",
    "media_url": "https://aac.saavncdn.com/848/9c1af8fc5fc4a848b69cc62fe69c9db0_320.mp4",
    "music": "Guru Randhawa",
    "music_id": "712878",
    "origin": "none",
    "perma_url": "https://www.jiosaavn.com/song/alone/OwUCaDIdWh4",
    "play_count": 1013807,
    "primary_artists": "Kapil Sharma, Guru Randhawa, Sanjoy",
    "primary_artists_id": "458733, 712878, 682505",
    "release_date": "2023-02-09",
    "rights": {
      "cacheable": true,
      "code": 1,
      "delete_cached_object": false,
      "reason": "Pro Only"
    },
    "singers": "Kapil Sharma, Guru Randhawa, Sanjoy",
    "song": "Alone",
    "starred": "false",
    "starring": "",
    "triller_available": false,
    "type": "",
    "vcode": "010910091866698",
    "vlink": "https://jiotunepreview.jio.com/content/Converted/010910091823538.mp3",
    "webp": true,
    "year": "2023"
  }
```

### **Usage**:
Fetching lyrics is optional and is triggered only when it is passed as an argument in the GET Request. (**&lyrics=true**)
**If you enable lyrics search, it will take more time to fetch results**


##### **Song URL Endpoint**:
```sh
https://jio-saavn-api-chintamanipala.vercel.app/song/?query=alone
```


**Contribution is allowed to this api**
