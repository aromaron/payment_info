Single-Field Credit Card Input
=======

This is a jQuery-based, progressively-enhanced solution for creating a [single-field credit card input](http://www.lukew.com/ff/entry.asp?1667). The idea is to create a more streamlined credit card entry process.


=======
###Instructions
(TODO)

###Requirements
(TODO)

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

###Demo
You can find a working demo [here](http://aromaron.github.io/payment_info_rails/).
