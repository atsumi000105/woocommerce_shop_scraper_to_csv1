# woocommerce_shop_scraper_to_csv
Using SCrapy Python.

Scrapy (/ˈskreɪpaɪ/) is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing or historical archival.

<h3>Installation instructions</h3>
<p>1. Install scrapy</p>
<em>Scrapy requires Python 3.7+, either the CPython implementation (default) or the PyPy implementation (see Alternate Implementations).</em>
<code>pip install Scrapy</code>
<p>2. Clone the repo </p>
<p>3. Insert the woocommerce shop urls in spiders > products_spider.py , You can use 1 or more shop urls</p>
<code>start_urls = [
        'https://www.woostore1.com/shop/',
        'https://www.woostore2.co.ke/shop/page/1',
        'https://woostore3.com/shop/page/1',
    ]
</code>
<p>cd into the projects directory and run the command</p>
<code>scrapy crawl productsSpider</code>

<p>The crawl will start and a new csv file will be generated on the projects root directory with the products populated</p>