<!DOCTYPE html>
<html>
<head>
<style>
body {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0;
  padding: 0;
}

#header {
  margin-top: 50px;
}

#logo {
  width: 300px;
  height: 150px;
}

#content {
  margin-top: 50px;
  text-align: center;
}

form {
  margin-top: 20px;
}

#search-box {
  padding: 10px;
}

#search-button {
  margin-top: 10px;
  padding: 10px;
}

h4 {
  margin-top: 50px;
}

a {
  margin-top: 10px;
  display: block;
}
</style>
</head>
<body>
    <!-- google resmi -->
<div id="header">
    <img src="goggle.png" width="300" height="150" alt="Google" id="logo">
</div>
<!-- arama çubuğu ve ara butonu -->
<div id="content">
    <label for="search">Search the web using Google!</label>
    <form action="https://www.google.com/search" method="get">
    <input type="text" name="q" id="search-box" placeholder="Ara...">
    <input type="submit" value="Ara" id="search-button">
    <br>
    <!-- google search ve ım feeling lucky butonu -->
    <button type="submit">Google Search</button>
    <button type="submit">I'm feeling lucky</button>
    </form>
</div>
<!-- arama çubuğunun altı -->
<h4> Special Searches</h4>
<a href="https://web.archive.org/web/19990224014327/http://www.google.com/stanford" id="Stnd">
    Stanford Search
</a>
<a href="https://web.archive.org/web/19990221231654/http://www.google.com/linux">
    Linux Search
</a>
<a href="https://web.archive.org/web/19990221212930if_/http://www.google.com/help.html">
    Help!
</a>
<a href="https://web.archive.org/web/19990427105230if_/http://www.google.com/about.html">
    About Google!
</a>
<a href="https://web.archive.org/web/19990221202430if_/http://www.google.com/company.html">
    Company
</a>
<a href="https://web.archive.org/web/19990224043535if_/http://www.google.com/stickers.html">
    Google Logos
    <br>
</a>
<label for="email">Get Google! <br> updates monthly:</label>
<br>
<input type="email" name="email" value="your e-mail">
<button type="submit">Subscribe</button>
    <a href="">Archieve</a>
<p>Copyright ©1998 Google Inc.</p>
</body>
</html>
