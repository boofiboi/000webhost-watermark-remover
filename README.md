# DISCLAIMER: AS OF 11.1.2022 MY SITE HAS GOTTEN DELETED FOR USING THIS! SO USE IT AT YOUR OWN RISK!


#### 000webhost-watermark-remover
Removes the annoying "000WebHost" watermark found on free sites hosted on the service.


# USAGE:
#1 - Integrate jquery into your html file, either by adding it into the <script> we will be creating or as a linked js file in the head tag.
#2 - Add this script block anywhere into your body or head.
  
  ```<script type="text/javascript">window.addEventListener('load', function () { $("a[href*='000webhostapp']")[0].parentElement.remove()})</script>```
  
#3 - Profit, the watermark will now be deleted every time once the entire website loads, make sure to put it on every html file in your website otherwise it will appear in the ones that dont have it.
