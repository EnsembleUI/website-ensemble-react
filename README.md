# website-ensemble-react

Download latest ensemble react starter build at https://storage.googleapis.com/ensemble-react-starter/ensemble-starter-latest.zip\n
Make the following modifications:\n
1. Delete the `favicon.ico` file. (Not subject to change with Ensemble React updates, continue using custom version already in `main`)
2. Delete the `ensemble-config.json` file. (Not subject to change with Ensemble React updates, continue using custom version already in `main`)
3. Change the `<title>` tag content in `index.html` from "React App" to "Ensemble".
4. Add the following between `<head>` and `<body>` in `index.html` for Google Analytics integration.\n
`
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
`
