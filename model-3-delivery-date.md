---
layout: page
title: Model 3 Delivery Estimate from Teslanomics
permalink: "/model-3-delivery-date"
published: true
---
<script>
function getQueryVariable(variable)
{
       var query = window.location.search.substring(1);
       var vars = query.split("&");
       for (var i=0;i<vars.length;i++) {
               var pair = vars[i].split("=");
               if(pair[0] == variable){return pair[1];}
       }
       return(false);
}
</script>

<img id="img-estimate"></div>
<script>

img = getQueryVariable("img");
document.getElementById("img-estimate").src=img;

</script>
