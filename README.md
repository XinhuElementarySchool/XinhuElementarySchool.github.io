### [臺北市內湖區新湖國民小學 (Website Page)](https://xinhuelementaryschool.github.io/)
* **Home**
  * *Image*
    * Location: [src/home/](./src/home/)
    * Update Method:  Replace images and keep the filenames same.
    * Update Notifications: small image size is better.  (.jpg is good enough in most case)
---
#### [活動影片專區](https://xinhuelementaryschool.github.io/gallery.html)
* **Galley**
  * *Banner*
    * Location: [src/gallery/](src/gallery/)
    * Dimensions: 1600x300.
    * Update Method: Replace images and keep the filenames same.
  * *Category* 
    * Name Update: Contact me (kind of complicated).
    * Color Update: [css/gallery.css](css/gallery.css) | .classColorAll | background-color] ([Reference](tutorial/gallery/Category_Color.png))
  * ### \~*Create a new Video\*~
    * Web Update: [javascript/gallery_videos.js](javascript/gallery_videos.js) ([DEMO video](https://www.youtube.com/watch?v=Eq7yArnPIIc&feature=youtu.be))
    * (Optional) Excel Update:  [youtubeVideos.xlsx](youtubeVideos.xlsx) 
    * (Optional) Excel to Web:  [csv2json](https://www.csvjson.com/csv2json) or [freeformate](https://www.freeformatter.com/csv-to-json-converter.html) ([Reference](tutorial/gallery/Excel_to_Web.mp4))
---
#### [獎盃專區](https://xinhuelementaryschool.github.io/medal.html)
* **Medal**
  * *Banner*
     * Location: [src/medal/](src/medal/)
     * Dimensions: 1600x300.
     * Update Method: Replace images and keep the filenames same.
  * *Category* 
     * Name Update: Contact me (kind of complicated).
     * Color Update: [css/medal.css](css/medal.css) | .classColorAll | background-color ([Reference](tutorial/medal/Category_Color.jpg))
  * ### \~*Create a new Medal\*~
     * Photo
       1. Big (original)
            * Location: [src/medal/medalPhotos/](src/medal/medalPhotos/)
            * Dimension: 3024x4032
       2. Small (compressed)
            * Location: [src/medal/medalPhotosDownsize/](src/medal/medalPhotosDownsize/)
            * Dimension: 320x426
     * Web Update: [javascript/medal_data.js](javascript/medal_data.js) ([DEMO video](tutorial/medal/Medal_Update.mp4))
     * (Optional) Excel Update:  [medals.xlsx](medals.xlsx)
     * (Optional) Excel to Web:  [csv2json](https://www.csvjson.com/csv2json) or [freeformate](https://www.freeformatter.com/csv-to-json-converter.html)  ([Reference](tutorial/medal/Excel_to_Web.mp4))
