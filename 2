<!-- Google Ads Remarketing Tag By FeedArmy Version 2.11 START -->
<!-- FeedArmy tutorial found at https://feedarmy.com/kb/adding-google-adwords-remarketing-tag-to-shopify/ -->

<!-- CODE SETTINGS START -->
<!-- CODE SETTINGS START -->

<!-- Please add your Google Ads Audience Source Tag ID -->
{% assign fa_google_ads_audience_tag_id = 705001359 %}

<!-- Please add your alpha2 code, you can find it here: https://help.shopify.com/en/api/custom-storefronts/storefront-api/reference/enum/countrycode -->
{% assign fa_product_id_alpha2_code = 'US' %}

<!-- if you have prices such as 1,000.00 set below to true, if you have prices such as 1.000,00 set below to false -->
{% assign fa_prices_with_decimal_separator = true %}

<!-- set your product id values are default, product_id, parent_id, sku-->
{% assign fa_product_id = 'default' %}

<!-- CODE SETTINGS END -->
<!-- CODE SETTINGS END -->

<!-- ------------------------------------ -->
<!-- DO NOT EDIT ANYTHING BELOW THIS LINE -->
<!-- Global site tag (gtag.js) - Ads. -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-{{ fa_google_ads_audience_tag_id }}"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'AW-{{ fa_google_ads_audience_tag_id }}');
</script>
<!-- Global site tag (gtag.js) - Ads. -->
{% if fa_prices_with_decimal_separator == true %}
	{% if template contains 'product' %}
		{% assign fa_product_price = product.price_min | money_without_currency | remove:',' %}
	{% elsif template contains 'cart' %}
		{% assign fa_product_price = cart.total_price | money_without_currency | remove:',' %}
	{% endif %}
{% else %}
	{% if template contains 'product' %}
		{% assign fa_product_price = product.price_min | money_without_currency | remove:'.' | replace: ',', '.' %}
	{% elsif template contains 'cart' %}
		{% assign fa_product_price = cart.total_price | money_without_currency | remove:'.' | replace: ',', '.' %}
	{% endif %}
{% endif %}
{% if template contains 'collection' %}
{% assign fa_event = 'view_item_list' %}
{% elsif template contains 'product' %}
{% assign fa_event = 'view_item' %}
{% elsif template contains 'search' %}
{% assign fa_event = 'view_search_results' %}
{% elsif template contains 'cart' %}
{% assign fa_event = 'add_to_cart' %}
{% elsif template contains 'index' %}
{% assign fa_event = 'home' %}
{% else %}
{% assign fa_event = 'other' %}
{% endif %}

<script>
  gtag('event', '{{ fa_event }}', {
    'send_to': 'AW-{{ fa_google_ads_audience_tag_id }}',
	{% if template contains 'product' or template contains 'cart' %}'value': {{ fa_product_price }},{% endif %}
	{% if template contains 'product' %}
    'items': [{
		{% if fa_product_id == 'default' %}
			'id': 'shopify_{{ fa_product_id_alpha2_code }}_{{ product.id }}_{% if product.variants.first.id %}{{ product.variants.first.id }}{% else %}{{ product.variants.id }}{% endif %}',
		{% elsif fa_product_id == 'product_id' %}
			'id': '{% if product.variants.first.id %}{{ product.variants.first.id }}{% else %}{{ product.variants.id }}{% endif %}',
		{% elsif fa_product_id == 'parent_id' %}
			'id': '{{ product.id }}',
		{% elsif fa_product_id == 'sku' %}
			'id': '{% if product.variants.first.id %}{{ product.variants.first.sku }}'{% else %}{{ product.variants.sku }}'{% endif %}',
		{% endif %}
      'google_business_vertical': 'retail'
    }]
	{% elsif template contains 'cart' %}
	'items': [
	{% for item in cart.items %}
	{
		{% if fa_product_id == 'default' %}
			'id': 'shopify_{{ fa_product_id_alpha2_code }}_{{ item.product_id }}_{{ item.variant_id }}',
		{% elsif fa_product_id == 'product_id' %}
			'id': '{{ item.variant_id }}',
		{% elsif fa_product_id == 'parent_id' %}
			'id': '{{ item.product_id }}',
		{% elsif fa_product_id == 'sku' %}
			'id': '{{ item.sku }}',
		{% endif %}
      'google_business_vertical': 'retail'
    },
	{% endfor %}
	]
	{% endif %}
  });
</script>
<!-- Google Ads Remarketing Tag By FeedArmy Version 2.11 END -->

// --------------------------------Purchased------------------------------------------

<!-- Google Ads Remarketing Tag By FeedArmy Version 2.11 START -->
<!-- FeedArmy tutorial found at https://feedarmy.com/kb/adding-google-adwords-remarketing-tag-to-shopify/ -->

<!-- CODE SETTINGS START -->
<!-- CODE SETTINGS START -->

<!-- Please add your Google Ads Audience Source Tag ID -->
{% assign fa_google_ads_audience_tag_id = 705001359 %}

<!-- Please add your alpha2 code, you can find it here: https://help.shopify.com/en/api/custom-storefronts/storefront-api/reference/enum/countrycode -->
{% assign fa_product_id_alpha2_code = 'US' %}

<!-- if you have prices such as 1,000.00 set below to true, if you have prices such as 1.000,00 set below to false -->
{% assign fa_prices_with_decimal_separator = true %}

<!-- set your product id values are default, product_id, parent_id, sku-->
{% assign fa_product_id = 'default' %}

<!-- CODE SETTINGS END -->
<!-- CODE SETTINGS END -->

<!-- ------------------------------------ -->
<!-- DO NOT EDIT ANYTHING BELOW THIS LINE -->
<!-- Global site tag (gtag.js) - Ads. -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-{{ fa_google_ads_audience_tag_id }}"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'AW-{{ fa_google_ads_audience_tag_id }}');
</script>
<!-- Global site tag (gtag.js) - Ads. -->
{% if fa_prices_with_decimal_separator == true %}
		{% assign fa_product_price = checkout.total_price | money_without_currency | remove:',' %}
{% else %}
		{% assign fa_product_price = checkout.total_price | money_without_currency | remove:'.' | replace: ',', '.' %}
{% endif %}


{% assign fa_event = 'purchase' %}

<script>
  gtag('event', '{{ fa_event }}', {
    'send_to': 'AW-{{ fa_google_ads_audience_tag_id }}',
	  'value': {{ fa_product_price }},
	  'items': [
	{% for item in checkout.line_items %}
	{
		{% if fa_product_id == 'default' %}
			'id': 'shopify_{{ fa_product_id_alpha2_code }}_{{ item.product_id }}_{{ item.variant_id }}',
		{% elsif fa_product_id == 'product_id' %}
			'id': '{{ item.variant_id }}',
		{% elsif fa_product_id == 'parent_id' %}
			'id': '{{ item.parent_id }}',
		{% elsif fa_product_id == 'sku' %}
			'id': '{{ item.sku }}',
		{% endif %}
      'google_business_vertical': 'retail'
    },
	{% endfor %}
	]

  });
</script>
<!-- Google Ads Remarketing Tag By FeedArmy Version 2.11 END -->
