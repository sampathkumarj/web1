<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DdL000006jKJ1',
				'Embedded_chat',
				'https://kasadara60-dev-ed.develop.my.site.com/ESWEmbeddedchat1720506576125',
				{
					scrt2URL: 'https://kasadara60-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://kasadara60-dev-ed.develop.my.site.com/ESWEmbeddedchat1720506576125/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
