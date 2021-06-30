<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Laravel-aplikasi-todo-sqlite
Projek Laravel aplikasi To-Do dengan menggunakan sistem Login Laravel Jetstream Livewire.

Program ini dibuat untuk mengorganisir To-Do dalam Kegiatan sehari-hari.

Database menggunakan sqlite.

Saya Development program ini menggunakan Laragon.

### Cara Clone Projek
Gunakan Terminal CMD / cmder / gitbash / powershell.
#### Clone Projek
<pre><code>git clone https://github.com/IrvanMaulana99/laravel-aplikasi-todo-sqlite.git
</code></pre>
#### Masuk folder projek
<pre><code>cd laravel-aplikasi-todo-sqlite
</code></pre>
#### Install Composer
<pre><code>composer install
</code></pre>
#### Duplikat file .env
<pre><code>cp .env.example .env
</code></pre>
#### Database
Aktifkan dulu Driver dan extension Sqlite di pengaturan php.ini jika belum aktif.

Buat file dengan nama " database.sqlite " di folder Database
#### Migrasi Database
<pre><code>php artisan migrate
</code></pre>
#### Generate Key
<pre><code>php artisan key:generate
</code></pre>
#### Jalankan Program
<pre><code>php artisan serve
</code></pre>
### Buka Program
Ketik http://localhost:8000/ di Url Browser

### Lisensi
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
