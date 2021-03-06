<!DOCTYPE html>
<html lang="en">
  <head>
    <title>PWA - getInstalledRelatedApps</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  
    <meta name="theme-color" content="#3f51b5">
    <link rel="manifest" href="/manifest.json">
    <!-- OT Expires 2020-01-14 -->
    <link http-equiv="origin-trial" content="At3uhlLvIiUq7b2cW267B1XKvHohHGuxeCqF3FJB/0RaR6BUUC5iOWgfYjkaBwzInT33eAdoSEHpONIpM8h4BQAAAABieyJvcmlnaW4iOiJodHRwczovL2dldC1pbnN0YWxsZWQtYXBwcy5nbGl0Y2gubWU6NDQzIiwiZmVhdHVyZSI6Ikluc3RhbGxlZEFwcCIsImV4cGlyeSI6MTU3OTAyOTYxNn0=">
  </head>  
  <body>
    <h1>
      getInstalledRelatedApps
    </h1>
    
    <p id="about">
      The <a href="https://developers.google.com/web/updates/2018/12/get-installed-related-apps">
      <code>getInstalledRelatedApps</code></a> API is a new web platform API 
      that allows your web app to check to see if your native app is installed
      on the users device, and vice versa. 
    </p>
    <div class="instructions">
      <span class="instructionsCount">1</span>
      <span>
        Install <a href="https://play.google.com/store/apps/details?id=ca.bigbackpack.getinstalledrelatedapps">this app</a>
      </span>
    </div>
    <div class="instructions">
      <span class="instructionsCount">2</span>
      <span>
        Come back to this page
      </span>
    </div>
    <p>
      This demo checks to see if a specific 
      <a href="https://play.google.com/store/apps/details?id=ca.bigbackpack.getinstalledrelatedapps">demo app</a> is installed
      from the Google Play Store. Only when it is installed will you see it
      listed below. Try installing it to see how <code>getInstalledRelatedApps</code>
      works when the expected app is installed.
    </p>
    
    <p>
      Check out the <a href="https://glitch.com/edit/#!/get-installed-apps">source</a>
      for this sample, or
      <a href="https://glitch.com/edit/#!/remix/get-installed-apps">remix it</a>
      on Glitch.
    </p>

    <p id="requireHTTPS" class="hidden">
      <b>STOP!</b> This page <b>must</b> be served over HTTPS.
      Please <a>reload this page via HTTPS</a>.
    </p>

    <p id="notSupported">
      <b>Sorry!</b> This browser doesn't support the <code>getInstalledRelatedApps</code>.
      The API is only available as an origin trial in Chrome 73+ on Android.
    </p>
    
    <div>
      <b>Installed Apps:</b> <span id="status"></span>
      <ul id="installedApps">
      </ul>
    </div>
      
    <script src="/common.js"></script>
    <script src="/demo.js"></script>

  </body>
</html>
