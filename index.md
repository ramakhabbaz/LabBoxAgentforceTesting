<html>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dbm000016EQoK',
				'Chat_Support_Channel',
				'https://orgfarm-2a650eb134.my.site.com/ESWChatSupportC1794337952760',
				{
					scrt2URL: 'https://orgfarm-2a650eb134.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-2a650eb134.my.site.com/ESWChatSupportC1794337952760/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</html>
