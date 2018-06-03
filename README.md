# Laravel E-commerce Rest API

## Requirements

1. PHP version 7 or latest
2. Composer


## Instructions
<ul>
<li>After cloning this repository, go to the root folder, run the following command's:
<pre>
    composer install
</pre>
</li>

<li>Rename .env.example to .env and provide your database details there.</li>

<li>It needs a database table to perform CRUD operations on it. To import the table, run:
<pre>php artisan migrate</pre>

<li>Seeding database:
<pre>php artisan db:seed</pre>
</li>

<li>Generating a New Application Key
<pre>php artisan key:generate</pre>

</li>
<li>Run 
<pre>php artisan serve</pre> </li>
</ul>