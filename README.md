/*** Thêm đoạn code bên dưới vào theme.liquid ***/
<!-- Global site tag (gtag.js) - Google Ads: 787609991 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-787609991"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-123456789');
</script>

<script>
  
{% if template contains 'product' %}
gtag('event', 'view_item', {
      'value': {{ product.price }},
      'items' : [{
        'id': '{{ product.id }}',
        'google_business_vertical': 'retail'
      }]
    });
{% endif %}	
{% if template contains 'cart' %}
			gtag('event', 'add_to_cart', {
				'value': {{ cart.total_price}},
				'items' :[
          {% if cart.item_count == 1%}
            {%for item in cart.items%}{'id':'{{item.product.id}}','google_business_vertical':'retail'}{%endfor%}
          ]
          {% else %}
           {%for item in cart.items%}{'id':'{{item.product.id}}','google_business_vertical':'retail'}{%if forloop.last%}{%else%},{%endif%}{%endfor%}]{% endif %}
			});																																														
{% endif %}
</script>

/*** Thêm đoạn code bên dưới vào trang check out ***/
<!-- Global site tag (gtag.js) - Google Ads: 787609991 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-787609991"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-123456789');
</script>
<script>
gtag('event', 'purchase', {
	'value': {{total_price}},
	'items' : [
				{% if line_items.size == 1%}
					{%for item in line_items%}{'id':'{{item.product.id}}','google_business_vertical':'retail'}{%endfor%}
				]
				{% else %}
				 {%for item in line_items%}{'id':'{{item.product.id}}','google_business_vertical':'retail'}{%if forloop.last%}{%else%},{%endif%}{%endfor%} ]{% endif %}
				
});
</script>
