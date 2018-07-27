<html>
<head>
<script src="home.js" type="text/javascript">
function init() {
 Tabletop.init( { key: ‘https://docs.google.com/spreadsheets/d/1O4OHBIjftGkG2NlwlKzQDrkykcKQsLuXXh-qt7Op4iA/pubhtml',
 callback: function(data, tabletop) { 
 console.log(data)
 },
 simpleSheet: true } )
}
window.addEventListener(‘DOMContentLoaded’, init)
</script>
</head>
<body onload="loadPage()">  
</body>
</html>
