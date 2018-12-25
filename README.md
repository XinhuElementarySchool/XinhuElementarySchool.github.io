[**台北市內湖區新湖國民小學 (Website Page)**](https://xinhuelementaryschool.github.io/)
* **Home**
  * *Image*
    * Location: [\src\home](\src\home)
      1. Update Method:  Replace images and keep the filenames same.
      2. Update Notifications: small image size is better.  (.jpg is good enough in most case)
---------------------------------------------------------------------------
* **Galley**
  * *Banner*
    1. Location: [.\src\gallery](.\src\gallery).
    2. Dimensions: 1600x300.
    3. Update Method: Replace images and keep the filenames same.
  * *Category* 
    1. Name Update: Contact me (kind of complicated).
    2. Color Update: xinhu/css/gallery.css | .classColorAll | background-color (Reference: xinhu\tutorial\gallery\Category_Color.png)
  * *<span style="color:red">Create a new Video<span>*
    1. Web Update: [.\javascript\gallery_videos.js](.\javascript\gallery_videos.js) ([Reference](.\tutorial\gallery\Video_Update.mp4))
    2. (Optional) Excel Update:  xinhu/youtubeVideos.xlsx 
    3. (Optional) Excel to Web:  [csv2json](https://www.csvjson.com/csv2json) or [freeformate](https://www.freeformatter.com/csv-to-json-converter.html) ([Refference](.\tutorial\gallery\Excel_to_Web.mp4))
---------------------------------------------------------------------------
* **Medal**
  * *Banner*
     1. Location: xinhu/src/medal.
     2. Dimensions: 1600x300.
     3. Update Method: Replace images and keep the filenames same.
  * *Category* 
     1. Name Update: Contact me (kind of complicated).
     2. Color Update: xinhu/css/medal.css | .classColorAll | background-color (Reference: xinhu\tutorial\medal\Category_Color.jpg)
  * *<span style="color:red">Create a new Medal</span>*
     * Recommended procedure: 1. tag index -> 2. take a photo -> 3.  web update / excel update 
     * Photo
       1. Big (original)
            * Location: [.\src\medalPhotos](.\src\medalPhotos)
            * Dimension: 3024x4032
       2. Small (compressed)
            * Location: xinhu\src\medalPhotosDownsize
            * Dimension: 320x426
     * Web Update: xinhu\javascript\medal_data.js (Reference: xinhu\tutorial\medal\Medal_Update.mp4)
     * (Optional) Excel Update:  [.xinhu\medals.xlsx](.xinhu\medals.xlsx)
     * (Optional) Excel to Web:  [csv2json](https://www.csvjson.com/csv2json) or [freeformate](https://www.freeformatter.com/csv-to-json-converter.html)  ([Refference](.\tutorial\medal\Excel_to_Web.mp4))
