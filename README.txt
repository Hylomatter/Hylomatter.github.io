Landing page for Hylomatter.

Need to add dynamics for contact form:
	The signup form won't actually do anything (other than report back with a "thank you" message)
	until you tie it to either a third party service (eg. MailChimp) or your own hosted solution.
	In either case, there are two ways to go:

	1. The conventional (non-AJAX) way, which pretty much comes down to pointing the form's "action"
	attribute to your service/script URL. If you go this route, remove the entire "Signup Form" code
	block from assets/js/main.js (since it's not needed for this approach).

	-or-

	2. The AJAX way. How you set this up is largely dependent on the service/solution you're using
	so you'll need to consult their/its documentation. However, I have included some basic code
	(under "Signup Form" in assets/js/main.js) that will at least let you interact with the
	form itself.
