<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
</head>
  <body>
Test
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKB000000HvBX',
				'Github',
				'https://dkb000000hvbx2a0-dev-ed.develop.my.site.com/ESWGithub1729878726765',
				{
					scrt2URL: 'https://dkb000000hvbx2a0-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://dkb000000hvbx2a0-dev-ed.develop.my.site.com/ESWGithub1729878726765/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
