<html> <body>
	
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWs000007IsfR',
				'MIAW2',
				'https://storm-403667cf952fd5.my.site.com/ESWMIAW21735728923526',
				{
					scrt2URL: 'https://storm-403667cf952fd5.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://storm-403667cf952fd5.my.site.com/ESWMIAW21735728923526/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body> </html> 
