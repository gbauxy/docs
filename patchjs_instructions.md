# Patch.js

Patch.js makes it easy for you to check a patient's benefits, eligibility, and file claims without having any protected health information (PHI) touch your website. Patch.js enables these features with a few lines of code and doesn't require directly integrating our API into your website. If you need help after reading this, feel free to reach out with your questions to developer@getpatch.com and we'll respond as fast as we can. 


Patch.js is Patch's foundational JavaScript library for securely sending sensitive information to Patch directly from the customer's browser. Patch.js can be used for:

- Collecting PHI
- Checking a patient's benefits and eligibility
- Filing a vision reimbursement claim

Patch.js also has built-in validators to check whether a patient's member ID or other information is correct and they exist in the insurer's systems. 

### Including Patch.js

However you're using Patch.js, you always begin by including the library and setting your API key. Add this script tag to your HTML page to get started with Patch.js:

```html
<script type="text/javascript" src="https://js.getpatch.com/v1.6/"></script>
```

Note: Patch.js should be loaded directly from `https://js.getpatch.com/v1.6/`.

### Setting your publishable key

Your publishable API key identifies your website to Patch during communications. Set your publishable key with setPublishableKey, after including Patch.js and before making any requests to Patch.

```javascript
Patch.setPublishableKey('pk_test_2bYg0i0xayUuxAZ8a2I0kCXH'); 
```

We've pre-filled the example with your test API key. Only you can see this value.

### Setting your API key

Patch provides a test key and a live API key for production uses. These keys authenticate you and should NEVER be shared publicly or stored in code. Your test key and live production key should be set in the environment variables of your website. If you need help doing this, please contact us directly. 

You will need to replace the test key with your live key for production uses. 


### Questions?

We're always happy to help with code or other questions you might have! Feel free to send an email to developer@getpatch.com!