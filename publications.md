---
layout: page
title: 
---




### Publication List

<div id="publicationlist"></div>

<script language="javascript">

  var purexml_SERG = "https://purexml-open.ewi.tudelft.nl/direct/tu/group/d40bac4b-3dd0-4427-aa5f-9331cae5d02e";
  var page_nr = location.search;

  var xhttp = new XMLHttpRequest();
  xhttp.onreadystatechange = function() {
    if (this.readyState == 4 && this.status == 200) {
      document.getElementById("publicationlist").innerHTML = this.responseText;
    }
  };
  xhttp.open("GET", purexml_SERG + page_nr, true);
  xhttp.send();
</script>

