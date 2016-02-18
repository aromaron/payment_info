Payment Info (Formerly Toscany)
===========

This is a jQuery-based, progressively-enhanced solution for creating a [single-field credit card input](http://www.lukew.com/ff/entry.asp?1667). The idea is to create a more streamlined credit card entry process.

The solution is based on the work by @zdfs.

=======

###Instructions
- Add the _**payment_info.js**_ file to your scripts folder.
- Add the _**payment_info.css**_ file to your stylesheets folder

###Requirements
Add this files in your project, you can download them from the following links or you can find them under the libs folder.

- [Modernizr.js](http://modernizr.com/)
- [jQuery.js](https://jquery.com)
- [jQuery Mask](https://igorescobar.github.io/jQuery-Mask-Plugin/)
- [Normalize.css](https://necolas.github.io/normalize.css/)

###Usage
Your credit card form should look like this:

    <form>
      <fieldset class="credit-card-group">
        <legend>Credit Card Information</legend>
        <label for="card-number">Credit Card Number</label>
        <input placeholder="1234 5678 9012 3456" pattern="[0-9]*" type="text" class="card-number" id="card-number">
        <label for="card-number">Expiration Date</label>
        <input placeholder="MM/YY" pattern="[0-9]*" type="text" class="card-expiration" id="card-expiration">
        <label for="card-number">CVV Number</label>
        <input placeholder="CVV" pattern="[0-9]*" type="text" class="card-cvv" id="card-cvv">
        <label for="card-number">Billing Zip Code</label>
        <input placeholder="ZIP" pattern="[0-9]*" type="text" class="card-zip" id="card-zip">
      </fieldset>
    </form>

###Using with Rails Applications
If you are planning to use the payment info plugin with your Rails application I suggest to use the [Payment Info Rails Gem](http://aromaron.github.io/payment_info_rails/).

###Demo
You can find a working demo [here](http://aromaron.github.io/payment_info_rails/).

