The WooCommerce Shop Scraper to CSV tool is a powerful python tool designed to simplify the process of extracting product data from a WooCommerce-powered online shop and generating a comprehensive CSV file. Built on the foundations of WordPress and WooCommerce, this project leverages advanced web scraping techniques to automate the extraction and organization of essential product information.

By utilizing this scraper, you can effortlessly gather a wealth of data from any WooCommerce-based online shop, including product names, descriptions, prices, images, categories, stock availability, and more. Whether you're an e-commerce enthusiast, a business analyst, or a developer seeking efficient data extraction, this project provides an intuitive and efficient solution.

 # woocommerce_shop_scraper_to_csv
Using Scrapy Python.

Scrapy (/ˈskreɪpaɪ/) is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing or historical archival.

<h3>Installation instructions</h3>
<p>1. Install scrapy</p>
<em>Scrapy requires Python 3.7+, either the CPython implementation (default) or the PyPy implementation (see Alternate Implementations).</em>
<p><code>pip install Scrapy</code></p>
<p>2. Clone the repo </p>
<p>3. Insert the woocommerce shop urls in spiders > products_spider.py , You can use 1 or more shop urls</p>
<p><code>start_urls = [
        'https://www.woostore1.com/shop/',
        'https://www.woostore2.co.ke/shop/page/1',
        'https://woostore3.com/shop/page/1',
    ]
</code></p>
<p>cd into the projects directory and run the command</p>
<p><code>scrapy crawl productsSpider</code></p>

<p>The crawl will start and a new csv file will be generated on the projects root directory with the products populated</p>
