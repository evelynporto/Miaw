<html>
	<body>
		<script type='text/javascript'>
			function initEmbeddedMessaging() {
				try {
					embeddedservice_bootstrap.settings.language = 'pt_BR';

					embeddedservice_bootstrap.init(
						'00D7d000008qeja',
						'CRC_Teste',
						'https://grupoboticario--devcrcmiaw.sandbox.my.site.com/ESWCRCTeste1685471244480',
						{
							scrt2URL: 'https://grupoboticario--devcrcmiaw.sandbox.my.salesforce-scrt.com'
						}
					);
				} catch (err) {
					console.error('Error loading Embedded Messaging: ', err);
				}
			};
		</script>
		<script type='text/javascript' src='https://grupoboticario--devcrcmiaw.sandbox.my.site.com/ESWCRCTeste1685471244480/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
	</body>
</html>
