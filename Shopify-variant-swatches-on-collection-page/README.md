# Shopify-variant-swatches-on-collection-page

  //On product-grid.liquid add this code
  
    <div class="product_listing_options">
     {% if product.variants.size > 1 %}
       {% if settings.product_info == 'colors' and product.available %}
         {% include 'show-colors' %}
         {% include 'show-sizes' %}
       {% elsif settings.product_info == 'sizes' and product.available %}
         {% include 'show-sizes' %}
       {% endif %}
     {% endif %}
    </div>
