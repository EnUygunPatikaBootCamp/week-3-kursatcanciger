# Week 3 Assignment for Enuygun PHP Bootcamp

# Araştırma Konusu

- Symfony kullanmanın avantajları nedir?
  - Framework ile gelen araçlar ile proje daha hızlı geliştirilir.
  - Framework ile çalışırken belirli bir yapı kullanıldığı için proje takibi ve farklı kişilerin çalışması kolaylaşır.
  - Bilinen güvenlik açıkları için önlemler alınmış, sürekli olarak güncelleme almaktadır.

- Symfony ile environment (ortam) ayarlaması nasıl yapılır?
  - Symfony varsayılan olarak dev ve prod ortamlarını barındırır. Dev ortamı geliştirme, prod ortamı uygulamanın çalıştırıldığı ortamdır.

- Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?
  - "composer create-project symfony/skeleton:"^5.4" my_project_directory" ile composer kullanarak proje oluşturabilir.
  - "symfony new my_project_directory --version=5.4 --webapp" ile altefnatif olarak symfon cli kullanılabilir.

- Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.
  - Laravel Blade şablon sistmei kullanırken Symfony Twig kullanır.
  - Laravel veritabanı için Eloquent kullanırken Symfony Doctrine kullanır.