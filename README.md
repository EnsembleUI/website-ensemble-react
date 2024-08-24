# website-ensemble-react

Download latest ensemble react starter build at https://storage.googleapis.com/ensemble-react-starter/ensemble-starter-latest.zip  
Make the following modifications:  
1. Delete the `favicon.ico` file. (Not subject to change with Ensemble React updates, continue using custom version already in `main`)
2. Delete the `ensemble-config.json` file. (Not subject to change with Ensemble React updates, continue using custom version already in `main`)
3. Change the `<title>` tag content in `index.html` from "React App" to "Ensemble".
4. Find the `<link>` tag that reads `<link rel="apple-touch-icon" href="/logo192.png"/>`, and replace `/logo192.png` with `/favicon.ico`.
5. Add the following between `<head>` and `<body>` in `index.html` for Google Analytics integration.
```
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-V7DEWZG0S4"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag() {
    dataLayer.push(arguments);
  }
  gtag("js", new Date());

  gtag("config", "G-V7DEWZG0S4");
</script>
```
Upload this modified build folder to the `update-build` branch and merge into `main` to update.
