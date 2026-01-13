# Whatsapp-Business-Validator-api-for-bulk
Api to real-time validate number on whatsapp is registered for business or not , Verified or not, business name , image link. Only need to provide number with country code.
Get key from here : https://rapidapi.com/vijay399/api/whatsapp-business-validator-data
<h3>Api Usage</h3>
<pre>
  <code>
    curl --request GET \
	--url 'https://whatsapp-business-validator-data.p.rapidapi.com/api.php?number=50522231770' \
	--header 'x-rapidapi-host: whatsapp-business-validator-data.p.rapidapi.com' \
	--header 'x-rapidapi-key: Rapidapi_key_here'
  </code>
</pre>
<h3>Api response</h3>
<pre>
  <code>
   {
  "business": true,
  "business_name": "McDonald's Nicaragua",
  "verified": true,
  "image": "https://pps.whatsapp.net/v/t61.24694-24/185608718_970652596841549_526702467214644446_n.jpg?ccb=11-4&oh=01_Q5Aa3gGwwjXusfZGA5piY-tlsuVaMhw2Y0q8xQTjUoUyMbmKfw&oe=69626571&_nc_sid=5e03e0&_nc_cat=103"
}
  </code>
</pre>
