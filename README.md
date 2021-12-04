# MemeShare
An android app built using Kotlin
MemeShare is an android app that fetches memes using the API.
</br>Minimum Support: Android 5
</br></br><b>API link:</b> https://meme-api.herokuapp.com/gimme
</br>The app uses <b>Volley and Glide libraries</b>. It also makes use of <b>Material Design.</b>
</br></br><b><h3>Functions used in MainActivity.kt</h3></b>
<ul>
  <li>
    <b>loadMeme():</b>
    <p>This function is called as soon as the main activity loads. It loads the meme and displays it in the ImageView.</p>
  </li>
  <li>
    <b>shareMeme():</b>
    <p>Shares the meme on WhatsApp, Facebook, etc. The current meme's url is shared to the receiver.</p>
  </li>
  <li>
    <b>nextMeme():</b>
    <p>This function loads another meme. It calls the loadMeme() function.</p>
  </li>
 </ul>
 </br>To make the app look lively, a Linear Progress bar is added. The progress bar will indicate the progress of fetching meme and gets disappear as the meme loads on the screen.
 </br><b>Open MemeShare_UI_Look.jpg to know how the app looks.</b>
  
  
